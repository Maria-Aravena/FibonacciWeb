# FibonacciWeb

En este proyecto se procederá a crear un modesto servidor http que acepte un valor "n".
Dicho valor se utilizará para entregar los valores "n" y "n-1" de la Frecuencia de Fibonacci.

(27/12/2018)
Desarrollo:
Actualmente el servicio HTTP implementado consiste en un archivo html en el cuál se encuentran ingresadas funciones en lenguaje Javascript.

Para la implementación de la consulta en Fibonacci se utilizó una función matemática que considera la ecuación de recurrencia de la secuencia de fibonacci:

		F(n) = (1/sqr(5)) * ( Math.pow(((1 + sqr(5))/2), n) - Math.pow( ((1 - sqr(5))/2), n) ).

Dada a la función utilizada, esta secuencia considera:

Posición 1: 1
Posición 2: 1
Posición 3: 2
...

En caso de que el n ingresado sea 1, la ecuación considera una posición 0 con el valor 0 de la secuencia de Fibonacci.


Dependencias: Ninguna.

Como Ejecutar:
	Actualmente el archivo html puede descargarse y abrirse en un navegador.

Como utilizar el servicio:
	-Descargar el archivo html.
	-Abrir el archivo html en un navegador.
	-Ingresar un valor positivo.


TODO: Impedir el uso de números decimales en la formula.



