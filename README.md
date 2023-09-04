# SENSOR FUSION AND OBJECT TRACKING
   This project use an 3D object detection using lidars data from [Waymo Open Dataset](https://waymo.com/open/). The original project files are from the related [Github repository](https://github.com/udacity/nd013-c2-fusion-starter).
   
## 1. Project Step 1
Step 1 deals with the implementation of an Extended Kalman Filter (EKF) for tracking a simple vehicle based on lidar sensor data.
| Results| 
| ------------- | 
| <p align="center" > <img width="100%" src="media/step_1.png" alt=""/> <br> <em>Tracking a single-target base on lidar data</em> </p> |
| <p align="center" > <img width="100%" src="media/step_1_RMSE.png" alt=""/> <br> <em>RMSE tracking index</em> </p> |
 
## 2. Project Step 2

In Step 2 of the final project, the track management to initialize and delete tracks, set a track state and a track score are implemented.

| Results| 
| ------------- | 
| <p align="center" > <img width="100%" src="media/step_2.png" alt=""/> <br> <em>Tracking a single-target base on lidar data</em> </p> |
| <p align="center" > <img width="100%" src="media/step_2_RMSE.png" alt=""/> <br> <em>RMSE tracking index</em> </p> |

## 3. Project Step 3
In Step 3, a single nearest neighbor data association to associate measurements to tracks is implemented. This is a multi-target tracking scenario.

| Results| 
| ------------- | 
| <p align="center" > <img width="100%" src="media/step_3.png" alt=""/> <br> <em>Tracking a single-target base on lidar data</em> </p> |
| <p align="center" > <img width="100%" src="media/step_3_RMSE.png" alt=""/> <br> <em>RMSE tracking index</em> </p> |

## 4. Project Step 4
In Step 4, the nonlinear camera measurement model and linear lidar model are implemented. The sensor fusion module for camera-lidar fusion is completed.

| Results| 
| ------------- | 
| <p align="center" > <img width="100%" src="media/step_3.png" alt=""/> <br> <em>Tracking a single-target base on lidar data</em> </p> |
| <p align="center" > <img width="100%" src="media/step_3_RMSE.png" alt=""/> <br> <em>RMSE tracking index</em> </p> |

## 4. Video

