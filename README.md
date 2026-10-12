# seamless-object-removal · 无痕去杂物修图提示词 Skill

把一套三段式"抹除杂物 → 像素级重建背景 → 光影统一"的修图提示词，做成 Claude 可调用的 Skill。对 Claude 说"帮我把这张图里的 XX 去掉，写个提示词"，它会按你的图改写出可直接复制到 GPT / 豆包 / 即梦 / Gemini / PS 创成式填充的版本。

## 安装

**Claude Code（一行命令）**

```bash
npx skills add <你的GitHub用户名>/<仓库名>
```

**Claude Code（手动）**：把 `seamless-object-removal` 文件夹复制到
- macOS / Linux：`~/.claude/skills/`
- Windows：`C:\Users\<用户名>\.claude\skills\`

重启 Claude Code 即可。

**Claude.ai 网页版 / 桌面版**：下载本仓库里的 `seamless-object-removal` 文件夹并压缩成 zip，进入 设置 → Capabilities（功能）→ Skills → Upload skill 上传。

## 使用

> 帮我写个提示词，把这张图里桌上的外卖盒和它的影子去掉

发图或描述画面都可以。说"给我原版"会直接输出母版，说"英文版"会给英文。
