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
