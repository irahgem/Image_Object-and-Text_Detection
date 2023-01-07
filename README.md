<h1 align="center"> Image_Object-and-Text_Detection </h1>

<img src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=BC4E99" alt="Star Badge"/>

Object Text Detection is the process of detecting and extracting both objects and text from an image. The text in the image is detected using EasyOCR, which is an OCR (Optical Character Recognition) library that can extract text from images. Then objects in the image are detected using Yolo v3, which is a popular object detection algorithm that uses convolutional neural networks to identify objects in images and videos. To implement this in Flask, Flask server is set and created a route that accepts an image file as input. You would then use EasyOCR to extract the text and Yolo v3 to detect the objects in the image. The detected objects and text can then be returned as output to the user. It is also possible to display the image with the detected objects and text overlaid on top of it using a library such as OpenCV.

#### Steps to Execute:
- Install EasyOCR, FLASK
- Install Required Dependencies using pip install 
- Run main.py
- Click on the local host which redirects to the web application
- Choose image file (JPEG images are allowed as of now).
- Click Upload to Detect Object and Text from the Image.
