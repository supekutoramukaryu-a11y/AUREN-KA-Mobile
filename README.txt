AUREN · PROYECTO KA · PROTOTIPO WEB v1.0

CONTENIDO
- index.html: interfaz y funciones iniciales.
- manifest.webmanifest: configuración instalable tipo PWA.
- sw.js: caché básica para modo sin conexión de la interfaz.
- icon.svg: icono KZ / AUREN.

PROBAR LOCALMENTE
Abre index.html en un navegador moderno. Para instalar como PWA y usar el service worker, publica la carpeta en un hosting HTTPS, por ejemplo GitHub Pages.

FUNCIONES PRESENTES
- Interfaz adaptable a móvil y escritorio.
- Accesos web a Google, YouTube, Spotify y WhatsApp Web.
- Comandos de texto y reconocimiento de voz si el navegador lo admite.
- Síntesis de voz con selección aproximada de voz masculina/femenina según las voces disponibles.
- Hora, fecha y comandos sencillos.
- Alarmas mientras la página permanece abierta y notificaciones si el navegador las permite.
- Configuración visual básica.

LIMITACIONES IMPORTANTES
- No incluye activación por palabra clave en segundo plano ("AUREN") con la página cerrada.
- Las alarmas web no son fiables con la página cerrada o suspendida.
- No accede a contactos ni a toda la galería; para ello hace falta una app nativa y permisos explícitos.
- El reconocimiento de voz depende del navegador, conexión y permisos.
- No incluye todavía un motor de IA online ni claves API. No introduzcas secretos en el frontend.
- Esta es una base de prototipo, no una versión comercial terminada.

PUBLICACIÓN EN GITHUB PAGES
1. Crea un repositorio nuevo llamado auren-ka-mobile.
2. Sube los cuatro archivos del proyecto a la raíz del repositorio.
3. En Settings > Pages, activa el despliegue desde la rama principal y carpeta /root.
4. Espera a que GitHub muestre la URL pública. La URL exacta la proporciona GitHub; no se presupone aquí.

AUREN seguirá siendo el nombre de la aplicación. KA es el nombre en clave del proyecto y KZ el monograma visual.
