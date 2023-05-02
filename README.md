# PEC2: Estudio de técnicas de visualización de datos
## Visualización de Datos
## Master Universitario en Ciencia de Datos
### Alumno: Carlos Luis Gento de Celis

# Índice
1. [Pie Chart](#pie-chart)
2. [Matrix Plot](#matrix-plot)
3. [Tile Grid Map](#tile-grid-map)

## Pie Chart
- **Descripción:** Es un círculo dividido en sectores proporcionales que representan una proporción de un total. Su objetivo es mostrar cómo se dividen los datos en proporciones o porcentajes entre categorías. La suma de proporciones debe ser igual al total de la muestra, y la de porcentajes debe ser igual al 100%.
- **Ejemplos:** Proporción de individios para cada nivel educativo en una muestra, porcentaje de ventas mensuales de cada producto en una tienda, distribución del valor de cada tipo de activo financiero (acciones, fondos de inversión, renta foja...) en la riqueza financiera de un hogar.
- **Tipos de datos:** Numéricos y categóricos. Debe haber al menos una variable categórica.

<div align="center">

  Número de individuos para cada nivel educativo
  
|  	| Nivel educativo 	|
|---	|:---:	|
| Inferior a bachillerato 	| 150 	|
| Bachillerato 	| 500 	|
| Estudios Universitarios 	| 250 	|
  
</div>
 
  
- **Limitaciones:**
   * Cuesta leerlos cuando hay más de cuatro o cinco categorías. A los humanos les cuesta leer ángulos.
   * No pueden representar evoluciones temporales.

- **Ejemplo de visualización: Distribución de adultos por raza**

    Datos utilizados: [Kaggle Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

 <p align="center">
  <img src="images/Pie_chart.png" />
 </p>


## Matrix Plot
- **Descripción:** Tipo de gráfico que permite visualizar datos que puedan representarse en formato de matriz, como por ejemplo matrices de correlaciones o de distancias. Las filas y columnas de la matriz representan dos variables, que pueden ser numéricas o categóricas, mientras que el valor de cada celda representa el valor para ese punto de la matriz. Un ejemplo es el mapa de calor, en el que los valores de la matriz se presentan a través de variaciones en su color.
- **Ejemplos:** Matrices de correlaciones, matrices de distacias, evolución temporal del porcentaje de voto a partidos políticos por región.
- **Tipos de datos:** Numéricas y categóricas. Tienen que poder representarse en formato de matriz.

<div align="center">
  
  Evolución de la proporción de individuos por nivel educativo. 1970 - 2000
  
|  	| 1970 	| 1980 	| 1990 	| 2000 	|
|---	|:---:	|:---:	|:---:	|:---:	|
| Inferior a bachillerato 	| 50% 	| 40% 	| 35% 	| 30% 	|
| Bachillerato 	| 45% 	| 50% 	| 50% 	| 40% 	|
| Estudios Universitarios 	| 5% 	| 10% 	| 15% 	| 30% 	|
  
</div>
 
  
- **Limitaciones:**
   * Cuesta leerlos cuando hay más de cuatro o cinco categorías. A los humanos les cuesta leer ángulos.
   * No pueden representar evoluciones temporales.

- **Ejemplo de visualización: Mapa de calor, llamadas al 911 por día de la semana y hora**

    Datos utilizados: [Kaggle Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
<p align="center">
  <img src="images/Matrix_plot.png" />
 </p>
 
## Tile Grid Map
<p align="center">
  <img src="images/Tile_Grid_Map.png" />
 </p>
