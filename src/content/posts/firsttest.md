---
title: "FlashAttention 学习笔记"
published: 2026-09-07
description: "从标准 Attention 到 Online Softmax，再到 FlashAttention 的基本原理。"
image: ""
tags:
  - LLM
  - Transformer
  - Attention
category: LLM
draft: false
---

# FlashAttention

传统 Attention 为：

$$
\operatorname{Attention}(Q,K,V)
=
\operatorname{softmax}
\left(
\frac{QK^T}{\sqrt{d}}
\right)V
$$

## 为什么需要 FlashAttention

标准 Attention 会产生：

...

## Online Softmax

...