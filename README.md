# CMPE-255-Dimensionality-Reduction-Techniques
1: This repository contains colab for various techniques of dimensionality reductiont.<br />
2: The 2 dataset used are Wine dataset for tabular dataset from Kaggle.com and is saved in the same repository in csv file and the other one is Digits which is image dataset from sklearn dataset.<br />
3: The colab file can be easily opened using the 'Open in Colab button'.<br />
4: It also contains descriptive comments in each step to describe the process.<br />
5: The conclusion of the analysis for Tabular dataset is:<br/>
  1.UMAP outperformed all the techniques as it is very effective for visualization and its speed is better compared to others.<br />

  2.Principal Component Analysis: This is most widely used techniques for dealing with linear data. It divides the data into a set of components which try to       explain as much variance as possible.<br />
  3.ISOMAP: We use this technique when the data is strongly non-linear.<br />
  4.t-SNE: This technique also works well when the data is strongly non-linear. It works extremely well for visualizations as well.<br />
  5.UMAP: This technique works well for high dimensional data. Its run-time is shorter as compared to t-SNE.<br />

6: he conclusion of the analysis for Image dataset is:<br/>
  PCA and SVD couldn't perform well for this dataset because its a high dimensional dataset with good number of important features to define the dataset. On the other hand T-SNE did a good job as compared to PCA when it comes to visualizing the cluster. UMAP outperformed all the techniques as it is very effective for visualization and its speed is better compared to others.
