# parcial-lenguajes
Parcial 1 – Lenguajes de Programación

Este repositorio contiene la resolución del Parcial 1 de la materia Lenguajes de Programación.
Cada punto fue implementado en un lenguaje diferente, de acuerdo con lo solicitado en el examen.

Estructura del repositorio

El proyecto está organizado en carpetas según los puntos del parcial:

python/ → contiene las soluciones de los puntos 1 y 2, que son autómatas finitos deterministas (DFA) implementados en Python. Dentro están los archivos abc_dfa.py, abd_dfa.py e id_dfa.py.

java/ → corresponde al punto 3, donde se implementa una calculadora que calcula la raíz cúbica de números reales. Incluye el archivo AFD.java y un Makefile para compilar y ejecutar.

punto4/ → contiene la implementación del algoritmo recursivo de Euclides en dos lenguajes diferentes para comparar rendimiento:

punto4/c/ → implementación en C (paradigma imperativo).

punto4/haskell/ → implementación en Haskell (paradigma declarativo).

punto5/ → implementación de la serie de Maclaurin para la función exponencial e^x usando ANTLR4 y Java. Contiene los archivos Maclaurin.g4, Eval.java, Main.java y un Makefile para compilar y ejecutar.

Descripción de cada punto

Puntos 1 y 2 – DFA en Python
En esta carpeta se encuentran programas que implementan autómatas finitos deterministas con diferentes reglas. Se pueden ejecutar con Python 3.

Punto 3 – Calculadora raíz cúbica en Java
Se desarrolla un programa que utiliza Flex y Bison en Java para calcular la raíz cúbica de números reales. El programa recibe una cadena de entrada y devuelve el resultado por consola.

Punto 4 – Algoritmo de Euclides
Aquí se compara el algoritmo recursivo de Euclides entre dos paradigmas:

Lenguaje imperativo: C.

Lenguaje declarativo: Haskell.
La comparación permite observar diferencias de rendimiento y estilo de programación.

Punto 5 – Serie de Maclaurin con ANTLR
Se implementa un analizador con ANTLR4 y Java para calcular los primeros n términos de la serie de Maclaurin para e^x. El usuario debe ingresar el valor de x y el número de términos n, y el programa devuelve la aproximación correspondiente.
