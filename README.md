# Checkpoint: reseñas de videojuegos

Aplicación web con Express y EJS para consultar videojuegos, leer reseñas y publicar una opinión con calificación.

## Requisitos

- Node.js
- npm

## Ejecutar

```bash
npm install
npm run dev
```

Abre `http://localhost:3000` en el navegador. También puedes iniciar la aplicación con `npm start`.

## Funcionalidades

- Catálogo con nombre, género, plataformas y descripción de cada videojuego.
- Calificación promedio y reseñas visibles por juego.
- Formulario para publicar nombre, comentario y calificación de 1 a 5 estrellas.
- Diseño adaptable a pantallas móviles y de escritorio.

Las reseñas se mantienen en memoria mientras el servidor está activo y se reinician cuando se reinicia la aplicación.
