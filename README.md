# Coffee Party 40

`Coffee Party 40` es una mini experiencia web hecha para celebrar un cumpleaños con estética arcade y temática cafetera. El sitio principal funciona como portada del evento y desde ahí se puede entrar a cuatro minijuegos inspirados en clásicos:

- `Arabicanoid`
- `Puck-Man`
- `Catch-A-Bean`
- `Bean Invaders`

Todo el proyecto está hecho en HTML, CSS y JavaScript vanilla. No requiere build, dependencias ni instalación.

## Qué incluye el repo

- `index.html`: landing principal con la invitación y accesos a los juegos.
- `games/arabicanoid.html`: versión cafetera de un rompebloques.
- `games/puck-man.html`: laberinto estilo arcade.
- `games/catch-a-bean.html`: juego de reflejos para atrapar granos.
- `games/bean-invaders.html`: shooter arcade con temática café.

## Cómo abrirlo

La forma más simple es abrir `index.html` en el navegador.

Si preferís levantar un servidor local, podés usar cualquiera de estas opciones desde la carpeta del proyecto:

```powershell
python -m http.server 8000
```

o

```powershell
npx serve .
```

Luego abrí `http://localhost:8000` o la URL que te indique el servidor.

## Para quién está pensado

Este repo está pensado para:

- compartir una invitación interactiva;
- publicar una landing estática en GitHub Pages u otro hosting simple;
- usarlo como base de una experiencia web casual, visual y sin backend.

## Estructura y tecnología

- Frontend estático puro.
- Sin framework.
- Sin proceso de build.
- Ideal para deploy estático.

## Publicación

Como el proyecto es completamente estático, se puede publicar muy fácil en plataformas como GitHub Pages, Vercel o Netlify.

En este caso, el repositorio remoto apunta a:

`https://github.com/nchiari/coffee-party-40`

## Nota

El contenido visual y textual está orientado a una celebración concreta, así que si querés reutilizar el proyecto para otro evento probablemente te convenga ajustar textos, fecha, lugar y detalles de la invitación.
