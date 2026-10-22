# ✨ Awesome Muse AI Skills

> 23 battle-tested agent skills that turn **Muse AI** from a chatbot into a video studio, voice lab, 3D workshop, research assistant, and engineering team — all installed, tested, and documented with copy-paste install commands.

If you run an AI agent (Muse, Claude Code, or any agent that supports skill packs), these are the highest-leverage upgrades you can install. Each one below is **free**, **open-source**, and **verified working** in a real daily-driver setup.

⭐ **Star this repo** if it saves you an evening — and star the skill repos too, so their authors keep building.

---

## 📦 The Skills

### 🎬 Video & Animation

| Skill | What it does for you | Install |
|---|---|---|
| ai-video-director 🛠️ *custom* | Directs cinematic AI video like a film director — camera language, shot lists, character consistency, captions & branding | custom skill, no public upstream yet — adapt the pattern |
| [animated-short-film](https://github.com/sonlovinbot/Muse-animated-short-film) | End-to-end animated short film pipeline: character sheets → story bible → keyframes → per-scene prompts → voiceover → ffmpeg assembly | `git clone https://github.com/sonlovinbot/Muse-animated-short-film.git` |
| [hyperframes](https://github.com/heygen-com/hyperframes) | Deterministic MP4 video from HTML/CSS animations — lyric videos, explainers, motion graphics, captioned clips | `git clone https://github.com/heygen-com/hyperframes.git` |
| [video-use](https://github.com/browser-use/video-use) | Edit video by *conversation*: "cut the filler words, grade it warm, burn subtitles" — transcribe → cut → grade → captions | `git clone https://github.com/browser-use/video-use.git` |
| [openfilm](https://github.com/openfilm/openfilm) | Turn any coding agent into a video agent: it writes the film as animated web pages (`film.html` + `window.film` `frame(t)` contract), a local Studio editor lets you change anything by hand, then export MP4/GIF/stems or Premiere/Final Cut timelines | `git clone https://github.com/openfilm/openfilm.git` |
| [ai-video-editor](https://github.com/MartinDelophy/ai-video-editor) | Local-first browser AI video editor + agent skill: CapCut-style multi-track timeline with local AI captions, voiceover, music & repair, reversible declarative edits, deterministic offline export | `git clone https://github.com/MartinDelophy/ai-video-editor.git` |
| media-revision-delivery 🛠️ *local* | Delivery discipline for revised media: versioned filenames, numeric loudness verification, verify-the-exact-file before shipping — no stale-cache or clipping surprises | local workflow skill — no public repo yet |

### 🎙️ Voice & Audio

| Skill | What it does for you | Install |
|---|---|---|
| [voicestudio](https://github.com/debpalash/VoiceStudio) | Voice cloning & design, video dubbing, dictation, transcription, audiobooks (646 languages) via local backend | `git clone https://github.com/debpalash/VoiceStudio.git` |

### 🌐 Web, 3D & Diagrams

| Skill | What it does for you | Install |
|---|---|---|
| [scroll-craft](https://github.com/nateherkai/scroll-craft) | Premium scroll-driven landing pages — cinematic camera journeys, not generic templates | `git clone https://github.com/nateherkai/scroll-craft.git` |
| [threeui](https://github.com/MengTo/threeui) | 50+ production Three.js components: shader heroes, particle systems, glass cards, 3D scenes | `git clone https://github.com/MengTo/threeui.git` |
| [diagram-design](https://github.com/cathrynlavery/diagram-design) | 45 diagram types — architecture, sequence, ER models, flowcharts, Sankey, Wardley maps — as polished, branded HTML/SVG/PNG | `git clone https://github.com/cathrynlavery/diagram-design.git` |
| [emilkowalski-skills](https://github.com/emilkowalski/skills) | 15 design-engineering skills by Emil Kowalski — UI polish, animation craft, prototyping, and the invisible details that make software feel right instead of generic | `npx skills@latest add emilkowalski/skills` |
| [anatomy-isometric](https://github.com/wheresryan22/anatomy) | Explains a technical idea by *building* it as a working isometric machine in SVG/WebGL — dial gauges, plotters, arcade cabinets — every number from a live model | `git clone https://github.com/wheresryan22/anatomy.git` (installs into `custom-skills/anatomy-isometric/`) |

### 💻 Engineering

| Skill | What it does for you | Install |
|---|---|---|
| [agent-skills](https://github.com/addyosmani/agent-skills) | 25 production-grade engineering workflows: spec-driven dev, TDD, code review, debugging, security hardening, CI/CD, ADRs | `git clone https://github.com/addyosmani/agent-skills.git` |
| [playwright-cli](https://github.com/microsoft/playwright-cli) | Token-efficient browser automation & testing from the CLI | `git clone https://github.com/microsoft/playwright-cli.git` |
| [reverse_engineer_anything](https://github.com/morluto/rea) | Decompile APKs, Electron apps, .NET assemblies, firmware — explain how *shipped* software actually works | `git clone https://github.com/morluto/rea.git` |
| [android-skills](https://github.com/android/skills) | Official Google Android skills: Compose, CameraX, on-device AI, Play billing, security — 30 modules | `git clone https://github.com/android/skills.git` |
| [headroom](https://github.com/headroomlabs-ai/headroom) | Context compression layer for agents — squeezes tool outputs, logs, RAG chunks & conversation history to a fraction of the tokens. Same answers, lower cost, runs locally | `git clone https://github.com/headroomlabs-ai/headroom.git` |
| [mattpocock-skills](https://github.com/mattpocock/skills) (~300k ⭐) | Matt Pocock's daily-driver skill pack: clarifying-question loops before coding, spec→implementation, TDD, retrospectives, codebase wayfinding, plus writing docs agents actually follow | `git clone https://github.com/mattpocock/skills.git` |

### 🌍 Research & Internet

| Skill | What it does for you | Install |
|---|---|---|
| [agent-reach](https://github.com/Panniantong/Agent-Reach) (~100k ⭐) | Internet reading layer: any web page, YouTube subtitles, GitHub repos, RSS — one CLI, zero API fees | `git clone https://github.com/Panniantong/Agent-Reach.git` |

### 💼 Career

| Skill | What it does for you | Install |
|---|---|---|
| [ai-job-search](https://github.com/MadsLorentzen/ai-job-search) (~50k ⭐) | Automate the job hunt: portal scraping, fit-ranked shortlists, tailored CVs & cover letters, interview prep, outcome tracking | `git clone https://github.com/MadsLorentzen/ai-job-search.git` |

### ✍️ Writing

| Skill | What it does for you | Install |
|---|---|---|
| [humanizer](https://github.com/blader/humanizer) | Rewrites AI-sounding prose so it reads human — kills the tells (no "delve", no not-X-but-Y contrasts) | `git clone https://github.com/blader/humanizer.git` |

### 🤖 Multi-Agent Orchestration

| Skill | What it does for you | Install |
|---|---|---|
| [paperclip](https://github.com/paperclipai/paperclip) (~100k ⭐) | 9 skills for running agent teams: heartbeat tasks, boards, hiring agents, plan→tasks, AgentMail, Slack | `git clone https://github.com/paperclipai/paperclip.git` |

> 🛠️ **ai-video-director** is a custom skill built for this setup (no public upstream yet) — included here as a pattern you can adapt: directing + producing AI video with phone apps as the generation backend.

---

## ⚡ Installation

```bash
# 1. Open your agent's skills folder (Muse shown here)
cd ~/workspace/custom-skills/

# 2. Clone any skill from the tables above, e.g:
git clone https://github.com/heygen-com/hyperframes.git

# 3. Done. Your agent discovers it automatically —
#    just describe the task: "make a lyric video for this song"
```

**Requirements some skills have** (called out honestly):
- `voicestudio` needs its backend running on your own machine (it isn't a self-contained tool).
- `paperclip` is inert without a running Paperclip server.
- `ai-video-director` generates clips on your phone (Higgsfield/Kling/Hailuo) — the skill directs & assembles.

---

## 🔥 Before vs After

| Task | ❌ Before (no skills) | ✅ After (skills installed) |
|---|---|---|
| Editing a video | Wrestling ffmpeg flags or Premiere timelines for an hour | *"Cut the filler words, warm up the grade, burn subtitles"* — done |
| Landing page | Generic AI-template look, card grids | Cinematic scroll-driven 3D journey |
| Voiceover | Robotic TTS everyone recognizes | Cloned / emotive voice, dubbed video |
| Research | Copy-pasting 10 articles by hand | One command pulls pages + YouTube subtitles + GitHub code |
| LinkedIn post | Obviously AI-written, zero engagement | Humanizer pass — reads like you wrote it |
| Animated short film | Months of animation work | Character sheets → keyframes → VO → assembled film |
| Lyric / explainer video | After Effects learning curve | HTML/CSS animation → deterministic MP4 |
| Android bug | Docs spelunking for an hour | Official Google skill answers with the right API |
| Shipping code | Cowboy commits, hope-driven | Spec → tests → review → ADR pipeline |
| Job hunt | 50 tabs, spreadsheets, burnout | Scraped, fit-ranked, tailored, tracked |
| Closed-source app | Guessing how a feature works | Decompile it and read the actual logic |
| Agent token costs | Logs & tool dumps eat your whole context window | Headroom compresses them ~4–8× before the model ever sees them |
| Architecture diagram | Whiteboard photo or default Mermaid boxes | Editorial, branded diagram in 45 types, export-ready |
| Technical explainer graphic | Generic stock illustration, static and vague | Working isometric "machine" figure — animated, every number from a live model |
| Vague build request | Agent builds the wrong thing from fuzzy instructions | Clarifying-question loop + spec pipeline before any code exists |
| Launch / explainer video | Paying for motion design or fighting After Effects | Agent writes it as web pages, you edit it in Studio, render MP4 |
| Reel / cut from raw footage | Timeline fiddling for hours | Agent makes reversible edits on a real multi-track timeline, AI captions + voiceover local |

---

## 🤝 Contributing

Found a skill that deserves a spot? Open a PR with: name, repo link, one-line superpower, install command. Bar is simple — **free, open-source, and genuinely useful in an agent workflow.**

## 📄 License

MIT — do whatever you want with this list.

---
*Curated from a real daily-driver Muse AI setup. If it helped you, a ⭐ is the cheapest thank-you there is.*
