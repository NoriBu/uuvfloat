# UUV float

## underwater unmanned autonomous vehicle

based on simulation evironment developed in EU SWARM project

[UUV simulator](https://github.com/uuvsimulator/)
[more info](https://uuvsimulator.github.io)
[SWARM](http://swarms.eu/index.html)



## installation

Ubuntu 18.04
ROS Melodic

## development

Visual Studio code

## build

do
```

 git clone https://github.com/uuvsimulator/uuv_simulation_evaluation.git 
```
to your workspace and then 

```

sudo apt install ros-melodic-uuv-simulator


catkin build
```

## run
```

roslaunch uuvfloat_gazebo start_demo_pid_controller.launch 

```

## License

Apache
