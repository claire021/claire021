# README_ZH.md
<div align="center">

# 你好！我是 Menghan Dai 👋
### AI 工程师 | 计算语言学在读

[**English**](./README.md) | 中文版

---

</div>

<div align="center">

---

### 🛠 技术栈
**编程语言:** ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white) ![Shell](https://img.shields.io/badge/Shell-444444?style=flat&logo=gnu-bash&logoColor=white)  
**深度学习/NLP:** ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)  
**工具与环境:** ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white)  
**IDE:** ![IntelliJ](https://img.shields.io/badge/IntelliJ-000000?style=flat&logo=intellijidea&logoColor=white) ![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat&logo=pycharm&logoColor=white) ![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

</div>

### 🔬 研究兴趣
*   **LLM 全栈:** 预训练、指令微调（SFT）与偏好对齐（DPO/GRPO/RLHF）。
*   **计算基础:** 将概率论与信息论应用于模型可解释性研究。
*   **工程实践:** **知识图谱 (KG)**、高效 RAG 系统、分布式训练与推理优化。

### 📂 项目经历

#### 🚀 基于 Llama3 的轻量级大语言模型训练与对齐系统
*   **核心架构:** 基于 Decoder-only 架构复现 Llama 3 核心模块，完成 **RoPE 位置编码、GQA 注意力、KV Cache、RMSNorm** 等模块开发。
*   **训练全流程:** 基于 PyTorch 搭建预训练、SFT 和 LoRA 微调代码，支持混合精度、梯度累积；结合对话模板与 **Loss Mask** 设计，减少无效信号干扰，提升训练稳定性。
*   **偏好对齐:** 实现 **DPO、GRPO** 等后训练方法，结合规则奖励与推理格式约束，显著提升模型回答的一致性和推理结果的格式稳定性。

#### 🔍 基于图增强 (Graph-RAG) 的垂域智能问答系统
*   **知识图谱集成:** 利用 **Neo4j** 构建实体间复杂关系网（如菜谱、食材、步骤、关联属性等），实现多跳逻辑推理，有效解决了传统 RAG 在处理非结构化关联知识时的断层问题。
*   **结构化分块:** 针对 Markdown 语义截断痛点，自研**结构感知分块**策略，落地“**子块召回、父文档生成**”策略，保障连续性知识的完整输出。
*   **混合检索与意图增强:** 构建 **向量搜索 (Milvus) + Cypher 图查询** 双路混合检索，集成 **RRF 算法**融合重排；前置 Query 重写与动态路由，指标达到 **Recall 97.4%, Precision 83.0%**。
*   **RAGAS 评测:** 基于 **RAGAS** 搭建自动化评测流水线，核心指标达准生产级：Faithfulness 75.4%, Relevancy 78.2%, Correctness 78.5%。

---

## 📈 GitHub 统计
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=claire021&show_icons=true&theme=radical&hide_border=true" />
</div>

<div align="right">
  <a href="#-你好我是-Menghan Dai-">返回顶部</a>
</div>
