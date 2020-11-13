# Historical Map Extraction
## What is this?

This notebook serves as a demonstration on the use of Machine Learning and Image Extraction algorithms to obtain useful information from an old map.  

Python libraries used in this project:

- [OpenCV](https://opencv.org/)
- [Sci-Kit Learn](https://scikit-learn.org/stable/modules/naive_bayes.html)
- [Geopandas](https://geopandas.org/)
- [Rasterio](https://rasterio.readthedocs.io/en/latest/)

## How to Access

The IPYNB file is better served using a running Jupyter Lab or Jupyter Notebook. [Click here](https://colab.research.google.com/github/danylaksono/historical-map-extraction/blob/main/Image%20Extraction%20on%20Historical%20Map.ipynb) to run this notebook in a Google Colab session.

## About the data

The "Jogjakarta en Omstreken" is a map from Colonial era of Indonesia in 1925. The map depict titular area of Yogyakarta, a center of cultural and historical importance in Indonesia. The map shows Town plan of Yogyakarta in Java, Indonesia, showing roads, boundaries, water features, vegetation, cultivation, swamps, buildings and built-up areasm and also relief which depicted by contours. The map is a collection of https://trove.nla.gov.au/m and could be accessed freely from [here](https://nla.gov.au/nla.obj-649375951/view)

## TODO

- Display the old map and resulting features using [Folium](https://python-visualization.github.io/folium/)
- Divide the map into tiles, so that processing is faster. Probably using [SuperMercado](https://github.com/mapbox/supermercado)
- Testing different Machine Learning Algorithm, such as [Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
- Experiments with [Cloud Optimised GeoTIFF (COG)](https://github.com/cogeotiff/rio-cogeo)
- Deep Learning using training [Model Transfer](https://link.springer.com/chapter/10.1007/978-3-319-66908-3_4)

## License

This works and its subsidiary are Licensed under [GNU General Public License v3.0](https://github.com/danylaksono/historical-map-extraction/blob/main/LICENSE)