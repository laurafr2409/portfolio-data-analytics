#  Análisis Estratégico de Adquisición y Embudo de Conversión (GA4)

##  Objetivo del Proyecto
El propósito de este análisis es evaluar el rendimiento de los canales de adquisición de la **Google Merchandise Store** y diagnosticar la eficiencia del embudo de ventas. La investigación se centra en identificar qué fuentes de tráfico generan ingresos reales y en qué etapas del proceso de compra se producen los mayores abandonos de usuarios.

---

##  Metodología Técnica
Para garantizar la precisión de los hallazgos en la propiedad demo de GA4, se aplicaron las siguientes técnicas de análisis avanzado:

* **Segmentación de Audiencias:** División de la data entre **"Usuarios con compra"** y **"Usuarios sin compra"** para normalizar las métricas de comportamiento.
* **Análisis de Cohortes:** Evaluación de la retención de usuarios activos por semana para medir la recurrencia.
* **Visualización de Embudos (Funnel Exploration):** Mapeo del recorrido desde la visualización del producto hasta la transacción final.

---

##  Exploraciones y Hallazgos Clave

### 1. Rendimiento por Canal de Adquisición (Tabla Segmentada)
![Tabla de Segmentos](../img/tabla_segmentada.png)
* **Análisis:** Al desglosar los grupos de canales, se observa que el canal **Direct** es el motor principal de ingresos, generando **$58,024.28** mediante 1,146 sesiones con compra.
* **Eficiencia:** El canal **Cross-network** presenta el *Purchase Conversion Rate* más alto del desglose con un **0.55%**.

### 2. Visión Ejecutiva de Ingresos
![Gráfico de Barras](../img/grafico_barras_compacto.png)
* **Hallazgo:** Existe una dominancia clara de los ingresos provenientes de **Direct** y **Organic Search**.
* **Contexto:** Los canales de pago (**Paid Search**) ocupan el tercer lugar en volumen de facturación, seguidos por Cross-network y Referral.

### 3. Matriz de Eficiencia (Scatter Plot)
![Scatter Plot](../img/scatter_plot.png)
* **Interpretación:** El gráfico permite identificar que **Organic Search** y **Direct** concentran el mayor volumen de sesiones, pero su tasa de conversión es moderada en comparación con canales de menor volumen pero alta eficiencia.

### 4. Diagnóstico del Embudo de Compra
![Embudo de Conversión](../img/embudo_pasos.png)
* **Punto de Abandono Crítico:** El mayor porcentaje de abandono ocurre inmediatamente después del primer paso (**Ver artículo**), donde el **73.5%** de los usuarios no avanza hacia el carrito.
* **Tasa de Cierre:** Una vez que el usuario llega a la etapa de **Checkout**, la tasa de finalización hacia la **Compra** es saludable, alcanzando un **54.1%**.

---

##  Conclusiones y Recomendaciones Estratégicas

1.  **Optimización de la Intención en el Sitio:** Dado que el abandono inicial es del 73.5%, se recomienda revisar la relevancia de las páginas de producto y la experiencia de usuario (UX) para incentivar la acción de "Añadir al carrito".
2.  **Escalabilidad de Cross-network:** Este canal demuestra ser el más eficiente en conversión (0.55%). Se sugiere evaluar un incremento en la inversión controlada para este segmento.
3.  **Fidelización del Tráfico Direct:** Al ser la mayor fuente de ingresos ($58k), es crítico mantener estrategias de retención para usuarios recurrentes, ya que son la base de la estabilidad financiera de la tienda.
4.  **Refuerzo de SEO (Organic Search):** Con un ingreso de **$28,736.88**, el tráfico orgánico es un pilar fundamental, pero requiere optimización en el flujo de navegación para mejorar su tasa de conversión actual.

---
**Tecnologías utilizadas:** Google Analytics 4 (Exploraciones de formato libre, Análisis de cohortes, Embudos de conversión y Segmentación personalizada).
