# NOAA-Temperature-Data-Analysis
### Dataset Description:
- `temperature.csv`: Contains daily temperature readings from weather stations.
- `BinSize.csv`: Additional metadata related to binning data.

### Steps Performed:
1. Processed temperature data, removed leap days, and extracted year and day-of-year.
2. Identified record high and low temperatures from 2005-2014.
3. Compared 2015 temperature data to find record-breaking values.
4. Visualized trends with a line graph and shaded region.
5. Plotted 2015 temperature summary near Ann Arbor.
6. Normalized temperature data using `sklearn.preprocessing.StandardScaler`.
7. Loaded `BinSize.csv` to incorporate any additional relevant data.

### Libraries Used and Why:
- `pandas`: Used for efficient data processing and analysis.
- `matplotlib`, `seaborn`: Used for plotting data and creating visual representations.
- `numpy`: Used for handling numerical operations and defining tick marks in the plots.
- `sklearn.preprocessing`: Used for normalizing temperature values for better comparison.
