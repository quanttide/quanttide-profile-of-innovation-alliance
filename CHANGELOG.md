# 更新日志

本文档记录项目所有重要变更。格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

## [Unreleased]

### 变更

- 对齐《招聘考核课题立项评审章程》（`docs/bylaw/qtrecurit/proposal.md`）：《人才孵化器》与产品路线图清除章程禁止的措辞（降本增效、AI 辅助、无指标的「优化」），改为可核算/可检查的表述；选题制考核条目挂上章程指针；CLI 补边界注记（批量与统计属工程目标，不构成课题立项方向依据）

### 移除

- 《人才孵化器》生长路径移除准入问卷条目：问卷流程废弃，投递后直接进群，筛选全部发生在选题制考核内部
- 《组织》移交实训基地第二大脑：`qtacademy/org.md` 移入 `quanttide-profile-of-training-base` 的 `default/org.md`，本仓不再保留。

### 新增

- 初始化仓库。
- 新增《组织》（`qtacademy/org.md`）：如何构建组织（选人与留人），以及主动报名、提名、投票的选人流程。

### 变更

- 《人力资源》并入《组织》：选人与留人下沉为《组织》的子节，不再单独成档。
- 《组织》选人流程补充可执行口径：问卷信息项、证据收集、评价顺序、筛选评分与通过标准。
- 档案来源：实训基地日志 2026-10-21。
- 迁入 qtrecurit 招聘政策档案（自 qtadmin CLI 数据目录）：policy.yaml、recruitment_policies.yaml、policy_summary.md，已脱敏（人名改写为秘书处/一次离职事件）
- 新增 strategy/open-vs-close.md：开源与闭源的战略判定（两步判定、三种形态、不对称的账、意图边界、转速表）
- 新增 strategy/acquisition.md：获客战略（判定标准、三条路径线索、与开源底料的关系）
- 新增 strategy/talent-incubator.md：人才孵化器（贡献抵消的账、生长路径、合同与贡献抵消两层确权、放弃直接招聘、招聘即撞墙体验）
