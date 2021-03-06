# Face Recognition
Query a given face, either from a given image or from a webcam, within pictures, either from a given directory or from the webcam.

## Demo
<!-- include demo gif -->
Here is a demo of me using this library. I use my Github profile picture as a query to detect on a live webcam.
### Query:
![](./sk7w4tch3r.jpg)
### Result (GIF):
![demo.gif](./demo.gif)


<hr>

## Usage

```
$ python main.py --query <OPTIONS>  --source <OPTIONS> 
```

Options:

```
--query
    C/capture : Capture a face from webcam
    <filename> : Query a face from image file
--source
    L/live: Find the query face in live video input.
    <directory>: Directory containing images to query.
```


<hr>

## Requirements
Make sure you have the following libraries installed:

- dlib
- face_recognition
- cv2

On Windows you can install them by running:
```
dlib
    pip install cmake
    conda install -c conda-forge dlib

face_recognition
    pip install face_recognition

cv2
    pip install opencv-python
```

<hr>

## Contributions
This project is for fun! 

Feel free to contribute the tasks below in your free time!
- [ ] Search faces in a movie file (ffmpeg)
- [ ] Convolutional models to detect faces
- [ ] Migrate to C++



<hr>

## Credits
This repository is based on the [face_recognition](https://github.com/ageitgey/face_recognition) project.
