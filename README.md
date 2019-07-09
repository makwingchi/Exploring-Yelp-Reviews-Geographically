# Exploring Yelp Reviews

### Description
In this analysis, I explore the restaurant review data available through the [Yelp Dataset Challenge](https://www.yelp.com/dataset/challenge). The city I choose is Charlotte, NC.

The notebook is broken into two parts:

**Part 1: testing how well sentiment analysis works**

Because Yelp reviews include the number of stars given by the user, the Yelp data set provides a unique opportunity to test how well our sentiment analysis works by comparing the number of stars to the polarity of reviews.

**Part 2: analyzing correlations between restaurant reviews and census data**

I explore geographic trends in the restaurant reviews, comparing our sentiment analysis results with user stars geographically. I also overlay review stars on maps of household income (using census data).

### Required Libraries
- `pandas`
- `numpy`
- `geopandas`
- `nltk`
- `textblob`
- `matplotlib`
- `seaborn`
- `census_area`
- `shapely`
- `cartopy`

### Result
[This Jupyter notebook](https://github.com/makwingchi/Exploring-Yelp-Reviews-Geographically/blob/master/notebook.ipynb) contains the detail of this analysis.
