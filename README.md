# GathSession - Header & Hero Landing Page

> Segunda tarea entregable de CSS: Maquetación estática de alta fidelidad del header-hero para **GathSession**, desarrollada con HTML5 semántico, SASS modular y gráficos vectoriales SVG.

---

## 📌 Características del Proyecto

- **Fidelidad al diseño**: Reproducción pixel-perfect del diseño estático de referencia a resolución 1920×1080.
- **Estructura semántica HTML5**: Uso riguroso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<button>`, etc.
- **Arquitectura SASS / SCSS modular**:
  - `_variables.scss`: Paleta de colores, tipografías y transiciones.
  - `_reset.scss`: Reseteo moderno de estilos para consistencia cross-browser.
  - `_header.scss`: Barra de navegación, logotipo y estados activos.
  - `_hero.scss`: Título principal, descripción, botones de llamada a la acción y fila de características.
  - `_cards.scss`: Cuadrícula artística de avatares con bordes redondeados y proporciones exactas.
  - `main.scss`: Punto de entrada que compila de forma limpia con Dart Sass (`@use`).
- **Iconografía 100% SVG**: Iconos vectoriales nativos para Community, Events, Information y flecha de acción.
- **Interactividad & Estados Hover**:
  - Efectos visuales de transición en enlaces de navegación y logotipo.
  - Elevación con sombra difusa en botón principal *Get Started*.
  - Desplazamiento dinámico en la flecha de *Learn More*.
  - Efectos de elevación e iluminación en los cuadros de características.
  - Efecto flotante con resplandor cromático personalizado según el color de cada tarjeta de avatar.

---

## 📁 Estructura del Repositorio

```text
├── assets/
│   ├── icons/
│   │   ├── arrow-right.svg
│   │   ├── community.svg
│   │   ├── events.svg
│   │   └── information.svg
│   └── images/
│       ├── card-1.png
│       ├── card-2.png
│       ├── card-3.png
│       ├── card-4.png
│       └── card-5.png
├── css/
│   └── style.css
├── scss/
│   ├── _cards.scss
│   ├── _header.scss
│   ├── _hero.scss
│   ├── _reset.scss
│   ├── _variables.scss
│   └── main.scss
├── index.html
├── package.json
├── .gitignore
└── README.md
```

---

## 🚀 Instalación y Uso Local

1. **Clonar el repositorio**:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_DIRECTORIO>
   ```

2. **Instalar dependencias**:
   ```bash
   npm install
   ```

3. **Compilar SASS**:
   ```bash
   # Compilación única
   npm run build:css

   # O modo observador en desarrollo
   npm run watch:css
   ```

4. **Abrir el proyecto**:
   Abre el archivo `index.html` en tu navegador favorito.
