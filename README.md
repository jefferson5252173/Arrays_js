# Arrays_js

un array es una zona de almacenamiento continuo, donde se ouede introducir varios valores cada uno de lleos ubicados por la pocsicion que ocupa enen array.
- tambien son denominados o llamados arreglos o vectorers, y cunado son de dos dimensiones son llamados matrices
- los arrays nos brindan la capacidad de almacenar una coleccion de elementos y acceder a ellos de manera individual- cada elemento se identifica mediante su posicion en el array denminada **indice**y estos indices son siempre secuenciales 
- en javascrip son altamente flexibles en terminos de los difernete tipos de datos que podemos almacenar encada posicion del array

1. Declarando un array con elementos en linea 
```Javascript
let miArray = [1, 2, 3];
consle.log(miArray);
```
2. Declarando un array con la sintaxis **new Array()**
```Javascript
let miArray2 = new Array(1, 2, 3);
consle.log(miArray2);
```
3. Declarando un arra con un tamaño especifico utilizando la sintaxis **new Array** y asignamos valores despues:

```Javascript
let miArray2 = new Array(3);
miArray[0]= 1;
miArray[1]= 2;
miArray[2]= 3;
consle.log(miArray3);
```
4. declarando un array con elementos de diferentes tipos de datos
```Javascript
let miArray = [1, "dos", true, {nombre: "juan", edad:30}];
consle.log(miArray4);
```

## accediendo a la informacion de un array 
### propiedad length
- devuelve la cantidad de elementos del array

### operador pos
- permite acceder para leer o modificar e elemento pos del array

### metodo at pos
- devuelve el elemnto de la posicion pos. El parametro admite valores negativos, lo que significa que empieza a contar por el final del array.

```Javascript
const letters = ["A", "B", "C"]
Cosole.log (letters.length);
console.log(letters)
```
## añadir o eliminar elementos
- push(elel, ele2); añade uno o varios elementos eafinal del arrray, devuelve el tamaño del array.

del array.

```Javascript
 let miArray = [1, 2, 3];
 miArray.push(4);//agrega el elemnto 4 al final del array
 console.log (miArray);
```
- pop(): devuelve el untimo elemento del array y lo elimina 



```Javascript
 let miArray = [1, 2, 3];
 miArray.pop();// elimina el ultimo elemento del array
 console.log (miArray);
```
-unshift(elemto2, elemto2): añade uno o varios elemetos al inicio devolviendo el tamaño de array despues de añadidios 

```Javascript
 let miArray = [1, 2, 3];
 miArray.unshitf(0);//agrge el elemento 0 al inicio del array del array
 console.log (miArray);
```

- SHIFT : DEVUELVE EL PRIEMR ELEMENTO DEL ARRAY Y LO ELIMINA

```Javascript
 let miArray = [1, 2, 3];
 miArray.unshitf(0);//agrge el elemento 0 al inicio del array del array
 console.log (miArray);
```

- CONCAT (ELEM1, ELEE2 )

```Javascript
 let miArray = [1, 2, 3];
 miArray.unshitf(0);//agrge el elemento 0 al inicio del array del array
 console.log (miArray);
```
- split(separador): a partir deuna cadena, crear un array dividiendo dicha cadena en elementos delimitados por separador

```Javascript
 let miArray = [1, 2, 3];
 miArray.unshitf(0);//agrge el elemento 0 al inicio del array del array
 console.log (miArray);
```

- join(separador): a partir de un array, crea una cadena separando cada elemento con el separador.
```Javascript
let miArray = "Hola,", "¿cómo", "estás?"];
let miString = miArray.join(" ");
console.log(miString);
```
## Búsqueda de elementos en un array
includes (elemento): devuelve true o false si el elemento existe o no dentro del array indexOf(elemento): devuelve la posición de la primera aparición del elemento. Si no
existe, devuelve -1. lastIndexOf(elemento): devuelve la posición de la ultima aparición del elemento. Si
no existe, devuelve -1. ## Modificar el array o crear fragmentos
- slice(inicio, fin): devuelve un array con los elementos desde la posición inicio hasta la posición fin, ambos excluidos.
## Ordenar elementos de un array
reverse(): invierte el orden de los elementos del array
sort(): ordena el array alfabeticamente
sort(criterio): ordena el array con el criterio determinado por la función criterio.
## Ordenar elementos de un array
reverse(): invierte el orden de los elementos del array
sort(): ordena el array alfabeticamente
sort(criterio): ordena el array con el criterio determinado por la función criterio.

## Borrar elementos de un array
Se puede borrar el contenido de un elementode un array poniendo su valor a null o
asignando una cadena vacía " "
Para eliminar completamente un elemento del array se utiliza el operador delete.
## Recorrido de un array
1. Recorrer con un bucle clásico, pasando por todos los elementos.
```Javascript
var dias = ["lunes", "martes", "miércoles", "jueves", "viernes", "sábado", "domingo"]; for(i=0;i<dias.lengt;
{
console.log(dias[i]);
}
2. Recorrer con un bucle clásica, pasando por todos los elementos.
Javascript
var dias ["lunes", "martes", "miércoles", "jueves", "viernes", "sábado", "domingo"]; for(i=0;i<dias.lengt;i++)
{
console.log(dias[i]);
}

# Ejercicios
1. Dada una lista de números separados por coma, calcular la suma, el mayor, el menor y la media de todos.
2. Introducir dos cadenas con elementos seperados por coma, y con un botón concatenar las dos cadenas y mostrarlas en pantalla.
3. Introducir uno a uno los elementos en un array a través de un boton. Con otro botón se va eliminado el último elemento. Siempre que se pulse alguno de los botones de debe mostrar el contenido del array.