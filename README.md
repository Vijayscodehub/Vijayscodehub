<h2>Vijay Mistry</h2>

<p>
  <strong>AI & Machine Learning Engineer · ADAS & Autonomous Driving</strong><br/>
  M.Eng. International Automotive Engineering · Technische Hochschule Ingolstadt, Germany
</p>

<p>
  <a href="https://www.linkedin.com/in/vijaymistry-ln/"><img src="https://img.shields.io/badge/LinkedIn-Vijay_Mistry-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Munich,_Germany-2E7D32?style=flat&logo=googlemaps&logoColor=white" alt="Location"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Machine_Learning-Deep_Learning-0d1117?style=flat" alt="Machine Learning"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Computer_Vision-Sensor_Fusion-0d1117?style=flat" alt="Computer Vision"/>
  &nbsp;
  <img src="https://img.shields.io/badge/ADAS-Autonomous_Driving-0d1117?style=flat" alt="ADAS"/>
</p>

---

## 🧠 About me

AI and machine learning engineer focused on ADAS and autonomous driving, with industry experience at BMW, CARIAD, Kärcher and Porsche Engineering. I like taking a problem all the way from raw sensor data to a decision the vehicle can act on.

I build perception pipelines that fuse camera, radar and LiDAR, train detection and segmentation models in PyTorch, and turn their outputs into control, from a rule-based adaptive cruise controller to a PPO agent trained in Gymnasium. On the automotive side I have tested AEB functions against NCAP scenarios in simulation, debugged with MCAP logs, and written C++ and Python features on ROS 1/2 for autonomous robots.

My master's thesis at CARIAD was on landmark-based radar SLAM with factor graph optimization for assisted parking. Outside of that I enjoy rebuilding ML from first principles: a neural network in pure NumPy with manual backprop, a CNN with a hand-written training loop, and an SSD-style detector from scratch. Knowing what happens under the hood makes debugging a lot faster.

Away from the screen: volleyball, football and chess. The kind of person who enjoys a well-tuned control loop as much as a well-planned endgame.

📍 Munich, Germany · Open to relocating<br/>
🌐 English C1 · German B2

## What I work on

<img src="focus_areas.svg" width="100%" alt="Focus areas: Machine Learning & AI, Computer Vision, Sensor Fusion, ADAS & Autonomous Driving, SLAM, Reinforcement Learning"/>

## 💼 Experience

| | Role | Company |
|:-:|---|---|
| <img src="assets/logos/bmw.png" alt="BMW" width="32" height="32"> | Intern: Driver Assistance Systems – Autonomous Emergency Braking (AEB) | BMW AG |
| <img src="assets/logos/cariad.png" alt="CARIAD" width="32" height="32"> | Master Thesis: Landmark-Based RADAR SLAM Using Factor Graph Optimization for ADAS and Autonomous Driving | Volkswagen Group – CARIAD SE |
| <img src="assets/logos/kaercher.png" alt="Kärcher" width="32" height="32"> | Intern: Algorithm Development & Integration – Automated Driving | Alfred Kärcher SE & Co. KG |
| <img src="assets/logos/porsche.jpg" alt="Porsche Engineering" width="32" height="32"> | Intern: Software Function Development | Porsche Engineering Group |
| <img src="assets/logos/thi.png" alt="TH Ingolstadt" width="32" height="32"> | Studentische Hilfskraft (Student Research Assistant) | CARISSMA Institute (C-ECOS), TH Ingolstadt |

## 🚗 Featured projects

