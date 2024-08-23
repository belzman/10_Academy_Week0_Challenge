# Analysis of Solar Radiation Measurement Data for Sierra Leone, Benin, and Togo
This analysis focuses on the solar radiation measurement data collected from three countries: Sierra Leone, Benin, and Togo. The study was conducted separately for each country, and the data sets were compared to identify patterns, trends, and anomalies. The following methods and techniques were used to analyze the data:

## Exploratory Data Analysis (EDA):

Summary Statistics: Calculated mean, median, standard deviation, and other statistical measures for each numeric column to understand data distribution.
Data Quality Check:
Checked for missing values, outliers, or incorrect entries, especially in columns like Global Horizontal Irradiance (GHI), Direct Normal Irradiance (DNI), and Diffuse Horizontal Irradiance (DHI).
Specifically looked for outliers in sensor readings (ModA, ModB) and wind speed data (WS, WSgust).
Time Series Analysis:

Plotted line graphs or area plots of GHI, DNI, DHI, and ambient temperature (Tamb) over time to observe monthly patterns, daily trends, or anomalies, such as peaks in solar irradiance or temperature fluctuations.
Evaluated the impact of cleaning (using the 'Cleaning' column) on the sensor readings (ModA, ModB) over time.
Correlation Analysis:

Used heatmaps or pair plots to visualize the correlations between solar radiation components (GHI, DNI, DHI) and temperature measures (TModA, TModB).
Investigated the relationship between wind conditions (WS, WSgust, WD) and solar irradiance using scatter matrices.
Wind Analysis:

Utilized polar plots to identify trends and significant wind events by showing the distribution of wind speed and direction and how variable the wind direction tends to be.
Temperature Analysis:

Examined how relative humidity (RH) might influence temperature readings and solar radiation.
Visualization Techniques:

Histograms: Created histograms for variables like GHI, DNI, DHI, WS, and temperatures to visualize the frequency distribution of these variables.
Z-Score Analysis: Calculated Z-scores to flag data points significantly different from the mean.
Bubble Charts: Explored complex relationships between variables, such as GHI vs. Tamb vs. WS, with bubble size representing an additional variable like RH or Barometric Pressure (BP).
Data Cleaning:

Based on the initial analysis, cleaned the dataset by handling anomalies and missing values, especially in columns like 'Comments', which appeared entirely null.
Advanced Analysis Techniques:

Applied Seasonal Decomposition of Time Series to understand underlying patterns.
Used boxplots for outlier detection and pair plots for multivariate relationships.
Generated lag plots to identify autocorrelation in time series.
Created violin plots for distribution and density, and heatmaps with annotations for better data visualization.
Developed 3D surface plots and radial bar charts for wind direction analysis.
Implemented KDE (Kernel Density Estimation) plots for density estimation.
By employing these comprehensive analysis techniques, we could gain valuable insights into solar radiation patterns and their interactions with various environmental factors across Sierra Leone, Benin, and Togo.