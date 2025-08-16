# hand-gesture-recognition-using-mediapipe
Estimate hand pose using MediaPipe (Python version).<br> This is a sample 
program that recognizes hand signs and finger gestures with a simple MLP using the detected key points.

![mqlrf-s6x16](https://user-images.githubusercontent.com/37477845/102222442-c452cd00-3f26-11eb-93ec-c387c98231be.gif)

# Requirements
* mediapipe 0.8.1
* OpenCV 3.4.2 or Later
* Tensorflow 2.3.0 or Later<br>tf-nightly 2.5.0.dev or later (Only when creating a TFLite for an LSTM model)
* scikit-learn 0.23.2 or Later (Only if you want to display the confusion matrix) 
* matplotlib 3.3.2 or Later (Only if you want to display the confusion matrix)

# Demo
Here's how to run the demo using your webcam.
```bash
python app.py

