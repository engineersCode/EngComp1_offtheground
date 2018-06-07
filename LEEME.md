# Cálculos Computacionales en Ingeniería - Módulo 1 

_Cálculos Computacionales en Ingeniería_ es un curso en línea realizado con módulos de aprendizaje intercambiables, proporcionando flexibilidad para adaptarlo a diversas situaciones. Apunta a desarrollar habilidades computacionales para estudiantes en ingeniería, pero también puede ser usado por estudiantes de otras disciplinas científicas. El curso utiliza el lenguaje de programación Python y las herramientas de código abierto de Jupyter para computación interactiva.

Este primer módulo no asume ninguna experiencia previa en programación, por lo que las tres primeras lecciones se centran en crear una base de conocimientos de programación en Python sin hacer uso de Matemáticas. La cuarta lección introduce la estructura de datos básicos en la informática científica: _arrays_. La última lección es un ejemplo de regresión lineal con datos reales.

## Sobre la traducción

La traducción de los módulos escritos originalmente en inglés se realiza de manera literal, tratando de mantener un español neutro y fácil de leer. Se traducirá los nombres de archivos de notebook, comentarios, mensajes, valores de los strings, y de manera general, lo que ayude a hacer más facil de entender el código. Sin embargo, no se traducirán los nombres de variables ni el contenido de los datos de ejemplo. Es necesario de todas maneras aprender un poco de inglés para comprender y redactar de mejor manera código de Python, por lo que el código en sí mismo se mantendrá casi completamente en inglés.

## Módulo 1: Obtener datos

_Aprender a interactuar con Python y manejar datos en Python._

> Obten una sesión interactiva en [MyBinder.org](https://mybinder.org/) con el material del curso utilizando el botón inferior.
> Selecciona la carpeta `notebooks_es` para acceder a las 5 lecciones de este curso como notebooks de Jupyter completamente ejecutables.
>
> [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/engineersCode/EngComp1_offtheground/master)

* **Puedes unirte al curso [open online course](https://openedx.seas.gwu.edu/courses/course-v1:GW+EngComp1+2018/about)** (en inglés) en nuestra plataforma _Open edX_.

* **Obtener una versión PDF para imprimir** (en inglés): _Engineering Computations Module 1: Get data off the ground._ figshare. https://doi.org/10.6084/m9.figshare.5673454.v1

### [Lección 1](https://github.com/engineersCode/EngComp1_offtheground/blob/translation_es/notebooks_es/1_Interactuando_con_Python.ipynb): Interactuando con Python.

Antecedentes: ¿Qué es Python? Nociones de lenguaje interpretado en comparación a lenguaje compilado. ¿Por qué usar Python? Es un lenguaje de uso general y de alta productividad.
Primeros pasos: Python interactivo (IPython).
Utilizando Python como una calculadora.
Nuevos conceptos: funciones, strings, variables, asignación, tipo, variables especiales (`True`,` False`, `None`).
Operaciones matemáticas, operaciones lógicas. Lectura de mensajes de error.

### [Lección 2](https://github.com/engineersCode/EngComp1_offtheground/blob/translation_es/notebooks_es/2_Strings_y_listas_en_Jupyter.ipynb): Jugando con los datos en Jupyter

¿Qué es Jupyter? Trabajando con Jupyter. Jugando con cadenas de texto (strings) en Python: asignación, indexación, subdivisión. Métodos de cadenas de texto: count, find, index, strip, startswith, split. Jugando con listas de Python: asignación, listas anidadas, indexación, segmentación. Métodos de listas: agregar, indexar. Pertenencia a una lista. Iteración con declaraciones for. Condicionales.

### [Lección 3](https://github.com/engineersCode/EngComp1_offtheground/blob/translation_es/notebooks_es/3_Ejemplo_con_MAEbulletin.ipynb): Cadenas de texto y listas en acción

Un ejemplo completo que utiliza lo aprendido en las lecciones 1 y 2: jugando con un archivo de texto que contiene el boletín MAE (lista de cursos con sus números, descripción, requisitos previos). Lectura de datos de un archivo. Limpieza y organización de datos de un texto.

### [Lección 4](https://github.com/engineersCode/EngComp1_offtheground/blob/translation_es/notebooks_es/4_NumPy_Arrays_y_Graficos.ipynb): Jugando con matrices NumPy

Dos de las bibliotecas más importantes para informática científica con Python: **NumPy** y **Matplotlib**. Importando bibliotecas. Funciones de NumPy para crear matrices: linspace, ones, zeros, empty, copy. Operaciones de un array. Matrices multidimensionales. Ventaja de rendimiento de arrays sobre listas. Graficando líneas 2D de datos a partir de arrays.

### [Lección 5](https://github.com/engineersCode/EngComp1_offtheground/blob/translation_es/notebooks_es/5_Regresion_Lineal_con_datos_reales.ipynb): Regresión lineal con datos reales

Un ejemplo completo que usa datos reales de la temperatura de la tierra a lo largo del tiempo. Paso 1: leer datos de un archivo. Paso 2: graficar los datos; haciendo gráficos hermosos. Paso 3: regresión lineal de mínimos cuadrados. Paso 4: aplicar regresión lineal usando NumPy. Bonus: regresión segmentada.

## Derechos de autor y licencia

(c) 2017 Lorena A. Barba, Natalia C. Clementi. Todo el contenido está bajo Atribución de Creative Commons [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode.txt), y todo [el código está bajo la cláusula BSD-3](https://github.com/engineersCode/EngComp/blob/master/LICENCE). ¡Estaremos felices si reutilizas el contenido de alguna manera!

[![Licencia](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Licencia: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/) [![Licencia: CC BY 4.0](https://img.shields.io/badge/Original-English-lightgreen.svg)](https://github.com/engineersCode/EngComp1_offtheground/) 
