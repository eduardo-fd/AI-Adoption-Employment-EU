# Impacto de la Adopción de la Inteligencia Artificial en la Estructura del Empleo Europeo (2023-2024)

**Trabajo de Fin de Grado – Grado en Economía, Universitat Autònoma de Barcelona**  
**Autor:** Eduardo Fernández Dionicio  
**Fecha de defensa:** 27 de mayo de 2025  
**Calificación:** 9 (Matrícula de Honor)

---

## Bienvenida

Este repositorio contiene el código y la documentación que permiten reproducir los resultados del Trabajo de Fin de Grado titulado “Impacto de la Adopción de la Inteligencia Artificial en la Estructura del Empleo Europeo (2023-2024)”. El objetivo es facilitar la transparencia, fomentar la replicabilidad y compartir los principales hallazgos con la comunidad académica y profesional.

---

## Motivación y objetivo

El avance de la inteligencia artificial (IA) genera incertidumbre y debate sobre su influencia en el empleo. El objetivo de este trabajo es analizar empíricamente cómo la adopción de IA por parte de las empresas afecta la estructura del empleo en Europa, diferenciando tanto por sectores económicos como por ocupaciones. Se plantea la hipótesis de que el impacto es heterogéneo según las características de cada sector y ocupación.

---

## Datos utilizados

- **Fuente principal:** Encuesta de Eurostat sobre el uso de tecnologías digitales en empresas (Digital Economy and Society).
- **Cobertura:** 29 países europeos, años 2023 y 2024.
- **Variables clave:**  
  - Proporción de empresas que utilizan IA por sector y país.
  - Distribución del empleo por sectores (NACE Rev.2) y por ocupaciones (ISCO-08).
  - Indicadores de PIB per cápita, nivel educativo y tasa de paro (controles macroeconómicos).
- *Nota*: La base de datos principal (data) no se incluye en el repositorio por su tamaño, pero se explica cómo obtenerla.

---

## Metodología utilizada

- **Modelos de datos de panel** con efectos fijos por país y año para captar la variabilidad temporal y geográfica.
- Estimaciones separadas para el análisis sectorial y ocupacional.
- Inclusión de variables de control macroeconómico para aislar el efecto de la adopción de IA.
- Cálculo de errores estándar robustos y clusterizados.
- Limitaciones reconocidas: horizonte temporal acotado, indicadores agregados de IA y restricciones de causalidad.

---

## Tecnologías utilizadas

- **Python** (análisis y procesamiento de datos)
- **Pandas** (manipulación de datos)
- **Statsmodels** y **linearmodels** (modelos econométricos de panel)
- **Matplotlib** y **Seaborn** (visualización de datos)
- **Eurostat** (fuente de datos)

---

## Principales resultados

- La adopción de IA se asocia a un aumento relativo del empleo en sectores y ocupaciones de alta cualificación, y a una disminución en sectores y ocupaciones rutinarias o de menor cualificación.
- No se observa un efecto neto de destrucción masiva de empleo, sino un reajuste estructural hacia puestos más cualificados.
- El detalle de los resultados, gráficos y análisis completos se encuentra en la memoria del TFG y el póster adjunto.

---

## Cómo reproducir el análisis

1. **Requisitos:**  
   - Python 3.x  
   - Instalar dependencias desde `requirements.txt`
2. **Datos:**  
   - Descargar el dataset de Eurostat (2023-2024) y colocarlo en la carpeta `/data`
3. **Ejecución:**  
   - Ejecutar el script principal en `/src/data_tfg.py`
4. **Resultados:**  
   - Los archivos de salida (tablas y gráficos) se guardan en la carpeta `/outputs`

---

## Documentación y contacto

- **Memoria completa del TFG:** `/docs/TFG-Eduardo Fernández Dionicio.pdf`
- **Póster:** `/docs/poster_TFG.pdf`
- **Autor:** Eduardo Fernández Dionicio  
- **LinkedIn** [www.linkedin.com/in/eduardo-fernandez-d]

---

## Licencia

Este repositorio está publicado bajo Licencia MIT.

---

## Cómo citar este trabajo

> Fernández Dionicio, E. (2025). *Impacto de la adopción de la inteligencia artificial en la estructura del empleo europeo (2023-2024): Un análisis empírico por sectores y ocupaciones*. Trabajo de Fin de Grado, Universitat Autònoma de Barcelona.

