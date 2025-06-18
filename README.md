# 🎓 Análisis de Desempeño Estudiantil - OULAD

Este proyecto utiliza el dataset OULAD (Open University Learning Analytics Dataset) para analizar patrones de desempeño académico y construir modelos predictivos que identifiquen factores relacionados con la aprobación o abandono de los estudiantes.

---

## 🎯 Objetivos

- Explorar y visualizar los factores que afectan el rendimiento estudiantil.
- Aplicar técnicas de EDA y análisis estadístico.
- Desarrollar modelos predictivos (clasificación) para estimar el desempeño final.
- Integrar todo el flujo en un pipeline tipo ETL + análisis.

---

## 🔧 Herramientas utilizadas

- **Python**: análisis y modelado (pandas, scikit-learn, matplotlib, seaborn)
- **MySQL**: carga del dataset limpio estructurado por tablas.
- **Jupyter / Google Colab**: desarrollo del análisis y gráficos.
- **Git**: control de versiones del flujo de análisis.

---

## 📊 Análisis realizado

- Estadísticas descriptivas y frecuencia
- Pruebas estadísticas: ANOVA, t-test, chi-cuadrado
- Matriz de correlación
- Boxplots, histogramas, gráficas de dispersión
- Matriz de confusión de los modelos

---

## 🤖 Modelos aplicados

- Regresión logística
- SVM (Máquinas de Vectores de Soporte)
- Red Neuronal Artificial (MLPClassifier)
- Comparación de desempeño con precisión y recall

---

## 📁 Estructura del repositorio

```
📦oulad-analisis/
 ┣ 📂data/
 ┃ ┗ 📄datasetpractica.xlsx
 ┣ 📂scripts/
 ┃ ┣ 📄etl_mysql.py
 ┃ ┣ 📄eda_completo.py
 ┃ ┣ 📄modelo_svm_ann.py
 ┣ 📂visuals/
 ┃ ┗ 📄graficos_boxplot_corr.png
 ┣ 📄README.md
 ┗ 📄requirements.txt
```

---

## 🧠 Conclusiones destacadas

- Variables como satisfacción, complejidad percibida y nivel de ingresos están asociadas al desempeño.
- Los modelos SVM y ANN mostraron buen rendimiento predictivo.
- Se recomienda profundizar en estrategias de retención basadas en estos hallazgos.

---

## 📫 Contacto

- 📧 normcarrasco@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/nocarrasco)  
- 🌐 [Blog AprenTICs](https://apren2tics.wordpress.com)

---

> Proyecto educativo realizado como parte del desarrollo en Ciencia de Datos & AI. Dataset público de OULAD. Todos los datos son anónimos y para uso académico.
