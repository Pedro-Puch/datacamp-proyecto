# datacamp-proyecto
# Analyzing the Effectiveness of a Test Preparation Course

Notebook de competencia (DataCamp): impacto de un curso de preparación en puntajes de **math, reading, writing** y relación con **nivel educacional de los padres**.

## Dataset
- 1.000 estudiantes, 8 columnas (3 numéricas; 5 categóricas).
- Sin valores faltantes; puntajes 1–100.
- Archivo ejemplo: `data/exams.csv` (o link a la fuente si no lo incluyes).

## Metodología (resumen)
- EDA y validación básica (descriptivos, distribuciones, outliers).
- Comparaciones de medias por **test_prep_course** y **parent_education_level**.
- Variable **average** = (math+reading+writing)/3.
- Correlaciones y visualizaciones (pairplot / heatmap).

## Hallazgos clave
- **Curso de preparación** mejora *reading*: con curso ≈ **73.9**, sin curso ≈ **66.5**.
- **Nivel educacional de padres**: mayor educación → mayor **average** (tope: *master’s degree* ≈ **73.6**).
- **Correlaciones** altas entre puntajes; **reading–writing** ≈ **0.95**.
- **Género**: mujeres > en reading/writing; hombres > en math (alineado con PISA).
- **Asistencia al curso**: ≈ **35.8%** de estudiantes.
- **Lunch**: estándar > free/reduced en **average** (hallazgo descriptivo; no causal).

## Ver el informe (DataCamp)
📓 https://www.datacamp.com/datalab/w/1565bce4-0449-4718-86c9-b60591e2798f

