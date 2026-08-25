# Next Level Basketball Academy 🏀

Sitio web oficial de **Next Level Basketball Academy**, una plataforma orientada al desarrollo técnico, táctico y formación integral de categorías formativas de básquetbol.

---

## 🚀 Demo del Proyecto

* **Sitio Web desplegado:** [Ver sitio en Vercel / GitHub Pages]https://academiadebasquet.netlify.app/

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica en todas las secciones.
* **CSS3 / SCSS (Sass):** Arquitectura modular mediante SASS (`@use`), variables, nesting, mixins y partials.
* **AOS (Animate On Scroll):** Librería externa para animaciones interactivas al hacer scroll.
* **Git & GitHub:** Control de versiones y repositorio remoto.
* **Vercel / GitHub Pages:** Hosting y despliegue continuo.

---

## 📂 Arquitectura SCSS

El proyecto utiliza la metodología de partials estructurada en carpetas temáticas dentro de `scss/`:

```text
scss/
├── base/
│   ├── _variables.scss      # Definición de colores y tipografía
│   ├── _reset.scss          # Reset global y estilos base
│   └── _animations.scss     # Keyframes y animaciones nativas
├── components/
│   ├── _buttons.scss        # Botones y estilos de interacción
│   ├── _cards.scss          # Grillas y tarjetas (categorías, staff, etc.)
│   └── _tables.scss         # Tablas de horarios adaptables
├── layout/
│   ├── _header.scss         # Barra de navegación principal
│   ├── _hero.scss           # Secciones principales / encabezados
│   ├── _forms.scss          # Formularios de contacto
│   └── _footer.scss         # Pie de página y redes
└── main.scss                # Archivo principal de compilación (@use)