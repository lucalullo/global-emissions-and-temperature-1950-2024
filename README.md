# Global Climate Analysis: CO₂ Emissions, Greenhouse Gases & Temperature Trends (1950-2024)

**Exploring 75 years of global climate data through emissions analysis, temperature trends, country-level comparisons, and interactive visualizations.**

This project investigates the evolution of global CO₂ emissions, greenhouse gas (GHG) emissions, and surface temperatures from 1950 to 2024. Using three country-level datasets, it combines exploratory data analysis, time-series comparisons, statistical correlations, and geographic visualizations to identify long-term patterns and regional differences.

[![Kaggle Notebook](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)
![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data_Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Plots-4C72B0)
![Plotly](https://img.shields.io/badge/Plotly-Interactive_Maps-3F4F75?logo=plotly&logoColor=white)

**[View on Kaggle](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)** | **[Explore the Notebook](global-emissions-and-temperature-1950-2024.ipynb)** | **[GitHub Profile](https://github.com/lucalullo)**

---

## Overview

Understanding long-term climate patterns requires examining both the evolution of greenhouse gas emissions and the geographic distribution of temperature changes.

This project provides a comprehensive exploratory analysis of global climate indicators across 75 years, combining historical trends, emission-source decomposition, country-level rankings, and statistical relationships.

The analysis addresses five main questions:

1. How have global CO₂ and greenhouse gas emissions changed since 1950?
2. How has the composition of emissions evolved across major sources?
3. Which countries contribute most to global emissions, both in absolute and per-capita terms?
4. How do reported surface temperature changes differ across countries?
5. What statistical relationships emerge between emissions and temperature trends?

The objective is to provide a reproducible, data-driven exploration of these patterns rather than a causal attribution study or climate forecasting model.

### Project at a Glance

| Category | Description |
|---|---|
| **Period** | 1950-2024 (75 years) |
| **Geographic Scope** | Global, with country-level comparisons |
| **Focus** | CO₂ emissions, GHG emissions, temperature trends |
| **Datasets** | Three Kaggle datasets |
| **Methods** | Exploratory analysis, time-series analysis, statistical correlations |
| **Visualizations** | Line charts, stacked area charts, bubble plots, choropleth maps |
| **Technologies** | Python, pandas, NumPy, Matplotlib, Seaborn, Plotly |
| **Environment** | Jupyter Notebook, Kaggle |

---

## Key Findings

The analysis identifies several long-term patterns in the examined datasets:

- **Global CO₂ emissions:** Annual emissions increased from 5,792 MtCO₂ in 1950 to 37,393 MtCO₂ in 2024, approximately **+546%**.
- **Greenhouse gas emissions:** Annual emissions increased from 17,040 to 54,412 MtCO₂eq, approximately **+219%**.
- **Surface temperature:** The dataset's reported mean temperature increased from 18.69°C to 20.34°C, a difference of **+1.65°C**.
- **Emission sources:** Natural gas recorded the largest relative increase among the examined CO₂ sources, rising from 353 to 8,009 MtCO₂.
- **Geographic distribution:** China emerged as the largest annual CO₂ emitter, while some of the strongest reported country-level temperature increases occurred in Central Asia.
- **Statistical relationships:** Global emissions and the reported mean temperature series exhibited strong positive correlations over the observed period.

### Key Indicators

| Indicator | 1950 | 2024 | Change |
|---|---:|---:|---:|
| Global CO₂ emissions | 5,792 MtCO₂ | 37,393 MtCO₂ | **+546%** |
| Global GHG emissions | 17,040 MtCO₂eq | 54,412 MtCO₂eq | **+219%** |
| Reported mean temperature | 18.69°C | 20.34°C | **+1.65°C** |
| Largest annual CO₂ emitter | USA | China | - |
| Natural gas CO₂ emissions | 353 MtCO₂ | 8,009 MtCO₂ | **+2,168%** |

**Important:** These values reflect the datasets analyzed in the notebook. The reported mean temperature series should not be interpreted as a standard global temperature anomaly relative to a pre-industrial baseline.

Correlations and temporal associations are descriptive findings and do not independently establish causality.

---

## Methodology

The project follows a structured exploratory workflow, progressing from data inspection to statistical interpretation.

### Analysis Workflow

```text
Global Climate Datasets
          |
          v
Data Inspection & Preparation
          |
          v
Global Emissions & Temperature Trends
          |
          v
Emission Source Analysis
          |
          v
Country-Level Comparisons
          |
          v
Geographic Visualizations
          |
          v
Statistical Correlation Analysis
          |
          v
Findings & Limitations
```

### 1. Global Trends

Examination of long-term changes in global climate indicators between 1950 and 2024.

The analysis includes:

- Annual global CO₂ emissions.
- Annual global greenhouse gas emissions.
- Reported mean surface temperature trends.
- Decade-over-decade growth comparisons.
- Long-term temporal patterns.

### 2. Emission Source Analysis

Investigation of the changing composition of CO₂ emissions across four major sources:

- Coal.
- Oil.
- Natural gas.
- Cement.

Stacked area charts and percentage-share visualizations illustrate both absolute contributions and changes in emission composition over time.

### 3. Country-Level Comparisons

Comparison of national emissions using complementary indicators:

- Total annual CO₂ and GHG emissions.
- Top 15 emitters in 2024.
- Per-capita CO₂ emissions.
- National shares of global emissions.
- Combined contribution of the five largest emitters.

These indicators help distinguish absolute emission volumes from population-adjusted contributions.

### 4. Temperature Analysis

Examination of country-level temperature changes between 1950 and 2024.

The analysis includes:

- Temperature differences between reference years.
- Countries with the largest and smallest reported changes.
- Geographic comparisons.
- Five-year rolling averages to reduce short-term variability.

### 5. Geographic Visualizations

Interactive Plotly visualizations are used to explore spatial patterns.

They include:

- Choropleth maps of per-capita CO₂ emissions.
- Maps of country-level temperature changes.
- Animated geographic representations of emissions over time.

### 6. Statistical Analysis

Pearson correlation coefficients, correlation matrices, and scatter plots with linear trend lines are used to examine statistical associations between emissions and temperature indicators.

These analyses describe relationships in the observed data without establishing causal attribution.

---

## Results

### Global Emissions and Energy Sources

The examined datasets show substantial increases in global emissions over the 1950-2024 period.

Natural gas CO₂ emissions increased from **353 MtCO₂ to 8,009 MtCO₂**, representing approximately **+2,168%**.

This was the largest relative increase among the four emission sources examined.

The analysis also highlights the growing contribution of China and India to global emissions from the 2000s onward.

### Geographic Distribution of Emissions

The 2024 country-level analysis combines total emissions, per-capita emissions, and national shares of global totals.

Selected observations from the analyzed data include:

- **China:** Approximately 32.9% of global CO₂ emissions and 8.7 tonnes per capita.
- **Saudi Arabia and Kuwait:** Reported per-capita CO₂ emissions exceeding 20 tonnes, with some values above 40 tonnes.
- **Top five emitters:** Their combined share is examined over time alongside emissions from the rest of the world.

The distinction between total and per-capita emissions is essential when comparing countries with different population sizes.

### Country-Level Temperature Changes

The notebook compares reported temperature changes between 1950 and 2024.

The largest increases identified in the analyzed data include:

| Country | Reported Temperature Change |
|---|---:|
| Uzbekistan | **+3.48°C** |
| Kazakhstan | **+3.29°C** |
| Kyrgyzstan | **+3.20°C** |

Five-year rolling averages are also used to visualize long-term patterns while reducing year-to-year fluctuations.

These comparisons depend on the temperature dataset's measurement definitions, geographic coverage, and selected reference years.

### Statistical Correlations

The analysis reports strong positive Pearson correlations between emissions and the dataset's mean temperature series.

| Variables | Pearson Correlation |
|---|---:|
| Global CO₂ emissions vs. mean temperature | **0.895** |
| Global GHG emissions vs. mean temperature | **0.889** |

Both relationships are positive and relatively strong within the examined time series.

However, correlations between variables that share long-term trends can be influenced by time dependence and non-stationarity.

**These results should not be interpreted as direct evidence of causation or as estimates of the independent effects of individual climate drivers.**

---

## Datasets

The project combines three datasets available on Kaggle.

| Dataset | Description |
|---|---|
| [Global Mean Temperature by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-mean-temperature-by-country-1950-2024) | Country-level mean surface temperature records |
| [Global CO₂ Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-co2-emissions-by-country-1950-2024) | CO₂ emissions, per-capita indicators, and emission sources |
| [Global GHG Emissions by Country (1950-2024)](https://www.kaggle.com/datasets/lucalullo/global-ghg-gas-emissions-by-country-1950-2024) | Greenhouse gas emissions by country |

The datasets are accessed through Kaggle. Their respective pages provide access information and applicable terms of use.

---

## Repository Structure

```text
Global-emissions-and-temperature-1950-2024/
├── README.md
└── global-emissions-and-temperature-1950-2024.ipynb
```

The Jupyter notebook contains the exploratory analysis, statistical comparisons, visualizations, and interpretation of the climate datasets.

---

## Getting Started

### Run on Kaggle

The original analysis was developed in Kaggle, where the notebook and its associated datasets are available.

**[Open the Kaggle Notebook](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)**

Running the notebook in its original Kaggle environment is the recommended approach.

### Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/lucalullo/Global-emissions-and-temperature-1950-2024.git
cd Global-emissions-and-temperature-1950-2024
```

**2. Install dependencies**

```bash
python -m pip install pandas numpy matplotlib seaborn plotly jupyter
```

**3. Download the datasets**

Download the three datasets listed in the [Datasets](#datasets) section.

**4. Launch Jupyter Notebook**

```bash
jupyter notebook global-emissions-and-temperature-1950-2024.ipynb
```

**5. Configure local data paths**

Make the downloaded datasets accessible to the notebook and update any Kaggle-specific file paths to match their local locations.

The notebook may require these path adjustments when executed outside Kaggle.

---

## Scope and Limitations

This project is intended as an exploratory analysis of historical climate indicators.

Several limitations should be considered:

- **Descriptive analysis:** The project does not provide causal attribution, predictive modeling, or climate forecasts.
- **Temporal correlations:** Strong correlations between long-term trends do not independently establish causation.
- **Temperature definitions:** Reported mean temperatures depend on the underlying dataset and should not automatically be interpreted as globally standardized temperature anomalies.
- **Geographic coverage:** Country-level comparisons depend on data availability, spatial definitions, and measurement consistency.
- **Reference years:** Temperature differences calculated from individual years may be influenced by short-term climate variability.
- **Emission indicators:** Total emissions and per-capita emissions represent different perspectives and should not be used interchangeably.
- **Historical coverage:** The analysis covers 1950-2024 and does not incorporate subsequent observations.

The findings should therefore be interpreted in the context of the datasets, assumptions, and exploratory methods used.

---

## Documentation

The primary documentation is contained in the Jupyter notebook, which includes the analysis workflow, visualizations, statistical comparisons, and interpretation of results.

- **[Jupyter Notebook](global-emissions-and-temperature-1950-2024.ipynb)**
- **[Kaggle Notebook](https://www.kaggle.com/code/lucalullo/global-emissions-and-temperature-1950-2024)**
- **[Kaggle Profile](https://www.kaggle.com/lucalullo)**

---

## Author

**Luca Lullo**

[GitHub](https://github.com/lucalullo) | [Kaggle](https://www.kaggle.com/lucalullo)
