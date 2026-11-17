PORTAL DE EVIDENCIAS - GUÍA RÁPIDA

ARCHIVOS
- index.html: estructura de las pantallas.
- styles.css: colores, tamaños y diseño adaptable a celular.
- app.js: navegación, formularios, registros y almacenamiento local.
- manifest.webmanifest y sw.js: permiten preparar la app como PWA cuando se sirve desde localhost/HTTPS.

CÓMO ABRIR
1. Descomprime la carpeta.
2. Abre la carpeta Portal_de_Evidencias desde Visual Studio Code.
3. Abre index.html con la extensión Live Server (recomendado), o usa cualquier servidor local.
4. En el navegador, crea una cuenta de demostración.
5. Prueba Perfil, Formación académica, Formación extracurricular, Proyectos y Mis evidencias.

PRUEBAS EN ANDROID
- La computadora y el teléfono deben estar conectados a la misma red Wi-Fi.
- Inicia Live Server y configura su acceso en la red local (host 0.0.0.0 si tu extensión lo permite).
- Abre en Chrome Android la dirección local de tu computadora, usando su IP y el puerto de Live Server.
- Para instalar como acceso directo/PWA, sirve el sitio por localhost/HTTPS y usa "Agregar a pantalla principal" en Chrome.

IMPORTANTE: ALCANCE DE ESTA VERSIÓN
Esta es una versión funcional de demostración, solo de front-end:
- Los perfiles y registros se guardan en el almacenamiento local del navegador.
- Los archivos adjuntos se guardan como datos locales y tienen un límite de 3 MB.
- La cuenta y la contraseña NO tienen seguridad real. No uses contraseñas reales ni información sensible.
- Los datos no se sincronizan entre dispositivos y pueden perderse si se borra el almacenamiento del navegador.
- Para uso real con varios estudiantes se necesita backend, base de datos, autenticación segura y almacenamiento de archivos.

NOTA
No abras el HTML con doble clic si quieres probar la función PWA. Usa Live Server o un servidor local.
