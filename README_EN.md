<h1 align="center">Hi 👋, I'm Haotian Liu</h1>

<h3 align="center">Robotics · Embodied AI · Robot Agents</h3>

<p align="center">
  <a href="./README.md">中文</a> | <a href="./README_EN.md">English</a>
</p>

<p align="center">
  I build robot-agent systems that connect <b>LLM/VLM reasoning</b> with
  <b>deterministic perception, planning, control, and simulation</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Robotics-Robot%20Agents-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Embodied%20AI-Manipulation-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Simulation-MuJoCo-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Main%20Languages-Python%20%7C%20C%2B%2B-informational?style=flat-square" />
</p>

---

## 👨‍💻 About Me

- 🤖 Building **robot-agent systems for manipulation and embodied AI**
- 🧠 Interested in the boundary between **probabilistic AI reasoning** and **deterministic robot execution**
- 👁️ Working on **VLM grounding, semantic task planning, robot perception, manipulation, and recovery**
- 🦾 Developing and testing with **Franka Panda, UR5e, MuJoCo, and Isaac Lab**
- 💻 Main languages: **Python / C++**
- 🔬 Background in **3D Vision, algorithms, and robotics**
- 🌱 Exploring **ROS 2, real-robot backends, stronger perception, and robot memory**
- 💬 Happy to discuss **Robot Agents, Embodied AI, Python, C++, simulation, and manipulation**

---

## 🧩 What I'm Building

A core idea behind my recent work is to keep **high-level AI reasoning** separated from **low-level deterministic robot execution**:

```text
Natural Language + RGB
        ↓
   VLM / Agent
        ↓
 Semantic Planning
        ↓
 Typed TaskPlan / Skill DAG
        ↓
 Deterministic Robot Runtime
        ↓
Perception → Geometry → IK → Control
        ↓
      MuJoCo
        ↓
Verification → Recovery / Replan
```

The goal is to let an Agent decide **what to do**, while deterministic robotics software remains responsible for **how the robot physically executes it**.

---

## 🚀 Featured Projects

| Project | Description | Stack / Focus |
| --- | --- | --- |
| [**robot_agent**](https://github.com/haotian2410/robot_agent) | Robot Agent framework with typed task plans, VLM grounding, atomic skills, deterministic execution, verification, and recovery. | Python · MuJoCo · Franka Panda · VLM · MCP · REST |
| [**robot_agent_sim**](https://github.com/haotian2410/robot_agent_sim) | Converts natural-language instructions into task intent, scene grounding, and high-level skill plans. | Python · MuJoCo · Qwen/VLM · Panda · UR5e |
| [**robot_agent_control**](https://github.com/haotian2410/robot_agent_control) | Robot execution layer that converts high-level commands into IK, trajectories, gripper actions, and robot interaction. | C++ · Robotics · IK · Motion · Control |
| [**cscv_agent**](https://github.com/haotian2410/cscv_agent) | Robot-agent dashboard prototype exploring task orchestration, perception, planning, mapping, and memory. | Python · Agent Architecture · Spatial Memory |
| [**robot_memory**](https://github.com/haotian2410/robot_memory) | Experiments around robot/spatial memory, object-centric scene information, and long-term environment understanding. | Python · Spatial Memory · Vision |
| [**atec2026**](https://github.com/haotian2410/atec2026) | Simulation and robotics task development around ATEC 2026 challenge environments. | Isaac Lab · Robot Simulation · Loco-Manipulation |

---

## 🛠️ Languages & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/MuJoCo-Simulation-2D6A4F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Isaac%20Lab-Robotics-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-Agent%20Tools-111111?style=for-the-badge" />
</p>

### Current Interests

`Robot Agents` · `Embodied AI` · `Manipulation` · `VLM Grounding`  
`Task Planning` · `Robot Memory` · `3D Vision` · `Simulation` · `Robot Control`

---

## 🎯 Current Focus

### Robot Agent Architecture

I am exploring how modern AI agents can interact with robots through **structured plans, reliable skills, explicit world models, and verifiable execution**.

### Embodied AI

My interests include connecting **language, vision, spatial understanding, manipulation, and long-horizon task execution** into complete embodied intelligence systems.

### Robot Memory

I am also interested in how robots can maintain **object-centric, spatial, and task-related long-term memory** across interactions.

---

## 🗺️ Roadmap

- [ ] ROS 2 integration
- [ ] Real-robot backend
- [ ] Stronger visual grounding
- [ ] Long-term robot memory
- [ ] More reusable robot skills
- [ ] Closed-loop planning and recovery
- [ ] Multi-robot / multi-agent exploration

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=haotian2410&show_icons=true&hide_border=true&theme=transparent" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=haotian2410&layout=compact&hide_border=true&theme=transparent" />
</p>

---

## 📫 Connect

GitHub: [@haotian2410](https://github.com/haotian2410)

If you're working on **Robot Agents, Embodied AI, robot manipulation, simulation, or robot intelligence**, feel free to connect and exchange ideas.

---

<p align="center">
  <b>Build agents that reason freely — and robots that execute reliably.</b>
</p>
