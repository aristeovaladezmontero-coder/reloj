[README.md](https://github.com/user-attachments/files/30941564/README.md)
<div align="center">

<img src="icono-rio.png" width="120" alt="Río, la mascota de la app">

# Río ENARM

**Estudiamos juntos. Rendimos más.**

Una app hecha *por un grupo de amigos, para amigos*, con un solo objetivo:
cumplir nuestros tiempos de estudio de manera **ordenada y sincronizada** —
mismo reloj, mismos descansos, misma meta.

🐶 **Río** es el perrito de la casa: la mascota oficial que vigila que todos cumplamos nuestros tiempos.

[**▶ Abrir la app**](https://aristeovaladezmontero-coder.github.io/reloj/) · [Instalar en Mac](#-app-para-mac-barra-de-menú)

</div>

---

## ✨ ¿Qué hace?

- ⏱️ **Temporizador sincronizado en tiempo real** — todos en la sala ven el mismo reloj, al segundo, sin importar en qué dispositivo estén
- 🔁 **Ciclo automático** — al terminar el estudio arranca solo el descanso, y al terminar el descanso vuelve el estudio. En loop, sin tocar nada
- 🏠 **Salas por nombre** — crea una sala, comparte el link y listo: quien llegue escribe la sala, su nombre ¡y adentro!
- ⚙️ **Ajustes compartidos** — la duración de estudio y descanso se sincroniza para toda la sala
- 🎯 **Metas y estadísticas** — meta diaria con barra de progreso, gráfica semanal, ranking con medallas 🥇 y metas de la sala
- 👀 **Presencia en vivo** — ve quién está enfocado, quién descansa y quién anda de ausente
- 🌧️ **Sonidos de ambiente** — lluvia, cafetería o ruido blanco para concentrarse
- 🎨 **4 paletas de color** — Violeta, Bosque, Medianoche y Atardecer, con diseño tipo glass de macOS
- 📅 **Cuenta regresiva al ENARM** — para no perder de vista la meta grande

## 🚀 Cómo usarla

1. Abre **https://aristeovaladezmontero-coder.github.io/reloj/**
2. Escribe el nombre de tu sala (o entra a una existente), tu nombre y elige tu avatar
3. Comparte el link con tu grupo para que entren a la misma sala
4. Elige la duración del bloque y ¡a estudiar! El resto es automático 🍀

## 🖥 App para Mac (barra de menú)

Versión nativa que vive junto al reloj de tu Mac: muestra el tiempo restante y cuántos están conectados 🟢, suena aunque tengas la tarjeta oculta, atajo global `⌘ ⇧ C` y arranque automático al encender.

Instalación en un comando (pega esto en Terminal):

```bash
curl -fsSL https://raw.githubusercontent.com/aristeovaladezmontero-coder/cukcoo-enarm-aris/main/install.sh | bash
```

O descarga el DMG desde [Releases](https://github.com/aristeovaladezmontero-coder/cukcoo-enarm-aris/releases).

## 🛠 Cómo está hecha

| Parte | Tecnología |
| --- | --- |
| Web | HTML + CSS + JavaScript (un solo archivo, sin frameworks) |
| Sincronización | Firebase Realtime Database (con transacciones y hora del servidor) |
| App de Mac | Tauri 2 (Rust) — barra de menú, alarma nativa, efecto glass |
| Hosting | GitHub Pages + GitHub Actions |

## 👥 Créditos

Creada por **Aristeo Efraín Valadez Montero** — hecha con ❤️ por médicos que estudian para el **ENARM 2026**, para todos los que quieran estudiar acompañados.

> “Solo se llega más rápido; juntos se llega más lejos.”
