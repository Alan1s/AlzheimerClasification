4 de abril de 2024

Kevin Jaimes Carrillo 
Juan Buitrago
Alanis Forero Salas

Objetivos:
  Clustering: Aplicar un metodo de clustering con el tema "Mental Health" y realizar el clustering de las regiones basado en las respuestas a las preguntas relacionadas con este tema.
Regresion: Predecir el valor del estrés mental frecuente basado en otros variables de entrada
18 de abril de 2024

Resumen de datos:

- Estadísticas Descriptivas: Las columnas YearStart, YearEnd, Data_Value, Data_Value_Alt, LocationID y LocationDesc_encoded son numéricas. Tienes estadísticas como la media, el mínimo, el máximo, y los cuartiles que te dan una idea de la distribución de los datos. Por ejemplo, la media de Data_Value es aproximadamente 35.69, lo que podría representar un porcentaje medio sobre alguna métrica de salud o comportamiento ya que los valores se mueven entre 0 y 100.
- Valores Únicos: La frecuencia que aparecen en diferentes columnas categóricas valores unicos. Por ejemplo, la columna RowId tiene 31,676 valores únicos, lo que sugiere que hay una gran cantidad de entradas individuales que podrían representar registros únicos en tu conjunto de datos.
- Columnas Específicas: Observar que ciertas columnas como Class, Topic, y Question contienen categorías o preguntas específicas. Por ejemplo, Class incluye categorías como 'Overall Health' y 'Screenings and Vaccines', que indican diferentes áreas de salud o tipos de datos recopilados.
- Notas al Pie y Símbolos: Hay símbolos y notas al pie en algunas columnas como Data_Value_Footnote_Symbol y Data_Value_Footnote, los cuales parecen indicar aspectos importantes sobre la calidad o la interpretación de los datos que no deben ser ignorados.
- Estratificación: Las columnas que empiezan con Stratification  muestran cómo se segmentan los datos, por ejemplo, por grupo de edad, raza/etnia o género.

Columna                         | Descripción
--------------------------------|---------------------------------------------------------
RowId                           | Identificador único para cada fila del conjunto de datos.
YearStart                       | Año de inicio del periodo de recolección de datos.
YearEnd                         | Año de fin del periodo de recolección de datos.
LocationAbbr                    | Abreviatura del nombre de la ubicación geográfica (generalmente estados de EE.UU.).
LocationDesc                    | Descripción completa de la ubicación geográfica.
Datasource                      | Fuente de los datos recogidos.
Class                           | Clasificación general del tipo de datos recogidos (por ejemplo, información de salud).
Topic                           | Tema específico del conjunto de datos (por ejemplo, salud mental).
Question                        | Pregunta específica a la que responden los datos.
Data_Value_Unit                 | Unidad de medida del valor de los datos (por ejemplo, porcentaje).
DataValueTypeID                 | Identificador del tipo de valor de datos.
Data_Value_Type                 | Tipo de valor de datos (por ejemplo, promedio).
Data_Value                      | Valor numérico concreto de la respuesta.
Data_Value_Alt                  | Valor alternativo o adicional relacionado con `Data_Value`.
Data_Value_Footnote_Symbol      | Símbolo utilizado para anotaciones a pie de página en los valores de datos.
Data_Value_Footnote             | Texto explicativo asociado a una anotación a pie de página.
Low_Confidence_Limit            | Límite inferior del intervalo de confianza para el valor de los datos.
High_Confidence_Limit           | Límite superior del intervalo de confianza para el valor de los datos.
StratificationCategory1         | Primera categoría de estratificación de los datos (por ejemplo, edad).
Stratification1                 | Detalle específico dentro de la primera categoría de estratificación.
StratificationCategory2         | Segunda categoría de estratificación de los datos, si aplica.
Stratification2                 | Detalle específico dentro de la segunda categoría de estratificación.
Geolocation                     | Datos de geolocalización asociados a la ubicación.
ClassID                         | Identificador de la clasificación de los datos.
TopicID                         | Identificador del tema del conjunto de datos.
QuestionID                      | Identificador de la pregunta específica dentro del conjunto de datos.
LocationID                      | Identificador numérico único para cada ubicación.
StratificationCategoryID1       | Identificador para la primera categoría de estratificación.
StratificationID1               | Identificador para el detalle específico dentro de la primera categoría de estratificación.
StratificationCategoryID2       | Identificador para la segunda categoría de estratificación, si aplica.
StratificationID2               | Identificador para el detalle específico dentro de la segunda categoría de estratificación.
LocationDesc_encoded            | Código numérico que representa la ubicación descripción de forma codificada.
--------------------------------|---------------------------------------------------------
