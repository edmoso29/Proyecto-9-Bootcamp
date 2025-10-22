Proyecto Bootcamp 9

•	Objetivo: Análisis de datos para la optimización de gastos de marketing de la empresa Showz.

•	Librerías principales: pandas, numpy, matplotlib.pyplot, seaborn, scipy.stats y/o statsmodels.

•	Carga y preprocesado:
  Lectura de uno o varios CSV/TSV (ruta relativa/absoluta).
  Renombrado de columnas y casting (IDs a str, timestamps a datetime con pd.to_datetime).
  Extracción de columnas derivadas: event_date, event_hour, flags binarios, cohort/date buckets.
  Eliminación/gestión de duplicados y nulos; generación de agregados por usuario/evento.

•	Análisis exploratorio de Datos:
  Conteos totales de eventos y usuarios únicos; tasas promedio de eventos por usuario.
  Distribuciones temporales (por fecha/hora), gráficos de series/barplots y heatmaps para actividad.
  Identificación de eventos clave y construcción de embudo: usuarios únicos por etapa y tasas de conversión entre pasos.

•	Agrupación y segmentación:
  Agrupados por experimento/variant (exp_id u otra columna) para comparar cohorts.
  Tablas pivot y resúmenes por grupo (usuarios, eventos, conversion rates).

•	Pruebas estadísticas y validación:
  Comparaciones de proporciones entre grupos (z-test / proportions_ztest) para eventos de conversión.
  Construcción de tablas de p-values por evento; decisión con alpha = 0.05.
  Posible uso de tests adicionales (chi2, t-test) según la métrica.

•	Resultados y outputs:
  Tablas resumen: usuarios por evento, conversion rates por etapa y por grupo experimental.
  Gráficos que ilustran embudo, evolución temporal y diferencias entre variantes.
  Conclusiones finales que sintetizan hallazgos y recomendaciones de producto/experimentación.
