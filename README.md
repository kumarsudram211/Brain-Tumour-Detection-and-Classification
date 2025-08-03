**Brain-Tumor-Detection-Using-Deep-Learning-MRI-Images-Detection-Using-Computer-Vision**
Datset used has been taken from the kaggle and below is its link
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa2ItNmc3bUs2SDBJM2JCUUx3eWN4OHowYmYtd3xBQ3Jtc0trMERScUgtNzVaWXpMc3NsME00ZTEtOUxUSi1yRGpKRE5NbkI3Tm5vVjdNYXl5d3pmakhnSXN3cVBld3U4dlVtOE1yVTZKVHBPandlaFdDa3QtWnQ4SmIzaUFINGFxay1KdlhoZFBZTFJLbXZJc3JrZw&q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fmasoudnickparvar%2Fbrain-tumor-mri-dataset&v=MTQQnziWGQY

Transfer Learning using VGG16
The model leverages the pre-trained VGG16 architecture as a feature extractor. The top layers were customized to adapt to the specific classification task. The convolutional base was frozen initially to retain learned weights from ImageNet, followed by fine-tuning of upper layers for better performance on the target dataset
