# 郭文涛 · Wentao Guo

## 教育背景

| 学校 | 学历与专业 | 时间 |
| --- | --- | --- |
| 浙江大学 | 硕士 · 人工智能 | 2021.09 – 2024.06 |
| 武汉大学 | 本科 · 计算机科学与技术 | 2017.09 – 2021.06 |

## 工作与研究方向

**腾讯 · 大模型训练数据质量｜2024.05 – 至今**

我的工作围绕大模型训练数据的质量与评估展开，覆盖文本、图像、视频和音频。重点关注如何将模型的失效模式转化为可验证的质量标准，并把评测反馈用于数据改进与模型训练。

### 大模型后训练数据质量

面向 Chatbot 与 Agent 的后训练数据，研究指令遵循、上下文完整性、事实准确性和推理质量等问题。构建通用维度与领域维度相结合的质量标准，将典型问题沉淀为自动化质检规则，并以人工标注集验证 LLM-as-Judge 的准确率与召回率，连接数据筛选、问题返修与训练准入。

### 多模态一致性与 Agentic 视频理解

关注视频内容与 Caption 的细粒度一致性。将长描述拆分为可验证的语义断言，通过时间片段定位、局部加密抽帧、Grounding 与多模型工具编排，核验主体属性、动作、时序和局部细节；区分定位误差与内容不一致，并在改写后再次核验。

### 可验证奖励与强化学习

探索将 Caption 质量评估转化为训练反馈，结合 SFT、PPO 与 RLVR 改善模型输出。关注断言级奖励对长描述训练的作用，以及模型通过减少描述信息规避扣分的问题，在事实准确性、信息丰富度与语言质量之间寻找平衡。

### Agent 数据与评测可靠性

研究任务要求、执行证据与评分规则之间的一致性：任务能否在给定环境中完成，等价正确解法是否被合理接纳，工具与环境证据能否支撑评分结论。结合静态预检、问题发现、独立验证与运行时复现，构建可追溯、可复核的自动化质检流程。

## 技术实践

- **开发与数据**：Python、SQL、Git、Linux。
- **训练与对齐**：PyTorch、SFT、PPO、RLVR、OpenRLHF、LLaMA-Factory。
- **多模态与 Agent**：VLM / MLLM、LLM-as-Judge、Function Calling、Grounding、视频与文本一致性评估。
- **数据治理**：多模态数据处理、质量标准与评测集建设、批量质检与结构化报告。

## 早期公开代码

[AISecurity](https://github.com/gwt0401/AISecurity) — 早期机器学习实践，包含基于 PyTorch 的 CIFAR-10 图像分类，以及回归模型正则化与超参数实验。

欢迎围绕大模型后训练、训练数据质量、多模态理解与 Agent 评测交流。

*I work on LLM training data quality at Tencent, focusing on post-training, multimodal consistency, verifiable rewards, and agent evaluation. Master's degree in Artificial Intelligence from Zhejiang University; bachelor's degree in Computer Science and Technology from Wuhan University.*
