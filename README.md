# Luz y Amor, Cafetería

Sitio estático de Luz y Amor, una cafetería costarricense. Una sola página en HTML, CSS y
JavaScript sin dependencias ni paso de build: se edita directo y se publica tal cual.

## Estructura
```
index.html               toda la página: markup, estilos y comportamiento
favicon.svg / .ico       íconos del sitio
apple-touch-icon.png
android-chrome-*.png
images/                  fotografías
.nojekyll                evita que GitHub Pages procese la carpeta con Jekyll
```

## Editar el menú
Los productos viven en `index.html`, dentro de las constantes `menu` y `secretMenu`
(etiqueta `<script>` al final). Cada producto es `{name, desc, price}`.

## Publicar con GitHub Pages
1. Sube estos archivos al repositorio, reemplazando lo anterior.
2. Settings > Pages > Source: rama `main`, carpeta `/(root)`.
3. El sitio queda en `https://<usuario>.github.io/<repositorio>/`.
