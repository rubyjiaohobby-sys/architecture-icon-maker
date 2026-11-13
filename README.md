[README.md](https://github.com/user-attachments/files/34782385/README.md)
# Architecture Icon Maker（建筑照片转图标）

## Claude Code 安装
将本文件夹 `architecture-icon-maker` 整个放进项目的 `.claude/skills/` 目录（或个人级 `~/.claude/skills/`）。

例如项目级：
```
YOUR_PROJECT/.claude/skills/architecture-icon-maker/SKILL.md
```

重新打开 Claude Code 对话，尝试输入：
“使用 architecture-icon-maker，把我上传的建筑照片转成地图图标，米白背景，不要人和树，严格保留建筑层数和拱廊数量。”

## ChatGPT 使用
可上传 `SKILL.md` 与建筑照片，说明“按这份 Skill 生成建筑图标”。是否能自动注册为 ChatGPT Skills 取决于所在应用环境；本文件本身不等于已安装到 ChatGPT。

## 文件
- `SKILL.md`：可复用的完整工作规则
- `templates/image-prompt.md`：独立可复制提示词
- `references/`：本次的源建筑、参考风格、示例图标

注意：实际出图需要所用环境能够调用图像生成/编辑工具。Skill 文件本身不包含生图模型。
