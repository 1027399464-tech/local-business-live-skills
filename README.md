# 本地生活商家直播技能包 (Local Business Live Skills)

从实战经验中蒸馏的直播方法论，覆盖**本地生活商家直播全链路**：进店诊断 → 开播获客 → 复盘迭代。

> ⚠️ 本仓库内容经历了两轮迭代：v1.0 混杂了多位外部作者的方法论未标注来源，v1.1 已替换为李鑫真实实战内容（基于某奶站门店诊断案例），并对剩余外部框架明确标注「框架参考」及来源。欢迎 PR 补充更多实战案例。

---

## 两种用法

### 用法一：没有 AI Agent → 当手册看

每个 skill 目录里都有两种文件：

| 文件 | 适合谁 | 怎么用 |
|------|--------|--------|
| **SKILL.md** | AI Agent 使用者 | 喂给 AI，自动输出结构化方法论 |
| **CHECKLIST.md / QUICK_REFERENCE.md** | 任何人 | 打印出来，直接照着干 |

比如直接打开 `live-review-six-steps/CHECKLIST.md`，就是一份**播后填空模板**，下播了照着填。

### 用法二：有 Hermes / Claude Code / Codex → 当技能装

#### Hermes
```bash
git clone https://github.com/你的用户名/local-business-live-skills.git ~/.hermes/skills/
```
装好后直接说：
- "帮我复盘一下今天的数据"
- "帮我写个餐饮商家脚本"

#### Claude Code / Codex
把对应的 SKILL.md 复制到你的项目目录，在 CLAUDE.md 里引用：
```
你是一个直播运营专家。当用户需要复盘时，参考 live-review-six-steps/SKILL.md 中的方法论。
```

---

## 包含的 Skills

| Skill | 覆盖范围 | 人也能读的版本 |
|-------|---------|--------------|
| **local-business-live-cycle** | 获客→开播→复盘全流程 | `QUICK_REFERENCE.md`（1页速查卡） |
| **live-review-six-steps** | 六部曲复盘方法论 | `CHECKLIST.md`（播后填空模板） |
| **cangjie-distill-workflow** | 内容蒸馏方法论 | 直接看 SKILL.md |

### 4. external/ — 外部补充技能包

来自 [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh)（⭐16,630）的 11 个营销类 agent skill，按补位关系整理：

| 外部 Skill | 长度 | 补什么 | 关联内部章节 |
|-----------|------|--------|------------|
| **douyin-strategist** | 5.7KB | 算法机制/内容矩阵/DOU+投放策略 | live-cycle 第一章·付费引流 |
| **livestream-commerce-coach** | 14.5KB | 主播训练/五段话术/选品排品/付费+自然流协同 | live-cycle 第二章·话术 |
| **short-video-editing-coach** | 27KB | 拍摄制作指导（灯光/剪辑/分镜/特效） | live-cycle 第一章·制作 |
| **video-optimization-specialist** | 5.3KB | 视频完播率优化/画面诊断 | live-cycle 第一章·优化 |
| **private-domain-operator** | 13.6KB | 微信私域运营体系 | — |
| **knowledge-commerce-strategist** | 17KB | 知识付费/课程产品设计 | — |
| **xiaohongshu-operator** | 5.5KB | 小红书运营 | — |
| **kuaishou-strategist** | 8.1KB | 快手运营 | — |
| **content-creator** | 5.4KB | 通用内容创作方法论 | — |
| **china-ecommerce-operator** | 13KB | 淘宝/拼多多/京东电商运营 | — |
| **entity-copywriter** | 30KB | 实体商家脚本生成器（Hook公式库+采访流程） | live-cycle 第一章·脚本 |

> 在 Hermes 中用 `skill_view(name='external/<文件名>')` 加载具体 skill。

---

### 1. local-business-live-cycle
本地生活商家直播全流程——进店诊断→设计方案→开播获客→复盘迭代。

四章结构：
- 第零章：商家诊断接入流程 — 深度聊→4信号诊断→找关键杠杆→出方案
- 第一章：短视频引流 — 532配比（框架参考）、说人话文案5条铁律（框架参考）、出圈选题模板
- 第二章：开播获客 — 福袋×放单循环（实战方案）
- 第三章：复盘 — 六部曲（框架参考）、关键指标速查表
- 第四章：三频协同 — 健康流量结构参考、协同检查清单

👉 不想看 AI 的，直接打开 `local-business-live-cycle/QUICK_REFERENCE.md`

### 2. live-review-six-steps
直播复盘六部曲：数据→节奏→商品→人群→短视频→流量结构，每步有合格线+问题定位+责任归属+优化方向。

👉 每次播完打开 `live-review-six-steps/CHECKLIST.md` 填空

### 3. cangjie-distill-workflow
把书籍、视频、播客、直播复盘等高质量内容蒸馏成可执行 Skills 的方法论。

受 [cangjie-skill](https://github.com/kangarooking/cangjie-skill) 的 RIA-TV++ 方法论启发。

---

## 作者

李鑫（李老师）— 本地生活商家内容咨询顾问

## License

MIT
