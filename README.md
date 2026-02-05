# ASIX_0373_A01_MisApuntes
Alberto apruébame porfa ;)

Encabezados
Los encabezados se crean usando el símbolo #. Cuantos más # uses, menor será el nivel del encabezado.

## HOLA 
### ADIOS

# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4

*Texto en cursiva*  
**Texto en negrita**  
***Texto en negrita y cursiva***  
~~Texto tachado~~

Esto esta en __negrita__
Esto esta en **negrita**

Esto esta en _cursiva_
Esto esta en *cursiva*

__*TEXTO*__

LISTAS ORDENADAS Y DESORDENADAS

1. ELEMENTO 1
2. ELEMENTO 2 
3. ELEMENTO 3
   
* ELEMENTO 1
* ELEMENTO 2
* ELEMENTO 3


mfnsidfoisoifjioddsonPININIniefjifnsvicovjpiavrmcznivInvecsifioesfmiskvcniPEMIVNSONVOSINVLKnoiSFMWIORVNIOSN`pivrninvaoinsrfoinsvak


mfnsidfoisoifjioddsonPININIniefjifnsvicovjpiavrmcznivInvecsifioesfmiskvcniPEMIVNSONVOSINVLKnoiSFMWIORVNIOSN`pivrninvaoinsrfoinsvak

Bloques de Código
Para poder poner un ejemplo de un codigo html
Para bloques de código usa triple comilla invertida:

```
<p>Esto es un parrafo</p>
```

