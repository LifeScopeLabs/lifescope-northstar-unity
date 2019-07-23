# lifescope-northstar-unity

LifeScope North Star / Polaris AR Unity tools


# Team


Liam Broza @mrhegemon 

Michelle Juarez @ojosgitanos 



**Special Thanks to Noa Labs & Polaris AR**



Hey North Star community! I’m @LiamBroza with @ojosgitanos working on a North Star / Polaris AR project based off our Unity tools and 3D maps. 



[https://github.com/LifeScopeLabs/lifescope-northstar-unity](https://github.com/LifeScopeLabs/lifescope-northstar-unity)

[https://github.com/LifeScopeLabs/lifescope-unity](https://github.com/LifeScopeLabs/lifescope-unity)



We are building tools to show 3D maps at worldscale, record the world, record people, and playback sensor data in AR. Looking forward to collaborating with you all!



# Notes

* [Project North Star Discord Community](https://discord.gg/DdXN7CC)
* [Leap Motion Blog](http://blog.leapmotion.com/)
* [Leap motion Display Driver Board GitHub](https://github.com/leapmotion/ProjectNorthStar/tree/master/Electronics/Hardware)
* [BOM List](https://github.com/leapmotion/ProjectNorthStar/blob/master/Electronics/Hardware/Bill%20of%20Materials-Project%20North%20Star.xls)



* [https://www.dropbox.com/sh/ilan0a0p7pom735/AADg3HF2Ayo7OTVQ7jVZQwH-a?dl=0](https://www.dropbox.com/sh/ilan0a0p7pom735/AADg3HF2Ayo7OTVQ7jVZQwH-a?dl=0)
* [https://developer.leapmotion.com/northstar/](https://developer.leapmotion.com/northstar/)
* [https://www.polaris-ar.com/](https://www.polaris-ar.com/)
* [https://github.com/leapmotion/ProjectNorthStar](https://github.com/leapmotion/ProjectNorthStar)

## 

## Voltage Regulation

* [https://www.amazon.com/dp/B01E6YSGPG/ref=cm_sw_em_r_mt_dp_U_MDKnDb3BKYK5J](https://www.amazon.com/dp/B01E6YSGPG/ref=cm_sw_em_r_mt_dp_U_MDKnDb3BKYK5J)



# Guides

* [https://forums.structure.io/t/room-capture-development-approach/348](https://forums.structure.io/t/room-capture-development-approach/348)



# Parts

* [https://www.smart-prototyping.com/index.php?route=product/product&product_id=44428](https://www.smart-prototyping.com/index.php?route=product/product&product_id=44428)
* [https://www.smart-prototyping.com/Project-North-Star-Display-Driver-Board](https://www.smart-prototyping.com/Project-North-Star-Display-Driver-Board)
* [https://www.smart-prototyping.com/Display-for-Project-North-Star-3_5inch-1440x1600-pixels](https://www.smart-prototyping.com/Display-for-Project-North-Star-3_5inch-1440x1600-pixels)



## Videos

* [David Holz‘s Video](https://players.brightcove.net/pages/v1/index.html?accountId=689254975001&playerId=default&videoId=6022148590001&autoplay=true)
* [Pumori](https://www.youtube.com/channel/UCkoJWd45XBRaFzc26jE7uEg)
* [https://www.youtube.com/user/noazark/videos](https://www.youtube.com/user/noazark/videos)



## Photos

* [https://drive.google.com/drive/folders/1KhYBybmO4MiF9iHTs7hrzJLp0eN9fiN9](https://drive.google.com/drive/folders/1KhYBybmO4MiF9iHTs7hrzJLp0eN9fiN9)



# Tools

## Masterpiece Studio

* [https://www.masterpiecevr.com/spotlight](https://www.masterpiecevr.com/spotlight)

## 

## Editor XR

* [https://forum.unity.com/threads/welcome-to-the-editorxr-forums.446379/](https://forum.unity.com/threads/welcome-to-the-editorxr-forums.446379/)
* [https://docs.google.com/document/d/1RD0SAjWnXdtY6eOC4qHk_fcl7w2-aBGrF3rX5pk5KDo/edit](https://docs.google.com/document/d/1RD0SAjWnXdtY6eOC4qHk_fcl7w2-aBGrF3rX5pk5KDo/edit)





# Code

## 

## Occipital Perception Engine

* JACOB ERVIN  [jacob@occipital.com](mailto:jacob@occipital.com) Twitter: JacobKyleErvin
* Sign up for Occipital Developer Portal (developer.structure.io)
* Download Structure SDK (Cross Platform) 0.7.1
* Update FW + Install Drivers

### 

### Core Streaming (Optional)

* Install CMake + Install Visual Studio 2017
* Generate the Visual Studio Solution > mkdir build > cd build >cmake -G"Visual Studio 15 2017 Win64" ..
* Open build\StructureSDK-CrossPlatform.sln
* Build and Run CorePlayground
* If a Unix-like environment such as Git Bash (part of Git for Windows) or MSYS2 is installed, the included build script may be used instead. $ Scripts/build.sh

### 

### Perception Engine

* Download Perception Engine + Sample Unity Package
* Launch Tools/XRService (launches into Windows System Tray)
* Right Click —> Start
* Navigate to Samples/XRUnity/Assets/Scenes 
* Double-click on FirstPersonScene.unity
* Play in Simulator

### 

### Integrating North Star 

#### Part 1

* Install Custom Leap Motion Drivers 
* Duplicate Occipital Unity Sample
* Import North Star Plugin  (https://github.com/leapmotion/ProjectNorthStar)
* Copy Everything From Leap Motion Sample Scene Into FirstPersonScene.unity
* Remove Ground Plane
* Scale World Objects to 0.1 

#### Part 2 

* Set Windows Display Scale to 100% 
* ARCameraRig, X Shift = Display Width 
* Select ARCameraRig, Close All Game Views
* ARCameraRig Move Game View to Headset
* ARCameraRig/Head/Leap provider —> X rotation = 37 

#### Part 3

* Set Windows Display Scale to 100% 
* ARCameraRig, X Shift = Display Width 
* Select ARCameraRig, Close All Game Views
* ARCameraRig Move Game View to Headset
* ARCameraRig/Head/Leap provider —> X rotation = 37 

#### Part 4

*  Comment out ARRaytracer.cs Line 73


## Pumori

* [https://www.pumori.io/](https://www.pumori.io/)
[Pumori YouTube Channel](https://www.youtube.com/channel/UCkoJWd45XBRaFzc26jE7uEg)
* [How to Install Pumori Apps onto North Star](https://www.youtube.com/watch?v=WZQwNd8dFtQ)

#### Project North Star: Software

This Unity Package contains the Unity Assets, Scenes, and Prewarping systems necessary to build Unity applications with the Project North Star headset.

#### Compatibility

These assets require the [Multi-Device Beta Service](https://github.com/leapmotion/UnityModules/tree/feat-multi-device/Multidevice%20Service) to display hands.

These assets are dependent on [Release 4.4.0](https://github.com/leapmotion/UnityModules/pull/1010) of the [Leap Motion Unity Modules](https://github.com/leapmotion/UnityModules) (included in the package).

Elements of type INLINE_IMAGE are not supported

#### Getting Started:

* Make sure your North Star AR Headset is plugged in
* Create a new Project in Unity 2018.2 or above
* Import "LeapAR.unitypackage"
* Navigate to LeapMotion/North Star/Scenes/NorthStar.unity
* Click on the ARCameraRig game object and look for the WindowOffsetManagercomponent
* Here, you can adjust the X and Y Shift that should be applied to the Unity Game View for it to appear on the North Star's display
* When you're satisfied with the placement; press "Move Game View To Headset"
* With the Game View on the Headset, you should be able to preview your experience in play mode!

Key Code Shortcuts in NorthStar.unity (in the Editor with the Game View in focus and playing)

* C to Toggle Visibility of Calibration Bars

#### Calibrating your Headset

We have included a pre-built version of the internal calibration tool. We can make no guarantees about the accuracy of the process in DIY environments; this pipeline is built from multiple stages, each with multiple points of failure. Included in the .zip file are a python script for calibrating the calibration cameras, a checkerboard .pdf to be used with that, and Windows-based Calibrator exe, and a readme describing how to execute the entire process.

Click for friendlier video overview:

