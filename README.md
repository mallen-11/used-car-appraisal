# Machine Learning: A New Used Car Salesman

An article for this repo can be found at this link https://www.linkedin.com/pulse/machine-learning-new-used-car-salesman-morgan-allen/?published=t.


This repository contains all of the steps in the analysis and model building for a used car price predictor. This includes a folder containing all the data, a notebook where all the data was cleaned and analyzed, an article, and a presentation. Below, I will go into what you can expect from each of these.

### Data

 The data folder contains a link to the original website containing the data. Named `used_cars_data.csv` it contains used car data from the United States from the years 1981-2021. This data set is very large and cannot be loaded by itself. There are some smaller chunks of the data for analysis here as well.
 
https://www.kaggle.com/ananaymital/us-used-cars-dataset


### Notebooks

Our notebook shows all the code used to clean the data as well as some initial analysis to understand which columns we felt were worthy of further evaluation. We were able to load the data into chunks and clean it and drop all of the null values. We then ran the data through a GridSearch Algorithm as well as an XGBoost model to find the feature importances. With this, we were able to determine which columns were the most important in predicting the car price. We then ran these columns through a XGBoost model as well as a K-Nearest Neighbors model. The predictions were ensembled togther. We then made a input function to get user input and predict the price of their car.

Also in this folder is a link to a tableau dashboard that goes with the price predictor.

### Article

This folder contains an article on Linkedin about our entire analysis. As well as another article just on the Tableau Dashboard.

### Presentation

This folder contains a presentation over the same material the article contains. The presentation is actually a pitch deck for a company that uses the Tableau Dashboard and the price predictor.


This analysis is done by Morgan Allen, Nick Phan, Stella Cunningham, and Woo Seok Kim.

