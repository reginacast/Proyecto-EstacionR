# 📊💜 Datos de la ENOE con perspectiva de género

Este proyecto analiza cómo el acceso al empleo y las trayectorias profesionales de las mujeres en México se ven afectados por diversos factores socioeconómicos, utilizando microdatos del 2do Trimestre de la Encuesta Nacional de Ocupación y Empleo (ENOE) de 2025.

## 🚀 Cómo ver el análisis
Para una experiencia visual e interactiva sin necesidad de descargar el código, puedes consultar el reporte final aquí:
👉 **[Ver reporte interactivo en RPubs](https://rpubs.com/reginacastaneda/1385642)**

---

## 📋 Descripción del Proyecto
El objetivo principal de esta investigación fue analizar, a través de evidencia estadística, los desafíos fundamentales que enfrentan las mujeres en el ámbito laboral mexicano. El estudio se centra en tres ejes críticos: la **brecha de acceso al empleo**, las **condiciones de precariedad** y el **impacto de la maternidad** en la trayectoria profesional.

Para profundizar en estos fenómenos, el análisis se estructura en torno a **cuatro preguntas de investigación estratégicas**. Cada una es abordada mediante un análisis exploratorio y descriptivo de datos (EDA), permitiendo transformar los microdatos brutos en respuestas concretas sobre la realidad laboral femenina.

Además, el proyecto incluye una sección dedicada a la metodología de la encuesta y su complejidad estadística. Se documenta paso a paso el proceso técnico realizado en **R**, desde la limpieza de la base de datos hasta la aplicación de factores de expansión y el diseño muestral, garantizando la validez de los resultados finales.

## 🛠️ Herramientas Utilizadas
* **Lenguaje:** R 
* **Librerías principales:** `tidyverse` (limpieza), `ggplot2` (visualización), `survey` (diseño muestral).
* **Fuente de datos:** INEGI - ENOE 2025 (Trimestre 2).

## 📂 Contenido del Repositorio
* [Proyecto.Rmd](Proyecto.Rmd): Código fuente principal (R Markdown).
* [Proyecto.html](Proyecto.html): Resultado final del análisis ejecutado.
* **Descriptor de base de datos/**: Documentación técnica de las variables.
* **Imágenes/**: Recursos visuales del reporte.

---
**Nota:** El archivo de datos original (`ENOE_SDEMT225.csv`) no se incluye en el repositorio por su peso (>100MB), pero puede descargarse en el sitio oficial del INEGI. **[ENOE INEGI](https://www.inegi.org.mx/programas/enoe/15ymas/#microdatos)**

