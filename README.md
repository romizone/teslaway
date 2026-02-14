<div align="center">

# 🚗 Tesla Self-Driving AI Simulation

<img src="https://img.shields.io/badge/Tesla-Autopilot-e82127?style=for-the-badge&logo=tesla&logoColor=white" alt="Tesla Autopilot"/>
<img src="https://img.shields.io/badge/JavaScript-Canvas_API-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/HTML5-Simulation-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
<img src="https://img.shields.io/badge/CSS3-Animations-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
<img src="https://img.shields.io/badge/Vercel-Deployed-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>

<br/>

<img src="https://img.shields.io/badge/status-live-00ff88?style=flat-square" alt="Status"/>
<img src="https://img.shields.io/github/license/romizone/teslaway-simulation?style=flat-square&color=blue" alt="License"/>
<img src="https://img.shields.io/github/last-commit/romizone/teslaway-simulation?style=flat-square&color=e82127" alt="Last Commit"/>
<img src="https://img.shields.io/github/repo-size/romizone/teslaway-simulation?style=flat-square&color=orange" alt="Repo Size"/>

<br/><br/>

**A real-time 3D autonomous vehicle simulation featuring LiDAR visualization, AI traffic management, and a cinematic HUD interface — all rendered in pure JavaScript Canvas.**

<br/>

[🌐 **Live Demo**](https://teslaway.vercel.app/) · [🐛 Report Bug](https://github.com/romizone/teslaway-simulation/issues) · [💡 Request Feature](https://github.com/romizone/teslaway-simulation/issues)

---

</div>

## 🎬 Preview

> Open [**teslaway.vercel.app**](https://teslaway.vercel.app/) — a 3-second countdown launches you straight into the simulation. No clicks needed.

<br/>

## ✨ Features

| | Feature | Description |
|---|---|---|
| 🛣️ | **3D Road System** | Procedurally generated roads with curves, intersections, lane markings & crosswalks |
| 🤖 | **AI Traffic** | Multiple AI-controlled vehicles with realistic behavior and tail lights |
| 📡 | **LiDAR Visualization** | Real-time 360° LiDAR sweep, point cloud rendering & 3D object mapping |
| 🚦 | **Traffic Lights** | Dynamic traffic signal system with countdown timer & auto speed adjustment |
| 🎯 | **Object Detection** | AI bounding boxes with distance tracking on detected vehicles |
| 🖥️ | **Cinematic HUD** | Full heads-up display with speed, battery, sensor status & AI decisions |
| 🗺️ | **LiDAR Minimap** | Circular radar-style minimap with real-time vehicle positions |
| 🌃 | **Night Environment** | Starfield, moon, illuminated buildings with window lights |
| 🏙️ | **City Objects** | Procedural buildings & trees with LiDAR point detection |
| ⏱️ | **Auto Countdown** | 3... 2... 1... GO! Auto-starts without user interaction |

<br/>

## 🛠️ Tech Stack

<div align="center">

| Technology | Usage |
|---|---|
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Core simulation engine & game loop |
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Canvas rendering & DOM structure |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | HUD layout, animations & effects |
| ![Canvas API](https://img.shields.io/badge/-Canvas_API-333?style=flat-square&logo=html5&logoColor=white) | 2D graphics & 3D perspective projection |
| ![Google Fonts](https://img.shields.io/badge/-Google_Fonts-4285F4?style=flat-square&logo=googlefonts&logoColor=white) | Orbitron & Inter typefaces |
| ![Vercel](https://img.shields.io/badge/-Vercel-000?style=flat-square&logo=vercel&logoColor=white) | Deployment & hosting |

</div>

<br/>

## 🎮 Controls

| Key | Action |
|---|---|
| <kbd>↑</kbd> | Increase speed (+10 km/h) |
| <kbd>↓</kbd> | Decrease speed (-10 km/h) |
| <kbd>L</kbd> | Toggle LiDAR system on/off |

<br/>

## 📊 HUD Panels

```
┌─────────────────────────────────────────────────────────┐
│ 🟢 FSD + LiDAR ACTIVE                        00:12:34  │
│                                                         │
│  ┌─────────┐           NEURAL NETWORK        ┌───────┐  │
│  │ 8 CAM   │          + LiDAR PROCESSING     │ DETECT│  │
│  │ L LiDAR │                                 │ 98.7% │  │
│  │ R RADAR │       ┌─ TRAFFIC SIGNAL ─┐      │ 96.2% │  │
│  │ U ULTRA │       │  🔴 🟡 🟢  12s  │      │ 94.1% │  │
│  │ N NEURL │       └──────────────────┘      │ 99.5% │  │
│  │ G GPS   │                                 └───────┘  │
│  └─────────┘                              ┌──────────┐  │
│                                           │ LiDAR360 │  │
│                                           │    🔵     │  │
│  ┌──────┐  FULL SELF-DRIVING BETA         └──────────┘  │
│  │ 120  │  LiDAR + VISION FUSION   BATTERY ████░ 87%   │
│  │ KM/H │  Highway 101 N - Palo Alto, CA               │
│  └──────┘                                               │
└─────────────────────────────────────────────────────────┘
```

<br/>

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/romizone/teslaway-simulation.git

# Navigate to the project
cd teslaway-simulation

# Open in browser (macOS)
open index.html

# Open in browser (Linux)
xdg-open index.html

# Open in browser (Windows)
start index.html
```

> 💡 No dependencies, no build step, no server needed — just open the HTML file!

<br/>

## 📂 Project Structure

```
teslaway-simulation/
├── 📄 index.html       # Complete application (HTML + CSS + JS)
├── 📋 README.md        # Documentation
├── 📝 LICENSE           # MIT License
└── 🚫 .gitignore       # Git ignore rules
```

<br/>

## 🔬 How It Works

### 🧠 AI Decision Engine
The simulation uses a procedural AI system that:
- Generates road segments (straights, curves, intersections)
- Manages traffic light state machines with countdown logic
- Adjusts vehicle speed based on traffic conditions
- Simulates object detection with confidence percentages

### 📡 LiDAR System
- **4 virtual sensors** scanning the environment
- Real-time **point cloud visualization** on road and objects
- **360° minimap** showing detected vehicles and road edges
- **Wireframe overlays** on detected objects with depth mapping

### 🎥 3D Rendering
- Custom **perspective projection** engine (no libraries)
- **Depth-sorted rendering** for buildings and environment
- Dynamic **lighting and fog** based on distance
- **Scanline & vignette** post-processing effects

<br/>

## 🌐 Deployment

This project is deployed on **Vercel** with automatic deploys on push:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/romizone/teslaway-simulation)

<br/>

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

<br/>

---

<div align="center">

**Made with ❤️ and JavaScript**

<img src="https://img.shields.io/badge/Pure-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="Pure JS"/>
<img src="https://img.shields.io/badge/Zero-Dependencies-00ff88?style=for-the-badge" alt="Zero Dependencies"/>
<img src="https://img.shields.io/badge/Single-File-e82127?style=for-the-badge" alt="Single File"/>

⭐ Star this repo if you found it interesting!

</div>
