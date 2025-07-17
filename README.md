#  Sleep Data Analysis Project

This project aimed to perform an exploratory and statistical analysis of a real-world dataset related to patients' sleep.  
The dataset included personal characteristics (age, weight, height, gender), lifestyle habits (alcohol, screen time, smoking), and the presence or absence of insomnia.

---

##  Methodology

### 1️⃣ Descriptive and Inferential Analysis
- Creation of new variables: BMI and BMI category (Normal / Overweight)
- Descriptive statistics on all variables
- Visualization of age distribution (histogram)
- Normality tests (Shapiro-Wilk on age)
- Age comparison based on insomnia status (boxplots + Student’s t-test after hypothesis verification)
- Cross-analysis between Insomnia and Smoking using Chi² independence test and bar plots

### 2️⃣ Principal Component Analysis (PCA)
- Normalization of quantitative variables
- PCA performed using the `prince` package
- Visualization of factor maps: correlation circle, individual projection
- Identification of the most contributing variables to the principal axes

### 3️⃣ Hierarchical Clustering (HAC)
- First HAC: based on BMI, Alcohol, Age, Screen time
- Second HAC: based on Weight, Height, Alcohol, Age, Screen time
- Dendrogram visualization and selection of optimal number of clusters
- Comparison of resulting clusters with BMI category (contingency tables)
- Cluster visualization on the PCA factorial plane

---

##  Skills Applied

- **Python** (Pandas, Seaborn, Scipy, Scikit-learn, Prince)
- **Statistical modeling** and hypothesis testing
- **Data preprocessing and transformation**
- **Dimensionality reduction** and **clustering techniques**

---

##  Author

Hajar Badraoui  
[GitHub Profile](https://github.com/Hajar-badr)  
Project conducted as part of applied statistics coursework.
