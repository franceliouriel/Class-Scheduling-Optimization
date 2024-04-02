# Programación de Clases Universitarias

Este proyecto aborda el desafío de programar las clases universitarias en el Instituto Tecnológico de Estudios Superiores Monterrey Campus CM de manera eficiente, considerando múltiples restricciones y variables. Se busca asignar óptimamente horarios y aulas a cursos y profesores, minimizando costos y tiempos de programación.

## Descripción del Problema

El **Problema de Programación de Clases Universitarias** implica asignar horarios y aulas a cursos y profesores de manera óptima, considerando diversas restricciones como disponibilidad de aulas y profesores, capacidad de los salones, y carga máxima semestral de los profesores, entre otros. Se busca minimizar los costos y el tiempo de programación, garantizando el cumplimiento de todas las restricciones.

## Formulación del Problema

### Variables de Decisión

Se definen las siguientes variables de decisión:

- $X_{ijk}$: Indica si el curso $i$ es impartido por el profesor $j$ en el horario $k$.
- $Y_{i}$: Indica si el profesor $i$ está impartiendo algún curso.

### Función Objetivo

Se busca minimizar la siguiente función objetivo:

$\text{Min}(Z) = \sum \limits_{i\in profesor} Y_{i}$

### Restricciones

1. Horas asignadas a los bloques.
2. Carga máxima semestral de cada profesor.
3. Evitar empalmes en los horarios de los profesores.
4. Relación entre las variables de decisión $X$ e $Y$.
5. Evitar empalmes en los horarios de las materias.

## Parámetros del Modelo

El modelo considera los siguientes parámetros:

- Datos del profesor (nombre, nómina y correo).
- Disponibilidad de horario del profesor (días y horas) y carga máxima semestral.
- Claves a programar y su número de grupos.
- Capacidad máxima de alumnos en el salón.
- Rango de horario para programar los grupos.
- Evitar empalmes entre materias.
- Acomodar el conjunto de bloques y materias de manera uniforme.
- Atributos de la Unidad de Formación (idioma, tipo de grupo y duración).
- Cantidad de alumnos a inscribirse.
- $C_{j}$ : Carga máxima del profesor $j$.
- $M_{i}$ : Número de horas de la materia $i$ .

## Conclusión

El **Problema de Programación de Clases Universitarias** es complejo debido a la variedad de restricciones y factores a considerar. Este proyecto propone abordar esta problemática mediante una programación sistematizada, eficiente y con una lista de espera de profesores. 
