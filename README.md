<h1 align="center"> Hi! I'm Linus Ghanadan 👋</h1>

I recently received a Bachelor’s degree in 2023 (B.S. in Environmental Economics from the University of Maryland) and a Master’s degree in 2024 (M.S. in Environmental Data Science from the Bren School at UC Santa Barbara). Moving forward, I am very interested in using analytics to help with Earth’s carbon and biodiversity crises.

<h1 align="center"> Data Science Portfolio</h1>

## Data Visualization Highlights

Python | [Blog](https://linusghanadan.github.io/blog/2024-7-23-post/)

R | [Blog](https://linusghanadan.github.io/blog/2024-7-24-post/)

## Statistics Final Project

**Time Series Analysis of Nutrient Concentration in the Chesapeake Bay**

Python | [Repository](https://github.com/linusghanadan/chesapeake-bay-nutrient-pollution-python) | [Blog](https://linusghanadan.github.io/blog/2024-8-20-post/chesapeake-bay-python.html)

Proposed statistical question on possible underlying linear trends in average nitrogen and phosphorus concentrations across the Chesapeake Bay since 2010 (when new Clean Water Act regulations were implemented for the Bay) and found appropriate data for answering the question (over 43,000 samples from the Bay’s tidal regions). Constructed two Seasonal-Trend using LOESS (STL) decomposition models to conduct time series analysis of nitrogen and phosphorus concentrations (selected length of seasons based on autocorrelation). For each pollutant, visualized model parameters comparatively and ran regressions of parameters (to determine proportion of variation attributable to seasonality and 95% confidence interval for 10-year linear trend component).

## Master's Capstone Project

**Improving GHG Data Analysis Workflow for an Outdoor Apparel Company**

R | [GitHub Page](https://github.com/carbonSOCKprint) | [Blog](https://linusghanadan.github.io/blog/2024-6-20-post/)

Worked with three classmates to streamline GHG data analysis workflow for outdoor apparel company. Created data entry template (using Microsoft Excel) and interactive dashboard (using R and GitHub) for the company to calculate their emissions, visualize historical data, and use interactive components to analyze future scenarios (e.g., could look at impact of using recycled wool). Individually took the lead with the scenario analysis components of interactive dashboard, and this involved coming up with ideas for how to go about analyzing scenarios, presenting ideas to the company’s Global Director for Environmental and Social Responsibility, and using the Global Director’s feedback to write code for the interactive dashboard. Used improved workflow to analyze the company’s GHG data from 2019 and 2020 and recommend solutions for meeting the company’s 2030 emissions reduction target.

## Environmental Modeling Project

**Dynamic Simulation of Forest Growth**

R | [Repository](https://github.com/linusghanadan/dynamic-simulation-forest-growth) | [Blog](https://linusghanadan.github.io/blog/2024-6-10-post/)

Used common scientific model that estimates forest size (measured in kilograms of carbon) and generated stochastic parameter sets for model inputs (exponential growth rate before canopy closure, linear growth rate after canopy closure, carrying capacity, and canopy closure threshold). Used an ordinary differential equations solver to run 300-year continuous dynamic simulations of forests. Conducted global sensitivity analysis (ran 2,000 simulations and computed Sobol indices of input parameters) to look at impact of varying parameter values on maximum forest size.

## Geospatial Analysis Projects

**Tracking Biodiversity Changes in Phoenix**

Python | [Repository](https://github.com/linusghanadan/phoenix_biodiversity) | [Blog](https://linusghanadan.github.io/blog/2023-12-13-post/phoenix_biodiversity.html)

Fetched items from Microsoft Planetary Computer (MPC) catalog based on search criteria, retrieving grid-cell data on 2017 and 2020 Biodiversity Intactness Index (BII) scores, which rate an area of land’s biodiversity from 0 to 1. Clipped raster of BII scores with polygon shapefile of Arizona subdivisions. For Phoenix’s subdivision, calculated percent of area where BII decreased from above 0.75 in 2017 to being below this threshold score in 2020. Created heatmap visualizing 2020 BII scores across Phoenix’s subdivision, highlighting areas that decreased below the 0.75 BII threshold.

**Using NASA Data to analyze Residential Blackouts from Houston Power Crisis**

R | [Repository](https://github.com/linusghanadan/houston_power_crisis/tree/main) | [Blog](https://linusghanadan.github.io/blog/2024-1-20-post/)

Used data from NASA’s VIIRS instrument, OpenStreetMap, and the U.S. Census Bureau to conduct a spatial analysis of the 2021 Houston Power Crisis. To determine census tracts where residential blackouts occurred, created a blackout mask excluding non-residential areas (excluded highways and commercial properties based on data from OpenStreetMap) and performed spatial joins with census tract data. Created visualization showing census tracts where residential blackouts occurred. As a second component to the analysis, joined census tract data with data on median income to create heatmap where fill color was based on median income and outline color was based on whether the census tract had residential blackouts. Lastly, created double-sided histogram demonstrating the lack of a clear relationship, except for census tracts at the highest end of the income distribution.

## Machine Learning Projects

**Regression Models to predict Dissolved Inorganic Carbon in California Coastal Ecosystems**

Python | [Repository](https://github.com/linusghanadan/dic-ml-models) | [Blog](https://linusghanadan.github.io/blog/2024-4-3-post/dic-ml-models.html)

Used data from a marine ecosystem research program to build three models (single decision tree, random forest, and stochastic gradient boosted trees) that predict dissolved inorganic carbon (DIC) based on other ocean chemistry features (e.g., sulfur trioxide concentration) that were also measured during water sampling. Developed visualizations comparing root mean squared error (RMSE) among the three models and analyzing feature importances in the best performing model.

**Cluster Analysis of Bio-Contaminating Algae in the Port Jackson Bay**

R | [Repository](https://github.com/linusghanadan/ml-clustering-lab/tree/main) | [Blog)](https://linusghanadan.github.io/blog/2024-4-1-post/)

Implemented K-means clustering algorithm with data on metal contents (Cd, Cr, Cu, Mn, and Ni) in two species of co-occurring algae at 10 sample sites around Port Jackson Bay to plot the Total Within Sum of Square (TWSS) for different numbers of clusters and determine the optimal number of clusters that indicate distinct types of bio-contaminating algae. In addition, calculated Euclidean distance matrix to build hierarchical clustering model and inspect the resulting dendrogram for outlier points.
