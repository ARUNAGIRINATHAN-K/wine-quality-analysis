## 🍷 Wine Quality Analysis

This project performs **exploratory data analysis (EDA)** and **multidimensional visualizations** on the UCI Wine Quality dataset (Red & White wines).

## 📊 Features
- Data preprocessing & cleaning
- Statistical summary
- Multivariate analysis:
  - Correlation heatmap
  - Pairplot
  - 3D scatter plot
  - Parallel coordinates
  - Andrews curves
  - Radar chart
  - PCA & KMeans Clustering
 
## 📊 Analysis Visualizations

| 📈 Visualization | 📉 Description |
|------------------|----------------|
| ![](images/01-overview.png) | **Overview** of the dataset - distribution of key variables. |
| ![](images/02-correlation.png) | **Correlation Heatmap** showing relationships between variables. |
| ![](images/03-pie-gender.png) | **Gender Distribution** represented in a pie chart. |
| ![](images/04-age-dist.png) | **Age Distribution** histogram of the subjects. |
| ![](images/05-income-bar.png) | **Income Categories** visualized using a bar chart. |
| ![](images/06-region-map.png) | **Geographic Spread** of data points on a map. |
| ![](images/07-trend-line.png) | **Trend Analysis** over time using a line chart. |
| ![](images/08-boxplot.png) | **Boxplot** of variable distribution for outlier detection. |
| ![](images/09-cluster.png) | **K-Means Clustering** visualization. |
| ![](images/10-forecast.png) | **Forecast** of future trends using time series. |

## 📁 Structure
- `data/`: CSV datasets
- `notebooks/`: Jupyter notebook with full EDA
- `src/`: Python scripts (optional modularization)
- `visuals/`: Saved plots/images

## 🚀 How to Run
1. Clone this repo  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
