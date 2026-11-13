# Análisis de clientes de ConnectaTel

## Objetivo del proyecto

Analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, utilizando datos hasta 2024.

El propósito es identificar patrones de consumo, detectar valores atípicos y segmentar a los usuarios por edad y nivel de uso para generar recomendaciones comerciales.

## Datasets utilizados

Se utilizaron tres archivos:

- **plans.csv:** Información de los planes de servicio, precios y beneficios incluidos.
- **users_latam.csv:** Información de los clientes, como edad, ciudad, plan contratado y fechas de registro o cancelación.
- **usage.csv:** Registros de llamadas y mensajes realizados por los usuarios.

## Etapas del análisis

1. **Exploración de datos:** Revisión de la estructura, tipos de datos y estadísticas descriptivas.
2. **Limpieza:** Identificación y tratamiento de valores faltantes, edades inválidas y fechas inconsistentes.
3. **Integración:** Agrupación de los registros de consumo y construcción de un perfil por usuario.
4. **Análisis exploratorio:** Visualización de distribuciones mediante histogramas e identificación de valores atípicos con boxplots y el método IQR.
5. **Segmentación:** Clasificación de clientes por edad y nivel de uso.
6. **Análisis ejecutivo:** Interpretación de resultados y elaboración de recomendaciones comerciales.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Cómo ejecutar el proyecto

1. Descargar el archivo `.ipynb` de este repositorio.
2. Abrirlo en Jupyter Notebook, JupyterLab o Google Colab.
3. Contar con los tres datasets originales y las bibliotecas indicadas.
4. Ajustar las rutas de lectura de los archivos CSV según el entorno utilizado.
5. Ejecutar las celdas del notebook en orden, desde la carga de datos hasta el análisis ejecutivo.

**Nota:** El notebook utiliza originalmente las rutas `/datasets/plans.csv`, `/datasets/users_latam.csv` y `/datasets/usage.csv`. Para reproducir el análisis fuera del entorno de TripleTen, es necesario disponer de estos archivos y configurar sus rutas correctamente.

## Principales hallazgos

- El 73.58% de los usuarios presenta un nivel de uso medio.
- El 50.45% de los clientes pertenece al segmento de adultos de 30 a 59 años.
- Se identificaron valores atípicos de consumo que podrían representar oportunidades para desarrollar ofertas especializadas.
- Se recomienda evaluar los beneficios de los planes actuales y considerar ofertas diferenciadas según los patrones de consumo.

## Conclusión

El análisis permitió identificar los principales segmentos de clientes de ConnectaTel y sus patrones de comportamiento. Los resultados proporcionan una base para evaluar mejoras en los planes de servicio y desarrollar estrategias comerciales orientadas a las necesidades de los usuarios.
