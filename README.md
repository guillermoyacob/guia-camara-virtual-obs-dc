# 🎥 Discord Virtual Camera Guide (OBS)

> Transmit videos, GIFs, or images as your webcam using OBS.  
> *Guía para transmitir videos, GIFs o imágenes como tu cámara usando OBS.*

---

### 🌐 Select Language / Seleccionar Idioma
[🇪🇸 Leer en Español](#-guía-de-cámara-virtual-en-pc) | [🇺🇸 Read in English](#-virtual-camera-guide-on-pc)

---

## 🇪🇸 Guía de Cámara Virtual en PC

### 1. Preparación con OBS
**OBS** es un software gratuito y sin publicidad para streaming. Lo usaremos para generar nuestra cámara virtual.
1. Descarga e instala [OBS Studio](https://obsproject.com/).
2. Lo que veas en el lienzo de OBS será lo que se transmita a Discord.

### 2. Configuración de Escenas y Fuentes
OBS se organiza en **Escenas** (carpetas) y **Fuentes** (archivos multimedia).
- Haz clic en el **+** en el panel de **Escenas** para crear una nueva.
- Haz clic en el **+** en el panel de **Fuentes** para añadir tu contenido:
    - **Video o GIF:** Selecciona `Fuente multimedia` > Marca `Bucle` > Elige tu archivo.
    - **Imagen:** Selecciona `Imagen` > Elige tu archivo.

### 3. Ajuste de Imagen
Para que el contenido se vea perfecto:
1. Clic derecho sobre la fuente > `Transformar` > `Ajustar a pantalla`.
2. Clic derecho sobre la fuente > `Transformar` > `Rotar horizontalmente` (esto evita el efecto espejo en Discord).

### 4. Transmitir a Discord
1. En OBS, haz clic en el botón **Iniciar Cámara Virtual** (abajo a la derecha).
2. En **Discord**, ve a `Ajustes` > `Voz y Video` > `Cámara` y selecciona **OBS Virtual Camera**.

---

### 💡 Tips Extra (Automatización)
**Ejecutar OBS al iniciar Windows:**
1. Presiona `Win + R`, escribe `shell:startup` y presiona Enter.
2. Pega un acceso directo de OBS en esa carpeta.

**Iniciar cámara virtual automáticamente:**
1. Clic derecho en el acceso directo > `Propiedades`.
2. En el campo **Destino**, al final del texto y fuera de las comillas, agrega:
   `--startvirtualcam`
3. En OBS, ve a `Archivo` > `Ajustes` > `General` y marca **Minimizar a la bandeja del sistema al iniciar**.

---

## 🇺🇸 Virtual Camera Guide on PC

### 1. Setup with OBS
**OBS** is a free, ad-free streaming software. We will use it to generate our virtual camera.
1. Download and install [OBS Studio](https://obsproject.com/).
2. Whatever is on the OBS canvas will be what Discord transmits.

### 2. Scenes and Sources Setup
OBS uses **Scenes** (folders) and **Sources** (media files).
- Click **+** in the **Scenes** panel to create one.
- Click **+** in the **Sources** panel to add your content:
    - **Video or GIF:** Select `Media Source` > Check `Loop` > Choose your file.
    - **Image:** Select `Image` > Choose your file.

### 3. Image Adjustment
To make your content look perfect:
1. Right-click the source > `Transform` > `Fit to screen`.
2. Right-click the source > `Transform` > `Flip Horizontal` (this prevents the mirror effect in Discord).

### 4. Streaming to Discord
1. In OBS, click the **Start Virtual Camera** button (bottom right).
2. In **Discord**, go to `Settings` > `Voice & Video` > `Camera` and select **OBS Virtual Camera**.

---

### 💡 Extra Tips (Automation)
**Run OBS on Windows Startup:**
1. Press `Win + R`, type `shell:startup`, and hit Enter.
2. Paste an OBS shortcut into that folder.

**Auto-start Virtual Camera:**
1. Right-click the shortcut > `Properties`.
2. In the **Target** field, at the end of the text (outside the quotes), add:
   `--startvirtualcam`
3. In OBS, go to `File` > `Settings` > `General` and check **Minimize to system tray on startup**.

---
> *Idea taken from ItsOnlyReaper and adapted for OBS by Guiye 🇦🇷*