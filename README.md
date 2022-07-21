## Environment Setup
```powershell
conda create --name DataMiningAndExploration
conda activate DataMiningAndExploration
conda install mkl-service
conda install mkl
conda install -c anaconda ipykernel nbconvert
python -m ipykernel install --user --name=DMaE
```
DMaE = Data Mining and Exploration <br>
**Switch to DMaE kernel in Jupyter Notebook**

## Contents
#### 1. Principal Component Analysis. [View](https://github.com/Smendowski/data-mining/blob/main/%5B1%5D%20Principal%20Component%20Analysis.ipynb)
- analysis of PCA data transformation technique
- dimensiality reduction using PCA
- analysis of the variancy expalined by principal components
- optimal amount of principal components based on scree plot
- eigenfaces based on LFW model

#### 2. Decision Trees and k-NN. [View](https://github.com/Smendowski/data-mining/blob/main/%5B2%5D%20Decision%20Trees%20and%20k-NN.ipynb)
- Decision Trees
- k-fold Cross Validation
- Optimal tree depth based on different criterion
- Decision Tree pruning
- Classification using DT and k-NN