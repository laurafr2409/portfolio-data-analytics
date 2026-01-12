# Análisis Estratégico de Adquisición y Conversión (GA4)

## Objetivo del Proyecto
Identificar qué canales de adquisición en la Google Merchandise Store generan valor real. El análisis busca separar el volumen de tráfico de la calidad del mismo, utilizando segmentación avanzada para calcular la eficiencia de conversión por canal.

---

## Exploraciones Realizadas

### 1. Desglose de Calidad de Usuarios (Tabla Segmentada)
![Tabla de Segmentos](./img/tabla_segmentada.png)
* **Técnica:** Segmentación de Usuarios con Compra vs. Usuarios sin Compra.
* **Propósito:** Al segmentar, se pudo calcular el Purchase Conversion Rate (PCR) real por canal, eliminando el ruido de las sesiones no transaccionales y validando la calidad del tráfico de fuentes como Paid Search.

### 2. Visión Ejecutiva de Ingresos (Gráfico de Barras)
![Gráfico de Barras](./img/grafico_barras.png)
* **Técnica:** Análisis de Total Revenue por Canal.
* **Propósito:** Identificar visualmente los pilares financieros del negocio. Este gráfico permite priorizar canales basándose puramente en el retorno económico inmediato.

### 3. Matriz de Eficiencia (Gráfico de Dispersión)
![Scatter Plot](./img/scatter_plot.png)
* **Técnica:** Relación entre Sesiones (X) y PCR (Y).
* **Propósito:** Identificar canales de alto rendimiento. Los canales en el cuadrante superior (alta conversión) son candidatos para aumentar la inversión, mientras que los de alta sesión pero baja conversión requieren optimización de landing page.

---

##  Conclusiones y Recomendaciones
1. **Escalar Paid Search:** Es el canal con mayor eficiencia (PCR) y retorno de inversión; se recomienda incrementar el presupuesto.
2. **Optimizar Organic Search:** Atrae el mayor volumen, pero su conversión es mejorable. Se sugiere revisar el flujo de usuario desde la Home.
3. **Auditar Canales de Baja Intención:** Canales como Display atraen tráfico masivo pero con nula conversión, lo que sugiere una desalineación en el targeting de audiencia.

---

## Stack Técnico
* **Herramienta:** Google Analytics 4 (GA4)
* **Propiedad:** Google Merchandise Store (Demo Account)
* **Técnicas:** Exploraciones de formato libre, Segmentación de audiencia, Análisis de correlación de métricas.
