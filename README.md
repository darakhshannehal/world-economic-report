## World Economic Report (1960-2018)

A data storytelling project built in **R**, visualizing global economic development trends from 1960 to 2018, focusing on the relationship between GDP, population, energy consumption, and human development. It culminates in a one-page infographic-style report that visualizes global patterns and regional disparities.

### View [Full Analysis](https://darakhshannehal.quarto.pub/world-economic-report/)

### Report

Visualizations generated are integrated into a one-page infographic-style report using the patchwork package, highlighting trends in global growth and development.

![](infographic-report.png)

### R Packages Used:

-   **tidyverse**: Data wrangling, transformation, and visualization
-   **readxl**: Importing Excel files
-   **skimr**: Data summaries
-   **ggplot2** (via tidyverse): Visualizations
-   **viridis**: perceptually uniform and colorblind-friendly color palettes
-   **RColorBrewer**: Region-based color palettes for plots
-   **patchwork**: Combining multiple ggplot visualizations into a single layout

#### Data: World Bank indicators & Human Development Index (HDI) data