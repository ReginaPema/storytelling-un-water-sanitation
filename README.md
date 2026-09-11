# <img src="https://img.icons8.com/?size=60&id=2WP6HZwhbWw8&format=png&color=000000" align="center"/> Data Storytelling: Global Water & Sanitation Access
## Storytelling de Datos: Acceso Global a Agua y Saneamiento

> **EN** · Data storytelling and interactive dashboard on global access to safely managed drinking water and sanitation (2010–2024), built on official United Nations data. Each visualization is grounded in a named visual-perception or design principle, and every non-obvious claim is verified with a printed, reproducible check inside the notebook.
>
> **ES** · Storytelling de datos y dashboard interactivo sobre el acceso mundial a agua potable y saneamiento gestionados de forma segura (2010–2024), construido sobre datos oficiales de Naciones Unidas. Cada visualización se fundamenta en un principio de percepción visual o diseño con nombre y autor, y cada afirmación no evidente se verifica con un chequeo impreso y reproducible dentro del notebook.

---

## <img src="https://img.icons8.com/?size=40&id=Ihw7rsNxtanQ&format=png&color=000000" align="center"/> Overview / Descripción

**EN** · This project turns a UN Statistical Yearbook table into a 5-chart data narrative plus an interactive Plotly + Dash dashboard: a global trend overview, an urban-rural gap comparison, a regional ranking, a world map, and a time evolution of the gap. Each chart answering one specific question to tell a story instead of just displaying data.

**ES** · Este proyecto convierte una tabla del Statistical Yearbook de la ONU en una narrativa de 5 gráficos más un dashboard interactivo con Plotly y Dash: panorama de tendencia global, comparación de brecha urbano-rural, ranking regional, mapa mundial y evolución de la brecha en el tiempo. Cada gráfico responde una pregunta concreta para contar una historia en lugar de solo muestrar datos.

---

## <img src="https://img.icons8.com/?size=40&id=80351&format=png&color=000000" align="center"/> Key Findings / Hallazgos Clave

### 1. Global progress, unevenly distributed / Progreso global, distribuido de forma desigual
- **EN** · Global safely managed sanitation access rose from **41.5% (2010) to 58.5% (2024)**; drinking water from **64.8% to 73.7%**. Steady progress worldwide, but that single global number hides where the gains actually landed.
- **ES** · El acceso mundial a saneamiento seguro subió de **41.5% (2010) a 58.5% (2024)**; el agua potable, de **64.8% a 73.7%**. Progreso constante a nivel mundial, pero esa única cifra global oculta dónde realmente llegaron esas ganancias.

### 2. The urban-rural gap varies by an order of magnitude / La brecha urbano-rural varía en un orden de magnitud
- **EN** · Comparing sanitation access across 11 UN sub-regions with complete data, the urban-rural gap ranges from **47.0 percentage points in Eastern Asia** (85.1% urban vs. 38.1% rural) down to just **5.4pp in Western Europe**. The same global indicator, radically different local realities.
- **ES** · Al comparar el acceso a saneamiento entre las 11 subregiones de la ONU con dato completo, la brecha urbano-rural va de **47.0 puntos porcentuales en Asia Oriental** (85.1% urbano vs. 38.1% rural) hasta apenas **5.4pp en Europa Occidental**. El mismo indicador global, realidades locales radicalmente distintas.

### 3. A reversed pattern in 3 of 11 sub-regions / Un patrón invertido en 3 de 11 subregiones
- **EN** · In **Central Asia (-18.5pp), South-eastern Asia (-8.5pp) and Southern Asia (-7.8pp)**, rural sanitation access is *higher* than urban, the opposite of the pattern in the other 8 sub-regions. This directly contradicts a "rural always lags urban" assumption and is likely explained by historical rural infrastructure investment outpacing unplanned urban growth.
- **ES** · En **Asia Central (-18.5pp), Sudeste Asiático (-8.5pp) y Asia Meridional (-7.8pp)**, el acceso rural a saneamiento es *mayor* que el urbano, el patrón opuesto al de las otras 8 subregiones. Esto contradice directamente el supuesto de que "lo rural siempre va detrás de lo urbano", y probablemente se explica por inversión histórica en infraestructura rural que superó el crecimiento urbano no planificado.

### 4. "Total" is a population-weighted average, not a sum / "Total" es un promedio ponderado por población, no una suma
- **EN** · The UN's reported "Total" coverage figure could be mistaken for Urban + Rural. Verified against the official SDG 6.2.1 methodology (UNSD): it's a population-weighted average, which is why it always falls *between* the urban and rural values rather than above both.
- **ES** · La cifra de cobertura "Total" que reporta la ONU podría confundirse con Urbano + Rural. Verificado contra la metodología oficial del indicador SDG 6.2.1 (UNSD): es un promedio ponderado por población, por eso siempre cae *entre* los valores urbano y rural, nunca por encima de ambos.

