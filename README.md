# Hi, I'm Carlo 

**Robotics & AI Engineer | ROS 2 · Autonomous Systems · Computer Vision**

Industrial Technologies Engineering graduate from the **Polytechnic University of Valencia (UPV)**, specializing in **Automation and Electronics**, currently pursuing an **MSc in Artificial Intelligence for Industry and Manufacturing at UNIR**.

My main focus is **robotics software development**, particularly the integration of **ROS 2, autonomous navigation, robotic manipulation and AI-based perception**.

I enjoy developing complete robotic systems, combining simulation, sensor processing, motion planning and control to build autonomous solutions. My work also covers computer vision, deep learning and intelligent industrial automation.

##  Robotics, ROS 2 & AI Expertise

Strong technical background in **robotics, computer vision and artificial intelligence**, combining hands-on experience developing autonomous systems with **ROS 2** and academic training in **deep learning, machine learning and intelligent perception**.

- **ROS 2 Development:** Python, nodes, topics, services, actions, launch files, parameters, lifecycle nodes and modular package development.
- **Autonomous Navigation:** Nav2, SLAM Toolbox, AMCL, NavFn, Regulated Pure Pursuit, Behavior Trees and costmap configuration.
- **Robotic Manipulation:** MoveIt 2, motion planning, inverse kinematics, Cartesian trajectories, collision objects, Planning Scene management and gripper control.
- **Simulation & Robot Modeling:** Gazebo Harmonic, URDF/Xacro, ros2_control, robot controllers and sensor simulation.
- **Computer Vision & Deep Learning:** PyTorch, TensorFlow, OpenCV, YOLO, EfficientNet, object detection, instance segmentation, transfer learning and model fine-tuning.
- **Visual Perception & Tracking:** RGB-D processing, 3D object localization, TF2 transformations, multi-object tracking, Re-ID and vision-guided robotic manipulation.
- **Robotic System Integration:** Multi-node architectures, autonomous task coordination, debugging and integration of perception, navigation and manipulation pipelines.

##  Featured Projects

### 1. [Autonomous Mobile Manipulator](https://github.com/ercarlo/autonomous-mobile-manipulator)

**ROS 2 Jazzy · Nav2 · MoveIt 2 · Gazebo Harmonic · YOLO11 · RGB-D Perception**

Development of an autonomous mobile manipulation system integrating a **MiR100 mobile platform, UR5e robotic arm, Robotiq 2F-85 gripper and wrist-mounted Intel RealSense D435 camera**.

The project combines autonomous navigation, AI-based object perception and robotic manipulation within a simulated industrial environment.

**Key implementations:**

- **Navigation:** SLAM Toolbox, AMCL localization, Nav2 path planning, obstacle-aware control and autonomous navigation.
- **Perception:** YOLO11 instance segmentation, RGB-D depth processing, 3D object localization and TF2 coordinate transformations.
- **Manipulation:** MoveIt 2 motion planning, vertical grasping, Cartesian approaches, collision-aware Planning Scene management and object attachment/detachment.
- **Robot Integration:** Custom URDF/Xacro descriptions, Gazebo Harmonic simulation, ros2_control and coordinated execution of robotic subsystems.
- **Mission Coordination:** High-level task execution integrating object pickup, navigation to a selected destination, placement and return to the starting position.

The integrated **Pick → Navigate → Place → Return** workflow has been demonstrated with an apple and a destination workstation. The architecture also incorporates multiple YCB objects and four destination stations for extending the manipulation scenarios.

**[View Repository, Demonstration GIFs & Technical Documentation](https://github.com/ercarlo/autonomous-mobile-manipulator)**

---

### 2. [Intelligent Robotic Assembly Cell](https://github.com/ercarlo/intelligent-robotic-assembly-cell)

**RoboDK · UR5e · Python · OpenCV · EfficientNet-B0**

Autonomous industrial assembly cell using **two UR5e robotic arms**, integrating computer vision, deep learning and robotic manipulation.

Developed a complete perception-to-action workflow combining:

- Deep learning-based part classification using EfficientNet-B0, achieving **97.92% test accuracy**.
- Object orientation estimation using PCA and camera-to-robot coordinate transformation through homography.
- Vision-guided grasping, robotic pick-and-place and coordinated assembly operations.
- Multi-robot task coordination with assembly precedence management across four workstations.

The system demonstrates the integration of **AI perception and robotic automation** in a simulated industrial assembly environment.

---

### 3. Multi-Object Tracking & Traffic Counting

**YOLO11s · ByteTrack · BoT-SORT · Re-ID · OC-SORT · OpenCV**

Computer vision system for detecting, tracking and counting pedestrians, cars and bicycles in urban video.

Implemented and compared multiple tracking algorithms under identical experimental conditions:

- ByteTrack
- BoT-SORT
- BoT-SORT + Re-ID
- OC-SORT

Developed bidirectional line-crossing detection, trajectory management, event logging and performance benchmarking.

On the evaluated sequence, **BoT-SORT achieved exact class-level counting** with 21 pedestrians, 45 cars and 1 bicycle, while **ByteTrack achieved the highest processing speed at 5.43 FPS on CPU**.

The project also investigates ID switches, occlusions, trajectory fragmentation and computational trade-offs.

---

### 4. Sim-to-Sim Domain Randomization

**Reinforcement Learning · PPO · Domain Randomization · Python**

Transfer of reinforcement learning policies between simulated environments through physical parameter randomization.

Improved the target-environment return from **835 to 1320 (+58%)**, achieving **100% successful evaluation episodes without falls**.

Analyzed policy robustness and learned representations using PCA and t-SNE.

---

### 5. Driver Monitoring System

**Computer Vision · OpenCV · Head Pose Estimation · Real-Time Monitoring**

Computer vision-based driver monitoring system integrating head-pose estimation, eye-closure detection, distraction analysis and physiological monitoring.

Designed to identify driver states associated with distraction, microsleep and drowsiness.

---

### 6. MITRE ATT&CK Tactic Classification

**NLP · BERT · UniXcoder · Transformers · PyTorch**

Token-level classification of MITRE ATT&CK tactics in SSH/Bash sessions.

Implemented preprocessing, token-level label alignment, Transformer fine-tuning, hyperparameter optimization and layer-freezing strategies.

Achieved **86.7% accuracy** and **0.724 macro F1-score** using UniXcoder.

## 🛠️ Technical Stack

### Robotics & ROS 2

`ROS 2 Jazzy` · `Nav2` · `MoveIt 2` · `Gazebo Harmonic` · `RViz2` · `TF2` · `ros2_control` · `URDF/Xacro` · `SLAM Toolbox` · `AMCL` · `LiDAR` · `RGB-D` · `RoboDK`

### Programming & Development

`Python` · `Linux / Ubuntu` · `Git` · `ROS 2 Launch` · `YAML` · `Robot Integration`

### Computer Vision & Deep Learning

`PyTorch` · `TensorFlow` · `OpenCV` · `YOLO` · `EfficientNet` · `Transformers` · `Object Detection` · `Instance Segmentation` · `3D Perception`

### Multi-Object Tracking

`ByteTrack` · `BoT-SORT` · `Re-ID` · `OC-SORT` · `Kalman Filters` · `Data Association`

### AI & Reinforcement Learning

`Deep Learning` · `Reinforcement Learning` · `PPO` · `Domain Randomization` · `Transfer Learning`

---

**Main interests:** Robotics Software Engineering · Autonomous Mobile Manipulation · ROS 2 · Robot Perception · Intelligent Automation
