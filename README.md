
# Análisis Exploratorio de Datos: Palmer Penguins 🐧

Este repositorio contiene un Análisis Exploratorio de Datos (EDA) y un estudio estadístico detallado sobre el conjunto de datos de los **Pingüinos de Palmer** (`species`, `longitud_pico_mm`, `grosor_pico_mm`, `longitud_aleta_mm`, `masa_corporal_g`).

---

## 📌 Principales Hallazgos

* **Identificación de Gentoo:** Destaca por presentar la menor profundidad de pico, combinada con la mayor longitud de aleta y masa corporal.
* **Diagnóstico de Adelie:** Se distingue por registrar la menor longitud de pico de todo el estudio.
* **Solapamiento entre Adelie y Chinstrap:** Comparten rangos muy similares en peso y tamaño de aleta, generando superposición visual en los datos.
* **Crecimiento intraespecie:** Dentro de cada grupo, las características físicas aumentan de forma proporcional con el tamaño corporal.
* **Paradoja de Simpson:** El análisis global genera tendencias negativas engañosas. Al segmentar por especie, todas las correlaciones se vuelven estrictamente positivas.

---

## 🛠️ Metodología Aplicada

1. **Pruebas de Normalidad (Shapiro-Wilk):** Demuestran que la falta de normalidad a nivel global se debe a la bimodalidad por mezcla de especies, mientras que la normalidad emerge al analizar subgrupos.
2. **Correlación de Spearman:** Utilizada para evaluar relaciones entre variables sin asumir distribuciones normales agregadas.
3. **Visualización de Datos:** Gráficos de densidad (KDE), matrices de correlación y análisis de regresión segmentados con Seaborn y Python.

---

## ✒️ Autor
Desarrollado por **Michael Ccasani**.
