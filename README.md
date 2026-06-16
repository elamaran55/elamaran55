<div align="center">

<img src="header-banner.svg" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=18&duration=2500&pause=600&color=00C896&center=true&vCenter=true&width=700&height=40&lines=ROS+2+%7C+Nav2+%7C+Gazebo+%7C+Embedded+Systems;Built+a+6-section+Continuum+Arm+with+24+Servos;Computer+Vision+%7C+OpenCV+%7C+Pick+%26+Place;Swarm+Robotics+%7C+SLAM+%7C+Multi-Robot+Coverage;2+International+Publications+%7C+TECHgium+Finalist;B.E.+Robotics+%40+SREC+Coimbatore+%7C+Batch+2027)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/elamaran-duraimurugan-763a27300)
[![Gmail](https://img.shields.io/badge/Gmail-amudhanmaran44-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:amudhanmaran44@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elamaran55)
[![Visitors](https://visitor-badge.laobi.icu/badge?page_id=elamaran55.elamaran55&color=00C896&style=for-the-badge&label=Profile+Views)](https://github.com/elamaran55)

</div>

---

## 👨‍💻 About Me

<img align="right" src="https://user-images.githubusercontent.com/74038190/229223263-cf2e4b07-2615-4f87-9c38-e37600f8381a.gif" width="270" alt="robot coding gif"/>

```python
#!/usr/bin/env python3

class Elamaran:
    name     = "Elamaran D  (Maran)"
    role     = "Robotics & Automation Undergrad"
    college  = "SREC Coimbatore  |  Batch 2027"
    cgpa     = 8.28
    location = "Coimbatore, Tamil Nadu 🇮🇳"

    stack    = ["ROS 2", "Python", "C++", "Nav2", "Gazebo"]
    hardware = ["Raspberry Pi", "ESP32", "ST3020 Servos"]
    vision   = ["OpenCV"]
    cad      = ["Fusion 360", "AutoCAD", "RoboDK"]

    publications = 2
    hackathons   = ["TECHgium 9th — Finalist", "CoIN 2026"]
    status       = "🟢 Open to Internships & Research Roles"

    def __str__(self):
        return "I don't just simulate robots. I build them."
```

📍 Coimbatore, Tamil Nadu &nbsp;|&nbsp; 📧 amudhanmaran44@gmail.com &nbsp;|&nbsp; 🎓 CGPA: 8.28 / 10

<br clear="right"/>

---

## 🛠️ Tech Arsenal

<div align="center">

### 🤖 Robotics & Simulation
![ROS2](https://img.shields.io/badge/ROS%202%20Humble-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo%20Sim-FF6600?style=for-the-badge&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2%20Stack-0066FF?style=for-the-badge&logoColor=white)
![RViz](https://img.shields.io/badge/RViz2-00C896?style=for-the-badge&logoColor=white)
![SLAM](https://img.shields.io/badge/SLAM%20Toolbox-8B00FF?style=for-the-badge&logoColor=white)
![URDF](https://img.shields.io/badge/URDF%20%2F%20Xacro-444444?style=for-the-badge&logoColor=white)

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

### 🔌 Embedded & Hardware
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ST3020](https://img.shields.io/badge/ST3020%20Servos-FFB300?style=for-the-badge&logoColor=black)

### 👁️ Computer Vision
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

### 📐 CAD & Tools
![Fusion360](https://img.shields.io/badge/Fusion%20360-FF6A00?style=for-the-badge&logo=autodesk&logoColor=white)
![AutoCAD](https://img.shields.io/badge/AutoCAD-CC0000?style=for-the-badge&logo=autodesk&logoColor=white)
![RoboDK](https://img.shields.io/badge/RoboDK-005B99?style=for-the-badge&logoColor=white)
![RobotStudio](https://img.shields.io/badge/RobotStudio-FF6600?style=for-the-badge&logoColor=white)

</div>

---

## 🚀 Projects

---

### 🦾 TDCR — Tendon Driven Continuum Robot Arm
> **TECHgium 9th Edition Finalist** &nbsp;·&nbsp; *Physical Robot · Custom Kinematics*

<img align="right" src="continuum-arm.svg" width="230" alt="animated 6-section continuum arm bending"/>

- Built a **6-section physical arm** with **24 ST3020 serial bus servos** — all custom-wired
- Implemented **constant-curvature kinematics** using 4×4 homogeneous transforms
- Parallel threading for simultaneous homing → repeatable starting pose
- Validated output with **3D matplotlib visualisations** against physical motion
- Debugged servo EEPROM persistence failures, COM port conflicts, baud-rate mismatches

**Stack:** `Python` `ST3020 SDK` `threading` `matplotlib` `numpy` `Flask`

📄 *Published in IJIRT · Vol. 11, Issue 12 · May 2025*

<br clear="right"/>

---

### 🤖 Café Butler Robot
> **ROS 2 · Nav2 · Gazebo** &nbsp;·&nbsp; *Full Simulation + Web Dashboard*

<img align="right" src="cafe-butler.svg" width="230" alt="animated robot route between kitchen, tables, and home dock"/>

- **7-scenario FSM**: Home → Kitchen → Table(s) → Home with timeouts & cancellations
- Full **Nav2 + SLAM** integration in a custom Gazebo café world
- **4-package ROS 2 workspace**: robot_description, nav_bringup, butler_node, web_dashboard
- Live **browser-based admin UI** for table order management

**Stack:** `ROS 2 Humble` `Nav2` `Gazebo` `Python` `URDF/Xacro` `Flask` `HTML/JS`

<br clear="right"/>

---

### 📦 Vision-Based HDPE Segregation
> **OpenCV · Raspberry Pi** &nbsp;·&nbsp; *Pick & Place · Computer Vision*

<img align="right" src="vision-sort.svg" width="230" alt="animated camera detecting and sorting HDPE on a conveyor"/>

- Camera-driven pick-and-place on **Raspberry Pi** for plastic sorting
- **MobileNet SSD v2** object detection for HDPE identification
- Systematic test cycles validating detection accuracy & arm precision

**Stack:** `OpenCV` `Python` `Raspberry Pi` `MobileNet SSD`

<br clear="right"/>

---

### 📚 AGV Library Assistant Robot
> **ESP32 · Autonomous Navigation** &nbsp;·&nbsp; *PID · WiFi · Browser UI*

<img align="right" src="agv-library.svg" width="230" alt="animated line-following AGV carrying books between shelves"/>

- **Autonomous navigation** via IR line-following with PID control
- **BTS7960 motor drivers** + ESP32 dual-core for real-time response
- **Mode-lock system**: AUTO / MANUAL handoff via WiFi UI
- Browser-based control panel for remote operation

**Stack:** `ESP32` `C++` `PID` `BTS7960` `HTML UI` `IR Sensors`

📄 *Published in IJRASET · Vol. 14, Issue 3 · March 2026*

<br clear="right"/>

---

### 🐝 SwarmMark — Multi-Robot Swarm Coverage
> **CoIN Hackathon 2026** &nbsp;·&nbsp; *ROS 2 · SLAM · Voronoi Partitioning*

<img align="right" src="swarm-coverage.svg" width="230" alt="animated 5-robot swarm patrolling Voronoi coverage cells"/>

- **5-robot ROS 2 swarm** for autonomous factory floor marking
- **Auction-based Voronoi partitioning** for dynamic area coverage
- Each robot independently maps, navigates, and marks its zone
- Full SLAM integration with Nav2 for autonomous exploration

**Stack:** `ROS 2` `SLAM` `Nav2` `Python` `Voronoi` `Auction Algorithm`

<br clear="right"/>

---

## 🗺️ How a Robot Project Comes Alive

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   📐 DESIGN      🔧 BUILD       🐛 DEBUG       🧪 TEST          ║
║   CAD / URDF  →  Hardware    →  Terminal    →  RViz / Real       ║
║                                                                  ║
║        ↑                                          ↓             ║
║        ║                                          ║             ║
║   🔁 ITERATE  ←  🚀 DEPLOY  ←  📄 PUBLISH  ←  📊 SIMULATE     ║
║   (Forever)      Real Robot     Journal           Gazebo         ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

---

## 📜 Publications

<div align="center">

| &nbsp; | Title | Journal | Date |
|:---:|---|---|:---:|
| 📄 | **Smart Robotic Arm System with Visual Processing Capabilities** | IJIRT · Vol. 11, Issue 12 | May 2025 |
| 📄 | **Autonomous Library Assistant** | IJRASET · Vol. 14, Issue 3 | Mar 2026 |

</div>

---

## 🏅 Certifications & Achievements

<div align="center">

| 🏆 | Achievement | Issuer | Year |
|:---:|---|---|:---:|
| 🥇 | TECHgium 9th Edition — Finalist | SREC / Industry | 2024 |
| 🥇 | CoIN Industrial Hackathon — SwarmMark | Industry Event | 2026 |
| ✅ | ROS 2 for Beginners (ROS Jazzy) | Udemy | 2024 |
| ✅ | Robotic Process Automation | NIELIT Chennai | 2024 |
| ✅ | Automation in Production Systems | NPTEL | 2024 |
| ✅ | Industry 4.0 & IIoT | NPTEL | 2024 |

</div>

---

## 💼 Experience

**Control Panel Intern** &nbsp;·&nbsp; *Technogreat Power Automation LLP, Coimbatore* &nbsp;·&nbsp; `June 2025`

> Validated industrial-grade control panels, documented wiring schematics, and identified hardware anomalies — directly applicable to embedded systems QA.

---

<div align="center">

<img src="footer-banner.svg" width="100%"/>

</div>
