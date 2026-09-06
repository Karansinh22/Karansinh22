<div align="center">

<img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/header.svg" alt="Karansinh Desai — Robotics · Autonomy · Applied AI/ML" width="100%"/>

<a href="https://www.linkedin.com/in/karansinh-desai-024144284">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Karansinh22?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-Browse-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/>
</a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1600&duration=4200&color=6F90AE&center=true&vCenter=true&width=720&height=34&lines=Building+robots+that+perceive%2C+decide+and+act.;ROS+2+%C2%B7+Computer+vision+%C2%B7+Applied+machine+learning." alt=""/>

<img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/>

</div>

## About

I build systems that **perceive, decide and act** — from autonomous ground and aerial robots running on ROS 2
and NVIDIA Jetson hardware, to machine learning pipelines that turn messy real-world data into decisions.

My work sits at the intersection of three things I care about:

- **Robotics & autonomy** — motion control, sensor fusion and navigation that runs on real hardware, not just in a notebook
- **Computer vision & perception** — making a camera and a depth sensor into something a robot can reason with
- **Applied machine learning** — models that are measured honestly and deployed, not left at the training script

I care about engineering that survives contact with reality: honest benchmarks, reproducible pipelines,
and code that runs on the embedded target it was written for.

## Focus Areas

<table>
<tr>
<td width="33%" valign="top">

### 🤖 Robotics & Autonomy
ROS 2 (Humble) · Gazebo simulation · `ros2_control` · URDF modelling · sensor fusion (IMU, LiDAR, encoders) · GNSS-visual-inertial odometry · autonomous navigation & state machines

</td>
<td width="33%" valign="top">

### 👁️ Computer Vision
Stereo camera calibration · depth perception (RealSense D455) · object detection (YOLOv8 / OBB) · OCR pipelines · real-time video processing with OpenCV

</td>
<td width="33%" valign="top">

### 🧠 AI / ML & Data
Ensemble learning (XGBoost, CatBoost) · feature engineering · class-imbalance handling · NLP & speech pipelines · large-scale data engineering · analytics dashboards

</td>
</tr>
</table>

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## Featured Projects

### 🏥 [Companio — Autonomous Healthcare Assistance Robot](https://github.com/Karansinh22/ROBOFEST5.0_Companio_Healthcare)
> **Robofest 5.0** (GUJCOST) · Team Roboraptos · Robotics Software Engineer

A compact mobile manipulator that maps a hospital ward, learns named rooms, and autonomously delivers
items between them while avoiding people and obstacles. Runs **2D SLAM** (RPLidar A1 + GMapping with
wheel-encoder odometry), **AMCL localisation with move_base/DWA** planning and re-planning, and **two
4-DOF servo arms** driven by analytic and numerical inverse kinematics. Adds voice commands
("go to Ward A"), a live web telemetry dashboard, and line/zone following with QR junction routing —
the whole stack containerised on a Raspberry Pi 5.

`ROS Noetic` `Python` `SLAM` `AMCL / move_base` `Inverse Kinematics` `Docker` `Raspberry Pi 5`

---

### 🌾 [Autonomous Agrobot](https://github.com/Karansinh22/Krishna_Arduino_Unoq) — AI Precision Weed Control
> **Arduino Physical AI Challenge India 2026** · Team Krishna · Track: Industrial AI Sustainability

An autonomous field robot that replaces blanket herbicide spraying with targeted, per-weed application.
A **YOLOv8-OBB** model identifies weeds from crops in real time on an **Arduino UNO Q**, while an **RPLIDAR A1**
handles obstacle awareness and row navigation. Includes a live web dashboard for field monitoring.

`Python` `YOLOv8-OBB` `RPLIDAR A1` `Embedded AI` `C++`

---

### 🎙️ [CMIS — Contextual Meeting Intelligence System](https://github.com/Karansinh22/CMIS)
A local-first tool that turns meeting recordings into **structured, queryable, persistent knowledge** —
not just a transcript. Speaker-diarized transcription feeds an NLP layer that extracts typed objects
(decisions, action items with urgency, topics) into a context store, with **MinHash/LSH recurring-topic
detection** that surfaces when a subject keeps resurfacing across meetings.

`Python` `JavaScript` `NLP` `SQLite` `Docker` `Full-Stack`

---

### 📈 [IPO Prediction Model](https://github.com/Karansinh22/IPO_PREDICTION_MODEL)
A fundamentals-driven ML platform that predicts IPO listing gains and classifies investment risk.
Feature engineering and a **stacking ensemble of XGBoost models** with **SMOTETomek** class balancing
lifted accuracy from 68% to **85.85%** — deployed as a web application with a live data scraper.

| Accuracy | Precision | Recall | F1 |
|:---:|:---:|:---:|:---:|
| **85.85%** | 87% | 86% | 86% |

`Python` `XGBoost` `CatBoost` `scikit-learn` `Flask` `Web Scraping`

---

### 🇮🇳 [Aadhaar Data Analysis Platform](https://github.com/Karansinh22/UIDAI_data_hackathon_solution)
An analytics pipeline for India's digital identity system that processes **5M+ records in under two minutes**
— down from 4+ hours — through strict typing and vectorised Pandas. Delivers population-normalised
state/district analysis, anomaly detection across 915 districts, demand forecasting, and an interactive
Streamlit dashboard with choropleth mapping.

`Python` `Pandas` `Plotly` `scikit-learn` `Streamlit` `GeoJSON`

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Robotics · Embedded · Systems**

![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6C00?style=for-the-badge&logo=gazebo&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![RPLIDAR](https://img.shields.io/badge/RPLIDAR-6366F1?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**AI / ML · Vision · Data**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/Tesseract%20OCR-4E9A06?style=for-the-badge)

**Development · Deployment**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## GitHub Activity

<div align="center">

<img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/languages.svg" alt="Language distribution across public repositories" width="46%"/>
&nbsp;&nbsp;
<img src="https://streak-stats.demolab.com?user=Karansinh22&hide_border=true&border_radius=12&background=0B1220&stroke=1E3E60&ring=22D3EE&fire=76B900&currStreakLabel=22D3EE&sideLabels=9FC5E8&dates=55738F&sideNums=EDF4FF&currStreakNum=EDF4FF&disable_animations=true" alt="Contribution streak" width="50%"/>

</div>

## Currently

- 🔭 Building autonomous ground and aerial robotics systems on **ROS 2 + NVIDIA Jetson**
- 🌱 Going deeper on **visual-inertial odometry**, sensor fusion and GPS-denied navigation
- 🎯 Interested in **robotics, autonomy, perception and applied ML** roles and collaborations
- 💬 Happy to talk about ROS 2, embedded computer vision, or squeezing ML models onto edge hardware

<div align="center">

<img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/>

**Let's connect**

<a href="https://www.linkedin.com/in/karansinh-desai-024144284">
  <img src="https://img.shields.io/badge/LinkedIn-Karansinh%20Desai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

</div>
