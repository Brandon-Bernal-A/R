# R

Aquí pondré un resumen de cómo usar el lenguaje de R.

# [Índice](https://github.com/Brandon-Bernal-A/R/blob/main/README.md#%C3%ADndice)

## [1. Introducción](Introduccion)

### [1.1 Primeros pasos](Introduccion/Primeros_Pasos.ipynb)

- Comentarios
- Operaciones
- Tipos de datos (`numeric`, `booleanos`)
- Variables
- Función `class()`
- Crear vectores con `c()`
- Nombrar elementos de vectores con `names()`
- Suma de vectores
- Función `sum()`
- Comparar vectores (`>`, `<`, `==`, etc.)
- Seleccionar elementos de un vector con `[i]`

### [1.2 Matrices y Factores](Introduccion/Matrices_y_Factores.ipynb)

- Crear una matriz con `matrix()`
- Nombrar filas y columnas con `colnames()` y `rownames()`
- Sumar filas y columnas con `rowSums()` y `colSums()`
- Combinar matrices con `cbind()` y `rbind()`
- Seleccionar elementos de una matriz
- Variables categóricas (Factores) con `factor()`
- Variables categóricas nominales y ordinales
- Función `summary()`

### [1.3 Data Frame y Listas](Introduccion/Data_Frame_y_Listas.ipynb)

- Crear un `data.frame()`
- `head()` y `tail()`
- Seleccionar elementos de un Data Frame (`$`, `[]`)
- `subset()`
- Crear listas con `list()`
- Seleccionar datos de listas

## 2. Intermedio

### [2.1 Condicionales y Funciones](Intermedio/Condicionales_y_Funciones.ipynb)

- Condicionales: `&`, `|`, `!`
- Estructuras `if` y `else`
- Estructura de funciones en R
- Uso de `help()` y `?`
- Intalar paquetes y `library()`

### [2.2 Ciclos y Fechas](Intermedio/Ciclos_y_Fechas.ipynb)

- Ciclo `while`
- Ciclo `for`
- Funciones de fecha: `now()` y `today()`
- Formato y manejo de fechas

### [2.3 Coincidencias y vapply](Intermedio/Coincidencias_y_sapply.ipynb)

- Coincidencias con `grepl()` y `grep()`
- Selección de patrones: `^`, `\\.`, `$`
- Reemplazo con `sub()` y `gsub()`
- Uso de `lapply()`
- Uso de `sapply()`
- Uso de `vapply()`
