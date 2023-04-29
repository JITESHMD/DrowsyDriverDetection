# DrowsyDriverDetection(Intel One API)

Drowsy driver detection refers to the use of technology to identify when a driver is becoming drowsy or falling asleep at the wheel. This technology typically involves monitoring the driver's behavior and physiological signals, such as eye movements, head movements, and changes in heart rate and breathing patterns.


Once the drowsiness detection system detects that the driver is becoming drowsy or falling asleep, it can issue alerts to wake the driver up, such as audible alarms or vibrations in the steering wheel or seat. In some cases, the system may also take more drastic actions, such as slowing down the vehicle or bringing it to a stop.


Drowsy driver detection systems are designed to improve safety on the road by reducing the risk of accidents caused by driver fatigue. They are particularly important for long-distance truck drivers, shift workers, and others who may be at high risk of drowsy driving.





SURVEY AND REPORT

![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/ezgif.com-video-to-gif.gif)




<h4>WHY INTEL ONE API</h4>

![](https://user-images.githubusercontent.com/90272634/230717338-f2dc33e7-31df-4dc0-98f1-9074cb7252e2.png)



Intel oneAPI is a suite of development tools for creating software that can run on a variety of platforms, including CPUs, GPUs, and FPGAs. It includes a number of components, such as compilers, libraries, and tools for performance analysis and debugging. The advantage of using oneAPI is that it allows developers to write code once and run it on a variety of hardware platforms, which can save time and effort.

<h4>SAMPLES</h4>

![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/val_batch0_labels%20(1).jpg)

THE ABOVE IMAGE SHOWS THE TRAINING AND VALIDATING OF THE IMAGE DATASETS

There are two classes :

          --> AWAKE
          
          --> DROWSY
          
          
<h4>INFERENCE</h4>          

After Traning and testing of different models we got more accuracy for the RESNET50 CNN model with accuracy of 80.00% for given data. The oneAPI reduced the overall runtime and GPU usage significantly compared to normal platforms. All the models haven been optimised and execution time have been reduced by using Intel oneAPI.
          

<h4>RESULTS</h4>


Video of predicted output of the model which is deployed in the flask framework


![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/ezgif.com-video-to-gif%20(1).gif)









![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/results%20(2).png)


<h4>GRAPHS AND VISUALIZATION</h4>


F1 CURVE

![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/F1_curve%20(1).png)

PR CURVE

![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/PR_curve%20(1).png)


CONFUSION MATRIX

The matrix which says the classes that are predicted precisely and accurately of the drowsiness of the driver 



![](https://github.com/JITESHMD/CROP-PREDICTION-GaussianNB/blob/main/confusion_matrix%20(1).png)

