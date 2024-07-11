# Skin-cancer-classification-with-augmented-datasets-from-generative-adversarial-networks

baseline.ipynb

This file contains the code to test the baseline CNN performance. It contains commented model designations (ResNet50, InceptionResNetV2, VGG-19) and seed information (42, 442, 4442, 422, 4222) for ease of use.

gan-fitzpatrick.ipynb

This file contains the GAN to generate the sythetic data. It also contains a random sampling of 10 images to be evaluated on the Structural Similarity Index (SSIM). The generated data can then be easily transfered to a dataset file.

graphs.ipynb

This file contains the code with manual performance metrics for generating graphs and figures.

semi-supervised-model.ipynb

This file cntains the semi-supervised learning approach to use on the synthetic and original data. It contains a label propagation step to deal with the unlabeled synthetic data. It still contains the seeding informataion and easy model changes, built upon ResNet50, InceptionResNetV2, and VGG-19.
