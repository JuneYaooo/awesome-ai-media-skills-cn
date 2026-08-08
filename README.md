# Awesome AI Media Skills 中文版 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> AI 视频与自媒体领域的 Claude Code 技能、MCP 服务器、AI Agent 能力精选合集 — 涵盖视频生成、多平台运营、内容自动化等。

[English](https://github.com/JuneYaooo/awesome-ai-media-skills) | [中文](README.md)

![Stars](https://img.shields.io/github/stars/JuneYaooo/awesome-ai-media-skills-cn?style=social)
![Last Commit](https://img.shields.io/github/last-commit/JuneYaooo/awesome-ai-media-skills-cn)
![License](https://img.shields.io/badge/license-CC0--1.0-blue)

## 目录

- [视频生成技能](#视频生成技能)
- [社媒运营 MCP 服务器](#社媒运营-mcp-服务器)
- [内容创作技能](#内容创作技能)
- [视频处理技能](#视频处理技能)

---

## 视频生成技能

| 技能 | 平台 | 可用性 | Stars | 说明 |
|------|------|--------|-------|------|
| [Generative-Media-Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) | Claude Code / MCP | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/SamurAIGPT/Generative-Media-Skills?style=flat-square) | 面向 AI Agent 的多模态创作技能库，封装 muapi-cli，可调用 100+ 图像、视频、音频模型，并支持通过 MCP 暴露为工具。 |
| [Ultimate-AI-Media-Generator-Skill](https://github.com/ZeroLu/Ultimate-AI-Media-Generator-Skill) | Claude Code / OpenClaw / Codex | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/ZeroLu/Ultimate-AI-Media-Generator-Skill?style=flat-square) | 开源 AI 图片/视频生成 Skill，适配多平台 agent，内置工作流模板与提示词优化，但需配置 CyberBara API 与模型额度。 |
| [MiniMax-MCP](https://github.com/MiniMax-AI/MiniMax-MCP) | MCP Server | ✅ 直接可用 | ![](https://img.shields.io/github/stars/MiniMax-AI/MiniMax-MCP?style=flat-square) | MiniMax 官方 MCP 服务器，提供语音、图片、视频生成能力，附示例配置、测试和 Python 打包脚本。 |
| [jimeng-mcp-server](https://github.com/wwwzhouhui/jimeng-mcp-server) | MCP Server / Skill | ✅ 直接可用 | ![](https://img.shields.io/github/stars/wwwzhouhui/jimeng-mcp-server?style=flat-square) | 即梦 AI MCP 服务器，让 Claude、Cherry Studio 等 AI 应用直接调用即梦的 AI 视频/图片生成能力。 |
| [OnlyShot](https://github.com/A-cat-with-carrots/OnlyShot) | Claude Code | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/A-cat-with-carrots/OnlyShot?style=flat-square) | AI 短剧工业流水线 Claude Skill — 一句话生成剧本/分镜/分镜图/视频/剪辑五步完成，可产出发布到抖音红果的完整短剧。 |
| [capsule-cinema](https://github.com/JuneYaooo/capsule-cinema) | Claude Code / Codex / OpenClaw | ✅ 直接可用 | ![](https://img.shields.io/github/stars/JuneYaooo/capsule-cinema?style=flat-square) | 可复用的 AI 视频生产配方集 — 分镜设计、视频生成、剪辑、字幕和质检的 Agent 工作流模板，支持 Codex / Claude Code / OpenClaw 等多平台。 |

## 社媒运营 MCP 服务器

| 技能 | 平台 | 可用性 | Stars | 说明 |
|------|------|--------|-------|------|
| [Postiz CLI](https://github.com/gitroomhq/postiz-agent) | Agent CLI / API | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/gitroomhq/postiz-agent?style=flat-square) | 面向 AI Agent 的社媒自动化 CLI，可连接 Postiz 执行排期、媒体上传和跨 28+ 平台发布；需自建服务并配置各平台凭证。 |
| [Douyin Upload MCP Skill](https://github.com/WJZ-P/douyin-upload-mcp-skill) | MCP Server / Skill | ✅ 直接可用 | ![](https://img.shields.io/github/stars/WJZ-P/douyin-upload-mcp-skill?style=flat-square) | 基于 CDP 的抖音创作者平台自动发布 MCP，支持视频/图文发布、扫码登录、短信校验、截图探测和浏览器托管，可被 OpenClaw 或任意 MCP 客户端调用。 |
| [ShortVideo.AutoPublisher](https://github.com/dorisoy/ShortVideo.AutoPublisher) | — | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/dorisoy/ShortVideo.AutoPublisher?style=flat-square) | ShortVideo.AutoPublisher 是套实现，抖音，百家号，小红书，视频号，头条，等平台短视频自动发布的创作者工具。 |
| [xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) | MCP Server | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/xpzouying/xiaohongshu-mcp?style=flat-square) | MCP for xiaohongshu.com |
| [xhs-mcp](https://github.com/Algovate/xhs-mcp) | MCP Server / CLI | ✅ 直接可用 | ![](https://img.shields.io/github/stars/Algovate/xhs-mcp?style=flat-square) | 小红书 MCP 服务器与 CLI 工具，支持登录、发布、搜索、推荐等自动化操作。 |
| [douyin-mcp-server](https://github.com/lancelin111/douyin-mcp-server) | MCP Server | ✅ 直接可用 | ![](https://img.shields.io/github/stars/lancelin111/douyin-mcp-server?style=flat-square) | 抖音 MCP 服务器 — 通过 Model Context Protocol 实现视频自动上传与管理。 |
| [turbopush-mcp](https://github.com/xueyc1f/turbopush-mcp) | MCP Server | ✅ 直接可用 | ![](https://img.shields.io/github/stars/xueyc1f/turbopush-mcp?style=flat-square) | 多平台内容发布 MCP 服务器，打通 AI Agent 与抖音/小红书/B站/视频号等平台的内容分发通道。 |
| [xiaohongshu-mcp-python](https://github.com/luyike221/xiaohongshu-mcp-python) | MCP Server | ✅ 直接可用 | ![](https://img.shields.io/github/stars/luyike221/xiaohongshu-mcp-python?style=flat-square) | 小红书内容自动化发布 MCP Server，支持图文/视频发布、笔记管理、数据分析、定时发布，为 AI 客户端提供完整的小红书运营能力。 |
| [yutu](https://github.com/eat-pray-ai/yutu) | Claude Code | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/eat-pray-ai/yutu?style=flat-square) | YouTube 频道自动驾驶 AI 工具包 — 自动选题、脚本生成、视频制作、SEO 优化、数据分析，一站式 YouTube 运营。 |
| [chubbyskills](https://github.com/chubbyguan/chubbyskills) | Claude Code | ✅ 直接可用 | ![](https://img.shields.io/github/stars/chubbyguan/chubbyskills?style=flat-square) | 中文内容摄入 Skill — 将抖音/B站/小红书/微信公众号/X/播客等内容一键转为个人知识库。支持本地 LLM，数据不出境。 |
| [bilibili-mcp](https://github.com/XZXZZX-Ai/bilibili-mcp) | MCP Server | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/XZXZZX-Ai/bilibili-mcp?style=flat-square) | Bilibili MCP工具(获取视频字幕和评论)                  A Bilibili MCP server for retrieving video subtitles and comments. |

## 内容创作技能

| 技能 | 平台 | 可用性 | Stars | 说明 |
|------|------|--------|-------|------|
| [社媒营销技能集 (linkedin-skills)](https://github.com/sergebulaev/linkedin-skills) | Claude Code / Codex | ✅ 直接可用 | ![](https://img.shields.io/github/stars/sergebulaev/linkedin-skills?style=flat-square) | LinkedIn/X/TikTok/Threads/Instagram/Facebook/YouTube 七大平台开源社媒营销技能集 — 爆款 hook 公式写作、评论/回复起草、AI 味去除（humanizer）、语气品牌画像，Apify 读取 + Publora 发布一键排期。 |
| [content-pipeline](https://github.com/OrangeViolin/content-pipeline) | Claude Code | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/OrangeViolin/content-pipeline?style=flat-square) | 面向创作者的 Claude Code Skill，覆盖选题调研、写稿、排版、封面、配图、多平台改写与一键发布。 |
| [social-media-skills](https://github.com/blacktwist/social-media-skills) | Claude Code | 🔧 需适配 | ![](https://img.shields.io/github/stars/blacktwist/social-media-skills?style=flat-square) | 社媒策略与文案技能集，覆盖受众上下文、内容日历、hook、thread、carousel、改写和复盘，默认偏向 X/LinkedIn 等文本平台。 |
| [baoyu-skills](https://github.com/JimLiu/baoyu-skills) | Claude Code / ClawHub | ✅ 直接可用 | ![](https://img.shields.io/github/stars/JimLiu/baoyu-skills?style=flat-square) | 宝玉老师开源 Claude Code 技能集 — 小红书图文卡片、信息图（21 种布局 × 21 种风格）、SVG 图解、Markdown 转 HTML 等一整套内容生产技能。 |
| [khazix-skills](https://github.com/KKKKhazix/khazix-skills) | Claude ​Code | ✅ 直接可用 | ![](https://img.shields.io/github/stars/KKKKhazix/khazix-skills?style=flat-square) | 「数字生命卡兹克」开源 AI 技能合集 — `khazix-writer` 公众号长文写作，复刻卡兹克"有见识的普通人"风格；`hv-analysis` 横纵分析法深度研究，输出排版精美的 PDF 报告。 |
| [social-account-doctor](https://github.com/JuneYaooo/social-account-doctor) | Claude ​Code | ✅ 直接可用 | ![](https://img.shields.io/github/stars/JuneYaooo/social-account-doctor?style=flat-square) | 自媒体「找对标 → 拆爆款 → 套自己」三命令闭环，覆盖小红书/抖音/快手/视频号/B站 — 输入账号或选题方向，输出可直接发的下一条笔记初稿（标题 + 封面大字 + 首段 + CTA）。仓库自包含 tikhub HTTP CLI，开箱即用。 |
| [AmpliPost](https://github.com/AlanSong2077/Amplipost) | Claude Code / MCP | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/AlanSong2077/Amplipost?style=flat-square) | 基于多 Agent + xiaohongshu-mcp 的多平台内容营销中台，覆盖生成、审核、风控与发布，但需平台凭证和浏览器环境。 |
| [servasyy_skills](https://github.com/huangserva/servasyy_skills) | Claude Code / Multi | ✅ 直接可用 | ![](https://img.shields.io/github/stars/huangserva/servasyy_skills?style=flat-square) | 中文多媒体内容生产技能集，覆盖写作、配图、播客、Remotion 视频制作、媒体下载和 Twitter 爬取，按目录交付 14 个可复用技能模块。 |
| [LearnPrompt](https://github.com/LearnPrompt/LearnPrompt) | OpenClaw | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/LearnPrompt/LearnPrompt?style=flat-square) | 永久免费开源的 AIGC 课程, 目前已支持Claude Code，Codex，Hermes，OpenClaw，Obsidian，Prompt Engineering, ChatGPT, Midjourney, Runway, Stable Diffusion, AI数字人，AI声音&音乐，开源大模型 |
| [From-Zero-to-AGI](https://github.com/AI-mzq/From-Zero-to-AGI) | MCP Server | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/AI-mzq/From-Zero-to-AGI?style=flat-square) | 从零走向AGI之路！！！旨在深入了解通用人工智能（AGI）的发展路径，从最基础的概念起，逐步构建完整的知识体系。涵盖AI Agent、RAG、MCP、具身智能、大语言模型、多模态、数字人、AI绘画、AI视频等！！ |
| [xhs-writer-skill](https://github.com/JuneYaooo/xhs-writer-skill) | Claude Code | ✅ 直接可用 | ![](https://img.shields.io/github/stars/JuneYaooo/xhs-writer-skill?style=flat-square) | 小红书爆款笔记生成器 — 基于 GPT-Image-2，强力超快生成封面+标题+正文+话题标签，自然语言修改，一站出图，开箱即用。 |
| [self-media-compliance-review](https://github.com/JuneYaooo/self-media-compliance-review) | Claude Code | ✅ 直接可用 | ![](https://img.shields.io/github/stars/JuneYaooo/self-media-compliance-review?style=flat-square) | 自媒体视频发布前违规风险审核 Skill — 结构化检查画面、声音、文字、封面、评论引导、带货信息、资质、授权、引流等平台常见风险，给出具体修改建议。不是敏感词表，是审核流程。 |

## 视频处理技能

| 技能 | 平台 | 可用性 | Stars | 说明 |
|------|------|--------|-------|------|
| [CapCut Mate API](https://github.com/Hommy-master/capcut-mate) | API / Skills | ✅ 直接可用 | ![](https://img.shields.io/github/stars/Hommy-master/capcut-mate?style=flat-square) | 开源剪映/CapCut 自动化工具，向智能体提供草稿编辑、素材插入、特效、字幕和导出等视频处理能力。 |
| [capcut-agent](https://github.com/qingpingwang/capcut-agent) | Claude Code / MCP | ✅ 直接可用 | ![](https://img.shields.io/github/stars/qingpingwang/capcut-agent?style=flat-square) | 基于 LangGraph + Flask 的剪映 AI 助手，提供对话式剪辑、素材库管理、SQLite 持久化和 FastMCP 工具接入，适合本地化视频制作工作流。 |
| [hotclip](https://github.com/xixihhhh/hotclip) | — | ⚠️ 部分可用 | ![](https://img.shields.io/github/stars/xixihhhh/hotclip?style=flat-square) | 免费开源的 AI 剪辑 / 直播切片工具:长视频、直播回放、播客一键切成爆款竖屏短视频——AI 找高光金句、自动加字幕、横屏转竖屏,本地运行无水印不上传 | Free open-source Opus Clip alternative, 100% local: AI clips long videos & livestream VODs into viral 9:16 shorts. No ... |

---

## 常见问题

### 什么是 Claude Code 技能？

Claude Code 技能是扩展 Claude Code 功能的可复用能力。技能可通过斜杠命令调用，为视频生成、社媒管理等特定任务提供专业领域知识和工具集成。

### 什么是 MCP 服务器？

MCP（Model Context Protocol）服务器提供 AI 助手可调用的工具接口。在自媒体工作流中，MCP 服务器可以连接社交媒体 API、视频编辑工具和内容管理系统。

---

## 贡献

欢迎贡献！请先阅读[贡献指南](CONTRIBUTING.md)。

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
