# Sprint-7-Telco-Analisis
En este repositorio encontrarás un analisis a 3 csv de una empresa de telecomunicaciones, usado como proyecto del Sprint 7 del Bootcamp para Analista de Datos.

## Datasets
En este repositorio se encuentran los datasets usados
- `plans.csv` que recopila los tipos de planes de la empresa, solo tiene 2 planes, por lo que son 2 renglones x 8 columnas que detallan el plan.
- `users.csv` recopila la informacion personal de los usuarios, presentan valores que requieren limpieza, misma que se lleva a cabo en el proyecto.
- `usage.csv` es el principal que contiene el registro de llamadas y mensajes, igual presenta valores que se limpian en el proyecto.

## Main code
El main code es `S7 Version-Estudiante-Project-ConnectaTel.ipynb` que lo encontrarás en este mismo repositorio. Quizas es necesario modificar las direcciones de los .csv para que los lea correctamente.
El main code:
  - Lee los .csv.
  - Explora el contenido en variables DataFrame.
  - Identifica valores faltantes y sentinels y los limpia.
  - Estructura los datos.
  - Los identifica sus distribuciones a traves de histogramas.
  - Unifica la informacion en patrones de consumo de mensajes y llamadas.
  - Identifica `outliers` a traves de boxplot.
  - Grafica grupos de edad y de uso para comprender las diferencias entre los clientes.
  - Presenta conclusiones a partir de lo visto en las gráficas.

## Como reproducir estos resultados
- Descarga el archivo `.ipynb` y los archivos `.csv`.
- Modifica la celda de lecturas para que la direccion se ajuste a la direccion donde se encuentran los `.csv`
- Ejecuta las celdas de forma ordenada

## Objetivo del proyecto
- Explorar los Datasets recibidos de la empresa
- Identificar valores incorrectos y tratarlos
- Realizar un analisis de la información para detectar:
  - Patrones de consumo
  - Distribuciones entre clientes
  - Variaciones entre planes
  - Grupos de uso
- Presentar conclusiones y recomendaciones enfocadas a mejorar y optmizar planes para los usuarios.
