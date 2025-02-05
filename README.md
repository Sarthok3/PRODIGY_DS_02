# **A STATISTICAL OVERVIEW OF THE TITANIC DATASET: EXPLORING SURVIVAL PATTERNS AND CORRELATIONS** #


**1. Loading Data:**
The Titanic dataset is loaded from a CSV file into a DataFrame (df).

**2. Handling Missing Values:**
- Missing values in the 'Age' column are filled with the median of that column.
- Missing values in the 'Embarked' column are filled with the most frequent value (mode).
- The 'Cabin' column is dropped since it contains too many missing values.

**3. Data Transformation:**
- The 'Sex' column is converted from categorical values ('male', 'female') to numeric (0, 1).
- The 'Embarked' column is one-hot encoded into dummy variables, with the first category dropped.

**4. Exploratory Data Analysis:**
- Descriptive statistics are displayed for the dataset.
- The survival rate is calculated and printed.
- Bar plots are created to show survival rates by gender and passenger class.
- A histogram with a KDE (Kernel Density Estimate) is plotted to visualize the distribution of ages.
- A correlation matrix is calculated and visualized using a heatmap.

**5. Label Encoding:** 
The 'Sex' and 'Embarked' columns are label encoded to convert categorical data into numeric format.

**6. Correlation Matrix**: 
A final heatmap of the correlation matrix is generated after encoding to show the relationships between numerical variables.

**Key Objective:**
The key objective of this code is to preprocess the Titanic dataset by handling missing values, converting categorical variables, and performing exploratory data analysis (EDA) to visualize survival patterns, distribution, and correlations between features to understand key relationships.
