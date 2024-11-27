# Proyecto GIS - Análisis de la Educación en Oaxaca

Este proyecto utiliza datos espaciales de los municipios de Oaxaca para analizar cómo influye la educación en los municipios vecinos. **¿La educación se contagia?** Este análisis busca responder a esta pregunta mediante herramientas de análisis espacial y visualización de datos.

---

## 📂 Estructura del Proyecto

La estructura de carpetas es la siguiente:

proyecto-GIS
  - datos     # Archivos base (shapefiles y otros datos crudos)
  - mapas       # Gráficos generados en GeoDa y R
  - output      # Resultados finales (PDF del informe, tablas procesadas)
  - scripts     # Archivo principal de R Markdown

---

## 🛠️ Herramientas Utilizadas

- **R**: Para análisis estadístico, visualización y generación del reporte final.
- **R Markdown**: Para documentar el análisis y generar un informe reproducible en formato PDF.
- **GeoDa**: Para crear mapas espaciales y realizar análisis como Índices de Moran y LISA.
- **Git** y **GitHub**: Para el control de versiones y la colaboración.

- Se utilizó una base de datos precargada de GeoDA [Oaxaca Development](https://geodacenter.github.io/data-and-lab/Oaxaca-Development/)
---

## 🚀 Cómo Usar este Proyecto

### Requisitos

1. Instalar las siguientes herramientas:
   - [R](https://www.r-project.org/)
   - [RStudio](https://posit.co/download/rstudio/)
   - [GeoDa](https://geodacenter.github.io/download.html)
   - [Git](https://git-scm.com/)

2. Clonar este repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/proyecto-GIS-Oaxaca.git
