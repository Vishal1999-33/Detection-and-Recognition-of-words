# About

The purpose of this project was to detect and recognize words from the text images. For this purpose Tesseract-ocr was used.

# What is Tesseract-ocr

Tesseract — is an optical character recognition engine with open-source code, this is the most popular and qualitative OCR-library.
OCR uses artificial intelligence for text search and its recognition on images.
Tesseract is finding templates in pixels, letters, words and sentences. It uses two-step approach that calls adaptive recognition. It requires one data stage for character recognition, then the second stage to fulfil any letters, it wasn’t insured in, by letters that can match the word or sentence context.

To get the installer for Tesseract click on the following link:-

[Click here](https://github.com/UB-Mannheim/tesseract/wiki)

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
