# ROS Workspace for manipulator '22

## Installation

Clone this repository:
```
git clone --recurse-submodules https://github.com/itu-rover/arm22_ws.git
```

Then, build the packages:
```
cd arm22_ws
catkin build
```


### Update to latest if this repo is not up to date
You can use the following in a command-line to update each submodule to their latest.

```
git submodule foreach "(git checkout main; git pull)&"
```

> **_IMPORTANT:_**  Please note that the aforementioned command pulls only the "main" branch by default.
