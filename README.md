# 📦 Productos Sensitivos — PWA

Aplicación web progresiva (PWA) para registrar, editar y exportar productos sensibles por secciones.  
Funciona como aplicación instalable desde **Google Chrome** en Android.

---

## 🚀 Características
- Tablas editables por secciones.
- Botones para **agregar**, **eliminar filas** y **borrar horarios**.
- Exportación a **vista imprimible / Guardar como PDF**.
- Guardado de datos en **localStorage** (se mantienen al cerrar la app).
- Instalación como **app independiente (APK ligera)** en Android vía PWA.

---

## 📂 Archivos principales
- `index.html` → la aplicación web.
- `manifest.json` → configuración PWA (nombre, íconos, tema).
- `sw.js` → *service worker* para cache y modo offline.
- `icon-192.png` y `icon-512.png` → íconos para instalar en el celular.

---

## 📱 Cómo instalar en Android (Chrome)
1. Sube estos archivos a un hosting (ejemplo: **GitHub Pages**, **Netlify**, **Vercel**).
2. Abre la URL en **Google Chrome (Android)**.
3. Espera unos segundos → aparecerá un mensaje: **“Añadir a pantalla de inicio”**.
4. Si no aparece: abre el menú ⋮ de Chrome → selecciona **“Añadir a pantalla de inicio”**.
5. Ahora tendrás un **icono en el celular** como si fuera una aplicación.

---

## 🌐 Publicar en GitHub Pages
1. Crea un repositorio en [GitHub](https://github.com).
2. Sube todos los archivos (`index.html`, `manifest.json`, `sw.js`, íconos).
   - Desde PC: arrastra la carpeta completa.  
   - Desde celular: sube uno por uno o usa Netlify (más fácil).
3. Ve a **Settings → Pages**.
4. En “Source” selecciona:  
   - Branch: `main`  
   - Folder: `/ (root)`
5. Guarda y espera unos segundos.
6. Tu app estará disponible en:
