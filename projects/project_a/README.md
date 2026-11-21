# Profitable App Profiles for the App Store and Google Play Markets

Mobile apps that are free to download often earn their revenue through in-app ads, which means the number of users is what matters most. Choosing the wrong kind of app can waste months of development time.

A company that builds free Android and iOS apps wants to make data-driven decisions about which apps to build next. Its strategy is to release a minimal Android version first, develop it further if users respond well, and build an iOS version only if the app is profitable after six months. We therefore need to find an app profile that attracts many users on **both** Google Play and the App Store.

For this analysis we clean two existing data sets (removing wrong entries, duplicates, non-English apps and paid apps) and compare:

* Which app genres are the most common in each market?
* Which app genres have the most users (installs on Google Play, user ratings on the App Store)?
* Which genres are only popular because of a few giant apps, and which still leave room for new apps?

The analysis suggests that taking a popular book and turning it into an app with extra features (daily quotes, audio version, quizzes, discussion forum) could be profitable on both platforms.

## Data Files

This project uses the following data files:

* `googleplaystore.csv`: Google Play data on about 10,000 Android apps ([Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps))
* `AppleStore.csv`: App Store data on about 7,000 iOS apps ([Kaggle](https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps))

## Instructions

1. Download or clone this repository.
2. Ensure that the data files are located in the `Data/` directory.
3. Open the Jupyter Notebook `Guided Project_Profitable App Profiles for the App Store and Google Play Markets.ipynb` and run the cells to reproduce the analysis.

## Project Notebook

You can also directly view or run the analysis in the [Jupyter Notebook](http://localhost:8888/notebooks/Documents/Weiterbildungen/Dataquest/python%20course/Guided%20Project_Profitable%20App%20Profiles%20for%20the%20App%20Store%20and%20Google%20Play%20Markets.ipynb).
