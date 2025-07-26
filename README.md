## Category: 
Bayesian Decision Trees
## Method: 
Bayesian Additive Regression Trees (BART)
## Topic: 
Planning & Operation Insights for Docked Bike-Sharing Systems - Usage Pattern Analysis
## Research Design: 
Current research primarily focuses on identifying the spatiotemporal patterns of bike-sharing usage, particularly rental patterns and their influencing factors. However, there is a limited understanding of the spatial and temporal imbalances between bike rentals and returns and the key factors contributing to these imbalances. To address this gap, we applied a spatiotemporal data analysis to characterize rental-return imbalances across different time periods and bike stations. Subsequently, with a respective focus on general and substantial rental-return imbalances, we used a Bayesian Additive Regression Trees (BART) model to reveal the relationships between different imbalances and their influencing factors, while also measuring and quantifying the uncertainty of these relationships. Our analysis used 2022 Capital Bikeshare trip data from 356 bike stations in Washington, D.C., incorporating socio-demographic, built environment, temporal, and weather variables to examine the spatiotemporal heterogeneity of rental-return imbalances in bike-sharing systems. Figure shown below presents the research design.

<table style="margin-left: auto; margin-right: auto;">
  <tr style="text-align: center;">
    <td><img src="Figures/Paper 2.png"></td>
  </tr>
 </table>

## Key Findings: 
From the perspective of docked bike-sharing operators, Bayesian decision trees were used to analyze station-level imbalances in Washington, D.C. Imbalances were classified as general or substantial (over 10 bikes/hour). General imbalances showed spatial clustering but lacked clear temporal trends. In contrast, substantial imbalances followed consistent daily patterns, specifically, rentals peaked from 5-8 pm and lagged returns from 7–10 am, which reflected commuter behavior. These imbalances were more likely in areas with high population density, greater white population shares, diverse land uses, and poor bike connectivity. Station-level attributes (e.g., rentals, returns, trip duration, and distance) had strong nonlinear threshold effects. These insights derived from this AI-assisted transport planning framework inform targeted planning and operational strategies to improve docked systems’ rental-return balance and operational performance.
## Paper available at https://doi.org/10.1016/j.cities.2025.105967
