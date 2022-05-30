## 🚀 Entorno de desarrollo

### 👩🏽‍🚒 Herramientas necesarias

1. [Instalar Node.js y npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
2. Clona este proyecto: `git clone git@github.com:uly081219/css-html-2-pec3.git`
3. Acceder a la carpeta del proyecto: `cd css-html-2-pec3`

### 🔥 Ejecución de la aplicación

1. Instalar todas las dependecias: `npm install`
2. Construir el sitio web: `npm run build`
3. Inicar el servidor de dessarrollo: `npm run dev`

Puedes acceder al servidor mediante la url: http://localhost:8123

### 👩🏽‍🏫 Explicación del proyecto

Este proyecto pretende ser un sitio web de un Festival de Jazz celebrado en la Costa Brava.

### 🗂 Estructura del proyecto

`tree -L 4 assets  src`

```
src
├── assets
│   ├── fonts
│   │   ├── OpenSans-Light.ttf
│   │   └── PlayfairDisplay-Regular.ttf
│   ├── images
│   │   ├── bateria-1.jpg
│   │   ├── cantante-1.jpg
│   │   ├── cantante-2.jpg
│   │   ├── festival.jpg
│   │   ├── guitarrista-1.jpg
│   │   ├── guitarrista-2.jpg
│   │   ├── guitarrista-3.jpg
│   │   ├── guitarrista-4.jpg
│   │   ├── guitarrista-5.jpg
│   │   ├── guitarrista-6.jpg
│   │   ├── jazz-club.jpg
│   │   ├── logo_128.png
│   │   ├── logo_256.png
│   │   ├── logo_48.png
│   │   ├── microfono.jpg
│   │   ├── piano-2.jpg
│   │   ├── piano.jpg
│   │   ├── trompetista-1.jpg
│   │   ├── trompetista-2.jpg
│   │   ├── trompetista-3.jpg
│   │   ├── trompetista-4.jpg
│   │   ├── wall\ copy.jpg
│   │   └── wall.jpg
│   ├── scripts
│   │   └── main.js
│   └── styles
│       ├── _fonts.scss
│       ├── _icons.scss
│       ├── _variables.scss
│       ├── layouts
│       │   ├── _bands.scss
│       │   ├── _blog.scss
│       │   ├── _common.scss
│       │   ├── _home.scss
│       │   └── _tickets.scss
│       └── main.scss
├── bands.html
├── blog.html
├── index.html
├── tickets.html
└── views
    ├── bands.html
    ├── blog.html
    ├── footer.html
    ├── header.html
    ├── home.html
    └── tickets.html

7 directories, 46 files
```

### 📡 Continuous Deployment con netlify

Cada vez que realizamos cambios en la rama main se deploya automáticamente el sitio web en la plataforma netlify

Url del proyecto: https://cerulean-kringle-87662b.netlify.app

### 🤹 Feliz desarrollo !
