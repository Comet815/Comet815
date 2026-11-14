# Comet815

> 青海 · 青北鹿工作室 · 做 AI 落地：本地部署、审查验证、生产流水线

**中文** · [English](README.en.md)

我做的是"把 AI 装进别人的机器里，并且证明它干得对"这一类活。

不是调 API 写 demo，是把模型、硬件、流程和证据链凑成一个能交付的东西。

---

## 现在

- 青海民族大学企业导师
- 带队拿了省赛成绩，下一步冲击国赛
- 本地模型部署跑在 Mac mini、Windows / Linux 迷你主机（N100 / 8845HS 等）上，跑得动才算数

---

## 两个项目

### [AuditX Verifier](https://github.com/Comet815/auditx-verifier) · 审查庭

[![CI](https://github.com/Comet815/auditx-verifier/actions/workflows/ci.yml/badge.svg)](https://github.com/Comet815/auditx-verifier/actions/workflows/ci.yml)

**别信我，自己算。**

审查账本的独立复核器：哈希链 + 逐条 Ed25519 签名 + 被审文件清单 + 证据原文核对。
客户双击一个 HTML，浏览器本地重算一遍，不联网、不装 Python。

`Python` `JavaScript` `Cryptography` `零依赖`

**[▶ 在线演示](https://comet815.github.io/auditx-verifier/)** —— 点开就能验，绿的是原始账本，红的是被改了一个词的。

**适用场景：**

- 单位软件验收：交付的不是一份 Word，而是一条能自己算的账本
- 代码审查：缺陷、整改条件、结论都留痕，改了能查出来
- 需要对外举证的交付：谁审的、审的哪一版、改没改过，都能复核

![审查庭](docs/auditx.png)

### [Hummingbird](https://github.com/Comet815/hummingbird) · 蜂鸟

**贵的地方只花在判断上，便宜的地方用来干活。**

一个人用的 AI 生产流水线方法：云上定标准，本地干活，机器门禁，换角色验收。
代码不公开，方法公开。

📄 **[方法全文 → METHOD.md](https://github.com/Comet815/hummingbird/blob/main/METHOD.md)**

![蜂鸟架构](https://raw.githubusercontent.com/Comet815/hummingbird/main/docs/hummingbird-arch.png)

`Method` `LLM Pipeline` `Cost Engineering`

实测：本地写手 26.8 tok/s，门禁测试 11/11 一次跑通，云端成本每次几分钱。

---

## 在开发

- 独立横版动作平台跳跃游戏（开发中，之后加进主页）

---

## 在做的事

- 本地模型部署（Mac mini、Windows / Linux 迷你主机上，跑得动才算数）
- 给单位做软件验收与代码审查，出可复核的报告
- 把"审查"这件事从一份 Word 变成一条能自己算的账本

## 如何合作

**接这两类活：**

1. **本地模型部署** —— Mac mini、Windows / Linux 迷你主机上，跑得动才算数
2. **软件验收与代码审查** —— 出可复核的报告，不是只给一份 Word

**流程：**

1. 沟通需求和机器环境
2. 先定验收标准，再开工
3. 本地部署 / 审查，过程留痕
4. 交付报告 + 可独立复核的账本，客户自己能重算一遍

周期和费用按项目定，先聊需求再报价。

## 技术栈

Python · JavaScript · Ed25519 · JSONL 哈希链 · llama.cpp / 本地推理 · Windows 工控环境

## 也接开发

JavaScript · PHP · 网页开发

---

## 联系方式

- 邮箱：joe09598375@gmail.com
- 微信：tk1264

---

*青北鹿 · 青海*
