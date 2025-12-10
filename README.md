
# 🏡 Descriptive Statistics on California Housing Dataset

## 📌 Objective
Perform basic descriptive statistics on a real dataset to understand central tendency, variation, and range of values before deeper analysis or modeling.

## [Live Demo](https://youtu.be/hjSgv77GSCw)

## 📂 Dataset
- **Source:** Google Colab’s `sample_data` folder  
- **File:** `california_housing_train.csv`  
- Contains housing data for California, including features like longitude, latitude, median income, and median house value.

## 🛠️ Tools & Libraries
- **Python**
- **Pandas**
- **NumPy**

## 🔑 Key Concepts
- `read_csv()` → Load dataset  
- `describe()` → Quick overview of all numeric columns  
- `mean()`, `median()`, `min()`, `max()`, `std()` → Specific descriptive statistics  

## 📖 Workflow
1. **Load dataset**
   ```python
   import pandas as pd
   import numpy as np

   df = pd.read_csv("/content/sample_data/california_housing_train.csv")
   ```
2. **Preview data**
   ```python
   df.head()
   ```
3. **Descriptive statistics**
   ```python
   df.describe()
   ```
   This provides count, mean, std, min, max, and quartiles for all numeric columns.

4. **Column-specific statistics (example: `median_income`)**
   ```python
   df["median_income"].mean()
   df["median_income"].median()
   df["median_income"].min()
   df["median_income"].max()
   df["median_income"].std()
   ```

## 📊 Results
- **Mean of median_income:** `3.88`  
- **Median of median_income:** `3.54`  
- **Minimum:** `0.49`  
- **Maximum:** `15.00`  
- **Standard Deviation:** `1.91`

## 💡 Insights
- Median income is a key factor in housing affordability and strongly influences housing prices.  
- Descriptive statistics provide a quick overview to spot trends and anomalies.  
- This step is essential before moving into deeper analysis or predictive modeling.

## 🎯 Learning Outcome
This task demonstrates:
- Ability to load and explore real datasets.  
- Application of statistical functions in Pandas.  
- Clear presentation of insights — a skill I am preparing to showcase in my internship applications.


