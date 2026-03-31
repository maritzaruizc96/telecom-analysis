# telecom-analysis
Análisis de Segmentación de Clientes - ConnectaTel
🎯 Objetivo del Proyecto
El propósito de este análisis es identificar patrones de comportamiento y consumo en la base de usuarios de ConnectaTel. Mediante el uso de técnicas de limpieza de datos y segmentación estadística, buscamos clasificar a los clientes por su nivel de actividad (bajo, medio, alto) y su rango generacional. Esto permitirá al equipo de marketing y producto diseñar estrategias de fidelización más precisas y ajustar la oferta comercial actual.
📊 Datasets Utilizados
Para este proyecto se utilizó un conjunto de datos denominado user_profile que contiene la siguiente información:
 * age: Edad del usuario (utilizada para segmentación demográfica).
 * cant_mensajes: Cantidad total de mensajes enviados.
 * cant_llamadas: Cantidad total de llamadas realizadas.
 * cant_minutos_llamada: Duración total acumulada de las llamadas (minutos).
 * Nota: El dataset consta de aproximadamente 4,000 registros de usuarios únicos.
🛠️ Etapas del Análisis
El flujo de trabajo se dividió en las siguientes fases:
 * Limpieza de Datos: Tratamiento de valores nulos e identificación de valores atípicos (outliers) mediante el método del Rango Intercuartílico (IQR).
 * Ingeniería de Características: Creación de nuevas variables categóricas (grupo_uso y grupo_edad) mediante lógica condicional en Python.
 * Análisis Exploratorio (EDA): Visualización de la distribución de los segmentos creados para identificar la masa crítica de clientes.
 * Generación de Insights: Redacción de conclusiones ejecutivas para la toma de decisiones estratégicas.
🚀 Cómo ejecutar el Notebook
Para visualizar y reproducir este análisis, sigue estos pasos:
 * Opción Google Colab: * Sube el archivo .ipynb a tu Drive.
   * Haz clic derecho sobre el archivo y selecciona "Abrir con Google Colaboratory".
 * Entorno Local (Jupyter):
   * Asegúrate de tener instalada una distribución de Python (como Anaconda).
   * Ejecuta jupyter notebook en tu terminal y abre el archivo del proyecto.
📋 Guía de Reproducción
Para obtener los mismos resultados presentados en este análisis:
 * Asegúrate de tener instaladas las librerías necesarias: pandas, numpy, matplotlib y seaborn.
 * Carga el archivo de datos al inicio del notebook.
 * Ejecuta las celdas en orden secuencial (de arriba hacia abajo) para asegurar que las variables y columnas nuevas se creen correctamente antes de graficar.
 * En la sección de Visualización, las gráficas se generarán automáticamente mostrando la distribución por uso y edad.
