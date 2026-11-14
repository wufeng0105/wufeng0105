<div align="center">

# 吐泡泡 · wufeng0105

**在 DeepSeek Harness（DSH）上做插件。**
把宿主里那些「改不了、看不见、说不清」的地方，做成能装、能验、能退出的东西。

[![DeepSeek Harness](https://img.shields.io/badge/DeepSeek%20Harness-dsh-4B6BFB?style=flat-square)](https://github.com/deepseek-ai/deepseek-harness)
[![Plugins](https://img.shields.io/badge/plugins-9-2ea44f?style=flat-square)](#-活跃项目)
[![Stars](https://img.shields.io/github/stars/wufeng0105/dsh-enhance?style=flat-square&label=stars&color=e3b341)](https://github.com/wufeng0105/dsh-enhance)

</div>

---

## 现在在做什么

主力方向是 **DSH 插件生态**。13 个在维护的仓库里，9 个是 DSH 插件，围绕一条主线：

> 宿主的行为边界在哪、我怎么知道它真的改了、改完能不能退回去。

每个插件都按同一套要求写：能安装、能验证生效、能干净退出。写插件的方法论本身也做成了插件——`dsh-plugin-kit` 里的 `plugin-kit` skill。

## 🔥 精选

<table>
<tr>
<td width="50%" valign="top">

### [dsh-enhance](https://github.com/wufeng0105/dsh-enhance) ★23
换掉 DSH 系统提示开头那句品牌声明，或在末尾常驻一段自己的文本。

模型还是那个模型，变的是它每轮开局读到的东西。带 CI，MIT。

</td>
<td width="50%" valign="top">

### [dsh-tool-keeper](https://github.com/wufeng0105/dsh-tool-keeper)
AI 每回答一次，都要把手上所有工具的说明书重读一遍——包括你从不用的那些。

这个插件让你把用不到的收起来，把留下的说明书改成自己的话。

</td>
</tr>
<tr>
<td valign="top">

### [dsh-plugin-kit](https://github.com/wufeng0105/dsh-plugin-kit)
一个包，两样东西：**契约查证顺序**（skill）+ **完成验证脚本**（首装自检 / 升级复检）。

DSH 的契约全在 208MB 的 `app.asar` 里，离线能跑的代码宿主里可能非法。

</td>
<td valign="top">

### [awesome-dsh-plugin](https://github.com/wufeng0105/awesome-dsh-plugin)
DSH 插件精选列表，同时是 **npm 上的插件市场索引**。

在 DSH 里「插件 → 发现 → 索引源」加上它的 `index.json`，就能直接搜到并安装。

</td>
</tr>
</table>

## 🛠 活跃项目

### DSH 插件与工具

| 项目 | 一句话 |
|---|---|
| [dsh-tool-keeper](https://github.com/wufeng0105/dsh-tool-keeper) | 收起用不到的工具说明书，重写留下的那些 |
| [dsh-enhance](https://github.com/wufeng0105/dsh-enhance) | 改写系统提示的开头与结尾 · ★23 |
| [dsh-plugin-kit](https://github.com/wufeng0105/dsh-plugin-kit) | 插件开发的契约查证顺序 + 完成验证脚本 |
| [dsh-draft-studio](https://github.com/wufeng0105/dsh-draft-studio) | 输入框里的半成品草稿，一键变成 AI 能照着干的提示词 · 原地改写、不发送 |
| [dsh-teammate-model-picker](https://github.com/wufeng0105/dsh-teammate-model-picker) | 给子智能体手动换模型——额度用完了换一个继续干，不用重建 |
| [dsh-skills](https://github.com/wufeng0105/dsh-skills) | 三个 DSH 适配的 skill：brainstorming / TDD / verification |
| [dsh-plugin-process-lab-archive](https://github.com/wufeng0105/dsh-plugin-process-lab-archive) | 插件开发流程规格，已并入 `dsh-plugin-kit`，仅留档 |

### 跨工具

| 项目 | 一句话 |
|---|---|
| [zcode-rules-plugin](https://github.com/wufeng0105/zcode-rules-plugin) | 写一次规则两处生效：既决定 ZCode 里哪条命令能跑，又投影成 `AGENTS.md` 的行为提示 |
| [workbuddy-console](https://github.com/wufeng0105/workbuddy-console) | WorkBuddy 宿主配置管理器：改之前告诉你代价，改完证明它真生效 |
| [zhll](https://github.com/wufeng0105/zhll) | 跨会话工程指挥法：Lead 派子智能体分批干活、独立复核、产物落盘 |
| [inkreckon](https://github.com/wufeng0105/inkreckon) | 手写中文采购清单照片 → 可导入内蒙古电子税务局的 XLSX |

## 🧰 技术栈

<p>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

## 📦 已归档

<details>
<summary><b>47 个历史项目</b>（点击展开）</summary>

> 归档只冻结写入，代码与历史全部保留。需要哪个随时可以解归档。

| 类别 | 项目 |
|---|---|
| **应用产品** | [EcoPasteAI](https://github.com/wufeng0105/EcoPasteAI) · EcoPaste 的 AI 维护线（815 commits）<br>[chinese-poetry-api](https://github.com/wufeng0105/chinese-poetry-api) · 诗泉，高性能古诗词 API<br>[ChinesePoetryApiTs](https://github.com/wufeng0105/ChinesePoetryApiTs) · 诗词前端 + TTS 代理<br>[DouKStudio](https://github.com/wufeng0105/DouKStudio) · 抖音视频 ASR 转写 + LLM 分析管线<br>[TikTokDownloader](https://github.com/wufeng0105/TikTokDownloader) · 抖音 / TikTok 数据采集（v5.8 Beta）<br>[Dictation](https://github.com/wufeng0105/Dictation) · WordPhonetic 英语听写（离线管线 + Supabase + 小程序）<br>[DaoVerse](https://github.com/wufeng0105/DaoVerse) · 网文小说项目<br>[ClauseZero](https://github.com/wufeng0105/ClauseZero) · 网文创作工具链<br>[Miaoxiang](https://github.com/wufeng0105/Miaoxiang) · 音乐生成知识库 / 创作台<br>[PoetryBlog](https://github.com/wufeng0105/PoetryBlog) · 诗词博客<br>[NexusPrime](https://github.com/wufeng0105/NexusPrime) · 小米遥控器 2 Pro 语音按键映射 |
| **开发工具** | [APIChecker](https://github.com/wufeng0105/APIChecker) · API 检查工具（75 commits）<br>[YuqueLake](https://github.com/wufeng0105/YuqueLake) · 语雀 Lake 格式转换工具集<br>[AtlasVault](https://github.com/wufeng0105/AtlasVault) · Obsidian 知识库模板 + Agent 维护工作流<br>[StableLink](https://github.com/wufeng0105/StableLink) · AI 客户端诊断与中转稳定性测试<br>[skills-hub](https://github.com/wufeng0105/skills-hub) · 跨平台 Agent Skill 管理器（Fork）<br>[skills-hub-sync](https://github.com/wufeng0105/skills-hub-sync) · Skill 同步<br>[docs](https://github.com/wufeng0105/docs) · Mintlify 文档站 |
| **小工具** | [FapiaoKit](https://github.com/wufeng0105/FapiaoKit) · 发票处理<br>[IpPool](https://github.com/wufeng0105/IpPool) · IP 代理池<br>[KQuick](https://github.com/wufeng0105/KQuick) · Windows 快捷工具（C#）<br>[ClickLoop](https://github.com/wufeng0105/ClickLoop) · 桌面自动化（C#）<br>[RpaSkills](https://github.com/wufeng0105/RpaSkills) · RPA 技能框架<br>[AligenieMusic](https://github.com/wufeng0105/AligenieMusic) · 天猫精灵音乐台技能<br>[Wan27Image](https://github.com/wufeng0105/Wan27Image) · wan2.7 生图 CLI<br>[FpTools](https://github.com/wufeng0105/FpTools)<br>[lnmkshu](https://github.com/wufeng0105/lnmkshu) |
| **浏览器扩展** | [GitBookmark](https://github.com/wufeng0105/GitBookmark) · GitHub 仓库收藏管理，AI 读 README 生成中文摘要<br>[YuqueMarkdownExporter](https://github.com/wufeng0105/YuqueMarkdownExporter) · 语雀 Markdown 导出<br>[ImpeccableExtension](https://github.com/wufeng0105/ImpeccableExtension) · 前端设计辅助<br>[KimiWebbridgeExtension](https://github.com/wufeng0105/KimiWebbridgeExtension) · Kimi 网页桥接 |
| **DSH 早期版本** | [dsh-superpowers-v7](https://github.com/wufeng0105/dsh-superpowers-v7) · superpowers v7.0.1 的 15 个 skill<br>[dsh-enhance-private](https://github.com/wufeng0105/dsh-enhance-private) · `dsh-enhance` 的私有版<br>[dsh-purge-desktop](https://github.com/wufeng0105/dsh-purge-desktop) · 桌面端改造实验 |
| **知识与笔记** | [AiKnowledge](https://github.com/wufeng0105/AiKnowledge) · 多平台大模型知识库与 OCR 评测<br>[AicodemirrorScraper](https://github.com/wufeng0105/AicodemirrorScraper) · 站点爬虫<br>[SystemPromptCC](https://github.com/wufeng0105/SystemPromptCC) · 系统提示词中文社区 |
| **其他** | [EcoPaste](https://github.com/wufeng0105/EcoPaste) · 上游 Fork（提 PR 用）<br>[ecopaste-ai-build](https://github.com/wufeng0105/ecopaste-ai-build) · EcoPasteAI 构建仓<br>[GoalRun](https://github.com/wufeng0105/GoalRun) · [Route](https://github.com/wufeng0105/Route) · [cli-setup-helper](https://github.com/wufeng0105/cli-setup-helper) · [PreDevPack](https://github.com/wufeng0105/PreDevPack) · [DocRegime-native](https://github.com/wufeng0105/DocRegime-native) · [codex-governance-method](https://github.com/wufeng0105/codex-governance-method) · [chatgptwebruntime](https://github.com/wufeng0105/chatgptwebruntime) · [ChatGPT-GitHub-Operator](https://github.com/wufeng0105/ChatGPT-GitHub-Operator) |

</details>

---

<div align="center">
<sub>活跃 13 · 归档 47 · 最近整理 2026-11</sub>
</div>
