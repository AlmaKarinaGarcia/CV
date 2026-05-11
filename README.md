# CV Interactivo — Alma Karina García

> Currículum vitae interactivo construido con HTML, CSS y JavaScript vanilla. Diseño editorial oscuro con animaciones, navegación dinámica y experiencia expandible.

---

## 🔗 Demo en vivo

[almakarinagarcia.github.io/portafolio](https://almakarinagarcia.github.io/portafolio/)

---

## ✨ Features

- **Cursor glow** — efecto de luz ambiental que sigue al puntero
- **Experiencia tipo acordeón** — cada puesto se expande/colapsa con clic
- **Skill bars animadas** — se llenan con transición al hacer scroll
- **Navegación inteligente** — resalta la sección activa automáticamente
- **Animaciones reveal** — elementos entran al viewport con fade + slide
- **Botón imprimir / PDF** — FAB flotante en esquina inferior derecha
- **Responsive** — adaptado para móvil y escritorio
- **Print-friendly** — estilos especiales para exportar como PDF limpio

---

## 🗂 Estructura del proyecto

```
portafolio/
├── index.html          # Página principal (portafolio)
├── cv.html             # CV interactivo
├── about.html          # Sobre mí
├── Assets/
│   ├── linkedin.png
│   ├── github.png
│   └── Especialista en Marketing Digital.png
└── README.md
```

---

## 🛠 Stack técnico

| Tecnología | Uso |
|---|---|
| HTML5 semántico | Estructura del documento |
| CSS3 (variables, grid, transitions) | Diseño y animaciones |
| JavaScript vanilla | Acordeón, scroll observer, cursor glow |
| Google Fonts | Playfair Display + DM Sans |
| IntersectionObserver API | Animaciones on-scroll y nav activa |

Sin frameworks. Sin dependencias. Cero npm.

---

## 🚀 Cómo usar

### Opción 1 — GitHub Pages (recomendado)

1. Clona o descarga este repositorio
2. Sube `cv.html` a tu repo como `cv.html` (o reemplaza `index.html`)
3. Activa GitHub Pages en **Settings → Pages → Branch: main**
4. Tu CV estará en `https://tu-usuario.github.io/portafolio/cv.html`

### Opción 2 — Local

Abre `cv.html` directo en el navegador. No requiere servidor.

### Generar PDF

1. Abre el archivo en Chrome o Edge
2. Presiona el botón 🖨 (esquina inferior derecha) o `Ctrl + P`
3. Selecciona **Guardar como PDF**
4. Recomendado: desactiva encabezados y pies de página en las opciones de impresión

---

## 🎨 Personalización

Todas las variables de color están en `:root` al inicio del `<style>`:

```css
:root {
  --bg: #0c0c0c;          /* Fondo principal */
  --surface: #141414;     /* Fondo de secciones */
  --accent: #e05a2b;      /* Color de acento principal */
  --accent2: #f0a16a;     /* Acento secundario */
  --text: #f0ece4;        /* Texto principal */
  --muted: #8a857c;       /* Texto secundario */
}
```

Para cambiar el esquema de color basta con editar esos 6 valores.

---

## 📄 Secciones del CV

| # | Sección | Contenido |
|---|---|---|
| 01 | Experiencia | 7 posiciones (2015–actualidad) con acordeón interactivo |
| 02 | Habilidades | Skill bars animadas + 20 herramientas del stack |
| 03 | Educación | Maestría, certificaciones y formación técnica |
| — | Contacto | LinkedIn, GitHub, Portafolio, WhatsApp |

---

## 👩‍💻 Sobre la autora

**Alma Karina García** — Especialista en Marketing Digital con más de 10 años de experiencia en Paid Media, SEO y analítica de datos. Actualmente Trafficker & SEO Specialist en QJMOTOR · AMILILLA.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-almag--planner-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/almag-planner/)
[![GitHub](https://img.shields.io/badge/GitHub-AlmaKarinaGarcia-181717?style=flat&logo=github)](https://github.com/AlmaKarinaGarcia)

---

## 📝 Licencia

Uso personal. Si te sirve de inspiración, un ⭐ al repo se agradece.
