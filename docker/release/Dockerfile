# Build with name tatu/robotti-base
FROM osrf/ros:humble-desktop-full

RUN apt update && apt upgrade -y && apt install -y \
  ninja-build

WORKDIR /
RUN mkdir -p /dev_ws/src
WORKDIR /dev_ws/src
RUN colcon build --cmake-args -DCMAKE_EXPORT_COMPILE_COMMANDS=ON -G Ninja





