## π Entorno de desarrollo

### π©π½βπ Herramientas necesarias

1. [Instalar Node.js y npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
2. Clona este proyecto: `git clone git@github.com:uly081219/css-html-2-pec3.git`
3. Acceder a la carpeta del proyecto: `cd css-html-2-pec3`

### π₯ EjecuciΓ³n de la aplicaciΓ³n

1. Instalar todas las dependecias: `npm install`
2. Construir el sitio web: `npm run build`
3. Inicar el servidor de dessarrollo: `npm run dev`

Puedes acceder al servidor mediante la url: http://localhost:8123

### π©π½βπ« ExplicaciΓ³n del proyecto

Este proyecto pretende ser un sitio web de un Festival de Jazz celebrado en la Costa Brava.

### π Estructura del proyecto

`tree -L 4 assets  src`

```
src
βββ assets
βΒ Β  βββ fonts
βΒ Β  βΒ Β  βββ OpenSans-Light.ttf
βΒ Β  βΒ Β  βββ PlayfairDisplay-Regular.ttf
βΒ Β  βββ images
βΒ Β  βΒ Β  βββ bateria-1.jpg
βΒ Β  βΒ Β  βββ cantante-1.jpg
βΒ Β  βΒ Β  βββ cantante-2.jpg
βΒ Β  βΒ Β  βββ festival.jpg
βΒ Β  βΒ Β  βββ guitarrista-1.jpg
βΒ Β  βΒ Β  βββ guitarrista-2.jpg
βΒ Β  βΒ Β  βββ guitarrista-3.jpg
βΒ Β  βΒ Β  βββ guitarrista-4.jpg
βΒ Β  βΒ Β  βββ guitarrista-5.jpg
βΒ Β  βΒ Β  βββ guitarrista-6.jpg
βΒ Β  βΒ Β  βββ jazz-club.jpg
βΒ Β  βΒ Β  βββ logo_128.png
βΒ Β  βΒ Β  βββ logo_256.png
βΒ Β  βΒ Β  βββ logo_48.png
βΒ Β  βΒ Β  βββ microfono.jpg
βΒ Β  βΒ Β  βββ piano-2.jpg
βΒ Β  βΒ Β  βββ piano.jpg
βΒ Β  βΒ Β  βββ trompetista-1.jpg
βΒ Β  βΒ Β  βββ trompetista-2.jpg
βΒ Β  βΒ Β  βββ trompetista-3.jpg
βΒ Β  βΒ Β  βββ trompetista-4.jpg
βΒ Β  βΒ Β  βββ wall\ copy.jpg
βΒ Β  βΒ Β  βββ wall.jpg
βΒ Β  βββ scripts
βΒ Β  βΒ Β  βββ main.js
βΒ Β  βββ styles
βΒ Β      βββ _fonts.scss
βΒ Β      βββ _icons.scss
βΒ Β      βββ _variables.scss
βΒ Β      βββ layouts
βΒ Β      βΒ Β  βββ _bands.scss
βΒ Β      βΒ Β  βββ _blog.scss
βΒ Β      βΒ Β  βββ _common.scss
βΒ Β      βΒ Β  βββ _home.scss
βΒ Β      βΒ Β  βββ _tickets.scss
βΒ Β      βββ main.scss
βββ bands.html
βββ blog.html
βββ index.html
βββ tickets.html
βββ views
    βββ bands.html
    βββ blog.html
    βββ footer.html
    βββ header.html
    βββ home.html
    βββ tickets.html

7 directories, 46 files
```

### π‘ Continuous Deployment con netlify

Cada vez que realizamos cambios en la rama main se deploya automΓ‘ticamente el sitio web en la plataforma netlify

Url del proyecto: https://elegant-taiyaki-2ef29d.netlify.app/

### π€Ή Feliz desarrollo !
