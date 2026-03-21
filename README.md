# 3D LiDAR-Based Environmental Mapping System

## Overview

This project focuses on developing a 3D environmental mapping system using a TF-Luna LiDAR sensor and ESP32. A rotating mechanical structure driven by servo and stepper motors is used to capture spatial data and generate 3D maps.

## Objectives

* Develop rotating LiDAR scanning mechanism
* Interface TF-Luna LiDAR with ESP32
* Implement 2D and 3D spatial mapping
* Enable WiFi-based data transmission
* Validate hardware performance and signal stability

## Features

* 2D LiDAR scanning using servo motor
* 3D mapping using stepper motor rotation
* ESP32-based data acquisition
* WiFi transmission of scan data
* Custom slip ring for continuous rotation
* Hardware debugging and noise reduction

## Hardware Components

* ESP32
* TF-Luna LiDAR sensor
* Stepper motor (NEMA 17)
* Servo motor
* Slip ring (custom)
* Motor driver
* Power supply

## Folder Structure

```
lidar-3d-environment-mapping/
├── cad/
├── circuit/
├── firmware/
├── data/
├── docs/
└── README.md
```

## Project Progress

* [ ] Upload CAD
* [ ] Upload circuit design
* [ ] Upload first prototype failure report
* [ ] Implement 2D WiFi transmission (servo)
* [ ] Implement basic 3D mapping (stepper)

## Development Stages

### Stage 1 – First Prototype

* Initial rotating LiDAR setup
* Basic data acquisition
* Identified motor noise issues
* Power stability debugging

### Stage 2 – 2D Mapping

* Servo-based rotation
* WiFi data transmission
* Real-time scan visualization

### Stage 3 – 3D Mapping

* Stepper motor integration
* Vertical scanning mechanism
* Absolute basic 3D reconstruction

## Challenges Faced

* Motor noise affecting sensor readings
* Power supply instability
* Mechanical alignment issues
* Data synchronization

## Future Improvements

* Sensor fusion with IMU
* SLAM integration
* Real-time 3D visualization
* Higher resolution scanning

## Tech Stack

* ESP32
* Fusion 360
* Python (visualization)
* Embedded C/C++

## Author

Anubhav Suri
