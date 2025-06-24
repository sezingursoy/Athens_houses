# Athens_houses
This project focuses on analyzing the housing market in Athens, Greece. Using publicly available real estate data, we explore key factors affecting property prices such as location, size, and property type. The analysis includes data cleaning, exploratory data visualization, and machine learning-based price prediction models.

## 📁 Project Structure
- `ProjectAthens.ipynb`: Main Jupyter Notebook with all analysis steps

- ## 📌 Objectives

- Clean and preprocess raw housing data from Athens
- Perform exploratory data analysis (EDA)
- Visualize important trends and distributions
- Identify key variables influencing housing prices
- Build a basic regression model to predict house prices

- ## 🛠️ Tools & Technologies

- Python 3  
- Jupyter Notebook  
- Pandas & NumPy (Data manipulation)  
- Matplotlib & Seaborn (Data visualization)  
- Scikit-learn (Machine learning)

- ## 🔍 Workflow Overview
### 1. **Data Collection & Loading**
- Real estate listings are gathered and imported as a CSV file.
- Loaded into a Pandas DataFrame for further processing.
  
### 2. **Data Cleaning**
- Removal of duplicates and rows with missing critical values
- Conversion of data types (e.g., price to float, area to numeric)
- Handling outliers and inconsistent entries
  
### 3. **Exploratory Data Analysis (EDA)**
- Distribution of house prices, sizes, and number of rooms
- Correlation heatmaps to identify relationships
- Neighborhood-level comparisons using groupby operations
- Visualizations (bar plots, box plots, scatter plots)

### 4. **Feature Engineering**
- Creation of new variables such as price per square meter
- Encoding of categorical variables (e.g., property type)
  
### 5. **Modeling**
- Splitting dataset into training and test sets
- Using linear regression (and possibly other models) to predict prices
- Evaluation of model performance using MAE, RMSE, and R² metrics

### 6. **Conclusion**
- Summary of key findings
- Discussion on influential features
- Limitations of the dataset or model
- Suggestions for future improvements

## 👩‍💻 Author
Developed by Ayşe Sezin Gürsoy, Öykü Süzgün, Serencan Sıla Özmen, Kutay Doğru
