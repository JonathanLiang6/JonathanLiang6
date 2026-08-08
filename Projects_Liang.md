# 📂 项目总览

<div align="center">

  <img src="https://img.shields.io/badge/总计项目-15-238636?style=for-the-badge" alt="Total Projects" />

</div>

Welcome to my project portfolio! 以下是我在 GitHub 上维护的所有公开仓库，按专业领域分类展示。

---

## 🧠 数据与人工智能

### 🔗 KnowledgeGraph

<div align="center">

  ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
  ![Vue.js](https://img.shields.io/badge/vue.js-%2335495E.svg?style=for-the-badge&logo=vue.js&logoColor=white)
  ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
  ![ChromaDB](https://img.shields.io/badge/ChromaDB-%23871EFF.svg?style=for-the-badge&logo=chroma&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/KnowledgeGraph)

</div>

**版本**: v4.0

个人知识库管理平台。将非结构化文档转化为结构化知识图谱，提供拓扑导航、混合检索、Agent 多步推理与知识覆盖诊断。采用 FastAPI + Vue 3 技术栈，支持 Docker 一键部署。

**核心特性**:
- 🌐 拓扑导航台：基于 D3.js 力导向图的层级知识库管理
- 📄 文档管理：支持 PDF/DOCX/PPTX/EPUB/Markdown/HTML/TXT/图片多格式
- 🕸️ 知识图谱：自动构建实体-关系知识图谱，双轨存储架构
- 💬 智能问答：SSE 流式输出，Markdown 实时渲染
- 🤖 Agent 工具集：多步推理、记忆系统、联网搜索、图像感知
- 📊 知识覆盖诊断：ECharts Treemap 矩形树图渲染

**技术亮点**:
- 检索融合 (RRF) 算法
- 文档处理流水线（6阶段异步处理）
- 实体对齐与关系去重
- PaddleOCR + BLIP 图像感知

---

### 🎥 BayesSigmoid-Defocus

<div align="center">

  ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
  ![PyMC](https://img.shields.io/badge/PyMC-Bayesian-orange?style=for-the-badge)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/BayesSigmoid-Defocus)

</div>

个性化离焦剂量探索系统。基于贝叶斯 Sigmoid（四参数逻辑斯蒂）模型和主动学习策略，为每个受试者动态推荐下一个离焦测量剂量。系统以最少实验次数（通常 2~5 次）估计个体离焦阈值（ED50）和最佳剂量。

**核心特性**:
- 双点启动（2.0D, 4.0D）避免单点方向误判
- 贝叶斯 MCMC 推断（PyMC）量化不确定性
- 主动学习采集函数：后验方差 + 期望改进
- 自动停止条件
- 纯 Python 脚本运行，无需 Jupyter

---

### 📝 PorterStemmer_Imitation

<div align="center">

  ![C++](https://img.shields.io/badge/c++20-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/PorterStemmer_Imitation)

</div>

基于 Porter Stemmer 算法改进的文本分析系统。实现英文词干提取、文本相似度计算和交互式查询功能。

**核心特性**:
- 英文词干提取（改进版 Porter Stemmer）
- 文本相似度计算
- 交互式查询界面
- UTF-8 编码支持

**技术亮点**:
- AVL 树数据结构应用
- C++20 现代特性
- 算法优化策略

---

### 🛡️ 天盾 - 反诈智能体助手

<div align="center">

  ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
  ![Vue.js](https://img.shields.io/badge/vue.js-%2335495E.svg?style=for-the-badge&logo=vue.js&logoColor=white)
  ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/fanzha)

</div>

天盾是一个基于 doubao-seed2 多模态大模型的反诈智能体助手系统，实现了"感知 → 决策 → 干预 → 进化"四阶能力闭环。支持文本、语音、图像、视频多种模态输入，能够精准识别 12 种常见诈骗类型。

**核心特性**:
- 🎯 多模态诈骗检测：文本/语音/图片/视频
- 🚨 12 种诈骗类型识别：投资理财、刷单返利、冒充公检法等
- ⚠️ 分级预警机制：低/中/高/紧急四级
- 👨‍👩‍👧 监护人联动：自动通知 + 风险事件推送
- 📈 个性化风险评估：基于用户画像动态调整阈值
- 🔄 知识库自适应进化：自动爬取更新反诈案例

---

## 💻 软件开发

### 📝 NoteMaster

<div align="center">

  ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
  ![.NET](https://img.shields.io/badge/.NET-%23512BD4.svg?style=for-the-badge&logo=.net&logoColor=white)
  ![WPF](https://img.shields.io/badge/WPF-%23512BD4.svg?style=for-the-badge)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/NoteMaster)

</div>

基于 WPF 框架开发的 Windows 桌面笔记管理应用。采用 MVVM 架构，支持笔记创建/编辑/删除、文件夹管理、待办事项管控及笔记搜索筛选等核心功能。

**核心特性**:
- 📝 笔记创建、编辑、删除
- 📁 文件夹层级管理
- ✅ 待办事项管理
- 🔍 笔记搜索与筛选
- 💾 数据持久化存储

---

### 📦 CsharpLittleApps

<div align="center">

  ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
  ![.NET](https://img.shields.io/badge/.NET-%23512BD4.svg?style=for-the-badge&logo=.net&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/CsharpLittleApps)

</div>

**Forks**: 4

多个 C# 小项目的集合，用于学习和展示 C# 语言的各种应用场景。涵盖控制台应用、Windows 窗体、WPF 等多种开发模式。

**核心特性**:
- 🎯 多种类型的 C# 应用示例
- 🏗️ 面向对象编程实践
- 📦 .NET 框架特性展示

---

### 📊 PythonCodeVisualization

<div align="center">

  ![Vue.js](https://img.shields.io/badge/vue.js-%2335495E.svg?style=for-the-badge&logo=vue.js&logoColor=white)
  ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
  ![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/PythonCodeVisualization)

</div>

Python 代码可视化项目，用于 Python 语言教学。帮助学习者理解和分析代码结构与执行流程，提升编程学习效率。

---

## 🔧 硬件设计

### 🧠 RISC-V_PipeLine_CPU

<div align="center">

  ![Verilog](https://img.shields.io/badge/verilog-%23d53a00.svg?style=for-the-badge&logo=verilog&logoColor=white)
  ![RISC-V](https://img.shields.io/badge/RISC--V-%23A6222C.svg?style=for-the-badge&logo=riscv&logoColor=white)
  ![FPGA](https://img.shields.io/badge/FPGA-%2300C5FF.svg?style=for-the-badge&logo=xilinx&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/RISC-V_PipeLine_CPU)

</div>

基于 RISC-V RV32I 指令集的五级流水线 CPU 设计。实现完整的取指、译码、执行、访存、写回五个阶段，支持数据冒险和控制冒险的检测与处理。适配 Nexys4DDR 开发板。

**核心特性**:
- 🏭 五级流水线架构（IF/ID/EX/MEM/WB）
- 🔄 数据前推（Forwarding）机制消除数据冒险
- 🎯 分支预测与冲刷（Flush）处理控制冒险
- 📋 完整的 RV32I 基础整数指令集
- 💾 集成指令/数据内存与通用寄存器堆

---

### ⚡ RISC-V_SingleCycle_CPU

<div align="center">

  ![Verilog](https://img.shields.io/badge/verilog-%23d53a00.svg?style=for-the-badge&logo=verilog&logoColor=white)
  ![RISC-V](https://img.shields.io/badge/RISC--V-%23A6222C.svg?style=for-the-badge&logo=riscv&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/RISC-V_SingleCycle_CPU)

</div>

基于 RISC-V RV32I 指令集的单周期 CPU 实现。使用 Verilog HDL 完成核心的数据处理、内存访问和控制流指令，通过板载七段数码管动态显示内部状态与执行结果。

**核心特性**:
- ⚡ 单周期指令执行架构
- 📋 支持 RV32I 核心指令集
- 🔢 七段数码管动态扫描显示
- 💡 LED 状态指示系统
- ⏱️ 时钟分频与控制逻辑

---

### ⏱️ GW_Timer

<div align="center">

  ![Verilog](https://img.shields.io/badge/verilog-%23d53a00.svg?style=for-the-badge&logo=verilog&logoColor=white)
  ![FPGA](https://img.shields.io/badge/FPGA-Gowin-orange?style=for-the-badge)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/GW_Timer)

</div>

**Forks**: 1

以高云 GW1N-UV9EQ144C6/I5 FPGA 芯片为核心，设计制作的高精度秒表系统。实现 0-59:59 计时范围，支持实时显示、清零、暂停恢复、预置时间和状态指示功能。

**核心特性**:
- ⏱️ 00:00-59:59 精准计时
- ⏯️ 暂停与恢复功能
- ⏲️ 时间预置功能
- 💡 LED 状态指示系统
- 🔢 七段数码管显示

---

## 🖥️ 系统设计

### 🔧 toyc_compiler

<div align="center">

  ![OCaml](https://img.shields.io/badge/ocaml-%233BE133.svg?style=for-the-badge&logo=ocaml&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/toyc_compiler)

</div>

Fork 自 Icarus-Yu/toyc_compiler。基于 OCaml 实现的编译器前端，支持词法分析、语法分析和语义分析等编译流程。

**核心特性**:
- 📖 词法分析（Lexing）
- 🔍 语法分析（Parsing）
- 🌲 抽象语法树（AST）构建
- ✅ 语义检查

---

### 🖥️ xv6_labs

<div align="center">

  ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
  ![RISC-V](https://img.shields.io/badge/RISC--V-%23A6222C.svg?style=for-the-badge&logo=riscv&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/xv6_labs)

</div>

xv6-labs-2022 实验代码库，基于 Unix v6 的教学操作系统。用于操作系统原理的学习与实验，涵盖进程管理、内存管理、文件系统等核心模块。

**核心特性**:
- 🖥️ 基于 RISC-V 的操作系统实现
- ⚙️ 进程调度与管理
- 🧠 虚拟内存与分页机制
- 📁 文件系统实现
- 🔌 系统调用接口

---

### 📚 CSAPP_Labs

<div align="center">

  ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/CSAPP_Labs)

</div>

《深入理解计算机系统》（CSAPP）课程实验代码库，包含 DataLab、BombLab、AttackLab 全过程帮助文档与相关文件。

**核心特性**:
- 🔢 DataLab：位级编程实验
- 💣 BombLab：逆向工程实验
- 🛡️ AttackLab：缓冲区溢出攻击实验
- 📖 完整的实验指导文档

---

## 📚 知识管理

### 📖 良识云库 (LOKR)

<div align="center">

  ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
  ![Obsidian](https://img.shields.io/badge/Obsidian-%237C3AED.svg?style=for-the-badge&logo=obsidian&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/Liang_Online_Knowledge_Repository)

</div>

良识云库（LOKR）是基于 Obsidian 构建的知识集合平台，由 JonathanLiang 发起打造。内容丰富且不断扩充，推荐使用 Obsidian 软件访问以获得最佳体验。

**核心特性**:
- 📚 多领域知识内容聚合
- 📥 仓库克隆 + Obsidian 一键导入
- 🔗 双向链接知识网络
- 🔄 持续更新与扩充

---

## 🐣 其他

### 🎮 Along

<div align="center">

  ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
  ![React](https://img.shields.io/badge/react-%2320232A.svg?style=for-the-badge&logo=react&logoColor=white)
  ![Wails](https://img.shields.io/badge/Wails-v2-238636?style=for-the-badge)
  ![SQLite](https://img.shields.io/badge/sqlite-%23003B57.svg?style=for-the-badge&logo=sqlite&logoColor=white)

  [![GitHub](https://img.shields.io/badge/查看项目-238636?style=for-the-badge&logo=github)](https://github.com/JonathanLiang6/Along)

</div>

基于 **Go + Wails + React** 的多 Agent 智能助手桌面应用。通过 **Orchestrator（主 Agent）** 统一编排 10 个专业子 Agent 协作，提供对话、规划、记忆、调研、自动化等能力。

**核心特性**:
- 🤖 **智能对话**：自然语言交互，支持流式响应，上下文感知
- 🎯 **Agent 编排**：LLM 驱动的主 Agent 自动分析意图 → 生成执行计划 → 调度子 Agent 协作完成复杂任务
- 🧠 **记忆系统**：5 层长期记忆（L1 个人画像 → L5 日常喜好），自动提取与去重
- 📋 **计划管理**：目标拆解、里程碑追踪、进度可视化、打卡记录
- 🔍 **联网调研**：多引擎搜索（DuckDuckGo + Bing），AI 自动总结生成结构化报告
- 🔄 **反思复盘**：周期性成长分析、关系回顾、项目总结
- 🛠️ **工具调用**：文件读写、目录浏览、Git 操作、浏览器打开
- ⚙️ **自动化任务**：Cron 定时调度 + 可视化工作流编排，支持 10 种任务类型

**10 个子 Agent**:
Planner（计划）、Web（搜索）、TechAnalysis（技术分析）、Research（调研）、Summarize（摘要）、FileGeneration（文件生成）、Tool（工具）、Reflection（反思）、Memory（记忆）、Emotion（情感）

**技术栈**:
- 桌面壳：Wails v2
- 后端：Go 1.25+
- 前端：React 18 + Vite 5 + Tailwind CSS 3
- 数据库：SQLite（WAL 模式）
- AI 提供商：DeepSeek / 智谱 GLM-4 / 通义千问
- 定时调度：robfig/cron v3

---

## 📊 项目统计

<div align="center">
  <table>
    <tr>
      <th>分类</th>
      <th>项目数量</th>
      <th>主要技术</th>
    </tr>
    <tr>
      <td>🔧 系统设计</td>
      <td>3</td>
      <td>OCaml, C, RISC-V</td>
    </tr>
    <tr>
      <td>🧠 数据与人工智能</td>
      <td>4</td>
      <td>Python, C++, Vue 3</td>
    </tr>
    <tr>
      <td>💻 硬件设计</td>
      <td>3</td>
      <td>Verilog, FPGA, PCB</td>
    </tr>
    <tr>
      <td>📱 软件开发</td>
      <td>3</td>
      <td>C# (WPF), Vue.js, Python</td>
    </tr>
    <tr>
      <td>📚 知识管理</td>
      <td>1</td>
      <td>Markdown, Obsidian</td>
    </tr>
    <tr>
      <td>🐣 其他</td>
      <td>1</td>
      <td>Go</td>
    </tr>
    <tr>
      <td><b>总计</b></td>
      <td><b>15</b></td>
      <td>-</td>
    </tr>
  </table>
</div>

---

<div align="center">

  *持续更新中...* 🚀

</div>