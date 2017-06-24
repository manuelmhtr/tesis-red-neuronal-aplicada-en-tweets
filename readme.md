# Predicción del impacto en mensajes de Twitter mediante redes neuronales

Por: Manuel Honorio de la Torre Ramírez

### Resumen

El objetivo de este proyecto de investigación es desarrollar un modelo de predicción, para la cantidad de impacto, medido en clics, retweets y favoritos, que va a obtener un mensaje en Twitter (conocido como tweet), mediante el uso de una red neuronal artificial.

El modelo tomará como entradas un conjunto de factores que se pueden medir al momento de la publicación de un tweet. Estos factores son propuestos de acuerdo a su relevancia en trabajos previos y su correlación con el impacto del mensaje, y se pueden dividir en dos tipos: datos de la cuenta de Twitter desde la que se publicó el mensaje y datos sobre el contenido del mensaje.

Se recolectó una muestra de 46,137 tweets que dentro de su contenido tuvieran un link (con el objetivo de medir los clics obtenidos). Posteriormente se realizó un modelo de ecuaciones estructurales (PLS-PM) con el fin de analizar la correlación de los factores de entrada en la salida y validar su utilización en el modelo de predicción. Finalmente se construyó la red neuronal artificial, con una arquitectura perceptrón multicapa, que predice el impacto de un mensaje de Twitter; esta red se entrenó utilizando la mitad de los datos recolectados (set de entrenamiento) y una vez lista, se aplicó a la otra mitad de los datos (set de prueba) para validar su correcto funcionamiento y presentar los resultados del modelo.

La innovación de este trabajo radica en que, hasta donde se tiene conocimiento, es el primer modelo que predice clics, retweets y favoritos simultáneamente; así como el primer trabajo en incluir los puntajes de influencia de [Klout](https://klout.com) y [Moz](https://moz.com) (empresas dedicadas al marketing en redes sociales) como parte de las entradas del modelo, ya que están estrechamente relacionados con el desempeño histórico de las interacciones que tiene la audiencia de un usuario hacia los mensajes que publica.

Dentro de las aplicaciones de esta investigación, están el área de marketing digital, el estudio de comportamientos humanos en internet y el estudio de la influencia en redes sociales. Mantener la infraestructura tecnológica y humana que requieren las grandes redes sociales cuesta millones de dólares, y muchos se preguntan cómo que es que ofrecen sus servicios gratuitamente; pues bien, lo logran gracias a la publicidad, que está estrechamente relacionado con el “impacto” estudiado en esta investigación. Al lograr predecirlo correctamente, se está prediciendo un mercado que genera billones de dólares al año; he ahí su valor.