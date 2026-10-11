<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,20:0a0818,60:1a0533,100:6C5CE7&height=260&section=header&text=Pranav%20Prasad%20K&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=44&desc=AI%20%C2%B7%20LLM%20Systems%20%C2%B7%20Embedded%20%C2%B7%20Builder&descAlignY=64&descSize=22&descColor=a29bfe" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2400&pause=700&color=6C5CE7&center=true&vCenter=true&width=750&lines=Building+LLMs+from+scratch+%E2%80%94+then+automating+everything+else;Agentic+AI+%C2%B7+System+Automation+%C2%B7+On-device+LLMs;IoT+%C2%B7+Computer+Vision+%C2%B7+Robotics+%C2%B7+Edge+AI;Open+Source+%C2%B7+Always+Building+%C2%B7+Never+Stopping" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/pranav-prasad-94a36138b">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>&nbsp;
  <a href="mailto:cb.en.u4cce25132@cb.students.amrita.edu">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>&nbsp;
  <a href="https://github.com/pranavprasad25">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=pranavprasad25&style=for-the-badge&color=6C5CE7&label=PROFILE+VIEWS" />
</p>

<br />

---

## `whoami`

```python
class PranavPrasad:
    degree = "B.Tech · Computer & Communication Engineering"

    building = [
        "Agentic AI & LLM Systems",
        "AI Agents & MCP",
        "Computer Vision",
        "Intelligent Automation",
        "AIoT & Embedded Systems",
    ]

    exploring = ["Local AI", "RAG", "Robotics", "Edge Intelligence"]

    obsession = "AI x Embedded — most people pick one. I do both."

    current = "Turning impossible-sounding ideas into working systems."
```

<br />

---

## Projects

<br />

<table>
<tr>
<td width="50%" valign="top">

<img src="./assets/cards/shadow_automator.svg" width="100%" alt="Shadow Automator" />

### Shadow Automator
*Privacy-First, AI-Powered Desktop Automation Agent*

A privacy-first, AI-powered desktop automation agent that converts natural-language instructions into executable, multi-step workflows. It combines vision-language models (VLMs), local LLM inference, computer vision, GUI automation, and visual state validation to operate desktop applications through natural-language commands.

Instead of relying on hardcoded screen coordinates or manually scripted interactions, the system captures the desktop, identifies UI elements from visual context, determines where actions should occur, and executes mouse and keyboard operations with self-healing feedback loops.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Qwen3--VL-Vision_Language-7c3aed?style=flat" />
  <img src="https://img.shields.io/badge/llama.cpp-Local_AI-1e1e1e?style=flat" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/PyAutoGUI-2ea043?style=flat" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25)

</td>
<td width="50%" valign="top">

<img src="./assets/cards/amazon_ml.svg" width="100%" alt="Amazon ML Challenge: Business Entity Resolution" />

### Amazon ML Challenge 2026
*High-Performance, GPU-Accelerated Business Entity Resolution*

Developed a scalable machine learning pipeline for Business Entity Resolution (ER), identifying matching business records across multiple independent data sources without relying on shared unique identifiers.

The system addresses inconsistencies in business names, legal suffixes, addresses, postal codes, and geographical information using text normalization, multi-key candidate blocking, fuzzy similarity metrics, and GPU-accelerated gradient-boosted classifiers.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.11-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-FF6F00?style=flat" />
  <img src="https://img.shields.io/badge/LightGBM-00A98F?style=flat" />
  <img src="https://img.shields.io/badge/RapidFuzz-8A2BE2?style=flat" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25/ML-HACK)

<details>
<summary><b>⚙️ Technical Architecture & Benchmarks</b></summary>

<br>

#### 1. Data Preprocessing and Normalization
Unicode NFKD normalization, lowercasing, regex address expansions (e.g. *Pvt Ltd* vs *Private Limited*), and country-specific postal code parsers (India, USA, France).

#### 2. Multi-Key Candidate Blocking
Five inverted-index strategies avoid exhaustive pairwise comparisons across large datasets using compound keys, significant name tokens, exact postal codes, phonetic Soundex, and 3-character prefixes.

#### 3. Pairwise Feature Engineering
16-feature similarity vectors using RapidFuzz (Levenshtein, Jaro-Winkler, token similarity, Jaccard, digit overlap, and exact postal matching).

#### 4. GPU-Accelerated Machine Learning
XGBoost and LightGBM classifiers trained with 5-fold stratified cross-validation, negative sampling for class imbalance, and NVIDIA CUDA acceleration.

#### 5. Precision-Focused Threshold Optimization
Predictions optimized against Macro F0.5, sweeping decision thresholds to minimize false merges while preserving match coverage.

#### Reported Benchmarks (RTX 5060 · 28 CPU Cores · 16 GB RAM)
| Stage | Workload | Reported Runtime |
| :--- | :--- | :--- |
| Preprocessing | 17.6 million rows | ~3.7 minutes |
| Candidate Blocking | 5.1 million test rows | ~1.5 minutes |
| Feature Extraction & Inference | ~40 million pairs | ~3 minutes |
| **End-to-End Pipeline** | **Full dataset** | **~7–9 minutes** |

