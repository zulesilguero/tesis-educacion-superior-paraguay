# 🎓 Modelado Territorial de la Oferta de Educación Superior en Paraguay mediante Ciencia de Datos

## Trabajo Final de Maestría
**Universidad Comunera**
**Maestría en Ciencia de Datos**

### Autoras
- Mónica Leticia Fleitas Guillén
- Zulema María Silguero Estigarribia

### Tutora
D.Sc. Margarita Ruiz

---

## Descripción

Este repositorio contiene el código fuente, los datos de apoyo cuya redistribución está permitida, y la documentación metodológica utilizados para desarrollar la investigación:

> **"Modelado Territorial de la Oferta de Educación Superior en Paraguay mediante Ciencia de Datos"**

El estudio propone una metodología reproducible y descriptiva para evaluar la distribución territorial de la oferta académica presencial, medir su cobertura relativa frente a la población joven, analizar su pertinencia respecto de los ejes productivos departamentales, y examinar la evolución de las brechas de oferta a partir de las proyecciones demográficas oficiales del INE.

---

## Objetivos

- Analizar la distribución territorial de la oferta de educación superior.
- Calcular el Índice de Cobertura Relativa (IC) por departamento.
- Evaluar la pertinencia territorial de la oferta frente a los ejes productivos.
- Analizar la evolución de la demanda potencial (población de 15 a 29 años) mediante las proyecciones oficiales del INE, 2022–2032.
- Identificar departamentos prioritarios mediante el Índice de Prioridad Territorial Educativa (IPTE).

---

## Metodología

El pipeline fue desarrollado en Python utilizando:

- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- SciPy (clustering jerárquico)
- GeoPandas / Folium
- libpysal / esda (Índice de Moran)
- OpenPyXL

Las principales técnicas implementadas incluyen:

- Clustering K-Means y clustering jerárquico aglomerativo (HAC-Ward)
- Selección del número de conglomerados mediante método del codo y coeficiente de silueta
- Índice Global de Moran (autocorrelación espacial)
- Normalización Min-Max
- Índice de Cobertura Relativa (IC)
- Índice de Herfindahl-Hirschman (diversidad disciplinar)
- Score de Pertinencia Territorial
- Índice de Prioridad Territorial Educativa (IPTE)

El estudio es exploratorio-evaluativo, descriptivo y prospectivo. **No se ajusta ningún modelo de regresión ni se elaboran proyecciones demográficas propias**; el análisis prospectivo utiliza exclusivamente las Estimaciones y Proyecciones Departamentales oficiales del INE (Revisión 2025).

---

## Estructura del repositorio
data/
notebooks/


---

## Resultados obtenidos

El pipeline genera:

- Distribución territorial de la oferta académica por modalidad y área disciplinaria.
- Índice de Cobertura Relativa por departamento y clasificación por cuartiles.
- Score de pertinencia territorial por departamento.
- Segmentación territorial mediante clustering (K-means y HAC-Ward).
- Análisis de brechas de oferta bajo escenario de oferta constante, 2022–2032.
- Ranking del Índice de Prioridad Territorial Educativa (IPTE).
- Mapas interactivos y figuras estáticas.

📁 **Resultados completos (CSV, figuras y mapas):** [https://drive.google.com/file/d/13jJth3MJV9lzAKQQujsL24svC8TqGSbs/view?usp=drive_link]

---

## Reproducibilidad

La investigación fue desarrollada siguiendo principios de ciencia reproducible. Las bases oficiales utilizadas provienen de:

- Consejo Nacional de Educación Superior (CONES) — Registro Nacional de Carreras
- Instituto Nacional de Estadística (INE) — Censo Nacional de Población y Viviendas 2022 y Estimaciones y Proyecciones Departamentales, Revisión 2025
- Instituto Geográfico Nacional (IGN) — cartografía departamental

Debido a restricciones de tamaño y a la actualización permanente de las fuentes oficiales, algunas bases de datos originales no se incluyen en este repositorio. El pipeline puede ejecutarse nuevamente utilizando las versiones oficiales disponibles en:

- Registro Nacional de Carreras (CONES/MEC): https://datos.mec.gov.py/data/rnc
- Portal de Datos Abiertos del INE (Censo 2022 y proyecciones departamentales): https://www.ine.gov.py/

---

## Licencia

MIT License

---

## Año

2026
