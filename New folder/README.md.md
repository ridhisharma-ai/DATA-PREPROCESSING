PROJECT OVERVIEW:
 This project focuses on the fundamental steps of Data Preprocessing, which is the most critical phase in any Machine Learning pipeline. Raw data is often messy, incomplete, or in a format that computers cannot understand. This task demonstrates how to transform raw data into a clean, scaled, and structured format ready for model training.

Objectives:
The primary goals of this project are:
Handle Missing Data: Identifying and filling null values to maintain dataset integrity.

Categorical Encoding: Converting text labels (like species names) into numerical values using LabelEncoder.

Feature Scaling: Standardizing numerical features using StandardScaler so that all variables contribute equally to the model.

Dataset Splitting: Dividing the data into Training and Testing sets to evaluate model performance fairly.

Tools and Libraries:
The following Python libraries were used:
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Scikit-learn: For preprocessing, scaling, and splitting the data.

Steps Involved:
1. Data Loading
Loading the iris.csv dataset and performing an initial inspection to understand the features (Sepal Length, Sepal Width, Petal Length, Petal Width) and the target (Species).
2. Data Cleaning
Checking for missing values. In this dataset, the data is complete; however, the pipeline includes logic to handle potential nulls by using mean or median imputation.
3. Encoding
The target variable species contains strings (setosa, versicolor, virginica). These are transformed into integers (0, 1, 2) because machine learning algorithms require numerical input.
4. Normalization & Scaling
Since numerical features can have different ranges, we apply Standardization. This shifts the distribution of each feature to have a mean of 0 and a standard deviation of 1.
5. Train-Test Split
The data is split into an 80% Training set and a 20% Testing set. This ensures we can test our future model on "unseen" data.