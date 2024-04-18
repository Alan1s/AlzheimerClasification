4 de abril de 2024

Kevin Jaimes Carrillo 
Juan Buitrago
Alanis Forero Salas

Objetivos:
  Clustering: Usar técnicas de clustering para identificar grupos de estados o regiones similares basados en métricas de salud específicas
  Regresion: Entender las relaciones entre diferentess factores y el resultado de salud en los datos
  Clasificación supervisada: Predecir un resultado de salud categórico basado en un conjunto de predictores.

18 de abril de 2024

Resumen de datos:

- Estadísticas Descriptivas: Las columnas YearStart, YearEnd, Data_Value, Data_Value_Alt, LocationID y LocationDesc_encoded son numéricas. Tienes estadísticas como la media, el mínimo, el máximo, y los cuartiles que te dan una idea de la distribución de los datos. Por ejemplo, la media de Data_Value es aproximadamente 35.69, lo que podría representar un porcentaje medio sobre alguna métrica de salud o comportamiento ya que los valores se mueven entre 0 y 100.
- Valores Únicos: La frecuencia que aparecen en diferentes columnas categóricas valores unicos. Por ejemplo, la columna RowId tiene 31,676 valores únicos, lo que sugiere que hay una gran cantidad de entradas individuales que podrían representar registros únicos en tu conjunto de datos.
- Columnas Específicas: Observar que ciertas columnas como Class, Topic, y Question contienen categorías o preguntas específicas. Por ejemplo, Class incluye categorías como 'Overall Health' y 'Screenings and Vaccines', que indican diferentes áreas de salud o tipos de datos recopilados.
- Notas al Pie y Símbolos: Hay símbolos y notas al pie en algunas columnas como Data_Value_Footnote_Symbol y Data_Value_Footnote, los cuales parecen indicar aspectos importantes sobre la calidad o la interpretación de los datos que no deben ser ignorados.
- Estratificación: Las columnas que empiezan con Stratification  muestran cómo se segmentan los datos, por ejemplo, por grupo de edad, raza/etnia o género.

RowId                          object
YearStart                       int64
YearEnd                         int64
LocationAbbr                   object
LocationDesc                   object
Datasource                     object
Class                          object
Topic                          object
Question                       object
Data_Value_Unit                object
DataValueTypeID                object
Data_Value_Type                object
Data_Value                    float64
Data_Value_Alt                float64
Data_Value_Footnote_Symbol     object
Data_Value_Footnote            object
Low_Confidence_Limit          float64
High_Confidence_Limit         float64
StratificationCategory1        object
Stratification1                object
StratificationCategory2        object
Stratification2                object
Geolocation                    object
ClassID                        object
TopicID                        object
QuestionID                     object
LocationID                      int64
StratificationCategoryID1      object
StratificationID1              object
StratificationCategoryID2      object
StratificationID2              object
LocationDesc_encoded             int8
dtype: object
