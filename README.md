# AI Title Generator — 一键生成爆款标题的 Agent Skill

**English** | [中文](README.zh-CN.md)

> AI title / headline generator **skill**. Turn any article into two tiers of titles in one shot:
> ① **Professional tier** (WeChat / Zhihu / Woshipm) — QbitAI (量子位) · Jiqizhixin (机器之心) · Xinzhiyuan (新智元) styles
> ② **Xiaohongshu (RED) tier** — first-person + emoji + pain-point hook

## ✨ What it does

- One article → **公众号标题 / 知乎标题 / 小红书标题** all at once
- Three Chinese tech-media styles (量子位 / 机器之心 / 新智元), each with a main pick + an alternate
- Built-in **platform → style** mapping, so you never have to guess which style fits where
- Title strategy baked in: borrow the viral mechanics, **never fabricate hooks**
- For Chinese content creators, 自媒体, product managers, and AI practitioners

## 🚀 Install (`npx skills add`)

```bash
npx skills add SweetPomelo0/ai-title-generator
```

Works with **Claude Code, Codex, Gemini CLI, GitHub Copilot** and other agents in the `skills` ecosystem.

## 🎯 Usage

Hand it an article or a topic and say **"write titles" / "起标题"**. Ask for a single tier or a single style when you only want one.

## 📦 Example

**Input:** an article announcing a faster, cheaper new AI model

**Output:**
```
【Tier A · WeChat / Zhihu / Woshipm】
🔥 QbitAI      刚刚！这家甩出新模型：推理更强，价格还砍了
🎓 Jiqizhixin  新一代模型发布：推理能力提升，调用成本同步下降
⚡ Xinzhiyuan  更强推理 + 更低价格：新模型一手登场，重新定义性价比

【Tier B · Xiaohongshu】
姐妹们这个 AI 又更新了😳 这次是真香：更聪明还更便宜
```

## 🗂 Platform → Style

| Platform | Tier / Style |
|---|---|
| 公众号 WeChat | Tier A (any of the three) |
| 人人都是产品经理 Woshipm | Tier A · Jiqizhixin (methodical) |
| 知乎 Zhihu | Tier A · Jiqizhixin / question-style (search-oriented) |
| 小红书 Xiaohongshu | Tier B |

## 🔑 Keywords / 适用场景

AI title generator · headline generator · viral title generator · claude skill · claude code skill · agent skill · content creation · copywriting · AI标题生成 · 爆款标题 · 公众号标题 · 知乎标题 · 小红书标题 · 起标题 · 量子位/机器之心/新智元风格 · 自媒体标题 · 中文 agent skill

## License

[MIT](LICENSE)
