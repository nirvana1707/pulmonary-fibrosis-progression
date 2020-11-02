# Pulmonary Fibrosis Progression
## Introduction
This project was created as part of a Kaggle research competition: https://www.kaggle.com/c/osic-pulmonary-fibrosis-progression
The objective is to predict a patient’s severity of decline in lung function based on a CT scan of their lungs along with its metadata, and baseline FVC.

## Background
Pulmonary fibrosis is a disorder created by scarring of the lungs however without a particular cause and cure. It is important to have a prognosis whether it will be long-term stability to rapid deterioration, but it is difficult for doctors to ascertain this for an individual. Current methods make fibrotic lung diseases difficult to treat, even with access to a chest CT scan. In addition, the wide range of varied prognoses create issues organizing clinical trials. Finally, patients suffer extreme anxiety in addition to fibrosis-related symptoms from the disease’s opaque path of progression.

A scalable and accurate computer vision based methodolgy will help patients and their families better understand their prognosis when they are first diagnosed with this incurable lung disease. Improved severity detection would also positively impact treatment trial design and accelerate the clinical development of novel treatments.

## Dataset
Open Source Imaging Consortium (OSIC), a group that enables rapid advances in the fight against Idiopathic Pulmonary Fibrosis (IPF), fibrosing interstitial lung diseases (ILDs), and other respiratory diseases, including emphysematous conditions, has collated such datasets for radiologists, clinicians and computational scientists globally to improve imaging-based treatments.

## Methodology

The methodology consists of exploring an ensemble approach based on EfficientNet and quantile regression along with tuning of hyperparameters

## Results
The ensemble approach resulted in below scores:
-6.8245 in public leaderboard (Top 17%)
-6.8797 in private leaderboard (Top 8%)

Sample patient analysis:

![alt text](https://github.com/nirvana1707/pulmonary-fibrosis-progression/blob/main/images/patient_eda.PNG)

Example CT scan:
![alt text](https://github.com/nirvana1707/pulmonary-fibrosis-progression/blob/main/images/ctscans.PNG)

Image processing:
![alt text](https://github.com/nirvana1707/pulmonary-fibrosis-progression/blob/main/images/image_contrast.PNG)




