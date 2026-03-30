# 🔴 VIF vs Partidos FPC — Análisis de Datos

## 📌 Objetivo
Analizar si existe correlación entre los resultados de los partidos del Fútbol Profesional Colombiano (FPC) y los casos de Violencia Intrafamiliar (VIF) reportados en ciudades con equipos de Primera División (2021–2025).

---

## 🛠 Herramientas
- **Power BI Desktop** — Dashboard interactivo
- **Python** (pandas, matplotlib) — Procesamiento y visualización
- **Fuentes de datos:** SIEDCO (Policía Nacional de Colombia) + API FPC

---

## 📊 Insights Principales

- 🔴 Las victorias del equipo **visitante** correlacionan con el mayor promedio de casos VIF **(8.8 casos/día)** — el resultado más alto entre todas las categorías analizadas
- 📈 Se observa una **tendencia al aumento de VIF** en la mayoría de ciudades con equipo FPC, independientemente del resultado del partido
- 📅 **Diciembre muestra subregistro sistemático** — los datos de ese mes deben interpretarse con cautela
- 🏙️ Los patrones varían significativamente por ciudad, lo que sugiere factores locales adicionales más allá del resultado deportivo

---

## 🗂 Estructura del Repositorio

| Archivo/Carpeta | Descripción |
|---|---|
| `vif_fpc.pbix` | Dashboard principal en Power BI |
| `dataset_vif.csv` | Casos VIF 2021–2025 por ciudad |
| `dataset_fpc.csv` | Partidos FPC 2021–2025 |
| `screenshots/` | Capturas del dashboard |
| `notebooks/` | Scripts Python de análisis |

---

## 🖼 Dashboard Preview

![Dashboard Principal](screenshots/dashboard_main.png)

---

## 📂 Fuentes de Datos

- **VIF:** Sistema de Información Estadístico, Delincuencial, Contravencional y Operativo (SIEDCO) — Policía Nacional de Colombia
- **FPC:** Resultados oficiales de partidos del Fútbol Profesional Colombiano

---

## ⚠️ Limitaciones

- El subregistro en diciembre puede afectar el análisis de tendencias anuales
- La correlación encontrada **no implica causalidad** — se requieren estudios adicionales para establecer relaciones causales
- Los datos de algunas ciudades pueden estar incompletos para ciertos períodos

---

## 👤 Autor

**[Tu Nombre]**  
Analista de Datos en formación | Barranquilla, Colombia  
[LinkedIn](#) · [GitHub](#)

---

*Proyecto desarrollado como parte del portafolio profesional de análisis de datos.*
