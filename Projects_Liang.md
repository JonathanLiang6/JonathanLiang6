# 📂 项目总览

Welcome to my project portfolio! This document provides detailed information about all my public repositories on GitHub, organized by professional domains.

---
## 🧠 数据与人工智能 Data & AI

### 🔗 KnowledgeGraph

**语言** | **Language**: Python + Vue.js

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/KnowledgeGraph)

**项目概述** | **Overview**

个人知识库管理平台 v4.0。将非结构化文档转化为结构化知识图谱，提供拓扑导航、混合检索、Agent 多步推理与知识覆盖诊断。采用 FastAPI + Vue 3 技术栈，支持 Docker 一键部署。

**核心特性** | **Features**

- 拓扑导航台：基于 D3.js 力导向图的层级知识库管理，支持自由增删节点、调整父子从属关系
- 文档管理：支持 PDF/DOCX/PPTX/EPUB/Markdown/HTML/TXT/图片多格式上传
- 知识图谱：文档上传后自动构建实体-关系知识图谱，双轨存储架构
- 智能问答：SSE 流式输出，Markdown 实时渲染，打字机效果光标
- Agent 工具集：支持多步推理、记忆系统、联网搜索、图像感知
- 知识覆盖诊断：基于关键词分类映射表，ECharts Treemap 矩形树图渲染

**技术亮点** | **Technical Highlights**

- 检索融合 (RRF) 算法
- 文档处理流水线（6阶段异步处理）
- 实体对齐与关系去重
- PaddleOCR + BLIP 图像感知
- 向量嵌入与索引构建

---

### 🎥 BayesSigmoid-Defocus

**语言** | **Language**: Python

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/BayesSigmoid-Defocus)

**项目概述** | **Overview**

个性化离焦剂量探索系统。基于贝叶斯 Sigmoid（四参数逻辑斯蒂）模型和主动学习策略，为每个受试者动态推荐下一个离焦测量剂量。系统以最少实验次数（通常 2~5 次）估计个体离焦阈值（ED50）和最佳剂量。

**核心特性** | **Features**

- 双点启动（2.0D, 4.0D）避免单点方向误判
- 贝叶斯 MCMC 推断（PyMC）量化不确定性
- 主动学习采集函数：后验方差（探索）+ 期望改进（开发）
- 自动停止条件
- 纯 Python 脚本运行，无需 Jupyter

**技术亮点** | **Technical Highlights**

- 四参数 Sigmoid 剂量-反应模型
- PyMC 贝叶斯推断（4链MCMC，R̂ < 1.05收敛诊断）
- 主动学习策略（探索-开发权衡）
- 可视化图表生成与结果分析

---

### 📝 PorterStemmer_Imitation

**语言** | **Language**: C++20

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/PorterStemmer_Imitation)

**项目概述** | **Overview**

基于 Porter Stemmer 算法改进的文本分析系统。实现英文词干提取、文本相似度计算和交互式查询功能。

**核心特性** | **Features**

- 英文词干提取（改进版 Porter Stemmer）
- 文本相似度计算
- 交互式查询界面
- UTF-8 编码支持

**技术亮点** | **Technical Highlights**

- AVL 树数据结构应用
- C++20 现代特性
- 算法优化策略

---

### 🛡️ 天盾 - 反诈智能体助手

**语言** | **Language**: Python + Vue 3

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/fanzha)

**项目概述** | **Overview**

天盾是一个基于 doubao-seed2 多模态大模型的反诈智能体助手系统，实现了"感知 → 决策 → 干预 → 进化"四阶能力闭环。支持文本、语音、图像、视频多种模态输入，能够精准识别12种常见诈骗类型，并提供分级预警、监护人联动和个性化风险评估。

**核心特性** | **Features**

- 多模态诈骗检测：文本/语音/图片/视频
- 12种诈骗类型识别：投资理财、刷单返利、冒充公检法等
- 分级预警机制：低/中/高/紧急四级
- 监护人联动：自动通知 + 风险事件推送
- 个性化风险评估：基于用户画像动态调整阈值
- 知识库自适应进化：自动爬取更新反诈案例
- 安全监测报告：可视化统计分析

