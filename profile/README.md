# Multimodal Fusion Models for Healthcare

In this project, we build a model for cardiovascular disease (CVD) diagnostic using different healthcare data modalities such as genomics, MRI scans, clinical notes, ECG etc.

The basic idea is to use pre-trained models that are publicly available for each data modality and fine-tune them, then combine the features to make the final diagnostic decisions. You can learn more about deep learning data fusion for example from [this paper](https://www.nature.com/articles/s41746-020-00341-z).  

To evaluate the performance of our method, we use [the Coherent dataset (2022)](https://www.researchgate.net/publication/359859530_The_Coherent_Data_Set_Combining_Patient_Data_and_Imaging_in_a_Comprehensive_Synthetic_Health_Record) as the test dataset. The Coherent dataset is a synthetic dataset that includes familial genomes, magnetic resonance imaging (MRI), clinical notes, and physiological (ECG) data. The data modalities are linked together using the HL7 Fast Healthcare Interoperability Resources (FHIR).