# BraTS2020_Segmentation

**Brain Tumor Segmentation:**

Brain tumor segmentation is the process of identifying and delineating tumor regions in medical images, typically MRI scans, to aid in diagnosis, treatment planning, and monitoring of disease progression. The complexity of brain tumor segmentation arises from the variations in tumor shapes, sizes, and locations, as well as the presence of surrounding structures with similar intensities, making manual segmentation challenging and time-consuming. Advanced techniques such as deep learning, especially convolutional neural networks (CNNs) and U-Net architectures, have shown promising results in automating the segmentation process. These models leverage spatial and contextual information from the MRI images to segment various tumor types and their sub-regions, such as enhancing tumor, edema, and necrotic core, which are crucial for treatment decisions and patient care.

**BraTS2020 Dataset:**

The Brain Tumor Segmentation Challenge (BraTS) 2020 dataset is a publicly available collection of multimodal MRI scans aimed at advancing the development of automated brain tumor segmentation methods. The dataset includes 3D images from 369 patients, each containing four different MRI modalities: T1-weighted, T1-weighted post-contrast (T1CE), T2-weighted, and Fluid Attenuated Inversion Recovery (FLAIR). It also includes corresponding ground truth tumor masks, which are annotated with tumor regions and labeled into different categories such as necrotic core, edema, and enhancing tumor. Here is the link to the dataset-https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation/data

**U-Net Architecture**

Here, we will use U-Net, a deep learning architecture specifically designed for semantic segmentation tasks, particularly in medical image analysis. It features a symmetric encoder-decoder structure where the encoder captures context through downsampling, and the decoder enables precise localization by upsampling. A distinctive feature of U-Net is the use of skip connections that link corresponding layers in the encoder and decoder, helping preserve fine-grained spatial details essential for accurate segmentation. U-Net is highly effective when working with limited training data, which is often the case in medical imaging, by utilizing data augmentation and its efficient design. It has become a widely-used model for tasks like organ segmentation, tumor detection, and other medical image analysis applications, offering high-resolution segmentation maps while maintaining computational efficiency.

References

1.https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation
2.https://github.com/bnsreenu/python_for_microscopists/tree/master/231_234_BraTa2020_Unet_segmentation
3.https://arxiv.org/abs/1505.04597
