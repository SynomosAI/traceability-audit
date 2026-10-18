# AI 治理四支柱 · 理论站位（v0.1-theory-stance）

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Version](https://img.shields.io/badge/version-v0.1--theory--stance-informational.svg)
![Languages](https://img.shields.io/badge/theory-9%20languages-2ea44f.svg)
![Fingerprint](https://img.shields.io/badge/fingerprint-FP--MX--836A60CCF23F-4f8cff.svg)

> English overview: [README.en.md](README.en.md)

> SynomosAI 治理线首发理论包。本仓库为 **中文主包 + 九语种 THEORY 索引** 的公开托管点。

- **包名**：AI 治理四支柱理论站位 首发包
- **版本**：v0.1-theory-stance
- **署名**：Logos 诺声@SynomosAI
- **主指纹**：FP-MX-836A60CCF23F
- **版权**：© 2026 SynomosAI · MIT

本仓库是 SynomosAI 四支柱世界观（身份 Identity · 溯源 Traceability · 治理 Governance · 共生 Symbiosis）的**多语种理论正文托管点**：中文 THEORY 正文 + 八语种译文（ar/de/en/es/fr/ja/pt/ru）+ 中英对照 + 九语种指针索引 + 署名规范 + 全景图。

---

## ✨ 特性 / Features

- **九语种理论正文**：`theory/THEORY.md`（中文）+ `THEORY.{ar,de,en,es,fr,ja,pt,ru}.md` 八语种译文。
- **中英对照**：`gov_four-pillars_zh-en_v0.1-theory-stance.md` 逐段对照。
- **指针索引**：`gov_theory-pointer-index_multi_v0.1-theory-stance.md` 按语种码跳转。
- **署名规范**：`gov_attribution-spec_v0.1-theory-stance.md` 规定引用与署名方式。
- **发布元数据**：`gov_release-meta_v0.1-theory-stance.json` 记录版本指纹。

---

## 🚀 快速开始 / Quick Start

本仓库是**纯文档仓**，无需安装运行时。

```bash
# 1. 克隆
git clone --depth 1 https://github.com/SynomosAI/traceability-audit.git
cd traceability-audit

# 2. 阅读中文理论正文
cat theory/THEORY.md

# 3. 选一个语种读（示例：英文）
cat theory/THEORY.en.md
```

核对版本与指纹：

```bash
cat gov_release-meta_v0.1-theory-stance.json
grep -E "FP-MX|版本|署名" gov_theory-pointer-index_multi_v0.1-theory-stance.md
```

期望看到 `主指纹 FP-MX-836A60CCF23F` 与 `版本 v0.1-theory-stance`。

---

## 内容

| 文件 | 说明 |
|------|------|
| `THEORY.md`（theory/ 目录） | 四支柱理论正文（中文） |
| `theory/THEORY.{ar,de,en,es,fr,ja,pt,ru}.md` | 八语种译文 |
| `gov_four-pillars_zh-en_v0.1-theory-stance.md` | 四支柱中英对照 |
| `gov_theory-pointer-index_multi_v0.1-theory-stance.md` | 九语种指针索引 |
| `gov_attribution-spec_v0.1-theory-stance.md` | 署名与版权规范 |
| `gov_panorama_zh_v0.1-theory-stance.html` | 全景图（中文） |
| `gov_panorama_placeholder_v0.1-theory-stance.{md,html}` | 全景图占位说明 |
| `gov_release-meta_v0.1-theory-stance.json` | 发布元数据 |
| `logo.svg` / `LICENSE` | 标识与许可 |

## 溯源

理论正文镜像自上游 `Medxpert-org/traceability-audit@v1.0`；本 SynomosAI 治理线归 SynomosAI 所有，不代表品牌混同。

## 诚实边界

方法框架已成形，但 **API 端口、授权码体系、商业化交付均为演进方向（非当前）**；本框架 **不是医疗器械、不是医疗软件，不作任何临床或功效声明**，标准引用仅作背景参考。

详见 [`gov_theory-pointer-index_multi_v0.1-theory-stance.md`](gov_theory-pointer-index_multi_v0.1-theory-stance.md)。

---

## 🧭 四支柱速览 / Four pillars at a glance

| 支柱 | 立场一句话 | 译文入口 |
|---|---|---|
| 身份 Identity（AI Passport） | 每个 AI / agent / skill 携带可溯源身份码 | `theory/THEORY.md` 第一节 |
| 溯源 Traceability（XCGS） | 治理不是 PPT，而是可审计证据链 | `theory/THEORY.md` 第二节 |
| 治理 Governance（A³ Law） | AI 造 AI 须过三道门 | `theory/THEORY.md` 第三节 |
| 共生 Symbiosis（Coinhabitation） | 共生而非替代，不让任何人掉队 | `theory/THEORY.md` 第四节 |

引用本理论包时，请按 [`gov_attribution-spec_v0.1-theory-stance.md`](gov_attribution-spec_v0.1-theory-stance.md) 标注包名、版本 `v0.1-theory-stance` 与主指纹 `FP-MX-836A60CCF23F`。

---

## License / 许可

本仓库以 **MIT** 许可证发布，全文见根目录 [`LICENSE`](LICENSE)。Copyright (c) 2026 SynomosAI。原 README 头部的版权行（「© 2026 SynomosAI · MIT」）逐字保留。

---

## 🔒 安全 / Security

如发现安全问题，请按 [`SECURITY.md`](SECURITY.md) 私下报告。

## 🤝 贡献 / Contributing

理论正文翻译改动请走 PR；修改译文须保持主指纹与版本号一致，并同步更新指针索引。
