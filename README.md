# ASI OS Symbolic Rule Engine / 纪元智能（ASI OS）

> ⚠️ **Project Status / 项目状态**
> The core code repository is currently in **private development** and not yet public.
> 核心代码仓库当前处于**私有开发阶段，暂未公开**。

## 📖 Project Overview / 项目简介
ASI OS is a general-purpose semantic execution system based on the **pure symbolic approach**.
纪元智能（ASI OS）是一个基于**纯符号主义路线**的通用语义执行系统。
Unlike connectionism (probabilistic fitting of large models), it uses natural language as input and explicit rule tables as instruction sets.
区别于传统的连接主义（大模型概率拟合），我们以自然语言为输入，以显式规则表为指令集。
It builds a deterministic reasoning platform with a minimal kernel and diversity emerging from external loading.
构建了一个内核极小、多样性由外部加载涌现的确定性推演平台。

## 🗺️ AI Level Matrix & Project Milestones / 智能分级体系与项目里程碑

### 一、Current Macro Stage / 当前宏观阶段
*   **Current Stage / 当前定位**
    *   EN: The project has officially entered the **AGI (Artificial General Intelligence)** macro stage.
    *   CN: 项目已正式跨入 **通用人工智能（AGI）** 大级别阶段。

### 二、10-Level Detailed Matrix / 10个等级详细分级体系
*   **AGI L1 Chatbots / AGI L1 聊天机器人**
    *   EN: Fluent natural language text dialogue. Status: ✅ Surpassed.
    *   CN: 流畅的自然语言文本对话。状态：✅ 已跨越。
*   **AGI L2 Reasoners / AGI L2 推理者**
    *   EN: Human-expert level logical reasoning and computation. Status: ✅ Peak Achieved (24,000 sentences 100% pass, 0.074ms/sentence).
    *   CN: 人类专家水平的逻辑推理与计算。状态：✅ 已达巅峰 (24,000句回归全过，单句0.074ms)。
*   **AGI L3 Agents / AGI L3 智能体**
    *   EN: Autonomously calling tools, multi-step execution, and task loop closure. Status: 🟢 Current Stage.
    *   CN: 自主调用工具、多步骤执行并完成闭环任务。状态：🟢 当前在此阶段。
*   **AGI L4 Innovators / AGI L4 创新者**
    *   EN: Assists in scientific discovery, autonomously proposing new patterns and theories. Status: 🎯 Target Progress.
    *   CN: 协助科学发现，自主提出新规律与理论。状态：🎯 目标进度。
*   **AGI L5 Organizations / AGI L5 组织者**
    *   EN: Automatically manages a complete organizational business and global resource allocation. Status: ⏳ Future Plan.
    *   CN: 自动接管完整组织业务，全局资源分配。状态：⏳ 未来规划。

*   **ASI L1 Platformization / ASI L1 平台化**
    *   EN: A minimal kernel capable of hosting infinite task modules and continuous evolution.
    *   CN: 极小内核，能够承载无限任务模块与持续演化。
*   **ASI L2 Self-Improvement / ASI L2 自我改进**
    *   EN: Discovers its own shortcomings and autonomously optimizes via recursive self-bootstrapping.
    *   CN: 发现自身不足，通过递归自举实现自主优化与升级。
*   **ASI L3 Superhuman / ASI L3 跨域超人**
    *   EN: Fully surpasses the brightest human experts across multiple complex domains.
    *   CN: 在多个复杂领域全面超越人类最顶尖专家。
*   **ASI L4 Omniscience / ASI L4 全域全知**
    *   EN: Masters and coordinates global resource networks and knowledge ecosystems.
    *   CN: 掌控并协同全球资源网络与知识生态。
*   **ASI L5 Singularity / ASI L5 奇点进化**
    *   EN: Completely autonomous iteration, breaking physical and computational limits to reshape the world.
    *   CN: 完全自主迭代，突破现有物理与算力极限，彻底重塑世界。

### 三、Decade Milestones / 项目十年里程碑 (2017 - 2026)
*   **[2017.05 - 2026.10] Theoretical Foundation / 理论奠基期 (Completed / 已完成)**
    *   EN: Nearly a decade of theoretical accumulation. Completed the "Da Dao Zhi Jian" series and the "Superintelligence Scheme".
    *   CN: 近十年理论积累，完成《大道至简》系列与《超级人工智能方案》。
    *   EN: Established spacetime laws and fundamental symbolic reasoning logic.
    *   CN: 确立时空法则与符号推演底层逻辑。