ENLACES 
[LINK](https://www.google.com/?zx=1759402167197&no_sw_cr=1/ "TITULO DEL ENLACE")

IMAGENES
![FOTONANO](./imagen1.jpg "FotoALONSO")


|NOMBRE|EQUIPO|POSICION|
|:-----------|:----------:|-----------:|
|MESSI|INTER MAIMI|MCO|
|PEDRI|FCB|MC|
|PAU CUBARSI|FCB|DFC|

:------- → Alineado a la izquierda
:------: → Centrado
-------: → Alineado a la derecha

COMANDO DE GIT PARA SUBIR COSAS A GITHUB

git init	Inicializa un nuevo repositorio

git add .	Añade todos los archivos al área de preparación

git commit -m "mensaje"	Guarda los cambios con un mensaje

git push origin main	Sube los cambios al repositorio remoto


HTML 

ESTRUCTURA 

```
<!DOCTYPE html>
<!-- Declara que este es un documento HTML5 -->

<html lang="es">
<!-- Elemento raíz, lang="es" indica idioma español -->

  <head>
    <!-- Metadatos del documento (no visibles en la página) -->
    <meta charset="UTF-8" />
    <!-- Codificación de caracteres UTF-8 para acentos y ñ -->
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Hace la página responsive (adaptable a móviles) -->
    
    <title>Título de la página</title>
    <!-- Aparece en la pestaña del navegador -->
  </head>

  <body>
    <!-- Todo el contenido visible va aquí -->
    <h1>Encabezado principal</h1>
    <p>Este es un párrafo.</p>
  </body>
</html>
```

Elementos Semánticos 

Estos elementos dan significado a las diferentes secciones de tu página:
```
<header>
  <!-- Encabezado de la página o sección -->
  <h1>Mi Sitio Web</h1>
  <nav>
    <!-- Menú de navegación principal -->
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#servicios">Servicios</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>
</header>

<body>
  <!-- Contenido principal único de la página -->
  <section>
    <!-- Sección temática del contenido -->
    <h2>Sección de Servicios</h2>
    <article>
      <!-- Contenido independiente y reutilizable -->
      <h3>Servicio 1</h3>
      <p>Descripción del servicio...</p>
    </article>
  </section>
</body>

<footer>
  <!-- Pie de página con info de contacto, copyright, etc. -->
  <p>&copy; 2024 Mi Sitio Web</p>
</footer>

```
Comentarios en HTML

<!-- Esto es un comentario en HTML -->
<!-- Los comentarios no se muestran en la página -->

LINK A OTRA PAGINA HTML
```
<a href="pagina2.html">Ir a Página 2</a>
<a href="pagina2.html" target="_blank">Abrir en nueva pestaña</a>
<a href="https://www.google.com" target="_blank" rel="noopener noreferrer">
  Google
</a>
```
IMAGEN 
```
<img src="imagen.jpg" alt="Descripción de la imagen" width="300" height="200" />
```
src: Ruta de la imagen

alt: Texto alternativo (obligatorio para accesibilidad)

width/height: Dimensiones en píxeles


TABLAS 
```
<table border="1">
  <!-- border="1" añade bordes visibles -->
  
  <caption>Título de la tabla</caption>
  <!-- Descripción de la tabla -->
  
  <thead>
    <!-- Encabezado de la tabla -->
    <tr>
      <!-- Table Row (fila) -->
      <th>Nombre</th>  <!-- Table Header (encabezado) -->
      <th>Edad</th>
      <th>Ciudad</th>
    </tr>
  </thead>
  
  <tbody>
    <!-- Cuerpo de la tabla con los datos -->
    <tr>
      <td>Ana</td>  <!-- Table Data (celda de datos) -->
      <td>22</td>
      <td>Madrid</td>
    </tr>
    <tr>
      <td>Carlos</td>
      <td>28</td>
      <td>Barcelona</td>
    </tr>
  </tbody>
  
  <tfoot>
    <!-- Pie de tabla (opcional, para totales o resúmenes) -->
    <tr>
      <td colspan="3">Total: 2 personas</td>
    </tr>
  </tfoot>
</table>
```
Combinar Celdas

```
<tr>
  <td rowspan="2">Esta celda ocupa 2 filas</td>
  <td>Celda normal</td>
</tr>
<tr>
  <td colspan="2">Esta celda ocupa 2 columnas</td>
</tr>
```
Atributos:

rowspan: Combina celdas verticalmente (filas)

colspan: Combina celdas horizontalmente (columnas)


FORMULARIO 

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASIX-0373-IntroHTML</title>
</head>
    <body>
    <!--A continuación he puesto un encabezado -->
        <h1>Introducción HTML</h1>
    
        <p>Lorem</p><strong>Impus dolor</strong>

    <form action="URLdeDestino" method="POST">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" required>
        
        <br>

        <label for="realname">Nombre real:</label>
        <input type="text" name="realname" id="realname">
        <input type="radio" name="carnet" value="carnetsi">
    </form>

  <table border="1">
    <thead>
        <tr>
            <td>ORDEN</td>
            <td>ATLETA</td>
            <td>TIEMPO</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>1</td>
            <td >Dani</td>
            <td>03:51:02</td>
        </tr>
        <tr>
            <td rowspan="2">2</td>
            <td colspan="2">Juan</td>
        </tr>
        <tr>
            <td>Juan</td>
            <td>03:51:02</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>ORDEN</td>
            <td>ATLETA</td>
            <td>TIMEPO</td>
        </tr>
    </tfoot>



    </table>
    <caption>Tabla </caption>

        <form action="URLdeDestino.html" method="GET">
            <label for="username">Username:</label>
            <input type="text" name="username" id="username" required>
            <br>
            <label for="realname">Nombre real:</label>
            <input type="text" name="realname" id="realname">
            <br>

            <fieldset>
                <legend>Carnet de conducir</legend>
                <label for="carnetsi">SI:</label>
                <input type="radio" name="carnet" value="carnetsi" id="carnetsi">
                <label for="carnetno">NO:</label>
                <input type="radio" name="carnet" value="carnetno" id="carnetno">
            </fieldset>
        <br>
            <fieldset>
                <legend>Gustos musicales</legend>
                <label for="pop">Pop:</label>
                <input type="checkbox" name="musica[]" value="pop" id="pop">
                <label for="heavy">Heavy:</label>
                <input type="checkbox" name="musica[]" value="heavy" id="heavy">
                <label for="pachanga">Pachanga:</label>
                <input type="checkbox" name="musica[]" value="pachanga" id="pachanga">
            </fieldset>
        <br>
        <label for="nacioniladidad">Nacionalidad:</label>
            <select name="Nacionalidad" id="nacioniladidad">
                <option value="españa">España</option>
                <option value="EEUU">EEUU</option>
                <option value="Uk">Uk</option>
                <option value="Japon">Japon</option>
            </select>
            <br>
            <label for="observaciones">Observaciones:</label><br>
            <textarea name="observaciones" id="observaciones" cols="25" rows="3" placeholder="Introduce aqui cualquier observacion que tengas"></textarea>
        <br>
            <button type="submit" name="Enviar" value="enviar">Enviar Datos</button>
        </form>
    </body>
</html>
```
```
<!-- Email con validación automática -->
<input type="email" name="email" required>

<!-- Contraseña (oculta caracteres) -->
<input type="password" name="password" required>

<!-- Número con límites -->
<input type="number" name="edad" min="18" max="99">

<!-- Fecha -->
<input type="date" name="fecha">

<!-- Color -->
<input type="color" name="color">

<!-- Archivo -->
<input type="file" name="archivo">

<!-- URL con validación -->
<input type="url" name="sitio-web">

<!-- Teléfono -->
<input type="tel" name="telefono">

<input 
  type="text" 
  name="ejemplo"
  placeholder="Texto de ayuda"
  required
  minlength="3"
  maxlength="20"
  pattern="[A-Za-z]+"
  disabled
  readonly
  value="Valor predeterminado"
>

```
placeholder: Texto de sugerencia

required: Campo obligatorio

minlength/maxlength: Longitud mínima/máxima

pattern: Validación con expresión regular

disabled: Desactiva el campo

readonly: Solo lectura (no editable)

value: Valor inicial del campo

# Apuntes de HTML y CSS

## Tabla de Contenidos

## ¿Qué es HTML?

**HTML** es el lenguaje estándar para crear páginas web y el responsable de mostrar contenido en el navegador.

Define la estructura y el contenido de una página mediante etiquetas como `<p>`, `<h1>`, `<body>`, etc.

**Importante:** HTML **NO es un lenguaje de programación** porque no tiene bucles, condiciones ni funciones. Su función es únicamente describir contenido, no darle estilo (CSS) ni comportamiento (JavaScript).

### Significado de las siglas HTML

- **HyperText:** texto que enlaza con otros recursos
- **Markup:** el contenido está organizado con etiquetas
- **Language:** tiene reglas y estructura propias

### Anatomía de un elemento HTML

Un elemento HTML suele estar formado por:

1. **Etiqueta de apertura** → `<p>`
2. **Contenido** → Hola
3. **Etiqueta de cierre** → `</p>`

```html
<p>Hola</p>
```

### Atributos

Las etiquetas pueden tener **atributos**, que añaden información extra (como `class`, `id`, `src`, `alt`, etc.).

- Los atributos siempre van en la **etiqueta de apertura**
- Tienen la forma: `nombre="valor"`

```html
<img src="imagen.jpg" alt="Descripción de la imagen">
```

### Elementos vacíos

Algunos elementos no tienen cierre ni contenido, como `<img>`, `<br>`, `<input>`. Por eso se llaman **elementos vacíos**.

---

## Estructura básica de HTML

Una página HTML básica incluye:
- Una declaración `DOCTYPE`
- Un elemento `html`
- Dentro de este, un `head` y un `body`

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Título de la página</title>
  </head>
  <body>
    <h1>Contenido de la página</h1>
  </body>
</html>
```

### Componentes principales

#### `<!DOCTYPE html>`
- Indica el tipo de documento
- Es un requisito técnico que debe estar al inicio de toda página HTML

#### `<html>`
- Contiene todo el contenido de la página
- Se conoce como el **elemento raíz**

#### `<head>`
Guarda información que no es visible en la página, como:

- **`<meta>`:** contiene información del documento (como el juego de caracteres `utf-8`, descripciones, palabras clave, etc.)
- **`<title>`:** título que aparece en la pestaña del navegador y en buscadores (importante para SEO)
- **`<link rel="icon">`:** agrega el favicon de la página
- Enlaces a CSS, JavaScript, u otros archivos externos
- Estilos CSS escritos dentro de `<style>`

#### `<body>`
Contiene el contenido principal de la página web que será visible para el usuario.

---

## Elementos HTML

### Elementos de bloque (block elements)

Ocupan todo el ancho disponible y separan el contenido en bloques.

**Ejemplos:**
- `<h1>` – `<h6>`
- `<p>`
- `<br>`
- `<hr>`
- `<blockquote>`
- `<pre>`
- `<div>`

### Elementos de línea (inline elements)

Se muestran dentro de una línea y no generan saltos.

**Ejemplos:**
- `<em>`
- `<strong>`
- `<q>`
- `<span>`
- `<cite>`
- `<abbr>`
- `<code>`

---

## Normas básicas de etiquetas HTML

1. Las etiquetas suelen venir en pares: `<p>` y `</p>`
2. Algunas son vacías (sin cierre): `<img>`, `<br>`, `<input>`
3. Las etiquetas deben anidarse correctamente
   ```html
   <p><b>Texto</b></p>
   ```
4. Los atributos van en la etiqueta de apertura y siguen el formato: `nombre="valor"`
   ```html
   <img src="imagen.jpg">
   ```

---

## Legibilidad y organización del código

Es importante escribir HTML claro para que otras personas (y tú mismo en el futuro) lo entiendan fácilmente.

### Comentarios

En un documento HTML podemos poner anotaciones que no se verán reflejadas cuando se mire la web con el navegador.

**Sintaxis:**
```html
<!-- Este es un comentario -->
```

### Indentación (sangría del código)

Usar una indentación consistente mejora la legibilidad del código.

### Organización en carpetas y archivos

Mantener una estructura ordenada de directorios facilita el mantenimiento del proyecto.

---

## Etiquetas básicas de HTML

### Encabezados (`<h1>` … `<h6>`)

Permiten especificar que ciertas partes del contenido son encabezados o subencabezados. Son **elementos de bloque**.

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Sección</h3>
```

### Párrafos (`<p>`)

Se utilizan para encerrar párrafos de texto. Son **elementos de bloque**.

```html
<p>Este es un párrafo de texto.</p>
```

### Salto de línea (`<br>`)

Permite agregar un salto de línea entre párrafos.

```html
<p>Primera línea<br>Segunda línea</p>
```

### Separador de línea (`<hr>`)

Permite agregar una línea horizontal divisoria. Útil para separar visualmente párrafos.

```html
<hr>
```

### Énfasis (`<em>`, `<strong>`)

Cuando queremos dar énfasis a una parte de texto para destacar su importancia.

```html
<p>Este texto es <em>importante</em> y este es <strong>muy importante</strong>.</p>
```

### Span (`<span>`)

Un `<span>` es un contenedor en línea que se usa para agrupar una pequeña parte de texto o contenido dentro de una línea, sin romper el flujo del texto.

A diferencia de `<div>`, que es un bloque, `<span>` no crea una nueva línea.

```html
<p>Este es un texto con <span style="color: red;">color rojo</span>.</p>
```

---

## Listas

### Listas desordenadas (`<ul>`)

Aquellas en las que el orden de los ítems no es relevante, como en una lista de compras.

Se puede escoger el símbolo tipográfico:

- `<ul type="disc">` → ●
- `<ul type="square">` → ■
- `<ul type="circle">` → ○

```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
```

### Listas ordenadas (`<ol>`)

Aquellas en las que el orden sí es relevante, como en una receta.

Se puede escoger el tipo de numeración:

- `<ol type="A">` → A, B, C...
- `<ol type="a">` → a, b, c...
- `<ol type="I">` → I, II, III...
- `<ol type="i">` → i, ii, iii...
- `<ol type="1">` → 1, 2, 3... (por defecto)

```html
<ol>
  <li>Primer paso</li>
  <li>Segundo paso</li>
  <li>Tercer paso</li>
</ol>
```

#### Atributos adicionales

- **`start="n"`:** fuerza la numeración a partir de un determinado valor
- **`value="n"`:** fuerza a que el elemento tenga el número de orden que indiquemos

```html
<ol type="i" start="10">
  <li>Elemento con numeración x</li>
  <li>Elemento con numeración xi</li>
</ol>
```

### Elementos de lista (`<li>`)

Cada elemento de la lista se coloca dentro de un elemento `<li>` (list item).

---

## Rutas en HTML

### Ruta Absoluta

Una ruta absoluta especifica la ubicación completa del archivo en la web, comenzando desde el dominio.

Es útil cuando el archivo se encuentra en un servidor diferente o en una ubicación específica de la web.

```html
<img src="https://www.example.com/images/logo.png" alt="Logo de Example">
```

### Ruta Relativa

Una ruta relativa especifica la ubicación del archivo en relación con la ubicación del documento actual.

Es útil para mantener una estructura de enlaces clara dentro de un mismo sitio web.

```html
<img src="images/logo.png" alt="Logo de Mi Sitio">
```

En este caso, `images/logo.png` indica que el archivo `logo.png` se encuentra en el directorio `images` dentro del mismo directorio que `index.html`.

---

## Imágenes

La etiqueta que utilizamos para insertar una imagen es `<img>`.

- Es un **elemento de línea**
- **No tiene etiqueta de cierre** (se cierra en sí misma)

### Atributos principales

- **`src`:** indica dónde está ubicada la imagen (URL externa o ruta local)
- **`alt`:** texto alternativo que se mostrará si el navegador no puede mostrar la imagen

```html
<img src="media/logo.png" alt="Logo de la web" />
```

---

## Enlaces (`<a>`)

El éxito de la WWW (World Wide Web) es la capacidad de saltar de un documento a otro mediante enlaces. El sistema que nos permite esta navegación se llama **hipertexto**.

La etiqueta HTML para crear enlaces es `<a>`. Es una **etiqueta de línea**.

### Atributo principal

- **`href`:** indica cuál es el destino del enlace

### Enlaces a páginas externas

```html
<p>
  <a href="https://m.joan23.fje.edu/" title="Joan XXIII">
    Jesuïtes Bellvitge – Joan XXIII
  </a>
</p>
```

### Enlaces a páginas locales

Si el enlace está dirigido a un documento local, podemos usar la ruta relativa:

```html
<div id="menu">
  <a href="index.html" title="Volver a la página de inicio">Inicio</a>
  <a href="secciones/presentaciones.html" title="Fotos de la web">Presentaciones</a>
  <a href="secciones/actividades.html" title="Actividades actuales">Actividades</a>
</div>
```

### Enlaces a etiquetas dentro del propio código HTML (Anclas)

Para navegar dentro de la misma página, creamos **anclas** usando el atributo `id`.

#### Crear el ancla

```html
<h2 id="seccion1">Sección 1</h2>
```

#### Enlazar al ancla

Los enlaces a anclas usan el valor del atributo `id` precedido del carácter `#`:

```html
<a href="#seccion1" title="Sección 1">Ir a la sección 1</a>
```

#### Enlazar a un ancla desde otro documento

```html
<a href="secciones.html#seccion1" title="Sección 1">Ir a la sección 1</a>
```

---

## Contenedores (DIV)

Un `<div>` en HTML es una caja o contenedor que sirve para agrupar diferentes elementos en una página web.

Es como un bloque donde puedes poner texto, imágenes, formularios, o cualquier otro contenido.

### ¿Para qué sirve?

1. **Organizar contenido:**
   - Dividir la página en secciones (cabecera, cuerpo, pie de página)

2. **Aplicar estilos:**
   - Darle un aspecto diferente a cada sección usando CSS

3. **Manipular con JavaScript:**
   - Trabajar con partes específicas del contenido

```html
<div class="contenedor">
  <h2>Título de la sección</h2>
  <p>Contenido de la sección</p>
</div>
```

---

## Formularios

Los formularios web permiten que el usuario envíe información a una aplicación.

Un formulario es código HTML que contiene **controles o campos** donde el usuario puede introducir datos.

### Tipos de controles comunes

- Campos de texto
- Campos de contraseña
- Botones de opción (radio buttons)
- Casillas de verificación (checkbox)
- Subida de archivos
- Listas de selección
- Áreas de texto
- Botones

Cada control debe tener el atributo **`name`**, con el cual se identifica el dato que se quiere enviar.

### Etiqueta `<form>`

Se utiliza para crear formularios que permiten al usuario enviar datos a un servidor o realizar alguna acción.

#### Atributos principales

- **`action`:** Define la URL donde se enviarán los datos del formulario
- **`method`:** Especifica el método de envío de datos (GET o POST)
- **`enctype`:** Define cómo se codifican los datos antes de ser enviados (necesario para subir archivos)
- **`target`:** Indica dónde se debe mostrar la respuesta al enviar el formulario
  - `_self` (por defecto): La respuesta se carga en la misma ventana
  - `_blank`: Abre la respuesta en una nueva pestaña o ventana

```html
<form action="/procesar" method="POST">
  <!-- Controles del formulario -->
</form>
```

### Etiqueta `<input>`

Se utiliza para crear diversos tipos de campos interactivos en un formulario.

#### Atributos principales

- **`type`:** Define el tipo de entrada (text, password, email, number, etc.)
- **`id`:** Identificador único para el campo
- **`name`:** Nombre del campo que se utiliza al enviar el formulario
- **`value`:** Valor predeterminado del campo
- **`placeholder`:** Texto que aparece cuando el campo está vacío
- **`required`:** Indica que el campo debe completarse antes de enviar el formulario
- **`disabled`:** Desactiva el campo
- **`readonly`:** Hace que el campo sea solo de lectura

```html
<input type="text" id="nombre" name="nombre" placeholder="Ingresa tu nombre" required>
```

### Input type="radio"

Botón de opción, se agrupa con otros del mismo nombre (solo se puede seleccionar uno).

```html
<input type="radio" id="opcion1" name="opciones" value="opcion1">
<label for="opcion1">Opción 1</label>

<input type="radio" id="opcion2" name="opciones" value="opcion2">
<label for="opcion2">Opción 2</label>
```

### Input type="checkbox"

Casilla de verificación, permite selecciones múltiples.

```html
<input type="checkbox" id="terminos" name="terminos" value="aceptado">
<label for="terminos">Acepto los términos y condiciones</label>
```

---

## Tablas

Las tablas en HTML permiten organizar datos en filas y columnas.

### Etiquetas principales

#### `<table>`
Define el inicio de una tabla.

**Atributos:**
- `border`: define el grosor del borde de la tabla
- `width`: especifica el ancho de la tabla

#### `<thead>`
Agrupa el encabezado de la tabla, normalmente contiene las etiquetas `<th>`.

#### `<tbody>`
Agrupa el cuerpo de la tabla. Útil para separar el contenido del encabezado y pie.

#### `<tfoot>`
Agrupa el pie de la tabla, generalmente utilizado para resumen o información adicional.

#### `<tr>`
Define una fila en la tabla.

**Atributos:**
- `align`: alinea el contenido
- `bgcolor`: define el color de fondo de la fila
- `valign`: alineación vertical

#### `<th>`
Define una celda de encabezado en una tabla.

**Atributos:**
- `colspan`: define cuántas columnas abarca la celda
- `rowspan`: define cuántas filas abarca la celda

#### `<td>`
Define una celda de datos dentro de una fila.

**Atributos:**
- `colspan`: abarca varias columnas
- `rowspan`: abarca varias filas
- `align`: alinea el contenido dentro de la celda

#### `<caption>`
Proporciona un título o descripción para la tabla. Se coloca justo después de la etiqueta `<table>`.

**Atributos:**
- `align`: alinea el título respecto a la tabla

### Ejemplo de tabla completa

```html
<table border="1" width="100%">
  <caption>Estudiantes del curso</caption>
  
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Apellido</th>
      <th>Nota</th>
    </tr>
  </thead>
  
  <tbody>
    <tr>
      <td>Juan</td>
      <td>Pérez</td>
      <td>8.5</td>
    </tr>
    <tr>
      <td>María</td>
      <td>García</td>
      <td>9.0</td>
    </tr>
  </tbody>
  
  <tfoot>
    <tr>
      <td colspan="2">Promedio</td>
      <td>8.75</td>
    </tr>
  </tfoot>
</table>
```

