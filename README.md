# Kernel Fusion Method for Detecting Cancer Subtypes via Selecting Relevant Expression Data
 
In this paper, we first extrect gene expression, miRNA expression and isoform expression of five novel datasets from The Cancer Genome Atlas (TCGA). Next, to avoid the effect of noise existing in 60483 genes, we select a small number of genes by using the method of LASSO that employs gene expression and survival time of patients. Then, we construct a similarity kernel for each expression data by using Chebyshev distance. And we combine three similarity kernels into one synthetical kernel by using Similarity Kernel Fusion (SKF). Finally, Spectral Clustering is applied to predict the clustering results for cancer subtypes. In the experimental results, our method has better P value in the Cox model than other methods on ten datasets. The difference between survival curves based on the experimental results is also obvious on each cancer, and some important genes are also found
to have an significant impact on cancer subtypes. 

The complete flow chart is as follows

![image](https://github.com/guofei-tju/Kernel-Fusion-Method-for-Detecting-Cancer-Subtypes-via-Selecting-Relevant-Expression-Data/blob/master/img/SS.jpg)
