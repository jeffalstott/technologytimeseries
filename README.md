# technologytimeseries

This is a aggregation of empirical data on numerous technologies' historical performances and prices, as reported in two published papers:

- J. D. Farmer and F. Lafond. "How predictable is technological progress?" Research Policy, Volume 45, Issue 3, Pages 647-665 (April 2016) [[journal](https://doi.org/10.1016/j.respol.2015.11.001), [arXiv](https://arxiv.org/abs/1502.05274)] (much of the data originates from the [Performance Curve Database](http://pcdb.santafe.edu/))

- C.L. Magee, S. Basnet, J.L. Funk and C.L. Benson. "Quantitative empirical trends in technical performance" Technological Forecasting and Social Change, Volume 104, Pages 237–246 (March 2016) [[journal](https://doi.org/10.1016/j.techfore.2015.12.011), [MIT DSpace](https://dspace.mit.edu/handle/1721.1/103015)]

This is data that I have aggregated and processed from data files that the authors shared with me. Academics, please cite those papers when using data originally published there.

The data should not be taken as perfect; there are undoubtedly measurement errors, reporting errors, conceptual errors and errors of ommission. 

[This Ipython Notebook](src/Original_Technology_Time_Series_Processing.ipynb) brings together the data from their original sources, adds some metadata, and visualizes the time series.

[data/time_series.csv](data/time_series.csv) is the aggregated data.
[data/time_series.csv](data/time_series_metadata.csv) is a table of metadata on each time series.

