Aprendre HTML
=============
# Todo Todo TODO
* `~/Documents/CCTW`
* [Como crear tu web](http://www.comocreartuweb.com/)

Conceptes
=========
* [Molon](http://jsbin.com/?html=%3C!DOCTYPE%20html%3E%0A%3Chtml%3E%0A%3Chead%3E%0A%20%20%3Cmeta%20charset%3D%22utf-8%22%3E%0A%20%20%3Cmeta%20name%3D%22viewport%22%20content%3D%22width%3Ddevice-width%22%3E%0A%20%20%3Ctitle%3EMathJax%20example%3C%2Ftitle%3E%0A%20%20%3Cscript%20type%3D%22text%2Fjavascript%22%20async%0A%20%20src%3D%22https%3A%2F%2Fcdnjs.cloudflare.com%2Fajax%2Flibs%2Fmathjax%2F2.7.5%2Flatest.js%3Fconfig%3DTeX-MML-AM_CHTML%22%20async%3E%0A%3C%2Fscript%3E%0A%3C%2Fhead%3E%0A%3Cbody%3E%0A%3Cp%3E%0A%20%20When%20%5C(a%20%5Cne%200%5C)%2C%20there%20are%20two%20solutions%20to%20%5C(ax%5E2%20%2B%20bx%20%2B%20c%20%3D%200%5C)%20and%20they%20are%0A%20%20%24%24x%20%3D%20%7B-b%20%5Cpm%20%5Csqrt%7Bb%5E2-4ac%7D%20%5Cover%202a%7D.%24%24%0A%3C%2Fp%3E%0A%3C%2Fbody%3E%0A%3C%2Fhtml%3E&live)
* [w3](https://www.w3.org)
  * [Markup Validation Service "Compilat"](https://validator.w3.org/#validate_by_input)

HTML
----
`<!DOCTYPE html>`
[`<html lang="es">`](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
`<!-- Comentaris -->`
* Head
  * `<meta charset="utf-8" />`
  * Title
  * `<meta name="Description" content="descripción de la página">`
  * `<meta name="keywords" content="palabrauno, palabra2, par de palabras, palabra4......., palabra10" />`
* Body
  * Divs (html 5 té etiquetes millors)
    * html5
      * `<header></header>   `
      * `<hgroup></hgroup>   `
      * `<nav></nav>         `
      * `<article></article> `
      * `<section></section> `
      * `<aside></aside>     `
      * `<figure></figure>   `
      * `<footer></footer>   `
      * `<address></address> `
      * `<section>` Capítols? Tots dins d'un titul?
        * `<article>` Sub apartats del section
    * id 1 vegada
    * class +1
  * Span
  * h1-6 Tituls
  * p Text
    * b __Bold__ Negreta
    * i _italic_ Italia
    * u ~underline~
    * br
  * ul li llistes desordenades
  * ol li llistes ordenades
  * table tr td
    * `colspan="3"`
    * `rowspan="3"`
  * a link
    * `<a href="http://www.comocreartuweb.com" target="_blank" title="Crear páginas web">Crear Paginas Web</a>`
    * target
      * top
      * parent
      * self
      * blank Nova pàgina (tabulació <C-N>)
    * Anclaje (link PDFs)
      * `<a name="arriba">`
      * `<a href="#arriba" title="Ir Arriba">Ir arriba</a>`
    * rel
      * archives Desactualitzat
      * author Suposo que important
      * prev, start, next Like read commic
      * first, last, up Repe, més info
      * prefetch, Estic força segur que l'usuari ho mirarà (more fast)
      * etc...
  * [img](http://www.comocreartuweb.com/curso-de-html/curso-html-introducion/las-imagenes.html) `<figure>, <figcaption> y/o <aside>`
    * src
    * width
    * height
    * alt
  * from `<form method="post" action="mostrardatosenpagina.php">`
    * Generar fromularis (usuari interactui)

\\( ax^2 + \sqrt{bx} + c = 0 \\)

CSS
---
