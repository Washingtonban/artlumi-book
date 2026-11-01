# Artlumi Books

Catálogo estático em português dos livros de colorir infantis da Artlumi Books. Funciona sem build, servidor de aplicação ou bibliotecas JavaScript.

## Conteúdo

Edite index.html para atualizar textos, capas e links dos livros. Os estilos estão em assets/style.css; assets/site.js controla apenas o menu móvel.

## Publicação

No repositório do GitHub, abra **Settings → Pages** e selecione **Deploy from a branch**, branch **main**, pasta **/ (root)**. O arquivo CNAME configura book.artlumi.com.br; o DNS do domínio também precisa apontar para o GitHub Pages. Para conferir localmente, rode python3 -m http.server na raiz.
