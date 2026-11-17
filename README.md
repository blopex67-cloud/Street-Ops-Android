# Street Ops — prototipo FPS táctil para Android

Prototipo de entrenamiento en HTML + Three.js empaquetado con Cordova. Incluye campo de tiro 3D, cámara en primera persona, movimiento con joystick, apuntado por arrastre, botón de disparo, recarga, marcador y un objetivo humanoide. No es un juego completo al nivel de Call of Duty: es una base jugable para ampliar.

## Controles Android
- Joystick inferior izquierdo: moverse.
- Arrastra el dedo por el centro/derecha de la pantalla: girar la cámara y apuntar.
- DISPARAR: dispara al objetivo que quede bajo la mira.
- RECARGAR: restaura 30 balas.

## Modelo incluido
`www/assets/CesiumMan.glb` fue descargado del repositorio [KhronosGroup/glTF-Sample-Assets](https://github.com/KhronosGroup/glTF-Sample-Assets), modelo Cesium Man. La colección está bajo CC BY 4.0. Ver [LICENSES.md](LICENSES.md) para atribución.

## APK
Cada push a `main` y cada ejecución manual de GitHub Actions construye un APK debug. En GitHub abre **Actions → Android APK → último run → Artifacts → Street-Ops-debug-APK**.

## Compilación local
Requiere Node.js 20, Java 17 y Android SDK: `npm install`, `npx cordova platform add android@13`, `npx cordova build android --debug`.
