<h1 align="center">Hi 👋, I'm Haotian Liu</h1>

<h3 align="center">机器人 · 具身智能 · Robot Agent</h3>

<p align="center">
  <a href="./README.md">中文</a> | <a href="./README_EN.md">English</a>
</p>

<p align="center">
  我致力于构建连接 <b>LLM/VLM 智能推理</b> 与
  <b>确定性感知、规划、控制和仿真</b> 的机器人智能体系统。
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Robotics-Robot%20Agents-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Embodied%20AI-Manipulation-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Simulation-MuJoCo-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Main%20Languages-Python%20%7C%20C%2B%2B-informational?style=flat-square" />
</p>

---

## 👨‍💻 关于我

- 🤖 专注于 **机器人操作、具身智能与 Robot Agent 系统**
- 🧠 关注 **概率式 AI 推理** 与 **确定性机器人执行系统** 之间的结合
- 👁️ 目前主要研究和开发 **VLM Grounding、语义任务规划、机器人感知、操作与失败恢复**
- 🦾 使用 **Franka Panda、UR5e、MuJoCo、Isaac Lab** 进行机器人开发与仿真
- 💻 主要开发语言：**Python / C++**
- 🔬 技术背景涵盖 **3D Vision、算法与机器人系统**
- 🌱 持续探索 **ROS 2、真机后端、更强的机器人感知与 Robot Memory**
- 💬 欢迎交流 **Robot Agent、具身智能、Python、C++、机器人仿真与操作**

---

## 🧩 我正在构建什么

我目前项目中的一个核心设计思想，是将 **高层 AI 推理与任务决策** 和 **底层确定性的机器人执行系统** 解耦：

```text
自然语言 + RGB 图像
        ↓
   VLM / Agent
        ↓
    语义任务规划
        ↓
Typed TaskPlan / Skill DAG
        ↓
  确定性机器人运行时
        ↓
感知 → 几何 → 逆运动学 → 控制
        ↓
      MuJoCo
        ↓
验证 → 恢复 / 重新规划
```

目标是让 Agent 负责理解任务并决定 **“做什么”**，而由确定性的机器人系统负责解决 **“如何可靠地执行”**。

---

## 🚀 代表项目

| 项目 | 项目介绍 | 技术方向 |
| --- | --- | --- |
| [**robot_agent**](https://github.com/haotian2410/robot_agent) | Robot Agent 框架，包含类型化任务规划、VLM Grounding、原子技能、确定性执行、结果验证与失败恢复。 | Python · MuJoCo · Franka Panda · VLM · MCP · REST |
| [**robot_agent_sim**](https://github.com/haotian2410/robot_agent_sim) | 将自然语言机器人指令转化为任务意图、场景 Grounding 与高层技能规划。 | Python · MuJoCo · Qwen/VLM · Panda · UR5e |
| [**robot_agent_control**](https://github.com/haotian2410/robot_agent_control) | 机器人执行控制层，将高层命令转化为 IK、轨迹、夹爪动作以及机器人交互。 | C++ · Robotics · IK · Motion · Control |
| [**cscv_agent**](https://github.com/haotian2410/cscv_agent) | Robot Agent Dashboard 原型，探索任务编排、感知、规划、地图与记忆系统。 | Python · Agent Architecture · Spatial Memory |
| [**robot_memory**](https://github.com/haotian2410/robot_memory) | 围绕机器人空间记忆、对象级场景信息和长期环境理解进行实验。 | Python · Spatial Memory · Vision |
| [**atec2026**](https://github.com/haotian2410/atec2026) | 面向 ATEC 2026 机器人挑战环境的仿真与机器人任务开发。 | Isaac Lab · Robot Simulation · Loco-Manipulation |

---

## 🛠️ 技术栈

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

### 当前研究兴趣

`Robot Agents` · `具身智能` · `机器人操作` · `VLM Grounding`  
`任务规划` · `Robot Memory` · `3D Vision` · `机器人仿真` · `机器人控制`

---

## 🎯 当前重点

### Robot Agent Architecture / 机器人智能体架构

我正在探索如何通过 **结构化任务计划、可靠技能、显式世界模型与可验证执行机制**，让现代 AI Agent 真正参与机器人任务执行。

### Embodied AI / 具身智能

我希望把 **语言、视觉、空间理解、机器人操作和长时序任务执行** 连接成完整的具身智能系统。

### Robot Memory / 机器人记忆

我也在研究机器人如何建立和维护 **对象级、空间级以及任务级长期记忆**，让机器人能够在持续交互中积累环境知识。

---

## 🗺️ 下一步方向

- [ ] 接入 ROS 2
- [ ] 接入真实机器人后端
- [ ] 增强视觉 Grounding
- [ ] 构建长期 Robot Memory
- [ ] 构建更多可复用机器人技能
- [ ] 强化闭环规划与失败恢复
- [ ] 探索多机器人与多智能体协作

---

## 📊 GitHub 数据

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=haotian2410&show_icons=true&hide_border=true&theme=transparent" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=haotian2410&layout=compact&hide_border=true&theme=transparent" />
</p>

---

## 📫 联系我

GitHub: [@haotian2410](https://github.com/haotian2410)

如果你也在研究 **Robot Agent、具身智能、机器人操作、机器人仿真或机器人智能系统**，欢迎交流。

---

<p align="center">
  <b>让 Agent 自由思考，让机器人可靠执行。</b>
</p>
