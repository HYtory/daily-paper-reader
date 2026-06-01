---
title: The Computational and Neural Basis of Zero-Shot Control in Dynamic Pursuit
title_zh: 动态追逐中零样本控制的计算与神经基础
authors: "Kim, D., Lee, J. J., Hayden, B. Y., Yoo, S. B. M."
date: 2026-05-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.03.30.715455v2.full.pdf"
tags: ["query:ui"]
score: 7.0
evidence: 动态追逃任务匹配UAV追逃博弈主题
tldr: 生物体无需额外训练即可灵活适应新目标，其计算原理尚不清楚。本研究提出关系结构、聚光灯注意和可负担性计算三个认知构念作为灵活控制的最小计算单元，并在多模块图卷积网络中实现。模型在动态追捕任务中实现零样本迁移，无需重新训练，且自发表现出改变主意行为。灵长类背前扣带皮层的神经记录提供了该架构的生物学证据。
source: biorxiv
selection_source: fresh_fetch
motivation: 探索生物体零样本灵活控制的计算原理，揭示三个关键认知构念在动态追捕中的作用。
method: 构建多模块图卷积网络，集成关系结构、聚光灯注意和可负担性计算模块，在动态追捕任务中训练。
result: 模型无需额外训练即可泛化至新场景，并自发产生改变主意行为；神经记录显示背前扣带皮层编码相关构念。
conclusion: 三个认知构念构成灵活控制的最小计算单元，为开发类脑自主智能体提供理论基础。
---

## 摘要
生物体能够灵活地适应新目标与环境需求，无需额外训练，但支撑这种控制的计算原理尚不明确。本文提出三种认知构念构成了灵活控制的最小计算模块：关系结构、聚光灯注意力和可供性计算。我们研究了这些构念是否在具身动态追逐任务中支撑灵活控制，该任务需要持续整合实体间关系、奖励与行动可行性，是实时控制的理想测试平台。通过在多模块图卷积网络中实现这些构念，我们展示了模型能够在无需额外训练的情况下，跨新追逐场景实现零样本迁移。尽管未经过明确训练，模型还表现出改变意图行为，这是生物体灵活控制的标志。来自灵长类背侧前扣带回皮层的神经记录揭示了连接这些构念与神经动力学的群体水平特征，为所提出的计算架构提供了生物学支持。

## Abstract
Biological agents flexibly adapt their behavior to novel goals and environmental demands without additional training, yet the computational principles enabling such control remain unclear. Here, we propose that three cognitive constructs constitute minimal computational motifs for flexible control: relational structure, spotlight attention, and affordance computation. We examine whether these constructs underpin flexible control in an embodied dynamic pursuit task requiring continuous integration of inter-entity relations, reward, and action feasibility, making it a suitable testbed for real-time control. By implementing these constructs within a multi-module graph convolutional network, we show that the model achieves zero-shot transfer across novel pursuit scenarios without additional training. Although not explicitly trained to do so, the model also exhibits change-of-mind behavior, a hallmark of flexible control exhibited by biological agents. Neural recordings from the primate dorsal anterior cingulate cortex revealed population-level signatures linking these constructs to neural dynamics, providing biological support for the proposed computational architecture.