<p align="center"><img src="banner.svg" alt="PaperKit：从研究材料到论文初稿" width="100%"></p>

<p align="center"><strong>让已有的研究，逐步成为可以审阅、修改的论文初稿。</strong></p>
<p align="center">Windows 本地工作台 · MCP 连接 · 作者逐阶段确认</p>
<p align="center"><a href="https://github.com/WangJ226/PaperKit/releases/latest"><strong>下载 PaperKit</strong></a> · <a href="GETTING_STARTED.md">首次使用</a> · <a href="FAQ.md">常见问题</a> · <a href="https://github.com/WangJ226/PaperKit/issues">反馈问题</a></p>

---

## 已有数据、结果和文献，接下来怎样写成论文？

研究材料散落在文件夹中，图表和论点还没对齐，AI 对话又容易遗漏前面的决定。PaperKit 把这些工作组织成可检查的论文流程：

**配合你自己的 AI 助手，从真实研究材料出发，讨论论文主线、图表安排和引用，按阶段推进成可供作者审阅、修改的初稿。**

你负责研究判断和关键确认；PaperKit 组织本地流程与成果；WorkBuddy、Codex 或 Claude Desktop 负责 AI 对话与模型调用。

| 研究中的任务 | PaperKit 如何协助 |
|---|---|
| 材料很多，主线还不清楚 | 整理权威输入、事实、假设和缺口，与作者明确论文方向 |
| 图表、结果和主张尚未对应 | 按阶段讨论证据需求、图表安排和论证关系 |
| 文献读过了，引用容易混乱 | 登记、深读并核验参考材料，组织引用与主张的对应 |
| 多轮对话之后不知道进展 | 本地记录阶段状态与成果，工作台每5秒自动刷新 |
| 需要一份可继续修改的初稿 | 配合AI逐步完成写作与Word导出，保留作者审阅节点 |

> 初稿质量取决于材料完整度、AI能力与作者参与。研究事实、引用准确性及最终内容由作者审阅确认。

## 用一个小任务开始

**01 下载并安装 → 02 连接自己的 AI 助手 → 03 选择项目副本 → 04 开始第一个阶段**

1. 在 [Releases](https://github.com/WangJ226/PaperKit/releases/latest) 下载 **PaperKit-0.3.20-Setup.exe**。普通用户选安装包即可。
2. 打开软件，填写联系邮箱并免费开始；有授权码时进入“授权与购买”兑换。
3. 在阶段页面选择 WorkBuddy、Codex 或 Claude Desktop，按提示配置并重启AI客户端。
4. 将阶段提示词发送给AI，请它实际调用 `project_status`，确认连接后从自己的材料开始。

完整步骤见 [首次使用指南](GETTING_STARTED.md)。AI账号及Token费用由使用者自行承担。

## 免费开始，按需要开通完整流程

| 权益 | 范围 |
|---|---|
| 免费体验 | Stage 00–03，可反复体验；一台设备一个项目，每项目5篇核心文献 |
| 90天完整体验 | 持邀请者发放的体验码；新码90天内领取，首次成功兑换后完整使用90天，绑定一台电脑 |
| 个人买断 · 500元 | 当前大版本永久个人使用权，绑定一台电脑；完整Stage 00–12 |

在软件“授权与购买”中可前往链动小铺购买，也可以兑换提供方直接发放的授权码。设备租约与永久使用权益分别展示，首次激活及后续租约刷新需要联网。

购买前可先用免费阶段验证是否适合自己的研究任务。个人授权与软件源码授权分别管理；第三方组件按随包许可证提供。

## 本地材料，清楚的使用边界

- 论文项目、原始数据和阶段材料保存在你的电脑；PaperKit授权服务处理账号、设备与权益信息。
- 你交给AI助手的内容按相应AI平台的数据政策处理，使用前核对敏感材料的分享范围。
- 支持Windows 10/11 64位。运行环境随软件提供，无需自行安装Python、Git、Node或Docker。
- Word相关功能请准备兼容的Microsoft Word；复杂图表和格式需要作者审阅。
- 当前安装包尚未完成Authenticode代码签名，Windows可能提示未知发布者。请核对下载来源及同版SHA-256，保留系统安全防护。

## 当前版本：0.3.20

本轮已完成客户端188项、服务器78项自动回归，以及本机实际联网兑换、冻结EXE的MCP调用、中文路径启动、Word导出、安装升级、回滚与卸载保护测试。

不同电脑及三个AI客户端的真实使用情况正在持续收集。上述测试范围与真实客户验收分别记录，复杂论文与实际付款链路继续以现场结果为准。

更新内容见 [CHANGELOG](CHANGELOG.md)。Releases提供安装包、便携包与SHA-256校验文件；后续版本也在同一入口发布。

## 帮助 PaperKit 变得更好

欢迎用一个真实的小任务体验。遇到问题可在 [Issues](https://github.com/WangJ226/PaperKit/issues) 描述步骤，或使用软件中的“反馈问题与经验”：复制提示词交给AI，让它总结反馈文件，检查脱敏后提交。

**公开反馈请保留软件版本、操作步骤和错误提示，隐藏论文正文、授权码、邮箱、Token与个人路径。** 涉及授权码或设备恢复，请通过软件内提供方联系方式私下联系。

如果这项工作对你有帮助，欢迎 Star，或把这个页面分享给正在整理研究材料、推进论文的朋友。

---

**English overview** — PaperKit is a Windows research workflow workbench connected to your own AI assistant via MCP. It helps organize research materials, discuss the manuscript narrative, plan figures and references, and progress toward an author-reviewed first draft. This repository hosts product documentation and downloadable releases; the application source remains privately maintained. AI accounts and usage fees are supplied by the user.
