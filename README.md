# RainyRoadsMadrid

## Descripción
Dashboard en Power BI que analiza la relación entre la lluvia y los accidentes de tráfico en Madrid, mostrando las calles más peligrosas durante episodios de lluvia.

## Objetivo
Demostrar cómo la lluvia afecta la seguridad vial y proporcionar una herramienta visual para concienciar y planificar medidas preventivas.

## Datasets y fuentes
- Lluvia: datos públicos de [AEMET / Comunidad de Madrid]
- Calidad del aire: datos públicos de [Ayuntamiento de Madrid]
- Accidentes de tráfico: datos públicos de [Ayuntamiento de Madrid]
- Licencias: todos los datos son abiertos y con permisos de reutilización.

## Flujo de trabajo / Arquitectura
1. Exploración de datos de lluvia y calidad del aire.
2. Correlación entre calidad del aire y lluvia para estimar días con lluvia.
3. Unión con datos de accidentes.
4. Modelo predictivo para inferir si llovió cuando el dato faltaba.
5. Creación de un dashboard en Power BI para visualizar los resultados.

## Cómo ejecutar / reproducir
- Abrir el archivo .pbix en Power BI Desktop.
- Abrir `notebooks/` con Jupyter o Google Colab.

## Límites y ética
- Solo se usan datos públicos y anonimizados.
- Las correlaciones no implican causalidad.
- Posibles sesgos en predicciones del modelo de lluvia.

## Licencia
MIT License
