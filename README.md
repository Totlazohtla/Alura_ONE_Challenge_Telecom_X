
# 📊 Telecom X - Análisis de Evasión de Clientes (Churn Prediction)

> Proyecto de Ciencia de Datos orientado al análisis exploratorio y limpieza avanzada de datos para la empresa ficticia **Telecom X**, centrado en detectar patrones de cancelación de clientes. Inspirado en estándares corporativos similares a Oracle Inc. para consultoría y presentación de resultados.

---

## 🎯 Objetivo del Proyecto

Telecom X experimenta una tasa creciente de pérdida de clientes y requiere un análisis detallado para comprender las causas principales de la evasión (churn).  
Este proyecto busca identificar patrones, correlaciones y variables clave que influyen en la cancelación, con el fin de proponer estrategias efectivas para mejorar la retención de clientes.

---

## 📂 Estructura del Proyecto

```
📁 telecomx-churn-analysis/
│
├── data/
│   └── backup                                     # Datos originales y transformados
│       └── bkp_df_normalize_120625_2154.csv       # Repaldo 1
│       └── telecomx_datos.csv.csv                 # DataFrame ocupado para realizar los ejercicios
├── notebooks/                                     # Análisis en formato Jupyter Notebook (.ipynb)
│   └── telecomx.ipynb                             # Notebook principal con análisis y visualizaciones
├── src/                                           # Código modular y funciones auxiliares
├── images/                                        # Visualizaciones exportadas
├── README.md                                      # Este archivo
└── requirements.txt                               # Dependencias del entorno
```

---

## 🔍 Alcance del Análisis

- ✅ Carga, inspección y comprensión de los datos
- ✅ Limpieza de valores nulos e inconsistencias
- ✅ Estudio estadístico y detección de outliers
- ✅ Visualización avanzada (Seaborn, Matplotlib)
- ✅ Análisis de correlación multivariable
- ✅ Detección de factores de riesgo de cancelación
- ✅ Recomendaciones estratégicas para mitigar el churn

---

## 🧼 Tratamiento de Datos

Se aplicaron los siguientes pasos:

- Eliminación y detección de registros nulos
- Conversión de tipos de datos inconsistentes
- Normalización de columnas y nombres
- Creación de subconjuntos con datos limpios y balanceados

---

## 📊 Principales Visualizaciones

- Gráficos de distribución por tipo de contrato, método de pago y cargos mensuales
- Histogramas y KDEs comparativos entre clientes leales vs cancelados
- Matriz de correlación con mapa de calor (heatmap) para entender relaciones numéricas
- Gráficos de barras con etiquetas numéricas y colores personalizados

---

## 📈 Principales Hallazgos

- Los contratos mensuales concentran el mayor volumen de cancelaciones.
- Métodos de pago automáticos se correlacionan con mayor deserción.
- Cargos mensuales altos (> $90) incrementan el riesgo de churn.
- Facturación electrónica podría estar generando fricción en la experiencia del cliente.
- Vínculos familiares (pareja/hijos) reducen la probabilidad de cancelación.

---

## 🧠 Recomendaciones Estratégicas

1. Incentivar contratos a largo plazo mediante beneficios escalonados.
2. Rediseñar la interfaz de facturación electrónica para mejorar la experiencia del usuario.
3. Replantear la política de precios y cargos adicionales.
4. Personalizar campañas de retención para clientes con perfiles de riesgo detectado.

---

## 🛠️ Tecnologías Utilizadas

| Herramienta / Paquete     | Propósito                           |
|---------------------------|--------------------------------------|
| `Python 3.12+`            | Lenguaje base                        |
| `Pandas / NumPy`          | Análisis y transformación de datos  |
| `Matplotlib / Seaborn`    | Visualización de datos               |
| `Jupyter Notebook`        | Documentación interactiva            |

---

## 📌 Cómo ejecutar el proyecto

1. Clona el repositorio:  
   ```bash
   git clone https://github.com/T1nu5/Challenge-TelecomX.git
   ```

2. Instala las dependencias:  
   ```bash
   pip install -r requirements.txt
   ```

3. Abre el notebook:  
   ```bash
   jupyter notebook ../notebooks/telecomx.ipynb
   ```

---

## 👤 Autor

**José Luis González Hernández**  
📍 Especialista en Optimización de Procesos, Inteligencia de Negocios y Transformación Digital
🔗 [LinkedIn](https://www.linkedin.com/in/jose-luis-glz-hdz/)

---

## 📝 Licencia

Este proyecto está disponible bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.
