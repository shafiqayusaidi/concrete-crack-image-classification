# concrete-crack-image-classification

# SUMMARY

This project is mainly to classify concrete crack images using convolutional neural network to evaluate whether the images has cracks or not. if there is a presence of cracks, it means the image is positive and vice versa. The analysis is also done to make predictions from the images. The model is trained with 40,000 images whereby 20,000 concrete images is in good condition and another 20,000 concrete images with cracks. The dataset is obtained from https://data.mendeley.com/datasets/5y9wdsg2zt/2

The model is trained using MobileNetV2 with transfer learning. The model is trained at epochs 10 with a learning rate od 0.0001. From the analysis, the model trained shows an acurracy of 99%. This means the model is almost perfectly trained with the large dataset.

<img width="557" alt="Screenshot 2022-04-29 at 01 16 33" src="https://user-images.githubusercontent.com/58509210/165809581-543955fb-a506-4e35-8c05-22fe57d4aacb.png">

The image predictions are shown below. The predictions are all accurate and correctly classified the images with cracks and no cracks.

![Uploading Screenshot 2022-04-29 at 01.17.16.png…]()
