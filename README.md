# dating-coach · 综合恋爱教练 Skill

一个覆盖「搭讪 → 邀约 → 展示面 → 约会 → 聊天复盘」全链路的恋爱沟通教练 Skill。
把生硬 / 油腻 / AI 味的台词，改成**自然、真诚、进退有度**的聊天与执行方案。

> 由课程视频 + 文章提炼而来。原始素材里民间称为「PUA」的技法（打压 / 推拉 / 合理推诿 / 进挪 / 收束节奏），已作为**中性参考库**收录，使用时一律以「尊重对方意愿」为前提。

---

## 模块覆盖

| 模块 | 文件 | 内容 |
|------|------|------|
| 1 · 搭讪开场 | `references/01-搭讪.md` | 焦虑破解 / 群体切入 / 低压力开场 / 第一印象 / 经典战术参考 |
| 2 · 邀约 | `references/02-邀约.md` | 铺垫 / 低压力邀约公式 / 被拒处理 / 红线 |
| 3 · 展示面拍摄 | `references/03-展示面拍摄.md` | ⚠️ 待补（需 Leon 视频转录稿） |
| 4 · AI 展示面 | `references/04-AI展示面.md` | ⚠️ 待补（需 Leon 视频转录稿） |
| 5 · 约会 SOP | `references/05-约会SOP.md` | ⚠️ 待补（需 Leon 视频转录稿） |
| 6 · 聊天复盘 | `references/06-复盘聊天记录.md` | 5 维复盘框架 / 真实 Q&A / 实战报告模板 |
| 技法参考库 | `references/07-技法参考库.md` | 五大技法（打压/推拉/合理推诿/进挪/收束）的健康用法 + 翻车边界 |

`references/README.md` 说明各参考文件的来源与提炼标准。

---

## 已固化的硬规则（铁律）

1. 不油、不装、**尊重意愿**；对方退 / 冷淡 / 不接就停。
2. 给话术 **+ 为什么 + 退路**。
3. **不爆金币、女性同等付出**：不单方面讨好砸钱；引导对方也付出，对方主动付出时顺水推舟。
4. **女方主动邀约 / 暗示必须接住坐实**（用合理推诿把发起权归她）。
5. 去 AI 味，说人话。

## 专属互动工作流

你（用户）**只发女方的信息**（她的消息 / 画像 / 状态）→ Skill 先速读、反问补齐关键项 → 结合知识库给方案。
详见 `使用指南.md`。

---

## 在任何设备 / agent 工具上使用

### 方式 A · Git Clone（推荐，全平台通用）

Skill 目录要求 `SKILL.md` 位于 `~/.workbuddy/skills/dating-coach/` 下。

**Windows（PowerShell / Git Bash）：**
```bash
git clone https://github.com/ddyuan-spec/dating-coach-skill.git "$HOME/.workbuddy/skills/dating-coach"
```
（若目录已存在，先 `Remove-Item -Recurse "$HOME/.workbuddy/skills/dating-coach"` 再 clone）

**macOS / Linux：**
```bash
git clone https://github.com/ddyuan-spec/dating-coach-skill.git ~/.workbuddy/skills/dating-coach
```

Clone 完**重启 / 刷新 WorkBuddy** 即可在对话里调用 `dating-coach`。

### 方式 B · 手机 / 其他 agent 工具（从 URL 加载）

若你的 agent 工具支持「从仓库 URL / raw 文件加载 Skill」，直接指向：
- 仓库：`https://github.com/ddyuan-spec/dating-coach-skill`
- 入口文件（raw）：`https://raw.githubusercontent.com/ddyuan-spec/dating-coach-skill/main/SKILL.md`

把整个仓库 clone / 下载到该工具约定的 skills 目录即可，目录名保持 `dating-coach`。

### 更新

在 skill 目录内 `git pull` 即可同步最新版。

---

## 素材与待补

- 已纳入：寒江雪 2009 邮件合集（搭讪 / 邀约 / 复盘 / 技法库）、零失误搭讪课（9 音频转写）、Leon 撩妹 3.0（17 视频转写）。
- 待补：模块 3 / 4 / 5 的实战内容依赖 Leon 视频转录稿精细化，后续补齐。
