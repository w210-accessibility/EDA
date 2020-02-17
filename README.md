# EDA
Scripts used for EDA of Street View images


## Extract and Plot Image Age

1. Run the `EDA_years.ipynb` notebook to extract the year each image was taken from the Google Street View metadata json files. 
2. Use the `years.csv` output from `EDA_years.ipynb` as input to `Image_Age.ipynb`, which will create a histogram of the year each image was taken as well as plot the image year on a map of Milwaukee to show if there's any clustering of newer or older images.