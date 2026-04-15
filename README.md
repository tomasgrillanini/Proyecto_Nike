# 👟 Nike USA — Análisis Comercial y Rentabilidad 2024

Dashboard de ventas en Power BI sobre el mercado de productos Nike
en Estados Unidos. Analiza facturación, rentabilidad, mix de producto
y performance regional con DAX avanzado y narrativa dinámica.


<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiNjI0NDI3MjctYzU2NS00YTZlLWJhNWUtMzE5M2VlMzE1MWEyIiwidCI6IjViMGFiY2EyLWUwYjYtNGYwYS1iODc4LWE3YmM1Mjg4M2NhMCIsImMiOjR9" target="_blank">
    <img src="https://img.shields.io/badge/ACCEDER_AL_DASHBOARD_INTERACTIVO-EA3D2F?style=for-the-badge&logo=microsoftpowerbi&logoColor=white" alt="Ver Dashboard" />
  </a>
</p>

---

## 🎯 Objetivo

Identificar qué productos, regiones y categorías concentran
el mejor rendimiento comercial, y proponer acciones para optimizar
el mix y mejorar la rentabilidad en zonas con menor desempeño.

## 🔍 Hipótesis

Las regiones con mayores márgenes operativos coinciden con una mayor
presencia de ciertos tipos de productos (calzado vs. indumentaria).
Una estrategia de diversificación en regiones con menor desempeño
podría incrementar los ingresos generales en un 10%.

## 📈 Principales hallazgos

- Facturación total: **$4,62 millones** con margen operativo promedio de ~**55%**
- Crecimiento interanual (YoY): **+25,57%**
- Subcategorías líderes por margen: **Sports Bras** y **Hats**
- Se identificaron líneas con margen ajustado que requieren
  revisión de precios y gestión de costos

## 🛠️ Herramientas y técnicas

- **Power BI** — modelado estrella con 14 tablas de dimensiones,
  dashboard interactivo con tooltips narrativos y títulos dinámicos
- **DAX avanzado** — tabla calendario con estaciones, campañas y
  períodos de liquidación; métricas YoY, ranking Top-N,
  segmentación de margen alto/medio/bajo, narrativa tooltip
- **Power Query** — limpieza de nulos, corrección de tipos de datos,
  columnas calculadas (Ganancia, Rentabilidad %, Tipo de Rentabilidad),
  merge de tablas para escudos por estado

## 📐 Columnas calculadas destacadas
```
Total Facturado  = Precio Unitario × Unidades Vendidas
Ganancia         = (Precio Unitario − Costo Unitario) × Unidades Vendidas
Rentabilidad %   = Ganancia / (Costo Unitario × Unidades Vendidas)
Tipo Rentabilidad → Alta (≥90%) / Media (≥70%) / Baja
```

## 📁 Estructura del proyecto
```
├── INFORME_NIKE.pdf          # Documentación completa del proyecto
├── dashboard_nike.pbix       # Archivo Power BI
└── README.md
```

## 👤 Autor

**Tomás Grillanini** — Data Analyst  
[LinkedIn](#) · [Portfolio](#)
