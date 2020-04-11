---
layout: default
title: 💻 Programación
nav_order: 2
has_children: true
has_toc: false
---


# Programación

## Algoritmos en pseudocódigo
### Algoritmo
### Pseudocódigo
*El pseudocódigo es un lenguaje de especificación de algoritmos.* El uso de tal lenguaje se hace el paso de la codigicación final (esto es, la traducción a un lenguaje de programación) relativamente fácil.

El pseudocódigo nació como un lenguaje similar al inglés y era un medio de representar básicamente las estructuras de control de programación estructurada. Se considera un *primer borrador* dado que el pseudocódigo tiene que traducirse posteriormente a un lenguaje de programacíon. El pseudocódigo no puede ser ejecutado por una computadora. La *ventaja del pseudocódigo* es que en su uso, en la planificación de un programa, el programador se puede concentrar en la lógica y en las [estructuras de control](## Estructuras de control) y no preocuparse de lasreglas de un lenguaje específico. Es también fácil modificar el pseudocódigo si se descubren errores o anomalías en la lógica del programa,  mientras que en muchas ocaciones suele ser difícil el cambio de la lógica, una vez que está codificado en un lenguaje de programamcíon.

Una represantación en pseudocódigo de un problema de cálculo del salario neto de un trabajador es la siguiente:

<div class="code-example" markdown="1">
**start**
<br>	//cálculo de impuesto y salarios
<br>	**read** nombre, horas, precio
<br>	salario ⬅️ horas * precio
<br>	tasas ⬅️ 0.25 * salario
<br>	salario_neto ⬅️ salario - tasas
<br>	**write** nombre, salario, tasas, salario
<br>**end**
</div>





El algoritmo comienza con la palabra **start** y finaliza con **end**, en inglés (en español, **inicio**, **fin**).  Entre estas palabras, solo se escribe una instrución o acción por linea.

La linea precedoda por **//** se denomina *comentario*. Es una información al lector del programa y no realiza ninguna instrucción ejecutable, sólo tiene efecto de documentación interna del programa.

Otro ejemplo aclaratorio en el uso del pseudocódigo prodía ser un sencillo algoritmo del arranque marinl de un coche.

<div class="code-example" markdown="1" style="background-color:lightgray">
**inicio**
	//arranque matinal de un coche
	introducir la llave de contacto
	girar la llave de contacto
	psiar el acelerador
	oir el ruido del motor
	pisar de nuevo el acelerador
	esperar unos instantes a que se caliente el motor
**fin**
</div>
### Diagramas de flujo

Un diagrama de flujo (*flowchart*) es una de las técnicas  de representación de algoritmos más antigua y a la vez mas utilizada, aunque su empleo ha disminuido considerablemente, sobre todo, desde la aparición de lenguajes de programamción estructurados. Un diagramam de flujo es un diagrama que utiliza símbolos (cajas) estándar y que tiene los pasos de algoritmo escritos en esas cajas unidas por flechas, denominadas *líneas de flujo*, que indican la secuenci en que se debe ejecutar.

![Símbolos de diagrama de flujo](/Inteligencia-Artifical/docs/programacion/img/1.png)

## Estructuras  de control

## Estructuras de datos: arreglos, registros, pilas, colas, listas ligadas, recursividad, árboles y grafos

## Búsquedas en profundidad y amplitud

## Algoritmos de Ordenamiento

