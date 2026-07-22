# JavaScript Drum Kit 🥁

Una aplicación web interactiva y responsiva que simula una batería (drum kit) utilizando HTML5, CSS3 y JavaScript vanilla.

## 🚀 Características

- Reproducción de sonido instantánea al presionar las teclas correspondientes.
- Animaciones visuales suaves cuando se activa una tecla (`transitionend`).
- Interfaz limpia y minimalista.

## 🎹 Teclas y Sonidos Mapeados

Puedes tocar la batería presionando las siguientes teclas en tu teclado:

| Tecla | Sonido  |
| :---: | :------ |
| **A** | Clap    |
| **S** | Hihat   |
| **D** | Kick    |
| **F** | Openhat |
| **G** | Boom    |
| **H** | Ride    |
| **J** | Snare   |
| **K** | Tom     |
| **L** | Tink    |

## 🛠️ Cómo Empezar

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en tu navegador web favorito. Tambien si deseas puedes hacer uso de servidores locales embebidos como [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) desde un editor de codigo compatible.
3. ¡Comienza a tocar presionando las teclas especificadas!

## 📁 Estructura del Proyecto

- `index.html`: Estructura HTML y la lógica de JavaScript para manejar eventos de teclado (`keydown`) y reproducir audios.
- `style.css`: Estilos generales, diseño de las teclas usando Flexbox, y animaciones de escala/borde.
- `assets/`: Carpeta que contiene los archivos de audio en formato `.wav`.