**技术亮点** | **Technical Highlights**

- FastAPI 后端架构，WebSocket 实时通信
- ChromaDB 向量数据库实现语义检索
- doubao-seed2 多模态大模型集成（火山引擎）
- Vue 3 + Element Plus + ECharts 可视化前端
- SQLite 关系数据库管理

---

## 📱 软件开发 Software Development

### 📝 NoteMaster

**语言** | **Language**: C# (WPF)

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/NoteMaster)

**项目概述** | **Overview**

基于 WPF 框架开发的 Windows 桌面笔记管理应用。采用 MVVM 架构，支持笔记创建/编辑/删除、文件夹管理、待办事项管控及笔记搜索筛选等核心功能。

**核心特性** | **Features**

- 笔记创建、编辑、删除
- 文件夹层级管理
- 待办事项管理
- 笔记搜索与筛选
- 数据持久化存储

**技术亮点** | **Technical Highlights**

- MVVM 架构设计
- SQLite 数据库集成
- JSON 数据处理
- 响应式 UI 设计

---

### 📦 CsharpLittleApps

**语言** | **Language**: C#

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/CsharpLittleApps)

**项目概述** | **Overview**

多个 C# 小项目的集合，用于学习和展示 C# 语言的各种应用场景。涵盖控制台应用、Windows 窗体、WPF 等多种开发模式。

**核心特性** | **Features**

- 多种类型的 C# 应用示例
- 面向对象编程实践
- .NET 框架特性展示

**技术亮点** | **Technical Highlights**

- C# 语言特性综合应用
- 跨项目代码复用

---

### 📊 PythonCodeVisualization

**语言** | **Language**: Vue.js + TypeScript + Python

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/PythonCodeVisualization)

**项目概述** | **Overview**

Python 代码可视化项目，用于 Python 语言教学相关。帮助学习者理解和分析代码结构与执行流程，提升编程学习效率。

**核心特性** | **Features**

- Python 代码结构可视化
- 代码执行流程动态展示
- 交互式分析界面
- 前后端分离架构

**技术亮点** | **Technical Highlights**

- Vue 3 + TypeScript 前端框架
- Python 后端服务
- 代码静态分析与解析

---

## 💻 硬件设计 Hardware  Design

### 🧠 RISC-V_PipeLine_CPU

**语言** | **Language**: Verilog

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/RISC-V_PipeLine_CPU)

**项目概述** | **Overview**

基于 RISC-V RV32I 指令集的五级流水线 CPU 设计。实现了完整的取指、译码、执行、访存、写回五个阶段，支持数据冒险和控制冒险的检测与处理。适配 Nexys4DDR 开发板，可完成仿真验证与 FPGA 上板部署。

**核心特性** | **Features**

- 五级流水线架构（IF/ID/EX/MEM/WB）
- 数据前推（Forwarding）机制消除数据冒险
- 分支预测与冲刷（Flush）处理控制冒险
- 支持完整的 RV32I 基础整数指令集
- 集成指令/数据内存与通用寄存器堆
- 适配 Xilinx Nexys4DDR FPGA 开发板

**技术亮点** | **Technical Highlights**

- 流水线冲突检测与解决策略
- 模块化设计，便于扩展与维护
- 完整的仿真测试与验证流程

---

### ⚡ RISC-V_SingleCycle_CPU

**语言** | **Language**: Verilog

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/RISC-V_SingleCycle_CPU)

**项目概述** | **Overview**

基于 RISC-V RV32I 指令集的单周期 CPU 实现。使用 Verilog HDL 完成核心的数据处理、内存访问和控制流指令，通过板载七段数码管动态显示内部状态与执行结果。

**核心特性** | **Features**

- 单周期指令执行架构
- 支持 RV32I 核心指令集
- 七段数码管动态扫描显示
- LED 状态指示系统
- 时钟分频与控制逻辑

