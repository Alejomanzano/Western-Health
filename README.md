# Western Health - Resource detail (HTML + Sass + BEM, sin JavaScript)

Estructura
  index.html          -> pagina completa
  css/main.css        -> CSS ya compilado (listo para abrir index.html)
  scss/               -> codigo fuente Sass
    abstracts/        -> variables y mixins
    base/             -> reset y tipografia
    layout/           -> container, header, footer, article
    components/       -> un parcial por componente (BEM)
  img/                -> logo.png y family.jpg

Recompilar Sass despues de editar:
  npx sass scss/main.scss css/main.css
  npx sass --watch scss/main.scss css/main.css
