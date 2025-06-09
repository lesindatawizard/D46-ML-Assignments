# D46-ML-Assignments
## 📌 ML Assignment 1 – Statistical Measures

**Dataset:** [House Price Data - Bangalore](https://drive.google.com/file/d/1UlWRYU0UglE2ex3iFse0J6eCLEU8g98P/view?usp=sharing)

### ✅ Objectives:
Analyze `price_per_sqft` in Bangalore's real estate data using various statistical and visualization methods.

### 🔧 Steps Performed:

1. **Exploratory Data Analysis (EDA)**:
   - Inspected structure, nulls, and summary statistics.

2. **Outlier Detection & Removal** using:
   - Mean & Standard Deviation
   - Percentile Method (5th and 95th)
   - IQR (Interquartile Range)
   - Z-Score
   - Handled using trimming, capping, and imputation.

3. **Box Plot**:
   - Compared outlier removal methods visually using boxplots.

4. **Histplot & Normality Checks**:
   - Plotted distribution of `price_per_sqft`.
   - Checked **Skewness** and **Kurtosis** before and after transformation.
   - Applied log/sqrt transformations if needed.

5. **Correlation Analysis**:
   - Generated a heatmap of numerical features.

6. **Scatter Plots**:
   - Visualized relationships between important numerical variables.

7. **Timely Submission** ✅

---

## 📌 ML Assignment 2 – EDA and Preprocessing

**Dataset:** [Data Preprocessing Dataset](https://drive.google.com/file/d/1F3lRf32JM8ejnXq-Cbf9y7fa57zSHGz_/view?usp=sharing)

### ✅ Objectives:
Build a robust preprocessing system tackling missing data, outliers, encoding, and scaling.

### 🔧 Steps Performed:

1. **Data Exploration**:
   - Extracted unique values and lengths for each feature.
   - Renamed columns for clarity and usability.

2. **Data Cleaning**:
   - Treated missing/inappropriate values.
   - Replaced 0 in age with NaN.
   - Imputed nulls using mean/median/mode.
   - Removed duplicate entries.
   - Detected and removed outliers.

3. **Data Analysis**:
   - Filtered: `age > 40` and `salary < 5000`
   - Visualized age vs salary
   - Counted and plotted people per location.

4. **Data Encoding**:
   - Applied **Label Encoding** and **One-Hot Encoding**.

5. **Feature Scaling**:
   - Scaled features using **StandardScaler** and **MinMaxScaler**.
