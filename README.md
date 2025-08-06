# Proyecto del Grupo 'Better Place To Work'
### Repositorio para el desarrollo del proyecto grupal del Módulo 3, Transformación de datos, de Adalab

En este repositorio tenemos la documentación necesaria para llevar a cabo el análisis exploratorio de los datos sobre los empleados de la empresa ABC Corporation, a la que proporcionaremos información valiosa que informe sus decisiones estratégicas.

ABC Corporation es una consultora tecnológica especializada en ofrecer soluciones de inteligencia artificial (IA) y aprendizaje automático (machine learning) a empresas de diversos sectores. Su enfoque principal radica en automatizar y optimizar procesos empresariales mediante tecnologías de vanguardia.

La empresa se distingue por tener un equipo multidisciplinario que abarca expertos en UX/UI, marketing, analistas, científicos de datos y otros campos relevantes.

El proyecto consta de 5 fases:

Fase 1: Análisis Exploratorio de Datos(EDA).

Es crucial comprender mejor el conjunto de datos y sus características. Para ello realizamos un análisis exploratorio detallado del conjunto de datos para familiarizarnos con ellos y entender qué información tenemos.

Fase 2: Transformación de los datos.

Incluye la limpieza de datos, la normalización, la conversión de tipos de datos y la aplicación de reglas empresariales específicas. Las transformaciones se han realizado mediante funciones de Python que se aplicaron a los datos extraídos. Algunas de las transformaciones realizadas:

- Conversiones de datos, como en la columna Gender que tenía valores de 0 y 1 y han sido reemplazados por "Male" y "Female".

- Algunas columnas, como la columna DailyRate, incluyen valores numéricos decimales que han sido redondeados por comodidad. 

- Otras columnas, como MonthlyIncome, aparecen como columnas de tipo string. Hemos realizado los cambios necesarios para convertirlas en columnas de tipo numérico.

-  Se han evaluado los datos buscando si hay valores duplicados y se ha procedido a su analisis para decidir si tiene sentido eliminarlos o mantenerlos. De igual forma, se han encontrado columnas redundantes, es decir, columnas que nos dan la misma información expresada de forma diferente. Se ha procedido a su análisis y eliminación cuando era necsario.

- Se han encontrado valores inconsistentes, por ejemplo en la columna DistanceFromHome con valores negativos y se ha procedido a su limpieza.

- También se han encontrado errores tipográficos, por ejemplo en la columna MaritalStatus en vez de "Married" en algunas filas aparece "Marreid" y han sido corregidas.



Fase 3: Visualizando los datos.

El objetivo de esta fase es proporcionar a ABC Corporation un informe detallado del contexto general de la empresa utilizando visualizaciones en Python. Este informe permitirá una comprensión más profunda de la situación actual y servirá como base para la toma de decisiones informadas.

Hemos generado un informe completo que incluye las visualizaciones junto con análisis descriptivos. Las visualizaciones ayuda a resaltar tendencias, áreas de mejora y fortalezas dentro de la empresa.

Fase 4: Diseño de BBDD e Insercción de los Datos.

En esta fase tiene como objetivo la creación y la inserción de datos en una base de datos desde el punto de vista de su arquitectura o estructura, es decir, definir como seria su BBDD final. Los aspectos principales de esta fase del proyecto son:

- Diseño de la Estructura de la Base de Datos: Hemos definido la estructura de la base de datos, identificando las tablas necesarias y sus relaciones, así como definiendo las claves primarias y foráneas.

- Creación de la Base de Datos: utilizando las herramientas aprendidas en el módulo 2 (connector de Python con MySQL).

- Inserción de Datos Iniciales: Hemos insertado los datos de los empleados de la empresa en la base de datos.

Fase 5: Creación de una ETL.(Bonus)

En esta fase del proyecto, deberás crear un archivo .py que llevará a cabo la extracción, transformación y carga (ETL) de datos. El objetivo de esta etapa es automatizar la inserción de datos en la base de datos relacional y garantizar que la información se actualice de manera consistente y también automatizar el proceso de transformación de la información antes de la inserción en la BBDD. Los pasos que deberás seguir en esta fase son:

- Extracción de Datos: En esta primera parte de la ETL, las alumnas desarrollarán una función para extraer datos desde las fuentes de datos previamente definidas. Estas fuentes pueden incluir hojas de cálculo, archivos CSV, bases de datos externas o cualquier otro formato de datos relevante. El objetivo es obtener datos frescos y relevantes que se cargarán en la base de datos.

- Transformación de Datos: Deberás desarrollar una función (o varias) para aplicar todas las transformaciones necesarias para garantizar la integridad y la calidad de los datos (estas transformaciones serán las mismas que en la fase 2).

- Creación de la Base de Datos: En esta etapa, crearás una función con el código para la creación de la BBDD diseñada en la fase 3.

- Carga de Datos: Después de la creación de las tablas, desarrollaras funciones que permitan la inserción de datos transformados en la base de datos. Esto garantizará que la base de datos esté siempre actualizada con la información más reciente.

NOTA Todo este código deberá estar en funciones y en archivos .py.