<table>
  <tr>
    <td width="65%">
      <h3>
        <a href="https://github.com/Vijayscodehub/Camera-Radar-Fusion-with-Object-Detection-Segmentation-for-Reinforcement-Learning-Based-ACC-">
          Camera–Radar Fusion for RL-Based Adaptive Cruise Control
        </a>
      </h3>
      <p>
        Perception pipeline on nuScenes that combines YOLO object detection, SegFormer
        drivable-area segmentation and front-radar range/velocity to find the lead vehicle
        in the driving path and estimate its distance, relative speed and time-to-collision.
        Adaptive cruise control is solved two ways: a rule-based distance/TTC controller and
        a PPO agent trained for 50,000 timesteps in Gymnasium.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Collision_Rate-5%25-brightgreen?style=flat" alt="Collision rate 5%"/>
        <img src="https://img.shields.io/badge/Gap_Error-4.6_m-blue?style=flat" alt="Gap error 4.6 m"/>
        <img src="https://img.shields.io/badge/Scenarios-100_randomized-orange?style=flat" alt="100 randomized scenarios"/>
        <img src="https://img.shields.io/badge/Real--data_Tests-0_collisions-red?style=flat" alt="Real-data tests with 0 collisions"/>
      </p>
    </td>
    <td width="35%" align="center">
      <img src="https://img.shields.io/badge/PyTorch-YOLO_·_SegFormer-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/><br/><br/>
      <img src="https://img.shields.io/badge/PPO-Gymnasium-0081A5?style=for-the-badge" alt="PPO"/><br/><br/>
      <img src="https://img.shields.io/badge/nuScenes-Camera_+_Radar-0d1117?style=for-the-badge" alt="nuScenes"/>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="65%">
      <h3>
        <a href="https://github.com/Vijayscodehub/ML_pedestrian_detection_and_tracking">
          Camera–LiDAR Pedestrian Detection, Depth Estimation & Tracking
        </a>
      </h3>
      <p>
        Detects pedestrians on KITTI Tracking with a fine-tuned YOLO11n, projects calibrated
        LiDAR points into the image to estimate each person's depth and 3D position, and keeps
        identities across frames with ByteTrack.
      </p>
      <p>
        <img src="https://img.shields.io/badge/mAP@50-40.6%25_%E2%86%92_47.4%25-brightgreen?style=flat" alt="mAP@50 40.6% to 47.4%"/>
        <img src="https://img.shields.io/badge/Recall-39.8%25_%E2%86%92_44.6%25-blue?style=flat" alt="Recall 39.8% to 44.6%"/>
        <img src="https://img.shields.io/badge/Median_Range_Error-12.5_cm-orange?style=flat" alt="Median range error 12.5 cm"/>
        <img src="https://img.shields.io/badge/Matched_Detections-1,412-red?style=flat" alt="1,412 matched detections"/>
      </p>
    </td>
    <td width="35%" align="center">
      <img src="https://img.shields.io/badge/YOLO11-Fine--tuned-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" alt="YOLO11"/><br/><br/>
      <img src="https://img.shields.io/badge/OpenCV-LiDAR_Projection-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/><br/><br/>
      <img src="https://img.shields.io/badge/KITTI-ByteTrack-0d1117?style=for-the-badge" alt="KITTI"/>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="65%">
      <h3>
        <a href="https://github.com/Vijayscodehub/vehicle_detection_from_scratch">
          Vehicle Detection from Scratch 🚧
        </a>
      </h3>
      <p>
        An SSD-style vehicle detector built from custom PyTorch components and trained on CPU:
        CNN backbone, anchor generation, IoU matching, box encoding, classification and
        Smooth L1 losses, hard-negative mining and non-maximum suppression. No pretrained
        backbones or ready-made detectors. The dataset is a curated 500-image BDD100K subset with
        written annotation guidelines and train/validation/test splits made by source video,
        so near-identical frames never leak between splits. Work in progress: annotation is
        underway and no validation or test results are reported yet.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Status-Work_in_progress-yellow?style=flat" alt="Work in progress"/>
        <img src="https://img.shields.io/badge/Dataset-500_images_·_25_videos-blue?style=flat" alt="500 images from 25 videos"/>
        <img src="https://img.shields.io/badge/Split-300_%2F_100_%2F_100_by_video-orange?style=flat" alt="300/100/100 split by video"/>
        <img src="https://img.shields.io/badge/Unit_Tests-21_passing-brightgreen?style=flat" alt="21 unit tests passing"/>
      </p>
    </td>
    <td width="35%" align="center">
      <img src="https://img.shields.io/badge/PyTorch-Custom_SSD-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch custom SSD"/><br/><br/>
      <img src="https://img.shields.io/badge/CPU_only-No_pretrained_weights-555555?style=for-the-badge" alt="CPU only, no pretrained weights"/><br/><br/>
      <img src="https://img.shields.io/badge/BDD100K-Curated_subset-0d1117?style=for-the-badge" alt="BDD100K curated subset"/>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="65%">
      <h3>Automotive Perception for Automated Driving / ADAS</h3>
      <p>
        Collective perception with a BMW test vehicle at the CARISSMA Institute, TH Ingolstadt.
        Collected real-world radar and camera object lists with a Perception Development Kit (PDK),
        processed and shared the sensor data between participants, and developed filtering algorithms
        that remove false-positive and false-negative detections to improve object detection.
        Results were visualized and evaluated in a virtual environment.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Test_Vehicle-BMW-blue?style=flat" alt="BMW test vehicle"/>
        <img src="https://img.shields.io/badge/Sensors-Radar_+_Camera-brightgreen?style=flat" alt="Radar and camera"/>
        <img src="https://img.shields.io/badge/Data-Real--world_object_lists-orange?style=flat" alt="Real-world object lists"/>
        <img src="https://img.shields.io/badge/Filtering-FP_%2F_FN_detections-red?style=flat" alt="False-positive and false-negative filtering"/>
      </p>
    </td>
    <td width="35%" align="center">
      <img src="https://img.shields.io/badge/ROS-Sensor_Data-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS"/><br/><br/>
      <img src="https://img.shields.io/badge/C++_·_Python-Algorithms-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++ and Python"/><br/><br/>
      <img src="https://img.shields.io/badge/Collective-Perception-0d1117?style=for-the-badge" alt="Collective perception"/>
    </td>
  </tr>
