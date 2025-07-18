---

# 📊 Census Income Data Clustering for Customer Segmentation

This project applies unsupervised machine learning to the **UCI Census Income dataset**, using clustering techniques to segment the US population into meaningful demographic groups. These insights can inform targeted marketing strategies and socio-economic policy decisions.

---

## 🚀 Features

* Combines and preprocesses Census Income train & test datasets.
* Performs exploratory data analysis (EDA) to identify data quality issues, outliers, and feature distributions.
* Encodes categorical variables and normalizes numerical features for clustering.
* Implements **KMeans clustering** and determines optimal number of clusters using **silhouette score**.
* Visualizes clusters using **Principal Component Analysis (PCA)**.
* Analyzes cluster composition to extract actionable insights about demographic patterns.

---

## 📂 Dataset

* **Source:** [UCI Machine Learning Repository – Census Income](https://archive.ics.uci.edu/ml/datasets/Census+Income)
* Files used:
  * `adult.data`
  * `adult.test`
* Dataset contains ~48,000 records and 15 features, including demographic and economic attributes such as age, workclass, education, marital status, occupation, race, sex, hours-per-week, capital gain/loss, and income (dropped for clustering).

---

## 🧰 Technologies & Tools

* Python 3.x
* Libraries:
  * `pandas`, `numpy` for data processing
  * `scikit-learn` for preprocessing, KMeans, PCA, silhouette score
  * `matplotlib`, `seaborn` for data visualization

---

## 📝 Project Workflow

1. **Data Preparation:**
   * Combine `adult.data` and `adult.test`.
   * Handle missing values and inconsistent categories.
   * Encode categorical features and scale numerical features.
   * Remove duplicates and outliers.

2. **Exploratory Data Analysis:**
   * Analyze feature distributions and correlations.
   * Identify demographic trends.

3. **Clustering:**
   * Train KMeans model and optimize number of clusters using silhouette score.
   * Visualize clusters in 2D using PCA.

4. **Cluster Analysis:**
   * Summarize key statistics of each cluster (e.g., age, hours worked, marital status, gender distribution).

---

## 📊 Results & Insights

* Optimal number of clusters: **3** (based on silhouette analysis)
* Each cluster exhibits distinct demographic and economic characteristics, including differences in age, working hours, income-related attributes, and marital or occupational trends.
* These clusters can help organizations or policymakers tailor strategies to specific population segments.

---

## 📎 Repository Structure

📁 Census_Clustering/
├── census-income-clustering.ipynb # Jupyter notebook with code and analysis
├── Analysis report.pdf # Detailed project report
├── README.md # Project overview and instructions


---

## 📜 How to Run

1️⃣ Clone the repository:

```bash
git clone https://github.com/your-username/customer-segmentation-census-data.git
cd customer-segmentation-census-data
```

2️⃣ Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

3️⃣ Run the notebook:

```bash
jupyter notebook Census_Solution.ipynb
```

## 📖 References
Census Income Dataset - UCI ML Repository

## 👨‍💻 Author
Harmanan Kohli
Data Scientist & Machine Learning Enthusiast

## 📌 GitHub Metadata
Repository Description:
Customer Segmentation using Census Income Data: Unsupervised clustering with KMeans and PCA to reveal demographic patterns.

## GitHub Topics:
machine-learning clustering customer-segmentation kmeans unsupervised-learning pca data-analysis census-data python scikit-learn

