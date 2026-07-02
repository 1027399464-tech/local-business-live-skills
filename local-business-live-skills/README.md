# 本地生活商家直播技能包 (Local Business Live Skills)

从实战经验中蒸馏的 Hermes AI Skills，覆盖**本地生活商家直播全链路**：线上获客 → 开播运营 → 播后复盘。

## 包含的 Skills

| Skill | 覆盖范围 | 适用场景 |
|-------|---------|---------|
| **local-business-live-cycle** | 获客→开播→复盘全流程 | 给商家做完整方案 |
| **live-review-six-steps** | 六部曲复盘方法论 | 每场播后复盘 |
| **cangjie-distill-workflow** | 内容蒸馏方法论 | 把新内容变成skill |

### 1. local-business-live-cycle
本地生活商家从线上获客到开播到复盘的全流程方法论。

**四章结构：**
- 第一章：线上获客 — 532内容配比、说人话文案5条铁律、出圈选题模板
- 第二章：开播 — 冷启动策略、医生坐诊模式、望闻问切连线筛客、AB分诊
- 第三章：复盘 — 六部曲完整流程、关键指标速查表、复盘填空模板
- 第四章：三频协同 — 健康流量结构参考、协同检查清单

### 2. live-review-six-steps
直播复盘六部曲：数据→节奏→商品→人群→短视频→流量结构，每步有合格线+问题定位+责任归属+优化方向。

### 3. cangjie-distill-workflow
把书籍、视频、播客、直播复盘等高质量内容蒸馏成可执行Skills的方法论。受 [cangjie-skill](https://github.com/kangarooking/cangjie-skill) 的 RIA-TV++ 方法论启发。

## 安装

### 方式一：Hermes 直接安装

```bash
# 克隆仓库
git clone https://github.com/你的用户名/local-business-live-skills.git ~/.hermes/skills/
```

### 方式二：手动安装

将 skill 目录复制到 `~/.hermes/skills/consulting/` 下即可。

## 使用

在 Hermes Agent 中，直接说：

- "帮我写个餐饮商家脚本" → 调用 local-business-live-cycle
- "帮我复盘一下今天的数据" → 调用 live-review-six-steps
- "把这篇文章蒸馏成skill" → 调用 cangjie-distill-workflow

## 作者

李鑫（李老师）— 本地生活商家内容咨询顾问

## License

MIT
