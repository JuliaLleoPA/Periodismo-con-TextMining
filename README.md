
 ### <span style="color:orange"> Periodismo-con-TextMining </span>
El siguiente repositorio forma parte del Trabajo de Fin de Máster "Modelo para la minería de textos en el sector periodístico", realizado por Julia Lleó Pérez-Abadín para el Máster Letras Digitales de la Universidad Complutense de Madrid durante el curso 2019-2020.

En él, se presenta un **modelo de aplicación para la minería de texto en el sector periodístico** para futuras investigaciones. Para su desarrollo y ejecución, se utilizan herramientas del campo del Procesamiento del Lenguaje Natural a través del lenguaje Python lanzado con la aplicación web JupyterLab. No se desarrollarán nuevos algoritmos para el análisis, sino que se aplica el uso de bibliotecas de PLN en Python y métodos de Análisis de sentimiento y Modelización de tópicos.

Se trata de un modelo abstracto de las fórmulas con que obtener los resultados de estudio. En la memoria del trabajo se encuentra una muestra de su aplicación a un caso de uso concreto: el estudio de la cobertura dada a la pandemia por coronavirus en los diez medios digitales más importantes de España en el mes de marzo de 2020.

Este tipo de automatización permite enfrentar el análisis de una gran cantidad de datos textuales, y su aplicación al sector periodístico puede servir tanto a estudios de contenido tradicionales, con las ventajas que este tipo de sistemas ofrecen, como estudios de mercado, como en el caso aplicado en el trabajo.

El flujo de trabajo recorrido pasa por las siguientes fases:

-	Colección de datos desestructurados de tipo texto.
-	Operaciones de preprocesamiento y limpieza para la eliminación de anomalías. Este proceso nos permite asegurarnos de que se está capturando correctamente la esencia del texto.
-	Procesamiento de los datos limpios, con diferentes técnicas como el análisis de sentimiento y modelado de tópicos.
-	Extracción de información relevante para su análisis.
-	Interpretación de los datos obtenidos.

Para poder hacer uso de los programas del repositorio, se deberá clonar o descargar el mismo y abrirlo a través de una libreta Jupyter a través de Anaconda. También se deberán **descargar algunas bibliotecas** previamente:
- https://anaconda.org/conda-forge/wordcloud
- https://anaconda.org/anaconda/gensim
- https://anaconda.org/conda-forge/keras
- https://anaconda.org/conda-forge/tensorflow
- https://pypi.org/project/sentiment-analysis-spanish/
