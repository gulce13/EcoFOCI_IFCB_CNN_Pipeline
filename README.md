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

### PyIFCB Environment (For Deploying and Monitoring Classifiers)

To create and activate the PyIFCB environment, run:

```bash
conda env create -f environments/environment-pyifcb.yml
conda activate pyifcb-env

```

### PyTorch Environment (For Segmentation and Trait Extraction)

To create and activate the PyTorch GPU-enabled environment, run:

```bash
conda env create -f environments/environment-pytorch.yml
conda activate ifcb-gpu-env

```

