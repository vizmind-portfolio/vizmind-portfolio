# 📊 Estudio de Mercado Publicitario 2022–2023

> **VizMind Portfolio** · Inteligencia de Negocio · Análisis de Inversión en Medios

---

## 🧭 Descripción del Proyecto

Dashboard interactivo desarrollado en **Power BI** para analizar la inversión publicitaria por sectores económicos, medios de comunicación y anunciantes durante los años 2022 y 2023. El análisis permite identificar tendencias de inversión, variaciones anuales y el comportamiento táctico de los anunciantes a lo largo del tiempo.

> ⚠️ Los datos han sido anonimizados para proteger la confidencialidad de la fuente original.

---

## 🎯 Objetivo Analítico

Responder preguntas estratégicas del mercado publicitario:

- ¿Cómo evolucionó la inversión publicitaria total entre 2022 y 2023?
- ¿Qué sectores económicos concentran mayor inversión y cómo varían trimestralmente?
- ¿Qué medios capturan mayor participación del presupuesto publicitario?
- ¿Cuál es la variación porcentual anual por anunciante y medio?
- ¿Existen patrones estacionales en la inversión?

---

## 🗂️ Estructura del Reporte

El dashboard está compuesto por **4 páginas** con navegación integrada:

| # | Página | Contenido |
|---|--------|-----------|
| 1 | **Página Principal** | Acumulado anual, estacionalidad y tabla resumen general |
| 2 | **Inversión en Sectores** | Variación trimestral y mensual por sector económico |
| 3 | **Mix de Inversión en Medios** | Participación, variación anual y mensual por medio final |
| 4 | **Táctica en Medios** | Inversión detallada por anunciante y medio con variación % |

---

## 📐 Estructura del Repositorio

```
📁 dashboard-estudio-mercado/
│
├── 📊 Estudio_de_Mercado_2022-2023.pbix   # Archivo Power BI
├── 📂 data/
│   └── historico_2022_2023_anonimizado.csv  # Dataset limpio y anonimizado
├── 📂 screenshots/
│   ├── 01_pagina_principal.png
│   ├── 02_inversion_sectores.png
│   ├── 03_mix_medios.png
│   └── 04_tactica_medios.png
└── 📄 README.md
```

---

## 📌 Campos del Modelo de Datos

| Campo | Descripción |
|-------|-------------|
| `Año` | Año del registro (2022 / 2023) |
| `Año y Trim` | Período trimestral |
| `Mes_L` | Mes en formato texto |
| `Sector Final` | Sector económico del anunciante |
| `Medio Final` | Medio publicitario (TV, digital, prensa, etc.) |
| `Vehículo Final` | Soporte específico dentro del medio |
| `Anunciante` | Empresa anunciante (anonimizada) |
| `NetoMillones` | Inversión neta en millones |
| `Dif A` | Diferencia absoluta anual |
| `VarA%` | Variación porcentual anual |

---

## 🛠️ Herramientas y Técnicas

| Herramienta | Uso |
|-------------|-----|
| **Power BI Desktop** | Modelado, DAX y visualización |
| **Power Query (M)** | Transformación y limpieza de datos |
| **DAX** | Métricas de variación anual, acumulados y KPIs |
| **Custom Visuals** | Advanced Pie/Donut, ZebraBI Cards, Smart Filter Pro |
| **Tabla Calendario** | Modelo de fechas para análisis temporal |

---

## 📊 Tipos de Visualizaciones Usadas

- 📈 Gráfico de líneas — Estacionalidad mensual y variación temporal
- 📊 Gráfico de columnas agrupadas y apiladas — Comparativo por sector y medio
- 🃏 Tarjetas KPI (ZebraBI Cards) — Acumulado anual con comparativo
- 📋 Tablas dinámicas (Pivot Table) — Detalle por anunciante con variación %
- 🔘 Segmentadores (Slicers) — Filtros por año, mes, medio y anunciante
- 🧭 Navegación entre páginas — Page Navigator integrado

---

## 🔍 Hallazgos Clave

> *(Completa esta sección con los insights reales tras revisar el dashboard con datos reales)*

Este tipo de análisis típicamente revela:

- Qué medios ganaron o perdieron participación entre 2022 y 2023.
- Sectores con mayor crecimiento en inversión publicitaria.
- Anunciantes con variación positiva destacada (oportunidades de benchmark).
- Estacionalidad en trimestres específicos que concentran la mayor inversión.

---

## ⚙️ Cómo Usar Este Proyecto

1. Clona o descarga este repositorio.
2. Abre `Estudio_de_Mercado_2022-2023.pbix` en **Power BI Desktop**.
3. Si es necesario, actualiza la ruta del archivo CSV en Power Query → `data/historico_2022_2023_anonimizado.csv`.
4. Navega entre páginas usando el menú de navegación integrado en el dashboard.

> **Versión recomendada:** Power BI Desktop — Octubre 2023 o superior.

---

## 👤 Autor

**VizMind** — Portafolio de Análisis de Datos e Inteligencia de Negocio

[![GitHub](https://img.shields.io/badge/GitHub-VizMind-181717?style=flat&logo=github)](https://github.com/VizMind)

---

*Proyecto desarrollado como parte del portafolio profesional VizMind. Los datos utilizados han sido anonimizados.*
