# Linear Algebra Applications in Data and Image Processing

This repository contains implementations of advanced **Linear Algebra (LA) concepts** applied to clustering and image processing tasks. The work is organized into two phases, each in its own directory: `Phase1` and `Phase2`.

## Phase 1 – Spectral Clustering

* **Objective:** Implement spectral clustering from scratch and apply it to graphs and kNN circles.
* **Description:**

  * Construct similarity, adjacency, and degree matrices (with and without kNN).
  * Perform eigenvalue and eigenvector analysis of the similarity matrix.
  * Reduce dimensionality and cluster data using KMeans.
* **Key Concepts:** Spectral clustering, dimensionality reduction, eigen decomposition, graph-based clustering.

## Phase 2 – Image Compression and Denoising

* **Objective:** Explore basis transformation techniques for image compression and denoising.
* **Description:**

  * Apply **Singular Value Decomposition (SVD)** and **2D-Fast Fourier Transform (FFT)** to compress and denoise grayscale images.
  * Evaluate reconstruction quality and performance across different ranks, frequencies, and compression rates.
  * Investigate self-supervised approaches to retain essential image information while reducing noise.
* **Key Concepts:** Basis transformations, rank approximation, low-pass filtering, image compression, image denoising.

## Structure

```
/Phase1
    └── Spectral_Clustering.ipynb
/Phase2
    └── Image_Compression_Denoising.ipynb
README.md
```

## Highlights

* Implemented core linear algebra techniques from scratch.
* Applied theoretical concepts to real-world datasets and digital images.
* Demonstrates practical applications of LA in machine learning and signal processing.