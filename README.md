<p align="center">
 <img src="data/img/henry.jpg" alt="henry" width="1200" height="600">
</p>

<h1 align="center">Segundo Proyecto individual de SoyHenry</h1>

<p align="center">

En este proyecto, se me ha encargado llevar a cabo un análisis exhaustivo para comprender el comportamiento del sector de las telecomunicaciones a nivel nacional en nombre de una empresa de telecomunicaciones. La empresa se dedica principalmente a proporcionar servicios de acceso a Internet, pero también es crucial considerar cómo se comportan los otros servicios de comunicación.<br>
El objetivo es orientar a la empresa en brindar una buena calidad de sus servicios, identificar oportunidades de crecimiento y poder plantear soluciones personalizadas a sus posibles clientes.<br>
Para ello, se han identificado los siguientes desafíos y oportunidades en el sector de las telecomunicaciones:<br>
<br>
- El sector de las telecomunicaciones se enfrenta a una demanda de servicios sin precedentes, lo que implica la necesidad constante de innovación e inversión.<br>
- Las empresas de telecomunicaciones deben implementar análisis avanzados para tomar decisiones más informadas sobre la complejidad de sus redes.<br>
<br>
El análisis llevado a cabo en este proyecto tiene como propósito abordar estos desafíos y oportunidades. Aportará a la empresa una comprensión sólida del comportamiento del sector de las telecomunicaciones y la orientará en su estrategia de crecimiento y expansión. Este análisis se realiza utilizando Python y Jupyter Notebooks.

</p>


<h2 align="center">Estructura del Proyecto</h2>

<p align="center">
El proyecto se estructura en Jupyter Notebooks, centrado en un aspecto específico del análisis. El cuaderno principal que contiene la mayor parte del análisis es:
<a href="EDA.ipynb">
<p align="center">(Análisis Exploratorio de Datos)</p>
</a>
</p>

<br>

<h2 align="center">Proceso de Análisis Exploratorio de Datos</h2>

<p align="center">
Este documento incluye la exploración de datos del sector de telecomunicaciones. En un inicio, se realiza la carga y la depuración de los datos, eliminando las columnas que no son relevantes y gestionando de manera adecuada los valores faltantes. Luego, se procede a analizar los datos depurados para obtener una comprensión más profunda de diversos aspectos en el ámbito de las telecomunicaciones, lo cual abarca: <br>

<p align="center"><strong>Análisis del acceso a Internet por cada 100 hogares en diferentes provincias</strong><br>

</p>

<p align="center">
<img src="data\img\Promedio Anual de Accesos a Internet por cada 100 hogares por Provincia.png" alt="Accesos" width="1200" height="600">
</p>

<p align="center">El gráfico de líneas que se presenta a continuación ofrece una representación visual de la transformación del acceso a Internet a lo largo de los años, abarcando diversas provincias. En esta representación:<br>

- **Eje X:** Se dedica a ilustrar el progreso a lo largo del tiempo, con los años dispuestos de manera cronológica.<br>
- **Eje Y:** Revela el acceso a Internet expresado en términos de la cantidad de conexiones por cada 100 hogares en las distintas provincias.</p>
<br>

<p align="center"><strong>Este grafico representa el Crecimiento Porcentual Año a Año de las Tecnologías
</strong><br>
<p align="center">
<img src="data\img\Crecimiento porcentual del uso de diferentes tecnoplogias.png" alt="Accesos" width="1200" height="600">
</p>
<br>
<p align="center">
 Declive de ADSL: La columna 'ADSL' presenta un descenso constante a lo largo de los años, indicando que la cantidad de conexiones a Internet por medio de ADSL ha estado disminuyendo de forma continua<br>

 Crecimiento de Fibra óptica: La columna 'Fibra óptica' revela un aumento constante a lo largo de los años, lo que sugiere que el número de conexiones a Internet mediante fibra óptica ha estado incrementándose de manera sostenida. En particular, entre 2018 y 2019, la fibra óptica experimentó un crecimiento cercano al 200%, mientras que las tecnologías que proporcionan velocidades más bajas decrecieron. Esto podría indicar que la fibra óptica está ganando popularidad en este período gracias a su mayor velocidad y fiabilidad.
