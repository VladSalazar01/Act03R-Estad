# 🧬 Análisis Exploratorio de Expresión Génica en Pacientes con Tratamientos Oncológicos

> Proyecto académico desarrollado en el marco de la Actividad Grupal 3 del **Máster Universitario en Bioinformática (UNIR, 2025)**.  
> Enfocado al análisis multivariado y Análisis de Componentes Principales de la expresión génica en pacientes con diferentes terapias oncológicas utilizando R.

---

## 📂 Estructura del repositorio

```text
├── Actividad Grupal 3.Rmd           # Script en RMarkdown con todo el análisis
├── Actividad-Grupal-3.html          # Informe HTML con visualizaciones interactivas
├── Dataset expresión genes.csv      # Dataset con la expresión de 46 genes en 65 pacientes
├── .gitignore                       # Exclusiones para Git (incluye archivos .html, .pdf, etc.)
├── figure-htlm/                     #Carpeta con figuras generadas por el análisis. 
```
## 🎯  Objetivo
Este proyecto tiene como finalidad realizar un análisis descriptivo, gráfico y exploratorio de un set de expresión génica en pacientes oncológicos, identificando agrupaciones, patrones de correlación y reducción de dimensionalidad mediante técnicas multivariadas como el Análisis de Componentes Principales (PCA) y analisis multivariado.

---
## 👨‍🔬 Público objetivo
Dirigido a:

- Bioinformáticos en formación  
- Investigadores en genómica y transcriptómica  
- Estudiantes de posgrado en ciencias biomédicas

## ⚙️ Tecnologías y dependencias
Este proyecto está implementado en **R**, y requiere las siguientes librerías:

```r
install.packages(c(
  "tidyverse", "ggplot2", "readr", "factoextra", 
  "psych", "reshape2", "knitr", "rmarkdown"
))
```
Recomendado ejecutar en RStudio (v1.4 en adelante) con R (v4.0 en adelante).

## 🚀 Ejecución del análisis
Clona el repositorio desde GitHub:
```bash
git clone https://github.com/VladSalazar01/Act03R-Estad.git
cd Act03R-Estad
```
1. Abre el archivo Actividad Grupal 3
2. Ejecuta todo el script o haz clic en "Knit to HTML" para generar el informe.
3. Visualiza los resultados en el archivo Actividad-Grupal-3.html.
## 📊 Funcionalidades principales
-Limpieza y transformación del dataset de expresión genética
-Estadística descriptiva con exploración por tipo de tratamiento
-Generación de histogramas, boxplots (diagramas de caja y bigote) y heatmap (diagramas de calor)
-Análisis de componentes Principales
-Generación automática de informes reproducibles. 
## 🔍 Base de Datos
Dataset expresión genes: Contiene observaciones tanto de variables clínicas como de expresión de genes de 65 pacientes en formato csv.
## 👥 Autores

Este trabajo fue desarrollado por:

- **Yuli Del Cisne Girón Castillo**  
- **Kelly Ailen Loja Chalén**  
- **Carolina Jacqueline Panchana Torres**  
- **Vladimir Oswaldo Salazar Córdova**  
- **Cristhian Santiago Vasco Toapanta**
## Licencia
Este repositorio se distribuye únicamente con fines académicos y prácticos. Para cualquier uso o redistribución, contactar con los autores principales. 
## Referencias
R Core Team. R: A language and environment for statistical computing. Vienna, Austria: R Foundation for Statistical Computing; 2024.
Wickham H, Grolemund G. R for Data Science. O'Reilly Media; 2017.
