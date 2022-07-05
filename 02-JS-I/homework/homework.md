# 02-JS-I

## Conceptos

* Variables:  
Las variables son un tipo de "cajita" a esta cajita le pones una  
etiqueta para diferenciarla de otras cajitas por ejemplo si quieres almacenar  
juguetes le puedes poner a la etiqueta el nombre de juguetes y ya que tienes tu  
cajita con su etiqueta entonces puedes ir guardando dentro de ella dichos "juguetes"
entonces despues cuando quieras buscar esos juguetes lo unico que tienes que hacer
es buscar la caja (o variable) con el nombre juguetes.

Dicho de otra forma, una variable es un espacio en la memoria de la computadora y que es echa para alamcenar un valor. Con codigo se expresa de esta forma:

```Javascript
var juguete = "Pelota";
```
* Strings  
Los strings son un tipo de dato que se escriben en secuencia (o sea uno detras de otro) y sirven para representar texto. Por regla general estan encerrados entre comillas.
```
"Este es un string", 'Este tambien es un string', 'A' el anterior es un string
```
* Funciones.  
Las Funciones son fragmentos de codigo que hacen una accion especifica y pueden regresar un valor. Ademas que pueden ser usadas en mas de una ocacion gracias a que se pueden usar parametros son vesatiles y muy practicas.  
```Javascript
Ejemplo de una funcion: 
function saludo(nombre){
  return  'Hola ' + nombre;
}
saludo('Javier');
Hola Javier
```
* Declaraciones if  
If es una palabra en ingles que en espanol significa Si y sirve  para tomar deciciones de acuerdo cierta condicion. Por ejemplo Si hoy es Domingo no voy a la escuela.Expresado en codigo seria de la siguiente forma:  
```Javascript 
let dia = 'Domingo';
if(dia === 'Domingo'){
  'No voy a trabajar'
}
```

* Valores booleanos.  
Los booleanos nos ayudan con la logica del programa y declarar si el resultado de una funcion es falsa o verdadera y actuar en consecuencia.
