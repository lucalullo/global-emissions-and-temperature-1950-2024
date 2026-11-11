
# Global Climate Analysis: CO₂, Greenhouse Gas Emissions & Temperature Trends (1950-2024)

**75 years of global climate data - analyzing CO₂ emissions, greenhouse gas emissions, and temperature trends across countries from 1950 to 2024.**

This project explores long-term changes in global emissions and surface temperatures through time-series analysis, country-level comparisons, statistical correlations, and interactive geographic visualizations.

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data_Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Plots-4C72B0)
![Plotly](https://img.shields.io/badge/Plotly-Interactive_Maps-3F4F75?logo=plotly&logoColor=white)

**[View the original Kaggle notebook](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)** | **[Explore the notebook](global-emissions-and-temperature-1950-2024.ipynb)** | **[Author's GitHub](https://github.com/lucalullo)**

---

## At a glance

| | |
|---|---|
| **Period** | 1950-2024 (75 years) |
| **Geographic scope** | Global, with country-level comparisons |
| **Focus** | CO₂ emissions, greenhouse gas emissions, surface temperature trends |
| **Data** | Three Kaggle datasets covering emissions and temperatures by country |
| **Methods** | Exploratory data analysis, time-series comparisons, correlation analysis |
| **Visualizations** | Line charts, stacked area charts, bubble plots, choropleth maps |
| **Core libraries** | pandas, NumPy, Matplotlib, Seaborn, Plotly |
| **Environment** | Python and Jupyter Notebook |

## Key observations

The original notebook highlights several long-term patterns:

1. **Global CO₂ emissions:** annual emissions increase from 5,792 MtCO₂ in 1950 to 37,393 MtCO₂ in 2024, a rise of approximately **546%**.
2. **Greenhouse gas emissions:** annual emissions grow from 17,040 to 54,412 MtCO₂eq over the same period, an increase of approximately **219%**.
3. **Surface temperature:** the dataset's reported mean temperature rises from 18.69°C to 20.34°C, a difference of **1.65°C**.
4. **Emission sources:** natural gas records the largest relative increase among the examined CO₂ sources, growing from 353 to 8,009 MtCO₂.
5. **Geographic differences:** China becomes the largest annual CO₂ emitter, while the strongest reported country-level temperature increases occur in Central Asia.
6. **Statistical relationships:** global emissions and mean temperature show strong positive correlations across the observed period.

These findings describe patterns in the analyzed datasets. Correlations and temporal associations should not be interpreted as direct evidence of causality.

### Key indicators

| Indicator | 1950 | 2024 | Change |
|---|---:|---:|---:|
| Global CO₂ emissions | 5,792 MtCO₂ | 37,393 MtCO₂ | **+546%** |
| Global GHG emissions | 17,040 MtCO₂eq | 54,412 MtCO₂eq | **+219%** |
| Reported mean temperature | 18.69°C | 20.34°C | **+1.65°C** |
| Largest annual CO₂ emitter | USA | China | - |
| Natural gas CO₂ emissions | 353 MtCO₂ | 8,009 MtCO₂ | **+2,168%** |

## Analysis workflow

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

- **Global trends (1950-2024):** annual CO₂ emissions, greenhouse gas emissions, and mean temperature, including decade-over-decade growth comparisons.
- **Emission source composition:** coal, oil, natural gas, and cement contributions through absolute stacked area charts and percentage-share visualizations.
- **Country emissions:** top 15 CO₂ and GHG emitters in 2024, per-capita emissions, and the cumulative share of the five largest emitters.
- **Country-level warming:** temperature changes between 1950 and 2024, rankings of the most and least warmed countries, and five-year rolling averages.
- **Geographic patterns:** choropleth maps of per-capita CO₂ emissions and temperature changes, including an animated emissions map.
- **Statistical relationships:** correlation matrices and scatter plots with linear trend lines comparing emissions and temperatures.

## Detailed findings

### Emissions and energy sources

The analysis examines the changing composition of global CO₂ emissions across coal, oil, natural gas, and cement.

Natural gas emissions increase from **353 MtCO₂ to 8,009 MtCO₂ (+2,168%)**, representing the largest relative growth among the examined sources.

The notebook also highlights the increasing contribution of China and India to global emissions from the 2000s onward.

### Country-level comparisons

The 2024 analysis combines total emissions, per-capita emissions, and global shares to distinguish between national emission volumes and population-adjusted contributions.

- **China:** 32.9% of global CO₂ emissions and approximately 8.7 tonnes per capita in the analyzed data.
- **Saudi Arabia and Kuwait:** per-capita CO₂ emissions exceeding 20 tonnes, with values reaching above 40 tonnes in the reported comparisons.
- **Top five emitters:** their combined contribution is tracked over time against the rest of the world.

### Temperature changes

The notebook compares country-level temperature differences between 1950 and 2024.

The largest reported increases include:

| Country | Temperature change |
|---|---:|
| Uzbekistan | **+3.48°C** |
| Kazakhstan | **+3.29°C** |
| Kyrgyzstan | **+3.20°C** |

Five-year rolling averages are also used to visualize temperature trends while reducing short-term fluctuations.

### Statistical correlations

The analysis reports strong positive correlations between global emissions and the dataset's mean temperature series:

| Variables | Pearson correlation |
|---|---:|
| Global CO₂ vs. mean temperature | **0.895** |
| Global GHG vs. mean temperature | **0.889** |

These are descriptive correlations between time-dependent aggregates. They do **not** establish direct causality or isolate the effects of individual climate drivers.

## Datasets

The analysis combines three datasets published on Kaggle:

| Dataset | Contents |
|---|---|
| [Global Mean Temperature by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-mean-temperature-by-country-1950-2024) | Country-level mean surface temperature records |
| [Global CO₂ Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-co2-emissions-by-country-1950-2024) | CO₂ emissions, per-capita indicators, and emission sources |
| [Global GHG Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-ghg-gas-emissions-by-country-1950-2024) | Greenhouse gas emissions by country |

The datasets are available through Kaggle. Refer to their respective pages for access and applicable terms of use.

## Repository contents

```text
Global-emissions-and-temperature-1950-2024/
├── README.md
└── global-emissions-and-temperature-1950-2024.ipynb
```

The notebook contains the exploratory analysis, statistical comparisons, visualizations, and interpretation of the climate datasets.

## Run the notebook

The reference environment is **Kaggle**, where the original notebook and its associated datasets are available.

To run it locally, install the required dependencies:

```bash
python -m pip install pandas numpy matplotlib seaborn plotly jupyter
```

Then:

1. Download the three datasets linked above.
2. Open `global-emissions-and-temperature-1950-2024.ipynb` in Jupyter.
3. Make the downloaded data files available to the notebook.
4. Update any Kaggle-specific dataset paths to match the local file locations.

These path adjustments are necessary only when the local environment differs from the original Kaggle setup.

## Scope and limitations

- The work is **descriptive exploratory analysis**, not a causal attribution study or a climate forecasting model.
- Correlations between emissions and temperatures do not establish causation, particularly when comparing variables with long-term trends.
- Country-level temperature differences depend on dataset coverage, measurement definitions, and the selected reference years.
- The reported mean temperature series should not automatically be interpreted as the standard global temperature anomaly relative to a pre-industrial baseline.
- National emission totals and per-capita indicators describe different aspects of environmental pressure and should not be treated as interchangeable.
- The analysis covers **1950-2024** and does not include subsequent years.

## Related work

This project complements my other work on exploratory data analysis, statistical visualization, and reproducible Python projects.

- [GitHub profile and selected projects](https://github.com/lucalullo)
- [Kaggle profile](https://www.kaggle.com/lucalullo)

---

**Author:** [Luca Lullo](https://github.com/lucalullo)  
**Original Kaggle work:** [Global Emissions and Temperature (1950-2024)](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)
