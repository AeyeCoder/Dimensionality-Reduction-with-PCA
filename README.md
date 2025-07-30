# Dimensionality-Reduction-with-PCA
Check out the code to see how exactly can you observe and greatly reduce the data size for reducing computational complexity especially by simple usage of PCA
154 components for ~80% is usually good enough for MNIST. You only need to go higher if you need near-lossless reconstruction.

This project demonstrates dimensionality reduction on the MNIST dataset using PCA (Principal Component Analysis). We first scale the data using StandardScaler, then apply PCA to reduce the dimensionality while preserving most of the variance. An elbow curve is plotted to visualize the cumulative explained variance across components. Based on this, we reconstruct the digits using a reduced number of components (e.g., 154 for ~80% variance). The project includes visual comparison between original and reconstructed digit images to show the effectiveness of PCA. All steps are implemented using scikit-learn and matplotlib.
