# UNet-for-hippocampus-MRI-segmentation

* DESCRIPTION OF TASK: To create a method for automatic segmentation of hippocampus glands based on MRI slices using U-Net architecture.
* DESCRIPTION OF DATASET: The dataset used in this research is obtained from research conducted by Boccardi et al.[1], and accessed through Kaggle platform [2]. The dataset contains MRI from 135 Alzheimer patients, as well as their corresponding mask of hippocampus glands, done by using Hippocampal Harmonized Protocols (HHP) with a slice thickness of 1.2 mm in sagittal orientation [1]
* METHODS: This work will use U-Net CNN architecture to perform the segmentation, with the flow is as follows:
  - Data collection, cleaning & preprocessing
  - Model creation & training
  - Model testing
  - Repeat for experimenting with model complexity & hyperparameters

REFERENCES:
1. M. Boccardi, M. Bocchetta, R. Ganzola, N. Robitaille, A. Redolfi, S. Duchesne, et al. Operationalizing protocol differences for EADC-ADNI manual hippocampal segmentation. Alzheimers Dement. 11: 2015; 184–194
2. Saber Malekzadeh. (2019). MRI Hippocampus Segmentation [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DS/400588
