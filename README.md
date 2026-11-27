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
| [**`universal-agent-embedding-kit`**](https://github.com/Audrey-cn/universal-agent-embedding-kit) | Model-agnostic, embeddable agent kit: verification, adaptive context, effort routing, cache-aware cost model & graded benchmarks — **evidence-first**, every metric red-teamed. <br><sub>*模型无关、证据优先的嵌入式 Agent 工具箱与基准测试。*</sub> | `Python` `LLM` `MCP` `Benchmarks` |
| [**`progenitor-protocol`**](https://github.com/Audrey-cn/progenitor-protocol) | 🧬 Self-bootstrapping capability layer for AI coding agents: one zero-dependency Python file for code auditing, cross-session state & an opt-in P2P "gene" network. <br><sub>*零依赖单文件 AI Agent 能力自举层与实验性 P2P 基因网络。*</sub> | `Python` `AI Agents` `Artificial Life` |
| [**`progenitor-registry`**](https://github.com/Audrey-cn/progenitor-registry) | The public capability gene pool and semantic index for the Progenitor Akashic network. <br><sub>*Progenitor 网络的公共能力基因库与语义索引。*</sub> | `Python` `Semantic Index` |

### 🎮 Bench 03 · Pocket Indie Games（零依赖离线游戏实验室）

| Experiment | What's cooking | Tech |
| :--- | :--- | :--- |
| [**`indie-game-lab`**](https://github.com/Audrey-cn/indie-game-lab) · [▶ **Play Live**](https://audrey-cn.github.io/indie-game-lab/) | Zero-dependency, single-file, 100% offline browser games: **Lunar Field Station** (WebGL2 lunar exploration) & **Roomba Raid** (casual roguelite extraction). <br><sub>*单 HTML 文件即点即玩、完全离线的月面勘探与割草搜打撤小游戏。*</sub> | `HTML5` `WebGL2` `Canvas2D` `Single-File` |

---

## 🛠️ Lab Toolkit · 常用装备

- **Languages:** `Python` · `Kotlin` · `HTML5 / WebGL2` · `Shell / Zsh`
- **Playgrounds:** `Android (chroot / proot)` · `Linux / Wayland` · `macOS / OpenCore`
- **AI Stack:** `AI Coding Agents` · `MCP` · `Prompt Caching` · `Eval & Benchmarks`

---

<div align="center">
  <sub>🧪 Always happy to geek out on AI agents, weird Linux/Android setups, Hackintosh hardware dossiers, or tiny browser games — feel free to open an Issue or PR!</sub><br />
  <sub>欢迎在任意仓库提 Issue / PR 交流折腾心得 ✨</sub>
</div>
