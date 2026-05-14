Clustering & Scaling Techniques

This project focuses on customer segmentation using unsupervised machine learning techniques on E-Commerce transaction data. Multiple clustering algorithms and preprocessing strategies were tested to identify the most meaningful customer groups.

Clustering Algorithms Used
K-Means Clustering
Gaussian Mixture Models (GMM)
Scaling & Transformation Techniques Tested

To improve clustering performance and handle skewed RFM features, several preprocessing techniques were evaluated:

StandardScaler
MinMaxScaler
RobustScaler
Quantile Transformer
Power Transformer
Quantile Normalization
Box-Cox Transformation
No Scaling (baseline comparison)
Model Evaluation

The models were compared using:

Silhouette Score
Cluster Balance
Cluster Stability
Visual Cluster Separation
Business Interpretability

Although the unscaled models achieved higher silhouette scores, the final selection prioritized practical customer segmentation and balanced cluster formation.

Final Selected Model

K-Means with StandardScaler was selected as the final model because it provided:

Better feature fairness across RFM variables
Cleaner silhouette structure
More balanced clusters
Stable and business-friendly customer segmentation
Key Insight

This project demonstrates that the best clustering model is not always the one with the highest silhouette score. Business interpretability, cluster balance, and practical usability are equally important in real-world segmentation problems.
