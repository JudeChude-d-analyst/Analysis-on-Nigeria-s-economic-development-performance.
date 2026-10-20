# An analysis on Nigeria's economic & development performance over a 25 year period (2000-2025)

---

## Project Overview
This project analyses Nigeria's economic and development performance over a 25 year period from 2000 to 2025. The analysis strictly uses data from the World Bank Development Indicators (WDI), selecting 15 major indicators across economic output, foreign investment, infrastructure, and human development. Nigeria is benchmarked against five peer countries: Egypt, Ghana, India, Kenya, and South Africa.

The primary goal is to evaluate whether headline macroeconomic expansion translates into real living standard improvement for citizens. 

---

## Tools Used

* **MYSQL:** Used  for structural queries, and relational data architecture.
* **Microsoft Excel:** Used for data cleaning, indicator calculation, and preliminary statistical analysis.
* **Microsoft Power BI:** Used for data transformation in Power Query and building the interactive analytical dashbaord.

---

## Data Cleaning & Preparation Methodology

1. **Structuring and Reshaping:**
* The raw World Bank WDI dataset waas imported and structured for analysis. Yearly colimns spanning 2000 to 2025 were unpivoted into a single column and filtered strictly to the selected core indicators across Nigeria and the five peer nations (Egypt, Ghana, India, Kenya, and South Africa).

2. **Missing Data & Quality Assessment:**
* Across the selected series, appproximately 105 blank cells were identified and categorized into two distinct causes:

* **Around 78 blank cells** came from missing data from Nigeria's import of goods and services, export of goods and services, and trade across the 25 year period. These were left blank to avoid errors in subsequent computations, and a dedicated sheet was created in the workbook as verifiable proof of these external omissions.



* **The remaining 27 blanks cells** were as a result of most peer countries' official indicators records only extending to 2024, with 2025 values yet to be published by the World Bank at the time of the analysis.

---
## Dashboard Architecture & Visual Analysis.

The Power BI dashboard is organized into three sequential analytical slides, progressing from high-level national indicators down to comparative human welfare outcomes:

### 1. Macroeconomic Overview & Core Indicators (2000-2025)

![Image1].jpg)

* **Visual Structure:**
Top level KPI cards displaying headline metrics (GDP at $291B, Inflation at 23.01%, FDI at 1.38% of GDP, Electricity Access at 62.5%, Internet Usage at 41.2%, Life Expectancy at 54.6 years), alongside a dual-axis line chart tracking Real GDP Growth (%) vs. Inflation (Consumer Prices, annual %).
* From 2000 to 2014, real GDP growth actively kept pace with inflation, helping maintain purchasing power. However, from 2019 to 2025, inflation accelerated sharply while GDP growth slowed down, severely squeezing household purchasing power.

---

### 2. Infrastructure Decoupling: Electricity Access vs. Internet Adoption

![Image2.jpg])

* **Visual Structure:** A comparative time-series chart tracking Access to Electricity (% of population) alongside Individuals using the Internet (% of population).

* **Key Insight:** Internet access grew rapidly from near zero to over 40%, while electricity acccess expanded by only around 17% (reaching 62.5%). Digital telecommniation leapfrogged the national grid, powered largely by off-grid private alternatives such as generators and solar setups.

---

### 3. Regional Benchmark: The Growth-Welfare Paradox

![Image3.jpg])

* Multi-country comparative panels benchmarking Nigeria against Egypt, Ghana, India, Kenya, and South Africa across aggregate GDP (logarithmic scale) and average life expectancy, paired with an interactive 2000-2025 timeline slicer.

* **Key Insight** Nigeria maintains the second highest aggregate GDP among peer countries (surpassed only by India), yet consistently ranks at the very bottom in life expectancy (~54.6 years), demonstrating that top line monetary output has not translated into proportional improvements in healthcare and everyday living conditions.

---

## Strategic Recommendations

1. **Target Primary Healthcare Delivery:** Channel dedicated public funding directly into community primary healthcare centers, subsidizing maternal delivery services and clean drinking water access to reduce the high mortality rates dragging down national longevity.
2. **Focus on Employment Quality:** Move policy focus beyond headline unemployemnt numbers toward job formalization and productivity, providing structured support that helps informal workers transition into stable, productive jobs and reduces underemployment.
3. **Expand Domestic Production & Processing:** Direct deliberate capital into domestic manufacturing and local processing so the country produces what it consumes, shielding domestic market prices from foreign exchange shortages and imported inflation.
4. **Equip the Growing Workforce:** Invest in equipping the existing labour force with industrial tools and technical capabilities, channeling everyday survival hustle into scalable, high value domestic production.

---

Economic growth means nothing if it doesn't translate into better living conditions for ordinary citizens. Moving forward requires addressing foundational utility bottlenecks like electricity, producing what we consume, and backing our people's hustle with real industrial capacity because until output touches evryday lives, the numbers don't count!