### 5. Map coverage gaps have real, traceable causes / Los vacíos del mapa tienen causas reales y rastreables
- **EN** · Only **159 of the 249** countries/territories in the UN's M49 catalog have a reported drinking-water figure for 2024; traced to real reporting gaps (e.g. Sudan, Bolivia have none at all), plus one fixable case: Eswatini's data exists but wasn't rendering, because Plotly's internal country-matching library still expects its pre-2018 name ("Swaziland").
- **ES** · Solo **159 de los 249** países/territorios del catálogo M49 de la ONU tienen dato reportado de agua potable en 2024; rastreado a vacíos reales de reporte (p. ej. Sudán, Bolivia no tienen ninguno), más un caso corregible: el dato de Eswatini existe pero no se pintaba, porque la librería interna de Plotly para reconocer países sigue esperando su nombre anterior a 2018 ("Swaziland").

---

## <img src="https://img.icons8.com/?size=40&id=5UkvQrF1KgvR&format=png&color=000000" align="center"/> Design Principles Applied / Principios de Diseño Aplicados

| Principle / Principio | Author(s) / Autor(es) |
|---|---|
| Prägnanz, Continuity, Similarity, Proximity, Enclosure / Prägnanz, Continuidad, Similaridad, Proximidad, Confinamiento | Wertheimer (1923) |
| Isomorphic correspondence / Correspondencia isomórfica | Köhler (1929) |
| Connectedness / Conexión | Palmer & Rock (1994) |
| Focal point (pre-attentive attention) / Punto focal (atención pre-atentiva) | Treisman & Gelade (1980) |
| Data-ink ratio, small multiples, chartjunk reduction / Razón dato-tinta, pequeños múltiplos, reducción de chartjunk | Tufte (1983) |
| Perceptual accuracy hierarchy, 45° banking / Jerarquía de precisión perceptual, ángulo de 45° | Cleveland & McGill (1984) |
| Sequential single-hue color scales / Escalas de color secuenciales de un matiz | Brewer (ColorBrewer) |

---

## <img src="https://img.icons8.com/?size=40&id=80431&format=png&color=000000" align="center"/> Tools / Herramientas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-b48cba?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-d19999?style=flat&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-008DE4?style=flat&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-C4A882?style=flat&logo=jupyter&logoColor=white)

---

## <img src="https://img.icons8.com/?size=45&id=80742&format=png&color=000000" align="center"/> Interactive Dashboard / Dashboard Interactivo

**EN** · Runs standalone (`python dash_app.py`) or inline from the notebook. Indicator selector (water/sanitation), region-highlight dropdown, and a year slider driving a world choropleth; all sharing the same region-classification logic as the static charts.

**ES** · Corre de forma independiente (`python dash_app.py`) o embebido desde el notebook. Selector de indicador (agua/saneamiento), dropdown para destacar una región, y un slider de año que controla un mapa mundial; todos comparten la misma lógica de clasificación regional que los gráficos estáticos.

---

## <img src="https://img.icons8.com/?size=40&id=h1xAEugGPnnt&format=png&color=000000" align="center"/> Run it / Cómo ejecutarlo

```bash
git clone https://github.com/ReginaPema/storytelling-un-water-sanitation.git
cd storytelling-un-water-sanitation
pip install -r requirements.txt

jupyter notebook notebook/Water_Sanitation_Storytelling.ipynb
# or:
cd dashboard && python dash_app.py    # then open http://127.0.0.1:8050
```

---

## <img src="https://img.icons8.com/?size=40&id=80358&format=png&color=000000" align="center"/> Data Source / Fuente de Datos

- [data.un.org — Water and Sanitation Services, Statistical Yearbook Table 27](https://data.un.org/_Docs/SYB/CSV/SYB68_315_202511_Water%20and%20Sanitation%20Services.csv), original source: WHO/UNICEF Joint Monitoring Programme (JMP).
- [UNSD — Standard Country or Area Codes for Statistical Use (M49)](https://unstats.un.org/unsd/methodology/m49/overview/).

---

## <img src="https://img.icons8.com/?size=40&id=PhymLYNNjf3I&format=png&color=000000" align="center"/> Repository Structure / Estructura

    storytelling-un-water-sanitation/
    ├── notebook/
    │   └── Water_Sanitation_Storytelling.ipynb
    ├── data/
    │   ├── SYB68_315_202511_Water_and_Sanitation_Services.csv   # UN Statistical Yearbook, Table 27
    │   └── UNSD_M49_Standard_Region_Codes.csv                   # UN M49 geographic code catalog
    ├── dashboard/
    │   └── dash_app.py
    ├── README.md
    └── requirements.txt

---

*Project developed as part of the Data Scientist Certificate ·
Proyecto desarrollado como parte del certificado Científico de Datos — EBAC (2026)* <img src="https://img.icons8.com/?size=35&id=FgMs84V9yrMV&format=png&color=000000" align="center"/>
