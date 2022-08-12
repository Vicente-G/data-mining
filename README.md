# Data-mining
This repo will have uploaded and updated all the data files required for the assignments of the data mining course at the UOH in 2022.
These data sets aren't from my authorship or property, but they are open source, I found the datasets on: [UCI ML Repository](http://archive.ics.uci.edu/ml/index.php), [Kaggle](https://kaggle.com), and more.

I might share this repo as it can help on charging the data at Google Colab in an easier way. If any problem with this implementation is recognized, please contact the author `Vicente-G` via pull-request/issues.

For an easier use of these data files on Google Colab, please follow the next structure:
```py
from pandas import read_csv
repo = "https://raw.githubusercontent.com/Vicente-G/data-mining/main/"
RED_WINE_DATAFRAME = read_csv(repo + "red_wine.csv")
```
By running the last example, the file `red_wine.csv` should be loaded in Google Colab as a `DataFrame` from `pandas` in the `RED_WINE_DATAFRAME` variable. If an official repo for the course is created I'll put down this one as well as I wouldn't need this anymore.
