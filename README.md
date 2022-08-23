# US-Housing-Factors
Predicting the impact of different social and economic factors on US Housing Prices


I've organised the analysis is 3 different notebooks:

1.  [Data Gathering](https://github.com/hitesh-pathak/US-Housing-Factors/blob/main/data_gathering.ipynb): This  notebook involves ingesting data into pandas from online publically available datasets, the data is cleaned and parsed to a proper form. Several different sources of data are employed in this analysis. Here I have combined several sources in to combined dataframes that are used in all other notebooks for analysis. Combined datasets are also saved in [data](https://github.com/hitesh-pathak/US-Housing-Factors/tree/main/data) directory, from where they are imported in the other notebooks.

2. [EDA](https://github.com/hitesh-pathak/US-Housing-Factors/blob/main/EDA.ipynb): Exploratory data analysis, mainly plots expressing relationship between various features.

3. [Model Building](https://github.com/hitesh-pathak/US-Housing-Factors/blob/main/Model_building.ipynb): Here, I've trained and evaluated Linear Regressor on data and documented the __results__. This model is used to understand the affect of different factors on US Single Household Price. Here I've used the [S&P/Case-Shiller U.S. National Home Price Index](https://fred.stlouisfed.org/series/CSUSHPISA) as a proxy for Home prices.

You can simply browse throgh the notebook, by clicking the html files or by clicking the ipynb ones (that will open them in github)
S&P/Case-Shiller Home Price Indices track changes in single-family residential home prices across US. These indices are based on sales pair that have undergone at least two arm's length transactions, which is to say that the repeat-sales method is used. This is to eliminate the problem of accounting for price differences in homes with varying characteristics. Therefore, it can be said that these indices measure change in single household prices over time given a constant level of quality. For this reason I've not used any quality determining characteristics of households like No. of Bedrooms, Bathrooms, Furnishing etcetera. 


You can simply browse throgh the notebooks, by clicking the __.html__ files or by clicking the ipynb ones (that will open them in github). Or you can run the notebooks on your system.

### How to browse:

1. Just Click the file you want to explore:
- [Data Gathering](https://raw.githack.com/hitesh-pathak/US-Housing-Factors/main/data_gathering.html)
- [EDA](https://raw.githack.com/hitesh-pathak/US-Housing-Factors/main/EDA.html)
- [Model Building](https://raw.githack.com/hitesh-pathak/US-Housing-Factors/main/Model_building.html)

_Powererd by_ [raw.githack.com](raw.githack.com)

### How to run:

1. Clone the repository or [download the zip file](https://github.com/hitesh-pathak/US-Housing-Factors/archive/refs/heads/main.zip).
2. Extract the .zip  file to an empty directory.
3. Use jupyter-notebook or jupyter-lab to open .ipynb files.
