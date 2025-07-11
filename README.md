# Titanic Dataset - Exploratory Data Analysis (EDA)

This project is a complete Exploratory Data Analysis (EDA) on the famous Titanic dataset using Python libraries like Pandas, Seaborn, and Matplotlib. The goal is to understand the structure of the data, detect patterns, handle missing values, and visualize insights.

---

##  Objective

To analyze the Titanic dataset and find key insights such as:
- Survival rates based on gender and passenger class
- Age distribution of passengers
- Correlation between features
- Handling missing values and outliers

---

## Technologies Used

- *Python 3.8+*
- *Pandas*
- *NumPy*
- *Matplotlib*
- *Seaborn*
- Jupyter Notebook / Google Colab

---

## Dataset

- Source: [Titanic Dataset - Kaggle](https://www.kaggle.com/c/titanic/data)  
- Alternative: [Open CSV Link](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## EDA Tasks Performed

1. *Data Loading*
2. *Initial Exploration*
   - Shape, Info, Describe
3. *Missing Values Handling*
   - Age filled with median
   - Dropped 'Cabin' due to high nulls
4. *Univariate Analysis*
   - Countplot for 'Survived'
   - Distribution of 'Age', 'Fare'
5. *Bivariate Analysis*
   - Survival by 'Sex' and 'Pclass'
   - Boxplot of 'Age' vs 'Pclass'
6. *Outlier Detection*
   - Boxplots, IQR method
7. *Correlation Analysis*
   - Heatmap

---

##  Key Insights

- Female passengers had much higher survival rates.
- Passengers in 1st class were more likely to survive.
- Many missing values in 'Cabin' and some in 'Age'.
- Strong negative correlation between Pclass and Survival.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda
