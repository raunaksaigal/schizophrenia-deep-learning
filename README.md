# Identifying Schizophrenia Using Structural MRI With a Deep Learning Algorithm

![](https://img.shields.io/badge/Work_Under_Progress-Contribute_Now-red)

This project is primarily based on the research paper [Identifying Schizophrenia Using Structural MRI With a Deep Learning Algorithm](https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2020.00016/full)

### Instructions for Setup

Make sure to create a virtual environment (or not). Tensorflow, if to be used with GPU support should be setup in a conda environment with the proper version of Python, cuda toolit and cudnn. To download the dataset following commands need to be run:-

```
pip install -r requirements.txt
datalad install https://github.com/OpenNeuroDatasets/ds004302.git
cd ds004302
datalad get .

```

### Major Problems Needed to be Addressed

>- The first problem is the model is not performing well and is not recognizing any patterns.
>- The dataset does not have consistent imges with the same orientation of patients (refer to cell number 20 of main.py for the visual distinction).
>- Images need proper preprocessing for good feature extraction




_**Ping Me up on discord if you have something in your mind! `dot2003`**_