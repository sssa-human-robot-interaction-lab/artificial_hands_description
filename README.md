# artificial_hands_description
The package contains all do you need to integrate the Mia Hand and the UR in a simulation environment. 

## Installation
You can install **artificial_hands_description** from source: 
```
git clone <url>
```
To use it you must install the Mia Hand and UR pkgs: 
```
git clone https://bitbucket.org/prensiliasrl/mia_hand_ros_pkgs/src/master/
```
```
git clone -b calibration_devel https://github.com/fmauch/universal_robot.git src/fmauch_universal_robot
```

## How to test the package

 - roslaunch artificial_hands_description mia_hand_on_ur_bringup.launch sim:=true 
