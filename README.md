# Mi Control Financiero — demo Android

Este proyecto contiene la demo HTML dentro de una app Android sencilla (WebView) y un flujo de compilación en la nube con GitHub Actions. No hace falta instalar Android Studio en tu computadora.

## Cómo generar el APK sin Android Studio
1. Descarga y descomprime este ZIP.
2. Entra a GitHub desde el navegador y crea un repositorio nuevo.
3. Sube todos los archivos y carpetas de este proyecto al repositorio, incluyendo `.github/workflows/build-apk.yml`.
4. Abre la pestaña **Actions** del repositorio y selecciona **Build Android APK**. Si te pregunta, habilita GitHub Actions y ejecuta el flujo.
5. Cuando termine correctamente, abre la ejecución finalizada y descarga el artefacto **Mi-Control-Financiero-APK**.
6. Dentro del ZIP descargado estará `app-debug.apk`. Descárgalo en tu Android y tócalo para instalarlo. Android podría pedir permiso para instalar aplicaciones desde el navegador/gestor de archivos.

## Qué incluye
- Demo en español y tema oscuro.
- Interfaz para movimientos, cuentas, tarjetas/cuotas, presupuesto y ahorros según lo implementado en el HTML.
- Guardado local mediante el almacenamiento del WebView.

## Importante
- Este ZIP es el código fuente y configuración de compilación; todavía no contiene un APK ya compilado.
- Es una demo local: no se conecta a bancos ni procesa pagos.
- No ingreses contraseñas bancarias ni números completos de tarjetas.
- Los datos locales pueden perderse al borrar datos de la aplicación o desinstalarla.
