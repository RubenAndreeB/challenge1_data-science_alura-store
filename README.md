# Análisis Estratégico de Retail: Alura Store Latam

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-ffffff?style=for-the-badge&logo=matplotlib)
![Status](https://img.shields.io/badge/Status-Finalizado-success?style=for-the-badge)

## Descripción del Proyecto

Este proyecto forma parte del **Challenge de Data Science de Alura Latam**. El objetivo principal es actuar como consultor de datos para la cadena de retail "Alura Store", analizando el desempeño comercial y operativo de sus cuatro sucursales.

La meta final es responder a una necesidad crítica de negocio: **Determinar qué tienda debe ser vendida (desinversión) basándose estrictamente en datos.**

## Objetivos del Análisis

1.  **Ingesta de Datos:** Unificar fuentes de datos dispersas (CSVs remotos).
2.  **Análisis Financiero:** Comparar la facturación bruta por sucursal.
3.  **Evaluación de Producto:** Identificar categorías dominantes y productos estancados (Top vs. Bottom).
4.  **Calidad del Servicio:** Medir la satisfacción del cliente (Rating/Estrellas).
5.  **Eficiencia Logística:** Analizar los costos promedio de envío.
6.  **Toma de Decisión:** Generar una recomendación estratégica justificada.

---

## Instalación y Ejecución

Para replicar este análisis en tu entorno local, asegúrate de tener instalado Python y las siguientes dependencias:

pip install pandas matplotlib

### Ejecución del Notebook

El análisis principal se encuentra en el archivo `AluraStoreLatam.ipynb`. Puedes abrirlo con Jupyter Notebook, Jupyter Lab o Google Colab.
> **Nota:** El código descarga automáticamente los datasets desde el repositorio del challenge, por lo que se requiere conexión a internet.

##  Resumen de Hallazgos (Data Insights)

### 1. Ranking de Facturación (Ingresos Totales)
La métrica más crítica para la sostenibilidad del negocio reveló una brecha significativa:

| Posición | Tienda | Facturación ($) | Estatus |
| :--- | :--- | :--- | :--- |
| 🥇 | **Tienda 1** | **$1,150,880,400** | Líder de Mercado |
| 🥈 | Tienda 2 | $1,116,343,500 | Estable |
| 🥉 | Tienda 3 | $1,098,019,600 | Promedio |
| 📉 | **Tienda 4** | **$1,038,375,700** | **Menor Rendimiento** |

> **Insight:** Existe una diferencia de más de **$112 Millones** entre la Tienda 1 y la Tienda 4.

### 2. Eficiencia Operativa (Costo de Envío)
Se analizó el costo promedio que asume cada tienda por envío:
* **Tienda 4:** Es la más eficiente ($23,459 promedio).
* **Tienda 1:** Es la más costosa ($26,018 promedio).

### 3. Satisfacción del Cliente
El análisis de ratings (escala 1-5) mostró un desempeño homogéneo:
* Todas las tiendas se mantienen en un rango entre **3.98 y 4.05**.
* La satisfacción del cliente no es la causa raíz del bajo rendimiento financiero.

### 4. Productos Top vs. Bottom
Se generaron visualizaciones detalladas (Bar Charts horizontales) para entender el mix de productos:
* **Tienda 1 (Top):** Microondas y TV LED (Alto volumen y ticket medio).
* **Tienda 4 (Top):** Cama Box y Cubertería (Ticket alto pero insuficiente volumen total).
* **Problema General:** Todas las tiendas presentan estancamiento en categorías de tecnología menor (Auriculares) e instrumentos musicales.

## Conclusión y Recomendación Final

Tras consolidar las métricas de ingresos, costos y satisfacción, se presenta la siguiente recomendación estratégica al directorio:

### Decisión: VENDER LA TIENDA 4

#### Justificación:
1.  **Insuficiencia de Ingresos:** La Tienda 4 es el "eslabón débil" financiero, facturando un **9.7% menos** que la tienda líder. Esta diferencia de capital ($112M) es demasiado grande para ser ignorada.
2.  **Falsa Eficiencia:** Aunque la Tienda 4 tiene los envíos más baratos, esto se debe a su menor volumen de operación. Ahorrar en envíos no compensa la pérdida masiva de ventas potenciales.
3.  **Costo de Oportunidad:** Mantener la Tienda 4 consume recursos que deberían destinarse a optimizar la logística de la **Tienda 1**, que es la que demuestra la verdadera tracción de mercado.

---

## Autor

**Ruben Andree Barba Magdaleno**
* *Data Scientist en formación*
* https://www.linkedin.com/in/rubenandreebarba/
