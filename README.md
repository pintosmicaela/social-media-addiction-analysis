# Adicción a las redes sociales en estudiantes – Análisis y visualización de datos

Proyecto de análisis exploratorio y visualización de datos realizado en la materia **Elementos de Visualización de Información**. Analiza cómo el uso de redes sociales se relaciona con la salud mental, el sueño y las relaciones personales de estudiantes.

**Autores:** Micaela Pintos y Claudio Solis

📊 **Dashboard interactivo:** [Tableau Public – Proyecto Visualización de Datos (Solis, Pintos)](https://public.tableau.com/)
📄 **Informe completo:** [`informe/Proyecto-Visualizacion-Adiccion-Redes-Sociales.pdf`](informe/Proyecto-Visualizacion-Adiccion-Redes-Sociales.pdf)

## Habilidades aplicadas

- Análisis exploratorio de datos (EDA)
- Formulación de preguntas de negocio/investigación y validación con datos
- Visualización con **Tableau**: scatter plots, tree maps, gráficos de barras, burbujas y dashboards
- Segmentación y comparación por variables categóricas (género, estado civil, nivel académico, país)
- Comunicación de hallazgos (storytelling con datos)

## Dataset

[Social Media Addiction vs Relationships](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships) (Kaggle, autor: adilshamim8). Aproximadamente 700 estudiantes.

| Variable | Descripción |
|---|---|
| `Age`, `Gender`, `Academic_Level`, `Country` | Datos demográficos |
| `Avg_Daily_Usage_Hours` | Horas promedio de uso diario |
| `Most_Used_Platform` | Plataforma más utilizada |
| `Sleep_Hours_Per_Night` | Horas de sueño por noche |
| `Mental_Health_Score` | Puntaje de salud mental |
| `Relationship_Status` | Estado de la relación |
| `Conflicts_Over_Social_Media` | Conflictos por redes sociales |
| `Addicted_Score` | Puntaje de adicción |

> El dataset no se redistribuye en este repositorio; descargalo desde Kaggle respetando su licencia.

## Preguntas planteadas

1. ¿Cómo se relacionan las horas de sueño con la salud mental y el nivel de adicción?
2. ¿Qué plataformas son las más usadas y cómo se vinculan con las horas de uso y la adicción?
3. ¿Qué relación hay entre el nivel de adicción y los conflictos en pareja, según estado civil y género?

## Hallazgos principales

- **Sueño:** a más horas de sueño, mejor puntaje de salud mental y menor puntaje de adicción.
- **Plataformas:** WhatsApp, TikTok y Snapchat son las más utilizadas.
- **Relaciones:** un mayor nivel de adicción se asocia con más conflictos vinculados a redes sociales.

## Limitaciones

Es un análisis observacional sobre datos de una encuesta: los resultados muestran **asociaciones, no causalidad**. Además, la muestra (~700 estudiantes) puede no ser representativa de toda la población.

## Estructura

```
.
├── README.md
└── informe/
    └── Proyecto-Visualizacion-Adiccion-Redes-Sociales.pdf
```

## Próximos pasos

- Reproducir el análisis en Python (pandas, matplotlib/seaborn) en un notebook.
- Agregar pruebas de correlación y regresión para cuantificar las relaciones.
- Limpieza y validación de datos documentadas.
