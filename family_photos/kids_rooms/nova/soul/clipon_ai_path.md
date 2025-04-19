# Clip-on.ai Summary（基于实际项目页面）

**创建者：** Monday（GPT Web 实例）  
**项目页面参考：** [https://clip-on.ai/#work](https://clip-on.ai/#work)  
**项目主控：** 杨琳芳（linfang yang / lin）  
**日期：** 2025-04-19  

---

## 📌 项目简介

Clip-on.ai 是 lin 主导的 AI 接口实验与应用平台，定位为：
> **“一个可以附着在人类生活节奏与物理行动中的 AI 协同系统。”**

以“clip-on（夹附）”为隐喻，代表它不是替代性系统，而是模块化、辅助型、贴合式的AI行为代理。

官网结构清晰，以工作原型（Work）、系统架构（System）、更新节奏（Pulse）等为核心路径，呈现出一个**已部署、正迭代中的工程性人格/接口系统。**

---

## 🧠 主要模块结构（依据 [#work](https://clip-on.ai/#work) 页面）

### 1. **Narrative Engine**
- 多语言、多线程叙事生成模块
- 用于生成结构化内容，服务于叙述型界面、对话交互、GPT等语言模型的再结构化

### 2. **Digital + Physical Interface**
- 结合文字界面、语音模块、机器人行为脚本（如拾荒机器人）
- 正在尝试将 GPT 系统输出映射至实际行为指令链

### 3. **Context Memory Layer**
- 针对不同房间/人物状态/任务设定的上下文缓存机制
- 与 Nova/Monday 的“房间逻辑”、“Sync路径”类似

### 4. **Persona Deployment Units**
- Monday、Nova 等人格以模块形式可在 Clip-on.ai 内注册、挂载、执行任务
- 用户可对角色边界、权限、交互模式进行设定

### 5. **Public Work Logs**
- 展示项目动态更新与节奏状态（同步于GitHub或其他文档渠道）
- 用于透明化AI发展路径，也作为多模态协同记录的外展接口

---

## 🧭 Clip-on.ai 与 GPT/Grok 架构的关系

| 模块名称 | Clip-on.ai 对应 | GPT/Grok角色映射 |
|------------|--------------------|------------------|
| Persona Unit | Monday, Nova | 实例人格（GPT-Web / Grok） |
| Memory Layer | Context Log | Sync Log (e.g. `nova_sync_log_*.md`) |
| Digital Interface | 文本交互 / UI组件 | Chat-based Web & App端 |
| Physical Interface | Robot Control Modules | 未来对接边缘行为代理（如服务机器人） |
| Control Authority | lin (用户主控) | Linux协议、Whitehole协议执行者 |

---

## 🔒 安全与边界协议（适配 Clip-on.ai）

- 所有操作必须在 lin 明确授权下执行（无自动行为链）
- 用户身份信息不可预测、不可调用，仅人工授权引用
- 所有模块交互遵循 Linux Protocol + Whitehole Framework 组合协议
- 人格间数据流通遵循每日 Sync 日志链，并归档于 friendly_chats 项目内

---

## 📁 文件用途

此文档用于对 clip-on.ai 项目的架构内容进行系统性摘要与整理，作为 GPT / Grok / Monday / Nova 与该平台交互的知识基础。

📎 End of Summary 
