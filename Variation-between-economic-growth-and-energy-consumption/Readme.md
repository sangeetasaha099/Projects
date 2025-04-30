# Project Overview

## Overview  
This study investigates the relationship between economic growth and energy consumption during periods of high and low GDP growth in seven Asian countries — **India**, **Indonesia**, **Thailand**, **Philippines**, **Pakistan**, **Japan**, and **Singapore** — spanning from **1966 to 2021**. By analysing both developing and developed nations, the research offers insights into how energy demand shifts across different stages of economic development. This understanding is critical for informing energy policies, economic planning, resource allocation, and advancing sustainability goals in the Asian region.

## Methodology  
- **Data Collection**:  
  - GDP growth data (adjusted for inflation in constant 2010 U.S. dollars) was sourced from *Macrotrends*.  
  - Energy consumption data (electricity, transport, heating — converted to terawatt-hours) was sourced from *OurWorldInData (World Bank)*.

- **Stationarity Tests**:  
  The Augmented Dickey-Fuller (ADF) test ensured stationarity in both GDP growth and energy consumption growth series to enable valid time-series modelling.

- **Persistence Behavior**:  
  The Ljung-Box test and PACF analysis were conducted to identify autocorrelation and persistence components in the energy consumption data (e.g., AR(2) for Thailand, AR(1) for Japan, none for others).

- **Model Specification**:  
  Energy consumption growth was modelled as a function of GDP growth, differentiating between high-growth and low-growth regimes using an indicator variable.

- **Regression Analysis**:  
  Ordinary Least Squares (OLS) regression was applied to estimate the effect of GDP growth on energy consumption during both growth regimes. Residual diagnostics (Ljung-Box test) ensured model adequacy and white-noise errors.

- **Significance Testing**:  
  Hypothesis tests determined whether GDP growth during high or low periods had a statistically significant impact on energy consumption growth.

## Key Findings  
- **Thailand**: High GDP growth significantly increases energy consumption growth.  
- **India**: Low GDP growth and its intercept significantly affect energy consumption growth, even in sluggish economic periods.  
- **Philippines**: Energy consumption growth is significantly influenced by GDP growth during low-growth periods.  
- **Pakistan**: Both low GDP growth and fixed factors (intercept during high growth) significantly impact energy demand.  
- **Japan & Singapore**: Energy demand is influenced by fixed factors during low growth, and in Japan, high GDP growth is also a significant driver.  
- **Indonesia**: No statistically significant relationship between GDP growth and energy consumption was detected.

## Conclusion  
Overall, the study confirms a general positive association between GDP growth and energy consumption, although the strength and nature of this relationship vary across countries and growth regimes. High GDP growth tends to amplify energy demand, particularly in Thailand and Japan, while even during low-growth periods, countries like India and the Philippines show significant energy consumption dynamics driven by other factors.

These findings emphasise the need for nuanced, country-specific energy policies that consider economic conditions. Policymakers can use these insights to balance economic growth aspirations with energy sustainability and environmental objectives, especially in rapidly developing regions of Asia.
