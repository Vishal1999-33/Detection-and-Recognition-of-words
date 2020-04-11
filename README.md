# About

The purpose of this project was to detect and recognize words from the text images. For this purpose Tesseract-ocr was used. The input images and their outputs can be obtained in the ORC Images and Outputs folders.

# What is Tesseract-ocr

Tesseract — is an optical character recognition engine with open-source code, this is the most popular and qualitative OCR-library.
OCR uses artificial intelligence for text search and its recognition on images.
Tesseract is finding templates in pixels, letters, words and sentences. It uses two-step approach that calls adaptive recognition. It requires one data stage for character recognition, then the second stage to fulfil any letters, it wasn’t insured in, by letters that can match the word or sentence context.

To get the installer for Tesseract, click on the following link:-

[Install Tesseract](https://github.com/UB-Mannheim/tesseract/wiki)

Choose the installer according to your bit system. Once Tesseract in installed, you need to install pytesseract module. For this open the anaconda prompt and give the following command:-

**_pip install pytesseract_**

While working on project you may get the following error even if you imported the pytesseract module :-

![Screenshot (255)](https://user-images.githubusercontent.com/54469035/78990959-6844d700-7b55-11ea-8793-ec684d808f5c.png)

To solve this problem make sure you run the following commands:-

![Screenshot (256)](https://user-images.githubusercontent.com/54469035/78991181-fb7e0c80-7b55-11ea-9d36-cf9beb0cce20.png)

The input image is processed and observed so as to get the text with highest accuracy. But it is observed that in most of the times the original image gives the maximum accuracy.

![Screenshot (257)](https://user-images.githubusercontent.com/54469035/78991669-1a30d300-7b57-11ea-9cef-045e7e17f5e6.png)

Output will be as follow:-

![Screenshot (258)](https://user-images.githubusercontent.com/54469035/78991896-a216dd00-7b57-11ea-8cc1-5e3f6d885cdb.png)

# Instructions

Install all the required modules mentioned in the requirement.txt file. Make sure to include the path where you installed Tesseract-ocr. Then read the image with following command:- 

![Screenshot (259)](https://user-images.githubusercontent.com/54469035/79047478-60a82f80-7c34-11ea-900d-568f8d891119.png)

Now we can pre-process the input image into different modes. Each mode have special characteristics. They are:-

1) **GrayScale Image**:-A grayscale image is simply one in which the only colors are shades of gray. The reason for differentiating such images from any other sort of color image is that less information needs to be provided for each pixel. In fact a gray color is one in which the red, green and blue components all have equal intensity in RGB space.

2) **Thresh Image** :- It contains the image which is thresholding techique. Image thresholding is a simple, yet effective, way of partitioning an image into a foreground and background. This image analysis technique is a type of image segmentation that isolates objects by converting grayscale images into binary images.

3) **Opening Image** :- Opening removes small objects from the foreground (usually taken as the bright pixels) of an image, placing them in the background, while closing removes small holes in the foreground, changing small islands of background into foreground.

4) **Canny Image** :- This image is processed by a technique which extract useful structural information from different vision objects and dramatically reduce the amount of data to be processed.

The output of the image can be obtained with the following command:-

![Screenshot (260)](https://user-images.githubusercontent.com/54469035/79047927-4754b280-7c37-11ea-85a1-5ddf9bb2be5e.png)

Make sure to make _.txt_ files in the directory you are working on. You can then save the output of the image by editing the .txt file with the help of **_write_** function in python. To know more about this function follow the link:-

[Python File Handling](https://www.guru99.com/reading-and-writing-files-in-python.html)


