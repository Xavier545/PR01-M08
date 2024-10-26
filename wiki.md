# MarkDown Wiki
Markdown es un lenguaje de marcas utilizado para agregar un formato al texto simple en documentos o paginas web, tiene una
syntaxis sencilla que le permite un aprendizaje accesible al usuario promedio.
## Uso
A continuacion unos ejemplos de como usar las herramientas que proporciona Markdown para el formato.
### Titulos
Para hacer de una linea de texto un titulo del documento solo hace falta añadir al inicio de la linea la cantidad de almohadillas que sean necesarias para el titulo deseado, hay 6 en total, uno mas pequeño que el anterior y los 2 primeros ademas de ser los de mayor tamaño, estos generan una linea separatoria entre el titulo y el contenido, puedes tomar de ejemplo los dos titulos de Markdown Wiki y Uso que son h1 y h2 respectivamente.
```Markdown
# Titulo Principal [h1]
## Titulo Secundario [h2]
### Titulo 3 [h3]
#### Titulo 4 [h4]
##### Titulo 5 [h5]
###### Titulo 6 [h6]
```
### Listas
Las listas son muy intuitivas de hacer, para empezar hay 2 tipos de listas, ordenada y desordenadas, mientras que las listas desordenadas siempre empezaran con un simple punto, las ordenadas empezaran con un index marcando su orden en ella, en el caso de las desordenadas solo hace falta poner un guion para empezar un elemento de esta lista y para las ordenadas cualquier numero, hay que tener en cuenta que el index se sobrepone al numero que hayas escrito, aqui tienes una vista las listas escritas y procesadas para que veas la super posicion del index.
```Markdown 
1. ejemplo1
2. ejemplo2
4. ejemplo3 // index mal puesto a proposito
3. ejemplo4

- Ejemplo1
- Ejemplo2
- Ejemplo3
- Ejemplo4
```
1. ejemplo1
2. ejemplo2
4. ejemplo3
3. ejemplo4

- Ejemplo1
- Ejemplo2
- Ejemplo3
- Ejemplo4
### Negrita y Cursiva
Para poner el texto en formato **Negrita**, solo es necesario abrir y cerrar unos dobles asteriscos para que el contenido cambie de formato, y para la _Cursiva_ debes de rodear de barra baja el contenido que quieres formatear, estos 2 formatos se pueden usar al mismo tiempo y solo debes de rodear de dichos caracteres el _**Contenido**_ al mismo tiempo y sin un orden en especifico.
```Markdown 
**Negrita**
_Cursiva_
**_Negrita_** y _**Cursiva**_
```
**Negrita**

_Cursiva_

**_Negrita_** y _**Cursiva**_

### Tablas
Para hacer tablas se debe de especificar cada columna rodeandolo con el caracter "|" y dentro su contenido, para hacer un encabezado simplemente hay que hacer celdas con exclusivamente los caracteres "-", la cantidad de estos caracteres no es influyente en el resultado, tambien es posible modificar la orientacion del texto con el caracter ":" al final o inicio de una celda de declaracion de encabezado, para centrar el texto hay que poner el caracter en ambos lugares, la celda que ocupe mas espacio horizontal en la columna sera el que defina la anchura de toda la columna, si este supera el limite de anchura en el contenedor en el que esta, este aunmentara una linea en por debajo para incluir todo el contenido.
```Markdown
| Encab. 1 | Encab. 2 | Encab. 3 |
|:---------------|:-----:|----------------------------:|
| Fila 1, Col 1 | Fila 1, Col 2 | F1C3 |
| Fila 2, Col 1 | Fila 2, Col 2 | F2C3 |
| ------------------Fila 3, Col 1 | -----------Fila 3, Col 2----------- | F3C3------------------ |
```
| Encab. 1 | Encab. 2 | Encab. 3 |
|:---------------|:-----:|----------------------------:|
| Fila 1, Col 1 | Fila 1, Col 2 | F1C3 |
| Fila 2, Col 1 | Fila 2, Col 2 | F2C3 |
| ------------------Fila 3, Col 1 | -----------Fila 3, Col 2----------- | F3C3-------------------------------------------------------------------------------------------------------------------- |

### Bloques de codigo
Este elemento sirve para mostrar un en un bloque un contenido en un lenguaje en especifico, hasta ahora en los ejemplo hemos visto bloques de codigo escritos en Markdown pero es posible utilizar otros tipos de bloque para una mejor demostracion en coloreado de sintaxys. La definicion del bloque se basa en una primera linea abriendo con 3 caracteres "`" y el nombre del lenguaje, el contenido que es el codigo y la linea que lo cierra son simplemente otros 3 acentos graves como los que lo abrieron, como ejemplo en este siguiente bloque de SQL.
```MarkDown
Esto esta con almohadillas para que Markdown no lo interprete como otro bloque 
# ```SQL
# SELECT * FROM Tabla
# ```
```

```SQL
SELECT * FROM Tabla
```
### HTML
Es posible utilizar las etiquetas de HTML dentro de Markdown y estas seran procesadas, esta puede ser una alternativa para las mismas funciones de Markdown.
```Markdown
<h1>Este es un titulo h1 en HTML</h1>
<p>Y este es un parrafo en html y lo siguiente es una linea de separacion de contenido</p>
<hr>
```
<h1>Este es un titulo h1 en HTML</h1>
<p>Y este es un parrafo en html y lo siguiente es una linea de separacion de contenido</p>
<hr>
