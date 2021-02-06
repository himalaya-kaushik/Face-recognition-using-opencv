# Face-recognition-using-opencv
It creates a model and trains  it on the face in real time and recognizes face in real-time using webcam
Step 1 : We create a custom datset using opencv tht captures our face and stores it a folder using opencv's detectMultiscale function
Step 2: We tran our LBPHFaceRecognizer on our facial datset and use CascadeClassifier to detect face in our image
Step 3 : We test our model in real-time using our webcam and create a bounding box around the recognized face.
