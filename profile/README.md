
<img src="https://user-images.githubusercontent.com/92492605/201941889-f4a18508-506d-4b2e-bd12-ac9e4553c2b9.png" width="200" height="200" />

# Welcome :boat:
Iceberg ASV is a student-led, inter-disciplinary engineering competition team representing Memorial University at the annual International [RoboBoat](https://robonation.org/programs/roboboat/) Competition in Florida. Our team works collaboratively to design, construct, and test an Autonomous Surface Vehicle (ASV). 

# GitHub Structure
Outline of how our repositories are structured.

## asv-system
[asv-system](https://github.com/IcebergASV/asv) is our *main repository* that integrates all software used on our boat. There exists asv-system [submodules](https://www.atlassian.com/git/tutorials/git-submodule) for each hardware component, such as [asv-lidar](https://github.com/IcebergASV/asv-lidar) and [asv-camera](https://github.com/IcebergASV/asv-camera). 

``` mermaid
graph TD;
    asv-system-->asv-lidar;
    asv-system-->asv-camera;
    asv-system-->asv-imu;
    asv-system-->asv-pixhawk;
```

## gz-simulator
[gz-simulator](https://github.com/IcebergASV/gz-simulator) contains all software and resources used in our GAZEBO simulation environment.


