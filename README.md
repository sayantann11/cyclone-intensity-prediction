# cyclone-intensity-prediction
Development of a deep Convolutional Neural Network for Tropical Cyclone intensity estimation using INSAT-3D IR Images and development of a web application for visualization of the cyclonic images.

## Theme & Problem Statement

Development of a deep Convolutional Neural Network (CNN) for Tropical Cyclone intensity estimation using half-hourly INSAT-3D IR Images and development of a web application for visualization of the cyclonic images.
INSAT3D/3DR observations are available at every 15-minute interval and these observations are very useful in understanding the instantaneous structural changes during evolution, intensification, and landfall of Tropical Cyclones. Datasets of Cyclones captured by INSAT-3D over the Indian Oceans are available since 2014. These datasets can be used for training and testing of the Model. Traditional methods for Intensity estimation require accurate center determination for intensity estimation. Development of CNN based model for intensity estimation will be very useful during the initial stage of cyclone formation when determination of accurate center becomes difficult.


## Proposed Solution/Idea Description

India currently has INSAT-3D Satellite that hovers on the Indian Ocean. 

Every year, 1000s of families and their homes are washed away because of the inaccurate prediction of forecasting and intensity of the cyclones. 

Since ISRO has given the challenge to predict the intensity of the upcoming cyclone of the future, given a satellite image captured by INSAT-3D, our model will use deep CNN and AlexNET to predict the intensity of the cyclone and the results can be used to mitigate the effects of the cyclone. AlexNET is a pre-defined model used for regression and classification problems of image datasets. 

Through this prediction we also aim to utilize the real time data from the images of the cyclones, that will be useful for the government.  

## PROCESS FLOW
![Capture1](https://user-images.githubusercontent.com/64836894/192084011-126578da-4ff1-4365-9c98-f7af8a91fca8.JPG)


## Objective
Use indian technology to predict real time intensity of cyclones along with the forecasting. 

To categorise the intensities of the cyclones in order to take the preventive measures and to generate real time data.


## USE cases

India will be able to predict the intensity of the cyclones which will in turn help in finding the places which will be adversely affected.

As of now India is relying on the information provided by foreign satellites but with the help of our proposed solution Indian government will have their own prediction system.

We can also fetch real time data if needed and will be able to get the intensities in the real time.

## CNN MODELS ARCHITECTURE

![Capture2](https://user-images.githubusercontent.com/64836894/192083982-af836d17-4fbb-466f-8cc0-4970e6423dd4.JPG)
## alexnet
![Capture3](https://user-images.githubusercontent.com/64836894/192083987-b95fa98a-027d-4de7-a5e1-bbc739ed3d6a.JPG)



## SUMMARY AND FUTURE FLOW

We have made two models in our solution, in order to compare the accuracies. 
        -  In Deep CNN, the input data is passed into three convolution layers . The image is thereby optimised and the output is passed through relu activation layer.
        -  In AlexNET, along with convolution layer, max pooling layer is used. 
The model with highest accuracy has been used. 

We aim to build a user friendly and interactive dashboard which will directly procure the real time data from the satellite and do real time prediction of the intensity level of the upcoming cyclones in future. 
The future work of the project includes improving the accuracy and introducing more features to extend the model to an extensive one.


## References

https://www.csie.ntu.edu.tw/~htlin/program/TCIR/ - TCIR satellite image dataset

https://link.springer.com/article/10.1007/s42452-019-1134-8  - Tropical cyclone intensity detection by geometric features of cyclone images and multilayer perceptron
https://ntrs.nasa.gov/api/citations/20170011716/downloads/20170011716.pdf  - Using Deep Learning for Tropical Cyclone Intensity Estimation
https://mausam.imd.gov.in/imd_latest/contents/satellite.php  - INSAT 3D SATELLITE IMAGE



