---
title: "Deep Learning Image Regression"
excerpt: "This project is for one of my Master's Courses, where I build an image Regression model.<br/><img src='/images/DL_IR.png'>"
collection: portfolio
---

The task for this project was to use a dataset containing a total of 1027 images of trays containing different foods, with a spatial dimension of 3264 x 2448 pixels in RGB. For each image, the percentage of pixels containing food was calculated.

Based on these (image, percentage) pairs, models based on Convolutional Neural Networks (CNNs) were defined and trained to provide the percentage of food pixels in a given image.

The quality of the models was estimated using the **Root Mean Square Error (RMSE)** error metric.

Specifically, three approximations were implemented and compared with a baseline with an RMSE of 4.8.

The models had to be implemented using the `keras` module form the library `TensorFlow`.


All the code can be found in my Repository: [ImageDLRegression](https://github.com/PerezDavid-98/ImageDLRegression) in the `ImageDLRegression.ipynb` Jupyter Notebook. Every step is explained (In Spanish) and reasoning for every decision is provided.

The README of the repository gives an overall explanation (in English) for the entire project. 

Additionally, a full report for this task can be read (in Spanish) in the [PDF file](https://github.com/PerezDavid-98/ImageDLRegression/blob/main/Deep%20Learning%20Image%20Regression.pdf) in the same repository.