# 🎹 Piano MIDI — Juego de Teclado

Una app web jugable de piano que funciona con cualquier archivo MIDI. Diseñada para iPhone en modo horizontal como PWA.

## 🚀 Características

- **Parser MIDI nativo** — sin dependencias externas, lee cualquier archivo `.mid`
- **88 teclas reales** — teclado completo de piano, scrolleable
- **Notas cayendo** — estilo Piano Tiles / Synthesia
- **Sistema de puntuación** — PERFECT / GOOD / OK + combos
- **Modo Libre** — toca sin canción, solo explora el piano
- **PWA** — instálala en tu iPhone como app nativa
- **Audio Web API** — síntesis de piano en tiempo real

## 📱 Instalar en iPhone

1. Abre Safari y ve a la URL de tu app (GitHub Pages, servidor local, etc.)
2. Toca el botón **Compartir** (el cuadrado con flecha ↑)
3. Selecciona **"Añadir a pantalla de inicio"**
4. Ponle nombre y toca **Añadir**
5. La app se abre en pantalla completa en horizontal 🎹

## 🌐 Deploy en GitHub Pages

```bash
git init
git add .
git commit -m "🎹 Piano MIDI app"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/piano-midi.git
git push -u origin main
```

Luego en tu repo GitHub:
- Ve a **Settings → Pages**
- Source: **Deploy from a branch → main → / (root)**
- Tu app estará en: `https://TU_USUARIO.github.io/piano-midi`

## 🎵 Cómo jugar

1. Sube un archivo MIDI (`.mid`)
2. Ajusta la velocidad si es muy rápido/lento
3. Presiona ▶ JUGAR
4. Toca las teclas del piano cuando las notas lleguen a la línea de golpe
5. ¡Acumula combos y puntaje!

## 🎹 Modo Libre

Sin archivo MIDI, solo explora el teclado. Ideal para practicar.

## 📁 Archivos

```
piano-midi/
├── index.html    ← App completa (todo en un archivo)
├── manifest.json ← Configuración PWA
├── sw.js         ← Service Worker (offline)
└── icon.png      ← Ícono de la app
```

## 🛠 Tecnologías

- HTML5 Canvas para las notas cayendo
- Web Audio API para el sonido
- Service Worker para modo offline
- Sin frameworks, sin npm, sin build step

---

*Hecho con ❤️ — solo sube el MIDI y a tocar*
