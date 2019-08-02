# Face-Recognizer
A project for recognition of faces among several faces in real-time.

## Usage

1. Download face_data_collect.py. Prepare a set of images of the known people you want to recognize by running the program file.      Organize these images in a single directory(specify the path where you want to store images).
   
   
2. Then, call the 'train' function with the appropriate parameters. Make sure to pass in the 'model_save_path' if you
   want to save the model to disk so you can re-use the model without having to re-train it.
3. Call 'predict' and pass in your trained model to recognize the people in an unknown image.
