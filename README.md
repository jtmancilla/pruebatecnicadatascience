# PRUEBA TÉCNICA PARA TEAM DE BOOTCAMP DE DATA SCIENCE E IA

¡Hola! Gracias por tu interés en ser parte de nuestro bootcamp de Data Science e Inteligencia Artificial de U Camp.🤖🚀 

A continuación, te comparto unas preguntas relacionadas a tu área. Respóndelas de acuerdo a tus conocimientos y experiencia y espero tus respuestas en mi correo nancy.nava@utel.edu.mx a más tardar 3 días naturales después de haberte enviado esta prueba.🤓



1. ¿Qué técnicas de Machine Learning has implementado?

NLP (natural language processing) para sentiment analysis y categorización de contenido por tópicos. En sentiment analysis utilicé SVM (Máquinas de soporte vectorial), algoritmo de aprendizaje supervisado para categorizar el sentimiento del texto en positivo, negativo o neutral. Y para la categorización de contenido por tópico he utilizado Naive Bayes y una acercamiento con WordToVec y sentenceToVec en combinación con Clustering (no supervisado). 

Supervisado:
Para predicción de precios he utilizado Regresión Logística y Lineal.  (El valor de una vivienda con base en sus carácteristicas y ubicación).

Para categorización de imágenes Red Neural con Tensorflow 

Naive Bayes para detección documentos no deseados.

Metodos ensamblados como Random Forests, GBM , AdaBoost para predicciones deportivas.

No Supervisado:
Clustering para segmentación de mercado.
Clustering exploración de información.


2. ¿Cuáles son los pasos para hacer un árbol de decisiones?

Un arbol de decisión nos va a permitir clasificar, recomendar o tomar una decisión con base en ciertos atributos que se van decidiendo conforme avanza el análisis (profundizando). 

Se empieza con una idea principal y se va ramificando según las consecuencias de las decisiones.

El enfoque común es de arriba hacia abajo, empezando por un nodo raiz o una idea. 
Posteriomente se van agregando nodos conforme se toma una decisión o se tienen nuevos atributos.
Se calculan los valores al tomar una decisión (probabilidad de decidir por uno o por otra rama).
Se evalua los resultados (Entropy o GINI son utilizados para evaluar la ganancia o perdida de información conforme se tomaron las decisiones).


3. ¿De qué forma evitas el sobreajuste en los modelos?

Para evitar el sobreajuste podemos probar varias caminos:

- La validación cruzada, esta es una técnica que nos va a permitir evaluar nuestros modelos dividiendo nuestro conjunto de datos en diferentes subconjuntos que seran evaluados de forma alternada.  
- Podemos probar modelos más simples. Un modelo demasiado cargado puede sobreajustar los resultados, por lo que es importante seleccionar atributos de relevancia y no necesariamente utilizar todo.
- Aumentar el volumen de datos, tener pocos datos nos puede sesgar los resultados, por lo que es conveniente tener una muestra robusta de datos para poder tener mejores resultados y evitar el sobreajuste.
- Parar anticipadamente, al utilizar técnicas de machine learning, buscamos minimizar el error y algunas veces nos topamos con mínimos locales, parar antes de sobreajustar un modelo, también se puedo probar.


4. ¿Cómo has evitado que tus modelos arrojen sesgos en los datos?

Primeramente se tiene que realizar un EDA, un análisis exploratorio de los datos, para entender como está distribuida nuestra información y que relaciones se presentan. Esto nos va a permitir detectar si existen sesgo en la recolección o generación de los datos por cuestiones técnicas o sociales.  Detectar si faltó algún atributo o se perdió por alguna razón (limpieza o código). Detectar si se presenta algún atributo sesjado por algún prejucio (genero, religión, etc) o decisión y balancearlo estadísticamente. 

También el sesgo puede evitarse con la validación cruzada, cuando sistemáticamente se elije el mismo conjunto de entrenamiento podemos caer en sesgo, lo mejor es entrenarlo bajo todos los posibles casos.


5. ¿De qué manera determinas que un conjunto de datos es de buena calidad?

Existen criterios que nos permiten evaluar si nuestro datos son de buen calidad o no.
Podemos evaluar la:

- Exactitud (los datos son confiables y precisos. Reflejan la fuente original sin errores o sesgos) 
- Integridad (brindan suficiente información)
- Singularidad (no presentan duplicados)
- Disponibilidad (son accesibles)
- Legibilidad ( son entendibles o interpretables)


6. Queremos predecir la probabilidad de muerte por enfermedad cardíaca basándonos en tres factores de riesgo: edad, sexo y nivel de colesterol en sangre. ¿Cuál es el algoritmo más adecuado para este caso y por qué?

Podemos utilizar un modelo basado en el teorema de Bayes, facilmente podemos utilizar la probabilidad condicional con base en los tres factores de riesgo para determinar la probilidad de muerte. 


7. Diferencia entre estimación puntual y el intervalo de confianza

La estimación puntual es el valor buscado, que regularmente suele ser dificil determinar, por lo que se estiman intervalos de confianza o intervalos de valores que permiten acotar el o los espacios donde puede estar la estimación puntual. 



8. ¿Qué es una compensación de sesgo-varianza?

A medida que nuestro modelo busca minimizar el error se calcula una función de optimización (error cuadrático medio o error absoluto), estas funciones van compensando la función de sesos y función varianza hasta encontrar el mínimo, que es cuando los dos se interceptan y se encuentra la mejor solución.   


9. ¿A qué desafíos te has enfrentado como profesionista dentro del mundo de la Data?

Tener una buena calidad de datos es complicado en el mundo real.  Generalmente nos enfrentamos a modelos que tienen que realizar predicciones con datos mal estructurados o datos sesgados por lo que se tiene que balancear, limpiar y enriquecer con otras fuentes. 

Procesar grandes volumenes de información.  Rescientemente analicé billones de resitros para detectar ciertos patrones, tuve que utilizar spark, hadoop y parquet para analizar y procesarla. 

Otro reto comun es presentar la información.  Todo el trabajo se refleja en una gráfica o en tomar una decisión y presentarlo es de suma importacia. 

Revisar y probar el código y los algoritmos. No es valido asumir que a la primera todo salió sin errores, cuando se programa se van haciendo ajustes y modificando conforme se toman decisiones. Es importante llevar un codigo limpio con un controlador de versiones (git) para poder probar y asegurarnos que realmente hace lo que queremos. 





10. ¿Qué temas consideras que una persona con interés en formarse como Data Scientist debería de tomar?

En general:
Machine Learning, Visual analytics y Manejo de base de datos.

(Inluye: estadística y matemáticas, python, postgresql y tableu o powerbi). 


