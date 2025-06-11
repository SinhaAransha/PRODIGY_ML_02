# Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using K-Means clustering based on the **Annual Income** and **Spending Score** of customers from a mall dataset. The segmentation helps in identifying distinct groups of customers, which can assist in targeted marketing and business strategy optimization.

## Dataset

The dataset used is the [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial) available on Kaggle. It contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

**File name**: `Mall_Customers.csv`

## Features Used for Clustering

- `Annual Income (k$)`
- `Spending Score (1-100)`

## Steps to Run

### 1. Open in Google Colab

You can run the notebook directly in [Google Colab](https://colab.research.google.com/).

### 2. Upload Dataset

- Download the dataset from [Kaggle Mall Customer Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial).
- Upload the `Mall_Customers.csv` file when prompted using the upload cell in the notebook.

### 3. Execution

The notebook performs the following steps:

- Loads and explores the dataset.
- Standardizes selected features.
- Applies the Elbow Method to determine the optimal number of clusters.
- Trains a K-Means model using the optimal number of clusters.
- Visualizes the customer segments using a scatter plot.

## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

## Output

- Elbow plot to determine optimal `k`
- Scatter plot of clusters in standardized feature space
- Cluster assignments appended to the dataset

## License

This project is open source and available under the [MIT License](LICENSE).
