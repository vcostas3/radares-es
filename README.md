# Radares ES

Avisador legal de radares para Android. Datos de la DGT + OpenStreetMap. Sin registro, sin publicidad, sin tracking. 100 % offline.

> **Avisador legal** según el Art. 18 RGCir. No es un detector (eso sería ilegal en España).

---

## Descarga

Ve a la pestaña **[Releases](../../releases)** y descarga el APK que corresponda a tu móvil:

| Tu móvil | APK | Tamaño |
|---|---|---|
| Cualquier Android moderno (95 % de los móviles, post-2018) | `app-arm64-v8a-release.apk` | ~30 MB |
| Móviles Android antiguos (pre-2018) | `app-armeabi-v7a-release.apk` | ~24 MB |
| Emuladores Intel | `app-x86_64-release.apk` | ~31 MB |

Enlace directo a la última versión arm64 (la que necesita el 95 % de la gente):

```
https://github.com/vcostas3/radares-es/releases/latest/download/app-arm64-v8a-release.apk
```

---

## Cómo instalarlo

1. Pulsa el enlace del APK desde el móvil (Chrome, WhatsApp, etc.).
2. Cuando se descargue, abre el archivo.
3. Android te dirá algo como **"Por seguridad, este tipo de archivos están bloqueados"** → pulsa **"Ajustes"** → activa **"Permitir desde esta fuente"** (Chrome, WhatsApp, lo que sea).
4. Vuelve atrás y pulsa **"Instalar"**.
5. Abre la app y concede los permisos de **ubicación** y, si quieres usar la burbuja sobre Waze, también **"Mostrar sobre otras apps"**.

Es totalmente seguro — sólo pide permisos de ubicación y ventana flotante para funcionar.

---

## Qué hace

- Avisa por voz cuando te acercas a un radar fijo, de tramo, semáforo o punto habitual de móviles.
- Avisa de incidencias de tráfico DGT (atascos, accidentes, obras, peligros).
- Muestra el límite de velocidad de la vía y avisa si lo excedes.
- Vista 3D del mapa estilo Waze, modo coche XXL, vista satélite.
- Burbuja flotante sobre Waze / Google Maps con la info del radar más cercano.
- Estadísticas de tus viajes con multas estimadas según el RGCir.

---

## Aviso legal

Esta aplicación es un **avisador** de radares fijos y de tramo conocidos públicamente (DGT + OSM). No detecta señales de radar en tiempo real ni patrullas activas. Cumple con el Art. 18 del Reglamento General de Circulación.

El cálculo de multas es **orientativo** y se basa en la tabla oficial del RGCir (no incluye la reducción del 50 % por pronto pago ni distingue delitos penales).

Cumple siempre los límites de velocidad. Esta app no exime de responsabilidad.