</table>

---

## 🗂 Projects

| Project | Description | Result | Stack |
|---|---|---|---|
| [vehicle_detection_from_scratch](https://github.com/Vijayscodehub/vehicle_detection_from_scratch) | Custom SSD-style vehicle detector on CPU (anchors, IoU matching, losses, NMS) with a curated 500-image BDD100K subset, annotation guidelines and video-level splits | 🚧 Work in progress | PyTorch |
| [Supervised_learning_CIFAR10](https://github.com/Vijayscodehub/Supervised_learning_CIFAR10) | Hand-designed CNN, hand-written training loop, validation-only model selection, error analysis | **77.57%** test accuracy | PyTorch · TensorBoard |
| [numpy_mlp_fashion_mnist](https://github.com/Vijayscodehub/numpy_mlp_fashion_mnist) | Neural network in pure NumPy: manual backprop, SGD and a numerical gradient check | **82.81%** test accuracy | NumPy |
| [pytorch_mlp_fashion_mnist_project3](https://github.com/Vijayscodehub/pytorch_mlp_fashion_mnist_project3) | The same MLP rebuilt in PyTorch, mapping every manual step to autograd and optimizers | **81.83%** test accuracy | PyTorch |
| [automotive-ai-journey](https://github.com/Vijayscodehub/automotive-ai-journey) | Learning path from ML foundations to vision perception, an automotive RAG assistant and a multimodal capstone | Ongoing | Python |
| Modelling & Simulation of an Automotive Braking System | Physics-based Simulink model of vehicle and wheel dynamics with a hysteresis-based ABS controller, simulated with and without ABS | Shorter braking distance with ABS | MATLAB · Simulink |

---

## 🛠 Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logo=mathworks&logoColor=white)

**Machine learning & deep learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat&logo=ultralytics&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium%20·%20PPO-0081A5?style=flat)
![TensorBoard](https://img.shields.io/badge/TensorBoard-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**Computer vision & perception**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Sensor Fusion](https://img.shields.io/badge/Camera%20·%20Radar%20·%20LiDAR%20Fusion-24292F?style=flat)
![SLAM](https://img.shields.io/badge/SLAM%20·%20Factor%20Graphs-24292F?style=flat)
![Datasets](https://img.shields.io/badge/nuScenes%20·%20KITTI%20·%20BDD100K-24292F?style=flat)

**ADAS & robotics tools**

![ROS](https://img.shields.io/badge/ROS%201%2F2-22314E?style=flat&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat&logo=mathworks&logoColor=white)
![Foxglove](https://img.shields.io/badge/Foxglove%20%2F%20MCAP-6F3BE8?style=flat)
![CAN](https://img.shields.io/badge/CAN%20·%20LIN%20·%20FlexRay-555555?style=flat)

**Development**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)

---

## 📊 GitHub stats

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Vijayscodehub&theme=default" alt="GitHub stats" height="170"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Vijayscodehub&theme=default" alt="Top languages" height="170"/>

</div>

---

## 🤝 Connect

<div align="center">

<a href="https://www.linkedin.com/in/vijaymistry-ln/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
&nbsp;&nbsp;
<a href="mailto:vijaymistry4532@gmail.com">
  <img src="https://img.shields.io/badge/Email-vijaymistry4532@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

<br/><br/>

<p>
  Open to full-time roles in <strong>Machine Learning · Computer Vision · Perception · ADAS & Autonomous Driving</strong>.<br/>
  LinkedIn or email are the best ways to reach me.
</p>

<img src="https://komarev.com/ghpvc/?username=Vijayscodehub&label=Profile%20views&color=0A66C2&style=flat" alt="Profile views"/>

</div>
