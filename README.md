<h1 align="center"> Hi! I'm Linus Ghanadan 👋</h1>

In June 2024, I graduated with a Master's in Environmental Data Science from the Bren School of Environmental Science & Management at UC Santa Barbara. I also hold a B.S. in Environmental Economics from the University of Maryland, which I received in May 2023.

<h1 align="center"> Data Science Portfolio</h1>

## Data Visualization

**Best of my Data Visualizations with R** | [Link to Blog](https://linusghanadan.github.io/blog/2024-7-24-post/)

**Best of my Data Visualizations with Python** | [Link to Blog](https://linusghanadan.github.io/blog/2024-7-23-post/)

## Final Project for Statistics Class

**Time Series Analysis of Nutrient Concentration in the Chesapeake Bay** | [Link to Repository (R Code)](https://github.com/linusghanadan/chesapeake-bay-nutrient-pollution) | [Link to Blog](https://linusghanadan.github.io/blog/2023-12-12-post/)

Proposed statistical question on how nutrient concentrations have changed since Clean Water Act protection measures (implemented in 2010) and found appropriate data for answering the question (used over 43,000 samples from the Bay’s tidal regions). Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct time series analysis of nitrogen and phosphorus concentrations (selected length of seasons based on autocorrelation). For each pollutant, visualized model parameters comparatively. In addition, ran regressions to determine the proportion of variation attributable to seasonality and the 95% confidence interval for change in trend component over the 10-year period.

## Master's Capstone Project

**Creating and Implementing an Analytical Workflow for an Outdoor Apparel Company’s Carbon Accounting and Sustainability Analysis** | [Link to GitHub Page](https://github.com/carbonSOCKprint) | [Link to Blog](https://linusghanadan.github.io/blog/2024-6-20-post/)

Worked with the Head of Sustainability at outdoor apparel company Darn Tough Vermont and three classmates to streamline the company's spreadsheet method for calculating and analyzing data on yearly Scope 1, 2, and 3 GHG emissions. Built interactive web-application dashboard that allows the company to visualize emissions and conduct scenario analysis based on adjustable input variables (e.g., can evaluate emissions under scenarios with differing fiber procurements).

## Projects for Geospatial Analysis Class

**Spatial Analysis of 2021 Houston Power Crisis** | [Link to Repository (R Code)](https://github.com/linusghanadan/houston_power_crisis/tree/main) | [Link to Blog](https://linusghanadan.github.io/blog/2024-1-20-post/)

Used data from NASA’s VIIRS instrument, OpenStreetMap, and the U.S. Census Bureau to conduct a spatial analysis of the 2021 Houston Power Crisis. To determine census tracts where residential blackouts occurred, created a blackout mask excluding non-residential areas (excluded highways and commercial properties based on data from OpenStreetMap) and performed spatial joins with census tract data. Created visualization showing census tracts where residential blackouts occurred. As a second component to the analysis, joined census tract data with data on median income to create heatmap where fill color was based on median income and outline color was based on whether the census tract had residential blackouts. Lastly, created double-sided histogram demonstrating the lack of a clear relationship, except for census tracts at the highest end of the income distribution.

**Spatial Analysis of Biodiversity Changes in Phoenix, AZ** | [Link to Repository (Python Code)](https://github.com/linusghanadan/phoenix_biodiversity) | [Link to Blog](https://linusghanadan.github.io/blog/2023-12-13-post/phoenix_biodiversity.html)

Fetched items from Microsoft Planetary Computer (MPC) catalog based on search criteria, retrieving grid-cell data on 2017 and 2020 Biodiversity Intactness Index (BII) scores, which rate an area of land’s biodiversity from 0 to 1. Clipped raster of BII scores with polygon shapefile of Arizona subdivisions. For Phoenix’s subdivision, calculated percent of area where BII decreased from above 0.75 in 2017 to being below this threshold score in 2020. Created heatmap visualizing 2020 BII scores across Phoenix’s subdivision, highlighting areas that decreased below the 0.75 BII threshold.

## Project for Policy Evaluation Class

**Impact Analysis of a 1998 Cash-Transfer Program in Rural Mexico** | [Link to Repository (R Code)](https://github.com/linusghanadan/cash-transfer-policy) | [Link to Blog](https://linusghanadan.github.io/blog/2024-3-6-post/)

Compared pre-treatment characteristics in the treatment and control groups of the 1998 Prospera cash-transfer program. Estimated the Average Treatment Effect (ATE) of the program on a household’s value of owned animals with the First-Difference, Fixed-Effects, and Difference-in-Difference estimators.

## Project for Modeling Class

**Dynamic Simulation of Forest Growth** | [Link to Repository (R Code)](https://github.com/linusghanadan/dynamic-simulation-forest-growth) | [Link to Blog](https://linusghanadan.github.io/blog/2024-6-10-post/)

Used common scientific model that estimates forest size (measured in kilograms of carbon) and generated stochastic parameter sets for model inputs (exponential growth rate before canopy closure, linear growth rate after canopy closure, carrying capacity, and canopy closure threshold). Used an ordinary differential equations solver to run 300-year continuous dynamic simulations of forests. Conducted global sensitivity analysis (ran 2,000 simulations and computed Sobol indices of input parameters) to look at impact of varying parameter values on maximum forest size.

## Projects for Machine Learning Class

**Cluster Analysis of Bio-Contaminating Algae in the Port Jackson Bay** | [Link to Repository (R Code)](https://github.com/linusghanadan/ml-clustering-lab/tree/main) | [Link to Blog)](https://linusghanadan.github.io/blog/2024-4-1-post/)

Implemented K-means clustering algorithm with data on metal contents (Cd, Cr, Cu, Mn, and Ni) in two species of co-occurring algae at 10 sample sites around Port Jackson Bay to plot the Total Within Sum of Square (TWSS) for different numbers of clusters and determine the optimal number of clusters that indicate distinct types of bio-contaminating algae. In addition, calculated Euclidean distance matrix to build hierarchical clustering model and inspect the resulting dendrogram for outlier points.

**Regression Models to predict Dissolved Inorganic Carbon in California Coastal Ecosystems** | [Link to Repository (Python Code)](https://github.com/linusghanadan/dic-ml-models) | [Link to Blog](https://linusghanadan.github.io/blog/2024-4-3-post/dic-ml-models.html)

Used data from a marine ecosystem research program to build three models (single decision tree, random forest, and stochastic gradient boosted trees) that predict dissolved inorganic carbon (DIC) based on other ocean chemistry features (e.g., sulfur trioxide concentration) that were also measured during water sampling. Developed visualizations comparing root mean squared error (RMSE) among the three models and analyzing feature importances in the best performing model.
