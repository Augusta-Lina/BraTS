# BraTS Tumour Segmentation

This repository contains code for building and evaluating machine learning models that segment tumour regions in brain MRI scans. The project focuses on developing and comparing different loss functions and exploring the potential of unsupervised pretraining using unlabelled data.

The research evaluates Convolutional Neural Networks (CNNs) and U-Net architectures for tumour segmentation in MRIs of glioma patients. The modelling process is structured into three main phases:

1. **Exploration of loss functions**
2. **Comparison of network architectures**
3. **Fine-tuning with unsupervised pretraining**

## Project Structure

This research is divided across four notebooks which are intended to be read in order:

* `0_Problem_Formulation_&_Data_Preprocessing`: Introduces the dataset and defines the segmentation problem.
* `1_Phase_1_Baseline_Model_&_Loss_Functions`: Implements a baseline CNN and evaluates multiple loss functions.
* `2_Phase_2_Architectures`: Experiments with architectural variants including U-Net.
* `3_Phase_3_Unsupervised_Pretraining,_Fine_Tuning_&_Test_Set_Evaluation`: Introduces pretraining on unlabelled data and evaluates final model performance on the test set.

The segmentation task is treated as a multi-class classification problem, where each pixel is assigned to one of four classes: healthy brain tissue or one of three tumour subregions.

A summary of the work is also included in the accompanying poster.

## References

1. Menze, B. H., et al. (2015). *The Multimodal Brain Tumor Image Segmentation Benchmark (BRATS)*. IEEE Transactions on Medical Imaging, 34(10), 1993–2024. [https://doi.org/10.1109/tmi.2014.2377694](https://doi.org/10.1109/tmi.2014.2377694)
2. Bakas, S., et al. (2017). *Advancing The Cancer Genome Atlas glioma MRI collections with expert segmentation labels and radiomic features*. Scientific Data, 4(1). [https://doi.org/10.1038/sdata.2017.117](https://doi.org/10.1038/sdata.2017.117)
3. Bakas, S., et al. (2018). *Identifying the Best Machine Learning Algorithms for Brain Tumor Segmentation...* arXiv. [https://doi.org/10.48550/arxiv.1811.02629](https://doi.org/10.48550/arxiv.1811.02629)
4. Liu, T. T. (2020). *MRI in systems medicine*. Wiley Interdisciplinary Reviews: Systems Biology and Medicine, 12(1). [https://doi.org/10.1002/wsbm.1463](https://doi.org/10.1002/wsbm.1463)
5. Singh, K. U., et al. (2022). *A Robust NIfTI Image Authentication Framework...*. IEEE Access, 10, 132608–132620. [https://doi.org/10.1109/access.2022.3225908](https://doi.org/10.1109/access.2022.3225908)
6. Bonato, B., Nanni, L., & Bertoldo, A. (2025). *Advancing Precision: A Comprehensive Review of MRI Segmentation Datasets from BraTS Challenges (2012–2025)*. Sensors, 25(6), 1838. [https://doi.org/10.3390/s25061838](https://doi.org/10.3390/s25061838)
7. Holbrook, M., et al. (2020). *MRI-Based deep learning segmentation and radiomics of sarcoma in mice*. Tomography, 6, 23–33. [https://doi.org/10.18383/j.tom.2019.00021](https://doi.org/10.18383/j.tom.2019.00021)

