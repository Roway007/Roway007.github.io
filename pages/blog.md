---
layout: default
tagline:
permalink: blog.html
---
<br><br>

# Blog

**En este semestre he podido diferenciar la utilidad de los bucles While, Do while, For.**


**While**

Estos bucles se utilizan cuando queremos repetir la ejecución de unas sentencias un número indefinido de veces, siempre que se cumpla una condición. Se más sencillo de comprender que el bucle FOR, pues no incorpora en la misma línea la inicialización de las variables su condición para seguir ejecutándose y su actualización. Sólo se indica, como veremos a continuación, la condición que se tiene que cumplir para que se realice una iteración.

**while (condición){ 
   	//sentencias a ejecutar 
}**

Un ejemplo de código donde se utiliza este bucle se puede ver a continuación.

**var color = "" 
while (color != "rojo"){ 
   	color = prompt("dame un color (escribe rojo para salir)","") 
}**


**DoWhile**

El bucle do...while es la última de las estructuras para implementar repeticiones de las que dispone en Javascript y es una variación del bucle while visto anteriormente. Se utiliza generalmente cuando no sabemos cuantas veces se habrá de ejecutar el bucle, igual que el bucle WHILE, con la diferencia de que sabemos seguro que el bucle por lo menos se ejecutará una vez.

Este tipo de bucle se introdujo en Javascript 1.2, por lo que no todos los navegadores los soportan, sólo los de versión 4 o superior. En cualquiuer caso, cualquier código que quieras escribir con DO...WHILE se puede escribir también utilizando un bucle WHILE, con lo que en navegadores antiguos deberás traducir tu bucle DO...WHILE por un bucle WHILE.

La sintaxis es la siguiente:

**do { 
   	//sentencias del bucle 
} while (condición)**

El bucle se ejecuta siempre una vez y al final se evalúa la condición para decir si se ejecuta otra vez el bucle o se termina su ejecución.


Veamos el ejemplo que escribimos para un bucle WHILE en este otro tipo de bucle.

**var color 
do { 
   	color = prompt("dame un color (escribe rojo para salir)","") 
} while (color != "rojo")**



**For**

El ciclo for es muy importante en programación debido a que es un ciclo que repite un conjunto de instrucciones mientras una condición es verdadera, pero, a diferencia de los ciclos if-else y while, normalmente en el ciclo for tiene aplicación cuando conocemos el número de veces que se repetirá el ciclo.

Cuando requieras programar integrales, cálculos estadísticos, recorrer matrices, listas, estructuras de datos, la lectura de archivos, incluso el recorrido de directorios, etc, normalmente utilizarás el ciclo for. El ciclo for también es frecuentemente referido como «bucle» for.


**for (Expresión-de-inicio; Condición; incremento)
{
	Instrucciones del ciclo.
}**

