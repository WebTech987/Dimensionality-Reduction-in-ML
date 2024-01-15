# Dimensionality-Reduction-in-ML
Project Title : Mathematics Behind the ML dimensionality reduction techniques


Summary of Performance of Dimensionality Reduction Techniques on MNIST Dataset:

1. PCA (Principal Component Analysis):
   - PCA achieved decent results in reducing the dimensionality of the MNIST dataset.
   - It provided a visualization of the data in lower-dimensional space.
   - However, PCA had limitations in effectively separating different classes and capturing intricate patterns in the dataset.

2. KPCA (Kernel PCA):
   - KPCA, specifically using the polynomial kernel and RBF kernel, showed reconstruction errors for the MNIST dataset.
   - The reconstruction errors indicate the loss of information during dimensionality reduction.
   - KPCA did not perform as well as other methods in terms of preserving the structure and separability of the data.

3. Isomap:
   - Isomap performed well in preserving the structure and clustering of the MNIST dataset.
   - It generated a lower-dimensional representation that provided clearer boundaries between different classes.
   - Isomap outperformed PCA and KPCA in terms of capturing the intrinsic geometry and maintaining the inter-class separation.

4. t-SNE (t-Distributed Stochastic Neighbor Embedding):
   - t-SNE produced excellent results in visualizing the MNIST dataset.
   - It effectively separated different classes and clusters, leading to clear boundaries.
   - The t-SNE algorithm captured local relationships and preserved the intricate structure of the data.
   - The visualization provided by t-SNE highlighted the similarities and dissimilarities among data points.

In summary, among the evaluated dimensionality reduction techniques, Isomap and t-SNE demonstrated better performance compared to PCA and KPCA for the MNIST dataset. Isomap successfully preserved the structure and clustering of the data, while t-SNE excelled in capturing intricate patterns and producing clear visualizations. Both Isomap and t-SNE could be considered effective approaches for reducing the dimensionality of the MNIST dataset.


# Conclusion
This project aimed to explore and compare different dimensionality reduction techniques for image data analysis. We researched widely used algorithms, including Principal Component Analysis (PCA), Kernel PCA (KPCA), Isomap, and t-SNE, and implemented them from scratch in Python. The project involved understanding the mathematical concepts behind each algorithm and writing code to apply them to real-world image datasets. By experimenting with these techniques, we gained insights into their strengths and limitations in capturing and visualizing patterns in image data. We also evaluated their performance in terms of computational complexity and preservation of important features. This project showcases our ability to comprehend complex algorithms, implement them effectively, and analyze their impact on image data. It demonstrates our skills in both theoretical understanding and practical application, making us well-equipped to tackle dimensionality reduction challenges in image analysis tasks.