<br>
 Cambio en cablemodem y fibra óptica: entre 2021 y 2022, se observó una disminución de aproximadamente un 30% en las conexiones por cablemodem, junto con un crecimiento similar en las conexiones de fibra óptica. Esto podría sugerir que las personas están migrando de cablemodem a fibra óptica.<br>

 Crecimiento desigual entre tecnologías: No todas las tecnologías han experimentado un crecimiento al mismo ritmo. Por ejemplo, la columna 'Fibra óptica' ha experimentado un crecimiento mucho más rápido que la columna 'ADSL'. Esto podría indicar que diversas tecnologías están siendo adoptadas a distintas velocidades, posiblemente en diversas regiones o por diferentes grupos de usuarios.
</p>
<br>
<p align="center"><strong>Estos graficos representan la velocidad en Mbps por provincias Año a Año
</strong></p><br>
<p align="center">
<img src="data/img/velocidad por provincias.png" alt="Accesos" width="1200" height="600">
</p>
<p align="center">
1- Cada provincia se representa con un gráfico de línea diferente, donde el eje x representa el año y el eje y representa la velocidad promedio del internet en Mbps(megabytes por segundo).
<br>
2- El color de cada línea corresponde a una paleta de colores pastel, lo que facilita la distinción entre las diferentes provincias. Además, se ha establecido un fondo de color negro para cada subplot, lo que mejora la legibilidad de los gráficos.
<br>
Analizando los graficos se puede observar una clara tendencia alsista en la velocidad del internet por provincia por año por lo que podemos decir que hubo inversiones en infraestructura tecnologia para la mejora del acceso a internet con una velocidad aprovechable para diferentes tareas.
<br>
Como en el resto de graficos se puede observar una fuerte superioridad en capital federal lo cual si no supiesemos nada de este pais nos dariamos cuenta que puede llegar a ser la capital del pais o una ciudad muy importante.
</p>


<br>
<p align="center"><strong>Estos graficos representan la diferencia de velocidad en Mbps por provincias para cada Año
</strong></p><br>
<p align="center">
<img src="data/img/velocidad del inter por provincias por anio.png" alt="Accesos" width="1200" height="600">
</p>

<p align="center">
En las representaciones gráficas, se puede observar de manera evidente cómo la velocidad de descarga en megabits por segundo (Mbps) ha experimentado un incremento en la mayoría de las provincias a lo largo del tiempo. No obstante, también resulta evidente que algunas provincias, como Chubut, han mantenido una velocidad de Internet relativamente estable sin experimentar un crecimiento significativo en comparación con otras regiones. Estos gráficos proporcionan una representación visual que permite identificar las diferencias en la evolución de la velocidad de Internet entre las distintas provincias.
</p>
<br>
<h2 align= "center">Datos</h2>
<p align="center">
Los datos utilizados en este proyecto son una colección de datos de telecomunicaciones, fueron extraidos de la pagina de ENACOM.<br>
Incluyen información sobre el acceso a Internet y su uso en diferentes regiones. Los datos se almacenan en varios archivos XLSX, para luego ser transformados en archivos CSV.<br>
se cargan en los cuadernos Jupyter para su análisis.</p>

<br>

<h2 align= "center">Librerías Utilizadas</h2>

<p align="center">
El proyecto utiliza varias bibliotecas de Python para el análisis de datos y la visualización</p>

<p align="center">import pandas as pd</p>
<p align="center">import numpy as np</p>
<p align="center">import matplotlib.ticker as ticker</p>
<p align="center">import matplotlib.pyplot as plt</p>
<p align="center">import matplotlib.colors as colors</p>
<p align="center">import random</p>
<p align="center">import seaborn as sns</p>
<p align="center">import warnings</p>

<br>

<h2 align= "center">Conclusion</h2>

<p align="center">
Para este proyecto, se utilizaron datos de telecomunicaciones recopilados de la página web del ENACOM.<br>

Estos datos incluyen información sobre el acceso a Internet y su uso en diferentes regiones de Argentina.<br>

Los datos se encuentran en varios archivos XLSX, que luego se convirtieron a archivos CSV.<br>

Finalmente, se cargaron en cuadernos Jupyter para su análisis.</p>

<h2 align= "center">Contacto</h2>

<br>

<p align="center">Estoy a tu disposición para cualquier consulta, sugerencia o simplemente para establecer una comunicación contigo. Puedes ponerte en contacto conmigo de la siguiente manera:</p>
<br>
<p align="center">Correo Electrónico: joaquincostamagna2608@gmail.com</p>


