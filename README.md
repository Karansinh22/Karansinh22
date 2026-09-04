<div align="center">

<img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/header.svg" alt="Karansinh Desai — Robotics · Autonomy · Applied AI/ML" width="100%"/>

<a href="https://www.linkedin.com/in/karansinh-desai-024144284">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Karansinh22?tab=repositories">
  <img src="https://img.shields.io/badge/Repositories-Browse-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repositories"/>
</a>
<img src="https://komarev.com/ghpvc/?username=Karansinh22&style=for-the-badge&color=0A66C2&label=PROFILE+VIEWS" alt="Profile views"/>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=900&duration=3400&color=22D3EE&center=true&vCenter=true&width=760&height=45&lines=Building+robots+that+perceive%2C+decide+and+act.;ROS+2+%C2%B7+Gazebo+%C2%B7+NVIDIA+Jetson+%C2%B7+Sensor+Fusion;Computer+Vision+%C2%B7+YOLOv8+%C2%B7+OpenCV+%C2%B7+Depth+Perception;Applied+ML+that+ships%2C+not+just+trains." alt="What I build"/>

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

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

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

---

### 🔤 [CV Text Reader](https://github.com/Karansinh22/CV) · [Speech & Vision Toolkit](https://github.com/Karansinh22/Speechtotext_and_cv)
Real-time assistive perception: reads text from a live camera feed with **Tesseract OCR**, speaks it aloud,
and raises visual/audio alerts on target keywords — with CSV logging for every detection. Paired with a
bidirectional speech-to-text / text-to-speech toolkit.

`Python` `OpenCV` `Tesseract OCR` `Text-to-Speech` `Accessibility`

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## Tech Stack

<div align="center">

**Languages & Core**

<img src="https://skillicons.dev/icons?i=python,cpp,c,js,ts,html,css&theme=dark" alt="Languages"/>

**Robotics · Embedded · Systems**

<img src="https://skillicons.dev/icons?i=ros,arduino,raspberrypi,linux,bash,cmake,docker&theme=dark" alt="Robotics and systems"/>

**AI / ML · Vision · Data**

<img src="https://skillicons.dev/icons?i=pytorch,opencv,sklearn,tensorflow,flask,nodejs,sqlite&theme=dark" alt="AI and data"/>

<br/>

![Gazebo](https://img.shields.io/badge/Gazebo-FF6C00?style=flat-square&logo=gazebo&logoColor=white)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR-4E9A06?style=flat-square)

</div>

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=Karansinh22&show_icons=true&include_all_commits=true&hide_border=true&border_radius=12&title_color=22D3EE&icon_color=76B900&text_color=9FC5E8&bg_color=0B1220" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=Karansinh22&layout=compact&langs_count=8&hide_border=true&border_radius=12&title_color=22D3EE&text_color=9FC5E8&bg_color=0B1220" alt="Top languages"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Karansinh22&hide_border=true&border_radius=12&background=0B1220&stroke=24486E&ring=22D3EE&fire=76B900&currStreakLabel=22D3EE&sideLabels=9FC5E8&dates=5E7C9B&sideNums=F2F7FF&currStreakNum=F2F7FF" alt="Contribution streak"/>

</div>

<div align="center"><img src="https://raw.githubusercontent.com/Karansinh22/Karansinh22/main/assets/divider.svg" width="100%" alt=""/></div>

## Currently

- 🔭 Building autonomous ground and aerial robotics systems on **ROS 2 + NVIDIA Jetson**
- 🌱 Going deeper on **visual-inertial odometry**, sensor fusion and GPS-denied navigation
- 🎯 Interested in **robotics, autonomy, perception and applied ML** roles and collaborations
- 💬 Happy to talk about ROS 2, embedded computer vision, or squeezing ML models onto edge hardware

<br/>

<div align="center">

### Let's connect

<a href="https://www.linkedin.com/in/karansinh-desai-024144284">
  <img src="https://img.shields.io/badge/LinkedIn-Karansinh_Desai-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,50:22D3EE,100:76B900&height=130&section=footer" width="100%" alt=""/>

</div>
