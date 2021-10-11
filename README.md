# Machine-Learning
Project 1:
Breast Cancer Detection:
Breast cancer is the second most common type of cancer in women. Early detection is essential in the survival for any form of cancer. A cell of the breast has various features like cell size, amount of nuclei, clump thickness etc. In this project, based on all these features, we will attempt to classify if the cell is cancerous or benign.
To train the model I have used the Wisconsin Breast Cancer dataset. The dataset had few missing values which were discarded. There were 699 records in total which is a fairly decent size of a dataset. I split the dataset into training and test dataset in the ratio 80:20. I used 2 different models- KNeighborsClassifier() and SVC() to see which model worked better for the given dataset. They provided a 0.94 and 0.95 accuracy respectively.
I also visualized the data in the form of scatter plot matrix to better understand the relationship between the various attributes.
Dataset link: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/breast-cancer-wisconsin.data

Project 2:
Gold Price Prediction:
Indian house households own over 11% of the total amount of gold worldwide. Gold prices fluctuate but on the long term is seen as a dependable investment. Forecasting and predicting the future price trends of gold and other precious metals will be beneficial for individual investors to hedge to decide when to buy or sell their gold. In this project, we predict future gold prices using Random Forest Regressor.
To train the model I have a gold prices dataset from kaggle. It consists of dates, silver, dollar, euro and gold price. The dataset did not have any missing values. Gold prices change on a daily basis and are also affected by major world events. This dataset consists over 2290 records. I split this dataset in an 80:20 ratio. The Random Forest Regressor model was fitted with the training dataset .
The values predicted by the model and the actual values were compared and the R squared error was 0.98.
Dataset link: https://www.kaggle.com/altruistdelhite04/gold-price-data
