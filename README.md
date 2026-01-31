# Task5_python-basics
## 📌 Objective
The objective of this task is to gain hands-on experience with Python and Pandas by reading a dataset, identifying data quality issues, performing basic data cleaning, and saving a cleaned version of the dataset for analysis.

---

## 🛠 Tools & Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy

---

## 📂 Dataset
- Dataset Used: `tested.csv` (Titanic Dataset)
- The dataset contains passenger information such as age, gender, fare, and survival status.

---

## 🧪 Steps Performed

1. Imported required Python libraries (`pandas`, `numpy`)
2. Loaded the dataset using `pd.read_csv()`
3. Explored the dataset using `.head()` and `.info()`
4. Identified missing values using `.isnull().sum()`
5. Handled missing values:
   - Numerical columns filled using median
   - Categorical columns filled using mode
6. Dropped irrelevant columns where necessary
7. Checked and removed duplicate records
8. Converted data types for accurate analysis
9. Created new feature columns for better insights
10. Saved the cleaned dataset as `cleaned_data.csv`

---

## 📁 Files Included
- `Task5_Cleaning.ipynb` → Jupyter Notebook with complete code and markdown explanations
- `cleaned_data.csv` → Cleaned dataset after preprocessing
- `README.md` → Task documentation

---

## 📊 Outcome
- Successfully cleaned and prepared the dataset using Pandas
- Improved understanding of data preprocessing techniques
- Learned how Python simplifies data cleaning compared to manual Excel methods

---

## 👩‍💻 Author
Ramya MA  
(Data Analyst Intern)
