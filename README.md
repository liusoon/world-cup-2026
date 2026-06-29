---
## 文件：`README.md`

```md
# work-cup-2026

一个用于 2026 世界杯球队分析的 Skill 仓库。

## 功能

- 分析指定球队状态
- 结合小组赛排名、赛程、球员状态与淘汰赛对阵进行综合判断
- 输出教练组视角与第三方评论员视角的比赛分析报告

## 仓库结构

- `SKILL.md`：技能定义文件
- `knowledge/32-data.md`：32 强对阵信息
- `knowledge/32-rule.md`：第一名/第二名出线分析逻辑
- `knowledge/group-rank.md`：小组赛排名获取规则
- `knowledge/group-schedule.md`：小组赛赛程获取规则
- `knowledge/player-status.md`：球员状态获取规则
- `knowledge/rules.md`：世界杯规则
- `knowledge/team-data.md`：球队信息获取规则

## 使用说明

该仓库适合作为 Skill 仓库导入支持 `SKILL.md` 的 AI Agent 平台。  
导入后，Agent 将根据仓库中的规则、数据路径和知识文件，对指定球队进行分析并输出结构化报告。
