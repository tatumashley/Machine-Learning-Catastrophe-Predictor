# CatastraSense - Natural Disaster Predictor 

## Description:
This project utilizes historical weather data, including temperature, precipitation, and disaster occurrences, to predict the likelihood of a natural disaster in Florida. The machine learning model, the DecisionTreeClassifier, is trained and tested on this dataset to make accurate predictions. Users can input one or two cities along with a date, and the model will forecast the probability of a natural disaster on that specific day and location in Florida. The application also visually compares temperature and precipitation between the chosen cities, along with offering insights through graphs based on past data. Finally, it displays past data and the trends involved in that.


## Instructions:

### Requirements:

- Jupyter Notebook 
- Python 3.7 or higher 
- Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Geopy, Folium 

### Data Downloading/SetUp:

If Performing Data Pre-processing Steps:
1. Download the “nrest_of_data.csv” file.
2. Download the “natural disaters.csv” file.

If Skipping Data Pre-processing Steps:
1. Download the “updated_data.csv” file.

* Notes the extra csv files ("merged_data.csv" and "modified_data.csv") are included just to show what they should look like meaning they are not necessary to run the code!

### Running the Code:

1. Open the Jupyter Notebook in a directory where you have write access (make sure the csv files are in the same directory as this).
2. Sequentially run each cell in the notebook. Pay attention to any cells that might require user input for predictions.
