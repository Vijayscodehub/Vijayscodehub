<h1 align="left">Hi, I'm Vijay Mistry 👋</h1>

### AI & Machine Learning Engineer · ADAS & Autonomous Driving
*Deep learning · Computer vision · Camera–Radar–LiDAR fusion · Reinforcement learning · M.Eng. TH Ingolstadt*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vijay%20Mistry-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vijaymistry-ln/)
![Location](https://img.shields.io/badge/Location-Ingolstadt%2C%20Germany-2E7D32?logo=googlemaps&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Machine%20Learning-FF6F00)
![Domain](https://img.shields.io/badge/Domain-ADAS%20%26%20Autonomous%20Driving-24292F)
![Languages](https://img.shields.io/badge/English%20C1%20·%20German%20B2-555555)
![Profile views](https://komarev.com/ghpvc/?username=Vijayscodehub&label=Profile%20views&color=0A66C2&style=flat)

---

## 🧠 About me

I build machine learning systems that help vehicles understand the world around them, turning raw camera, radar and LiDAR data into detections, tracks and driving decisions.

I hold an M.Eng. in International Automotive Engineering from Technische Hochschule Ingolstadt. Along the way I worked on automated driving software in industry and research:

- <img src="assets/logos/bmw.png" alt="BMW" width="16" height="16" align="center"> **BMW AG**: tested and debugged the Autonomous Emergency Braking (AEB) function in simulation, including NCAP scenarios and MCAP log analysis
- <img src="assets/logos/cariad.png" alt="CARIAD" width="16" height="16" align="center"> **Volkswagen Group – CARIAD SE**: master thesis on landmark-based **radar SLAM with factor graph optimization** for assisted parking
- <img src="assets/logos/kaercher.png" alt="Kärcher" width="16" height="16" align="center"> **Kärcher**: developed and integrated motion-planning features for the autonomous driving stack of industrial robots (C++, Python, ROS 1/2)
- <img src="assets/logos/porsche.jpg" alt="Porsche" width="16" height="16" align="center"> **Porsche Engineering**: prototyped and tested collision-avoidance algorithms in simulation and on hardware
- <img src="assets/logos/thi.png" alt="TH Ingolstadt" width="16" height="16" align="center"> **CARISSMA Institute (C-ECOS), TH Ingolstadt**: student research assistant (Studentische Hilfskraft) on automotive perception for automated driving. Worked on collective perception with a BMW test vehicle, collected radar and camera object lists, and wrote filters that remove false-positive and false-negative detections (ROS, Python, C++). Also supported battery testing

My ML work covers the full workflow: clean data splits, training from scratch, choosing models on validation data only, a single honest test run, and error analysis.

📍 Ingolstadt, Germany · open to relocating · 🏐 Volleyball, ⚽ football and ♟️ chess when I'm offline

---

## 🚗 Featured projects

### Camera–Radar Fusion with Object Detection & Segmentation for RL-Based Adaptive Cruise Control
Perception pipeline on **nuScenes** that combines YOLO object detection, SegFormer drivable-area segmentation and front-radar range/velocity to find the lead vehicle in the driving path. Adaptive cruise control is done in two ways, a rule-based distance/TTC controller and a **PPO** reinforcement-learning agent trained in Gymnasium.
- **5% collision rate** across 100 randomized scenarios, **4.6 m** mean following-gap error
- Collision-free on 2 real-data-seeded tests

`Python` `PyTorch` `YOLO` `SegFormer (Hugging Face)` `PPO` `Gymnasium` `nuScenes`
→ [Repository](https://github.com/Vijayscodehub/Camera-Radar-Fusion-with-Object-Detection-Segmentation-for-Reinforcement-Learning-Based-ACC-)

### Camera–LiDAR Pedestrian Detection, Depth Estimation & Tracking
Detects pedestrians on **KITTI Tracking**, projects calibrated LiDAR points into the image to estimate each person's depth and 3D position, and keeps identities across frames with ByteTrack.
- Fine-tuned YOLO11n: **mAP@50 40.6% → 47.4%**, recall 39.8% → 44.6%
- **12.5 cm** median range error across 1,412 matched detections

`Python` `PyTorch` `YOLO11` `OpenCV` `ByteTrack` `KITTI`
→ [Repository](https://github.com/Vijayscodehub/ML_pedestrian_detection_and_tracking)

---

## 🗂 ML foundations: built from scratch

| Project | What it shows | Result | Stack |
|---|---|---|---|
| [vehicle_detection_from_scratch](https://github.com/Vijayscodehub/vehicle_detection_from_scratch) | Custom SSD-style vehicle detector on CPU (anchors, IoU matching, losses, NMS) with a curated 500-image BDD100K subset, annotation guidelines and video-level splits | 🚧 Work in progress | PyTorch |
| [Supervised_learning_CIFAR10](https://github.com/Vijayscodehub/Supervised_learning_CIFAR10) | Hand-designed CNN, hand-written training loop, validation-only model selection, error analysis | **77.57%** test accuracy | PyTorch · TensorBoard |
| [numpy_mlp_fashion_mnist](https://github.com/Vijayscodehub/numpy_mlp_fashion_mnist) | Neural network in pure NumPy: manual backprop, SGD and a numerical gradient check | **82.81%** test accuracy | NumPy |
| [pytorch_mlp_fashion_mnist_project3](https://github.com/Vijayscodehub/pytorch_mlp_fashion_mnist_project3) | The same MLP rebuilt in PyTorch, mapping every manual step to autograd and optimizers | **81.83%** test accuracy | PyTorch |
| [automotive-ai-journey](https://github.com/Vijayscodehub/automotive-ai-journey) | Learning path from ML foundations to vision perception, an automotive RAG assistant and a multimodal capstone | Ongoing | Python |

---

## 🔧 Automotive engineering projects

### Modelling & Simulation of an Automotive Braking System
Dynamic Simulink model of a vehicle braking system built from physics-based equations.
- Derived the equations of motion for the vehicle and wheel subsystems, including aerodynamic drag and normal forces
- Implemented a hysteresis-based **ABS controller** that regulates wheel slip and braking torque
- Simulated full braking scenarios with and without ABS; ABS gave a shorter braking distance

`MATLAB` `Simulink`

---

## 🛠 Tech stack

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?logo=mathworks&logoColor=white)

**Machine learning & deep learning**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLO-111F68?logo=ultralytics&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium%20·%20PPO-0081A5)
![TensorBoard](https://img.shields.io/badge/TensorBoard-FF6F00?logo=tensorflow&logoColor=white)

**Computer vision & perception**
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![Sensor Fusion](https://img.shields.io/badge/Camera%20·%20Radar%20·%20LiDAR%20Fusion-24292F)
![SLAM](https://img.shields.io/badge/SLAM%20·%20Factor%20Graphs-24292F)
![Datasets](https://img.shields.io/badge/nuScenes%20·%20KITTI%20·%20BDD100K-24292F)

**ADAS & robotics tools**
![ROS](https://img.shields.io/badge/ROS%201%2F2-22314E?logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?logo=mathworks&logoColor=white)
![Foxglove](https://img.shields.io/badge/Foxglove%20%2F%20MCAP-6F3BE8)
![CAN](https://img.shields.io/badge/CAN%20·%20LIN%20·%20FlexRay-555555)

**Development**
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white)

---

## 📊 GitHub stats

<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Vijayscodehub&theme=default" alt="GitHub stats" height="180">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Vijayscodehub&theme=default" alt="Top languages" height="180">
</p>

---

## 🤝 Connect

Open to full-time roles in **Machine Learning · Computer Vision · Perception · ADAS & Autonomous Driving**.
The best way to reach me is [LinkedIn](https://www.linkedin.com/in/vijaymistry-ln/).
