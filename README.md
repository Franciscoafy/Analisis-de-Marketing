#Análisis de Ventas por Medio Publicitario
Este notebook realiza un análisis de las ventas en función del presupuesto invertido en diferentes medios publicitarios: TV, radio y periódicos. Se utilizan técnicas de regresión para entender el impacto de cada medio en las ventas y se exploran varios escenarios de redistribución del presupuesto para maximizar el retorno de inversión (ROI).

Contenido
Estructura de Carpetas

ANALISIS_VENTAS
├── data
├── documents
├── models
├── notebooks
├── requirements
├── scripts
├── environments.yml
└── README.md
data: Contiene los archivos de datos utilizados en el análisis.
documents: Documentación relacionada con el proyecto.
models: Modelos de machine learning guardados.
notebooks: Notebooks de Jupyter, incluyendo ventas_por_medio.ipynb.
requirements: Archivos de requerimientos para las dependencias de Python.
scripts: Scripts de Python utilizados en el análisis.
environments.yml: Archivo para configurar el entorno de conda.
README.md: Archivo README del proyecto


Carga de Datos

Se carga un conjunto de datos publicitarios bicado en la capeta "DATA" (Advertising.csv) que incluye columnas de presupuesto en TV, radio y periódicos, junto con las ventas resultantes.
Exploración de Datos

Visualizaciones iniciales y estadísticas descriptivas para entender la distribución y relación de los datos.
Análisis de Regresión

Se implementa un modelo de regresión lineal para identificar la relación entre el presupuesto en cada medio publicitario y las ventas.
Se examinan los coeficientes del modelo para determinar la influencia de cada medio.
Escenarios de Redistribución del Presupuesto

Se simulan diferentes escenarios de redistribución del presupuesto entre TV, radio y periódicos.
Se analiza el impacto de estos cambios en las ventas proyectadas.
Conclusiones

Se concluye que los medios de radio y periódicos tienen un mayor retorno de inversión (ROI) debido a sus menores costos.
Se destaca la sinergia entre TV y radio en términos de impacto en las ventas.
Se identifican escenarios prometedores para la redistribución del presupuesto, sugiriendo que hay un punto de equilibrio donde cambiar la inversión de TV a radio maximiza las ventas.

Uso
Para ejecutar este notebook, necesitas tener instalado:

Python 3.x
Jupyter Notebook
Las siguientes bibliotecas de Python:
pandas
numpy
matplotlib
seaborn
scikit-learn
Ejecución
Clona este repositorio o descarga el archivo ventas_por_medio.ipynb.
Abre el archivo en Jupyter Notebook.
Ejecuta todas las celdas para reproducir el análisis y las visualizaciones.
Estructura de Datos
El conjunto de datos utilizado contiene las siguientes columnas:

TV: Presupuesto invertido en TV.
Radio: Presupuesto invertido en radio.
Newspaper: Presupuesto invertido en periódicos.
Sales: Ventas generadas.
Visualizaciones
Se incluyen varias visualizaciones para explorar la relación entre el presupuesto en diferentes medios y las ventas:

Gráficos de dispersión para TV, radio y periódicos vs. ventas.
Diagramas de regresión para mostrar las líneas de mejor ajuste.
Gráficos comparativos de diferentes escenarios de redistribución del presupuesto.

#Autor
[Francisco Flores]
Contacto: [Franciscof22_54@hotmail.es]
¡Gracias por revisar este proyecto! Si tienes alguna pregunta o sugerencia, no dudes en contactarme.