 Warehouse Optimization Using Clustering 

📌 Project Overview  
Efficient warehouse management is crucial for reducing operational costs and improving logistics. This project applies clustering methods to optimize warehouse layouts, streamline storage allocation, and enhance inventory management.  

By using **unsupervised machine learning techniques**, we segment inventory based on demand patterns, product categories, and storage efficiency.  

Dataset  
The dataset contains warehouse-related attributes such as:  
- Demand
- Longitude
- Latitude 

 Machine Learning Approach  
We applied clustering algorithms to optimize warehouse operations:  

✅ K-Means Clustering – Grouping similar inventory items  
✅ Hierarchical Clustering – Understanding product relationships  
✅ DBSCAN – Detecting anomalies in stock movements  

 Evaluation Metrics  
To validate clustering effectiveness, we used:  
- Silhouette Score – Measures clustering quality  
- Inertia (Within-Cluster SSE) – Evaluates compactness  
- Davies-Bouldin Index – Assesses cluster separation  

Key Insights  
📌 K-Means clustering provided optimal warehouse segmentation  
📌 High-demand items were moved to easily accessible zones  
📌 Anomaly detection identified slow-moving or misplaced stock  

Future Improvements
- Test with additional clustering techniques (Gaussian Mixture, Agglomerative Clustering)
- Integrate real-time warehouse tracking data


🛠 Installation & Usage  
🔹 Clone the Repository  
```sh
git clone https://github.com/yourusername/Warehouse-Optimization.git
cd Warehouse-Optimization
