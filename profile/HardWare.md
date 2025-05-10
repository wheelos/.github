**Autonomous Driving Hardware Support Matrix**

This document provides an industry-aligned overview of hardware supported by our autonomous driving software stack. It draws on best practices and widely adopted sensors and compute platforms in the autonomous vehicle domain.

---

## 1. Compute Units

Our software stack supports a range of edge computing devices commonly used for on-vehicle inference and control.

| **Model**                | **Image**                                            | **Supported** | **Notes**                                         |
| ------------------------ | ---------------------------------------------------- | ------------- | ------------------------------------------------- |
| Raspberry Pi 5           | <img src="images/raspberry-pi-5.jpg" width="100">    | Yes           | Suitable for prototyping, limited AI performance  |
| D-Robotics RDK™ X5       | <img src="images/D-Robotics-RDK-X5.jpg" width="100"> | No            | Custom robotics development kit                   |
| D-Robotics J6            |                                                      | No            | Under evaluation                                  |
| NVIDIA Jetson Orin Nano  | <img src="images/jetson-orin-nano.png" width="100">  | Yes           | Quad-core ARM CPU + 60 TOPS AI accelerator        |
| NVIDIA Jetson Orin NX    | <img src="images/jetson-orin-nx.png" width="100">    | Yes           | 100+ TOPS, ideal for mid-tier autonomous features |
| NVIDIA Jetson AGX Orin   | <img src="images/jetson-agx-orin.png" width="100">   | Yes           | 275 TOPS, high-end performance                    |
| NVIDIA Jetson AGX Xavier | <img src="images/jetson-agx-xavier.png" width="100"> | Yes           | 32 TOPS, established in robotics                  |
| NVIDIA Jetson Xavier NX  | <img src="images/jetson-xavier-nx.png" width="100">  | Yes           | 21 TOPS, compact form factor                      |
| NVIDIA Jetson TX2        | <img src="images/jetson-tx2.png" width="100">        | Yes           | Legacy platform, still supported                  |
| NVIDIA Jetson Nano       | <img src="images/jetson-nano.jpeg" width="100">      | Yes           | Entry-level AI, suitable for simple tasks         |

---

## 2. LiDAR Sensors

High-resolution LiDAR sensors are critical for 3D environment perception.

| **Model**             | **Image**                                          | **Supported** | **Notes**                                 |
| --------------------- | -------------------------------------------------- | ------------- | ----------------------------------------- |
| Velodyne VLP-16       | <img src="images/velodyne-vlp-16.jpg" width="100"> | Yes           | 16-channel, 100m range                    |
| Ouster OS1            | <img src="images/ouster-os1.jpg" width="100">      | Yes           | 128 channels, high-resolution point cloud |
| Hesai Pandar64        | <img src="images/hesai-pandar64.jpg" width="100">  | Yes           | Long-range, 200m                          |
| Livox Horizon         | <img src="images/livox-horizon.jpg" width="100">   | Yes           | Mid-range, non-repetitive scanning        |
| RoboSense RS-LiDAR-M1 | <img src="images/robosense-m1.jpg" width="100">    | No            | Under integration                         |

---

## 3. Cameras

Visual sensors for object detection and lane tracking.

| **Model**              | **Image**                                          | **Supported** | **Notes**                                |
| ---------------------- | -------------------------------------------------- | ------------- | ---------------------------------------- |
| FLIR Blackfly S        | <img src="images/flir-blackfly.jpg" width="100">   | Yes           | Global shutter, up to 20 FPS at full res |
| Basler Ace U           | <img src="images/basler-ace.jpg" width="100">      | Yes           | GigE interface, low latency              |
| Huawei HiLens SmartCam | <img src="images/hilens-smartcam.jpg" width="100"> | Yes           | On-board AI acceleration                 |
| Logitech C920          | <img src="images/logitech-c920.jpg" width="100">   | No            | Consumer-grade, research only            |
| ZED 2 (Stereo)         | <img src="images/zed2.jpg" width="100">            | Yes           | Stereo depth camera, integrated IMU      |

---

## 4. Positioning Devices (GNSS/INS)

Precise localization modules combining GNSS and inertial navigation.

| **Model**        | **Image**                                          | **Supported** | **Notes**              |
| ---------------- | -------------------------------------------------- | ------------- | ---------------------- |
| NovAtel OEM7     | <img src="images/novatel-oem7.jpg" width="100">    | Yes           | Centimeter-level RTK   |
| u-blox ZED-F9P   | <img src="images/ublox-zedf9p.jpg" width="100">    | Yes           | Multi-band RTK         |
| Hemisphere S321+ | <img src="images/hemisphere-s321.jpg" width="100"> | No            | Under evaluation       |
| VectorNav VN-300 | <img src="images/vectornav-vn300.jpg" width="100"> | Yes           | Tight-coupled GNSS/INS |

---

## 5. Millimeter-Wave Radar

Short-range and long-range radar for collision avoidance and speed estimation.

| **Model**          | **Image**                                             | **Supported** | **Notes**                    |
| ------------------ | ----------------------------------------------------- | ------------- | ---------------------------- |
| TI AWR1642         | <img src="images/ti-awr1642.jpg" width="100">         | Yes           | 76–81 GHz, radar-on-chip     |
| NXP MR2001         | <img src="images/nxp-mr2001.jpg" width="100">         | Yes           | Short-range automotive radar |
| Continental ARS408 | <img src="images/continental-ars408.jpg" width="100"> | No            | OEM integration pending      |

---

## 6. By-Wire Vehicle Interfaces

Actuation interfaces for steering, braking, and throttle control.

| **Model**               | **Image**                                        | **Supported** | **Notes**                                    |
| ----------------------- | ------------------------------------------------ | ------------- | -------------------------------------------- |
| ClearMotion CM Autonomy |                                                  | Yes           | CAN-based drive-by-wire                      |
| EPIC Autonomous Kit     | <img src="images/epic-autonomy.jpg" width="100"> | Yes           | Integrated steer-by-wire and braking control |
| Faurecia X-by-Wire      |                                                  | No            | Under evaluation                             |

---

*For any hardware not listed or further integration inquiries, please contact the hardware integration team.*
