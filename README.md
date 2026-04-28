# vcvyg

目前求职方向是 **AI 原生工程师 / LLM 应用开发 / RAG 知识库系统 / Agent 应用开发**。

我更关注把大模型能力落到真实业务和产品场景里：从文档解析、Embedding、向量检索、Rerank、Prompt 设计，到 Agent Tool Use、后端 API、前端演示和效果评估，尽量把一个 AI 应用做成可运行、可解释、可迭代的工程系统。

## 求职方向

- AI 开发
- RAG 知识库与企业文档问答
- Agent 架构、Tool Use、Planning、Memory
- LLM 接入、Prompt Engineering、效果评估与调优
- Python 后端工程、FastAPI 服务、AI 应用产品原型

## 技术栈

**AI / LLM**

- RAG、Embedding、Hybrid Retrieval、Rerank、Citation、Evidence Guard
- OpenAI-compatible API、DeepSeek、Qwen、OpenAI、混元等模型接入思路
- Prompt Engineering、结构化输出、低证据保护、问答评估

**Backend / Engineering**

- Python、FastAPI、Pydantic、Uvicorn
- REST API、文档解析、数据清洗、模块化工程组织
- Linux、screen、远程服务部署与调试

**Knowledge / Data**

- Chroma、TF-IDF、向量检索、关键词检索、知识库构建
- Neo4j、知识图谱、Cypher、KBQA、图谱可视化
- PDF、DOCX、Markdown、TXT 等资料解析

**Machine Learning**

- 机器学习基础、深度学习、NLP、CV
- CNN / ResNet、模型训练流程、评估指标、实验记录

## 重点项目

### AI 课程资料知识库 + 学习 Agent 系统

Repo: [ai-native-knowledge-agent](https://github.com/vcvyg/ai-native-knowledge-agent)

面向大学课程复习场景的 RAG + Learning Agent 系统。用户上传课件、笔记、实验报告后，系统自动构建课程资料知识库，并支持资料问答、知识点总结、自动出题、复习计划、错题回顾和简历化项目分析。

关键词：

- FastAPI + RAG + Agent Router
- Chroma / TF-IDF 向量检索后端
- Hybrid Retrieval + Rerank
- Evidence Guard，低证据不强行回答
- Tool Trace、Session Memory、Runtime Metrics
- OpenAI-compatible LLM Adapter

这个项目主要用来体现 AI 原生工程岗位需要的完整链路：业务场景设计、知识库构建、LLM 调用、Agent 工具选择、前端演示、指标展示和工程可迭代性。

### NLP 知识图谱自动化构建与智能问答系统

Repo: [nlp_kg_llm](https://github.com/vcvyg/nlp_kg_llm)

围绕自然语言处理课程知识构建知识图谱，并实现 Web 可视化与大模型增强问答。系统覆盖课程语料整理、实体关系抽取、Neo4j 图数据库建模、KBQA 问答和图谱联动展示。

关键词：

- Python + FastAPI + Neo4j
- NLP 实体关系抽取
- Knowledge Graph + KBQA
- LLM 增强问答
- 图谱可视化与节点关系探索

说明：该项目用于课程设计/竞赛展示。因参赛评审与项目保护要求，仓库仅公开 README 与系统效果图，暂不公开源码、运行配置、数据库文件和原始数据集。

### 深度学习课程设计

项目整理中。主要方向包括图像分类、CNN / ResNet 模型训练、训练流程设计、实验结果分析和可视化展示。后续会整理为更完整的项目说明与实验报告。

## 我正在加强的能力

- 将 RAG 原型升级为更标准的向量数据库方案，例如 bge embedding、Chroma、FAISS、Milvus 或 pgvector。
- 引入 Cross-Encoder / LLM Rerank，提高复杂问题下的证据排序质量。
- 构建问答评估集，统计 Top-K 命中率、MRR、引用覆盖率、低证据拦截率和工具选择准确率。
- 用 Docker Compose 管理前后端、向量数据库和模型服务，让项目更接近真实工程部署。
- 继续补充 AI Agent 项目的产品化体验和面试可讲的工程难点。

## 简历关键词

`Python` `FastAPI` `RAG` `Agent` `Embedding` `Chroma` `Neo4j` `Knowledge Graph` `Prompt Engineering` `LLM` `Tool Use` `Memory` `Rerank` `NLP` `Deep Learning`

## GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=vcvyg&show_icons=true&theme=default&hide_border=true)

