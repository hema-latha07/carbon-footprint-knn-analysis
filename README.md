This repository features a Carbon Footprint Analysis & Prediction project designed to analyze how daily habits and behavioral choices impact sustainable living. Using a primary dataset built entirely from scratch via crowdsourced survey responses, the project tracks key environmental indicators such as transit choices, home appliance usage, dietary habits, and consumer behaviors. 

The core of the project focuses on an end-to-end data pipeline and machine learning workflow:
Data Preprocessing: Standardized text inputs, handled missing values via mode imputation, and verified structural integrity using pandas.

Encoding: Transformed categorical lifestyle and behavioral attributes into numerical formats using scikit-learn's LabelEncoder.  

Predictive Modeling: Split the data into an 80/20 train-test ratio and built a K-Nearest Neighbors (KNN) classification model to analyze patterns in sustainable living. 

Optimization: Evaluated performance using a confusion matrix and executed an iterative optimization loop (testing $K$-values from 1 to 50) using matplotlib to pinpoint the most accurate neighbor configuration. 

🚀 How to Run

Clone this repository to your local system.
Install the required dependencies: pip install pandas scikit-learn matplotlib.
Open the Jupyter Notebook or run the Python script to execute the data pipeline and view the optimization plot.

Tech Stack: Python, pandas, scikit-learn, matplotlib.  
