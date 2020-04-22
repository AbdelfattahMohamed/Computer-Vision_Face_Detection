# Computer-Vision_Face_Detection-
Using OpenCV &amp; Python 
#### For the run

Enter the path of your photo after run the Notebook
# Face Recognition

[![PyPI](https://img.shields.io/apm/l/computer-vision-object-detection?color=blue&label=coursera&logo=coursera&style=social)]
[![Build Status](https://img.shields.io/github/license/AbdelfattahMohamed/Computer-Vision_Face_Detection-?color=blue&label=github&logo=github&logoColor=red)](https://github.com/AbdelfattahMohamed/Computer-Vision_Face_Detection-)


## Features

#### Find faces in pictures

Find all the faces that appear in a picture:

![](download.jpg)
<img src="https://img.icons8.com/plasticine/100/000000/arrow.png"/>
![](Run.jpg)
```python
import face_recognition
image = face_recognition.load_image_file("your_file.jpg")
face_locations = face_recognition.face_locations(image)
```
