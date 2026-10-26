<div align="center">

# Hi, I'm Jason 👋

**Building tools that let AI coding agents work as a real dev team.**
**让 AI 编程工具像一支真正的开发团队一样协作。**

[🌐 Homepage](https://jasonchencnn.github.io) · [🧩 AI Team Workspace](https://github.com/jasonchencnn/ai-team-workspace)

</div>

---

### 🇨🇳 中文

我在做 **AI Team Workspace（Teamspace）**：一个 macOS 桌面应用，让 Claude Code、Codex、MiniMax Code、Gemini CLI 等 AI 编程工具按固定岗位（Leader / 产品 / 前端 / 后端 / QA）组成开发团队。

我只和 Leader 对话，Teamspace 负责 **建任务 → 派工 → 在隔离的 git worktree 里执行 → 验收合并 → 留痕**，人不再是在各个 AI 之间来回搬运任务和上下文的那个人。

- 🧠 **岗位 ≠ 工具 ≠ 模型**：任务派给岗位，岗位可以随时换绑到不同的 Harness 和模型
- 🔌 **基于 ACP 协议** 驱动各家 CLI，内置 MCP 工具箱让 Leader 直接拆任务、派工、验收
- 🌳 **每次执行独立 worktree**，逐文件 diff 验收，通过后才合入基线分支
- 🙋 **人始终有最终控制权**：权限请求、换绑、合并主分支都由人拍板

我也在实践这种工作方式本身：项目由 Claude 担任总指挥，按任务强度把活派给不同模型（Opus / Sonnet / Haiku / MiniMax），用 Teamspace 开发 Teamspace。

### 🇺🇸 English

I'm building **AI Team Workspace (Teamspace)** — a macOS desktop app that turns AI coding agents such as Claude Code, Codex, MiniMax Code and Gemini CLI into a team with fixed roles (Leader / PM / Frontend / Backend / QA).

I only talk to the Leader. Teamspace handles the rest: **create tasks → dispatch → run in an isolated git worktree → review & merge → keep an audit trail**, so I'm no longer the person shuttling tasks and context between AI tools.

- 🧠 **Role ≠ tool ≠ model** — work is assigned to roles, and a role can be rebound to another harness or model at any time
- 🔌 **Built on ACP** to drive each CLI, plus an MCP toolbox so the Leader can split, assign and review tasks itself
- 🌳 **One worktree per run**, per-file diff review, merged into the base branch only after approval
- 🙋 **Humans stay in control** — permission requests, rebinding and merges to main are always the human's call

I also practice this way of working on the project itself: Claude acts as the lead and routes work to models by difficulty (Opus / Sonnet / Haiku / MiniMax). Teamspace is built with Teamspace.

---

### 🛠️ Tech · 技术栈

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB)
![Tauri](https://img.shields.io/badge/Tauri_2-24C8DB?logo=tauri&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?logo=anthropic&logoColor=white)

### 📌 Now · 当前进展

- ✅ M1–M7 complete: teams & roles, ACP dispatch, review loop, Leader MCP orchestration, role messaging, harness rebinding, polish & `.dmg` packaging
- ✅ M1～M7 已完成：团队与岗位、ACP 派工执行、验收闭环、Leader 编排、岗位通信、换绑与上下文继承、打磨与打包
- 🔍 Final product check in progress · 正在做最终产品校验