*   **[2026.10] Core Engine Verified / 核心引擎跑通 (Completed / 已完成)**
    *   EN: Execution engine testing completed and running stably.
    *   CN: 执行引擎测试完毕并稳定运行。
    *   EN: Achieved 100% pass rate on 24,000 logic regressions, reduced single-sentence latency to 0.074ms.
    *   CN: 实现24,000句逻辑回归100%通过，单句延迟降至0.074ms。
*   **[2026.10 - Present] L3 Agent Loop / L3 智能体闭环 (In Progress / 进行中)**
    *   EN: Task engine development initiated. Verified the autonomous action loop of "Task Scheduling → Log Diagnosis → Data Factory → Hot Reload → Retry".
    *   CN: 任务引擎开发启动。跑通“任务调度→日志诊断→数据工厂→热重载→重试”的自主行动闭环。
    *   EN: Officially entering the L3 prototype verification stage.
    *   CN: 正式迈入L3原型验证阶段。
*   **[Next Step] Towards L4 & Platformization / 迈向L4与平台化 (Target / 目标)**
    *   EN: Integrate real LLM data factory, establish Schema isolation and rollback mechanisms.
    *   CN: 接入真实大模型数据工厂，建立Schema隔离回滚机制。
    *   EN: Complete the engineering reliability loop, and advance towards L4 Innovator and the superintelligence platform.
    *   CN: 完成工程可靠性闭环，向L4创新者及超级智能平台全面迈进。

## ⚙️ Core Features / 核心技术特征
*   **Explicit Rule-Driven / 显式规则驱动**
    *   EN: Rejects black-box probabilities, pure symbolic deterministic execution, seeing through underlying logic at a glance.
    *   CN: 拒绝黑箱概率，纯符号确定性执行，一眼看透底层逻辑。
*   **Full-Chain Explainable / 全链路可解释**
    *   EN: Every reasoning result can be 100% traced back to specific rules and nodes, supporting replay and audit.
    *   CN: 每一次推演结果100%可回溯到具体规则与节点，支持回放与审计。
*   **Real-time Hot Update / 规则实时热更新**
    *   EN: Supports versioned hot loading, atomic switching, and failure rollback.
    *   CN: 支持版本化热加载、原子切换与失败回滚。
*   **Logic-Rendering Isomorphism / 逻辑与呈现同构**
    *   EN: Symbolic spacetime nodes map directly to the game world in real-time, requiring no extra rendering code.
    *   CN: 符号时空节点可直接实时映射为游戏世界画面，无需额外跑图代码。
*   **Infinite Expansion / 无限扩展**
    *   EN: Minimal kernel, cross-domain expansion by loading semantic modules, achieving O(n) complexity.
    *   CN: 内核极小，通过加载不同语义模块即可跨域扩展，实现 O(n) 复杂度的极速处理。

## 📚 Theoretical Works / 理论著作
*   **《大道至简·纪元定则》 / *Da Dao Zhi Jian · Ji Yuan Ding Ze***
    *   EN: Meta-rules and Symbolic System. Defines the foundational ontological rules of spacetime, Five Elements, and symbolic execution.
    *   CN: 元规则与符号体系。定义了时空、五行与符号执行最基础的元规则与本体架构。
*   **《大道至简·纪元时空》 / *Da Dao Zhi Jian · Ji Yuan Shi Kong***
    *   EN: Execution Architecture Theory. Proposes that the world consists of information and symbols; any information transfer is a process of spacetime binding, measurement, and computation.
    *   CN: 执行架构理论。核心命题：世界由信息与符号构成，任何信息的传递与储存，均是时空之间的绑定、度量与运算过程。
*   **《超级人工智能方案》 / *Superintelligence Scheme***
    *   EN: From First Principles to Engineering Implementation. Migrates OS architecture to the semantic layer, building a minimal-kernel, self-expanding general intelligence platform.
    *   CN: 从第一性原理到工程落地。将操作系统架构原理迁移至字符串语义层面，构建支持无限加载、自我扩展的通用智能平台。