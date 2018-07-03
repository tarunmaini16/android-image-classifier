# Machine Learning Example
## Android: Camera application for image classification
A sample android application by which user can classify among set of images.  
We are retraining final layer of images to create labels and graphs for our provided set of images, classification model is getting created by Transfer Learning.  

We are using TensorFlow library of python here. TensorFlow is an open-source software library for dataflow programming across a range of tasks. It is a symbolic library used for machine learning applications such as neural networks.  
<br>
##### Following are the tasks we will be performing in this exercise:
* Retrain a MobileNet
* Convert the model to TFLite Format and create optimized graphs
* Setup Android App
* Test Run our customized app 
  
##### Prerequisites are as follow:  
* Install Tensorflow `$ pip install --upgrade "tensorflow==1.7.*"`  
* Android Studio setup [v3.1+]
* Android Device(With Debugging Enabled) or Emulator (API Level = 27, Target = Android 8.1)

#### Output will be similiar to below images in real device:
<p float="center">
  <img src="https://drive.google.com/uc?id=1yDcRRrjgrig1R2Bpo2u-6neLrQ9bLkKh" width="195" />
  <img src="https://drive.google.com/uc?id=1oc7hk3796frk6eCw-udGNy8GatUczbvt" width="195" /> 
  <img src="https://drive.google.com/uc?id=15ix8M0mGlIzKLj2fe6h-JSUj1yfNpGns" width="195" />
  <img src="https://drive.google.com/uc?id=1tkabGhP12KaWRoRsJATDI1-lwqQVn3IX" width="195" />
</p><br>

##### _CLI version of same_:
> **https://github.com/tarunmaini16/image-classifier**