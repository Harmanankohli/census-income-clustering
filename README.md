# Census Income Data Clustering for Customer Segmentation

This project applies unsupervised machine learning to the **UCI Census Income dataset**, using clustering techniques to segment the US population into meaningful demographic groups. These insights can inform targeted marketing strategies and socio-economic policy decisions.

## Features

- **Data Integration**: Combines and preprocesses Census Income train & test datasets
- **Exploratory Data Analysis**: Identifies data quality issues, outliers, and feature distributions
- **Feature Engineering**: Encodes categorical variables and normalizes numerical features for clustering
- **Clustering Implementation**: Uses KMeans clustering with optimal cluster determination via silhouette score
- **Visualization**: Employs Principal Component Analysis (PCA) for cluster visualization
- **Insight Generation**: Analyzes cluster composition to extract actionable demographic patterns

## Dataset

- **Source**: [UCI Machine Learning Repository – Census Income](https://archive.ics.uci.edu/ml/datasets/Census+Income)
- **Files**: `adult.data` and `adult.test`
- **Size**: ~48,000 records with 15 features
- **Features**: Demographic and economic attributes including:
  - Age, workclass, education, marital status
  - Occupation, race, sex, hours-per-week
  - Capital gain/loss, native country
  - Income (excluded from clustering analysis)

## Technologies Used

- **Python 3.x**
- **Core Libraries**:
  - `pandas`, `numpy` - Data processing and manipulation
  - `scikit-learn` - Preprocessing, KMeans, PCA, evaluation metrics
  - `matplotlib`, `seaborn` - Data visualization and plotting

## Project Workflow

### 1. Data Preparation
- Combine training and test datasets
- Handle missing values and inconsistent categories
- Encode categorical features using appropriate techniques
- Scale numerical features for clustering optimization
- Remove duplicates and handle outliers

### 2. Exploratory Data Analysis
- Analyze feature distributions and correlations
- Identify demographic trends and patterns
- Visualize data quality and completeness

### 3. Clustering Analysis
- Implement KMeans clustering algorithm
- Optimize cluster count using silhouette score analysis
- Generate 2D cluster visualizations using PCA
- Validate clustering results

### 4. Cluster Interpretation
- Summarize key statistics for each cluster
- Analyze demographic characteristics (age, gender, marital status)
- Examine economic patterns (working hours, occupation types)
- Extract actionable insights for segmentation strategies

## Key Results

- **Optimal Clusters**: 3 clusters identified through silhouette analysis
- **Distinct Segments**: Each cluster shows unique demographic and economic characteristics
- **Actionable Insights**: Clear differences in age groups, working patterns, and socio-economic status
- **Business Value**: Enables targeted marketing and policy development for specific population segments

## Repository Structure

```
Census_Clustering/
├── census-income-clustering.ipynb    # Main analysis notebook
├── Analysis_report.pdf               # Detailed project report
├── README.md                         # Project documentation

```

## Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Analysis

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/census-income-clustering.git
   cd census-income-clustering
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter notebook**:
   ```bash
   jupyter notebook census-income-clustering.ipynb
   ```

4. **Download dataset** (if not included):
   - Visit the [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income)
   - Download `adult.data` and `adult.test` files
   - Place them in the `data/` directory

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## References

- Dua, D. and Graff, C. (2019). UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science.
- Census Income Dataset: https://archive.ics.uci.edu/ml/datasets/Census+Income

## Author

**Harmanan Kohli**  
Data Scientist & Machine Learning Enthusiast 

## Repository Metadata

**Description**: Customer Segmentation using Census Income Data: Unsupervised clustering with KMeans and PCA to reveal demographic patterns for targeted marketing and policy insights.

**Topics**: `machine-learning` `clustering` `customer-segmentation` `kmeans` `unsupervised-learning` `pca` `data-analysis` `census-data` `python` `scikit-learn` `demographics` `population-analysis`
