# Informe de Análisis de Evasión de Clientes (Churn)

## 1. Introducción
El objetivo de este análisis es comprender las causas detrás de la **evasión de clientes** (Churn) en la empresa.  
El churn se refiere a los clientes que dejan de utilizar el servicio dentro de un periodo determinado.  
Reducir este indicador es clave para la sostenibilidad y el crecimiento, ya que retener clientes es más rentable que adquirir nuevos.

En este proyecto:
- Se exploran datos históricos de clientes.
- Se identifican patrones asociados a la cancelación del servicio.
- Se generan conclusiones y recomendaciones estratégicas.

---

## 2. Limpieza y Tratamiento de Datos
**Pasos realizados:**
1. **Importación de datos:**  
   - Lectura del archivo CSV/Excel con `pandas`.
2. **Inspección inicial:**  
   - Uso de `.head()`, `.info()`, `.describe()` para conocer la estructura.
3. **Manejo de valores faltantes:**  
   - Reemplazo de valores vacíos por `NaN`.
   - Imputación de datos o eliminación de registros según el caso.
4. **Conversión de tipos de datos:**  
   - Transformación de variables categóricas en numéricas (ej. `Yes` → 1, `No` → 0).
5. **Corrección de inconsistencias:**  
   - Estandarización de nombres de columnas.
   - Unificación de categorías similares.
6. **Creación de variables auxiliares:**  
   - Ejemplo: Etiquetas para gráficos (`Sí`/`No`).

---

## 3. Análisis Exploratorio de Datos (EDA)
Se realizaron análisis para entender la relación entre las variables y el churn.

**Visualizaciones sugeridas (inserta tus gráficos generados):**
- Distribución de facturación mensual según cancelación.
- Churn por tipo de contrato.
- Relación entre soporte técnico y cancelación.
- Impacto de servicios adicionales (streaming, líneas múltiples, etc.).

---

## 4. Conclusiones e Insights
**Principales hallazgos:**
- Clientes con contratos mensuales presentan una tasa de cancelación de más del 88%.
-Los clientes con menor antigüedad muestran mayor propensión a cancelar.
- La ausencia y/o baja calidad de soporte técnico incrementa significativament la probabilidad de cancelación, más del 77% de los clientes que cancelaron no tienen soporte técnico.
-El método de pago por débito bancario automático influye en la cancelación, más del 45% de las cancelaciones se ven relacionadas a este medio de pago.
-Aunque los adultos mayores representan el 25% de las cancelaciones totales ,dentro de esta población existe un riesgo de cancelacion alto de casi el 50% .
- La facturación mensual no evidencia impacto negativo en la cancelacion del servicio, por el contrario , el plan mas economico concentra la mayor cantidad de clientes  y presenta menor proporción de cancelaciones, lo que sugiere que el costo mensual podria actuar como factor de retención.

---

## 5. Recomendaciones Estratégicas

- Incentivar migración de contratos mensuales a contratos de mayor duración con descuentos y beneficios.  
- Implementar programa de bienvenida y seguimiento para clientes nuevos durante los primeros 3 meses.  
- Mejorar calidad y cobertura del soporte técnico, promoviendo su contratación con ofertas.  
- Revisar procesos del débito automático, si se hace nesario seguir incentivando o no este medio de pago.
- Ofrecer atención preferencial y beneficios especiales para adultos mayores.  
- Mantener y promocionar planes económicos como estrategia de retención.  

---
##  Tecnologías
- Python
- Pandas
- Matplotlib / Seaborn
- Google Colab

---
✍️ *Autor:* Yulitza Gámez
