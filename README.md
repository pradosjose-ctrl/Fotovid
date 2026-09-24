# FotoVid — fotos a vídeo

Aplicación web que convierte tus **fotos en un vídeo**, directamente en el navegador.
Se puede instalar en el móvil como si fuera una app, con su propio icono en la pantalla de inicio.

## ✨ Qué hace

- Selecciona varias imágenes desde tu dispositivo.
- Genera un vídeo a partir de las fotos, 100 % en tu teléfono (no se suben a ningún servidor).
- Instalable como app (PWA): icono propio, pantalla completa y sin barra del navegador.
- Diseño pensado para móvil. Interfaz en español.

## 🚀 Cómo usarla

1. Abre `index.html` en el navegador (o la URL de GitHub Pages).
2. Pulsa el botón para **elegir tus fotos**.
3. Ajusta las opciones y pulsa **crear vídeo**.
4. Descarga el resultado.

## 📲 Cómo poner el icono en la pantalla de inicio

**iPhone / iPad (Safari):**

1. Abre la página en **Safari** (en iOS solo funciona con Safari).
2. Pulsa el botón **Compartir** ⬆️.
3. Baja y toca **«Añadir a pantalla de inicio»**.
4. Nombre: **FotoVid** → **Añadir**.

**Android (Chrome):**

1. Abre la página en Chrome.
2. Menú **⋮** → **«Añadir a pantalla de inicio»** / **«Instalar aplicación»**.

> El icono aparece correctamente si abres la página desde una dirección web
> (por ejemplo GitHub Pages), no desde un archivo local.

## 🛠️ Tecnología

- HTML5, CSS3 y JavaScript (vanilla, un solo archivo).
- API `canvas` + `MediaRecorder` para montar el vídeo en el propio dispositivo.
- `manifest.webmanifest` + iconos PNG para poder instalarla como app.
- Sin dependencias externas ni backend.

## 📁 Estructura

```
.
├── index.html            # La aplicación completa (HTML + CSS + JS)
├── manifest.webmanifest  # Datos de la app instalable (nombre, colores, iconos)
├── icon-512.png          # Icono grande
├── icon-192.png          # Icono Android
├── icon-180.png          # Icono iPhone (apple-touch-icon)
├── icon-152.png          # Icono iPad
├── favicon-32.png        # Icono de la pestaña del navegador
└── README.md
```

## 🌐 Publicar con GitHub Pages

1. Entra en **Settings → Pages** del repositorio.
2. En *Source*, elige la rama `main` y la carpeta `/ (root)`.
3. Guarda y espera un minuto: tendrás una URL pública (`https://usuario.github.io/fotovid/`).
4. Abre esa URL en el móvil y añádela a la pantalla de inicio.

## 📄 Licencia

Pendiente de definir por el autor.
