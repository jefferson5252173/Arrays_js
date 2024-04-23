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