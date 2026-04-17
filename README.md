# MySelf Collage 🖼

Una galería personal de fotos con scroll infinito animado mediante GSAP.

🔗 **[Ver en vivo](https://OlaiGV.github.io/GSAP-Gallery/)**

---

## Tecnologías

- **HTML5 / CSS3**
- **[GSAP 3](https://gsap.com/)** — animaciones de columnas y ScrollTrigger

## Estructura

```
GSAP-Gallery/
├── index.html
├── CSS/
│   ├── reset.css
│   └── style.css
├── IMG/
└── JS/
    └── script.js
```

## Funcionamiento

- Tres columnas de imágenes se desplazan verticalmente de forma continua y en direcciones alternas.
- Al hacer scroll, la velocidad de las columnas se acelera proporcionalmente al impulso del scroll.
- Al pasar el cursor sobre una imagen, pasa de escala de grises a color.

## Uso local

```bash
git clone https://github.com/OlaiGV/GSAP-Gallery.git
cd GSAP-Gallery
```

> Recomendado usar **Live Server** en VS Code para evitar problemas de CORS con las imágenes.
