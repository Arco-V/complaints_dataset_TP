# complaints_dataset_TP
## Introducción
En el mundo financiero, la satisfacción del cliente es un factor crítico para el éxito y la reputación de una compañía. Las quejas de los consumidores pueden proporcionar una valiosa fuente de información para identificar áreas problemáticas y mejorar los productos y servicios ofrecidos. Este trabajo se centra en el análisis de una base de datos que contiene quejas de consumidores sobre diversos productos financieros proporcionados por diferentes compañías con el fin de entender qué productos deberían revisarse y sus puntos débiles, cuáles empresas podrían presentar problemas con sus niveles de satisfacción. Además se suma una nube de palabras más frecuentes en las quejas para poder tener una interpretación cualitativa de los problemas.
## Problema de Negocio
El problema de negocio que se aborda en este análisis es la insatisfacción de los clientes con ciertos productos o servicios financieros, analizando principalmente las variables de productos, cantidad de quejas por productos, los problemas relacionados a ellos y sus tendencias temporales. La capacidad de una compañía para identificar y abordar de manera efectiva las áreas problemáticas es crucial para mejorar la satisfacción del cliente y, por ende, la retención y lealtad del mismo.
## Objetivo del análisis
El objetivo principal de este análisis es tener una comprensión más profunda de las quejas de los clientes de las compañías financieras. Al identificar tendencias y ver cómo se distribuyen los datos reportados, podemos ayudar a las compañías a tomar acciones correctivas específicas para mejorar sus productos y servicios, lo cual resultará en una mayor satisfacción del cliente y una mejor reputación en el mercado.
## Descripción de la Base de Datos
La base de datos utilizada en este análisis incluye información detallada sobre las quejas de los consumidores. Los campos de la base de datos son:
-Date received: Fecha en que se recibió la queja
-Product: Producto
-Sub-product: Subproducto
-Issue: Problema
-Sub-issue: Subproblemas
-Consumer complaint narrative: Narrativa de la queja del consumidor
-Company public response: Respuesta pública de la compañía
-Company: Compañía
-State: Estado
-ZIP code: Código postal
-Tags: Etiquetas
-Consumer consent provided?: ¿Consentimiento del consumidor proporcionado?
-Submitted via: Enviado a través de..
-Date sent to company: Fecha en que se envió a la compañía
-Company response to consumer: Respuesta de la compañía al consumidor
-Timely response?: ¿Respuesta oportuna?
-Consumer disputed?: ¿Disputado por el consumidor?
-Complaint ID: ID de la queja

## Conclusión
Se identificó que los productos con mayor quejas son: “debt collection”, “credit reporting, credit repair services or other personal consumer reports”, “mortgage”, “credit reporting”, “credit card” y “bank account or service”, por lo que la recomendación sería poner foco en estos inicialmente en estos para implementar mejoras. 

En general, se pudo identificar tanto el principal problema como la mayor razón de las quejas. Es evidente que la hipoteca es el producto que más quejas genera entre los clientes, mientras que el problema más frecuente es el de la información errónea. Para aumentar la satisfacción de los clientes, se deberá mejorar la comunicación de la información tanto de las hipotecas como de los reportes crediticios y la colección de deudas. Además, se deberá mejorar el sistema de supervisión de datos a la hora de realizar los reportes. 

## Próximos Pasos
Habiendo analizado los principales productos que causan quejas y cuáles son los problemas asociados, hay otra serie de análisis que puede ser útil para realizar en un futuro. Estos pueden resolver distintos problemas de negocio con este mismo dataset.
### Efectividad del Equipo en la Resolución de Quejas:
- Tiempo de Respuesta Oportuno (Timely Response): Analiza cómo el tiempo de respuesta afecta la satisfacción del cliente y la resolución de las quejas. Se podrían calcular métricas como el tiempo promedio de respuesta y compararlo con la satisfacción del cliente o la resolución satisfactoria de las quejas.
- Respuesta Pública de la Empresa (Company Public Response): Evalúa cómo las respuestas públicas de la empresa afectan la percepción del cliente y la resolución de las quejas. Se podrían categorizar las respuestas públicas según su tono (positivo, neutral, negativo) y analizar su impacto en la satisfacción del cliente.
### Análisis de Problemas por Ubicación:
- Correlación entre Quejas y Ubicación (State): Examina si existe alguna correlación entre la cantidad o tipo de quejas y la ubicación geográfica del cliente (estado). Se podrían realizar análisis estadísticos para identificar patrones geográficos en las quejas. Por ejemplo, ¿ciertos estados tienen más problemas con productos financieros específicos?
- Análisis Espacial: Utiliza técnicas de visualización geoespacial para mapear las quejas por ubicación y ver patrones espaciales en los datos. Esto podría ayudar a identificar áreas geográficas con problemas específicos que podrían requerir atención especializada.
### Análisis de Tendencias Temporales:
- Eventos Externos: Examina si eventos externos como cambios regulatorios, campañas publicitarias, o crisis económicas afectan la cantidad y tipo de quejas recibidas.
Segmentación y Perfiles de Clientes:
- Segmentación de Clientes: Utiliza técnicas de clustering para agrupar clientes basados en el tipo y frecuencia de sus quejas. Esto puede revelar segmentos de clientes con necesidades o problemas específicos que pueden ser abordados de manera diferente.
### Análisis Predictivo y Modelos de Machine Learning:
- Predicción de quejas: Desarrolla modelos predictivos para anticipar la cantidad y tipo de quejas futuras. Se podrían utilizar técnicas como regresión, clasificación o modelos de series temporales para prever patrones de quejas.
- Análisis de Sentimientos: Aplica análisis de sentimientos a las narrativas de quejas para entender mejor la tonalidad y emociones detrás de las quejas. Esto puede proporcionar información adicional sobre la satisfacción del cliente y áreas de mejora.

