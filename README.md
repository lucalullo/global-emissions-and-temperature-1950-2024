# Global Climate Analysis: CO₂, Greenhouse Gas Emissions & Temperature Trends (1950-2024)

**75 years of global climate data - exploring how CO₂ emissions, greenhouse gas emissions, surface temperatures, and geographic patterns have changed over time.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white) [![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)

[Kaggle notebook](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024) · [GitHub profile](https://github.com/lucalullo)

## At a glance

| | |
|---|---|
| **Period** | 1950-2024 |
| **Geographic scope** | Global, with country-level comparisons |
| **Focus** | CO₂ emissions, greenhouse gas emissions, surface temperature trends |
| **Sources** | Three country-level climate datasets published on Kaggle |
| **Data** | Global emissions, emission sources, per-capita indicators, and country-level temperatures |
| **Methods** | Exploratory data analysis, time-series comparisons, Pearson correlations |
| **Stack** | Python, pandas, NumPy, Matplotlib, Seaborn, Plotly, Jupyter |

## Key findings

The original notebook highlights six long-term patterns:

1. **CO₂ emissions:** global annual emissions increase from 5,792 MtCO₂ in 1950 to 37,393 MtCO₂ in 2024, approximately **+546%**.
2. **Greenhouse gas emissions:** global annual emissions grow from 17,040 to 54,412 MtCO₂eq, approximately **+219%**.
3. **Surface temperature:** the dataset's reported mean temperature increases from 18.69°C to 20.34°C, a difference of **+1.65°C**.
4. **Emission sources:** natural gas records the largest relative increase among the examined CO₂ sources, rising from 353 to 8,009 MtCO₂ (**+2,168%**).
5. **Geographic differences:** China becomes the largest annual CO₂ emitter, while some of the strongest reported country-level temperature increases occur in Central Asia.
6. **Statistical relationships:** global emissions and mean temperature exhibit strong positive correlations across the observed period.

### Key indicators

| Indicator | 1950 | 2024 | Change |
|---|---:|---:|---:|
| Global CO₂ emissions | 5,792 MtCO₂ | 37,393 MtCO₂ | **+546%** |
| Global GHG emissions | 17,040 MtCO₂eq | 54,412 MtCO₂eq | **+219%** |
| Reported mean temperature | 18.69°C | 20.34°C | **+1.65°C** |
| Largest annual CO₂ emitter | USA | China | - |
| Natural gas CO₂ emissions | 353 MtCO₂ | 8,009 MtCO₂ | **+2,168%** |

These are descriptive findings from the analyzed datasets, not causal claims about individual climate drivers. The reported temperature series should not automatically be interpreted as a standard global temperature anomaly relative to a pre-industrial baseline.

## Methodology

```text
Global climate datasets
          |
          v
    Data inspection
          |
          v
Global emissions and temperature trends
          |
          v
  Emission source analysis
          |
          v
Country rankings and comparisons
          |
          v
  Geographic visualizations
          |
          v
  Statistical correlations
          |
          v
Interpretation and limitations
```

### What the notebook visualizes

- **Global emissions (1950-2024):** annual CO₂ and greenhouse gas emissions, including decade-over-decade growth comparisons.
- **Temperature trends (1950-2024):** reported mean surface temperatures and long-term changes.
- **Emission sources:** coal, oil, natural gas, and cement contributions through stacked area charts and percentage-share visualizations.
- **Country emissions:** top 15 CO₂ and GHG emitters in 2024, per-capita emissions, and the cumulative contribution of the five largest emitters.
- **Country-level warming:** temperature changes between 1950 and 2024, country rankings, and five-year rolling averages.
- **Geographic patterns:** choropleth maps of per-capita CO₂ emissions and temperature changes, including an animated emissions map.
- **Statistical relationships:** correlation matrices and scatter plots with linear trend lines comparing emissions and temperatures.

### Selected results

**Emission sources**

Natural gas CO₂ emissions increase from **353 MtCO₂ to 8,009 MtCO₂ (+2,168%)**, representing the largest relative growth among the four examined sources.

The analysis also highlights the growing contribution of China and India to global emissions from the 2000s onward.

**Country-level comparisons**

The notebook examines total emissions, per-capita emissions, and national shares of global emissions.

Selected observations from the analyzed data include:

- **China:** approximately 32.9% of global CO₂ emissions and 8.7 tonnes per capita in 2024.
- **Saudi Arabia and Kuwait:** reported per-capita CO₂ emissions exceeding 20 tonnes, with some values above 40 tonnes.
- **Top five emitters:** their combined contribution is tracked over time against the rest of the world.

**Temperature changes**

The largest reported country-level temperature increases between 1950 and 2024 include:

| Country | Temperature change |
|---|---:|
| Uzbekistan | **+3.48°C** |
| Kazakhstan | **+3.29°C** |
| Kyrgyzstan | **+3.20°C** |

Five-year rolling averages are used to reduce short-term fluctuations and highlight longer-term patterns.

**Statistical correlations**

The analysis reports the following Pearson correlation coefficients:

| Variables | Pearson correlation |
|---|---:|
| Global CO₂ emissions vs. mean temperature | **0.895** |
| Global GHG emissions vs. mean temperature | **0.889** |

These correlations describe statistical associations between time-dependent aggregates. They do **not** establish direct causality or isolate the effects of individual climate drivers.

## Data

The analysis combines three datasets published on Kaggle:

| Dataset | Contents |
|---|---|
| [Global Mean Temperature by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-mean-temperature-by-country-1950-2024) | Country-level mean surface temperature records |
| [Global CO₂ Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-co2-emissions-by-country-1950-2024) | CO₂ emissions, per-capita indicators, and emission sources |
| [Global GHG Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-ghg-gas-emissions-by-country-1950-2024) | Greenhouse gas emissions by country |

The datasets are available through Kaggle. Refer to their respective pages for access and applicable terms of use.

## Repository structure

```text
global-emissions-and-temperature-1950-2024/
├── README.md
└── global-emissions-and-temperature-1950-2024.ipynb
```

The notebook contains the exploratory analysis, statistical comparisons, geographic visualizations, and interpretation of the climate datasets.

## Getting started

The original notebook was developed for Kaggle, where the analysis and its associated datasets are available.

**[Open the original Kaggle notebook](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)**

To run it locally:

1. Download the three datasets linked above.
2. Install dependencies: `python -m pip install pandas numpy matplotlib seaborn plotly jupyter`.
3. Open `global-emissions-and-temperature-1950-2024.ipynb` in Jupyter.
4. Make the downloaded datasets available to the notebook.
5. Adjust any Kaggle-specific dataset paths to match your local file locations.

These path adjustments are necessary only when the local environment differs from the original Kaggle setup.

## Limitations

- The work is **descriptive exploratory analysis**, not a causal attribution study or a climate forecasting model.
- Correlations between emissions and temperatures do **not** independently establish causation, particularly when comparing variables with long-term trends.
- The reported mean temperature series should not automatically be interpreted as a standardized global temperature anomaly relative to a pre-industrial baseline.
- Country-level temperature differences depend on dataset coverage, measurement definitions, and the selected reference years.
- Temperature differences calculated from individual years may be influenced by short-term climate variability.
- National emission totals and per-capita indicators describe different aspects of environmental pressure and should not be treated as interchangeable.
- The analysis presents historical trends and statistical associations rather than formal causal tests or estimates of uncertainty.
- The data cover **1950-2024**, not subsequent years.

## Related work

This analysis complements my work on exploratory data analysis, statistical visualization, and reproducible Python projects.

**[GitHub profile](https://github.com/lucalullo) · [Kaggle profile](https://www.kaggle.com/lucalullo)**

## Author

Created by [Luca Lullo](https://github.com/lucalullo).
