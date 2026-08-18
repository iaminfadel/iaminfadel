```
  ┌──────────────────────────────────────────────────────────────┐
  │                                                              │
  │    AMIN FADEL                                                │
  │    Robotics & Embedded Software Engineer                     │
  │    Ain Shams University · Mechatronics & Robotics            │
  │    Cairo, Egypt                                              │
  │                                                              │
  └──────────────────────────────────────────────────────────────┘
```

Building autonomous systems end-to-end — from bare-metal firmware to multi-agent AI pipelines.

Currently: software team lead for the ASU ROAR space robotics team (ERC 2025), firmware owner at Sparrow (smart agriculture), and collab with Honda Research Institute on AI-assisted rover workflows. Thesis topic: autonomous rover systems with real-time on-board perception.

---

## What I build

| | | |
|---|---|---|
| **Embedded & Real-Time** | STM32 · ESP32 · RP2040 · FreeRTOS · FOC / SVPWM · ISO 26262 | Bare-metal C that runs on hardware that touches dirt and crops |
| **Robotics & Autonomy** | ROS / ROS2 · FastSLAM · LeGO-LOAM · Sensor Fusion · EKF | Vehicles that drive themselves — race cars, rovers, robots |
| **Perception & AI** | YOLO · TensorRT · OpenCV · PCL · DQN · LLM agents | Making machines see, plan, and act |
| **Model-Based Design** | MATLAB · Simulink · Simscape · Embedded Coder · XCP / A2L | From math model to calibrated firmware, traceably |

## Flagship work

- **[flowjob](https://github.com/iaminfadel/flowjob)** — multi-agent AI pipeline that automates job applications end-to-end: scouts openings, analyzes fit, fills forms via browser automation, and audits its own mistakes. Built to save 15+ hrs/week; runs 50+ applications with zero CAPTCHA lockouts. *(Python · Playwright · LLM agents · TUI)*
- **PMSM Motor Control Platform (EV)** — model-based FOC with Jellyfish-Search-tuned PI gains, MIL/HIL on NI myRIO, Embedded Coder → A2L calibration, ISO 26262 supervisory layer. *(MATLAB · Simulink · Embedded C)*
- **[CSE473-NN-Library](https://github.com/iaminfadel/CSE473-NN-Library)** — neural network training library from scratch in Python (backprop, gradient descent variants, SVM via SMO); 28% more memory-efficient than an equivalent TensorFlow baseline. *(Python)*
- **[llm-cp](https://github.com/iaminfadel/llm-cp)** — LLM-based command planner that turns natural language into ROS navigation commands for a differential-drive robot in simulation. *(Python · ROS · GPT)*

## Competition record

- **European Rover Challenge 2025** — led a 10-person software team to 21st place; owned the full architecture: perception (YOLO + TensorRT INT8, RANSAC + Euclidean clustering point-cloud pipeline), localization, planning, and control on a ROS stack.
- **Formula Student AI UK** — 5th place; cut global raceline computation from **151s → 17s** (~90%); implemented FastSLAM + Hungarian data association for cone landmarks.

## More on GitHub

- [inventor-to-step-action](https://github.com/iaminfadel/inventor-to-step-action) — CI that converts Inventor `.ipt` → STEP, slices via PrusaSlicer CLI, and emits a full BOM.
- [ROAR-24-Perception](https://github.com/iaminfadel/ROAR-24-Perception) — perception simulations for ERC-24 missions.
- [rtsp-camera-ros-driver](https://github.com/iaminfadel/rtsp-camera-ros-driver) — ROS driver for RTSP camera feeds.
- [agrimonitor](https://github.com/iaminfadel/agrimonitor) — smart agriculture monitoring (IoT + embedded, deployed with Sparrow).

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iaminfadel&show_icons=true&hide_title=true&hide_border=true&theme=transparent" width="420"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iaminfadel&layout=compact&hide_title=true&hide_border=true&theme=transparent" width="320"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amin-fadel-595313161">LinkedIn</a> · 
  <a href="mailto:aminmoustafa.f@gmail.com">Email</a>
</p>
