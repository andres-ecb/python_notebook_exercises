Este repositorio contiene ejercicios desarrollados en Python como práctica de programación y análisis básico de datos. El objetivo es aplicar conceptos fundamentales de:

- Programación estructurada
- Validación de datos
- Programación orientada a objetos
- Análisis de datos con Pandas
- Equivalencias entre Pandas y SQL

Todo el código se encuentra en **un notebook de Jupyter** para facilitar la explicación y visualización de resultados.

# Ejercicios:
## 1. Práctica Uno: Programa Secuencial - Gestor de notas estudiantiles
Permite registrar estudiantes y sus calificaciones, en una asignatura X. Sus funcionalidades principales son:
- Validación de entrada de datos
- Registro de múltiples estudiantes
- Registro variable de notas por estudiante
- Cálculo automático de: nota más alta, nota más baja, promedio, bonificación por notas adicionales, y nota definitiva
- Clasificación del estudiante en aprobado y reprobado
Los datos se almacenan en un dataframe de Pandas llamado *notas_definitivas*

## 2. Práctica Dos: Consultas a un dataframe y su equivalencia en SQL
Una vez construido el dataframe se realizan diversas consultas para analizar la información. Entre las operaciones realizadas se encuentran:
- Estadísticas descriptivas del conjunto de datos
- Conteo de estudiantes por estado (aprobado/reprobado)
- Promedio de nota definitiva por estado
- Comparación de notas mínimas (notas más bajas) por estado
- Identificación de estudiantes con las notas más altas y más bajas
Las consultas incluyen su equivalencia conceptual en SQL, lo cual permite comparar operaciones de análisis entre Pandas y bases de datos relacionales.

## 3. Práctica Tres: Programación Orientada a Objetos
Programa que permita clasificar y contar una serie de triángulos por su clasificación, desarrollado utilizando programación orientada a objetos.
Se implementa una clase *Triangulo* que permite:
- Validar si tres lados forman un triángulo válido
- Clasificar el triángulo como: Equilátero, Isósceles o Escaleno
El programa permite registrar múltiples triángulos y muestra la distribución final de tipos.

# Tecnologías utilizadas
- Python
- Pandas
- Jupyter Notebook

# Objetivo General
Este repositorio está enfocado en:
- Manipulación de datos
- Lógica de programación
- Uso de estructuras de datos
- Análisis exploratorio básico

# Estructura
python-notebook-exercises/
│
├── exercises.ipynb
└── README.md
