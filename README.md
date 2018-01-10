# RGBDSLAM Based on Astra Camera 

You can visit the original RGBDSLAM package for Kinect [here](https://github.com/felixendres/rgbdslam_v2)  

### Step 1: Download the [install.sh](https://github.com/yzqin/rgbdslam/blob/master/install.sh) file

`$ wget https://github.com/yzqin/rgbdslam/blob/master/install.sh`

### Step 2: Change the WORKSPACE in line 17 of [install.sh](https://github.com/yzqin/rgbdslam/blob/master/install.sh) to your own catkin workspace

>WORKSPACE=~/grad_design/catkin_ws

### Step 3: Install g2o and rgbdslam from scratch

` $ bash install.sh`

### Step 4: Install ROS-Astra-SDK follow this [link](https://github.com/orbbec/ros_astra_camera) and install ROS-Astra-Launch from [here](https://github.com/orbbec/ros_astra_launch)

### Step 5: Run RGBDSLAM with Astra Camera

#### Terminal 1:
`$ roscore`
#### Terminal 2:
`$ roslaunch astra_launch astra.launch`
#### Terminal 3:
`$ roslaunch rgbdslam rgbdslam.launch`






