# Fashion_MNIST_Classification
1. Fashion Label Classification using CNN:
- A Convolutional Neural Network (CNN) model was developed for fashion label classification.
- Through hyperparameter tuning, the network architecture was optimized, resulting in a test accuracy of 94%.
  
2. Identifying Mystery Labels using Intermediate Layer Encodings:
- Encodings from the intermediate layer of a CNN model were utilized to uncover unidentified labels within the dataset.
- Dimensionality reduction techniques like Principal Component Analysis (PCA) were applied to reduce the dimensionality of the encodings.
- Clustering algorithms such as K-means and DBSCAN were employed for unsupervised classification, enabling grouping of similar encodings. This process facilitated the identification and classification of the mystery labels in the dataset.

3. Feature Extraction and Representation Analysis:
- PCA and Autoencoder were compared for dimensionality reduction to analyze the effectiveness of feature extraction techniques.
- Autoencoder was found to generate the most effective representation, as evidenced by improved classification test accuracy when combined with a K-nearest neighbors (KNN) classifier.
This suggests that the Autoencoder model extracted more informative and discriminative features for accurate classification.

