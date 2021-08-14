# Population Segmentation with SageMaker

Two unsupervised learning algorithms (PCA and k-means) are used to do population segmentation on US Census data. Population segmentation aims to find natural groupings in population data that reveal some feature-level similarities between different regions in the US.

Using principal component analysis (PCA), the dimensionality of the original census data is reduced. Then, k-means clustering is used to assign each US county to a particular cluster based on where a county lies in component space. How each cluster is arranged in component space can inform which US counties are most similar and what demographic traits define that similarity. 

Ref: Udacity ML Engineer Case Study Project
