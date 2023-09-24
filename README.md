# Implementing the CCT model to detect skin cancer

## Implementation challenge

Skin cancer is the most common human malignancy, frequently diagnosed by visual assessment, starting with an initial clinical screening, which may be followed by dermoscopic analysis, biopsy and histopathological examination. Automated lesion classification using images is a challenging task due to the fine-grained variability in lesion appearance.

The dataset was obtained from the ISIC (International Skin Imaging Collaboration) archive. It consists of 1,800 photos of benign moles and 1,497 photos of moles classified as malignant. Images were resized to low resolution RGB (224x224x3). The task of this nucleus is to create a model capable of visually classifying a spot as benign or malignant.

Given the balanced distribution of the dataset, the model will be evaluated based on the accuracy metric, expressed as (TP + TN)/(ALL).
