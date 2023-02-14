# Australian Housing Price Prediction - Advanced Regression

## Introduction 

Este es un análisis para lograr una Prediccion de Precios en Bienes Raices, basado en una base de datos de venta de casas en Australia, con lo que se pretende determinar.

### Methods Used
El método usado en este proyecto, es la regression. Para poder ver que tipo de regressión es la más adecuada, se hicieron prubeas con:
 - Linear regression
 - Ridge Regression 
 - LASSo Regression
 
### Technologies
* Python
* Pandas
* numpy
* matplotlib
* pylab 
* seaborn
* impyute
* sklearn
* statsmodels
* scipy

## Download and Setup
### Prerequisitos

Para lograr ver los resultados de este proyecto, se recomienda el uso de un Jupyter Notebook, en este caso se hizo uso de Google Colab Notebooks, los cuales vienen enlazados con una cuenta de gmail y no es necesario otro requisito para su uso. 

Sin embargo, puede lograrse un normal funcionamiento con una instalación de Python y el uso de cualquier herramienta de edición (en algunos casos puede requerir la instalación de algunas librerias extra). 

### How to Run

Se puede hacer uso de este proyecto con el siguiente procedimiento:
1. Clonar el repositorio desde GitHub
    * Copiar en url del repo y en una terminal de su preferencia seguir estos pasos:
      - Ubicar una carpeta para almacenar el proyecto
      - Escribir en la terminal:
              git clone <Repo URL>
      - Abrir el archivo .ipynb y verificar que la base de datos este bien ruteada.
      - Empezar a correr los pasos propuestos.
2. Copiar el contenido en un Google Colab Notebook, verificando que la base de datos tambein se encuentren ahi.

#### Most Significant Variables are:
De acuerdo al análisis de Randon Forest, se encontraron las 10 variables más importantes del modelo:

* OverallQual (Material general y el acabado de la casa): 0.482385524510015
* TotalSF (pies cuadrados totales del área de sotano): 0.31151294786171596
* EdadCasa: 0.019820532193987023
* OverallCond (Califica el estado general de la casa): 0.017556625169394883
* EdadRemod (Fecha de remodelación): 0.014247354824679592
* LotArea (Tamaño del lote en pies cuadrados): 0.013963901725239928
* TotalBathrooms (Cantidad de baños): 0.012771176156901357
* GarageCars (Tamaño del garaje en capacidad de automóviles): 0.011134577026914588
* LotFrontage (Pies lineales de calle conectados a la propiedad): 0.00706667606021561
* GarageType_Detchd (Ubicación del garaje): 0.006446318011371601