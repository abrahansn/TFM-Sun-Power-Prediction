# TFM-Sun-Power-Prediction

ABRAHAN SANTANA NARANJO

Predicción de valores de producció a partir de datos de meteorológicos.

En este TFM se busca crear un prototipo que permita predecir la producciónde una central fotovoltaica a partir de los datos
meteorológicos recogidos de la API de la AEMET. Para ello, se ha entranado un modelo basado en árboles de decisición, entrenado
con un dataset de una central real.

A lo largo de los notebooks, se ha ido explicando cada uno de los pasos y decisiones tomadas. Se ha comparado el modelo final con un modelo
simple de regresión lineal, además de un libro empaqueta de Tableau que facilita l visualización de los datos y da idea de cómo sería el
proyecto final puesto en producción.

EJECUCIÓN DE DOCUMENTOS:

 0-. Se debe partir de un entorno que disponga de Anaconda instalado previamente. A partir de ahí se podrán ejecutar los archivos en el
 siguiente orden.

1-. Se ejecuta el notebook "00_Preparing_Environment.ipynb", el cual descargará desde GDrive el dataset utilziado para el entrenamiento del
modelo. Además de instalar todas las librerías necesarias para la correcta ejecución del código.

2-. Se ejecuta el notebook "01_Fixing_data.ipynb", el cual limpiará y justificará el procedimiento seguido para preparar los datos antes de 
ser usados para el entrenamiento del modelo. En el se explica el motivo de cada decisión.

3-. A continuación, se ejecuta el notebook "02_Creating_Model.ipynb", el cual permite el entrenamiento y selección del modelo usado para la
predicción de la producción.

4-. Por último, se ejecuta el notebook "03_Scraping_AEMET.ipynb" el cual contiene un algoritmo en el que se apoyrá el modelo de visualziación
y el futuro proyecto de producción para la descarga de datos de la API de la AEMET, que nos permitirá predecir la producción.

5-. Para la visualización de los datos, y con el fin de mostrar un prototipo del panel de visualización buscado para este proyecto, se ha 
creado un libro empaquetado de Tableau. En el cual se muestra, con los datos recogidos el día 9/01/2020, como quedaría dicho prototipo cuando
se ejecute y ponga en producción.
