# AGENTS.md — 给 AI Agent 的工作指引

本文件面向自动化 AI Agent。人类读者请看 [README.md](README.md)。

## 这个仓库是什么

`traceability-audit` 是一个**纯文档仓**（多语种理论正文），不是可运行的 SDK。核心资产是 `theory/THEORY.md`（中文）与八语种译文，外加指针索引、署名规范、全景图。版本 v0.1-theory-stance，主指纹 FP-MX-836A60CCF23F。

## 可用的工作命令

```bash
# 读中文理论正文
cat theory/THEORY.md

# 读某语种译文（示例英文）
cat theory/THEORY.en.md

# 核对发布元数据与指纹
cat gov_release-meta_v0.1-theory-stance.json
```

前置依赖：无。

## 约定（Do）

- 修改译文时保持与中文正文语义一致，并在指针索引登记语种状态。
- 修改版本号/指纹时，同步更新 `gov_release-meta_v0.1-theory-stance.json` 与 README 头部。
- 新增语种译文须新增 `theory/THEORY.<code>.md` 并在指针索引表加行。

## 禁止（Don't）

- 不要改动 `LICENSE` 的版权主体（Copyright (c) 2026 SynomosAI）与 README 头部版权行——**权属字段只由维护者变更**。
- 不要在仓内提交任何密钥、令牌或真实客户数据。
- 不要声称本仓「已认证 / 已商用交付 / 已服务特定客户」或作任何临床/功效声明。
- 不要把本仓当作可执行检查器。

## 边界

本仓专注**四支柱理论正文的多语种托管**；不覆盖具体合规检查、审计流程。理论正文镜像自上游 Medxpert-org/traceability-audit@v1.0。
