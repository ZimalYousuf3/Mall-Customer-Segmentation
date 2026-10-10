# Mall Customer Segmentation using K-Means

A customer segmentation project that uses K-Means clustering to group mall customers based on their annual income and spending score. The goal is to identify distinct customer groups that a marketing team could actually use, going beyond raw cluster numbers into clear, human readable personas.

## Workflow

- Performed initial EDA (info, describe, dtypes, missing values check)
- Scaled `Annual Income` and `Spending Score` using `StandardScaler`
- Used the Elbow Method to determine the optimal number of clusters (k=5)
- Trained a K-Means model and assigned cluster labels
- Visualized clusters with a scatter plot, including cluster centers
- Built customer personas by analyzing each cluster's average income and spending 

## Personas Identified

- **Average** — customers with income and spending close to the overall average
- **High Income, High Spending** — top target customers for premium offers
- **Low Income, High Spending** — price sensitive but highly engaged shoppers
- **High Income, Low Spending** — high potential customers who are currently under-engaged
- **Low Income, Low Spending** — budget conscious, minimal engagement customers

## Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Scikit-learn (`KMeans`, `StandardScaler`)

## Dataset

[Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle, containing customer ID, gender, age, annual income, and spending score for 200 mall customers.
