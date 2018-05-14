# StereoDisparityRecoveryDepthAndReconstruction
This demo restores depth information of scenes through stereo images and uses Pangolin for dense reconstruction of scenes.

## Mathematical theory
<div align=center>  
  
![](https://github.com/TianQi-777/StereoDisparityRecoveryDepthAndReconstruction/blob/master/Images/disparity.png)
</div>

## Additional Prerequisites for this demo
**Pangolin**  
Use [Pangolin](https://github.com/stevenlovegrove/Pangolin) for visualization and interface. 
Dowload and install instructions can be found at: https://github.com/stevenlovegrove/Pangolin.

**Eigen3**  
Download and install instructions can be found at: http://eigen.tuxfamily.org.  

**OpenCV**  
Use [OpenCV](http://opencv.org) to process images.  

**C++11 or C++0x Compiler**  
Use the new thread and chrono functionalities of C++11.

## Build and Run
```
cd XX/XX(include disparity.cpp ,disparity.png ,left.png ,right.png and CMakeLists.txt)  
mkdir build  
cd build  
cmake ..  
make -j2  
./disparity
```

## Result
**Pangolin GUI:**   
**Dense reconstruction**
<div align=center>  
  
![](https://github.com/TianQi-777/StereoDisparityRecoveryDepthAndReconstruction/blob/master/Images/point_cloud_viewer.png)
</div>

**Change the perspective**
<div align=center>  
  
![](https://github.com/TianQi-777/StereoDisparityRecoveryDepthAndReconstruction/blob/master/Images/change_viewer.png)
</div>
Because we only use 2 pictures, we will see a fault.



