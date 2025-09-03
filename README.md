# ISIC2018
This repo refers to the International Skin Imaging Collaboration (ISIC) 2018 challenge for diagnosis of skin cancer through dermoscopic images.<br>
The data and further information on the ISIC challenge can be found through the link <a href="https://challenge.isic-archive.com/landing/2018/">ISIC Archive - Challenges</a>.<br>

## Task 3
Classification of skin lesion across 7 categories: MEL (melanoma), NV (melanocytic nevus), BCC (basal cell carcinoma), AKIEC (actinic keratosis / Bowen’s disease), BKL (benign keratosis), DF (dermatofibroma), and VASC (vascular lesion).<br>
The goal of the classification is to provide specific information and treatment options for a lesion, and detect skin cancer with a reasonable sensitivity and specificity.<br>
Task 3 of the challenge provided 10,015 images as training dataset for the model, 193 images for validation and 1,512 images for testing. Those are available in the page <a href="https://challenge.isic-archive.com/data/#2018">ISIC Archive - Data</a>.<br><br>
The project contains the following folders/files for this task:
- <a href="https://github.com/isaqueiros/ISIC2018/blob/main/ISIC2018_Task3_Data_Analysis.ipynb">Data_Analysis</a>: this file reports on medical understanding and analysis of the data provided, including the image dataset and the separated ground truth data provided by ISIC.
- <a href="https://github.com/isaqueiros/ISIC2018/tree/main/model_experiments">model_experiments</a>: this folder holds the different experiments of each model, including models from the families EfficientNet, ResNet, InceptionResNet and DenseNet, as well as Transformer-based architectures and hybrid models.
- <a href="https://github.com/isaqueiros/ISIC2018/tree/main/model_experiments/model_optmisation">model_experiments/model_optimisation</a>: this folder holds the experiments involving bayesian optmisation technique application for selection of hyperparameters for each of the models studied.
- <a href="https://github.com/isaqueiros/ISIC2018/tree/main/modular_build">modular_build</a>: this folder provides a modular build with data preprocessing, model build and model training, supporting model implementation and maintainability.