## Environment Setup
```powershell
conda create --name DataMiningAndExploration
conda activate DataMiningAndExploration
conda install mkl-service
conda install mkl
conda install -c anaconda ipykernel nbconvert
python -m ipykernel install --user --name=DMaE
```
NNaDL = Neural Networks and Deep Learning <br>
**Switch to DMaE kernel in Jupyter Notebook**

## Contents
#### 1. Principal Component Analysis. [View]()
- analysis of PCA data transformation technique
- dimensiality reduction using PCA
- analysis of the variancy expalined by principal components
- optimal amount of principal components based on scree plot
- eigenfaces based of LFW model