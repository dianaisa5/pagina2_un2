# Página Web Responsiva - Diana Frontend Developer

## Estructura del Proyecto

Este proyecto demuestra conceptos clave de CSS moderno y responsive design con una página personalizada basada en el perfil de Diana.

### Archivos Principales
- **index.html** - Estructura HTML5 semántica
- **modelo.css** - Estilos CSS con responsividad completa
- **AFKUE6016.jpg** - Imagen de perfil

---

## Secciones Implementadas

### 1. Header Sticky
- Encabezado fijo en la parte superior
- Título "Diana - Frontend Developer"
- Color azul (#007BFF) con contraste blanco
- Z-index 1000 para mantenerlo sobre otros elementos

### 2. Tarjeta de Perfil
- Foto de perfil circular (90px)
- Nombre en verde (#28a745)
- Ubicación (CDMX) en color lima (#b2ff59)
- Descripción personalizada
- Habilidades: HTML, CSS, JavaScript
- Botones de enlace: GitHub, Frontend, LinkedIn, Twitter, Instagram

### 3. Proyectos Destacados
- Diseño responsive con grid (2 columnas en desktop, 1 en móvil)
- 3 Proyectos: FireWatch, Fit AI, Portfolio Web
- Tarjetas con descripción y tags
- Efecto hover con cambio de color y sombra

### 4. Posicionamiento CSS (Position)
- **FireWatch IoT**: Ejemplo de absolute positioning con capas
  - Sensor (azul)
  - Network (rojo)
  - API (verde)
  - Database (naranja)
- **Responsive Design**: Ejemplo con navbar, contenido y footer
- Uso de: `position: sticky`, `position: absolute`, `position: relative`

### 5. Flexbox - Distribución de Contenido
- **Experiencia Laboral**: Flex con `justify-content: space-between`
  - Frontend Developer (Presente)
  - UI/UX Designer (2022-2023)
  - Web Developer (2021-2022)
- **Especialidades**: Flex con `justify-content: center`
  - Diseño UI, Frontend, Responsive
  - Ciberseguridad, Networks, Software

### 6. Media Queries - Responsividad
- **Mi Perfil Adaptable**: Sección que cambia layout según pantalla
- Muestra: Avatar, información, roles profesionales, habilidades
- 3 Breakpoints implementados:
  - **Desktop**: 2 columnas en grillas, layouts amplios
  - **Tablet (≤768px)**: Ajustes intermedios, textos más pequeños
  - **Mobile (≤480px)**: 1 columna, tamaños compactos

### 7. CSS Grid - Galería de Habilidades
- Grid con 2 columnas en desktop (`grid-template-columns: repeat(2, 1fr)`)
- 4 Items con iconos emoji:
  - HTML5 - Estructura semántica
  - CSS3 - Diseño y estilos
  - JavaScript - Interactividad
  - Ciberseguridad - Protección de datos
- Efecto hover: cambio de borde, sombra, elevación

---

## Sistema de Colores

| Color | Hex | Uso |
|-------|-----|-----|
| Fondo | #141414 | Fondo principal oscuro |
| Primario | #007BFF | Encabezado, botones, bordes |
| Verde | #28a745 | Nombre, énfasis |
| Lima | #b2ff59 | Headings, destacados |
| Gris | #1f1f1f | Tarjetas, secciones |
| Rojo | #FF6B6B | Especialidades |
| Naranja | #FF9500 | Posición relativa |

---

## Puntos de Quiebre (Breakpoints)

```css
/* Desktop (por defecto) */
Ancho: > 768px
- 2 columnas en grillas
- Tamaño de fuente: 16-28px
- Layouts con gap de 20px

/* Tablet */
@media (max-width: 768px)
- 1 columna en grillas
- Tamaño de fuente: 14-22px
- Layouts con gap de 15px

/* Mobile */
@media (max-width: 480px)
- 1 columna en todo
- Tamaño de fuente: 11-20px
- Layouts con gap de 10px

/* Ultra-mobile */
@media (max-width: 320px)
- Espaciado mínimo
- Textos muy pequeños
```

---

## Propiedades CSS Principales

### Flexbox
- `display: flex`
- `flex-direction: column | row`
- `justify-content: space-between | center`
- `align-items: center`
- `flex-wrap: wrap`
- `gap: 20px`

### CSS Grid
- `display: grid`
- `grid-template-columns: repeat(2, 1fr)`
- `gap: 20px`
- Responsivo con media queries

### Position
- `position: sticky` (header)
- `position: absolute` (capas en FireWatch)
- `position: relative` (ajustes menores)
- `z-index: 1000` (control de superposición)

### Transiciones
- `transition: 0.3s` (suave)
- `transform: scale(1.05)`, `translateY(-5px)` (efectos hover)
- `box-shadow` (profundidad)

---

## Características Implementadas

- ✅ Diseño fully responsive (mobile-first approach)
- ✅ Header sticky con navegación
- ✅ Flexbox para alineación de contenido
- ✅ CSS Grid para galería de habilidades
- ✅ Position (sticky, absolute, relative)
- ✅ Media Queries en 4 breakpoints
- ✅ Efectos hover suaves con transiciones
- ✅ Tipografía Google Fonts Roboto
- ✅ Semántica HTML5 correcta
- ✅ Accesibilidad básica (alt en imágenes)

---

## Cómo Usar

1. Abre `index.html` en un navegador web
2. Redimensiona la ventana para ver la responsividad
3. Prueba en dispositivos móviles (usar DevTools: Ctrl+Shift+I)
4. Hovea sobre elementos para ver efectos interactivos

---

## Anatomía del Archivo CSS

```
modelo.css (1250+ líneas)
├── Variables y Base (p, body, sticky-header)
├── Card Principal (card, avatar, name, location)
├── Proyectos (projects-section, project-card)
├── Flexbox (flexbox-alignment-section, work-experience, specialties)
├── Position (position-properties-section, firewatch-demo)
├── Media Queries (768px, 480px, 320px breakpoints)
└── CSS Grid (grid-section, gallery-container, gallery-item)
```

---

## Aprendizajes Clave

Este proyecto integra todos los conceptos CSS aprendidos en el módulo:

1. **Flexbox**: Para alineación flexible de elementos
2. **CSS Grid**: Para layouts complejos de galería
3. **Position**: Para control preciso de capas
4. **Media Queries**: Para diseño responsivo multi-dispositivo
5. **Transiciones**: Para interactividad suave

Cada sección demuestra el concepto de forma práctica con contenido relacionado al perfil de Diana.

---

*Proyecto desarrollado con HTML5, CSS3 y responsive design principles.*
