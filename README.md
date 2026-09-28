# perat.es

Dossier de ponente de **Gerard Perat** — fundador y CEO de Cositt Technology®.

Publicado en <https://perat.es>

## Qué hay aquí

```
index.html     La página completa. Sin dependencias, sin build, sin framework.
assets/        Las imágenes que usa la página.
```

Es una sola página estática. No hay proceso de compilación: lo que está en el
repositorio es exactamente lo que se sirve.

La única dependencia externa son las tipografías (Montserrat y Nunito) que se
cargan desde Google Fonts. Si no cargan, la página sigue siendo legible con las
tipografías del sistema.

## Cómo se publica

El repositorio está conectado al Plesk de `alojamiento.cositt.com`, que despliega
la rama `main` automáticamente en el directorio público de perat.es
(`httpdocs/public`).

Publicar un cambio = hacer push a `main`.

## Cómo editarlo

Abre `index.html` y edítalo directamente. Está escrito a mano, sin minificar, con
los estilos al principio en un único bloque `<style>` y comentarios en las
secciones. Las variables de color y tipografía están en `:root`.

El color corporativo es `#C52439`. Cualquier cambio de marca debe respetar la
guía de identidad de Cositt Technology®.

## Imágenes

Las fotos de eventos con asistentes identificables solo se publican cuando existe
cesión de imagen firmada. La foto de la formación de Córdoba
(`assets/cordoba-sala.jpg`) está pixelada por ese motivo.
