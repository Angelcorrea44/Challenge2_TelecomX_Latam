# 📄 Informe Final: Análisis de Evasión de Clientes (Churn) en TelecomX

---

## 🔹 Introducción

El objetivo de este análisis es comprender los factores que influyen en la evasión de clientes (Churn) en TelecomX. La evasión de clientes es un problema crítico para las empresas de telecomunicaciones, ya que impacta directamente en los ingresos y la sostenibilidad del negocio. Identificar patrones y variables asociadas al churn permite diseñar estrategias efectivas para la retención de clientes.

---

## 🔹 Limpieza y Tratamiento de Datos

- **Importación:** Se cargaron los datos desde un archivo JSON público.
- **Normalización:** Se aplanó la estructura anidada del dataset para facilitar el análisis.
- **Verificación:** Se identificaron y corrigieron valores ausentes, duplicados y errores de formato.
- **Estandarización:** Se homogenizaron los valores de las variables categóricas (minúsculas, sin espacios, valores binarios a 0/1).
- **Conversión:** Se aseguraron los tipos de datos correctos para variables numéricas y categóricas.
- **Nuevas variables:** Se creó la columna `cuentas_diarias` para analizar el gasto diario promedio de los clientes.

---

## 🔹 Análisis Exploratorio de Datos

- **Distribución de Churn:** Se visualizó la proporción de clientes que permanecen y los que se dieron de baja, tanto en gráfico de barras como de pastel.
- **Variables categóricas:** Se analizaron variables como género, tipo de contrato, método de pago e internet, observando su relación con la evasión mediante gráficos de barras segmentados.
- **Variables numéricas:** Se exploró la distribución de cargos mensuales, total gastado, tiempo de contrato y cuentas diarias, diferenciando entre clientes que cancelaron y los que no, usando boxplots.
- **Estadísticas descriptivas:** Se calcularon medidas como media, mediana y desviación estándar para comprender la dispersión y tendencia central de las variables clave.

---

## 🔹 Conclusiones e Insights

- **Churn:** Existe un porcentaje significativo de clientes que han abandonado la empresa.
- **Tipo de contrato:** Los contratos mensuales presentan mayor tasa de evasión comparados con contratos a plazo fijo.
- **Método de pago:** Los clientes que pagan con métodos electrónicos o facturación sin papel tienden a tener mayor churn.
- **Antigüedad:** Los clientes con menor tiempo de contrato (tenure) muestran mayor propensión a cancelar.
- **Gasto:** Los clientes con cargos mensuales más bajos y menor gasto total presentan mayor evasión.
- **Servicios adicionales:** La falta de servicios adicionales (seguridad, soporte, streaming) puede estar asociada a mayor churn.

---

## 🔹 Recomendaciones

- **Fidelización:** Implementar programas de retención enfocados en clientes con contratos mensuales y baja antigüedad.
- **Incentivos:** Ofrecer descuentos o beneficios a quienes utilicen métodos de pago asociados a mayor churn.
- **Servicios adicionales:** Promover la contratación de servicios complementarios para aumentar el valor percibido.
- **Seguimiento personalizado:** Identificar y contactar proactivamente a clientes con bajo gasto y menor tiempo de permanencia.
- **Educación:** Informar a los clientes sobre las ventajas de contratos a largo plazo y servicios adicionales.

---

> **Este análisis proporciona una base sólida para la toma de decisiones estratégicas orientadas a reducir la evasión y mejorar la satisfacción del cliente en TelecomX.**
