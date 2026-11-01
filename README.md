# Artlumi Books

Catálogo estático em português dos livros de colorir infantis da Artlumi Books. Funciona sem build, servidor de aplicação ou bibliotecas JavaScript.

## Conteúdo

Edite index.html para atualizar textos, capas e links dos livros. Os estilos estão em assets/style.css; assets/site.js controla apenas o menu móvel.
Para atualizar “Livros da semana” e “Próximos livros”, edite os cartões em index.html e as páginas em livros/; quando sair o ASIN, troque o link de busca da Amazon na chamada final da página do livro pelo link direto do produto.

## Publicação

No repositório do GitHub, abra **Settings → Pages** e selecione **Deploy from a branch**, branch **main**, pasta **/ (root)**. O arquivo CNAME configura book.artlumi.com.br; o DNS do domínio também precisa apontar para o GitHub Pages. Para conferir localmente, rode python3 -m http.server na raiz.

Ao alterar `assets/style.css` ou `assets/site.js`, troque o `?v=` nas referências em todos os HTML (index.html, 404.html e livros/), para os navegadores não usarem o arquivo antigo em cache.
