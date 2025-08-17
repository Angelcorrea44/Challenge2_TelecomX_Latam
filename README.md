# 📊 Análisis de Evasión de Clientes (Churn) en TelecomX

Este proyecto utiliza Python y pandas para analizar los factores que influyen en la evasión de clientes (churn) en una empresa de telecomunicaciones. El análisis se realiza en un Jupyter Notebook y abarca desde la carga y limpieza de datos hasta la visualización y generación de insights accionables.

---

## 🚀 Contenido del Notebook

### 1. **Extracción de Datos**
- **Carga de datos:** Se importa un archivo JSON público con información de clientes de TelecomX.
- **Librerías:** Uso de `pandas` para manipulación de datos y `matplotlib`/`seaborn` para visualización.

### 2. **Transformación y Limpieza**
- **Normalización:** Se aplana la estructura anidada del JSON usando `pd.json_normalize`.
- **Verificación:** Se identifican valores ausentes, duplicados y errores de formato.
- **Estandarización:** 
  - Se eliminan duplicados.
  - Se estandarizan strings (minúsculas, sin espacios).
  - Se convierten variables binarias a 0/1.
  - Se convierten columnas numéricas a tipo adecuado.
  - Se reemplazan valores nulos por "no informado" o 0 según el caso.
- **Creación de variables:** Se agrega la columna `cuentas_diarias` (gasto diario promedio).

### 3. **Análisis Descriptivo**
- **Estadísticas generales:** Uso de `describe()`, media, mediana y desviación estándar para variables numéricas.
- **Distribución de variables categóricas:** Conteo de valores únicos y proporciones.

### 4. **Visualización de Evasión**
- **Gráficos de barras y pastel:** Para visualizar la proporción de clientes que permanecen y los que se dieron de baja.
- **Análisis por variables categóricas:** Gráficos segmentados por género, tipo de contrato, método de pago, etc.
- **Análisis por variables numéricas:** Boxplots para comparar cargos, antigüedad y gasto diario entre clientes que cancelaron y los que no.

### 5. **Conclusiones e Insights**
- Resumen de hallazgos clave sobre los factores asociados a la evasión.
- Identificación de perfiles de clientes con mayor riesgo de churn.

### 6. **Recomendaciones**
- Sugerencias estratégicas para reducir la evasión, como programas de fidelización, incentivos y educación al cliente.

---

## 🛠️ Requerimientos

### Paquetes de Python

- `pandas`
- `matplotlib`
- `seaborn`
- `jupyter` (opcional, pero recomendado para ejecutar el notebook)

Instala los requerimientos con:

```bash
pip install pandas matplotlib seaborn jupyter
```

### Archivos necesarios

- El notebook principal: `TelecomX_LATAM.ipynb`
- Acceso a internet para descargar el dataset JSON desde GitHub.

---

## 📋 Ejecución paso a paso

1. **Abre el notebook en Jupyter o Visual Studio Code.**
2. **Ejecuta las celdas en orden:**
   - Carga y visualización inicial de los datos.
   - Limpieza y transformación.
   - Creación de nuevas variables.
   - Análisis descriptivo y visualizaciones.
   - Consulta de conclusiones y recomendaciones al final del notebook.
3. **Personaliza el análisis:** Puedes modificar las variables analizadas o agregar nuevas visualizaciones según tus necesidades.

---

## 📈 Resultados esperados

- **Visualizaciones claras** sobre la distribución de churn y su relación con variables clave.
- **Insights accionables** para reducir la evasión de clientes.
- **Código limpio y comentado** para facilitar la reutilización y adaptación a otros datasets similares.

---

## 📞 Contacto

Para dudas o sugerencias, puedes abrir un issue o contactar al autor del repositorio.

---

> ¡Este proyecto es una base sólida para cualquier análisis de churn en empresas de servicios!
