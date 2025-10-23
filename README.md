# Inequality and Shared Prosperity Across Countries

## Overview

This project analyzes global inequality using welfare share by decile data from the World Bank’s Poverty and Inequality Platform (PIP) using 2021 PPP terms.

## Data

Data source:

```
https://api.worldbank.org/pip/v1/pip?country=all&year=all&povline=3&ppp_version=2021&format=csv&fill_gaps=false
```

## Key Findings

* Developed countries mainly use income-based welfare measures, while developing countries use consumption-based ones.
* Data availability declines after 2021, leading to underrepresentation in Africa and some developed countries.
* The richest 10% hold between 20–40% of total welfare, while the poorest 10% receive less than 5%.
* Indonesia performs relatively well among countries with populations above 50 million.
* Nordic countries exhibit lower inequality, while Colombia and the United States show higher inequality levels.

## Caveats and Future Work

* Limited recent data (2022–2024) reduce sample coverage.
* Welfare data based on income and consumption may underestimate wealth inequality.
* Future work should include Gini coefficients or wealth-based indicators, incorporating time series and regional analysis.
