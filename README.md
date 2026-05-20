# ciencia-de-dato-s8

REPOSITORIO PERSONAL DEL TIPO ESTUDIANTIL
# Proyecto Analítico – AquaLimpia S. A.

## Análisis del desempeño de plantas de tratamiento de aguas residuales (IACC CDD S8)

# 1. Introducción

AquaLimpia S. A. opera diversas plantas de tratamiento de aguas residuales urbanas e industriales. Durante el último trimestre se detectaron incumplimientos intermitentes en parámetros críticos de calidad del efluente tratado, especialmente en los niveles de Demanda Biológica de Oxígeno (DBO).

Debido a la variabilidad operacional entre plantas y la ausencia de patrones evidentes, se desarrolló un proyecto de análisis de datos orientado a identificar tendencias, evaluar el desempeño operacional y apoyar la toma de decisiones de las áreas de Operaciones, Gestión Ambiental y Gerencia.

---

# 2. Objetivos del proyecto

## Objetivo general

Desarrollar un análisis exploratorio y un dashboard interactivo que permitan evaluar el desempeño de las plantas de tratamiento y detectar posibles factores asociados a incumplimientos normativos.

## Objetivos específicos

- Analizar el comportamiento operacional de las plantas.
- Identificar tendencias en DBO de entrada y salida.
- Evaluar la eficiencia de remoción de contaminantes.
- Detectar plantas con mayor cantidad de incumplimientos.
- Construir visualizaciones exploratorias.
- Generar reportes específicos para distintas áreas de la empresa.

---

# 3. Dataset utilizado

El dataset contiene información operacional y ambiental de las plantas de tratamiento, incluyendo variables como:

- Fecha de registro.
- Planta de tratamiento.
- Caudal de entrada.
- DBO de entrada y salida.
- Consumo energético en aireación.
- Cantidad de lodos generados.
- Estado de cumplimiento normativo.

---

# 4. Proceso analítico

## 4.1 Carga y exploración de datos

Se importó el dataset utilizando Python y Pandas para realizar una exploración inicial de la estructura de los datos.
llamado ("dataset_set_A_aguas_residuales.xlsx")
