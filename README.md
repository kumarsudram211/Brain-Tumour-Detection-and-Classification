**Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision**
Datset used has been taken from the kaggle and below is its link
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
Transfer Learning using VGG16
The model leverages the pre-trained VGG16 architecture as a feature extractor. The top layers were customized to adapt to the specific classification task. The convolutional base was frozen initially to retain learned weights from ImageNet, followed by fine-tuning of upper layers for better performance on the target dataset
