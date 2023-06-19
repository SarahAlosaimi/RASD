(RASD)
![Dashcam (1)](https://user-images.githubusercontent.com/98524329/200344318-1f31874e-ba4c-41f7-9220-156cb5ff183e.png)



# About this project
"RASD" is a mobile application that has been developed to detect traffic violations with the help of a driver's dashcam. The app is designed to generate a readymade report that can be used to report the violation to the authorities. The application support both English and Arabic languages to cater to a wider audience. With the help of the app, drivers can easily report any violations they witness on the road, which in turn can help in making the roads safer.

# Technology and tools used In the project
The technology and tools utilized in this project include the Flutter framework and Dart programming language for building the application, as well as Firebase for cloud storage and database. Visual Studio Code and the emulator provided by Android Studio were employed for development purposes. In addition, the model was built using the Python programming language on Google Colab and subsequently deployed on Heroku server.

 <br> <img height="40" width="40" 
 src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/firebase/firebase.png">
 <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/192108895-20dc3343-43e3-4a54-a90e-13a4abbc57b9.png">
  <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png">
  <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/186150304-1568ffdf-4c62-4bdc-9cf1-8d8efcea7c5b.png">
  <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/186150365-da1eccce-6201-487c-8649-45e9e99435fd.png">
     <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/117269608-b7dcfb80-ae58-11eb-8e66-6cc8753553f0.png">
   <img height="40" width="40" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png">
      <img height="40" width="40" src="https://colab.research.google.com/img/colab_favicon_256px.png">
            <img height="40" width="40" src="https://www.herokucdn.com/favicons/favicon.ico">



# launching Instructions 
 In order to run the code you need the following: 
 ## Prerequisites to run the application: 
 - Visual studio code/Android Studio
 - Android emulator.
 - Flutter SDK.
 - Stable internet connection -Since we are using cloud Firestore database
 
 ## Prerequisites to run the model: 
 - Google Colab

 
## Installation :
 1. Download VS from https://code.visualstudio.com/  or download Android Studio from https://developer.android.com/studio
 2. Download any android emulator.                                         
   Suggestion: Android Studio emulator from https://developer.android.com/studio
 3. Download Flutter SDK from https://docs.flutter.dev/get-started/install 
 
## Start Running flutter code :
1. Import the code in VS/Android studio.
2. Run the emulator.
3. Run the code.
4. Sign up to the application or log in using the provided credentials. 

## Start Running the model: 
1. Download violationDetectionModel.h5 file
2. Download coco.names , yolov5s288.onnx , rasd-d3906-firebase-adminsdk-1djor-9976e852c3.json files
3. Download the notebook ( vehicle_objects_and_violation_detection_yolov5s.ipynb ) from Model Training and Testing folder
4. Upload all the files in google drive 
5. Run the notebook in Google collab

## Resources:
The attached object detection model and violation detection model were inspired by:

https://github.com/chandran-jr/Violence-Alert-System

https://learnopencv.com/object-detection-using-yolov5-and-opencv-dnn-in-c-and-python/

The code was modified as needed to suit the requirements of RASD.

# Connect with US 
 <a href="https://twitter.com/rasdgp?s=21&t=wSUpQhdTJfIKRsMi9yXcAQ" target="blank"><img align="center"
      src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg"
      alt="adampithewan" height="30" width="40" /></a>
