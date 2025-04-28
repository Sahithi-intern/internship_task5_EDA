<!-- Heading 1 -->
# Titanic Exploratory Data Analysis (EDA)

<!-- Heading 2 -->
## Objective
<!-- Bold -->
Perform **Exploratory Data Analysis** (EDA) on the **Titanic dataset** using **Pandas**, **Seaborn**, and **Matplotlib** to uncover survival patterns among passengers.

---

<!-- Heading 2 -->
## Dataset Details
- **Training Set:** 891 rows  
- **Test Set:** 418 rows  
- **Key Columns:**  
  - `Survived` (Target)
  - `Pclass`
  - `Sex`
  - `Age`
  - `SibSp`
  - `Parch`
  - `Fare`
  - `Embarked`

---

<!-- Heading 2 -->
## EDA Steps

<!-- Heading 3 -->
### 1. Load & Inspect
- Use `.info()`, `.describe()`, and `.isnull().sum()` to understand the data structure and missing values.

<!-- Heading 3 -->
### 2. Univariate Analysis
- **Histograms:**  
  - Age
  - Fare
- **Countplots:**  
  - Survived
  - Sex
  - Pclass
  - Embarked

<!-- Heading 3 -->
### 3. Bivariate Analysis
- **Boxplot:**  
  - Fare by Survived
- **Countplots:**  
  - Survived by Sex
  - Survived by Pclass

<!-- Heading 3 -->
### 4. Multivariate Analysis
- **Correlation Heatmap:**  
  - Visualize feature correlations using `sns.heatmap()`.
- **Pairplot:**  
  - Examine feature interactions using `sns.pairplot()`.

---

<!-- Heading 2 -->
## Observations
Observations are written directly **under each plot** for clarity and context.

---

<!-- Heading 2 -->
## Final Summary
<!-- Bold -->
**Key Findings:**
- **Female passengers** had significantly higher survival rates.
- **Lower-class** passengers (`Pclass=3`) had reduced survival odds.
- **Higher fares** were positively correlated with survival.
- **Age distribution** was skewed; survival patterns varied between children and the elderly.


