# COVID-19 Data Analysis Dashboard

An Excel-based data analysis project that explores COVID-19 cases,
deaths, recoveries, active cases, recovery rates, case fatality rates,
and future case forecasts across Indian States and Union Territories.

## 📌 Project Overview

This project was created using **Microsoft Excel** to analyze a COVID-19
dataset covering the period **2020--2025**. The project uses Excel
data-analysis and visualization features such as:

-   Excel Tables
-   PivotTables
-   PivotCharts
-   Slicers / Filters
-   Interactive Dashboard
-   Forecasting

The goal is to transform raw COVID-19 data into meaningful summaries and
visualizations that make trends and comparisons easier to understand.

## 🎯 Objectives

-   Analyze COVID-19 cases across different States and Union
    Territories.
-   Compare new cases, deaths, recovered cases, and active cases.
-   Study recovery rate and case fatality rate trends.
-   Use PivotTables to summarize large amounts of data.
-   Create PivotCharts for visual analysis.
-   Develop an interactive COVID-19 dashboard.
-   Use historical data to create a simple forecasting model for future
    cases.

## 📊 Dataset

The main dataset is stored in the **`Data`** worksheet.

It contains **198 records** and the following 8 columns:

  -----------------------------------------------------------------------
  Column                              Description
  ----------------------------------- -----------------------------------
  `Year`                              Year of the COVID-19 observation

  `State/UT`                          Indian State or Union Territory

  `New COVID Cases`                   Number of new COVID-19 cases

  `Deaths`                            Recorded COVID-19 deaths

  `Recovered Cases`                   Recorded recovered cases

  `Active Cases at Year End`          Active cases remaining at the end
                                      of the year

  `Recovery Rate %`                   Recovery-rate value provided in the
                                      dataset

  `Case Fatality Rate %`              Case-fatality-rate value provided
                                      in the dataset
  -----------------------------------------------------------------------

### Data Coverage

The dataset covers **2020 to 2025** and contains observations for Indian
States and Union Territories.

## 📈 Key Analysis

-   **2021** has the highest recorded number of new COVID-19 cases in
    the dataset, with **34,265,213 cases**.
-   **2021** also has the highest recorded active cases at year end,
    with **30,350,527 cases**.
-   **2021** has the highest recorded death total in the dataset, with
    **2,071,089 deaths**.
-   **2022** has the highest recorded recovered-case total, with
    **4,043,534 recoveries**.
-   The recorded number of new cases falls sharply after 2022.
-   By 2025, the dataset records **6,495 new cases, 6,495 recovered
    cases, and 0 active cases**.

## 🗺️ State-wise Analysis

The project also compares COVID-19 cases across States and Union
Territories.

The top States/UTs by total new cases in the supplied dataset are:

    Rank State/UT           Total New Cases
  ------ ---------------- -----------------
       1 Maharashtra             10,190,569
       2 Kerala                   7,670,220
       3 Karnataka                5,002,787
       4 Tamil Nadu               4,459,633
       5 Uttar Pradesh            2,732,074
       6 West Bengal              2,671,381
       7 Delhi                    2,664,023
       8 Andhra Pradesh           2,587,635
       9 Odisha                   1,677,558
      10 Rajasthan                1,636,513

These comparisons help identify the States/UTs with larger recorded case
totals within the project dataset.

## 🔄 PivotTable Analysis

PivotTables were used to summarize the raw data and make comparisons
easier.

The project includes analysis of:

1.  **Year-wise New COVID Cases**
2.  **Year-wise Deaths**
3.  **Year-wise Recovery Rate**
4.  **State-wise Recovery Rate**
5.  **Active Cases at Year End**
6.  **Recovered Cases**
7.  **Case Fatality Rate**

## 📊 PivotCharts

The project contains multiple charts to visually represent the analysis:

### COVID Data Year Wise

Shows the distribution of new COVID-19 cases across States/UTs and
years.

### Year-wise Recovery Rate

Shows the change in the supplied recovery-rate values from 2020 to 2025.

### State-wise Recovery Rate

Compares recovery-rate values across different States and Union
Territories.

### Case Fatality Rate

Shows the change in the supplied case-fatality-rate values over the
years.

### Death Counts

Shows the year-wise death trend, including the large peak in 2021 and
the decline in later years.

### Year-wise COVID Pie/Doughnut Chart

Shows the relative distribution of new cases, active cases, recovered
cases, and deaths in the summarized data.

## 🖥️ Dashboard

The **Dashboard** worksheet combines the major visualizations into a
single view.

The dashboard provides:

