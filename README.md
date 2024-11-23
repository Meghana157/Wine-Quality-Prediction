# Wine-Quality-Prediction
## Project Objective
The primary goal of this project is to build a machine learning model that predicts the quality of wine based on its physicochemical properties. By analyzing key features such as acidity, sugar levels, and alcohol content, this project aims to assist wineries and wine enthusiasts in assessing wine quality effectively.
## Project Overview
Wine quality is a critical factor in the wine industry, often assessed through sensory analysis by experts. However, leveraging machine learning allows for objective and automated quality assessment. This project uses a dataset containing physicochemical properties and quality ratings of wines to develop a predictive model.

The solution involves:

- Data Preprocessing: Cleaning and preparing the data for analysis.
- Label Binarization: Converting the target variable (Quality) from a scale of 1 to 10 into binary values:
Values >7 are categorized as 1 (high quality).
Other values are categorized as 0 (not high quality).
- Exploratory Data Analysis (EDA): Identifying key patterns and relationships in the dataset.
- Model Training: Building machine learning models to predict wine quality.
- Model Evaluation: Assessing the model’s performance using evaluation metrics like accuracy score.

## Key Features in the Dataset
The dataset contains the following physicochemical properties of wine:

- Fixed Acidity: Acidity that does not evaporate.
- Volatile Acidity: Acidity that contributes to the aroma.
- Citric Acid: Adds freshness and flavor.
- Residual Sugar: Indicates sweetness.
- Chlorides: Salt content.
- Free and Total Sulfur Dioxide: Helps in preservation.
- Density: Correlated with sugar and alcohol content.
- pH: Acidity level.
- Sulphates: Enhances flavor.
- Alcohol: Affects taste and quality.
- Quality: Target variable rated on a scale (e.g., 0–10).

## Workflow of the Project
- Data Collection: Using the public wine quality dataset
- Data Preprocessing:
Handling missing values.
- Label Binarization of the Quality column.
- Exploratory Data Analysis (EDA):
    Analyzing feature distributions and correlations.
    Visualizing relationships between features and wine quality.
- Model Building:
Training machine learning model
- Model Evaluation:
Using metrics like accuracy, precision, recall, F1-score, and confusion matrix to assess the models.

## Key Insights
- Correlation with Quality:
Alcohol and sulphates have a positive correlation with wine quality.
High volatile acidity negatively impacts quality.
- Feature Importance: Alcohol and volatile acidity are the most important predictors for wine quality.

## Technologies and Tools Used
- Programming Language: Python
- Libraries: Pandas and NumPy for data manipulation.
- Matplotlib and Seaborn for data visualization.
- Scikit-learn for machine learning.
- Jupyter Notebook: For code execution and visualization.

  ## Results and Performance
The Random Forest Classifier achieved the highest accuracy of 92%, with precision and recall optimized for the high-quality (1) wines.
Label binarization improved the interpretability of the target variable, making it easier to focus on high-quality wines.

## Conclusion
This project demonstrates the potential of machine learning in predicting and classifying wine quality. The binary classification approach allows for focused attention on high-quality wines, enabling wineries to enhance production and marketing strategies.

## Future Scope
- Integrating sensory data (e.g., taste and aroma) for improved predictions.
- Deploying the model into a user-friendly application for wineries and sommeliers.

<a href="http://localhost:8888/notebooks/Wine%20Quality%20Prediction.ipynb?">Project</a>


## How to Run the Project
- Clone this repository:
git clone https://github.com/Meghana157/Wine-Quality-Prediction.git  
- Install required dependencies:
pip install -r requirements.txt  
- Run the Jupyter Notebook for analysis and model building:
jupyter notebook  



  

