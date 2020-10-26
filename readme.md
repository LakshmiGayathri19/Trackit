**Name:** _Monitoring Heart-Rate Using Web-Cam_


**Description:**
This project deals with real-time monitoring of a person’s heartbeat using web-cam. 
It replaces the traditional machines used for measuring the heart-rate which not only limits the mobility of patients 
but also causes local skin problems and may aid the spread of contagious infections between patients.


**Requirements:**
To run the above cod	e the requirements are:
Setup:
•	Python 3.7</br>
•	Laptop with a webcam</br>


**Modules:**
•	Opencv</br>
pip install opencv-python</br>
pip install opencv-contrib-python</br>
•	datetime</br>
pip install datetime</br>
•	Matplotlib</br>
Pip install matplotlib</br>
•	Pytimeparse</br>
Pip install pytimeparse</br>
•	Pylab</br>
Pip install pylab</br>
•	Skimage</br>
Pip install scikit-image</br>


**Run the project:**
1.	Open cmd with the folder containing the project</br>
2.	Python pulse.py</br>
3.	Person’s face should be tracked by the webcam</br>
The above commands will run the project. In order to smoothly execute the code a fluorescent light should be placed in front of the person’s face. 



**Input Sample:**


![](FaceDetection.png)


•	The webcam must track the person’s face perfectly using haarcascade frontal face detection. </br>
•	The green box is used to detect the person’s face.</br>
•	 The blue box is used to detect the forehead (adjust your position according to the blue box in such a manner that forehead lies within the box)</br>
•	Color variation will be seen in the blue box representing the change in pixel intensity with each cardiac cycle</br>
•	If there are no color variations, then external luminous provided by the fluorescent light isn’t sufficient</br>
•	The person need to wait until 90 frames to get the heartrate</br>



**Output Sample:**


![](HeartRateGraph.png)


![](RGBCIE.png)


![](Terminal.png)



**Figure (a):**
•	This graph represents the change in ppg (Photoplethysmography) signals with time.</br>
•	 There could be sudden increase or drop in the frequency due to external disturbance like light intensity.</br>
•	The graph also contains the person’s heart rate measured per minute.</br>



**Figure (b), (c):**
•	The figure b represents the variations of ppg signals in RGB channel</br>
•	The figure c represents the variations of ppg signals in LAB channel</br>
•	This figures are used to signify the variation of ppg signals in RGB and lab color space with motion artifacts of the person</br>



**Figure (d):**
•	This figure shows command prompt after closing all the graph windows.</br>
•	The cmd contains “Face not Found” for those frames whose face is not detected by haar-cascade algorithm.</br>
•	The frames in which the face is not detected are pruned</br>
•	The measured HeartRate is also displayed on the cmd .</br>



**References:**
[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5995145/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5995145/)


[http://www.ep.liu.se/ecp/129/002/ecp16129002.pdf](http://www.ep.liu.se/ecp/129/002/ecp16129002.pdf)

***
##Contributor
[Swathi Guptha](https://github.com/Swathi-Guptha/Track-it)
