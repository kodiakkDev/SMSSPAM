# Colección de SMS Spam

---

Este es un corpus de texto de más de 5,500 mensajes SMS en inglés con aproximadamente el 13% etiquetados como spam. 

El archivo de texto contiene un mensaje por línea con dos columnas: la etiqueta ("ham" o "spam") y el texto crudo del mensaje. Los mensajes etiquetados como "ham" son mensajes no spam que se pueden considerar legítimos.


Fuente del conjunto de datos. Este corpus fue creado por Tiago A. Almeida y José María Gómez Hidalgo.

> Almeida, T.A., Gómez Hidalgo, J.M., Yamakami, A. Contribuciones al Estudio del Filtrado de SMS Spam: Nueva Colección y Resultados. Actas del Simposio ACM de 2011 sobre Ingeniería de Documentos (DOCENG'11), Mountain View, CA, EE.UU., 2011.

>Gómez Hidalgo, J.M., Almeida, T.A., Yamakami, A. Sobre la Validez de una Nueva Colección de SMS Spam. Actas de la 11ª Conferencia Internacional IEEE sobre Aprendizaje Automático y Aplicaciones (ICMLA'12), Boca Raton, FL, EE.UU., 2012.

> Almeida, T.A., Gómez Hidalgo, J.M., Silva, T.P. Hacia el Filtrado de SMS Spam: Resultados bajo un Nuevo Conjunto de Datos. Revista Internacional de Ciencia de la Seguridad de la Información (IJISS), 2(1), 1-18, 2013.

## Objetivos

- 🗺️ Explorar: ¿Cuáles son las palabras más comunes en los mensajes de spam frente a los mensajes normales?

- 📊 Visualizar: Crea una nube de palabras que visualice las palabras más comunes en el conjunto de datos.

- 🔎 Analizar: ¿Qué palabra tiene más probabilidades de indicar que un mensaje es spam?

## Contexto

Una empresa de telecomunicaciones que está lanzando una nueva aplicación de mensajería. Desafortunadamente, los filtros de spam anteriores que han utilizado están desactualizados y ya no son efectivos. Te han preguntado si puedes usar los nuevos datos que han proporcionado para distinguir con precisión entre mensajes de spam y mensajes regulares. También te han dicho que es esencial que __los mensajes regulares rara vez, o nunca, se categorizen como spam__.

> prepara un informe que sea accesible para una audiencia amplia. Debe esbozar tu motivación, pasos, hallazgos y conclusiones.


## Contenido del procesos de analisis 

- Exploracion Inicial
  1. Obtencion de los datos.
  2. Visualizaciones exploratorias.
  3. Aplicacion de estadistica basica.
- Preprocesamiento de Datos.
  1. Limpieza de Datos.
  2. Tokenizacion.
  3. Eliminacion de stopwords.
  4. Lematizacion/Steamming.
- Alisis Exploratorio de Datos (EDA). 
  1. Palabras Más Comunes.
  2. Visualización de datos.
  3. Análisis de Palabras Clave.
- Modelo de ML.
  1. Seleccion.
  2. Entrenamineto.
  3. Evaluacion.

 ## Metodologia

### Datos

| variable | clase  | descripción                                                     |
| -------- | ------ | --------------------------------------------------------------- |
| 0        | String | Cadena de texto que identifica si el mensaje es 'ham' o 'spam'. |
| 1        | String | Cadena de texto que representa el mensaje.                      |


### Tools

- Python: latest
- Conda: latest
- Pandas: latest
- Plotly: latest
- Nltk: latest
- Wordcloud: latest
- Sklearn
