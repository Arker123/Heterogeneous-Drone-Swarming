# Heterogeneous-Drone-Swarming

## Installation

### Docker
You'll need to install Docker in your computer, if you've used Docker before this step should be straight forward, otherwise check this link for more information about it.

- Installation's instructions for Ubuntu can be found [HERE](https://docs.docker.com/engine/installation/linux/ubuntu/)
- Installation's instructions for Windows can be found [HERE](https://docs.docker.com/docker-for-windows/install/)
- Installation's instructions for MacOS can be found [HERE](https://docs.docker.com/docker-for-mac/install/)

### Pull images for ROS 
docker pull osrf/ros:noetic-desktop-full

install nvidia-toolkit 

run ./start.sh to start the docker container

<!-- sudo rm -rf /tmp/.docker.xauth -->
<!-- XAUTH=/tmp/.docker.xauth
xauth_list=$(xauth nlist :0 | tail -n 1 | sed -e 's/^..../ffff/')
if [ ! -f $XAUTH ]; then
    if [ ! -z "$xauth_list" ]; then
        echo $xauth_list | xauth -f $XAUTH nmerge -
    else
        touch $XAUTH
    fi
    chmod a+r $XAUTH
fi
file $XAUTH
echo "-->
