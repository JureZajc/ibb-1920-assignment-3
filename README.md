# ibb-1920-assignment-3

prerequirements:<br/>
-python 3.6<br/>
-keras<br/>
-cv2 <br/>
-tensorflow<br/>
-Webcam

First we need to create folder "images" where we put our training images, we need to change their names to the person they belong. After we put images into folder, we run file create_embedding.py, if we don't have GPU we must comment line 20, so it use CPU instead. After program finishes embeedings.npy file is created. Finally we run face-recognition.py, Webam will opened and if trained correctly face will be squared and on top of that name of the person will be displayed.
