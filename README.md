# 📊 Online Retail Sales & Customer Analytics

## 📌 Descripción del proyecto

Proyecto de **Data Analytics aplicado a un negocio de e-commerce**, desarrollado con **Microsoft Excel** a partir de una base de datos de más de **541.000 registros de transacciones**.

El objetivo fue transformar datos transaccionales en información útil para analizar el comportamiento de las ventas, productos, clientes y mercados, aplicando procesos de **limpieza, transformación, análisis exploratorio y visualización de resultados**.

El proyecto busca responder preguntas de negocio como:

* ¿Cómo evolucionan las ventas a través del tiempo?
* ¿Qué productos generan mayor volumen e ingresos?
* ¿Cuáles son los principales mercados?
* ¿Qué clientes presentan mayor actividad?
* ¿Existen problemas de calidad en los datos?
* ¿Qué oportunidades comerciales pueden identificarse a partir de los datos?

---

## 🎯 Objetivo

Analizar el comportamiento comercial de un negocio de retail online y convertir una base transaccional en **insights accionables para apoyar la toma de decisiones**.

El análisis se enfocó en cuatro dimensiones principales:

**Ventas · Productos · Clientes · Geografía**

---

## 🗂️ Dataset

La base contiene información transaccional con variables como:

| Campo         | Descripción                    |
| ------------- | ------------------------------ |
| `InvoiceNo`   | Número de factura              |
| `StockCode`   | Código del producto            |
| `Description` | Descripción del producto       |
| `Quantity`    | Cantidad registrada            |
| `InvoiceDate` | Fecha y hora de la transacción |
| `UnitPrice`   | Precio unitario                |
| `CustomerID`  | Identificador del cliente      |
| `Country`     | País del cliente               |

### Volumen inicial

**541.909 registros**

Después del proceso de validación y limpieza:

**539.388 registros**

---

## 🧹 Data Cleaning & Preparation

Una de las principales etapas del proyecto fue la evaluación de la calidad de los datos.

Se identificaron:

* Valores negativos en cantidades.
* Registros con cantidades iguales a cero.
* Registros sin descripción de producto.
* Transacciones sin `CustomerID`.
* Diferentes situaciones que requerían validar si un registro debía corregirse o eliminarse.

En lugar de eliminar automáticamente los registros problemáticos, se evaluó cada caso de acuerdo con su contexto.

También se creó una variable de **Cantidad Corregida** y una métrica de **Precio Total** para facilitar el análisis posterior.

### Fórmula utilizada

```text
Precio Total = Cantidad Corregida × Precio Unitario
```

---

## 🔎 Data Analysis

El análisis se desarrolló utilizando diferentes herramientas de Excel para transformar y explorar la información.

### Tablas dinámicas

Se utilizaron **Pivot Tables** para analizar:

* Ventas por mes.
* Ventas por país.
* Ventas por producto.
* Unidades vendidas.
* Número de transacciones.
* Actividad de clientes.
* Distribución de ingresos.

Las tablas dinámicas permitieron resumir grandes volúmenes de información y encontrar patrones de comportamiento comercial.

### BUSCARX (XLOOKUP)

Se utilizó **BUSCARX** para relacionar información entre tablas y recuperar datos asociados a diferentes registros.

Esto permitió enriquecer la información utilizada en el análisis y reducir procesos manuales de búsqueda.

### Fórmulas de Excel

Se utilizaron diferentes fórmulas para:

* Crear variables calculadas.
* Validar información.
* Realizar cálculos de ventas.
* Clasificar registros.
* Obtener métricas.
* Preparar información para las tablas dinámicas y visualizaciones.

---

## 📊 Visualización de resultados

Los resultados fueron consolidados mediante gráficos y elementos visuales para facilitar la interpretación de la información.

El dashboard permite analizar:

* 📈 Evolución de ventas.
* 🌎 Ventas por país.
* 🛍️ Desempeño de productos.
* 👥 Actividad de clientes.
* 💰 Ingresos.
* 📦 Unidades vendidas.

La visualización fue utilizada como una herramienta para **comunicar los principales hallazgos del análisis de forma clara y orientada al negocio**.

---

## 📌 Key Findings

### 🌎 Concentración geográfica

United Kingdom representa el principal mercado de la empresa, con aproximadamente **9,84 millones** en ventas.

### 📈 Estacionalidad

Noviembre de 2011 presentó el mayor nivel de ingresos del período analizado, con aproximadamente **1,56 millones**.

### 👥 Identificación de clientes

Se identificaron aproximadamente **132.603 transacciones sin CustomerID**, asociadas a cerca de **2,04 millones en ventas**.

Esto representa una oportunidad para mejorar la trazabilidad de los clientes y permitir análisis más completos de comportamiento y valor.

### 🛍️ Productos

El análisis mostró diferencias entre:

* Productos con mayor número de unidades vendidas.
* Productos con mayor frecuencia de transacciones.
* Productos con mayor generación de ingresos.
* Productos de baja rotación.

Esto demuestra la importancia de utilizar diferentes métricas para evaluar el desempeño de un producto.

---

## 💡 Business Recommendations

A partir de los resultados se identificaron algunas oportunidades:

1. **Mejorar la captura del CustomerID** para aumentar la trazabilidad de las transacciones.
2. **Analizar la concentración geográfica** y evaluar oportunidades de crecimiento en otros mercados.
3. **Investigar la estacionalidad de las ventas**, especialmente durante los meses de mayor actividad.
4. **Revisar productos de baja rotación** para evaluar su comportamiento dentro del catálogo.
5. Desarrollar posteriormente una **segmentación RFM** para identificar clientes según recencia, frecuencia y valor monetario.

---

## 🛠️ Tools & Skills

### Herramienta principal

**Microsoft Excel**

### Técnicas utilizadas

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis
* Pivot Tables
* BUSCARX / XLOOKUP
* Excel Formulas
* KPI Analysis
* Data Visualization
* Dashboard
* Business Analysis

---

## 📈 Data Analytics Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Data Validation
   ↓
Data Transformation
   ↓
Pivot Tables & Excel Formulas
   ↓
Exploratory Data Analysis
   ↓
KPI Analysis
   ↓
Data Visualization
   ↓
Business Insights
   ↓
Recommendations
```

---

## 🎯 Skills Demonstrated

Este proyecto demuestra mi capacidad para:

* Trabajar con grandes volúmenes de datos.
* Identificar y tratar problemas de calidad de información.
* Utilizar Excel para análisis de datos.
* Construir tablas dinámicas para explorar información.
* Utilizar BUSCARX para relacionar información.
* Aplicar fórmulas para transformar y analizar datos.
* Construir visualizaciones orientadas al negocio.
* Identificar patrones y oportunidades comerciales.
* Comunicar resultados de forma clara para apoyar la toma de decisiones.
