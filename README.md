# Face_Recognition
Developed a Real Time Face Recognition using OpenCV and Python.
Using the face_recognition library and use of algorithms such as Deep learning based face recognition using CNN (convolution Neural Network) and HOG (histogram of oriented gradients)

Devices Used :

* Raspberrypi 4B 

* Web Cam (can also use pi cam if needed)

Instructions : 

Step 1 - Install the dependencies 
          
(I)  opencv 
*        sudo apt install python3-opencv
*    Refer (https://pimylifeup.com/raspberry-pi-opencv/) for installing opencv
          
(II)  face_recognition
*        sudo apt install face-recognition
          
(III)  imutils
*        sudo apt install imutils

(IV)  openBLAS library
*        sudo apt install libopenblas-dev

Step 2 - Download the code from the github repository. https://github.com/mrwitty-ec/Face_Recognition.git 

Step 3 - Create a New Folder named dataset and within the dataset create another folder named afer the persons name as you wish.

Step 4 - Open the face_shot.py file using thonny and replace the name(witty) in the line 3 with the person's name. And run the code. Once the code runs without any error you can see the camera feed window. Press "spacebar" to capture the model image and "esc" to exit.

Step 5 - Make sure the captured images are present in the correct folder as you mentioned and run the train_model.py file in thonny. Here all the images will be recognised and the model will be trained.

Step 6 - Finally run the face_rec.py file in thonny. If all the steps are done correctly it should identify the faces that were trained by you.




!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! auto.py runs all the programs for you. You just need to install the dependencies from the Step 1 !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
