# GPT/Codex 文稿写作与修改经验

GPT、Codex 写的正式中文文稿常有防御性强、措辞保守、自我交代、形式堆砌等问题。本仓库整理了写作前约束模型、写完后检查修改的经验，适用于报告、规程、技术说明等正式文稿；用于科研论文时的调整和补充检查见文件第六部分。

## 文件

| 文件 | 用途 |
|---|---|
| `GPT文稿写作与修改经验.md` | 完整经验：写作约束与指令模板、八类常见问题、执行任务时的问题、修改流程、自查清单、用于科研论文时 |
| `codex/AGENTS-snippet.md` | 九条写作约束，可粘贴进 Codex 的 `AGENTS.md` |
| `skills/formal-doc-revision/` | Claude Code 与 Codex 通用的技能（SKILL.md 格式） |

## 使用方法

- **ChatGPT 网页版**：把 `GPT文稿写作与修改经验.md` 作为附件上传，再使用文件第一部分的指令模板。
- **Codex**：把 `codex/AGENTS-snippet.md` 的内容追加到 `~/.codex/AGENTS.md`（全局）或项目根目录的 `AGENTS.md`；需要完整流程时，把 `skills/formal-doc-revision/` 复制到 `~/.codex/skills/`。
- **Claude Code**：把 `skills/formal-doc-revision/` 复制到 `~/.claude/skills/`（全局）或项目的 `.claude/skills/`。

本仓库只给方向，各领域的文体和格式按自己领域的规范处理；规则冲突时，以当前任务的要求和单位、期刊的专门规范为准。

## 许可

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh-hans)：可自由转载和修改，请注明出处。

---

相关项目：[Codex 额度扩容](https://github.com/Acyeee/codex-route-bridge)。

<sub>作者另外提供 [小噜噜 API](https://xiaolulu.cc) 和 AI 订阅代充服务，有需要可以联系我。</sub>
