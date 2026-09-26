<div align="center">

<img src="./林汐音小猫娘喵_meow.svg" alt="林汐音 · 小猫娘喵 · meow" width="600">

<img src="./林汐音_ba-style@logo.bluearchive.cc.png" alt="林汐音" width="220">

# 林汐音 · juangchuank-ops

**AI 网关 / 反向代理 · AstrBot 插件 · 实用工具**

[![Repositories](https://img.shields.io/badge/Repositories-24-2496ED?style=flat-square)](https://github.com/juangchuank-ops?tab=repositories)
[![Stars](https://img.shields.io/badge/Stars-30-f1c40f?style=flat-square)](https://github.com/juangchuank-ops?tab=repositories)
[![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://go.dev)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Followers](https://img.shields.io/github/followers/juangchuank-ops?style=flat-square&color=2ea44f)](https://github.com/juangchuank-ops)

</div>

---

## 关于我

喜欢把**网页端 / 桌面端的 AI 能力**包装成标准 API，也喜欢把想法做成能直接跑起来的小工具。
主力语言是 **Go**（追求零依赖、单二进制、纯标准库）和 **Python**（快速验证想法），
偶尔折腾 Java / JavaScript。

> 把曾经的美好，续成往后的陪伴。 —— 来自 [Afterglow](https://github.com/juangchuank-ops/Afterglow)

---

## 兴趣 / 审美

写代码之外，审美上偏爱这几样：

| | |
| :--- | :--- |
| **猫娘** | 猫耳、尾巴、软绵绵的松弛感。理想型是安静陪伴那种，不是吵闹的 |
| **Femboy** | 中性偏女装的质感，单纯觉得好看 |
| **林汐音** | 就是上面那张 logo，Blue Archive 风格的自设形象 |
| **其他** | 像素风、低饱和冷调、蓝白主色，以及一堆「懒得解释但就是喜欢」的东西 |

审美归审美，代码归代码，仓库都摆在那儿，随便看。

<!-- 想换配图时，替换下面 src 的文件名即可
-->

<div align="center">

<img src="./catgirl_original.png" alt="原创猫娘插画" width="300">

<sub>原创猫娘 · 蓝白配色</sub>

</div>

---

## 技术栈

| 领域 | 技术 |
| :--- | :--- |
| 后端 | Go（标准库优先）、Python、FastAPI、Java |
| 前端 | React、原生 Web 管理台 |
| 方向 | OpenAI / Anthropic / Gemini 兼容协议转换、号池调度、Cookie 续期、计费与限流 |
| 平台 | AstrBot 插件生态、Minecraft Fabric 模组移植、向量数据库 |

---

## 精选项目

### 🚀 [minimax2api](https://github.com/juangchuank-ops/minimax2api) · ![stars](https://img.shields.io/github/stars/juangchuank-ops/minimax2api?style=flat-square&color=f1c40f)

MiniMax Agent 反向网关：**OpenAI 兼容接口** + **号池调度** + **管理控制台**（Go + React）。

### 🚀 [dola2api](https://github.com/juangchuank-ops/dola2api) · ![stars](https://img.shields.io/github/stars/juangchuank-ops/dola2api?style=flat-square&color=f1c40f)

把 Dola 变成 OpenAI 兼容接口 · 号池管理 · 管理台 · 纯 Go 标准库。

### 🌟 [Afterglow](https://github.com/juangchuank-ops/Afterglow)

使用社交软件聊天记录结合**向量数据库**，让 AI 更好地扮演对方的角色。
在**不微调模型**的情况下即可达到可观的效果。

### 🌟 [xianyu-auto-reply-fix](https://github.com/juangchuank-ops/xianyu-auto-reply-fix)

闲鱼智能客服系统：多账号管理、AI 自动回复、自动发货确认、多渠道消息通知，附带完整 Web 管理后台。

### 🌟 [FishTool](https://github.com/juangchuank-ops/FishTool)

完全基于 AstrBot 开发的 **AI 运营工具箱**，面向新手个人创作者、无需学习成本的个人自媒体智能运营助理。

---

## 项目总览

### AI 网关 / API 反向代理

把网页端、桌面端、第三方 Agent 的模型能力，统一转换成标准 API。

| 项目 | 说明 | 语言 | ★ |
| :--- | :--- | :---: | :---: |
| [minimax2api](https://github.com/juangchuank-ops/minimax2api) | MiniMax Agent 反向网关：OpenAI 兼容接口 + 号池调度 + 管理控制台 | Go + React | 10 |
| [dola2api](https://github.com/juangchuank-ops/dola2api) | 把 Dola 变成 OpenAI 兼容接口 · 号池管理 · 管理台 · 纯 Go 标准库 | Go | 9 |
| [new-api-main-copy](https://github.com/juangchuank-ops/new-api-main-copy) | AI API 网关 / 代理：多供应商聚合（OpenAI、Claude、Gemini、AWS Bedrock）+ 用户、计费、限流 | Go | 3 |
| [new-api](https://github.com/juangchuank-ops/new-api) | 统一的 AI 模型聚合与分发中心，支持 OpenAI / Claude / Gemini 格式互转 | Go | 1 |
| [geminiweb2api](https://github.com/juangchuank-ops/geminiweb2api) | 把 gemini.google.com 网页端包装成 OpenAI 兼容接口 · 多账号号池 + Cookie 自动续期 | Go + React | 1 |
| [jev2api](https://github.com/juangchuank-ops/jev2api) | TypeSafe Jev 反向代理网关：原生 `/v1/systemone` 透传 + OpenAI 兼容层，含号池与控制台 | Go | 1 |
| [mistral2api](https://github.com/juangchuank-ops/mistral2api) | Mistral 反向代理网关 | Python | 1 |
| [grok2api](https://github.com/juangchuank-ops/grok2api) | 基于 FastAPI 的 Grok 网关，将 Grok Web 能力转换为 OpenAI 兼容 API | Python | — |
| [Essence](https://github.com/juangchuank-ops/Essence) | OpenAI 兼容 AI 网关：模型目录、计费、管理后台、上游价格同步 | Go | — |
| [Minimax-design2api](https://github.com/juangchuank-ops/Minimax-design2api) | 把 MiniMax Design 桌面版反代成 OpenAI / Anthropic 兼容 API，纯 Go 标准库单二进制 | Go | — |
| [gemini-web2api](https://github.com/juangchuank-ops/gemini-web2api) | Gemini 网页端 → OpenAI 兼容 API，含 Web UI 控制台、多账号轮换、并发限制 | JavaScript | — |
| [new-api-registration-code](https://github.com/juangchuank-ops/new-api-registration-code) | new-api 注册码相关 | — | — |
| [ghcp_proxy](https://github.com/juangchuank-ops/ghcp_proxy) | GitHub Copilot 代理 | Python | — |

### AstrBot 插件

| 插件 | 说明 | ★ |
| :--- | :--- | :---: |
| [astrbot_plugin_ancient_poem](https://github.com/juangchuank-ops/astrbot_plugin_ancient_poem) | 古诗词插件 | 2 |
| [astrbot_plugin_group_verify](https://github.com/juangchuank-ops/astrbot_plugin_group_verify) | 群聊验证 | 1 |
| [astrbot_plugin_llm_condenser](https://github.com/juangchuank-ops/astrbot_plugin_llm_condenser) | LLM 对话压缩 | — |
| [astrbot_plugin_robot_identity](https://github.com/juangchuank-ops/astrbot_plugin_robot_identity) | 机器人身份设定 | — |
| [FishTool](https://github.com/juangchuank-ops/FishTool) | AI 运营工具箱（面向 B 站自媒体创作者） | — |

### 应用与工具

| 项目 | 说明 | 语言 | ★ |
| :--- | :--- | :---: | :---: |
| [xianyu-auto-reply-fix](https://github.com/juangchuank-ops/xianyu-auto-reply-fix) | 闲鱼智能客服系统：多账号 + AI 自动回复 + 自动发货 + Web 后台 | Python | — |
| [Afterglow](https://github.com/juangchuank-ops/Afterglow) | 聊天记录 + 向量数据库，让 AI 扮演对方角色，无需微调模型 | Python | — |
| [GrokX](https://github.com/juangchuank-ops/GrokX) | Grok 协议注册机 · Grok Web 批量自动注册工具 | Python | — |
| [my-imegas](https://github.com/juangchuank-ops/my-imegas) | 个人图床 / 图片集合 | — | — |

### Minecraft 模组

| 项目 | 说明 | 语言 | ★ |
| :--- | :--- | :---: | :---: |
| [Tacz-Golden-Deagle-P320-Standalone-26.2](https://github.com/juangchuank-ops/Tacz-Golden-Deagle-P320-Standalone-26.2) | TACZ 独立枪械包（Golden Deagle P320） | Java | 1 |
| [Tacz-fabric](https://github.com/juangchuank-ops/Tacz-fabric) | TACZ-Fabric-26.2 移植版 | Java | — |

---

## 语言分布

```
Python      ████████████████████░░░░░░░░░░░░░░░░░░  11
Go          ██████████████░░░░░░░░░░░░░░░░░░░░░░░░   8
Java        ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   2
Other       ████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   2
JavaScript  ██░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░   1
```

---

## 联系

- GitHub：[@juangchuank-ops](https://github.com/juangchuank-ops)
- 仓库列表：[github.com/juangchuank-ops?tab=repositories](https://github.com/juangchuank-ops?tab=repositories)

<div align="center">

<img src="./林汐音_ba-style@logo.bluearchive.cc.png" alt="林汐音" width="120">

<sub>林汐音 · Blue Archive Style</sub>

</div>
