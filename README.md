# Rain-Predictor

A machine learning project to predict rainfall likelihood using historical weather data.

## Tech Stack
- Python  
- scikit-learn  
- pandas, numpy  
- matplotlib, seaborn  

## Dataset
The dataset was sourced from [Weather Dataset (Kaggle)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package).  
It contains historical weather observations such as temperature, humidity, wind speed, and rainfall.

## Methodology
1. Data cleaning and preprocessing (handling missing values, encoding categorical features).  
2. Exploratory Data Analysis (EDA) to understand weather patterns.  
3. Built a classification model using scikit-learn.  
4. Evaluated model performance with accuracy and confusion matrix.  

## Results
- Built a rain prediction model that classifies whether it will rain tomorrow.  
- Highlighted the most influential features such as humidity, temperature, and pressure.  

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/rain-predictor.git
   cd rain-predictor

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Open and run the Jupyter/Colab notebook:
   ```bash
   jupyter notebook notebook.ipynb