</details>

</td>
</tr>

<tr>
<td width="50%" valign="top">

<img src="./assets/cards/thermoshift.svg" width="100%" alt="ThermoShift" />

### ThermoShift
*Predictive Thermal Management Platform*

AI-powered thermal management system that monitors live multi-point temperature telemetry and dynamically optimizes cooling duty cycles for improved efficiency and hardware performance.

<br />

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/IoT-00CEC9?style=flat" />
  <img src="https://img.shields.io/badge/AI%2FML-6C5CE7?style=flat" />
  <img src="https://img.shields.io/badge/Sensors-2d3436?style=flat" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25/ThermalCore)

</td>
<td width="50%" valign="top">

<img src="./assets/cards/gesture_ai.svg" width="100%" alt="Gesture AI Assistant" />

### Gesture AI Assistant
*Vision-Based Human-Computer Interface*

Hands-free control of mouse navigation, volume levels, screenshots, and media playback via real-time 21-point hand landmark estimation coupled with an integrated voice assistant.

<br />

<p align="left">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25/Gesture-AI-Assistant)

</td>
</tr>

<tr>
<td width="50%" valign="top">

<img src="./assets/cards/healthos.svg" width="100%" alt="HealthOS AI" />

### HealthOS AI
*Agentic Healthcare Orchestration via MCP*

AI healthcare platform leveraging the Model Context Protocol (MCP) to unify electronic health records, prescription extraction, medication safety alerts, and personalized clinical insights.

<br />

<p align="left">
  <img src="https://img.shields.io/badge/NitroStack-6C5CE7?style=flat" />
  <img src="https://img.shields.io/badge/MCP-a29bfe?style=flat" />
  <img src="https://img.shields.io/badge/LLMs-412991?style=flat" />
  <img src="https://img.shields.io/badge/AI_Agents-00CEC9?style=flat" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25/Healthos-Ai)

</td>
<td width="50%" valign="top">

<img src="./assets/cards/pacbot.svg" width="100%" alt="PacBot" />

### PacBot
*Autonomous Robotics Navigation & Simulation*

Autonomous robotics platform combining low-latency sensor fusion, embedded C++ control loops, and simulated physics in MuJoCo for real-time maze exploration and path planning.

<br />

<p align="left">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat" />
  <img src="https://img.shields.io/badge/MuJoCo-E17055?style=flat" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25)

</td>
</tr>

<tr>
<td width="50%" valign="top">

<img src="./assets/cards/conveyor.svg" width="100%" alt="Conveyor Health Monitor" />

### Conveyor Health Monitor
*Industrial Computer Vision & IoT Inspection*

IoT and computer vision system detecting belt surface micro-cracks, tears, and tracking misalignment in real time, with machine learning models providing predictive maintenance alerts.

<br />

<p align="left">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/IoT-00CEC9?style=flat" />
  <img src="https://img.shields.io/badge/ML-6C5CE7?style=flat" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25)

</td>
<td width="50%" valign="top">

<br />

### ➕ Add New Repository
*Easily showcase your latest build or repository*

<details>
<summary><b>[ copy card template ]</b></summary>

<br>

```html
<td width="50%" valign="top">

<img src="./assets/cards/your_card.svg" width="100%" alt="Project Title" />

### Project Title
*Domain · Focus*

Concise 2-3 sentence overview of the architecture and impact.

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Open_Source-2ecc71?style=flat" />
</p>

[**➜ [ access repository ]**](https://github.com/pranavprasad25/your-repo)

</td>
```

</details>

<br />

<p align="center">
  <a href="https://github.com/pranavprasad25?tab=repositories">
    <img src="https://img.shields.io/badge/VIEW_ALL_REPOSITORIES-7C3AED?style=for-the-badge&logo=github&logoColor=white&labelColor=1A1330" alt="View All Repositories" />
  </a>
</p>

</td>
</tr>
</table>

<br />

---

## Stack

<br />

### AI / ML
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Qwen-615EFF?style=for-the-badge&logo=qwen&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/llama.cpp-Local_AI-37474F?style=for-the-badge" />
</p>

### Vision
<p align="left">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=mediapipe&logoColor=white" />
</p>

### Systems
<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
</p>

### Embedded / IoT
<p align="left">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" />
  <img src="https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white" />
</p>

### Dev
<p align="left">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</p>

<br />

---

## Github Telemetry

<div align="center">

<img src="./skyline.svg" width="100%" alt="Skyline of @pranavprasad25's GitHub contributions" />

</div>

<br />

---

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C5CE7,50:1a0533,100:0D1117&height=140&section=footer&text=let%27s%20build%20something%20real&fontSize=20&fontColor=a29bfe&animation=fadeIn&fontAlignY=65" width="100%" />
