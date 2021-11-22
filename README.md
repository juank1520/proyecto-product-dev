# Proyecto 1 Product Development
Consiste en crear un modelo de regresión para poder predecir la nota que obtendrá el alumno en
el último periodo del año.

## Archivos del proyecto
1. Analisis.ipynb - Es un notebook que contiene todo el análisis de forma de tallada que se realizó para poder crear el modelo
2. pipeline.ipynb - Es un notebook que contiene el pipeline a utilizar al momento de poner el proyecto en producción, se utilizó como base los resultados obtenidos en Analisis.ipynb
3. proprocess_data - Todos los archivos creados para poder replicar facilmente el modelo
4. housePricePipeline.pkl - El modelo, este modelo se puede cargar y comenzar a predecir sin configurarle ningún parámetro
5. dataset.csv - El dataset que se utilizó

## Descripción del Dataset
Esta data se obtiene de colegios de secundaria de Portugal, los atributos del dataset incluyen
información de los estudiantes, características demográficas y sociales. En el dataset se
proporciona el desempeño de dos materias (matemática y lenguaje, que es este caso es
portugués) en tres distintas épocas, el primer periodo del año, el segundo periodo del año y el
último periodo del año, estas calificaciones se clasifican en 5 niveles.

## Utilidad del modelo
Puede ser de gran ayuda para prestarle más atención a ciertos estudiantes que pueden llegar a
perder el año o bajar su rendimiento académico.
También puede ser de utilidad para extraer hallazgos de qué características le afectan a los
alumnos en su rendimiento académico