**技术亮点** | **Technical Highlights**

- 指令译码与控制信号生成
- 算术逻辑单元（ALU）设计
- 内存映射 I/O 接口

---

### ⏱️ GW_Timer

**语言** | **Language**: Verilog

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/GW_Timer)

**项目概述** | **Overview**

以高云 GW1N-UV9EQ144C6/I5 FPGA 芯片为核心，设计制作的高精度秒表系统。实现 0-59:59 计时范围，支持实时显示、清零、暂停恢复、预置时间和状态指示功能。

**核心特性** | **Features**

- 00:00-59:59 精准计时
- 暂停与恢复功能
- 时间预置功能
- LED 状态指示系统
- 七段数码管显示

**技术亮点** | **Technical Highlights**

- 高云 FPGA 芯片开发
- 数字逻辑电路设计
- PCB 硬件开发

---


## 💻 系统设计 System  Design

### 🔧 toyc_compiler 

**语言** | **Language**: OCaml

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/toyc_compiler)

**项目概述** | **Overview**

Fork 自 Icarus-Yu/toyc_compiler。基于 OCaml 实现的编译器前端，支持词法分析、语法分析和语义分析等编译流程。

**核心特性** | **Features**

- 词法分析（Lexing）
- 语法分析（Parsing）
- 抽象语法树（AST）构建
- 语义检查

**技术亮点** | **Technical Highlights**

- 编译器理论实践
- OCaml 函数式编程
- 形式语言与自动机

---

### 🖥️ xv6_labs

**语言** | **Language**: C

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/xv6_labs)

**项目概述** | **Overview**

xv6-labs-2022 实验代码库，基于 Unix v6 的教学操作系统。用于操作系统原理的学习与实验，涵盖进程管理、内存管理、文件系统等核心模块。

**核心特性** | **Features**

- 基于 RISC-V 的操作系统实现
- 进程调度与管理
- 虚拟内存与分页机制
- 文件系统实现
- 系统调用接口

**技术亮点** | **Technical Highlights**

- 操作系统核心原理实践
- RISC-V 架构适配
- 并发控制与同步机制

---

### 📚 CSAPP_Labs

**语言** | **Language**: C

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/CSAPP_Labs)

**项目概述** | **Overview**

《深入理解计算机系统》（CSAPP）课程实验代码库，包含 DataLab、BombLab、AttackLab 全过程帮助文档与相关文件。

**核心特性** | **Features**

- DataLab：位级编程实验
- BombLab：逆向工程实验
- AttackLab：缓冲区溢出攻击实验
- 完整的实验指导文档

**技术亮点** | **Technical Highlights**

- 计算机系统底层原理
- 汇编语言与机器级编程
- 系统安全与漏洞分析

---

## 📚 知识管理 Knowledge Management

### 📖 Liang_Online_Knowledge_Repository (LOKR)

**语言** | **Language**: Markdown + Obsidian

**链接** | **Link**: [GitHub](https://github.com/JonathanLiang6/Liang_Online_Knowledge_Repository)

**项目概述** | **Overview**

良识云库（LOKR）是基于 Obsidian 构建的知识集合平台，由 JonathanLiang 发起打造。内容丰富且不断扩充，推荐使用 Obsidian 软件访问以获得最佳体验。

**核心特性** | **Features**

- 多领域知识内容聚合
- 仓库克隆 + Obsidian 一键导入
- 双向链接知识网络
- 持续更新与扩充

**技术亮点** | **Technical Highlights**

- Obsidian 知识管理生态
- Markdown 文档标准化
- 知识图谱思维模式

---

## 📊 项目统计

| 分类 | 项目数量 | 主要技术 |
|------|----------|----------|
| 硬件与系统设计 | 5 | Verilog, C |
| 软件开发 | 3 | C#, Vue.js, Python |
| 数据与人工智能 | 5 | Python, C++, OCaml, Vue 3 |
| 知识管理 | 1 | Markdown, Obsidian |
| **总计** | **15** | - |

---

*持续更新中...* 🚀