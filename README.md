# PEC2: Estudio de técnicas de visualización de datos
## Visualización de Datos
## Master Universitario en Ciencia de Datos
### Alumno: Carlos Luis Gento de Celis

# Índice
1. [Pie Chart](#pie-chart)
2. [Matrix Plot](#matrix-plot)
3. [Tile Grid Map](#tile-grid-map)

## Pie Chart
- **Origen:** Principios del siglo XIX
- **Descripción:** Es un círculo dividido en sectores proporcionales que representan una proporción de un total. Su objetivo es mostrar cómo se dividen los datos en proporciones o porcentajes entre categorías. La suma de proporciones debe ser igual al total de la muestra, y la de porcentajes debe ser igual al 100%.
- **Ejemplos:** Proporciones de hombres y mujeres en una muestra, porcentaje de ventas mensuales de cada producto en una tienda,
- **Tipos de datos:** Numéricos y categóricos. Debe haber al menos una variable categórica.

<div align="center">
  
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

 | Más del 80% de la muestra de individuos son de raza blanca. El siguiente grupo más numeroso es el de raza negra, que representa el 9.6% de la muesta. El resto de razas representa el 4.9%.

## Matrix Plot
<p align="center">
  <img src="images/Matrix_plot.png" />
 </p>
 
## Tile Grid Map
<p align="center">
  <img src="images/Tile_Grid_Map.png" />
 </p>
