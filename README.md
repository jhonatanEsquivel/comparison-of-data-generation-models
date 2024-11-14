# Comparación de Resultados de Modelos de Generación de Datos Sintéticos

Este repositorio contiene una notebook que analiza y compara los resultados obtenidos al aplicar diferentes técnicas de generación de datos sintéticos para resolver problemas de desbalanceo de clases. Las técnicas evaluadas incluyen:

- **SMOTE-NC**
- **CTGAN**
- **VAE**
- Un modelo base sin técnicas de balanceo (**Sin Balanceo**)

## Contenido del Repositorio

- `comparacion_resultados_modelos.ipynb`: Notebook principal donde se realiza el análisis y la comparación de los modelos.
- `resultados_clasificadores_smote_nc.csv`: Resultados de las métricas de clasificación utilizando SMOTE-NC.
- `resultados_clasificadores_ctgan.csv`: Resultados de las métricas de clasificación utilizando CTGAN.
- `resultados_clasificadores_vae.csv`: Resultados de las métricas de clasificación utilizando VAE.
- `resultados_clasificadores_sin_balanceo.csv`: Resultados de las métricas de clasificación sin aplicar técnicas de balanceo.

## Objetivo

El objetivo de este proyecto es evaluar la efectividad de diferentes técnicas de generación de datos sintéticos para mejorar el rendimiento de clasificadores en datasets desbalanceados. Se calculan métricas como F1-Score, Precisión, Recall, AUC-ROC, Specificity y MCC para identificar cuál técnica es la más adecuada.

## Cómo Usar Este Repositorio

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
