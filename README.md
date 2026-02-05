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

## APUNTES HTML

### ¿Qué es HTML?

HTML es el lenguaje estándar para crear páginas web y el responsable de mostrar contenido en el navegador.
Define la estructura y el contenido de una página mediante etiquetas como <p>, <h1>, <body>, etc.

HTML NO es un lenguaje de programación porque no tiene bucles, condiciones ni funciones. Su función es únicamente describir contenido, no darle estilo (CSS) ni comportamiento (JavaScript).

Significado de las siglas HTML

HyperText: texto que enlaza con otros recursos
Markup: el contenido está organizado con etiquetas
Language: tiene reglas y estructura propias

Anatomía de un elemento HTML
Un elemento HTML suele estar formado por:

Etiqueta de apertura → <p>
Contenido → Hola
Etiqueta de cierre → </p>

```
<p>Hola</p>
```

