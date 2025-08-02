<h1 align="center"> Hi! I'm Linus Ghanadan 👋</h1>

I received a Bachelor’s degree in 2023 (B.S. in Environmental Economics from the University of Maryland) and a Master’s degree in 2024 (M.S. in Environmental Data Science from UC Santa Barbara), and during my studies, I worked on several fascinating data science projects!

Reach out to me on [LinkedIn](https://www.linkedin.com/in/linus-ghanadan/) if you would like to connect!

<h1 align="center"> Data Science Portfolio</h1>

## Master's Capstone Project

**Improving GHG Data Analysis Workflow for an Outdoor Apparel Company**

R | [Project Page (UCSB)](https://bren.ucsb.edu/projects/creating-reproducible-model-annual-emissions-outputs-sock-manufacturers-supply-chain) | [Project Page (GitHub)](https://github.com/carbonSOCKprint) | [Blog](https://linusghanadan.github.io/blog/2024-6-20-post/)

Collaborating with three classmates and the Sustainability Director at an outdoor apparel company, created a web application for GHG (Scope 1, 2, and 3) data tracking and interactive scenario analysis, replacing Excel-only workflow with one combining Excel and R-Shiny web application. Managed all data products on private code repositories, and created metadata and documentation for reproducibility. Final dashboard product provides the company with the ability to visualize their emissions and conduct scenario analysis based on adjustable input variables (e.g., can evaluate emissions under scenarios with differing fiber procurement levels).

## Statistics Final Project

**Time Series Analysis of Chesapeake Bay Pollution**

Python | [Repository](https://github.com/linusghanadan/chesapeake-bay-nutrient-pollution-python) | [Blog](https://linusghanadan.github.io/blog/2024-8-20-post/chesapeake-bay-python.html)

For self-guided final project in his statistics course, Linus conducted a time series analysis of nitrogen and phosphorus concentrations in Chesapeake Bay tidal regions, studying data from over 43,000 readings taken between 2010 and 2019.

Since 2010 marked the beginning of TMDL regulation applying to the Chesapeake Bay under the Clean Water Act, Linus was curious about what he could learn regarding the effectiveness of the TMDL regulation by looking at seasonal and non-seasonal trends in the data. 

Attempting to answer his question, Linus built STL decomposition models, which involved tuning season length based on autocorrelation of time lags. Based on selected season length, STL models use MLR to separate variation in the data into three distinct components: Seasonality, Trend (intra-seasonal variation), and Residual/Randomness (inter-seasonal variation). Using his STL models, Linus visualized these three model components, allowing him to identify early 2014 as a localized event with a spike in nitrogen that the model attributed to the Residual/Randomness component.

Moreover, from running regressions with the resulting model parameters, Linus came to the conclusion that the overall non-seasonal trend from 2010 to 2019 was slightly negative for both pollutants. He also found that phosphorus had very distinct seasonality, with seasonality explaining 87% of the variation in concentrations. For nitrogen, seasonality explained 73% of variation.

## Data Visualization Final Project

**Infographic on Anthropogenic Methane Emissions**

R | [Repository](https://github.com/linusghanadan/methane-infographic) | [Blog](https://linusghanadan.github.io/blog/2024-3-12-post/)

For self-guided final project in data visualization course, created an infographic on anthropogenic methane emissions using code that created three visualizations (treemap, scatterplot, and dodged column plot). Data came from the International Energy Agency and provided granularity for the country and sector of emissions.

## Econometrics Projects

**Econometric Analysis of 1998 Mexican Cash-Transfer Program**

R | [Repository](https://github.com/linusghanadan/cash-transfer-policy) | [Blog](https://linusghanadan.github.io/blog/2024-3-6-post/)

Compared pre-treatment characteristics in the treatment and control groups of the 1998 Prospera cash-transfer program. Estimated the Average Treatment Effect (ATE) of the program on a household’s value of owned animals with the First-Difference, Fixed-Effects, and Difference-in-Difference estimators.

**Econometric Analysis of Catch Shares Program**

R | [Repository](https://github.com/linusghanadan/catch-shares-policy) | [Blog](https://linusghanadan.github.io/blog/2024-3-11-post/)

Compared pre-treatment ecosystem characteristics in the treatment and control groups. Compared propensity scores (prior to matching) in the treatment and control groups. Estimated Average Treatment Effect on Treated (ATT) using nearest neighbor matching estimator. Estimated ATE using Weighted Least Squares (WLS) estimator.

## Machine Learning Projects

**Predictive Regression Models of Dissolved Inorganic Carbon**

Python | [Repository](https://github.com/linusghanadan/dic-ml-models) | [Blog](https://linusghanadan.github.io/blog/2024-4-3-post/dic-ml-models.html)

Employed data from a marine ecosystem research program to build three models (single decision tree, random forest, and stochastic gradient boosted trees) that predict dissolved inorganic carbon (DIC) based on other ocean chemistry features (e.g., sulfur trioxide concentration) that were also measured during water sampling. Compared root mean squared error (RMSE) among models and analyzed feature importances in the best performing model.

**Predictive Classification Models of Spotify Liked Songs**

R | [Repository](https://github.com/linusghanadan/ml-spotify-lab) | [Blog](https://linusghanadan.github.io/blog/2024-3-29-post/)

Built four different types of decision tree models that predict whether a given song was in my Spotify collection or in the collection my classmate Maxwell. Then, I compared performance across the four models. Specifically, I compared the performance of models built using a single decision tree, bagged decision trees, a random forest, and Stochastic Gradient Boosting (SGB).

**Cluster Analysis of Bio-Contaminating Algae**

R | [Repository](https://github.com/linusghanadan/ml-clustering-lab/tree/main) | [Blog](https://linusghanadan.github.io/blog/2024-4-1-post/)

Implemented K-means clustering algorithm with data on metal contents in two species of co-occurring algae to plot the Total Within Sum of Square (TWSS) for different numbers of clusters and determine the optimal number of clusters that indicate distinct types of bio-contaminating algae. In addition, calculated Euclidean distance matrix to build a hierarchical clustering model and inspect the resulting dendrogram for outlier points.

## Geospatial Analysis Projects

**Geospatial Analysis of Biodiversity Changes**

Python | [Repository](https://github.com/linusghanadan/phoenix_biodiversity) | [Blog](https://linusghanadan.github.io/blog/2023-12-13-post/phoenix_biodiversity.html)

Fetched items from Microsoft Planetary Computer (MPC) catalog based on search criteria, retrieving grid-cell data on 2017 and 2020 Biodiversity Intactness Index (BII) scores (0 to 1 biodiversity scores). Clipped raster of BII scores with polygon shapefile of Arizona subdivisions. For Phoenix’s subdivision, calculated percent of area where BII decreased from above 0.75 in 2017 to being below this threshold score in 2020. Created heatmap of 2020 BII scores across Phoenix’s subdivision, highlighting areas that decreased below the 0.75 BII threshold.

**Geospatial Analysis of Houston Power Crisis**

R | [Repository](https://github.com/linusghanadan/houston_power_crisis/tree/main) | [Blog](https://linusghanadan.github.io/blog/2024-1-20-post/)

Used data from NASA’s VIIRS instrument, OpenStreetMap, and the U.S. Census Bureau to conduct a spatial analysis of the 2021 Houston Power Crisis. To determine census tracts where residential blackouts occurred, created a blackout mask excluding non-residential areas (excluded highways and commercial properties based on data from OpenStreetMap) and performed spatial joins with census tract data. Created visualization showing census tracts where residential blackouts occurred. As a second component to the analysis, joined census tract data with data on median income to create heatmap where fill color was based on median income and outline color was based on whether the census tract had residential blackouts. Lastly, created double-sided histogram demonstrating the lack of a clear relationship, except for census tracts at the highest end of the income distribution.

## Systems Modeling Projects

**Dynamic Simulation of Forest Growth**

R | [Repository](https://github.com/linusghanadan/dynamic-simulation-forest-growth) | [Blog](https://linusghanadan.github.io/blog/2024-6-10-post/)

Used common scientific model that estimates forest size (measured in kilograms of carbon) and generated stochastic parameter sets for model inputs (exponential growth rate before canopy closure, linear growth rate after canopy closure, carrying capacity, and canopy closure threshold). Used an ordinary differential equations solver to run 300-year continuous dynamic simulations of forests. Conducted global sensitivity analysis to look at the impact of varying parameter values on maximum forest size.

**Global Sensitivity Analysis for an Atmospheric Conductance Model**

R | [Repository](https://github.com/linusghanadan/atmospheric-conductance-sobol) | [Blog](https://linusghanadan.github.io/blog/2024-6-7-post/)

Investigated an atmospheric conductance model based on vegetation height and windspeed, applying a variance-based sensitivity analysis by calculating Sobol indices. Interpreted takeaways of how variance in these model parameters informs climate science.



