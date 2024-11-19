# **GAN Experimental Project**

Welcome to the **GAN Experimental Project** GitHub repository! This project was created as an experimental learning initiative to explore the capabilities of Generative Adversarial Networks (GANs) with a limited number of image samples. Below, you'll find all the necessary information to understand, use, and contribute to the project.

## **Table of Contents**
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Technologies Used](#technologies-used)


## **Overview**
The **GAN Experimental Project** aims to train GANs with a very small dataset (around 100 samples) to generate realistic images. This approach can be particularly useful for data augmentation in scenarios where there are limited samples available for training a classifier. The project experiments with Wasserstein GANs and Adaptive Data Augmentation, demonstrating the potential of these techniques even with limited computational resources.

## **Features**
- **Small Sample Training**: Train GANs with a dataset as small as 100 images to generate realistic outputs.
- **Wasserstein GAN**: Implement and experiment with Wasserstein GAN for better training stability.
- **Adaptive Data Augmentation**: Use adaptive data augmentation to improve the diversity of generated images.
- **Data Augmentation for Classifiers**: Generate additional images to augment datasets with limited samples, aiding in classifier training.

## **Usage**
- **Train the GAN**: Use the provided training script to train the GAN model:
  ```bash
  python train_gan.py
  ```
- **Set Parameters**: Modify the parameters in the script to experiment with different GAN settings, such as the number of epochs or the batch size.
- **Generate Images**: After training, generate new images by running the generation script:
  ```bash
  python generate_images.py
  ```

## **Technologies Used**
- **Generative Adversarial Networks (GANs)**: Used to generate realistic images from a small dataset.
- **Wasserstein GAN (WGAN)**: Implemented to enhance stability during training.
- **Adaptive Data Augmentation**: Utilized to improve training results with a limited dataset.
- **Programming Language**: Python (with popular libraries such as TensorFlow/PyTorch for deep learning).


## **Contact**
If you have any questions or suggestions, feel free to reach out:
- **GitHub**: [DCODE-ARMY](https://github.com/DCODE-ARMY)

Thank you for exploring the **GAN Experimental Project**! We hope it helps you understand GANs, data augmentation, and the potential of working with limited datasets. If you find this project helpful, don't forget to give it a star! ⭐

