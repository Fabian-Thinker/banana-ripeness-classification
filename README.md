## Dataset
The dataset consists of images categorized into four classes and is divided into training, validation, and testing sets.  
**Dataset Source:** [Link to Dataset](https://universe.roboflow.com/roboflow-universe-projects/banana-ripeness-classification/dataset/4)  

## Setup Environment

This project uses two separate environments:
1. **`train-env`** → Used for training the model with GPU.
2. **`tfjs-env`** → Used for saving and converting the model.

### **1. Create and Activate the Training Environment (`train-env`)**
```
conda create --name train-env python=3.10
conda activate train-env
pip install -r requirements-train.txt
```
### **2. Create and Activate the TensorflowJS Environment (`tfjs-env`)**
```
conda create --name tfjs-env python=3.10
conda activate train-env
pip install -r requirements-tfjs.txt
```
