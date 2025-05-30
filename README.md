# 📊 Análisis de Evasión de Clientes - Telecom X

## 🎯 Descripción del Proyecto

Este proyecto analiza los patrones de evasión de clientes (churn) en la empresa de telecomunicaciones Telecom X, con el objetivo de identificar los factores que contribuyen a la cancelación de servicios y proponer estrategias efectivas para mejorar la retención de clientes.

## 🎪 Objetivos

- **Identificar** los principales factores que influyen en la evasión de clientes
- **Analizar** patrones de comportamiento en diferentes segmentos de clientes
- **Proporcionar** insights basados en datos para estrategias de retención
- **Desarrollar** recomendaciones actionables para reducir la tasa de churn

## 📋 Descripción de los Datos

### Dataset
- **Fuente**: Datos históricos de clientes de Telecom X
- **Tamaño**: 7,043 registros de clientes únicos
- **Período**: Datos históricos de comportamiento de clientes

### Variables Principales
- **Datos demográficos**: Género, edad, dependientes
- **Información contractual**: Tipo de contrato, antigüedad
- **Servicios**: Internet, teléfono, servicios adicionales
- **Facturación**: Cargos mensuales, método de pago
- **Target**: Churn (Yes/No)

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Operaciones numéricas
- **Matplotlib** - Visualización de datos
- **Seaborn** - Visualizaciones estadísticas
- **Jupyter Notebook / Google Colab** - Entorno de desarrollo


## 🚀 Cómo Ejecutar el Proyecto

### Opción 1: Google Colab (Recomendado)
1. Abre el notebook en Google Colab
2. Ejecuta todas las celdas secuencialmente
3. Los datos se cargan automáticamente desde la URL proporcionada

### Opción 2: Entorno Local
1. **Clona este repositorio**:


## 📊 Principales Resultados

### Resumen Ejecutivo
- **Tasa de churn general**: 26.5% (1,869 de 7,043 clientes)
- **Factor de mayor riesgo**: Contratos month-to-month (42.7% churn)
- **Método de pago crítico**: Electronic check (45.3% churn)
- **Período vulnerable**: Primeros 12 meses (47.4% churn)

### Hallazgos Clave

| Factor | Categoría | Churn Rate |
|--------|-----------|------------|
| **Tipo de Contrato** | Month-to-month | 42.7% |
|  | One year | 11.3% |
|  | Two year | 2.8% |
| **Método de Pago** | Electronic check | 45.3% |
|  | Mailed check | 19.1% |
|  | Bank transfer (automatic) | 16.7% |
|  | Credit card (automatic) | 15.2% |
| **Antigüedad** | ≤12 meses | 47.4% |
|  | >12 meses | 17.1% |
| **Cargos Mensuales** | Cargos altos (>$70) | 35.2% |
|  | Cargos bajos (≤$70) | 17.9% |

### Métricas de Negocio
- **ARPU** (Average Revenue Per User): $64.76
- **Tenure promedio**: 32.4 meses
- **CLV promedio**: $2,283.30

## 💡 Recomendaciones Principales

1. **Incentivos contractuales**: Promover contratos anuales/bianuales con descuentos
2. **Optimización de pagos**: Migrar clientes a métodos de pago automáticos
3. **Programa de onboarding**: Retención especial para nuevos clientes
4. **Bundling de servicios**: Ofertas de servicios adicionales competitivas
5. **Monitoreo proactivo**: Sistema de alertas para clientes de alto riesgo

## 📈 Visualizaciones

El proyecto incluye múltiples visualizaciones que muestran:
- Distribución general de churn
- Análisis por tipo de contrato
- Comportamiento por método de pago
- Evolución según antigüedad del cliente
- Correlaciones entre variables

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para contribuir:

1. **Fork el proyecto**
2. **Crea una rama** para tu feature (`git checkout -b feature/AmazingFeature`)
3. **Commit tus cambios** (`git commit -m 'Add some AmazingFeature'`)
4. **Push a la rama** (`git push origin feature/AmazingFeature`)
5. **Abre un Pull Request**

## 📧 Contacto

- **Autor**: Juan Carlos Vanegas Molina

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

## 🏆 Impacto del Proyecto

Este análisis proporciona una base sólida para:
- **Reducir la tasa de churn** del 26.5% actual
- **Mejorar la retención** especialmente en clientes nuevos
- **Optimizar estrategias** de adquisición y retención
- **Incrementar el CLV** mediante mejores prácticas de fidelización

---


