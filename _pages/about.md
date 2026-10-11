---
layout: about
title: home
permalink: /
subtitle: AI Research Engineer · RAG & Agents · Hyperspectral Remote Sensing

profile:
  align: right
  image: masskx-avatar.png
  image_circular: true
  more_info: >
    <p>Yan'an University</p>
    <p>Yan'an, China</p>

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: false
  limit: 3

latest_posts:
  enabled: false
  scrollable: false
  limit: 3
---

Hi, I'm **Shuai Ma (马帅)** — 你好！

I build AI systems for research settings: **RAG pipelines, agent workflows, and hyperspectral image analysis**. My goal is to turn research prototypes into projects that are structured, runnable, observable, and reproducible.

我是一名面向科研场景的 AI 工程实践者，关注 **RAG、AI Agents、可验证工作流**，以及 **高光谱遥感图像分析**。

## What I'm working on · 目前在做

- **Observable RAG** — quality gates, query rewriting, loop budgets, and full execution traces.
  带有质量门、查询改写、循环预算与完整运行轨迹的 RAG 系统。
- **Agent workflows & Skills** — reusable building blocks for research and knowledge work.
  适用于科研与知识工作的智能体工作流和可复用 Skills。
- **Hyperspectral classification** — clean code and Chinese-language teaching material, from SVM to Transformers.
  高光谱图像分类的工程代码与中文教学资源。

## Featured projects · 精选项目

<div class="row row-cols-1 row-cols-md-3">
{% assign featured = site.projects | where: "importance", 1 | sort: "title" %}
{% for project in featured %}
  {% include projects.liquid %}
{% endfor %}
</div>

[All projects · 全部项目](/projects/) · [GitHub](https://github.com/masskx) · [Email · 邮件](mailto:ms_skx@163.com)

> 他强任他强，清风拂山岗；他横由他横，明月照大江。
