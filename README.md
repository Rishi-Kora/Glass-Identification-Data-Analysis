# Glass-Identification-Data-Analysis
This project aims to classify different types of glass using the K-Nearest Neighbors (KNN) algorithm. The dataset used is the Glass Identification Database from UCI Machine Learning Repository. The dataset contains 214 instances with 9 features, including the refractive index, and the percentage of various elements present in the glass. The goal is to build a model that can accurately predict the type of glass based on these features.<br>

Methodology:<br>

1. Data Loading and Preprocessing: The project begins by loading the dataset into a Pandas DataFrame. It then preprocesses the data by handling missing values, removing duplicates, and converting categorical features to numerical using Label Encoding.<br>

2. Exploratory Data Analysis (EDA): EDA is performed to gain insights into the dataset. Descriptive statistics, correlation heatmaps, and violin plots are used to understand the distribution and relationships between features.<br>

3. Feature Scaling: Feature scaling is applied using StandardScaler to standardize the features and improve model performance.<br>

4. Model Training: The data is split into training and testing sets, and a KNN classifier is trained using the training set. The optimal value for the number of neighbors (k) is determined.<br>

5. Model Evaluation: The trained model is evaluated on the testing set using metrics such as accuracy, classification report, and confusion matrix.<br>

6. Outlier Detection: Outliers in the dataset are detected using the Z-score method and removed for better model training.<br>

Dataset Link: https://archive.ics.uci.edu/ml/machine-learning-databases/glass/glass.data

Feel free to download the code and data.
