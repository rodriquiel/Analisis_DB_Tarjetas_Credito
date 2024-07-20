# Analisis DataBase con tarjetas de credito

## Proyecto creado por Ezequiel Rodriguez en base a curso de Alura "Data Visualization: Explorando con Seaborn"

### Proyecto destinado a trabajar mediante el uso de una base de datos ya procesada de mas de 9 mil elementos con distintos metodos de la biblioteca Pandas y Seaborn perteneciente al lenguaje Python. El principal objetivo es crear gráficos que expresen y comuniquen mejor los insights encontrados.

### Conocimientos aplicados:
### ·Importar datos y trabajar con DataFrames
### ·Tratamiento de datos previo a su analisis
### ·Utilizar Seaborn para creación de diferentes gráficos
### ·Desarrollar técnicas graficas y cuantitativas, orientadas a obtener informaciones relevantes

### Uso de Python Pandas, Matplotlib, Seaborn, Scipy, Jupyter y Anaconda

## Ejemplo de resultados generados a partir del tratamiento de los datos

## Relacion entre edad y limite de la tarjeta mediante grafico de dispersion combinado con histograma desde distintas visuales

### Los siguietes graficos permiten visualizar al mismo tiempo como es la distribución individual de una variable y cómo se relaciona con otra variable con la que se desea hacer comparaciones. En este caso, muestra donde se concentran los limites de las tarjetas de credito en base a las diferentes edades.

### Visual 1
![visual1](https://user-images.githubusercontent.com/111917955/228096918-032d52c1-f323-4837-a621-d9a930afef1e.png)

### Visual 2
![visual2](https://user-images.githubusercontent.com/111917955/228097020-f8e88112-b1e8-4a54-895d-e39abd91a1a7.png)

### Visual 3
![visual3](https://user-images.githubusercontent.com/111917955/228097096-21481ef2-9106-456a-9173-509b79e0befd.png)

## Test de Hipotesis en base a lineas de tendencia de morosidad aplicadas en la relacion entre el indice de uso y el valor de la factura a pagar por el uso de la tarjeta de credito

### Al grafico de dispersion de relacion entre valor de factura e indice de uso (iu), se le agrega la condicion de moroso, viendo dos lineas de tendencia directamente proporcionales pero con diferente inclinacion, por lo que se busca saber si dicha diferenciaa es estadisticamente significativa
![visual4](https://user-images.githubusercontent.com/111917955/228097772-0a15615b-8174-463b-8b7c-c74ecfe600aa.png)

### Las hipotesis planteadas son: 
### H<sup>0<sup> 
### (Hipotesis nula): La distribucion de los grupos moroso y no moroso es la misma
### H<sup>1<sup> 
### (Hipotesis alternativa): La distribucion de los grupos moroso y no moroso es distinta
### Utilizando la funcion ranksums de la biblioteca Scipy se realiza el test, el cual arroja un pvalue por debajo del 0.05 (5%), por lo cual se puede aceptar la hipotesis alternativa como cierta para el caso planteado
