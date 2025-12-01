# UNet & Attention UNet for hippocampus MRI segmentation

* DESCRIPTION OF TASK: To create a method for automatic segmentation of hippocampus glands based on MRI slices using U-Net architecture.
* DESCRIPTION OF DATASET: The dataset used in this research is obtained from research conducted by Boccardi et al.[1], and accessed through Kaggle platform [2]. The dataset contains T1-weighted MRI images from 135 Alzheimer patients, as well as their corresponding mask of hippocampus glands, done by using Hippocampal Harmonized Protocols (HHP) with a slice thickness of 1.2 mm in sagittal orientation [1]
* METHODS: Tthe flow is as follows:
  - Data handling: cleaning & mask alignment, contrast enhancement & normalization, patient-level split, data augmentation
  - Model creation & training: basic UNet & attention UNet
  - Model testing
  - K-fold crossvalidation
  - Repeat for experimenting with model complexity & hyperparameters
 
# Snippet of the results (trained in 30 epoch):
## UNet
<img width="1208" height="684" alt="image" src="https://github.com/user-attachments/assets/a79ff4ca-e52f-4074-a5f4-ceca71771544" />

## Attention UNet
<img width="1215" height="685" alt="image" src="https://github.com/user-attachments/assets/43dd6d92-1d98-406b-8ff9-9efeef7216dd" />



# REFERENCES:
1. Boccardi, M., Bocchetta, M., Morency, F. C., Collins, D. L., Nishikawa, M., Ganzola, R., Grothe, M. J., Wolf, D., Redolfi, A., Pievani, M., Antelmi, L., Fellgiebel, A., Matsuda, H., Teipel, S., Duchesne, S., Jack, C. R., Jr, Frisoni, G. B., & EADC-ADNI Working Group on The Harmonized Protocol for Manual Hippocampal Segmentation and for the Alzheimer's Disease Neuroimaging Initiative (2015). Training labels for hippocampal segmentation based on the EADC-ADNI harmonized hippocampal protocol. Alzheimer's & dementia : the journal of the Alzheimer's Association, 11(2), 175–183. https://doi.org/10.1016/j.jalz.2014.12.002
2. Saber Malekzadeh. (2019). MRI Hippocampus Segmentation [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DS/400588 (https://drive.google.com/file/d/1KsSlV8msaQNOE3FMTsM9OjUEJdPh2OQr/view?usp=drive_link)
