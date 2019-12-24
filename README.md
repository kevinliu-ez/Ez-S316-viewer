# Ez S316 Viewer (For Engineering Purpose)

Ez S316 viewer is a lightweight MS Windows application that provides basic functionality to real-time display the depth map and RGB point cloud from the EzRGBD device.

## Setup
* Hardware
  * Plug the USB DC power supply into a power outlet.
  * Connect a USB 3.0 cable from the EzRGBD device to your MS Windows computer.
  * Connect a USB 2.0 cable from the USB DC power supply to the EzRGBD device.
  * The current configuration of the device is optimized for static scenes, a tripod is recommended for holding the device.
* Software
  * Install the MS Visual C++ Redistributable for Visual Studio 2015. Or you can find the installer [here](https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/Setup/MSVCRedist_x64_VS2015-2017-2019.exe) in the repository.

## Usage
The viewer has two modes, 'PREVIEW' and 'POINT_CLOUD' modes. To start the viewer, please run the viewer located at  'EzS316Viewer\EzS316Viewer.exe'. The viewer will be in 'PREVIEW' mode after it started.

<p align="center"> 
<img src="https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/README/Viewer_StateMachine.png">
</p>

* Preview mode:
![](https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/README/EzS316Viewer.png)
  * To capture the 3D RGB point cloud of the scene, please short press (<0.5 second) key 'p'. The virtual camera may locate behind the axis mark, pressing 'r' after the windows opened is recommended.
  * To exit, please short press (<0.5 second) key 'q'.

* Point Cloud mode:
![](https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/README/EzS316Viewer_RGBDPtCloud.png)
  * To reset the virtual camera pose, please press 'r'.
  * To enlarge or decrease the size of points, please press '+' or '-' respectively.
  * To exit, please short press (<0.5 second) key 'q'.

