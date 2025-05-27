# XCA-preprocessing

### X-ray coronary angiography (XCA) is a medical imaging method widely used for diagnosing and treating coronary heart disease (CHD). In recent years, the use of machine learning models, such as convolutional neural networks (CNNs) and transform-based models, for detecting pathological structures in medical images has grown, driving the development of AI-powered computer-aided detection (CAD) systems.
### Vessel segmentation and lesion detection can be challenging, mainly due to highly noisy images, patient motion, and varying levels of contrast. Thus, image preprocessing is key to improving model training (by providing higher-quality data) and enhancing its predictions.
### In this notebook we explore diverse filters founded in literature, oriented to XCA images preprocessing.
### References:
#### Popov, M., Aimyshev, T., Ismailov, E., Bulegenov, A., & Fazli, S. (2022). A review of modern approaches for coronary angiography imaging analysis. arXiv preprint arXiv:2209.13997.
#### Nguyen-Tat, T. B., Hung, T. Q., Nam, P. T., & Ngo, V. M. (2025). Evaluating pre-processing and deep learning methods in medical imaging: Combined effectiveness across multiple modalities. Alexandria Engineering Journal, 119, 558-586.
#### Images were collected from ARCADE dataset: https://paperswithcode.com/dataset/arcade
