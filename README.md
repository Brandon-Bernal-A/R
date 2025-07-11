# Notas R

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

## [2. Intermedio](Intermedio)

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

## [3. Tidyverse - Introducción](Tidyverse)

### [3.1 dplyr básico](Tidyverse/dplyr_basico.ipynb)

- `install.packages()`
- `library()`
- `gapminder()` dataset
- `str()`
- `filter()`
- Pipes con `%>%`
- `arrange()`
- `mutate()`

### [3.2 Summarize y Group by](Tidyverse/Summarize_y_Group_by.ipynb)

- `summarize()`
- `group_by()`
- Introducción a `ggplot2`

### [3.3 Unir tablas con dplyr](Tidyverse/Unir_tablas_con_dplyr.ipynb)

- `inner_join()`
- `left_join()`
- `right_join()`
- `full_join()`
- `anti_join()`
- `semi_join()`
- `replace_na()`
- `bind_rows()`

## 4. [Manipulación con dplyr](Manipulacion_Dplyr)

### [4.1 Funciones Esenciales](Manipulacion_Dplyr/Funciones_Dplyr.ipynb)

- `glimpse()`
- `select()`
- `arrange()`
- `filter()` y `%in%`
- `mutate()`
- `count()`
- `summarize()` y `group_by()`
- `slice()` y variantes
- Seleccionar casos (`:`, `contains()`, eliminación, etc.)
- `rename()`
- `relocate()`
- `levels()` y `droplevels()`
- `table()`


## [5. ggplot2](ggplot2)

### [5.1 Gráficos](ggplot2/Visualización.ipynb)

- Librería `ggplot2`
- Estructura básica de un gráfico
- `aes()` para asignación estética
- Complementos útiles: `+ ... +`
- Argumentos `geom_*()`
- Gráfico de dispersión: `geom_point()`
- Gráfico de líneas: `geom_line()`
- Gráfico de barras
- Histograma
- Boxplot
- Títulos y etiquetas
- Función `labs()`
- Líneas de tendencia: `geom_smooth()`
- Guardar gráficos: `ggsave()`
- Líneas verticales y horizontales: `geom_vline()` y `geom_hline()`
- Límites: `xlim()`, `ylim()` y `scale_x/y_continuous()`
