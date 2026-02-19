# LINCE — Tienda de Ropa Deportiva

Landing page de e-commerce para **Lince**, una marca de indumentaria deportiva femenina. El sitio presenta la nueva colección de tops deportivos con un diseño elegante, minimalista y completamente responsive.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## Vista previa

### Home
La página principal muestra una imagen hero a pantalla completa y un grid con los productos de la nueva colección.

### Detalle de Producto
Cada producto tiene su propia vista con imagen, nombre, precio, selector de talle y botón de compra que redirige a WhatsApp con un mensaje predefinido.

---

## Características

- **Diseño responsive** — Se adapta a dispositivos móviles y escritorio con media queries.
- **Navegación dinámica** — Los productos se cargan dinámicamente según el parámetro `id` de la URL.
- **Integración con WhatsApp** — El botón "Comprar" genera un mensaje automático con el producto y talle seleccionado.
- **Selector de talles interactivo** — Permite elegir entre S, M y L con feedback visual.
- **Tipografía serif elegante** — Uso de Google Fonts (GFS Didot) para una estética premium.
- **CSS modular** — Estilos separados en archivos por responsabilidad (`base`, `layout`, `components`, `home`, `product`).

---

## Tecnologías

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura semántica del sitio |
| **CSS3** | Estilos, grid layout, flexbox, transiciones y responsive design |
| **JavaScript (Vanilla)** | Lógica de producto, renderizado dinámico e integración con WhatsApp |
| **Google Fonts** | Tipografía GFS Didot |

---

## Estructura del proyecto

```
Lince/
├── index.html                  # Página principal (home)
├── pages/
│   └── product.html            # Página de detalle de producto
├── assets/
│   ├── css/
│   │   ├── base.css            # Reset, variables CSS y estilos globales
│   │   ├── layout.css          # Footer y estructura general
│   │   ├── components.css      # Cards, botones y elementos reutilizables
│   │   ├── home.css            # Estilos específicos del home
│   │   └── product.css         # Estilos de la vista de producto
│   ├── js/
│   │   └── product.js          # Lógica: datos, renderizado, talles y compra
│   └── images/
│       ├── hero.jpeg
│       ├── brand_logo.jpeg
│       ├── logo.ico
│       └── products/
│           ├── black_top.jpeg
│           ├── grey_top.jpeg
│           └── pink_top.jpeg
└── README.md
```

---

## Cómo ejecutar

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/lince.git
   ```
2. Abrí `index.html` en tu navegador, o usá una extensión como **Live Server** en VS Code.

> No requiere instalación de dependencias ni build tools. Es un proyecto 100% estático.

---

## Autor

Desarrollado por **Agus** — 2026



