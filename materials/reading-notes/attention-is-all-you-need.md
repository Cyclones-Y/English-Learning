# 《Attention Is All You Need》阅读笔记

## 来源和主题

- 原始材料：[`materials/inbox/Attention Is All You Need.md`](../inbox/Attention%20Is%20All%20You%20Need.md)
- 作者：Ashish Vaswani 等
- 主题：论文提出完全依赖注意力机制的 Transformer 架构，并通过机器翻译和句法分析实验评估其效果与训练效率。
- 开始阅读日期：2026-09-01

## 文章核心意思

当时主流的序列转换模型主要依赖循环神经网络或卷积神经网络。论文提出 Transformer，用注意力机制取代循环和卷积结构。实验显示，该架构在翻译质量、并行计算能力和训练成本方面具有优势，并且能够迁移到英语成分句法分析任务。

## 代表性长句

### 1. 主流模型的基础

> The dominant sequence transduction models are based on complex recurrent or convolutional neural networks that include an encoder and a decoder.

- 主干：`models are based on networks`。
- `that include an encoder and a decoder` 修饰 `neural networks`。
- 重点：完整谓语是固定搭配 `are based on`，不能漏掉 `on`。

### 2. Transformer 的核心设计

> We propose a new simple network architecture, the Transformer, based solely on attention mechanisms, dispensing with recurrence and convolutions entirely.

- 主干：`We propose a new simple network architecture.`
- `the Transformer` 是同位语，为该架构命名。
- `based solely...` 和 `dispensing with...` 补充说明架构的设计特点。

### 3. 实验结论

> Experiments on two machine translation tasks show these models to be superior in quality while being more parallelizable and requiring significantly less time to train.

- 主干：`Experiments show these models to be superior.`
- `show A to be B` 表示“实验表明 A 具有 B 的性质”。
- `being...` 与 `requiring...` 的逻辑主语都是 `these models`。
- 三个结论：质量更好、更容易并行化、训练时间更少。

## 新词汇和固定搭配

- `sequence transduction`：序列转换。
- `be based on`：基于……。
- `attention mechanism`：注意力机制。
- `dispense with`：摒弃；不再使用。
- `parallelizable`：可并行化的。
- `show A to be B`：表明 A 是或具有 B。

## 新语法结构

- 同位语：`a new simple network architecture, the Transformer` 中两部分指同一事物。
- 分词补充说明：`based solely...`、`dispensing with...` 为架构补充特征。
- `show + 宾语 + to be + 补语`：常用于论文中陈述实验或证据得到的结论。

## 真实错误和纠正

- 把 `are based on` 的完整谓语写成 `are based`：固定搭配中的介词不能省略。
- 把 `sequence transduction` 直接限定为“序列翻译”：该术语范围更广，应译为“序列转换”。
- 第一次遇到 `show A to be B` 时无法分析：先压缩为 `Experiments show...`，再识别 A 和 B，能够顺利提取三项实验结论。
