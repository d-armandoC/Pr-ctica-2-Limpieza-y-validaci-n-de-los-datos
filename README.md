# 1. Detalles de la actividad 

## 1.1. Descripción 

En esta actividad se elabora un caso práctico, consistente en el tratamiento de un conjunto de datos (en inglés, dataset), orientado a aprender a identificar los datos relevantes para un proyecto analítico y usar las herramientas de integración, limpieza, validación y análisis de las mismas.

## 1.2. Objetivos 

Los objetivos que se persiguen mediante el desarrollo de esta actividad práctica son los
siguientes:
- Aprender a aplicar los conocimientos adquiridos y su capacidad de resolución de problemas en entornos nuevos o poco conocidos dentro de contextos más amplios o
multidisciplinares.

- Saber identificar los datos relevantes y los tratamientos necesarios (integración, limpieza y validación) para llevar a cabo un proyecto analítico.

- Aprender a analizar los datos adecuadamente para abordar la información contenida en los datos.

- Identificar la mejor representación de los resultados para aportar conclusiones sobre el problema planteado en el proceso analítico.

- Actuar con los principios éticos y legales relacionados con la manipulación de datos en
función del ámbito de aplicación.

- Desarrollar las habilidades de aprendizaje que permita continuar estudiando de un
modo que tendrá que ser en gran medida autodirigido o autónomo.

- Desarrollar la capacidad de búsqueda, gestión y uso de información y recursos en el
ámbito de la ciencia de datos.

## 1.3. Competencias

En esta práctica se desarrollan las siguientes competencias del Máster de Data Science:

- Capacidad de analizar un problema en el nivel de abstracción adecuado a cada situación y aplicar las habilidades y conocimientos adquiridos para abordarlo y resolverlo.

- Capacidad para aplicar las técnicas específicas de tratamiento de datos (integración, transformación, limpieza y validación) para su posterior análisis.
## 2.  Ficheros del código fuente

- Dataset a analizar datos.csv
- Dataset Limpio Datos?operaciones
- Practica 2 Limpieza y análisis de datos.Rmd.- Contiene el notebook en R del código.
- Practica 2 Limpieza y análisis de datos.Html.- Contiene el notebook en R del código.
- Practica 2 Limpieza y análisis de datos.pdf.- Contiene el notebook en R del código.

## 3. Conclusiones

- General 

Como se ha visto, se han realizado tres tipos de pruebas estadísticas sobre un conjunto de datos que se correspondía con diferentes variables relativas a vehículos con motivo de cumplir en la medida de lo posible con el objetivo que se planteaba al comienzo. Para cada una de ellas, hemos podido ver cuáles son los resultados que arrojan (entre otros, mediante tablas) y qué conocimientos pueden extraerse a partir de ellas.
Así, el análisis de correlación y el contraste de hipótesis nos ha permitido conocer cuáles de estas variables ejercen una mayor influencia sobre el cáncer de mama, mientras que el modelo de regresión lineal obtenido resulta de utilidad a la hora de realizar predicciones para esta variable dadas unas características concretas.
Previamente, se han sometido los datos a un preprocesamiento para manejar los casos de ceros o elementos vacíos y valores extremos (outliers). Para el caso del primero, se ha hecho uso de un método de imputación de valores de tal forma que no tengamos que eliminar registros del conjunto de datos inicial y que la ausencia de valores no implique llegar a resultados poco certeros en los análisis. Para el caso del segundo, el cual constituye un punto delicado a tratar, se ha optado por incluir los valores extremos en los análisis dado que parecen no resultar del todo atípicos si los comparamos con los valores que toman las correspondientes variables para el cancer de mama.

- Específico

Se puede considerar factores de riesgo en la infección postquirúrgica:
La edad>=65
El nivel de hematocritos< 37
La desnutrición
La diabetes
Obesidad
Hemos visto que la probabilidad de infección postquirúrgica aumenta en los pacientes que presentan desnutrición, diabetes y obesidad.
También aumenta la probabilidad de infección, si el paciente es mayor de 65 años. Por otro lado, si el número de hematocritos es alto las probabilidades de infección postquirúrgica disminuyen.


# 4. Recursos

- Gavin Brown. Diversidad en conjuntos de redes neuronales . La universidad de Birmingham. 2004. 
- Hussein A. Abbass. Un enfoque evolutivo de redes neuronales artificiales para el diagnóstico de cáncer de mama . Inteligencia artificial en medicina, 25. 2002. 
- Calvo M., Subirats L., Pérez D. (2019). Introducción a la limpieza y análisis de los datos. Editorial UOC.
- Megan Squire (2015). Clean Data. Packt Publishing Ltd.
-  Jiawei Han, Micheine Kamber, Jian Pei (2012). Data mining: concepts and techniques.
Morgan Kaufmann.
- Jason W. Osborne (2010). Data Cleaning Basics: Best Practices in Dealing with Extreme
Scores. Newborn and Infant Nursing Reviews; 10 (1): pp. 1527-3369.
- Peter Dalgaard (2008). Introductory statistics with R. Springer Science & Business Media.
- Wes McKinney (2012). Python for Data Analysis. O’Reilley Media, Inc.
- Tutorial de Github https://guides.github.com/activities/hello-world. 
