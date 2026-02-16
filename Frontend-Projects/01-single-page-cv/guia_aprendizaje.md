# Guía de Aprendizaje: Proyecto CV de Una Sola Página

Esta guía está diseñada para acompañarte en la construcción de tu CV de una sola página utilizando HTML. No te daré el código final, sino los bloques de construcción y el plan para que tú mismo lo armes.

## 📅 Plan de Ejecución del Proyecto

Sigue estos pasos en orden para completar tu proyecto. No intentes hacerlo todo de una vez.

1.  **Configuración Inicial**: Crea tu archivo `index.html` y establece la estructura básica vacía.
2.  **Estructura Semántica**: Define las grandes secciones de tu CV (`header`, `main`, `footer`) sin contenido real todavía.
3.  **Contenido Principal**: Rellena cada sección con tus datos reales usando encabezados (`h1`, `h2`), párrafos (`p`) y listas (`ul`, `li`).
4.  **Multimedia y Enlaces**: Agrega tu foto de perfil (`img`) y enlaces a tus redes sociales o email (`a`).
5.  **Metadatos y SEO**: Configura la sección `<head>` con títulos, descripciones y etiquetas para redes sociales.
6.  **Revisión Final**: Verifica que tu código esté limpio y ordenado.

---

## 🧠 Conceptos Clave y Ejemplos

### 1. La Estructura Básica de HTML

Todo archivo HTML5 comienza con una declaración de tipo de documento y una estructura de árbol básica.

**Concepto**:
-   `<!DOCTYPE html>`: Le dice al navegador que esto es HTML5.
-   `<html>`: La raíz de todo el documento.
-   `<head>`: Información *para el navegador* (meta datos, título, estilos). No se ve en la página.
-   `<body>`: El contenido *visible* para el usuario.

**Ejemplo**:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <title>Mi CV</title>
</head>
<body>
    <!-- Aquí va todo lo que se ve en pantalla -->
    <p>¡Hola Mundo!</p>
</body>
</html>
```

### 2. HTML Semántico (Estructura con Significado)

En lugar de usar `<div>` para todo, usamos etiquetas que describen *qué es* el contenido. Esto es vital para accesibilidad y SEO.

**Etiquetas para tu CV**:
-   `<header>`: Cabecera. Usualmente contiene tu nombre, foto y título profesional.
-   `<main>`: El contenido principal.
    -   `<section>`: Agrupa temas relacionados (ej: "Experiencia", "Educación").
-   `<footer>`: Pie de página. Derechos de autor, enlaces secundarios.

**Ejemplo de Estructura**:
```html
<body>
    <header>
        <!-- Foto y Nombre -->
    </header>

    <main>
        <section>
            <!-- Perfil / Sobre mí -->
        </section>
        
        <section>
            <!-- Experiencia Laboral -->
        </section>
    </main>

    <footer>
        <!-- Copyright -->
    </footer>
</body>
```

### 3. Etiquetas de Contenido

Cómo mostrar tu información dentro de las secciones.

-   **Encabezados (`h1` a `h6`)**: `h1` es el más importante (tu nombre). `h2` para títulos de sección (Experiencia, Educación).
-   **Párrafos (`p`)**: Para bloques de texto normal.
-   **Listas Desordenadas (`ul` + `li`)**: "Unordered List". Perfectas para listar habilidades o tareas.

**Ejemplo**:
```html
<section>
    <h2>Mis Habilidades</h2>
    <ul>
        <li>HTML5</li>
        <li>Comunicación efectiva</li>
        <li>Trabajo en equipo</li>
    </ul>
</section>
```

### 4. Imágenes y Enlaces

-   **Imágenes (`img`)**: Etiqueta de cierre automático. Requiere `src` (dónde está la imagen) y `alt` (descripción alternativa para ciegos o si falla la carga).
-   **Enlaces (`a`)**: "Anchor". Requiere `href` (destino).

**Ejemplo**:
```html
<!-- Imagen (Asegúrate de tener la foto en tu carpeta) -->
<img src="mi-foto.jpg" alt="Foto de perfil de Juan" width="150">

<!-- Enlace (target="_blank" abre en nueva pestaña) -->
<a href="https://linkedin.com/in/usuario" target="_blank">Mi LinkedIn</a>
<a href="mailto:correo@ejemplo.com">Envíame un correo</a>
```

### 5. Metadatos (SEO y Open Graph)

Todo esto va dentro del `<head>`. Ayuda a Google a entender tu página y a que se vea bien al compartirla en Facebook/Twitter/LinkedIn.

**Concepto**:
-   `meta charset="UTF-8"`: Permite ñ, tildes y emojis.
-   `meta name="description"`: El texto que sale debajo del enlace en Google.
-   `meta property="og:..."`: Protocolo Open Graph. Controla la "tarjeta" de previsualización en redes sociales.

**Ejemplo**:
```html
<head>
    <meta charset="UTF-8">
    <title>CV de Juan Pérez - Desarrollador Web</title>
    
    <!-- SEO Básico -->
    <meta name="description" content="Curriculum Vitae de Juan Pérez, especializado en HTML y desarrollo web.">
    
    <!-- Open Graph (Para redes sociales) -->
    <meta property="og:title" content="CV de Juan Pérez">
    <meta property="og:description" content="Echa un vistazo a mi trayectoria profesional.">
    <meta property="og:image" content="https://tudominio.com/imagen-preview.jpg">
    
    <!-- Favicon (El iconito en la pestaña del navegador) -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
```

---

## 🚀 Tu Misión

Empieza por el **Paso 1**: Crea el archivo `index.html` en esta carpeta y escribe la estructura básica. Cuando lo tengas, avísame y pasamos a rellenarlo.
