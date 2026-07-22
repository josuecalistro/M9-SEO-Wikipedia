# Proyecto Final - SEO, Git y Buenas Prácticas Web

## Descripción del proyecto

Este proyecto consiste en el desarrollo de un sitio web utilizando HTML5 y CSS3 aplicando buenas prácticas de SEO On-Page, accesibilidad, optimización de imágenes y organización profesional del código mediante Git y GitHub.

Durante el desarrollo se implementó un flujo de trabajo basado en ramas para mantener una correcta organización de cambios y facilitar el control de versiones.

---

# Tecnologías utilizadas

- HTML5
- CSS3
- Git
- GitHub
- Visual Studio Code

---

# Implementación SEO

## SEO On-Page

Se aplicaron las siguientes mejoras:

- Uso correcto de la etiqueta `<title>`.
- Implementación de `<meta name="description">`.
- Uso jerárquico de encabezados:
  - `<h1>` para el título principal.
  - `<h2>` para secciones.
  - `<h3>` para subsecciones.

- Implementación de etiquetas semánticas HTML5:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

Estas etiquetas permiten que los motores de búsqueda comprendan mejor la estructura del contenido.

---

# Optimización de imágenes

Las imágenes utilizadas en el proyecto fueron optimizadas para mejorar el rendimiento.

## Buenas prácticas aplicadas:

- Uso de formatos comprimidos.
- Reducción del peso de archivos.
- Implementación del atributo `alt`.
- Mejora de accesibilidad.

Ejemplo:

```html
<img 
src="img/producto.png" 
alt="Producto destacado del catálogo">
```

El atributo `alt` permite:

- Mejor accesibilidad para lectores de pantalla.
- Mejor interpretación del contenido por parte de Google.
- Mejora de la experiencia del usuario.

---

# Validación HTML

Antes de la entrega final se realizó una revisión del archivo `index.html`.

Se corrigieron errores relacionados con etiquetas de imágenes:

Antes:

```html
<img src="imagen.png">
```

Después:

```html
<img 
src="img/imagen.png"
alt="Descripción de la imagen">
```

Correcciones realizadas:

- Se agregaron atributos `alt` obligatorios.
- Se verificaron rutas de archivos.
- Se revisó la correcta apertura y cierre de etiquetas.
- Se eliminó código innecesario.

El documento HTML quedó validado y sin errores de sintaxis.

---

# Flujo de trabajo Git Flow

Para organizar el desarrollo se utilizó un flujo basado en ramas.

## Ramas utilizadas

### main

Contiene la versión estable y final del proyecto.

### develop

Rama utilizada para integrar nuevas funcionalidades antes de pasar a producción.

### feature-seo

Utilizada para implementar:

- Etiquetas SEO.
- Meta descripción.
- Mejoras semánticas HTML.

### feature-images

Utilizada para:

- Optimización de imágenes.
- Implementación de atributos alt.
- Mejoras de accesibilidad.

---

# Proceso de desarrollo

El flujo aplicado fue:

1. Creación del repositorio en GitHub.

2. Creación de la rama principal:

```
main
```

3. Creación de rama de desarrollo:

```
develop
```

4. Creación de ramas específicas:

```
feature-seo
feature-images
```

5. Desarrollo de cambios en cada rama.

6. Creación de Pull Requests para revisar modificaciones.

7. Unión de ramas mediante merge.

8. Actualización final de la rama main.

---

# Pull Requests realizados

Los cambios fueron organizados mediante Pull Requests.

Ejemplo:

## Pull Request 1

Nombre:

```
Implementación SEO On-Page
```

Cambios realizados:

- Agregado title.
- Agregada meta description.
- Mejorada estructura HTML.

---

## Pull Request 2

Nombre:

```
Optimización de imágenes y accesibilidad
```

Cambios realizados:

- Corrección de imágenes.
- Incorporación de atributos alt.
- Mejora del rendimiento.

---

# Historial de commits

Los commits fueron realizados utilizando mensajes claros y descriptivos.

Ejemplo:

```
Initial commit - creación del proyecto
```

```
Agrega estructura HTML semántica
```

```
Implementa estilos CSS principales
```

```
Agrega etiquetas SEO On-Page
```

```
Optimiza imágenes y agrega atributos alt
```

```
Corrige errores de sintaxis HTML
```

```
Actualiza documentación README
```

---

# Buenas prácticas aplicadas en Git

Durante el desarrollo se aplicaron las siguientes prácticas:

- Commits pequeños y específicos.
- Nombres descriptivos.
- Uso de ramas independientes.
- Revisión mediante Pull Requests.
- Conservación de una rama main estable.

---

# Estructura del proyecto

```
Proyecto
│
├── index.html
│
├── css
│   └── styles.css
│
├── img
│   ├── imagen1.png
│   ├── imagen2.png
│
└── README.md
```

---

# Conclusión

El proyecto integra buenas prácticas de desarrollo web, SEO y control de versiones.

La implementación de una estructura HTML correcta, imágenes optimizadas, accesibilidad mediante atributos alt y una metodología organizada con Git Flow permiten crear un sitio más eficiente, mantenible y preparado para los motores de búsqueda.

El uso de ramas y Pull Requests permitió trabajar de manera profesional, simulando un entorno real de desarrollo colaborativo.