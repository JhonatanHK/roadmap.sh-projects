# 🧭 Fundamentos para el Proyecto: Sitio Web Básico (HTML Multi-página)

Este documento lista los conceptos clave que necesitarás investigar para completar este proyecto. No te doy el código, te doy el mapa de búsqueda.

## 1. Gestión de Archivos y Enlaces
Este es el salto principal desde el proyecto anterior (una sola página) a un sitio web real.

*   **Concepto a buscar**: `Rutas relativas vs absolutas HTML`.
    *   *Por qué*: Necesitas conectar `index.html` con `contact.html`, `projects.html`, etc.
    *   *Pista*: `./` significa "aquí mismo". `../` significa "carpeta anterior".
*   **Concepto a buscar**: `Etiqueta ancla href`.
    *   *Reto*: Cómo hacer que el menú de navegación funcione igual en todas las páginas.

## 2. Estructura Semántica (Nivel 2)
Viendo la imagen de referencia (el mockup), la estructura es más compleja que una simple columna.

*   **Concepto a buscar**: `Etiqueta HTML nav`.
    *   *Uso*: Para la barra de menú superior.
*   **Concepto a buscar**: `Etiqueta HTML hr`.
    *   *Uso*: Para crear esa línea horizontal divisoria que se ve en el diseño (debajo del header y encima del footer).
*   **Concepto a buscar**: `Etiqueta HTML aside`.
    *   *Análisis*: En el diseño, ves una columna a la izquierda ("Projects") y contenido a la derecha. Sin CSS, esto se verá uno debajo del otro, pero semánticamente podrías usar `<aside>` para la barra lateral o simplemente `<section>` separadas. (Nota: Sin CSS, no se verán en columnas, ¡y eso está bien!).

## 3. Formularios (Contact Page)
La página de contacto requiere interactividad básica.

*   **Concepto a buscar**: `HTML form tag`.
*   **Concepto a buscar**: `HTML input types` (text, email, submit).
    *   *Importante*: Validar que el usuario escriba un correo real.
*   **Concepto a buscar**: `HTML textarea`.
    *   *Uso*: Para mensajes largos (no sirve el `input` normal).
*   **Concepto a buscar**: `HTML label for attribute`.
    *   *Accesibilidad*: Cómo vincular el texto "Nombre" con su casilla correspondiente.

## 4. Listas y Tablas (Organización de datos)
En las secciones de "Projects" y "Education" del diseño.

*   **Concepto a buscar**: `Listas anidadas HTML`.
    *   *Uso*: Listas dentro de listas (ej: Lista de cursos dentro de Education).
*   **Concepto a buscar**: `Tablas HTML básicas` (`table`, `tr`, `td`, `th`).
    *   *Reflexión*: A veces, para mostrar datos estructurados (como la lista de proyectos a la izquierda parece un menú tabular), se usan tablas. *Ojo: No uses tablas para maquetar todo el sitio, solo si los datos lo piden.*

## 5. Caracteres Especiales
*   **Concepto a buscar**: `Entidades HTML` (HTML Entities).
    *   *Reto*: Cómo poner el símbolo de Copyright © en el footer correctamente.

---

### 💡 Consejo Pro
Recuerda que **sin CSS, tu página se verá todo en una sola columna vertical** (uno debajo de otro).
*   Primero verás el Header.
*   Luego el Nav.
*   Luego el "Frontend Developer".
*   Luego la lista de Projects.
*   Luego Work Experience...
*   Y al final el Footer.

**¡No intentes forzar que se vea lado a lado todavía!** Eso es trabajo de CSS. Tu objetivo es que el código HTML tenga lógica.
