
SGADS: Safe and Generalized end-to-end Autonomous Driving System with Reinforcement Learning and Demonstrations
======

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.md) ![example](https://img.shields.io/badge/Python-API-red.svg) ![example](https://img.shields.io/badge/Ubuntu-18.04-yellow.svg) ![example](https://img.shields.io/badge/Logitech-G29-yellow.svg) ![example](https://img.shields.io/badge/CARLA-0.9.10-yellow.svg)
 
## The overview of Human expert collects the datasets via the Logitech G29 steering wheel. This repo is part of [SGADS](https://github.com/Tangzj2020/SGADS) 
![images](G29.png)


## 1.Install CARLA
* Based on Ubuntu 18.04
* Download  [CARLA_0.9.10](https://github.com/carla-simulator/carla/releases)

    `$ export PYTHONPATH=$PYTHONPATH:$YourFolder$/CARLA_0.9.10/PythonAPI/carla/dist/carla-0.9.10-py3.7-linux-x86_64.egg`
    
    `$ cd ~/YourFolder/CARLA_0.9.10/PythonAPI/examples $` and `Add manual_control_steeringwheel_G29.py`
  
    `$ pip install pygame==1.9.6 $`
