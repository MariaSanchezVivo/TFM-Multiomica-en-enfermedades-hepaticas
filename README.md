# TFM - Análisis multi-ómico en enfermedades hepáticas

Este repositorio contiene los scripts y análisis desarrollados para el Trabajo Fin de Máster (TFM), centrado en el estudio integrado de datos de microbiota intestinal y metabolómica en enfermedades hepáticas (hepatitis C crónica, hepatitis autoinmune y colangitis biliar primaria).

---

## Objetivo

El objetivo de este trabajo es caracterizar los patrones multiómicos diferenciales en pacientes con enfermedades hepáticas mediante la integración de datos clínicos, metabolómicos y metataxonómicos. El análisis se basa en un enfoque exploratorio no supervisado orientado a la identificación de posibles biomarcadores y mecanismos fisiopatológicos asociados al eje intestino–hígado.

---

## Contenido del repositorio

- **Scripts de análisis (.Rmd)**: contienen los principales flujos de trabajo en R junto con sus correspondientes salidas en HTML.
- **Carpeta `metaboanalyst_results/`**: resultados de análisis de enriquecimiento funcional basados en bases de datos KEGG y Gut Microbiota–Host interactions.
- **Carpeta `figures/`**: visualizaciones generadas durante el análisis que no están incluidas en el informe principal.

---

## Metodología resumida

- Análisis estadístico descriptivo e inferencial
- Análisis de microbiota intestinal (diversidad y composición taxonómica)
- Agrupación taxonómica a nivel de Phylum
- Análisis exploratorio no supervisado (PCA, UMAP, t-SNE)
- Análisis de correlación entre variables ómicas
- Integración multi-ómica mediante MOFA+ y DIABLO

---

## NOTA

Este repositorio contiene únicamente datos procesados, scripts de análisis y resultados gráficos. No incluye información clínica sensible ni datos identificables de pacientes.
