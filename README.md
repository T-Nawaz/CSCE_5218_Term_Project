# EmojiBert
## CSCE 5218 Term Project Group 2

# Running this Notebook Locally

This document provides step-by-step instructions to run this notebook on your local machine.

## Prerequisites

- Python 3.8+ installed
- pip (Python package installer)
- Git installed
- Jupyter Notebook or JupyterLab installed (optional - you can install this in step 2)

## Step 1: Clone the Repository

Open a terminal or command prompt and run:

```
git clone https://github.com/T-Nawaz/EmojiBert.git
cd EmojiBert
```

## Step 2: Set Up a Virtual Environment (Recommended)
```
python -m venv venv
```

### Activate the virtual environment
#### For Windows:
```
venv\Scripts\activate
```
#### For macOS/Linux:
```
source venv/bin/activate
```

## Step 3: Install Required Dependencies
```
pip install -r requirements.txt
```
If requirements.txt is not available, install these packages individually:
```
pip install pandas numpy scikit-learn matplotlib seaborn requests
pip install torch torchvision
pip install transformers
pip install jupyter
```
## Step 4: Launch Jupyter Notebook
```
jupyter notebook
```
### This will open Jupyter in your default web browser. Navigate to and open the notebook file TermProjectDL.ipynb

## Step 5: Run the Notebook
Once the notebook is open:
* Select "Kernel" > "Restart & Run All" to execute all cells from the beginning
* Or run each cell individually by selecting it and pressing Shift+Enter

### Troubleshooting
* If you encounter CUDA-related errors but don't have a GPU, the code will automatically fall back to CPU
* For memory issues, consider reducing batch sizes in the model training sections
* Make sure all data paths referenced in the notebook are correct

