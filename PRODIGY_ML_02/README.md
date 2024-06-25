<div style="font-family: 'Arial', sans-serif; max-width: 90%; margin: 0 auto; text-align: justify; line-height: 1.6; background: linear-gradient(to bottom, #394240, #1C1F29); padding: 20px; border-radius: 15px; box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2); color: #D2C9B8;">

  <div style="text-align: center; margin-bottom: 20px;">
    <h2 style="color: #E4D8B4; font-size: 28px; border-bottom: 2px solid #E4D8B4; padding-bottom: 10px;">Clustering Algorithms</h2>
  </div>

  <div style="margin-bottom: 20px;">
    <p style="margin-bottom: 10px;">Clustering algorithms are essential tools in machine learning, used for grouping similar data points. This study examines four popular clustering algorithms: K-means, Hierarchical Clustering, DBSCAN, and Affinity Propagation..</p>
  </div>

  <div style="margin-bottom: 20px;">
    <h3 style="font-size: 24px; border-bottom: 2px solid #E4D8B4; padding-bottom: 10px;">K-means Clustering</h3>
    <p style="margin-bottom: 10px;">K-means is an iterative algorithm that partitions data into K distinct clusters by assigning data points to the nearest cluster centroids. It minimizes the within-cluster sum of squares, making it computationally efficient and effective for well-separated, similarly-sized clusters. However, it requires the number of clusters to be specified in advance..</p>
  </div>

  <div style="margin-bottom: 20px;">
    <h3 style="font-size: 24px; border-bottom: 2px solid #E4D8B4; padding-bottom: 10px;">Hierarchical Clustering</h3>
    <p style="margin-bottom: 10px;">Hierarchical clustering creates a tree-like structure of clusters by either merging (agglomerative) or splitting (divisive) clusters based on similarity. Unlike K-means, it doesn't require specifying the number of clusters beforehand. It provides a dendrogram, a visual representation of the clustering process, which helps in deciding the number of clusters.y.</p>
  </div>

  <div style="margin-bottom: 20px;">
    <h3 style="font-size: 24px; border-bottom: 2px solid #E4D8B4; padding-bottom: 10px;">DBSCAN (Density-Based Spatial Clustering of Applications with Noise)</h3>
    <p style="margin-bottom: 10px;">DBSCAN is a density-based clustering algorithm that groups together data points based on their density. It defines clusters as dense regions separated by sparser areas. DBSCAN can discover clusters of arbitrary shapes, handle noisy data, and does not require specifying the number of clusters in advance. It classifies points as core, border, or noise based on density and connectivity.</p>
  </div>

  <div style="text-align: center; margin-bottom: 20px;">
    <h2 style="color: #E4D8B4; font-size: 28px; border-bottom: 2px solid #E4D8B4; padding-bottom: 10px;">The Dataset</h2>
  </div>

  <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px;">
    <thead>
      <tr style="background-color: #4CAF50; color: white;">
        <th style="padding: 10px; border: 1px solid #ddd;">Column</th>
        <th style="padding: 10px; border: 1px solid #ddd;">Description</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">CustomerID</td>
        <td style="padding: 10px; border: 1px solid #ddd;">An identifier for each customer.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">Gender</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Indicates the gender of the customer (Male or Female).</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">Age</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Represents the age of the customer in years.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">Annual Income (k$)</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Denotes the annual income of the customer in thousands of dollars.</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd;">Spending Score (1–100)</td>
        <td style="padding: 10px; border: 1px solid #ddd;">A score ranging from 1 to 100 that quantifies the customer’s spending habits and preferences. A higher score indicates a higher tendency to spend.</td>
      </tr>
    </tbody>
  </table>

  <div style="text-align: center;">
    <p style="margin-bottom: 10px;">
      Explore the dataset on Kaggle
      <a href="https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python" target="_blank" style="text-decoration: none; color: #007BFF; margin-left: 5px;">
        🌐 View Dataset
      </a>
    </p>
  </div>

</div>
