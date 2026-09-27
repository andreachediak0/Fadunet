# FaduNet 1.0

Navegador Android liviano, en español y sin bibliotecas externas. Interfaz propia en tonos lila y azul, con barra de direcciones, búsqueda, navegación atrás/inicio/recargar y un bloqueador de anuncios sencillo integrado en WebView.

## Funciones

- Busca en internet o abre una dirección web desde la misma barra.
- Accesos rápidos a Wikipedia, YouTube y OpenStreetMap.
- Botones para volver, ir al inicio y recargar.
- Bloqueador activado al iniciar; se puede prender/apagar con **Bloqueo ON/OFF**.
- Controles de zoom y diseño adaptable a teléfonos.
- Solo solicita permiso de Internet; no pide ubicación ni acceso a archivos.
- Sin SDK de anuncios, servicios de Google Play ni librerías externas.

## Aviso sobre el bloqueador

El bloqueo incluido es ligero y funciona por dominios conocidos de publicidad (por ejemplo, redes publicitarias externas). No descarga listas actualizadas y no puede quitar todos los anuncios: algunos sitios sirven anuncios desde sus propios dominios o pueden cambiar sus servidores. Apagarlo/encenderlo recarga la página actual.

## Compatibilidad y compilación

- Android Studio **2.3.3** / Android Gradle Plugin **2.3.3**.
- `compileSdkVersion 25`, `minSdkVersion 16` (Android 4.1 o posterior).
- No necesita claves API.

1. Extraé el ZIP.
2. En Android Studio elegí **Open** y abrí la carpeta `FaduNet`.
3. Esperá la sincronización de Gradle.
4. Elegí **Build > Build APK(s)**. El APK de prueba quedará en `app/build/outputs/apk/debug/app-debug.apk`.
5. Para instalarlo, copiá ese APK al teléfono y autorizá la instalación de esa fuente cuando Android lo solicite.

El proyecto requiere que Android Studio tenga instalado el SDK 25 y Build Tools 25.0.3. El APK debug no es una versión firmada para publicar en Play Store.

## Privacidad

FaduNet no incorpora analítica propia ni recopila ubicación. Los sitios que visites y el proveedor de búsquedas que uses pueden recibir información según sus propias políticas, como ocurre con cualquier navegador web.
