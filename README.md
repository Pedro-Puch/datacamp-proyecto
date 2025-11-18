# datacamp-proyecto
# Analyzing the Effectiveness of a Test Preparation Course

Notebook de competencia (DataCamp): impacto de un curso de preparación en puntajes de **math, reading, writing** y relación con **nivel educacional de los padres**.

## Dataset
- 1.000 estudiantes, 8 columnas (3 numéricas: math, reading, writing; 5 categóricas).
- Sin valores faltantes; puntajes 1–100.
- Archivo de ejemplo: `data/exams.csv` (o enlace al dataset si no lo incluyes).

## Metodología (resumen)
- EDA y validación básica (descriptivos, distribuciones, outliers).
- Comparaciones de medias por **test_prep_course** y **parent_education_level**.
- Variable auxiliar **average** = (math+reading+writing)/3.
- Correlaciones y visualizaciones (pairplot / heatmap).

## Hallazgos clave
- **Curso preparación mejora reading**: con curso ≈ **73.9**, sin curso ≈ **66.5**.
- **Nivel educacional padres**: mayor educación → mayor **average** (máximo: *master’s degree* ≈ **73.6**).
- **Correlaciones** altas entre puntajes; **reading–writing** ≈ **0.95**.
- **Género**: mujeres > en reading/writing; hombres > en math (alineado con PISA).
- **Asistencia a curso**: ≈ **35.8%** de estudiantes.
- **Lunch**: estándar > free/reduced en **average** (hallazgo descriptivo; no causal).

## Reproducir
```bash
pip install -r requirements.txt
python -c "import webbrowser as w; w.open('proyecto.ipynb')"
# o abrir el .ipynb en Jupyter/VSCode
