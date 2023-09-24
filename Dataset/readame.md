
# Dataset
This folder contains the dataset used for training and evaluating the machine & deep learning models in your project. 

# Dataset Description

* The Berkeley Earth Surface Temperature Study combines 1.6 billion temperature reports from 16 pre-existing archives. It is nicely packaged and allows for slicing into interesting subsets (for example by country or By state). They publish the source data and the code for the transformations they applied. They also use methods that allow weather observations from shorter time series to be included, meaning fewer observations need to be thrown away.

In this dataset, several files have been included:

Global Land and Ocean-and-Land Temperatures **(GlobalTemperatures.csv)**:

* **Date:** starts in 1750 for average land temperature and 1850 for max and min land temperatures and global ocean and land temperatures
* **LandAverageTemperature:** global average land temperature in celsius
* **LandAverageTemperatureUncertainty:** the 95% confidence interval around the average
* **LandMaxTemperature:** global average maximum land temperature in celsius
* **LandMaxTemperatureUncertainty:** the 95% confidence interval around the maximum land temperature
* **LandMinTemperature:** global average minimum land temperature in celsius
* **LandMinTemperatureUncertainty:** the 95% confidence interval around the minimum land temperature
* **LandAndOceanAverageTemperature:** global average land and ocean temperature in celsius
* **LandAndOceanAverageTemperatureUncertainty:** the 95% confidence interval around the global average land and ocean temperature

Other files include:

1. Global Average Land Temperature by Country (**GlobalLandTemperaturesByCountry.csv**)
1. Global Average Land Temperature by State (**GlobalLandTemperaturesByState.csv**)
1. Global Land Temperatures By Major City (**GlobalLandTemperaturesByMajorCity.csv**)
1. Global Land Temperatures By City (**GlobalLandTemperaturesByCity.csv**)


Finally, Make sure to Download the full dataset from the attached Source and place the rest of the CSV files within the "Dataset" Folder, as not the all files was apploaded to this repo.

Dataset source: [Climate Change: Earth Surface Temperature Data](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
