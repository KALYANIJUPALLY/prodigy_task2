# prodigy_task2

# K-Means Customer Segmentation

## Overview
This project applies K-Means clustering to segment customers of a retail store based on their purchase history. The dataset used is `Mall_Customers.csv`. The clustering model helps in identifying distinct customer groups to improve marketing strategies and business insights.

## Dataset
The dataset contains customer information, including:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

## Features Used for Clustering
For clustering, the model considers:
- **Annual Income**
- **Spending Score**

## Steps
1. Load and preprocess the dataset.
2. Standardize the selected features.
3. Determine the optimal number of clusters using the **Elbow Method**.
4. Apply K-Means clustering.
5. Visualize the customer segments.
6. Save the clustered dataset.

## Installation & Requirements
Ensure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Running the Script
Execute the Python script:
```bash
python kmeans_customer_segmentation.py
```

## Output
- **Elbow Method Graph**: Helps determine the optimal number of clusters.
- **Clustered Scatter Plot**: Visual representation of customer segments.
- **Clustered Dataset**: Saved as `Mall_Customers_Clustered.csv`.

## Usage
This segmentation can be used for:
- Targeted marketing campaigns.
- Personalized customer engagement.
- Business decision-making based on customer behavior.

## Contributing
Feel free to fork this repository and submit pull requests for improvements or additional features.

## License
This project is licensed under the MIT License.

