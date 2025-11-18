# Scikit-learn-Unsupervised-Learning-Image-Segmentation-Anomaly-and-Skin-Detection
A comprehensive Python project demonstrating unsupervised learning techniques, including image segmentation with clustering, anomaly detection in credit card transactions, and skin detection using YCbCr and Gaussian Mixture Models (GMM). Ideal for learning real-world applications of clustering and pattern recognition.
1. **Image Segmentation with Clustering**
   - Segment images into meaningful regions using **K-means++, K-medoids, and Agglomerative Clustering**.
   - Visualize results and evaluate clustering performance using **WCSS** and **Silhouette Scores**.
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/c64a16bb-26c0-40ca-bb47-51ccde7b9eaa" width="250" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/56c748a5-df07-4015-bd2d-a33a463c0618" width="200" />
  <img src="https://github.com/user-attachments/assets/e16d9d66-2662-4901-b043-3a4c8cec3117" width="200" />
  <img src="https://github.com/user-attachments/assets/6a67d0a0-12ea-4572-bf6d-0b79ff5b15d5" width="200" />
</p>
<br>

2. **Anomaly Detection in Credit Card Transactions**
   - Detect fraudulent transactions using clustering methods such as **K-means++, K-medoids, and DBSCAN**.
   - Preprocess and standardize the dataset for effective analysis.
   - Visualize anomalies in 2D using **PCA** and **t-SNE** projections.
   - Identify patterns and correlations for fraud detection.
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/affe3957-de92-425f-a570-89cce9fc4f7d" width="250" />
  <img src="https://github.com/user-attachments/assets/702c737b-f4ab-49c8-93d9-16e601558209" width="250" />
  <img src="https://github.com/user-attachments/assets/a806a8c8-5d0f-4e8e-af50-00c9e8b47783" width="250" />
</p>
<br>

3. **Skin Detection via YCbCr + GMM**
   - Convert RGB images to YCbCr color space.
   - Apply **Gaussian Mixture Models** to detect and segment skin regions.
   - Explore applications in computer vision and biometric systems.
<p align="center">
  <img src="https://github.com/user-attachments/assets/ec96e801-3d79-45ec-afad-2aa4afa4a5bf" width="200" />
  <img src="https://github.com/user-attachments/assets/572226ab-a693-409f-8971-399305be40c1" width="200" />
  <img src="https://github.com/user-attachments/assets/ac374d92-2d6c-4492-8279-dd8d07bf1635" width="200" />
  <img src="https://github.com/user-attachments/assets/bbc607fb-ba68-4b18-b3ca-017a907981b7" width="200" />
</p>
<br>

## **Technologies & Libraries Used**
- **Python 3.x**
- **NumPy, Pandas** – for numerical and data manipulation
- **Matplotlib, Seaborn** – for data visualization
- **scikit-learn** – for clustering, dimensionality reduction, and evaluation metrics
- **OpenCV, PIL** – for image processing
- **t-SNE, PCA** – for dimensionality reduction in visualization

---
## **Project Structure**
├── Image_Segmentation/
│ ├── kmeans.py
│ ├── kmedoids.py
│ ├── agglomerative.py
│ └── example_images/
├── Anomaly_Detection/
│ ├── credit_card_fraud.ipynb
│ └── datasets/
└── Skin_Detection/
├── ycbcr_gmm.py
└── example_images/

---

## **Features**
- **Clustering Algorithms**: Custom implementations of K-means++, K-medoids, and Agglomerative Clustering.
- **Anomaly Detection**: Identify rare events in financial transactions using unsupervised methods.
- **Visualization**: High-quality visualizations of clusters, segmented images, and anomalies using PCA and t-SNE.
- **Evaluation Metrics**: Silhouette score and Within-Cluster Sum of Squares (WCSS) to assess clustering quality.
- **Real-world Applications**: Fraud detection, image segmentation, and skin detection for computer vision tasks.

---

1. Clone the repository:
```bash
git clone https://github.com/your-username/Unsupervised-Learning-Image-Analysis-and-Anomaly-Detection.git
cd Unsupervised-Learning-Image-Analysis-and-Anomaly-Detection
---

Install required libraries:
pip install -r requirements.txt
Run Jupyter notebooks or Python scripts for:

Image Segmentation
Credit Card Fraud Detection
Skin Detection

Datasets
Credit Card Fraud Detection Dataset: Available on Kaggle, also in this repository

License
This project is licensed under the MIT License.








