# Titanic Dataset: Exploratory Data Analysis (EDA)

This project explores the **Titanic dataset** using **Python, Pandas, NumPy, Matplotlib, and Seaborn**.  
The goal is to perform **data cleaning, visualization, and analysis** to understand **factors affecting passenger survival**.

---

## **Project Overview**

The Titanic dataset contains information about passengers aboard the Titanic, including demographics, ticket info, and survival outcome.  

**Columns in the dataset:**

| Column | Meaning |
|--------|---------|
| PassengerId | Unique ID for each passenger |
| Survived | Survival status: 0 = Did not survive, 1 = Survived |
| Pclass | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| Name | Full name of the passenger |
| Sex | Gender of the passenger (male/female) |
| Age | Age in years |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare in British pounds |
| Embarked | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## **Key Steps in the Analysis**

1. **Import Libraries** – Set up Python libraries for data analysis and visualization.  
2. **Load Data** – Load Titanic dataset from Excel / CSV file.  
3. **Explore Data** – Check structure, summary statistics, and missing values.  
4. **Clean Data** – Fill missing values, drop irrelevant columns, and prepare dataset for analysis.  
5. **Analyze Survival**  
   - Overall survival rate  
   - Survival by **sex**  
   - Survival by **passenger class (Pclass)**  
   - Age distribution and effect on survival  
6. **Feature Correlations** – Explore relationships between numerical features.  
7. **Cross Analysis** – Survival by **sex and class combination** to identify groups with highest and lowest survival.  
8. **Save Cleaned Dataset** – Save processed data for future analysis or modeling.

---

## **Key Insights**

- **Overall survival:** ~38% of passengers survived  
- **Gender:** Women had a higher survival rate (~75%) than men (~20%)  
- **Passenger class:** 1st class had the highest survival (~62%), 3rd class the lowest (~25%)  
- **Age:** Younger passengers had slightly better survival, but age was less impactful than sex or class  
- **Combination:** Women in 1st class survived the most; men in 3rd class survived the least  

---

## **Visualizations**

The notebook includes:  

- Bar charts for **survival by sex and class**  
- Histograms for **age distribution by survival**  
- Heatmaps for **missing values and correlations**  
- Stacked bar plots for **cross-analysis of sex and class**

These plots help **quickly identify patterns and trends** in the dataset.  

---

## **Files in the Repository**

- `titanic_eda.ipynb` → Colab notebook with full EDA  
- `titanic_cleaned.csv` → Cleaned dataset used in analysis  

---

## **Technologies Used**

- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab  

---

## **How to Use**

1. Open `titanic_eda.ipynb` in **Colab**. 
2. Ensure `titanic_cleaned.csv` is in the same folder.  
3. Run the cells sequentially to see **plots, tables, and insights**.  

---

## **GitHub Link**

You can view this project and interact with the notebook here:  
[GitHub Repository](https://github.com/KankanaSinhaBabu/Titanic_EDA)  

---

## **Author**

- Kankana Sinha Babu
- Email: kankanasb2004@gmail.com
- LinkedIn: [linkedin.com/in/KankanaSinhaBabu](https://www.linkedin.com/in/KankanaSinhaBabu)
- GitHub: [github.com/KankanaSinhaBabu](https://github.com/KankanaSinhaBabu)
  
