# Fábrica de Ideas para la fundación Fábrica de Sueños

Código fuente completo de la versión actual, preparado para GitHub Pages. El nombre visible «Fábrica de Ideas» se conserva tal como aparece en la página original. Esta entrega no cambia el diseño ni publica automáticamente el sitio.

## Archivos

- `index.html`: documento original y estructura de la página.
- `styles.css`: todos los estilos originales, en el mismo orden, incluidos colores, tipografías, diseño adaptable e impresión.
- `script.js`: JavaScript original completo, anteriormente llamado `app.js`.
- `.nojekyll`: archivo vacío para servir este proyecto estático sin procesarlo con Jekyll.
- `README.md`: estas instrucciones.

No requiere Node.js, PHP, base de datos, instalación de paquetes ni compilación.

## Publicar desde tu navegador

1. Descarga y descomprime el ZIP en el computador. No subas el ZIP sin descomprimir.
2. Inicia sesión en GitHub con `VivianCubides02`.
3. Abre https://github.com/new y crea un repositorio llamado `fabrica-de-suenos`. Selecciona **Public** para utilizar GitHub Pages con una cuenta gratuita. Puedes inicializarlo con un README para disponer de la rama `main`.
4. En el repositorio selecciona **Add file → Upload files**. Arrastra los archivos de esta carpeta, no la carpeta que los contiene. Confirma con **Commit changes**. Si ya existe un README, reemplázalo con el incluido en el paquete o conserva las instrucciones por separado.
5. Comprueba que `index.html`, `styles.css` y `script.js` estén directamente en la raíz del repositorio, al mismo nivel. En Windows, `.nojekyll` puede no verse; si no puedes subirlo, créalo con **Add file → Create new file**, escribe `.nojekyll` como nombre y confirma el archivo vacío. Este proyecto no utiliza contenido que necesite Jekyll.
6. En **Settings → Pages**, elige **Deploy from a branch** en **Source**.
7. Selecciona la rama **main** y la carpeta **/(root)**. Pulsa **Save**.
8. Revisa la publicación en **Actions** y vuelve a **Settings → Pages** para abrir la dirección confirmada por GitHub. La dirección esperada, si usas exactamente ese usuario y repositorio, es:

   https://viviancubides02.github.io/fabrica-de-suenos/

Esa dirección es la prevista, no una confirmación de que ya esté publicada. Si el repositorio ya existe, úsalo sin borrar contenido ajeno al proyecto o elige otro nombre; la parte final del enlace cambiará.

## Comprobar después de publicar

- Abre Inicio: deben aparecer el cielo ilustrado, las nubes, el arcoíris y los bloques A, 3 y estrella.
- Entra a Para practicantes: revisa las seis actividades y prueba la búsqueda y el filtro por tema.
- Abre cada actividad y sus dos opciones de impresión. En la ventana de impresión puedes elegir Guardar como PDF.
- En los imprimibles de colores, activa la impresión de gráficos de fondo para reproducir los fondos de color.
- Guarda una nota y vuelve a abrir la actividad en el mismo navegador y dirección.
- En Para niños prueba Parejas escondidas, Cuenta y descubre y La vocal perdida. Comprueba los mensajes, los botones para avanzar y para repetir.
- Revisa la página en celular y abre el enlace desde una ventana sin sesión de GitHub: los visitantes no necesitan cuenta.

## Recursos y funcionamiento conservados

La ilustración principal y las plantillas se generan con SVG o HTML incluido en el código. No faltan carpetas de imágenes ni archivos de actividades: se producen al pulsar los botones. Se conservaron los emojis originales; su apariencia puede variar según el dispositivo.

Las fuentes originales DM Sans y Outfit se solicitan a Google Fonts desde `styles.css`. Se necesita acceso a ese servicio para mostrar exactamente esas tipografías; si no está disponible, el navegador usa la alternativa sans-serif que ya estaba definida en la versión original. No se sustituyeron las fuentes ni se añadieron bibliotecas externas.

Las notas usan `localStorage`: permanecen únicamente en ese navegador, dispositivo y origen web. Las notas guardadas en el dominio anterior no aparecen automáticamente en GitHub Pages. Si quieres conservarlas, cópialas antes de cambiar de dirección. Borrar los datos del navegador también puede eliminar las notas. No hay sincronización ni cuentas de usuarios.

El código QR no forma parte de la versión original. Se puede preparar después con la dirección definitiva. Las guías y juegos actuales sí están incluidos completos.

## Abrir sin publicar

Descomprime la carpeta y abre `index.html` en un navegador moderno. Las tipografías necesitan conexión. Para verificar el almacenamiento de notas en condiciones equivalentes al sitio publicado, utiliza la dirección de GitHub Pages; el comportamiento del almacenamiento en archivos locales puede variar entre navegadores.

## Actualizar

Edita el archivo correspondiente y vuelve a subirlo a la rama `main`. GitHub Pages volverá a publicar los cambios. Si ves una versión anterior, revisa el estado en Actions y recarga con Ctrl + F5.

No cambies las rutas relativas `./styles.css` y `./script.js` por rutas que empiecen con `/`: las rutas relativas permiten que el sitio funcione dentro de `/fabrica-de-suenos/`.

Si aparece un error 404, verifica la rama, la carpeta y que `index.html` esté en la raíz con ese nombre exacto. Si se ve sin colores o no funcionan los botones, comprueba que ambos archivos vinculados estén subidos con sus nombres exactos.

## Conservación de la versión

Se extrajo el bloque CSS original sin cambiar sus reglas y se copió íntegramente el JavaScript. Las únicas modificaciones de la página son los vínculos a los archivos separados. No se modificaron textos, secciones, botones, actividades, imprimibles ni lógica de juegos. Se mantuvieron también sus comportamientos y límites originales.

El proyecto es un sitio estático con recursos imprimibles e interacción en el navegador. Esta entrega no incluye credenciales, archivos de configuración del alojamiento anterior ni información de la cuenta.

## Documentación oficial de publicación

https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
