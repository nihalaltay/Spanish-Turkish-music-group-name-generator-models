# **Spanish-Turkish Music Group Name Generator Models**  

This repository contains **character-level language models** trained to generate **music band names** in **Spanish and Turkish**. The project explores how **model size impacts performance**, comparing a **larger model (higher embedding size and hidden layers)** with a **smaller model** on a **limited dataset**. The models were trained using **PyTorch**, inspired by **Andrej Karpathy’s character-level language model**.  

## **Features**  
 **Dataset**: 305 Spanish and 268 Turkish band names  
 **Two model variations**: Large vs. small architecture comparison  
 **Evaluation**: Native speaker assessment of generated names  
 **Analysis**: Impact of model size on generalization and overfitting  

## **Installation & Dependencies**  
To run the code, you need the following Python libraries:  

```python
import pandas as pd  
import torch  
import torch.nn.functional as F  
import matplotlib.pyplot as plt  # for generating visualizations  

%matplotlib inline  # (For Jupyter Notebook users)
```  

You can install the required dependencies using:  
```bash
pip install pandas torch matplotlib
```  
