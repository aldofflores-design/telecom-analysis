# telecom-analysis
📊 Análisis de Segmentación y Calidad de Datos: ConnectaTel
Este proyecto consiste en un análisis de datos (EDA) aplicado al sector de telecomunicaciones. El objetivo principal es limpiar una base de datos de usuarios, detectar comportamientos de consumo extremo y segmentar a los clientes para mejorar la toma de decisiones comerciales.

🎯 Objetivo del Proyecto
Optimizar la estrategia comercial de ConnectaTel mediante:

Limpieza de Datos: Corregir inconsistencias y valores nulos en el perfil de usuario.

Análisis de Outliers: Identificar "Heavy Users" mediante el método estadístico IQR.

Segmentación: Clasificar a los usuarios por edad y nivel de uso (Llamadas/Mensajes).

Generación de Insights: Proponer mejoras en la oferta de planes tarifarios.

📂 Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

users.csv: Información demográfica (edad, ciudad, fecha de registro, plan).

calls.csv: Registro de llamadas (duración y fecha).

messages.csv: Registro de mensajes de texto enviados.

🛠️ Etapas del Análisis
Exploración Inicial: Identificación de tipos de datos y valores faltantes.

Preprocesamiento (Data Wrangling): * Tratamiento de valores centinela (ej. edad -999).

Conversión de tipos (fechas y números).

Unión de tablas (Merge) para crear un perfil único de usuario.

Detección de Outliers: Visualización con Boxplots y cálculo de límites mediante el Rango Intercuartílico (IQR).

Segmentación: Creación de categorías de grupo_uso y grupo_edad mediante lógica condicional.

Visualización: Gráficos de distribución (Seaborn/Matplotlib) para validar los segmentos encontrados.
