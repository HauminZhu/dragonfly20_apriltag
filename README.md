## snap_cam_ros
```
roslaunch snap_cam_ros downward_cam_pose_estimator.launch
```

# apriltag

A collection of apriltag libraries and a ros node.

## apriltag_mit

a c++ library from http://people.csail.mit.edu/kaess/apriltags/

## apriltag_umich

a c library from http://april.eecs.umich.edu/wiki/index.php/AprilTags

## apriltag_ros

a ros node for detecting apriltag.

Detect apriltags in image topic `~image`
```
roslaunch apriltag_ros apriltag_detector_node.launch camera:=camera
```

Detect apriltags in images
```
rosrun apriltag_ros apriltag_detect image1.png image2.png -t 0 -b 2
```
## apriltag_msgs

apriltag ros messages
