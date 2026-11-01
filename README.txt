HYUNDAI GAMING LAUNCHER — prototipo 0.1
=======================================

Este es un proyecto Android inicial para Android 6.0 (API 23). Incluye:
- Interfaz horizontal negra y roja.
- Lista de aplicaciones que exponen una actividad LAUNCHER.
- Navegación básica por teclado/ratón.
- Solicitud de desinstalación solo para aplicaciones que Android marca como no-sistema.
- Selector de archivo para elegir imagen o vídeo; esta versión todavía NO aplica ni guarda el fondo.
- Actividad declarada como posible HOME launcher, además de acceso normal a aplicaciones.

IMPORTANTE:
- Este proyecto es un prototipo inicial, no un APK compilado ni una versión probada en el Hyundai.
- El menú HOME predeterminado depende del firmware. La opción se debe probar sin desinstalar el menú original.
- El sistema decide si permite desinstalar cada app; la app no fuerza ni elimina paquetes del sistema.
- Los accesos HDMI/TV en directo y la reproducción/guardado de fondos se implementarán después de comprobar qué permite el firmware.
- El proyecto usa Android Gradle Plugin 3.5.4 y compileSdk 28; podría requerir instalar componentes antiguos desde Android Studio.
- Abre la carpeta en Android Studio, deja que Gradle sincronice y compila con Build > Build APK(s).
