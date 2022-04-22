# Data-mining
This repo will have uploaded and updated all the data files required for the assignments of the data mining course at the UOH in 2022.
The data sets in this repo aren't from my authorship or property, so this repo will be erased at the end of the course.

I might share this repo as it can help on charging the data at Google Colab in an easier way. If any problem with this implementation is recognized, please contact the author `Vicente-G` via pull-requesting.

For an easier use of these data files on Google Colab, please follow the next structure:
```py
from pandas import read_csv
repo = "https://raw.githubusercontent.com/Vicente-G/data-mining/main/"
RED_WINE_DATAFRAME = read_csv(repo + "red_wine.csv")
```
Running the last example the file `red_wine.csv` should be loaded in Google Colab as a `DataFrame` from `pandas` in the `RED_WINE_DATAFRAME` variable.
