# Feature Imitating Networks Enhance the Performance, Reliability and Speed of Deep Learning on Biomedical Image Processing Tasks
**Published in the 2024 46th Annual International Conference of the IEEE Engineering in Medicine & Biology Society**

Authors: Shangyang Min, Hassan B. Ebadian, Tuka Alhanai, Mohammad M. Ghassemi

[See paper, here](https://www.dropbox.com/scl/fi/ysrq0n9l9i2v4twe0s61x/EMBC-FINS-Biomedical-Image-Processing.pdf?rlkey=qmkzpdp5irz0211kgo23y5sm3&dl=0)

## Overview:
Feature-Imitating-Networks (FINs) are specialized neural networks that first learn to replicate specific closed-form statistical features, such as Entropy. These networks are then incorporated into larger neural network architectures to potentially enhance their functionality. Our study marks the inaugural evaluation of FINs within the context of biomedical image processing. These findings suggest that FINs could significantly improve the state-of-the-art in various other biomedical image processing tasks. This opens up new pathways for research and practical applications in medical imaging fields.

## Overview of Repostiory Contents

* Tutorial.ipynb: Tutorial notebook demonstrating the setup, training, and application of FINs
* radiomics_training.ipynb: Contains code for training radiomics models. 
* random_topology.ipynb: Utility notebook to generate random topologies.
* Exps/
    * BrainMRIDectection.ipynb: Experiment code detects medical conditions from brain MRI scans.
    * Covid.ipynb: Experiment code detects COVID-19 from imaging data.

## Python Package Requirements

```
tensorflow
keras
pandas
matplotlib
cv2
glob
sklearn
pyradiomics
```

### Dataset
```
Dataset used are public available and can be download from [Kaggle](https://www.kaggle.com/datasets/mehradaria/covid19-lung-ct-scans/data), [TCIA](https://www.cancerimagingarchive.net/collection/tcga-lgg/)
```

## Cite

```
@inproceedings{min2024feature,
  title={Feature Imitating Networks Enhance the performance, Reliability and Speed of Deep Learning on Biomedical Image Processing Tasks},
  author={Min, Shangyang and Ebadian, Hassan B. and Alhanai, Tuka and Ghassemi, Mohammad M.},
  booktitle={Proceedings of the 46th Annual International Conference of the IEEE Engineering in Medicine and Biology Society}
}

```
