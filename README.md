# Guía de sonido

Guía gratuita para quienes operan sistemas de sonido convencionales en iglesias y lugares chicos.
Es una sola página estática (`public/index.html`), sin servidor ni base de datos.

## Contenido

- **Señales y conexiones:** reconocer conectores, niveles de señal, compatibilidad y práctica.
- **Ajuste de nivel del sistema:** paso a paso y práctica con una consola simulada.
- **Ajuste de canales:** práctica de ganancia por instrumento.

## Publicar con Firebase Hosting

1. Crear el proyecto en la consola de Firebase y activar Hosting.
2. Instalar las herramientas: `npm install -g firebase-tools` y `firebase login`.
3. Dentro de esta carpeta: `firebase init hosting:github`.
   - Carpeta pública: `public`.
   - Single-page app: **No**.
   - Elegir este repositorio y publicar automáticamente al hacer merge en la rama principal.
4. Cada cambio subido a la rama principal se publica solo.

Para probarlo en local: abrir `public/index.html` en el navegador.

## Editar

Todo el contenido (textos, estilos, scripts e imágenes) está dentro de `public/index.html`.
