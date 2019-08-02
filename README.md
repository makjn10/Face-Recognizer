# Face-Recognizer
A project for recognition of faces among several faces in real-time.

### Requirements
  * Python 3.7
  * Numpy 1.16
    You can install it using pip:
    ```
    $ pip3 install numpy
    ```
  * OpenCV - contrib - python 4.1.0 
    You can install it using pip:
    ```
    $ pip3 install opencv-python
    ```

### Usage
1. Download face_data_collect.py. Prepare a set of images of the known people you want to recognize by running the downloaded file.
   To run the file in command line use the following command : 
   ```
   $ python face_data_collect.py 
   ```
   Organize these images in a single directory(specify the path where you want to store images). Also while running the program        you will be prompted to give the name of the person of whom images are being stored.
   
   ![Path to directory](datapath.jpg)
   
2. Now download face_recognition.py and run the program file. To run the file in command line use the following command :
   ```
   $ python face_recognition.py
   ```
   
3. You can see the predicted labeling to all the faces in live video stream captured from your webcam. Press 'q' key to exit the      program.
