# Apartment Visualization VR app
The project goal was to design and create an apartment scene based on several 3D models with nice lighting and custom animation.  
![alt text](https://github.com/julciane/Udacity-VRND-Apartment-Visualization/blob/master/Screenshot/Screenshot_20170505-015816.png)  
![alt text](https://github.com/julciane/Udacity-VRND-Apartment-Visualization/blob/master/Screenshot/Screenshot_20170505-015816.png)  
![alt text](https://github.com/julciane/Udacity-VRND-Apartment-Visualization/blob/master/Screenshot/Screenshot_20170505-015946.png)  
![alt text](https://github.com/julciane/Udacity-VRND-Apartment-Visualization/blob/master/Screenshot/Screenshot_20170505-020327.png)  
## What I've learned in this project:
This project is about combining various ideas and skills i’ve been practicing throughout the course. They include:  

* Adding 3D models to a scene  
* Moving, scaling, and rotating 3D models  
* Deploying to your Cardboard Viewer  
* Creating materials and assigning textures  
* Creating animations and triggering them  
* Creating lights and baking them   
* Optimizing a scene for top performance  

## How to run

Open the project in Unity.   
Import the Google VR SDK package.  
Set "VR Mode Enabled" to true in GvrViewerMain.  
Build and run tihs app.  
Or you can also install /Build/VRWorld.apk into your phone.  

It was tested on Unity 5.5.1f1 using Google VR SDK 1.0.3

## Lightmap Settings:
   I activated "Hard shadows" on spotlights, Baked Resolution was set to 80 and I used an uncompressed lightmap. The result was that app runned at 60 FPS as desired, but it didn't presented lighting artifacts.  
   
   Personal impressions: One thing I liked was learning about baked lighting. However, adjusting lighting for mobile/unlit shader once I have already adusted it to mobile/difuse was very challenge.  
   
   This project was particularly challenge for me because there were so many lighting concepts that I was not familiar, so I have to understand these concepts and figure out why and how apply them to the scene.  
   
   Another difficult point was the Profiler analysis of how "Lightmap Settings" affects app performance.  
