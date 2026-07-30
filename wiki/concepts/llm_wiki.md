---
title: LLM Wiki
type: concept
created: 2026-07-29
updated: 2026-07-29
sources: [raw/articles/2026-06-30_南璋Zephyr_我用ObsidianWorkBuddy打造个人知识库.md]
---

# LLM Wiki

## 定义
一种知识管理思路——让 LLM 负责编写 Wiki（人只负责采集资料与提问），实现「一次编译、持续复用」。[?]

## 核心要点
- 人负责采集：把看到的好文章、论文、笔记存进 raw 层
- AI 负责编译：大模型读取原始资料，生成结构化 Wiki 页面并建立概念间的链接
- 知识持续生长：每次新增资料，AI 增量更新相关页面，知识滚雪球式累积
- 与 RAG 的本质区别：知识被真正沉淀下来（见 [[llm_wiki_vs_rag]]）

## 与相关概念的关系
| 概念 | 关系 |
|------|------|
| [[rag]] | 对立/对比：LLM Wiki 沉淀知识，RAG 临时拼答案 |
| [[三层分离]] | LLM Wiki 实践依赖 Raw/Wiki/Schema 三层分离 |
| [[知识摄入流程]] | 是 LLM Wiki 落地的具体操作步骤 |

## 应用场景
长期跟踪某领域的研究型学习、持续输出的内容创作、需要 DIY 配置的技术人知识库。

## 争议/分歧（如有）
> 本文观点（来源：raw/articles/2026-06-30_南璋Zephyr_我用ObsidianWorkBuddy打造个人知识库.md）：LLM Wiki 与 RAG 最大区别是知识被真正沉淀。
> 注：该对比为文章作者基于自身实践的主观框架，RAG 是否"无沉淀"存在不同工程口径，本 wiki 仅记录来源观点，未作独立判定。[?]

## 参考资料
- [2026-06-30_南璋Zephyr_我用ObsidianWorkBuddy打造个人知识库.md](../../raw/articles/2026-06-30_南璋Zephyr_我用ObsidianWorkBuddy打造个人知识库.md)
