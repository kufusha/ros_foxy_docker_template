FROM osrf/ros:foxy-desktop

# for gnu screen
ENV SHELL /bin/bash

RUN apt-get update && apt-get install -y \
    vim \
    git \
    screen \
    && rm -rf /var/lib/apt/lists/*

# setup ros2 enviroment param
RUN echo "source /opt/ros/foxy/setup.bash" >> ~/.bashrc \
    && /bin/bash -c "source ~/.bashrc"