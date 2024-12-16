**Predicting Falcon 9 First Stage Landing Success**

## Overview  

In this capstone project, we aim to predict the success of Falcon 9 first-stage landings using data analysis and machine learning techniques.  

SpaceX revolutionized space exploration by reusing its Falcon 9 rocket's first stage, significantly reducing the cost of launches. With a price of $62 million per launch compared to other providers charging upwards of $165 million, much of the savings come from SpaceX's reusability. Predicting whether the first stage will successfully land can help estimate launch costs and allow alternate companies to bid competitively against SpaceX for rocket launches.  

---

## Objectives  

1. **Understand the data**: Analyze the historical launch data of Falcon 9 rockets.  
2. **Build predictive models**: Predict the success of first-stage landings using supervised machine learning techniques.  
3. **Evaluate cost implications**: Use prediction outcomes to assess the potential cost of launches.   

---

## Methodology  

### 1. **Data Collection & Preprocessing**  
   - Historical launch data was sourced from publicly available APIs and databases.  
   - The data underwent cleaning and transformation to handle missing values, categorical variables, and feature scaling.  

### 2. **Exploratory Data Analysis (EDA)**  
   - Insights into key factors influencing landing success, such as payload mass, orbit type, and booster version.  
   - Visualizations to understand correlations and trends.

### 3. **Machine Learning**  
   - Supervised learning models, including Logistic Regression, Support Vector Machines, Decision Trees, and Gradient Boosting, were trained to predict first-stage landing success.  
   - K-fold cross-validation was used to validate models.  

### 4. **Evaluation**  
   - Models were evaluated on accuracy, precision, recall, and F1 score.  
   - The best-performing model was selected for deployment.  

---

## Prerequisites  

### Tools and Libraries  
The project requires the following:  

- Python 3.8 or higher  
- Jupyter Notebook  
- Libraries:  
  ```bash
  pip install numpy pandas matplotlib seaborn scikit-learn
