# Bug_Algorithms

**Robot Navigation Algorithms — Bug0, Bug1, Bug2 in MATLAB**

![MATLAB](https://img.shields.io/badge/Language-MATLAB-orange)
![Robotics](https://img.shields.io/badge/Domain-Robotics-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

MATLAB implementation of classic **bug algorithms** for autonomous robot navigation. These algorithms enable a robot to navigate from point A to point B while avoiding unknown obstacles using only local sensor information.

---

## 📦 Structure

```
Bug_Algorithms/
├── EE596_MP1/                    # Main project folder
│   ├── bug_planner.m            # Bug planner core algorithm
│   ├── build_arena.m            # Environment/map builder
│   ├── draw_arena.m             # Arena visualization
│   ├── draw_range_map.m         # Sensor range visualization
│   ├── read_sensor.m            # Sensor data processing
│   ├── user_ModeTypes.m         # Mode type definitions
│   ├── user_dist2Obs.m          # Distance to obstacle calculation
│   ├── user_shortestPoints.m    # Shortest path computation
│   ├── user_change_dir.m        # Direction change logic
│   ├── circle.m                 # Circle geometry helper
│   ├── curveintersect.m         # Curve intersection detection
│   ├── EE596_MP1.m              # Main entry point
│   ├── mustafa_yilmaz.fig       # GUI figure (MATLAB App)
│   └── mustafa_yilmaz.rar       # Archived project
├── LICENSE
└── README.md
```

---

## 🧩 Bug Algorithms

| Algorithm | Behavior | Completeness |
|:----------|:---------|:-------------|
| **Bug0** | Head toward goal, follow obstacle on contact | Not guaranteed |
| **Bug1** | Fully circumnavigate obstacle, leave from closest point | ✅ Complete |
| **Bug2** | Follow obstacle along line to goal, leave when line reached | ✅ Complete |

---

## 🚀 Running

Open `EE596_MP1.m` in MATLAB and run. The GUI will display the robot navigating through the arena.

---

## 🛠 Requirements

- MATLAB (R2020+ recommended)
- MATLAB App Designer (for `.fig` GUI)

---

## 📄 License

MIT License.

---

## 📬 Contact

**Mustafa YILMAZ** — Embedded Software Engineer
