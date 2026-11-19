# Diario de obra (Android, Capacitor)

Requisitos: Node.js 22+ y Android Studio (última versión).

1. `npm install`
2. `npm run sync`        (copia jsPDF a www/ y sincroniza el proyecto Android)
3. `npx cap open android` (abre Android Studio)
4. Conecta el móvil con depuración USB y pulsa Run, o Build > Build APK(s).
   El APK queda en android/app/build/outputs/apk/debug/

Tras cualquier cambio en www/index.html: `npm run sync` y volver a compilar.

PDF: se guardan en Documentos/DiarioObra (si Android lo bloquea, van a caché; usa "Enviar").
Los partes y fotos se guardan en la base de datos interna de la app.
