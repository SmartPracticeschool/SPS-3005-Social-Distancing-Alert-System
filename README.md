# SPS-3005-Social-Distancing-Alert-System
Social Distancing Alert System
Project Idea: 
COVID-19 spread is emotionally challenging for many people, changing day-to-day life in unprecedented ways. All sections of society should play a vital role to protect themselves and each other and help prevent further spread of the disease. Social-distancing is an important way to slow down the spread of infectious diseases. People are asked to limit their interactions with each other, reducing the chances of the disease being spread with physical or close contact.

Solution

The solution is to create a system that uses pre-installed cameras/ recorded videos to analyze images from public areas like shopping malls, streets to see whether the public is adhering to safety measures, like maintaining social distancing.

This project uses python combined with deep learning and computer vision to monitor social distancing. A web application is built and is hosted on the cloud which streams the video of  Social distancing Violations

Project Flow :

1) Get the camera / Video Feed

2) Detect pedestrians in the frame using the Yolo pre-trained model

3) Localize the pedestrians in the frame

4) calculate the centroid of the pedestrians detected

5) Find the distance between Pedestrians 

6) Draw rectangle bounding boxes around pedestrians who are very close 

7) Count the number of bounding boxes which are very near

8) Display the count of Violations on the frame

9) Create a Flask application which streams the frames 

10)  Host Web app on IBM Cloud

