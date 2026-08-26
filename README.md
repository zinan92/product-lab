<div align="center">

# Product Lab

**Product Lab 的 capability-first registry：按子分类浏览 owned 与 starred repo。**

[![Snapshot](https://img.shields.io/badge/snapshot-20%20repos-0969DA.svg)](snapshot.yaml)
[![Source](https://img.shields.io/badge/source-Park%20OS-8250DF.svg)](https://github.com/zinan92/park-operating-system)

</div>

---

```text
in  canonical Park OS snapshot + source provenance + fixed commit locks
out 20-repo Product Lab map, grouped by function and owned/starred source

fail snapshot checksum mismatch → stop before publishing
fail private source inaccessible → preserve name/link and mark PRIVATE
fail unclassified placement → keep needs_review; do not guess
```

Snapshot: `github-universe-2026-08-27-taxonomy-01` · canonical source: [Park OS](https://github.com/zinan92/park-operating-system)

## How to read this page

- **Owned** — repo owned by Park.
- **Starred** — external repo selected as a locked reference.
- **Lock** — external source is pinned to a commit SHA, not a live branch.
- **PRIVATE / ARCHIVED** — GitHub visibility or lifecycle flags are preserved.

## Browse by function

### Mysticism / 命理 Products (10)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [6tail/tyme4ts](https://github.com/6tail/tyme4ts) | Tyme是一个非常强大的日历工具库，可以看作 Lunar 的升级版，拥有更优的设计和扩展性，支持公历、农历、藏历、回历、星座、干支、生肖、节气、月相、法定假日等。 | Starred | `9e776099e164` |
| [Brhiza/mingyu](https://github.com/Brhiza/mingyu) | 八字、紫微、星盘、六爻、梅花、奇门、大六壬、小六壬、塔罗、雷诺曼、灵签、择日一站式玄学算命占卜工具包，输出结构化提示词与数据。提供公开 API、MCP Server 与 skill。 | Starred | `1272aa0cd83a` |
| [curionox/lifekline](https://github.com/curionox/lifekline) | 人生K线 - 基于AI的八字命理可视化工具 | Starred | `b9a27a71260a` |
| [DestinyLinker/MingLi-Bench](https://github.com/DestinyLinker/MingLi-Bench) | A benchmark for evaluating LLMs on Chinese traditional fortune telling — Bazi (八字) and Ziwei Doushu (紫微斗数). | Starred | `b7433280fd86` |
| [learnwithu/mingli-master](https://github.com/learnwithu/mingli-master) | 紫微斗数命盘解读 skill · 基于 iztro-py 精确排盘，生成可视化命盘 HTML | Starred | `000da99552cd` |
| [Ming-H/yinyuan-skills](https://github.com/Ming-H/yinyuan-skills) | yinyuan-skills | Starred | `b091c8861a14` |
| [miounet11/life-kline](https://github.com/miounet11/life-kline) | 🌟 人生K线 - 基于 AI 大模型 + 传统八字命理的人生运势可视化工具。将命运绘制成 K 线图，像看股票一样看人生！支持自托管部署。 | Starred | `7abf184df370` |
| [Renhuai123/ziwei-doushu](https://github.com/Renhuai123/ziwei-doushu) | 紫微斗数开源排盘引擎 — 基于倪海夏《天纪》体系，含完整排盘算法、四化系统、格局知识库、古籍原文数据 | Starred | `88194a404242` |
| [SylarLong/iztro](https://github.com/SylarLong/iztro) | ⭐This is a lightweight kit for generating astrolabes for Zi Wei Dou Shu (The Purple Star Astrology), an ancient Chinese astrology. It allows you to obtain your horoscope and personality analysis. 支持多语言轻量级获取紫微斗数排盘信息的javascript开源库。 | Starred | `814b77e6371e` |
| [zinan92/life-kline](https://github.com/zinan92/life-kline) | No description | Owned | owned source · PRIVATE |

### WeChat Chat Analysis (2)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [afumu/wetrace-skill](https://github.com/afumu/wetrace-skill) | 微信聊天记录skill | Starred | `6280e9c106a2` |
| [zinan92/wechat-customer-pipeline](https://github.com/zinan92/wechat-customer-pipeline) | 把授权的本机微信数据库转成私有客户管道与关系行动快照。in WeChat 数据 + 迁移确认 → out HTML + CSV + A/B/C/D + actions + receipts | Owned | owned source · PRIVATE |

### Codex Harness (3)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [zinan92/codex-harness](https://github.com/zinan92/codex-harness) | 本地记录 Codex thread 的 token 使用与项目归属。in Codex session JSONL → out daily thread ledger + read-only HTML UI | Owned + Starred | owned source |
| [zinan92/tokenpulse](https://github.com/zinan92/tokenpulse) | 把 Claude/Codex 本地 token 日志变成桌面鞭策 widget、Telegram 推送、CLI 状态和可分享 QR 战绩卡。in 本地日志 + models.dev → out goad widget + share card | Owned | owned source · ARCHIVED |
| [zinan92/tokenrouter](https://github.com/zinan92/tokenrouter) | 个人项目组合工作台：双通道成本账本 + TokenRouter v0 级联内核 | Owned | owned source · ARCHIVED |

### E-commerce / Product Media (2)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [Usagi-org/ai-goofish-monitor](https://github.com/Usagi-org/ai-goofish-monitor) | 基于 Playwright 和AI实现的闲鱼多任务实时/定时监控与智能分析系统，配备了功能完善的后台管理UI。帮助用户从闲鱼海量商品中，找到心仪产品。 | Starred | `f85d140b6b45` · ARCHIVED |
| [zinan92/paileggemai](https://github.com/zinan92/paileggemai) | 电商商品图生成短视频工作台 | Owned | owned source · PRIVATE |

### Knowledge Planet / Knowledge Products (3)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [helloianneo/obsidian-ai-second-brain](https://github.com/helloianneo/obsidian-ai-second-brain) | Obsidian + Claude AI 个人知识库完整搭建指南 \| 基于 Karpathy LLM Wiki 方法论 \| 4 阶段 12 步 \| 不用写代码 | Starred | `fb3468a1d5fa` |
| [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click | Starred | `1b4a168175e8` |
| [zinan92/wechat-xingqiu](https://github.com/zinan92/wechat-xingqiu) | wechat-xingqiu：原生微信会员内容小程序 | Owned | owned source · PRIVATE |

## Update contract

This README and the generated data are scoped views. Taxonomy, source state and lock authority remain in Park OS.

```bash
bash scripts/verify-scoped.sh
```

The registry is a catalog, not a production-readiness or execution-authorization claim.
