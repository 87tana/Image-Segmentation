# Segmentation in Medical Imaging

### Studied segmentation network

<div align="center">
    <img width="800" src="/Images/ResNet-18 Segmentation Network.png" alt="Material Bread logo">
    <p style="text-align: center;">Figure 1: CNN architecture for brain tumor segmentation task. Created by author.</p>   
</div>

### Aim of study

In this study, we explore the effectiveness of deep learning techniques for image semantic segmentation, focusing on their practical impact on a specialized dataset. We utilized several prominent neural network architectures as encoders, including ResNet-18, ResNet-34, ResNet-50, and VGG16, to assess the influence of network depth on segmentation accuracy. To optimize the decoding process, we varied the number of up-sampling layers and increased the complexity of our models by adding additional convolutional layers within the decoder structures, aiming to enhance the model's ability to reconstruct detailed segmentation maps from feature compressions.

<div align="center">
    <img width="800" src="/Images/ec_cnn_mri.png" alt="Material Bread logo">
    <p style="text-align: center;">Figure 2: CNN architecture for brain tumor segmentation task. Created by author.</p>   
</div>

### Dataset

The dataset, sourced from [kaggle](https://www.kaggle.com/datasets/pkdarabi/brain-tumor-image-dataset-semantic-segmentation), consists of 2146 images with tumors annotated in COCO Segmentation format. It's part of the TumorSeg Computer Vision Project, which focuses on Semantic Segmentation and aims to accurately identify tumor regions within Medical Images using advanced techniques


### Results


<div align="center">
    <img width="800" src="/Images/final.png" alt="Material Bread logo">
    <p style="text-align: center;">Figure 3: CNN architecture for brain tumor segmentation task. Created by author.</p>   
</div>


<div align="center">
    <img width="800" src="/Images/table.png" alt="Material Bread logo">
    <p style="text-align: center;">Figure 4: CNN architecture for brain tumor segmentation task. Created by author.</p>   
</div>
  




 

