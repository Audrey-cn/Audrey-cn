<div align="center">

# ⚡ Audrey's Cyber Lab · 赛博折腾实验室

**Stuffing Linux desktops into phones, coaxing macOS onto a Panasonic laptop,<br />building self-bootstrapping AI agents, and shipping zero-dependency pocket games.**

*把完整桌面塞进手机 · 给松下小本子装黑苹果 · 给 AI Agent 造工具箱 · 顺手写点单文件离线小游戏*

`🟢 Lab Status: Tinkering` · `🤖 AI Agents` · `📱 Android & Linux` · `🍎 Hackintosh` · `🎮 Pocket Games`

</div>

---

```yaml
# $ cat ~/.audrey/lab_manifest.yml
operator: Audrey (Audrey-cn)
vibe:     Curious tinkerer · Systems hacker · AI agent builder · Weekend game dev
timeline: 2023–2024 Prompt Engineering → 2025 Private & Team R&D → 2026 Open-Source Extraction
motto: |
  "If a device has a CPU, it deserves an unreasonable OS —
   or at least a single-file game."
  # 只要有 CPU，就值得装点不讲道理的系统，或者跑一个单文件小游戏
lab_rules:
  - Zero-dependency when possible   # 能单文件搞定，绝不拉一整个宇宙的依赖
  - Evidence-first & honest caveats # 实测说话，自己红队自己的基准数据
  - Make weird hardware do cool things
```

---

## 🧪 Active Lab Benches · 正在折腾的实验台

### 📱 Bench 01 · Systems & Hardware Tinkering（跨界系统与硬件整活）

| Experiment | What's cooking | Tech |
| :--- | :--- | :--- |
| [**`omarchy-android`**](https://github.com/Audrey-cn/omarchy-android) | Run a full **Omarchy Wayland desktop** & ARM64 AI CLI suite (CC Switch, Codex, Claude, Hermes) directly on Android via Root `chroot` & Non-Root `proot`. <br><sub>*把完整的 Wayland 桌面和 ARM64 AI 套件直接塞进安卓手机里。*</sub> | `Kotlin` `Linux` `Wayland` `Android` |
| [**`sv1-hackintosh`**](https://github.com/Audrey-cn/sv1-hackintosh) | Panasonic Let's Note **CF-SV1** (i5-1135G7 / Iris Xe 80EU) macOS 26 Tahoe + WhateverXe engineering repo, AMI BIOS IFR extractor & Tahoe tools. <br><sub>*松下 CF-SV1 黑苹果工程库、BIOS IFR 提取与显卡底层硬件调研。*</sub> | `Python` `OpenCore` `BIOS/IFR` `macOS` |

### 🤖 Bench 02 · AI Agent Infrastructure（AI Agent 基础设施与实验）

| Experiment | What's cooking | Tech |
| :--- | :--- | :--- |
| [**`rpe-harness`**](https://github.com/Audrey-cn/rpe-harness) | ⚙️ Local-first, zero-daemon verifiable execution kernel for coding agents (`v2.3.2` · 3-OS native containment): stdio MCP + local Web/CLI Approval Inbox, 7 verified contracts + SDK, **−98% tokens &amp; 11.5× faster** in 10-step long-horizon pipeline benchmark. <br><sub>*面向编程 Agent 的本地优先可验证执行内核（MCP + 本地审批台、7 大内置合约、10 步大文件长线实测省 98% Token）。*</sub> | `Python` `MCP` `Node.js` `SQLite` |
| [**`universal-agent-embedding-kit`**](https://github.com/Audrey-cn/universal-agent-embedding-kit) | Model-agnostic, embeddable agent kit: verification, adaptive context, effort routing, cache-aware cost model & graded benchmarks — **evidence-first**, every metric red-teamed. <br><sub>*模型无关、证据优先的嵌入式 Agent 工具箱与基准测试。*</sub> | `Python` `LLM` `MCP` `Benchmarks` |

### 🎮 Bench 03 · Pocket Indie Games（零依赖离线游戏实验室）

| Experiment | What's cooking | Tech |
| :--- | :--- | :--- |
| [**`indie-game-lab`**](https://github.com/Audrey-cn/indie-game-lab) · [▶ **Play Live**](https://audrey-cn.github.io/indie-game-lab/) | Zero-dependency, single-file, 100% offline browser games: **Lunar Field Station** (WebGL2 lunar exploration), **Roomba Raid** `v0.9.0` (roguelite living-room extraction) & **Meowball Rush** `v0.3.0` (cel-shaded 3D kitty hamsterball). <br><sub>*单 HTML 文件即点即玩、完全离线的三款原创小游戏：月面采集站、半夜扫地机与魔女猫球。*</sub> | `HTML5` `WebGL2` `Three.js` `Single-File` |

---

## 🧭 Lab Log · 演进脉络

- **`2023 – 2024` · Prompt Engineering Research** — Deep-dive into prompt architecture, structured reasoning, and failure modes of LLM-only workflows. *(提示词工程研究与大模型能力边界探索)*
- **`2025 (since Q1)` · Private & Team Engineering** — Transitioned from prompts to real systems with my team: internal AI agent infrastructure, evaluation pipelines, and cross-device prototypes. *(与团队转入私仓工程化研发：Agent 底座、评测体系与跨端原型)*
- **`2026 – Present` · Open-Source Extraction** — Sanitized and open-sourced reusable kernels, benchmarks, hardware dossiers, and pocket games for public collaboration. *(提炼脱敏通用内核与实验项目，全面转向开源与实测协作)*

---

## 🛠️ Lab Toolkit · 常用装备

- **Languages:** `Python` · `Kotlin` · `HTML5 / WebGL2` · `Shell / Zsh`
- **Playgrounds:** `Android (chroot / proot)` · `Linux / Wayland` · `macOS / OpenCore`
- **AI Stack:** `AI Coding Agents` · `MCP` · `Prompt Caching` · `Eval & Benchmarks`

---

<div align="center">
  <sub>🤝 <strong>Open Collaboration:</strong> All public repositories here actively encourage <strong>Forks, Issues, and Pull Requests</strong> — feel free to remix, build on them, report bugs, or drop a PR!</sub><br />
  <sub>所有公开仓库均热烈欢迎 <strong>Fork 二次开发、提 Issue 交流与提交 PR</strong>，欢迎一起折腾 ✨</sub>
</div>
