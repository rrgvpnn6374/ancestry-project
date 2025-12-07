\# Genetic Ancestry Prediction (Unsupervised Learning)



\## 📌 Project Overview

This project applies \*\*Unsupervised Machine Learning\*\* techniques to genetic data from the \*\*1000 Genomes Project\*\*. The goal was to rediscover human ancestry groups without using labeled data.



By analyzing single nucleotide polymorphisms (SNPs), I successfully identified distinct population clusters that align with historical geographic separation.



\## 📊 Key Results

\- \*\*Dimensionality Reduction:\*\* PCA successfully captured ancestral variance in just 2 components.

\- \*\*Clustering:\*\* K-Means clustering identified \*\*3 distinct groups\*\* with a Silhouette Score of \*\*0.572\*\*.

\- \*\*Evolutionary Validation:\*\* Hierarchical clustering produced a dendrogram that reflects the "Out of Africa" migration and subsequent population splits.



\## 🛠️ Tech Stack

\- \*\*Language:\*\* Python 3.x

\- \*\*Libraries:\*\* Pandas, NumPy, Scikit-Learn, SciPy, Seaborn, Matplotlib

\- \*\*Data Source:\*\* \[1000 Genomes Project](https://www.internationalgenome.org/) (Subset)



\## 📂 Project Structure

\- `genetics\_analysis.ipynb`: The main Jupyter Notebook containing all EDA and modeling.

\- `images/`: Saved visualizations (PCA, Dendrograms).



\## 🚀 How to Run

1\. Clone the repository:

&nbsp;  ```bash

&nbsp;  git clone \[https://github.com/YOUR\_USERNAME/ancestry-project.git](https://github.com/YOUR\_USERNAME/ancestry-project.git)

