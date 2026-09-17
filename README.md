# TFM — Predicción de Riesgo de Desnutrición Infantil en Colombia

Pipeline de machine learning que clasifica municipios de Colombia como
`prioritario` o `no_prioritario` según el riesgo de desnutrición aguda
infantil, usando datos epidemiológicos de SIVIGILA cruzados con variables
socioeconómicas (IPM censal, MDM, SISBEN) y geográficas.

Este repositorio divide el notebook original (`TFM_VF.ipynb`) en un
notebook por capítulo, en el orden en que aparecen en el análisis. GitHub
renderiza cada `.ipynb` directamente en el navegador (código, texto y
gráficas incluidos), así que basta con hacer clic en un capítulo para
verlo — no hace falta descargarlo ni ejecutarlo. Son la versión de
**lectura/referencia**; para reproducir los resultados hay que correr el
pipeline completo, no un capítulo suelto.

## Índice

| Capítulo |
|---|
| [1. Preliminares](01.%20Preliminares.ipynb) |
| [2. EDA - overview](02.%20EDA%20-%20overview.ipynb) |
| [3. EDA - features](03.%20EDA%20-%20features.ipynb) |
| [4. Limpieza de los datos](04.%20Limpieza%20de%20los%20datos.ipynb) |
| [5. Feature engineering](05.%20Feature%20engineering.ipynb) |
| [6. Modelling](06.%20Modelling.ipynb) |
| [7. Modelling con un target binario](07.%20Modelling%20con%20un%20target%20binario.ipynb) |
| [8. Modelo final](08.%20Modelo%20final.ipynb) |
| [9. Interpretabilidad del modelo final](09.%20Interpretabilidad%20del%20modelo%20final.ipynb) |
| [8.3 Datos para exportar](10.%20Datos%20para%20exportar.ipynb) |
| [10. Productivizar el Modelo](11.%20Productivizar%20el%20Modelo.ipynb) |
| [ANEXO](12.%20ANEXO.ipynb) |

> ⚠️ El capítulo 3 (EDA - features) tenía originalmente un mapa interactivo
> de Colombia (HTML/JS) que pesaba más de 200 MB — se omitió con una nota
> en su lugar, porque no es viable de todos modos previsualizar un mapa
> interactivo dentro de un notebook renderizado de forma estática.

## Autor

Jefferson Montoya Hoyos · Máster en Data Science
