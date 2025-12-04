#  CRUDScope – HTML MediaPanel

## 📌 Descripción general

Este proyecto es una página web enfocada en la **gestión y subida de tareas**.
El usuario puede llenar un formulario, enviar una tarea y visualizarla en una **tabla de registros**.
Además, la página incluye una sección de **multimedia** donde se integran y reproducen elementos como **audio** y **video**.

---

## Investigación de etiquetas

###  **1. Estructura**

**Etiquetas:** `html`, `head`, `body`, `title`, `base`, `meta`
**Uso:** Definen la estructura fundamental de un documento HTML.
**Caso típico:** Crear la base del documento, establecer título, codificación (`meta charset`), y rutas relativas (`base href`).

---

###  **2. Semánticas**

**Etiquetas:** `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `address`, `time`
**Uso:** Dan significado al contenido, mejorando accesibilidad y SEO.
**Caso típico:** Organizar una página en encabezado, navegación, contenido principal y pie de página.

---

###  **3. No semánticas**

**Etiquetas:** `div`, `span`
**Uso:** Contenedores genéricos sin significado propio.
**Caso típico:** Divisiones para maquetación o estilos cuando ninguna etiqueta semántica aplica.

---

###  **4. Texto y formato**

**Etiquetas:** `h1–h3`, `p`, `strong`, `em`, `u`, `abbr`
**Uso:** Presentan títulos, párrafos y resaltan textos.
**Caso típico:** Poner títulos (`h1`), resaltar palabras importantes (`strong`) o abreviaciones (`abbr`).

---

###  **5. Tablas**

**Etiquetas:** `table`, `tr`, `th`, `td`
**Uso:** Mostrar información estructurada en filas y columnas.
**Caso típico:** Registrar tareas subidas por el usuario en una tabla ordenada.

---

### **6. Formularios**

**Etiquetas:** `form`, `label`, `input`, `textarea`, `button`
**Uso:** Permiten al usuario enviar datos al sistema.
**Caso típico:** Formulario para registrar una nueva tarea con texto y descripción.

---

### 🔷 **7. Multimedia**

**Etiquetas:** `img`, `audio`, `video`, `source`
**Uso:** Integran elementos multimedia directamente en la página.
**Caso típico:** Reproducir un audio o video sin plugins externos.

---

##  Diferencias entre etiquetas semánticas y no semánticas

###  **Etiquetas semánticas**

* Mejoran la accesibilidad, el SEO y la estructura lógica del documento.

**Ejemplos y cuándo usarlas:**

* `header` para un encabezado.
* `nav` para un menú.
* `section` para dividir contenido por temas.

###  **Etiquetas no semánticas**

* No aportan significado: solo sirven para estructura o estilos.
* Se usan cuando no existe una etiqueta semántica adecuada.

**Ejemplos:**

* `div` para agrupar elementos de diseño.
* `span` para textos pequeños dentro de una línea.

---

##  Enfoque en etiquetas poco comunes

###  **1. `<base>`**

Define la **URL base** que usarán todos los enlaces relativos del documento.

* Si colocas `<base href="https://ejemplo.com/">`, cualquier enlace sin dominio se abrirá basado en esa URL.
* Útil para proyectos con muchos enlaces relativos.

---

###  **2. `<abbr>`**

Representa una **abreviatura** o sigla.
Permite mostrar el significado al pasar el cursor.

```html
<abbr title="Create, Read, Update, Delete">CRUD</abbr>
```

---

###  **3. `<time>`**

Representa fechas u horas en un formato legible por máquinas.

```html
<time datetime="2025-12-03">3 de diciembre de 2025</time>
```

Se usa en blogs, eventos o registros donde la fecha es importante.

---

###  **4. Ventajas de las etiquetas multimedia (`audio`, `video`)**

* Reproducción directa sin plugins (como Flash).
* Controles nativos (play, pausa, volumen).
* Permiten múltiples formatos con `<source>`.
* Mayor compatibilidad y accesibilidad.

---

##  Referencias

* Documentación oficial:

  * [https://developer.mozilla.org/es/docs/Web/HTML](https://developer.mozilla.org/es/docs/Web/HTML)
  * [https://html.spec.whatwg.org/](https://html.spec.whatwg.org/)
* Artículos de referencia:

  * W3Schools – HTML Tutorial
  * FreeCodeCamp – HTML5 Guide

