# RutaSegura — Prototipo V1

Prototipo navegable (mobile-first) para testear con usuarios la hipótesis de rutas
nocturnas seguras en Arequipa. Todo es un solo archivo `index.html` (HTML/CSS/JS,
sin dependencias ni backend). Los datos son simulados.

## Cómo abrirlo

- **Directo:** doble clic en `index.html` (abre en cualquier navegador).
- **Desde el celular en la misma red Wi-Fi:**
  ```
  cd rutasegura
  python3 -m http.server 8080
  ```
  y abre `http://<IP-de-tu-computadora>:8080` en el celular.
- **Compartir con testers remotos:** sube la carpeta a GitHub Pages, Netlify Drop o Vercel.

## Flujo de testeo

Inicio → Buscar ruta segura → elegir ruta (mapa + score) → Reportar algo →
Compartir mi viaje (link → en vivo → llegada) → "Cuéntanos qué te pareció".

Las respuestas de intención de uso (Sí / Tal vez / No) se guardan en el navegador
del dispositivo; ver Perfil → "Resultados de esta sesión de testeo (facilitador)",
con botón para copiar en CSV.
