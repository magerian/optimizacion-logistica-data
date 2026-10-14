# Optimización Volumétrica de Almacenamiento (Slotting), Flujos de Datos y Eficiencia de Costos Operativos

## 📌 Descripción del Proyecto
Este proyecto analítico simula y estructura la metodología implementada para el rediseño estratégico de zonas de almacenaje (*Slotting Optimization*). El objetivo principal radica en integrar variables multidimensionales de demanda, rotación física de inventarios y restricciones volumétricas para maximizar la capacidad del almacén, garantizar la sustentabilidad del espacio en el tiempo y reducir costos logísticos de distribución.

---

## 🚀 1. El Problema de Negocio y Desafío Operativo
El centro de distribución enfrentaba serios problemas de saturación física constante, ineficiencia en los tiempos de preparación de pedidos (*picking*) y un incremento en los costos de expedición debido a:
*   Falta de correlación entre la disposición del inventario y la demanda real (productos de alta rotación ubicados en zonas alejadas).
*   Inexistencia de un control de capacidad basado en **espacio volumétrico ocupado (m³)**, lo que generaba riesgos de quiebres de stock o saturación de espacio.
*   Fugas de rentabilidad debido a tarifas de proveedores logísticos no auditadas analíticamente en relación con los circuitos de envío.

---

## 🛠️ 2. Tecnologías y Herramientas Utilizadas
*   **SQL / Excel Avanzado:** Extracción, normalización, limpieza y procesamiento integral de las bases de datos de inventario, ventas y dimensiones de empaque.
*   **Modelado Analítico Logístico:** Cruce matricial de variables para cálculos de índices de rotación e indicadores volumétricos de ocupación sostenible.
*   **Business Intelligence / Dashboards:** Estructuración de flujos de datos operativos orientados a la creación de reportes y tableros de control para la Alta Dirección.

---

## 📊 3. Metodología y Análisis Paso a Paso

### Fase 1: Limpieza y Preparación de Datos (Integridad desde el Origen)
*   Consolidación de bases de datos heterogéneas (ventas reales, impresiones/rotación, stock físico y dimensiones de productos).
*   Normalización y cálculo del volumen cúbico individual por producto (Alto × Ancho × Largo) para estructurar la variable de espacio volumétrico ocupado.

### Fase 2: Diseño de Flujos de Datos y Clasificación ABC
*   Diseño de un flujo de información para clasificar dinámicamente los productos según su tasa de rotación y nivel de demanda.
*   Mapeo volumétrico del almacén para contrastar la capacidad cúbica disponible contra las proyecciones de inventario a mediano y largo plazo.

### Fase 3: Auditoría y Negociación de Costos
*   Desarrollo de un sistema de análisis de datos de envíos para auditar las rutas de distribución y tarifas de transportistas, proporcionando data confiable para la renegociación de contratos con proveedores.

---

## 📈 4. Resultados e Impacto Logrado
*   **Sustentabilidad del Almacén:** Se garantizó la optimización del uso del espacio físico a largo plazo, anulando la necesidad de incurrir en costos de ampliación de infraestructura o alquiler de depósitos externos.
*   **Eficiencia en Costos y Rentabilidad:** El rediseño de circuitos de distribución y el sistema de auditoría de envíos permitieron identificar fugas financieras y optimizar los acuerdos comerciales con proveedores logísticos, incrementando el margen neto de la operación.
*   **Mejora del Flujo de Trabajo:** Reducción drástica en los tiempos de traslado interno y preparación de pedidos al reubicar estratégicamente las referencias de alta rotación en las zonas óptimas del layout.
*   **Toma de Decisiones Directivas:** Entrega de indicadores clave de rendimiento (KPIs) limpios y tableros de control confiables directamente a la Gerencia.
