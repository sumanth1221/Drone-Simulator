# Drone Simulator

I have worked on Drone Simulator using UnityHub and ROS Gazebo. I have created a project in the Unity Hub then planted Bushes and Trees in the Agricultural Terrain. I have added Drone related packages in the project and my Projects looks as follows:

![image](https://user-images.githubusercontent.com/43805517/209765325-1efefc5e-ae3e-4813-b76c-9da3ce2c6d9a.png)

![image](https://user-images.githubusercontent.com/43805517/209765371-1356ec72-c3f4-4125-8a66-19ff41c2a643.png)

1. Drones equipped with multi-spectral imaging equipment can be used to collect data from agricultural fields which can be processed into vegetative indices. These cameras can also provide a live image feed to properly navigate the drone around obstacles. This increases the safety of operating the drone, as well as provides the pilot with a smoother operating experience.

2. In this project, we explore different software applications to aid with the collection and processing of agricultural data, the usability of simulated environments for researching drone-based imaging, and the application of drone-based imaging for vegetation analysis. Remote sensing is performed to capture red, green, and blue (RGB) images for vegetation analysis in the ROS-Gazebo simulated environment.

3. Using Unity and ROS/Gazebo, we were able to create a simulated drone that accurately flew and took pictures of an agricultural landscape and saved the appropriate image files necessary to create a large map of the area. 

4. Using the multiple pictures that were taken of the landscape, we then used software to create an orthomosaic that combines the separate images into a single high-resolution image, attempting to correct inconsistencies between the images like camera tilt or distortion. The software used to create the aerial pictures is called WebODM, a web-based application for Open Drone Maps. 

5. Then, with aid from the geographic information system application QGIS, vegetative indices were added to our images. Microsoft AirSim, a drone simulation plugin for Unreal Engine, was used to create a simulated agricultural environment for autonomously flying and collecting image data for processing. 

6. We expanded our horizon to not only use Unity and ROS/Gazebo but also the Unreal Engine. The research provided helped to guide most of our team in having a successful experience, while also using their engine of choice.
