# **NOAA IFCB Technical Memo Book**

*Author: Gulce Kurtay, Valentina Staneva (2025)*

This book includes Jupyter notebooks that align with the NOAA IFCB Technical Memo. It documents workflows for managing, processing, and analyzing IFCB image data.

## Contents

- Data Access and Storage
- Regional Classifier Development through Transfer Learning  
- Deploying and Monitoring Classifiers 
- Segmentation and Trait Extraction

## How to Use This Book

- Browse the chapters on the left sidebar.
- Build the book locally by running:

  ```bash
  jupyter-book build .

---

## Setting Up Your Environments

This project uses multiple conda environments to run different parts of the workflow.

### IFCB Predict Environment (For Deploying and Monitoring Classifiers)

To create and activate the ifcb_predict environment, run:

```bash
conda create -n ifcb_predict python=3.10.12
conda activate ifcb_predict
```

Then, navigate to the folder containing the requirements file and install the dependencies:

```bash
cd "C:\Desktop\IFCB-image-data-process\environments"
pip install -r ifcb_predict2.txt
```

### PyTorch Environment (For Segmentation and Trait Extraction)

To create and activate the PyTorch GPU-enabled environment, run:

```bash
conda env create -f environments/environment-pytorch.yml
conda activate ifcb-gpu-env

```

