# Brain tumor prediction project

## Our Presentation
[Presentation](https://github.com/MostafaNabiehMourad/Brain-tumor-prediction-project/blob/main/Brain.pdf)


## Introduction / Motivation
Brain tumor is one of the most dangerous diseases which require early , and accurately detection methods.

Now most detection and diagnosis methods depend on decision of neurospecialists, and radiologist for image evaluation which possible to human error and time consuming.

The main purpose of this project is to build a robust CNN model that can classify if the subject has a tumor or not based on Brain MRI scan images with an acceptable accuracy for medical grade application

## What is Brain Tumor?
A brain tumor occurs when abnormal cells form within the brain.

### There are two main types of tumors:
Cancerous (malignant) tumors and benign tumors.

Cancerous tumors can be divided into primary tumors, which start within the brain, and secondary tumors, which have spread from elsewhere, known as brain metastasis tumors.

All types of brain tumors may produce symptoms that vary depending on the part of the brain involved.

## Some Image from the 3D-Dataset
![89139468-07e00800-d53f-11ea-9ff0-744e04cc3edd](https://user-images.githubusercontent.com/81525051/139526154-7d26f2fd-07ba-4a78-b396-7fe17162b6b7.gif)

## Image Preprocessing
![89139836-4629f700-d540-11ea-98c3-6070c7e01d99](https://user-images.githubusercontent.com/81525051/139526247-36f2d551-ceb1-48f7-8a44-d5ea620c094a.png)

## Data Augmentation
We used the "ImageDataGenerator“ provided by Keras among other technologies for data augmentation.

* Rotation range,
* Width shift range,
* Height shift range,
* Brightness range,
* Horizontal flip and Vertical flip

## Brain Tumor Detection 3D-Models :: 3D Dataset ::
What is Autoencoder: Autoencoders (AE) are neural networks that aims to copy their inputs to their outputs.
Encoder: This is the part of the network that compresses the input into a latent-space representation. It can be represented by an encoding function h=f(x).

Decoder: This part aims to reconstruct the input from the latent space representation. It can be represented by a decoding function r=g(h).
![89140147-192a1400-d541-11ea-8077-6aba61a56dbc](https://user-images.githubusercontent.com/81525051/139526277-98d999e3-5763-4539-af3a-644b74d8947f.png)
