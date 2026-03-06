# 👗 App de E-commerce de Ropa

Una experiencia de compra simple, visual y confiable para moda — diseñada para reducir fricción, facilitar el descubrimiento de productos y guiar al usuario hacia el checkout de forma natural.

---

## 📌 Descripción

Este proyecto es una interfaz de e-commerce de ropa construida con **HTML y CSS nativos**, sin frameworks ni librerías externas. El objetivo es ofrecer una UI limpia y mobile-first que priorice:

- **Descubrimiento**: categorías claras, tarjetas de producto visuales y barra de búsqueda.
- **Comparación rápida**: ratings visibles, precios y variaciones de talla/color en un vistazo.
- **Ruta clara al checkout**: carrito siempre accesible, feedback inmediato y flujo de pago sin sorpresas.

---

## 🎯 Público objetivo

| Perfil | Necesidad principal |
|--------|---------------------|
| Compradores mobile-first | Explorar por categorías y búsqueda |
| Usuarios indecisos | Señales de confianza: precios visibles y calificaciones |
| Compradores recurrentes | Carrito siempre a mano y feedback inmediato |

---

## 🗂️ Estructura del proyecto

```
app_de_ecommerce_de_ropa/
├── css/
│   ├── variables.css      # Variables globales (colores, tipografía, espaciado)
│   ├── style.css          # Estilos de la página de inicio
│   ├── detail.css         # Estilos de la página de detalle de producto
│   └── checkout.css       # Estilos de la página del carrito / checkout
├── storage/
│   ├── font/
│   │   └── encode_sans/   # Fuente tipográfica del proyecto
│   └── img/               # Imágenes de productos y assets visuales
├── views/
│   ├── detail.html        # Página de detalle del producto
│   └── checkout.html      # Página del carrito de compras
└── index.html             # Página de inicio
```

---

## 📄 Páginas y funcionalidades

### 🏠 Página de Inicio (`index.html`)
- Saludo personalizado con nombre y foto de perfil del usuario.
- Barra de búsqueda para encontrar productos específicos.
- Categorías disponibles: Vestidos, Camisetas, Vaqueros, entre otras.
- Tarjetas de producto con: imagen, botón de favoritos, título, categoría, precio y calificación.
- Menú móvil con accesos a: Inicio, Carrito, Favoritos y Perfil.

### 🛍️ Página de Detalle del Producto (`views/detail.html`)
- Encabezado con botón "Atrás" y botón para añadir/quitar de favoritos.
- Imagen destacada del producto.
- Información: título, calificación, número de vistas, selector de cantidad y botón "Ver más" (despliega descripción completa).
- Sección de personalización: selector de talla y color.
- Botón de compra con precio total actualizado según cantidad.

### 🛒 Página del Carrito / Checkout (`views/checkout.html`)
- Navegación con botón "Atrás" y menú hamburguesa. Título: *Checkout*.
- Listado de productos seleccionados en tarjetas con imagen, título, categoría, precio, cantidad y controles para modificarla.
- Resumen de pago:
  - Método de pago (tarjeta de crédito o débito).
  - Total de productos, precio total, costo de envío, descuentos y subtotal.
  - Botón "Pagar" que muestra un modal de confirmación de compra.

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/app_de_ecommerce_de_ropa.git
   ```

2. Abre el proyecto en tu editor de código preferido (se recomienda [VS Code](https://code.visualstudio.com/)).

3. Instala la extensión **Live Server** en VS Code.

4. Haz clic derecho sobre `index.html` y selecciona **"Open with Live Server"**.

> No se requiere instalación de dependencias ni servidor backend. Es un proyecto estático.

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura semántica de las páginas |
| CSS3 nativo | Estilos, variables CSS y media queries |
| Fuente Encode Sans | Tipografía principal del proyecto |

> ⚠️ **Sin JavaScript, sin frameworks, sin librerías externas.**

---

## 📐 Diseño y recursos

- **Diseño de referencia**: [Figma – Wireframe del proyecto](#)
- **Barra de búsqueda** (opcional): [Referencia](#)
- **Menú hamburguesa** (obligatorio): [Referencia](#)

El diseño sigue principios de **mobile-first** con media queries para adaptarse a pantallas más grandes.

---

## 🌿 Control de versiones

Este proyecto usa **Conventional Commits** para mantener un historial limpio y descriptivo.

### Tipos de commits utilizados

| Tipo | Descripción |
|------|-------------|
| `feat` | Nueva funcionalidad o página |
| `fix` | Corrección de errores visuales o de estructura |
| `style` | Cambios de estilos CSS sin impacto funcional |
| `refactor` | Reorganización de código o estructura de archivos |
| `docs` | Cambios en documentación (como este README) |
| `chore` | Tareas de mantenimiento o configuración |

### Ejemplos

```
feat: add product detail page with size and color selectors
fix: correct cart total calculation display
style: update color palette using CSS variables
docs: add README with project structure and setup guide
```

### Ramas

| Rama | Propósito |
|------|-----------|
| `main` | Rama de presentación — solo código estable y revisado |
| `develop` | Rama de desarrollo activo |
| `feature/*` | Ramas por funcionalidad específica |

---

## 📱 Responsive Design

La UI está optimizada para dispositivos móviles como punto de partida y se adapta progresivamente a tablets y escritorio mediante **media queries** definidas en cada hoja de estilos.

---

## 👤 Autor

Desarrollado como proyecto de interfaz de usuario para una experiencia de compra de moda moderna y accesible.

---

## 📝 Licencia

Este proyecto es de uso educativo y personal. No está destinado a uso comercial.