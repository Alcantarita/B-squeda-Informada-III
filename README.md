# B-squeda-Informada-III
Practica 6

Este repositorio contiene la implementación del algoritmo de Recocido Simulado para encontrar los valores de (x, y) que minimizan la función de Himmelblau en el rango [-5, 5]. Esta práctica es parte del curso de Inteligencia Artificial y explora técnicas de optimización en problemas no lineales.

Descripción
El algoritmo de recocido simulado es un método estocástico utilizado para aproximar el óptimo global de una función en un espacio de búsqueda. En este caso, aplicamos el recocido simulado para minimizar la función de Himmelblau, que tiene múltiples mínimos locales.

La función de Himmelblau está definida como: f(x,y)=(x2+y−11)2+(x+y2−7)2

Parámetros de la ejecución
Límites del dominio: [-5, 5] para ambas variables x e y.
Temperatura inicial: 10,000.
Factor de enfriamiento: 0.99.
Número de iteraciones: 10,000.

Para ejecutar el código, asegúrate de tener instalado Python 3.x y numpy: python BúsquedaInformadaIII.py
El programa imprimirá los valores de x e y que minimizan la función de Himmelblau, junto con el valor mínimo alcanzado.

Código
El algoritmo principal se encuentra en el archivo BúsquedaInformadaIII.py, e incluye las siguientes funciones clave:
himmelblau(x, y): Calcula el valor de la función de Himmelblau para un par de coordenadas (x, y).
recocido(himmelblau, limites, temp, enfriamiento, iteraciones): Implementa el algoritmo de recocido simulado para encontrar el mínimo de la función.

Alumno: Aldo Alcántara Martínez Materia: Inteligencia Artificial Grupo: 6CV3 Profesor: García Floriano Andres Correo: aldoalcantara2004@gmail.com
