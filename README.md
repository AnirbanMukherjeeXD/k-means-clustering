# 🎨 Color Quantization using K-Means Clustering

This project demonstrates color quantization on images using the K-Means clustering algorithm. It also includes a basic K-Means example on the Iris dataset.

<!-- Option 1: Base64 embedded image -->
<!-- Uncomment and replace YOUR_BASE64_STRING to embed image -->


<img src="gif/color_quantized.png" alt="Color Quantization Example" width="80%"/>


<!-- Option 2: Use GIFs from the gif/ folder -->






## 📂 Project Structure

```plaintext
.
├── .ipynb_checkpoints/
├── gif/
│   ├── Clusters-3D.gif
│   └── Clusters-3D-500.gif
├── Color Quantization using K-Means Clustering.ipynb
├── KMeansClustering.ipynb
└── README.md
```


## 📘 Notebooks Overview

### 📒 Color Quantization using K-Means Clustering.ipynb

This notebook loads an image and applies **K-Means clustering** to reduce the number of unique colors (a process known as color quantization). It visualizes the original image alongside the quantized version, and can optionally generate animated GIFs to show clustering effects.

Key features:
- Read and display images using `OpenCV` and `matplotlib`
- Reshape image data for clustering
- Apply K-Means with a user-defined number of clusters
- Reconstruct the quantized image using cluster centroids
- Save output or create GIFs using `imageio`


### 📘 KMeansClustering.ipynb

![3D Clustering](gif/Clusters-3D.gif)

A beginner-friendly notebook that walks through the application of **K-Means clustering** on the classic **Iris dataset**.

Highlights:
- Data loading using `scikit-learn`
- 2D and 3D visualization of clustered data
- Step-by-step explanation of clustering mechanics
- Visual exploration of how K-Means separates different species of Iris flowers

Useful for understanding the intuition behind clustering before applying it to images.

---
