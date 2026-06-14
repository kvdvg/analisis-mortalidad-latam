# Análisis de Mortalidad y Gasto en Salud — Latinoamérica 2018–2022

## Descripción
Pipeline completo de análisis de datos sobre mortalidad por enfermedades crónicas 
y gasto en salud en 12 países de Latinoamérica durante el período 2018–2022.

## Herramientas
- Python (pandas, numpy, matplotlib, seaborn)
- SQL (SQLite con SQLAlchemy)
- Google Colab
- Power BI Desktop

## Fuentes de datos
- OPS/OMS — Indicadores Básicos de Salud 2023
- Banco Mundial — Health Expenditure (SH.XPD.CHEX.GD.ZS)

## Estructura del proyecto
- `analisis_mortalidad_latam.ipynb` — Notebook completo con las 5 fases del análisis
- `salud_latam.csv` — Dataset integrado (60 registros, 10 variables)
- `ranking_mortalidad.csv` — Ranking de mortalidad cardiovascular por país
- `gasto_vs_mortalidad.csv` — Relación gasto en salud vs mortalidad
- `impacto_covid.csv` — Impacto del COVID-19 por país
- `eficiencia_sistemas.csv` — Índice de eficiencia del sistema de salud
- `colombia_vs_latam.csv` — Colombia vs promedio latinoamericano
- `analisis_mortalidad_latam.png` — Visualizaciones del análisis
- `Analisis_Mortalidad_LATAM.pbix` — Dashboard ejecutivo en Power BI

## Hallazgos principales
- Argentina y Venezuela presentan la mayor mortalidad cardiovascular de la región
- Colombia tuvo el menor impacto del COVID-19 en mortalidad cardiovascular (8.8%)
- Colombia está consistentemente por debajo del promedio latinoamericano
- Mayor gasto en salud no garantiza menor mortalidad cardiovascular
