This is the repository for the thesis "A Comparative Analysis of Machine Learning Algorithms for the Purpose of Predicting Norwegian Air Passenger Traffic" by Aleksander Stanulov.

"Air2009-2019_Sample.csv" is sample data from the real dataset that has 744 rows corresponding to a month of data for January 2009. This is not the data used for the ML models, the actual dataset contains 96186 rows spanning from 2009 to 2019. The actual dataset could not be shared because of it's sensitive nature. 
Special thanks to Avinor for the passenger data.

The other 4 files are the .ipynb (jupyter notebook) Python code files containing the code that was used for the data cleaning, preprocessing, ML model training and evaluation.
"DataPreprocessing.ipynb" contains the code that was used for the preprocessing of the data, and explains how the dataset is created. Note that considering that the raw data was yearly, 11 csv's for the passenger data and 11 csv's for the weather data, many of the code blocks were executed once for each yearly csv. Furthermore some preprocessing steps such as dataset splitting, normalization and reshaping are within each of the ML model .ipynb files.
"LSTM_Model.ipynb", "SVRM_Model.ipynb", and "DT_Model.ipynb" each correspond to the ML algorithm that has been trained, tested and evaluated on the same dataset.
