# Predicting steel item prices: a regression analysis using daily offers dataset
The attached dataset “daily_offers.xlsx” is a representation of steel items offered to customers. Each row represents an item and has an offered/selling price of that item. I analyzed all the features, using statistical and visualization methods and prepare the data for a regression model. I split the data into training and testing sets in the ratio of 90:10 respectively. Then, build 4 regression models to predict the price of an item. Then, evaluate the best model using the metric r2 score on the testing set.

## Files included
1. daily_offers.xlsx: The main dataset that contains steel items and their prices.
2. README.md: A readme file that explains the project and its contents.
3. Analysis.docx: This report provides a detailed analysis of the data and includes insights and conclusions drawn from the Model.
4. ML.ipynb: This file is a well-documented Jupyter notebook that includes all of the code used for the analysis. It also provides detailed explanations of the code and the methodology used for the analysis.

# Usage
To use this dataset and the code for regression analysis, please follow these steps:

1. Download the dataset named "daily_offers.xlsx".
2. Load the dataset into your preferred software for data analysis and visualization.
3. Run the code provided in the "regression_analysis.py" file.
4. The output will be a regression analysis report that includes at least 4 regression models and their r2 scores on the testing set.

# Methodology
The methodology used in this analysis consists of the following steps:

* Data preprocessing: This step involved cleaning the data by removing missing values, outliers, and scaling the data using StandardScaler.
* Model selection: Two machine learning models, Linear Regression and Random Forest Regression, were selected to predict the target variable based on the input features in the dataset.
* Model training: The selected models were trained using the training set and their parameters were adjusted to minimize the difference between the predicted and actual values.
* Model evaluation: The performance of the trained models was evaluated using the testing set and compared using the metric r2 score.
* Model optimization: AdaBoosting and PCA were used to optimize the performance of the selected models and improve their accuracy.
* Analysis: The final step involved analyzing the results and providing insights into the dataset and the models' performance.

# Results
The regression analysis report contains the following results:

* Data exploration: This section provides an overview of the dataset and the exploratory data analysis performed on it.
* Regression models: This section presents at least 4 regression models that were built to predict the price of steel items. Each model includes a description of the model, its parameters, and its r2 score on the testing set.
* Model selection: This section compares the performance of the different models using the metric r2 score and selects the best-performing model.
* Model optimization: This section describes the techniques used to optimize the performance of the selected models and improve their accuracy.
* Conclusion: This section provides a summary of the findings and recommendations for future research or application of the machine learning model.

# Conclusion
In conclusion, this regression analysis project involved analyzing the daily offers dataset to predict the prices of steel items. The analysis included data preprocessing, model selection, model training, model evaluation, model optimization, and analysis. At least 4 regression models were built, and their performance was compared using the metric r2 score. The best-performing model was selected, and techniques such as AdaBoosting and PCA were used to optimize its performance. The final report provides insights into the dataset and the models' performance, which can be used for future research or real-world applications.

# Contributors
* Kanak Poddar
# License
This project is licensed under the MIT License.
