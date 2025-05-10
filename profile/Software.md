Certainly! Below is an updated and comprehensive list of software tools and platforms supporting autonomous driving systems, excluding any ROS-related content and presented in English. This compilation reflects current industry best practices and encompasses various components essential for autonomous vehicle development.

---

## 1. Simulation Tools

* **[CARLA](https://carla.org)**
  An open-source urban driving simulator supporting diverse sensor configurations and environmental conditions, ideal for autonomous driving research and validation.&#x20;

* **[Apollo Simulation](https://apollo.auto)**
  A high-fidelity simulation environment provided by Baidu's Apollo platform, facilitating comprehensive autonomous driving testing.

* **[AirSim](https://github.com/Microsoft/AirSim)**
  Developed by Microsoft, AirSim is a high-fidelity visual and physical simulator based on Unreal Engine, supporting various vehicle and sensor models.&#x20;

* **[LGSVL Simulator](https://www.lgsvlsimulator.com)**
  A high-fidelity simulator developed by LG, compatible with Apollo and Autoware, suitable for end-to-end autonomous driving system testing.&#x20;

* **[Gazebo](https://gazebosim.org)**
  A widely-used 3D virtual environment simulator for robotic systems, supporting autonomous driving algorithm testing.

* **[Waymax](https://github.com/waymo-research/waymax)**
  A data-driven multi-agent simulation platform developed by Waymo, focusing on decision-making and planning module testing.

* **[Huawei Octopus](https://www.huawei.com)**
  Huawei's autonomous driving development platform offering data services, training services, and simulation services, supporting large-scale parallel simulations.

* **[MathWorks Automated Driving Toolbox](https://www.mathworks.com/products/automated-driving.html)**
  Provides tools for designing and testing perception systems, supporting multi-sensor fusion and high-definition map data access.

---

## 2. High-Definition (HD) Mapping Tools

* **[Apollo HD Map](https://apollo.auto)**
  Baidu Apollo's high-definition mapping solution supporting autonomous vehicle localization and path planning.

* **[HERE HD Live Map](https://www.here.com)**
  Offers real-time updated high-definition maps, aiding autonomous vehicle positioning and navigation.

* **[TomTom ADAS Map](https://www.tomtom.com)**
  Provides advanced driver assistance system maps, supporting lane-level navigation and path planning.([Reuters][1])

* **[Lanelet2](https://github.com/fzi-forschungszentrum-informatik/Lanelet2)**
  An open-source lane-level map format suitable for autonomous driving research and development.

* **[DeepMap](https://en.wikipedia.org/wiki/DeepMap)**
  Offers high-precision mapping solutions with real-time updates and vehicle localization support; acquired by NVIDIA to enhance its autonomous driving platform.

* **[Jakarto HD Maps](https://www.jakarto.com/en/hd-map)**
  Provides centimeter-level precision HD maps using LiDAR and imagery data, creating high-definition digital twins of the environment.([jakarto.com][2])

* **[iMerit HD Mapping](https://imerit.net/hd-mapping-autonomous-vehicles/)**
  Delivers high-quality, scalable, and flexible HD mapping solutions with expertise in building and labeling HD maps for autonomous vehicle companies.([iMerit][3])

---

## 3. Data Annotation Tools

* **[Scale AI](https://scale.com)**
  Provides high-quality data annotation services, supporting autonomous driving data processing and management.

* **[Labelbox](https://labelbox.com)**
  Offers a scalable data annotation platform supporting various data types and workflows.

* **[CVAT](https://cvat.org)**
  An open-source computer vision annotation tool supporting video and image annotation tasks.

* **[Supervisely](https://supervisely.com)**
  Provides an end-to-end data annotation and model training platform, supporting team collaboration and automated workflows.

* **[iMerit Data Annotation](https://imerit.net/domains/autonomous-vehicles/)**
  Offers comprehensive data labeling services across computer vision applications, including LiDAR annotation, semantic segmentation, and object tracking.([iMerit][4])

---

## 4. Model Training Frameworks

* **[NVIDIA DriveWorks & TAO Toolkit](https://developer.nvidia.com/drive)**
  Provides tools for developing and deploying autonomous driving models, supporting end-to-end training workflows.

* **[TensorFlow](https://www.tensorflow.org)** / **[PyTorch](https://pytorch.org)**
  Leading deep learning frameworks widely used in developing and training autonomous driving models.

* **[MMDetection3D](https://github.com/open-mmlab/mmdetection3d)**
  A PyTorch-based open-source toolbox for 3D object detection, supporting various 3D detection models.

* **[Horovod](https://github.com/horovod/horovod)**
  A distributed training framework supporting TensorFlow, Keras, PyTorch, and more, suitable for large-scale model training.

* **[Tesla Dojo](https://en.wikipedia.org/wiki/Tesla_Dojo)**
  A supercomputer designed by Tesla for computer vision video processing and recognition, used to train Tesla's machine learning models for its Full Self-Driving system.([en.wikipedia.org][5])

---

## 5. System Architecture & Middleware

* **[AUTOSAR Adaptive Platform](https://www.autosar.org)**
  A standardized software architecture for advanced driver assistance systems and autonomous driving, supporting high-performance computing and service-oriented communication.

* **[DDS (Data Distribution Service)](https://www.omg.org/dds/)**
  A real-time data exchange middleware standard supporting high reliability and low latency data communication, adopted by the AUTOSAR platform.

* **[Apex.AI](https://www.apex.ai)**
  Provides safety-certified autonomous driving software platforms, suitable for applications with high functional safety requirements.

---

## 6. Compute Platforms & Hardware Support

* **[NVIDIA DRIVE AGX](https://developer.nvidia.com/drive)**
  NVIDIA's autonomous driving computing platform supporting various applications from advanced driver assistance systems to full autonomy.

* **[Qualcomm Snapdragon Ride](https://www.qualcomm.com/products/automotive)**
  A high-performance, low-power autonomous driving platform supporting functions from Level 1 to Level 5 autonomy.

* **[Arm Automotive Enhanced (AE) Processors](https://www.arm.com/solutions/automotive)**
  Arm's processor architecture for automotive applications, supporting high-performance computing and safety requirements.

* **[NVIDIA Deep Learning Accelerator (NVDLA)](https://en.wikipedia.org/wiki/NVDLA)**
  An open-source hardware neural network AI accelerator by NVIDIA, configurable and scalable for various architecture needs, used in edge computing inference engines including object recognition for autonomous driving.([en.wikipedia.org][6])

---

## 7. Datasets & Evaluation Tools

* **[Waymo Open Dataset](https://waymo.com/open)**
  A large-scale autonomous driving dataset released by Waymo, containing various sensor data suitable for training perception and prediction models.

* **[nuScenes](https://www.nuscenes.org)**
  A multimodal autonomous driving dataset by Motional, featuring 360-degree perception data and comprehensive annotations.&#x20;

* **[Argoverse](https://www.argoverse.org)**
  An autonomous driving dataset by Argo AI, supporting 3D tracking and motion forecasting tasks.

* **[KITTI](http://www.cvlibs.net/datasets/kitti/)**
  A classic autonomous driving dataset widely used for evaluating computer vision algorithms.

* **[Waymo Open Motion Dataset](https://waymo.com/open/data/motion/)**
  A dataset focused on motion prediction tasks, supporting multi-agent interaction modeling.([arXiv][7])

* **[aiMotive Dataset](https://arxiv.org/abs/2211.09445)**
  A multimodal dataset for robust autonomous driving with long-range perception, including synchronized LiDAR, camera, and radar data. ([arXiv][8])

* **[V2X-Sim](https://arxiv.org/abs/2202.08449)**
  A multi-agent collaborative perception dataset and benchmark for autonomous driving, facilitating research in vehicle-to-everything communication. ([arXiv][7])

---

This comprehensive list encompasses key software tools and platforms essential for autonomous driving system development, reflecting current industry standards and practices. If you require further assistance, such as tool recommendations tailored to specific requirements or constructing a complete software architecture, please feel free to ask.

[1]: https://www.reuters.com/technology/chinas-deeprouteai-team-up-with-qualcomm-develop-advanced-driver-assistance-2025-04-08/?utm_source=chatgpt.com "China's DeepRoute.ai to team up with Qualcomm to develop advanced driver assistance solutions"
[2]: https://www.jakarto.com/en/hd-map?utm_source=chatgpt.com "HD mapping leader for self-driving vehicles | Jakarto HD Maps"
[3]: https://imerit.net/hd-mapping-autonomous-vehicles/?utm_source=chatgpt.com "HD Mapping For Autonomous Vehicles - iMerit"
[4]: https://imerit.net/domains/autonomous-vehicles/?utm_source=chatgpt.com "Data Annotation For Autonomous Vehicle Technology | iMerit"
[5]: https://en.wikipedia.org/wiki/Tesla_Dojo?utm_source=chatgpt.com "Tesla Dojo"
[6]: https://en.wikipedia.org/wiki/NVDLA?utm_source=chatgpt.com "NVDLA"
[7]: https://arxiv.org/abs/2202.08449?utm_source=chatgpt.com "V2X-Sim: Multi-Agent Collaborative Perception Dataset and Benchmark for Autonomous Driving"
[8]: https://arxiv.org/abs/2211.09445?utm_source=chatgpt.com "aiMotive Dataset: A Multimodal Dataset for Robust Autonomous Driving with Long-Range Perception"
