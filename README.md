# Ez S316 Viewer

Ez S316 viewer is a lightweight MS Windows application that provides basic functionality to realtime display the depth map and RGB point cloud from a EzRGBD device.

## Setup
* Hardware
  * Plug the USB DC power supply into a power outlet.
  * Connect a USB 3.0 cable from the EzRGBD device to your MS Windows computer.
  * Connect a USB 2.0 cable from the USB DC power supply to the EzRGBD device.
* Software
  * Install the MS Visual C++ Redistributable for Visual Studio 2015. Or you can find the installer [here](https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/Setup/MSVCRedist_x64_VS2015-2017-2019.exe) in the repository.

## Usage
The viewer has two modes, 'Preview' and 'Point Cloud' modes.

###FlowChart

```flow
st=>start: Login
op=>operation: Login operation
cond=>condition: Successful Yes or No?
e=>end: To admin

st->op->cond
cond(yes)->e
cond(no)->op
```

![](https://github.com/kevinliu-ez/Ez-S316-viewer/blob/master/README/EzS316Viewer.png)
* Run the viewer located in 'EzS316Viewer\EzS316Viewer.exe'.
* To capture the 3D RGB point cloud of the scene, please short press (<0.5 second) key 'p'.
* To exit, please short press (<0.5 second) key 'q'.

