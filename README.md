<div align="center">

  <h1>🌻 Ruleta Dedsafio 3 — Special Edition 🌻</h1>

  <p><b>Una experiencia interactiva web inspirada en la interfaz gráfica de Minecraft, creada con Vanilla JS y animaciones cuadro por cuadro sincronizadas por audio.</b></p>

  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
  [![Minecraft Style](https://img.shields.io/badge/Style-Minecraft_GUI-55FF55?style=for-the-badge)](https://www.minecraft.net/)

</div>

---

## 🌟 Sobre el Proyecto

**Ruleta Dedsafio 3** es un minijuego web interactivo que simula el giro de una ruleta del evento *Dedsafio*, adaptado con un motor de renderizado liviano en HTML5 Canvas para reproducir animaciones complejas frame-by-frame.

El proyecto cuenta con un sistema de **8 modos temáticos de color**, efectos de resplandor dinámicos (`glow`), audio inmersivo y eventos de animación especiales (**Momento Nutria** y **Modo Reviil**) que se ejecutan al detenerse la ruleta.

---

## ✨ Características Principales

* 🎮 **Interfaz Pixel Art (Minecraft GUI):** Estilo retro con sombras duras, tipografía clásica de Minecraft, contenedores e inventarios con bordes extruidos.
* 🌈 **8 Categorías de Color:** Sistema de temas dinámicos que cambia el título, los bordes, los iconos y los mensajes del servidor en tiempo real.
* 🎞️ **Motor de Animaciones Canvas Frame-by-Frame:** 
  * Carga e interpolación suave de secuencias PNG de más de 200 fotogramas.
  * Sincronización precisa basada en `requestAnimationFrame` y la duración en segundos del audio.
* 💥 **Efectos Visuales Avanzados:**
  * **Modo Reviil (Rojo):** Overlay con scanlines de CRT, aberración cromática, pulso dinámico y distorsión.
  * **Momento Nutria (Rosado):** Glow estético y desenfoque de fondo.
* 💬 **Modal de Chat del Servidor:** Simula la caja de chat multijugador de Minecraft para mostrar los mensajes personalizados.

---

## 🎨 Modos de Color y Significado

| Color | Nombre | Evento Especial / Mensaje |
| :---: | :--- | :--- |
| 🌻 | **Amarilla** | Especial Flores Amarillas (Detalle lindo y luz) |
| 💙 | **Azul** | Calma y cero estrés (Paz y descanso) |
| 💜 | **Morada** | Cómplice y parche (Juegos y charla random) |
| 🧡 | **Naranja** | Risas y comida (Vales para salir por algo dulce) |
| ❤️ | **Roja** | Modo Épico (**Animación Reviil ACTIVADA**) |
| 💗 | **Rosada** | Aprecio sincero (**Animación Nutria ACTIVADA**) |
| 🩵 | **Turquesa** | Anécdotas y chisme (Momentos random) |
| 💚 | **Verde** | Buena suerte y éxito (Exámenes y proyectos) |

---

## 📁 Estructura del Repositorio

```text
├── ImgR/                 # Secuencias de imágenes para cada ruleta por color
│   ├── amarilla/         # Frames amarilla-1.png ... amarilla-288.png
│   ├── azul/             # Frames azul-1.png ...
│   ├── morada/
│   ├── naranja/
│   ├── roja/
│   ├── rosada/
│   ├── turqueza/
│   └── verde/
├── nutria/               # Frames de animación Momento Nutria (1-98)
├── reviil/               # Frames de animación Modo Reviil (1-199)
├── sounds/               # Archivos de audio (.ogg)
│   ├── ruleta.ogg
│   ├── muerte.ogg
│   └── reviil.ogg
├── index.html            # Aplicación principal (HTML + CSS + JS)
└── README.md             # Documentación del proyecto
