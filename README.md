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
