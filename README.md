# Customer Service Metrics: A Comprehensive Analysis of Call Center Performance

## Overview

This project analyzes customer service metrics from call center data, focusing on improving call handling through insightful metrics and IVR improvements. The analysis includes visualizations and suggestions based on call transcript data, sentiment analysis, and agent performance.

## Files Included

1. **Skyhack_UA_(1&2).ipynb**: Contains the initial data analysis, metrics calculations, and IVR improvement suggestions.
2. **Skyhack_UA_(3).ipynb**: Contains further analysis, including graphs and additional insights.

## Setup Instructions

To run the notebooks, ensure you have Jupyter Notebook installed on your system. You can install it using Anaconda or pip. 

### Required Libraries

Make sure to install the following libraries if they are not already available:

```bash
pip install pandas matplotlib seaborn
```

## Running the Notebooks

2. **Set File Paths**: Open each notebook and ensure that the file paths to your data files are correct. Look for sections in the notebooks where files are being read (e.g., CSV files) and update the paths accordingly:
# Example path setting
   calls = pd.read_csv('path_to_your_calls_data.csv')
   sentiment_stats = pd.read_csv('path_to_your_sentiment_stats.csv')
   reasons = pd.read_csv('path_to_your_reasons_data.csv')
   customers = pd.read_csv('path_to_your_customers_data.csv')

### How to Run
Clone the Repository: First, clone the repository to your local machine or use Google Colab:


```git clone https://github.com/PratyushSoni/SKYHACK_United-Airlines```

### Upload Required Data Files: Upload the CSV files (calls.csv, customers.csv, reason.csv, sentiment_statistics.csv, and test.csv) to the notebook's working directory if you are using Google Colab or Jupyter Notebook.

### Install Required Libraries: In case you are running the notebook locally, install the required dependencies:

```pip install pandas scikit-learn nltk```
If you are using Google Colab, these libraries are pre-installed.

### Open the Notebook: Open the call_center_optimization.ipynb notebook and ensure the data files are correctly loaded into the environment.

### Run the Notebook: Execute each cell in sequence. The following tasks will be performed: 
  Data Preprocessing: Cleaning, merging, and preparing data.
  Feature Engineering: Extracting features like sentiment scores, call duration, and silence percentage.
  Model Training: Training a machine learning model (Random Forest Classifier) to predict the primary call reason.
  Predictions: Generating predictions for the test data.
  Save Predictions: Once predictions are made on the test set (test.csv), you can save the results in a new CSV file:


