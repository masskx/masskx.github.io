---
layout: page
title: Loop RAG Engineering Lab
description: Observable RAG with evaluation, query rewriting, budgets, and execution traces.
importance: 1
category: AI Engineering
---

一个面向 RAG 进阶学习者的闭环工程实验室。项目把检索、回答、质量评估、查询改写和再次检索组织为显式的 LangGraph 工作流。

核心设计包括：

- 确定性规则与 LLM Judge 组成的质量门；
- 明确的循环预算和停止条件；
- 查询改写与逐轮扩大检索范围；
- 保存完整 JSON 运行轨迹，便于观察和复盘；
- 无需调用模型即可运行的质量门测试。

[View source on GitHub →](https://github.com/masskx/loop-rag-engineering-lab)
