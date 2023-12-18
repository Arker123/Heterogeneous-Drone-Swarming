# Heterogeneous-Drone-Swarming

## Installation

### Docker
You'll need to install Docker in your computer, if you've used Docker before this step should be straight forward, otherwise check this link for more information about it.

- Installation's instructions for Ubuntu can be found [HERE](https://docs.docker.com/engine/installation/linux/ubuntu/)
- Installation's instructions for Windows can be found [HERE](https://docs.docker.com/docker-for-windows/install/)
- Installation's instructions for MacOS can be found [HERE](https://docs.docker.com/docker-for-mac/install/)

### Pull images for ROS 
docker pull osrf/ros:noetic-desktop-full

docker run -it --net=host osrf/ros:noetic-desktop-full roscore

docker run -it --net=host osrf/ros:noetic-desktop-full bash
