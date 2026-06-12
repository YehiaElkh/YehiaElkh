<!-- ████████████████████████████████████████████████████████████ -->
<!--                  YEHIA ELKH — GitHub Profile README         -->
<!-- ████████████████████████████████████████████████████████████ -->

<!-- ═══════════════════════  HEADER BANNER  ═══════════════════════ -->
<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0A0FF9,50:1D6AF0,100:58a6ff&height=220&section=header&text=Yehia%20Elkh&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Robotics%20%26%20IoT%20Engineer%20%7C%20ROS%202%20Developer%20%7C%20Autonomous%20Systems&descAlignY=58&descSize=18)

</div>

<!-- ═══════════════════════  TYPING ANIMATION  ═══════════════════════ -->
<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&multiline=false&width=600&lines=%F0%9F%A4%96+Junior+ROS+2+Developer;%F0%9F%8C%90+IoT+%26+Embedded+Systems+Engineer;%F0%9F%A7%A0+Exploring+AI+%2B+Robotics;%F0%9F%9A%80+Building+Autonomous+Systems+from+scratch;%F0%9F%93%8D+ENIAD+Berkane+%7C+ROC+4th+Year)](https://git.io/typing-svg)

</div>

---

<!-- ═══════════════════════  BADGES STATUT  ═══════════════════════ -->
<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=YehiaElkh&color=0A0FF9&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/YehiaElkh?style=flat-square&color=58a6ff&label=Followers)
![Open to Collaborate](https://img.shields.io/badge/Open%20to-Collaborate-brightgreen?style=flat-square&logo=handshake)
![Student](https://img.shields.io/badge/Student-ENIAD%20Berkane-orange?style=flat-square&logo=graduation-cap)

</div>

---

<!-- ═══════════════════════  À PROPOS  ═══════════════════════ -->

## 🤖 About Me

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class YehiaElkh:
    def __init__(self):
        self.name        = "Yehia Elkh (Yahya Elkhoulati)"
        self.location    = "Driouch, Nador, Morocco 🇲🇦"
        self.school      = "ENIAD Berkane — Robotique & Objets Connectés (ROC)"
        self.year        = "4th Year Engineering Student"
        self.email       = "yahyaelkhoulati@ump.ac.ma"

        self.roles = [
            "Junior ROS 2 Developer",
            "Autonomous Systems Enthusiast",
            "IoT & Embedded Systems Engineer",
        ]

        self.tech_core = {
            "robotics"   : ["ROS 2 Humble", "Gazebo Classic", "Nav2", "slam_toolbox", "TF2"],
            "languages"  : ["Python", "C++", "C"],
            "iot"        : ["ESP32", "Arduino", "Raspberry Pi 5", "MQTT", "Zigbee"],
            "ai_ml"      : ["PyTorch", "YOLOv8", "TensorFlow", "scikit-learn", "OpenCV"],
            "devops"     : ["Docker", "Git", "CMake", "PlatformIO"],
            "hardware"   : ["NVIDIA RTX 3060", "CUDA", "Ubuntu 22.04"],
        }

        self.currently_building = [
            "AMR-Y  → Full autonomous mobile robot (SLAM + Nav2 + ROS 2)",
            "FireBot → Fire detection robot (Raspberry Pi 5 + YOLOv8 + MQTT)",
            "Deep RL → Quadruped locomotion via PPO (legged_gym / ETH Zurich)",
        ]

        self.fun_facts = [
            "⚡ I build everything from scratch — no shortcuts",
            "🎯 Goal: Contribute to the future of autonomous systems",
            "📚 I document every project professionally (LaTeX + Word + GitHub)",
        ]

    def say_hello(self):
        return "Hey, I'm Yehia 👋 — let's build something autonomous together!"

me = YehiaElkh()
print(me.say_hello())
```

---

<!-- ═══════════════════════  CURRENTLY BUILDING  ═══════════════════════ -->

## 🚧 Currently Building

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| 🤖 **AMR-Y** | Full autonomous mobile robot — SLAM, Nav2, custom bringup | ROS 2, Gazebo, slam_toolbox | 🔨 In Progress |
| 🔥 **FireBot** | Fire detection robot with real-time inference | Raspberry Pi 5, YOLOv8, MQTT | 🔨 In Progress |
| 🐾 **Deep RL Quadruped** | Legged locomotion via PPO (ETH Zurich legged_gym) | PyTorch, IsaacGym, Ubuntu 22.04 | 🔬 Research |
| 🏥 **Clinical AI Workflow** | Multi-agent clinical orientation system | Python, LangChain, FastAPI | ✅ Report Done |

---

<!-- ═══════════════════════  PROJETS PHARES  ═══════════════════════ -->

## 🏆 Featured Projects

### 🐢 turtle_navigation — ROS 2 Navigation Algorithms

> Autonomous navigation algorithms implemented on TurtleSim using ROS 2

**What it does:**
- 🧭 **PID Controller** — smooth goal-reaching with configurable gains
- 🔁 **FSM (Finite State Machine)** — robust state-based navigation
- 🌀 **Artificial Potential Fields (APF)** — real-time obstacle avoidance

**Tech stack:** `ROS 2 Humble` · `Python` · `Control Theory` · `TurtleSim`

**Highlights:** 3 navigation algorithms · Automated testing · Comprehensive docs

[![Repo](https://img.shields.io/badge/GitHub-turtle__navigation-181717?style=for-the-badge&logo=github)](https://github.com/YehiaElkh/turtle_navigation)
![Stars](https://img.shields.io/github/stars/YehiaElkh/turtle_navigation?style=for-the-badge&color=yellow)

---

### 🌀 APF_Obstacle_Avoidance_ROS2 — Real-time Obstacle Avoidance

> Real-time obstacle avoidance using Artificial Potential Fields in a simulated environment

**Architecture:**
- 🔴 **Repulsive forces** push the robot away from obstacles
- 🟢 **Attractive forces** pull the robot toward the goal
- ⚡ **Real-time** computation at each control cycle in Gazebo Classic

**Tech stack:** `ROS 2 Humble` · `Gazebo Classic` · `Python` · `LaserScan`

[![Repo](https://img.shields.io/badge/GitHub-APF__Obstacle__Avoidance-181717?style=for-the-badge&logo=github)](https://github.com/YehiaElkh/APF_Obstacle_Avoidance_ROS2)

---

### 📚 ros2_yehia_learning — Complete ROS 2 Learning Repository

> A structured journey through ROS 2 fundamentals — C++ and Python side by side

**Topics covered:**
- 📡 Publishers / Subscribers (C++ & Python)
- 🔗 Services & Clients
- ⚙️ Parameters & Launch files
- 🔄 TF2, QoS, DDS internals

**Tech stack:** `ROS 2 Humble` · `Python` · `C++` · `CMake` · `ament`

[![Repo](https://img.shields.io/badge/GitHub-ros2__yehia__learning-181717?style=for-the-badge&logo=github)](https://github.com/YehiaElkh/ros2_yehia_learning)
![Stars](https://img.shields.io/github/stars/YehiaElkh/ros2_yehia_learning?style=for-the-badge&color=yellow)
![Forks](https://img.shields.io/github/forks/YehiaElkh/ros2_yehia_learning?style=for-the-badge&color=blue)

---

### 🚗 Robot-Evite-Obstacle — Autonomous RC Car

> Self-driving RC car with real-time obstacle avoidance

**Features:**
- 🛤️ Lane detection
- 🔍 Object recognition
- ⚡ Real-time motor control

**Tech stack:** `Arduino Uno` · `C/C++` · `Ultrasonic sensors`

[![Repo](https://img.shields.io/badge/GitHub-Robot--Evite--Obstacle-181717?style=for-the-badge&logo=github)](https://github.com/YehiaElkh/Robot-Evite-Obstacle)

---

### 🏠 SmartSound-Monitor — IoT Ecosystem

> Complete IoT system for sound monitoring and smart environment automation

**Features:**
- 📊 Real-time sensor monitoring
- 🌐 Remote control via HTTPS
- 📱 Web dashboard
- 🔔 Alert system

**Tech stack:** `ESP32` · `HTTPS` · `Firebase` · `PlatformIO`

[![Repo](https://img.shields.io/badge/GitHub-SmartSound--Monitor-181717?style=for-the-badge&logo=github)](https://github.com/YehiaElkh/SmartSound-Monitor)

---

<!-- ═══════════════════════  TECH STACK  ═══════════════════════ -->

## ⚙️ Tech Stack

### 🤖 Robotics & Simulation
![ROS2](https://img.shields.io/badge/ROS%202%20Humble-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo%20Classic-E36209?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-0A0FF9?style=for-the-badge&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

### 🌐 IoT & Embedded
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=Raspberry-Pi)
![PlatformIO](https://img.shields.io/badge/PlatformIO-222?style=for-the-badge&logo=platformio&logoColor=%23f5822a)
![Zigbee](https://img.shields.io/badge/Zigbee-EB0443?style=for-the-badge&logo=zigbee&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=for-the-badge&logo=eclipse-mosquitto&logoColor=white)

### 🧠 AI / Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-000000?style=for-the-badge&logo=nVIDIA&logoColor=76B900)

### 🔧 DevOps & Tools
![Git](https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-008FBA?style=for-the-badge&logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Ubuntu%2022.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

---

<!-- ═══════════════════════  GITHUB STATS  ═══════════════════════ -->

## 📊 GitHub Stats

<div align="center">

[![Yehia's GitHub Stats](https://github-readme-stats.vercel.app/api?username=YehiaElkh&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&show_icons=true)](https://github.com/YehiaElkh)
[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YehiaElkh&theme=tokyonight&hide_border=true&layout=compact)](https://github.com/YehiaElkh)

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=YehiaElkh&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

<div align="center">

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=YehiaElkh&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=6)](https://github.com/YehiaElkh)

</div>

---

<!-- ═══════════════════════  CONTRIBUTION SNAKE  ═══════════════════════ -->

## 🐍 Contribution Graph

<div align="center">

[![Snake animation](https://github.com/YehiaElkh/YehiaElkh/blob/output/github-contribution-grid-snake.svg)](https://github.com/YehiaElkh)

</div>

> ⚙️ **Snake not showing yet?** Follow the setup steps below — takes 2 minutes.

---

<!-- ═══════════════════════  ROADMAP  ═══════════════════════ -->

## 🗺️ Learning Roadmap 2025–2026

```
Robotics & AI — Progress Tracker
════════════════════════════════════════════════════════════════════

 ROS 2 Fundamentals        ████████████████████  100% ✅
 Gazebo Simulation         ████████████████░░░░   80% 🔨
 SLAM (slam_toolbox)       ██████████████░░░░░░   70% 🔨
 Nav2 Navigation           ██████████████░░░░░░   70% 🔨
 Deep RL (PPO/legged_gym)  █████████░░░░░░░░░░░   45% 🔬
 Computer Vision (YOLO)    ████████████░░░░░░░░   60% 🔨
 IoT Full Stack (ESP32)    ████████████████░░░░   80% 🔨
 Docker / DevOps           █████████░░░░░░░░░░░   45% 📚
 CUDA / GPU Programming    ██████░░░░░░░░░░░░░░   30% 📚

 Legend:  ✅ Done   🔨 In Progress   🔬 Research   📚 Learning
```

---

<!-- ═══════════════════════  EDUCATION  ═══════════════════════ -->

## 🎓 Education & Experience

```
📅 2022 – Present
   ENIAD Berkane — École Nationale de l'Industrie, de l'Artisanat et des Technologies
   ├─ Program : Robotique et Objets Connectés (ROC)
   ├─ Year    : 4th Year Engineering
   └─ Supervisors : Dr. Mohamed Fartitchou · Pr. Sajida Mhammedi

🏆 Key Academic Projects
   ├─ AMR-Y     : Full autonomous mobile robot (ROS 2 + SLAM + Nav2)
   ├─ FireBot   : Fire detection robot (RPi 5 + YOLOv8 + MQTT)
   ├─ Clinical AI Workflow : Multi-agent system (co-authored w/ Youness Lamrini)
   ├─ Drone     : Obstacle avoidance (ArduPilot SITL + ROS 2 + Gazebo)
   └─ TP6 DQN  : Deep Q-Network (ROS 2 + TurtleBot3 + PyTorch)
```

---

<!-- ═══════════════════════  CONTACT  ═══════════════════════ -->

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yahya%20Elkhoulati-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yahya-elkhoulati-535580331/)
[![Email](https://img.shields.io/badge/Email-yahyaelkhoulati%40ump.ac.ma-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yahyaelkhoulati@ump.ac.ma)
[![GitHub](https://img.shields.io/badge/GitHub-YehiaElkh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YehiaElkh)
[![Discord](https://img.shields.io/badge/Discord-Yehia__Elkh-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/Yehia_Elkh)

</div>

> 💡 I'm always interested in collaborating on **robotics**, **IoT**, and **autonomous systems** projects!

---

<!-- ═══════════════════════  SNAKE SETUP  ═══════════════════════ -->

## ⚙️ Snake Animation Setup

**Step 1** — Create file `.github/workflows/snake.yml` in this repo:

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

**Step 2** — Go to `Actions` tab → `Generate Snake Animation` → `Run workflow`

**Step 3** — Done! The snake above will appear automatically after the first run.

---

<!-- ═══════════════════════  FOOTER  ═══════════════════════ -->

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,50:1D6AF0,100:0A0FF9&height=120&section=footer)

</div>

<!-- Proudly created with passion for robotics 🤖 — Yehia Elkh 2026 -->
