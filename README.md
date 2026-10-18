# Hi, I'm Carlo 

Industrial Informatics & Robotics Engineer from the **Polytechnic University of Valencia (UPV)**, currently pursuing an **MSc in Artificial Intelligence for Industry and Manufacturing at UNIR**.

My main interests lie at the intersection of **artificial intelligence, computer vision, robotics and autonomous systems**, with a particular focus on perception and intelligent robotic applications.

## Areas of Interest

-  Robotics & Autonomous Systems
-  Computer Vision & Robotic Perception
-  Object Detection & Multi-Object Tracking
-  Artificial Intelligence & Deep Learning
-  ROS 2 & Robot Software
-  Reinforcement Learning
-  Intelligent Manufacturing & Industrial Automation

## Featured Projects

###  Intelligent Robotic Assembly Cell

Autonomous robotic assembly cell developed in **RoboDK** using two **UR5e robots**, integrating **OpenCV** and **EfficientNet-B0** for part classification, pose estimation, grasping and assembly.

The system uses image-to-robot coordinate transformation through **homography**, computer vision-based grasping and dynamic precedence management to coordinate four assembly stations.

---

###  Multi-Object Tracking & Traffic Counting

Computer vision system for **detecting, tracking and counting pedestrians, cars and bicycles** in urban video using **YOLO11s**.

Compared multiple multi-object tracking algorithms under the same experimental conditions:

- **ByteTrack**
- **BoT-SORT**
- **BoT-SORT + Re-ID**
- **OC-SORT**

Implemented bidirectional line-crossing detection, event logging and performance benchmarking.

On the evaluated sequence, **BoT-SORT achieved exact class-level counting** with **21 pedestrians, 45 cars and 1 bicycle**, while **ByteTrack achieved the highest processing speed at 5.43 FPS on CPU**.

The project also analyzes **ID switches, occlusions, trajectory fragmentation and the trade-off between tracking accuracy and computational cost**.

---

###  Sim-to-Sim Domain Randomization

Transfer of reinforcement learning policies between simulation environments using **PPO and domain randomization** over physical parameters.

Improved the return in the target environment from **835 to 1320 (+58%)** and achieved **100% successful episodes without falls**, including robustness analysis using **PCA and t-SNE**.

---

###  Driver Monitoring System

Computer vision system for real-time driver monitoring, including **head-pose estimation, eye-closure detection, distraction analysis and physiological monitoring**.

Designed to detect driver states such as **distraction, microsleep and drowsiness** from visual information.

---

###  MITRE ATT&CK Tactic Classification

Token-level classification of **MITRE ATT&CK tactics** in SSH/Bash sessions using **BERT and UniXcoder**.

Implemented preprocessing, token-level label alignment, Transformer fine-tuning, hyperparameter optimization and layer-freezing strategies, achieving **86.7% accuracy** and **0.724 macro F1-score** with UniXcoder.

## Technologies

### Computer Vision & AI

`Python` · `PyTorch` · `TensorFlow` · `OpenCV` · `YOLO` · `Deep Learning` · `Transformers`

### Robotics

`ROS 2` · `RoboDK` · `UR5e` · `Robot Perception` · `Autonomous Systems`

### Tracking & Perception

`ByteTrack` · `BoT-SORT` · `Re-ID` · `OC-SORT` · `Multi-Object Tracking`

### Other

`Reinforcement Learning` · `PPO` · `Git` · `Linux`
