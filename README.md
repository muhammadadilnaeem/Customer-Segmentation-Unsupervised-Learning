
---

# Customer Segmentation Using Clustering Techniques

This project explores customer segmentation using various clustering techniques on a dataset of mall customers. The goal is to identify distinct customer groups based on demographic and behavioral attributes, enabling businesses to tailor their marketing strategies more effectively.

## **Project Overview**

The objective of this analysis is to segment customers to better understand their demographics and spending behavior, which can help businesses improve their marketing strategies and customer satisfaction.

## **Dataset Description**

The dataset consists of the following attributes:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars.
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature.

## **Data Exploration and Cleaning**

1. **Checked for missing values**: Ensured the dataset is complete with no missing values.
2. **Summary statistics**: Provided an overview of the data distribution.
3. **Feature Engineering**: Encoded the 'Gender' attribute and scaled the features to ensure they are on a comparable scale.

## **Clustering Techniques Employed**

### **K-Means Clustering**
Tried different numbers of clusters (k = 2 to 5) and selected the best one based on silhouette scores.

### **Agglomerative Clustering**
Experimented with various cluster counts and selected the best model based on silhouette scores.

### **DBSCAN**
Explored different epsilon values for density-based clustering and identified the best model based on silhouette scores.

## **Key Findings and Insights**

- Identified distinct customer groups based on age, income, and spending habits.
- Uncovered patterns that can drive personalized marketing efforts and enhance customer experiences.

## **Recommendations**

- Further exploration with additional features could refine the segmentation.
- Diving deeper into individual clusters for more targeted strategies.

## **Project Structure**

- `data/`: Contains the dataset used for the analysis.
- `notebooks/`: Jupyter notebooks with the data exploration, cleaning, and clustering models.


## Usage

To reproduce the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-clustering.git
   cd customer-segmentation-clustering
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebooks or scripts to perform the analysis:
   ```bash
   jupyter notebook notebooks/data_exploration.ipynb
   ```

## Contributing

If you have suggestions for improvements or would like to contribute, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE]([LICENSE](https://github.com/muhammadadilnaeem/Customer-Segmentation-Unsupervised-Learning/blob/main/LICENSE)) file for details.

---
