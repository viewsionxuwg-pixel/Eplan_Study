---
title: EPLAN学习环境
type: environment
tags:
  - EPLAN
  - 学习环境
eplan_version: 2025
eplan_internal_version: 23406
interface_language: Chinese (Simplified)
license_model: Concurrent License
status: active
verification: 用户提供 EPLAN 实机截图；产品、内部版本、界面语言和截图可见许可证范围已核对
created: 2026-07-19
updated: 2026-07-22
source: 用户确认、EPLAN 实机产品页与 Licensed add-ons 页面、当前工作区环境
source_version: 2025
---

# EPLAN 学习环境

## 已确认

- EPLAN 2025 安装在 VMware 虚拟机中。
- 产品为 `EPLAN Electric P8 Professional (64 位)`。
- 产品页显示版本 `2025`、内部版本号 `23406`；本次证据没有显示单独的 Update 名称或编号。
- Vault 中已有项目元数据把构件号 `23406` 与版本 `2025.0.3` 成对记录；结合 EPLAN 官方 API 帮助的 `Version 2025.0.3` 标识，可高可信度推定当前为 `2025.0.3 / Update 3`，但仍需用 Download Manager 或官方支持信息最终确认。
- 当前对话框语言为 `Chinese (Simplified)`（简体中文）。
- 许可证模式为 `Concurrent License`（并发许可）。
- 本轮 Obsidian Vault 工作区位于宿主机 `E:/Eplan_Study`。
- 宿主机安装检测不到 EPLAN 属于预期情况，后续环境核对需要在虚拟机内完成。

## 许可证范围（2026-07-22 实机截图）

下列结论来自 `文件 → 帮助 → 信息 → Licensed add-ons`。勾选表示本次截图中显示为已许可；这里只记录与学习规划有关的能力，不保存许可证序列号。

### 初学阶段直接相关

- 电气设计与项目：`EPLAN Electric P8 (Add-on)`、`EPLAN Graphical Reports`、`EPLAN PLC & BUS Extension`、`EPLAN Operational Sequence`、`EPLAN Single Line`。
- 项目治理：`EPLAN Project Processing`、`EPLAN Project Reference`、`EPLAN Project management`、`EPLAN Project options`、`EPLAN Revision Management`、`EPLAN User Rights Management`。
- 部件与交换：`EPLAN Data Portal`、`EPLAN ECLASS Import`、`EPLAN EDZ Format`、`EPLAN ERP/PDM Integration Suite`。
- 协作与语言：`EPLAN Comments`、`EPLAN Multiuser Management`、`EPLAN Multiuser Monitor`、`EPLAN Multi Language Translation`；已许可语言中包含 `EPLAN Language Chinese Simplified`。

### 后续阶段可用

- 自动化与接口：`EEC - Scripting Extensions`、`EPLAN API Extension`、`EPLAN API Extension Partsmanagement`、`EPLAN Batch Server`、`EPLAN Cogineer Builder`、`EPLAN Cogineer Designer`、`EPLAN Autodesk Vault Interface`。
- 其他专业：`EPLAN FieldSys`、`EPLAN Fluid (Add-on)`、`EPLAN Fluid Hose Configurator (Add-on)`、`EPLAN Harness proD Extensions`、`EPLAN Preplanning P&ID (Add-on)`、`EPLAN Preplanning Professional (Add-on)`。
- 3D 与制造：`EPLAN Pro Panel (Add-on)`、`EPLAN Pro Panel Professional`、`EPLAN Mounting Panel`、`EPLAN Net Based Wiring`，以及截图中已勾选的 Pro Panel 交换、工艺和生产接口。

### 截图中明确未勾选

- `EPLAN Data Portal Professional`
- `EPLAN Fluid Compact (Add-on)`
- `EPLAN Pro Panel Production Wiring Wus-Tec`
- `EPLAN Productstream Interface`

> [!note] 解释边界
> 许可证清单说明软件许可可用范围，不代表每个功能都已配置、已掌握或适合当前项目。学习主线仍以 Electric P8 为先，API、Cogineer、Preplanning、Fluid 和 Pro Panel 后置。

## 待确认

- [ ] 通过 EPLAN Download Manager、安装包或官方支持信息确认 `23406` 对应的明确 Update 名称/编号；在取得证据前只记录“内部版本号 23406”
- [ ] 虚拟机操作系统版本
- [ ] EPLAN 示例项目、基本项目和主数据位置
- [ ] 宿主机与虚拟机之间用于传递截图、PDF 和练习项目归档的目录
- [ ] 虚拟机快照或其他可恢复点已建立

## 核验依据

- EPLAN 产品页实机截图：2026-07-22 核对；因包含序列号，原图未复制到 Vault、未纳入 Git。
- EPLAN `Licensed add-ons` 实机截图：2026-07-22 核对；只把脱敏后的文字结论写入 Vault。
- [[01_Inbox/待整理资料/外部EPLAN案例库_盘点|外部 EPLAN 案例库盘点]]：本机 `ProjectInfo.xml` 元数据记录 `2025.0.3` 与构件号 `23406`，仅作为版本映射的交叉证据。
- [EPLAN Platform 2025：产品版本和内部版本号位置](https://www.eplan.help/en-us/Infoportal/Content/Plattform/2025/Content/htm/prjmanagementgui_r_status.htm)
- [EPLAN API 2025 官方帮助：Version 2025.0.3](https://www.eplan.help/en-us/Infoportal/Content/api/2025/index.html)
- [EPLAN Platform 2025：Licensed add-ons 与许可范围说明](https://www.eplan.help/en-us/Infoportal/Content/Plattform/2025/Content/htm/license_k_start.htm)

## 使用边界

- 外部旧项目只复制到虚拟机隔离练习目录后打开，不直接操作原件。
- 版本转换、项目升级或数据库更新只能对副本执行。
- Vault 和 GitHub 只保存允许共享的 Markdown、索引、小型配置和脱敏结果。
- 许可证信息、虚拟机磁盘、客户工程和来源不明的 EPLAN 主数据不得提交。

相关入口：[[00_Home/EPLAN学习主页|EPLAN 学习主页]] · [[00_Home/学习进度看板|学习进度看板]] · [[60_案例工程/案例工程_MOC|案例工程 MOC]]
