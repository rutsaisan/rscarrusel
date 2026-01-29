# rscarrusel
📸 RS Carrusel de Imágenes

Un carrusel de imágenes sencillo y ligero hecho con HTML, CSS y JavaScript puro, sin dependencias externas.
Permite navegar entre imágenes mediante botones de avance y retroceso con animación suave.

🚀 Características

Sin librerías externas

Fácil de integrar en cualquier proyecto

Navegación con botones ◀ ▶

Animación fluida con CSS

Código simple y educativo

🧩 Estructura del proyecto
/
├── index.html
├── rscarrusel.css
├── rscarrusel.js
├── dalmata1.jpg
├── dalmata2.jpg
├── ...
└── dalmata8.jpg

🛠️ Uso
1️⃣ HTML

Solo necesitas un contenedor con la clase rscarrusel y las imágenes dentro:

<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
  </head>
  <body>

    <div class="rscarrusel">
      <img src="dalmata1.jpg" alt="Imagen 1">
      <img src="dalmata2.jpg" alt="Imagen 2">
      <img src="dalmata3.jpg" alt="Imagen 3">
      <img src="dalmata4.jpg" alt="Imagen 4">
      <img src="dalmata5.jpg" alt="Imagen 5">
      <img src="dalmata6.jpg" alt="Imagen 6">
      <img src="dalmata7.jpg" alt="Imagen 7">
      <img src="dalmata8.jpg" alt="Imagen 8">
    </div>

    <link rel="stylesheet" href="https://rutsaisan.github.io/rscarrusel/rscarrusel.css">
    <script src="https://rutsaisan.github.io/rscarrusel/rscarrusel.js"></script>

  </body>
</html>

2️⃣ CSS (rscarrusel.css)

Define el tamaño del carrusel, la disposición horizontal y el estilo de los botones.

Tamaño del carrusel: 1280x820

Imágenes alineadas en fila

Botones posicionados en el centro lateral

⚠️ Si cambias el ancho del carrusel, recuerda actualizarlo también en el JavaScript.

3️⃣ JavaScript (rscarrusel.js)

El script:

Reorganiza las imágenes dentro de un <section>

Crea dinámicamente los botones

Controla el desplazamiento horizontal

Gestiona el índice actual del carrusel

⚙️ Configuración

Puedes modificar estas variables en el JS:

var anchura = 1280; // ancho de cada imagen
var contador = 0;  // posición inicial


Si usas más o menos imágenes, ajusta el límite del contador:

if(contador < -7){contador = 0;}


(7 = número de imágenes - 1)

🎯 Ejemplo de uso

Ideal para:

Galerías de fotos

Portfolios

Proyectos educativos

Prácticas de JavaScript y DOM