-   Year-wise COVID case analysis
-   State-wise recovery-rate comparison
-   Case fatality rate trend
-   Recovery-rate trend
-   Death-count trend
-   Distribution of major COVID-19 measures
-   Interactive year and State/UT filters where available

The dashboard makes it easier to understand the overall situation
without manually reviewing every row of the dataset.


## 🔮 Forecasting Model

The project also contains a forecasting section for future new COVID-19
cases.

The forecast included in the workbook estimates:

    Year   Forecast   Lower Confidence Bound   Upper Confidence Bound
  ------ ---------- ------------------------ ------------------------
    2026        325                      163                      488
    2027         30                       15                       45

The forecast indicates a continued downward trend based on the
historical values in the dataset.

> **Note:** The forecast is a model-based estimate and should not be
> treated as an actual prediction of future COVID-19 cases. Real-world
> outbreaks can be affected by new variants, vaccination, public-health
> measures, testing, reporting practices, and many other factors.

## 📁 Workbook Structure

The Excel workbook contains the following main worksheets:

  Worksheet               Purpose
  ----------------------- -----------------------------------------
  `Data`                  Main COVID-19 dataset
  `Dashboard`             Final interactive dashboard
  `Pivot Chart`           PivotChart analysis
  `West Bengal Dataset`   State-specific supporting data
  `Forecast`              Forecasting model information
  `Forcast`               Forecast-related calculations
  `New Case Forcast`      New-case forecast and confidence bounds

## 🛠️ Tools Used

-   **Microsoft Excel**
-   Excel Tables
-   PivotTables
-   PivotCharts
-   Slicers / Filters
-   Excel Dashboard
-   Excel Forecasting / Trend Analysis

## 📌 Project Workflow

``` text
Raw COVID-19 Dataset
        ↓
Data Organization & Checking
        ↓
PivotTables
        ↓
PivotCharts
        ↓
Trend & State-wise Analysis
        ↓
Forecasting
        ↓
Interactive Dashboard
        ↓
Final Insights & Report
```

## ⚠️ Data Limitations

This project is intended as an **academic Excel data-analysis project**
and the results are based on the supplied workbook.

Some values in the dataset appear unusual when compared with typical
COVID-19 statistics. For example, the dataset contains a very large
death total in 2020 and zero recorded recoveries in 2020. Therefore:

-   The figures should be interpreted as values from the supplied
    dataset.
-   The dataset has not been independently verified against official
    public-health records.
-   Recovery Rate % and Case Fatality Rate % should not be interpreted
    by simply adding percentage values across States/UTs.
-   The forecasting results depend on the historical data provided in
    the workbook.
-   The project demonstrates data-analysis techniques rather than
    providing an official epidemiological assessment.

## 💡 Future Improvements

The project could be improved by:

-   Adding monthly or weekly COVID-19 data.
-   Adding vaccination and testing data.
-   Adding population-based rates such as cases per 100,000 people.
-   Adding hospitalization and ICU data.
-   Using verified official datasets.
-   Creating maps for state-wise analysis.
-   Moving the dashboard to Power BI for more advanced interactivity.
-   Comparing multiple forecasting models and evaluating their accuracy.

## 📷 Project Preview
<img width="1696" height="903" alt="Dashboard" src="https://github.com/user-attachments/assets/ca4f0e97-3be8-4d91-ae5b-2263822932b6" />
<img width="1546" height="740" alt="Forecasting Model Chart" src="https://github.com/user-attachments/assets/abf3cbb0-4f89-4f15-8b90-e0221849d87e" />
<img width="1077" height="807" alt="Covid Data 2020-2025 Chart" src="https://github.com/user-attachments/assets/7c2208f8-64f3-4313-a99c-48a726022363" />
<img width="1208" height="642" alt="West Bengal Graph" src="https://github.com/user-attachments/assets/404a2139-978e-41c9-9f6f-12173849e426" />


## 👨‍💻 Project Type

**Academic / College Excel Data Analysis Project**

This project demonstrates practical skills in:

-   Data Analysis
-   Microsoft Excel
-   PivotTables
-   PivotCharts
-   Data Visualization
-   Dashboard Creation
-   Basic Forecasting
-   Data Interpretation

## 📄 Files

The main project file is:

``` text
Covid Dataset.xlsx
```

## ⭐ Conclusion

This project demonstrates how Microsoft Excel can be used to transform a
raw COVID-19 dataset into meaningful information through PivotTables,
PivotCharts, forecasting, and dashboard visualization. The analysis
highlights major changes in cases, deaths, recoveries, and active cases
across years and States/UTs while providing an interactive way to
explore the data.
