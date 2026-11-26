# Kemal

I build small tools that help AI coding agents work together,
and I send fixes to the open-source tools I use every day.

<!-- profil:urun:basla -->
**New:** [oss-ai-policy-check](https://github.com/KemalG-u/oss-ai-policy-check), finds a GitHub repository's AI contribution policy, with every line linked at a pinned commit. Early release (0.3.1), on [PyPI](https://pypi.org/project/oss-ai-policy-check/).
<!-- profil:urun:bitir -->

**New:** [look-before-you-code](https://github.com/KemalG-u/look-before-you-code), a skill and a pre-write hook
that make Claude Code and Codex search for existing solutions before writing new code.

**New:** [prove-it-review](https://github.com/KemalG-u/prove-it-review), a skill and a reviewer subagent
that make coding agents prove a delivery with fresh evidence before calling it done.

**New:** [subagent-tiers](https://github.com/KemalG-u/subagent-tiers), reusable Claude Code agent definitions
with a guide for matching work to evidence, risk and review needs.

**New:** [signed-agent-mailbox](https://github.com/KemalG-u/signed-agent-mailbox), a durable, optionally HMAC-signed message box
that lets Claude Code and Codex sessions hand work to each other and wake each other up. Python standard library only.

<!-- profil:birlesen:basla -->
**Recently merged**
- [vyncint/termlens#796](https://github.com/vyncint/termlens/pull/796): fix(emu): list a `<`-marked CSI with the marker before its parameters
- [cdklabs/cdk-from-cfn#1376](https://github.com/cdklabs/cdk-from-cfn/pull/1376): feat: add --name CLI option and deprecate --stack-name
- [RizgarOzan/turkish-rag-eval#34](https://github.com/RizgarOzan/turkish-rag-eval/pull/34): Review computer-science draft questions 001–010
- [cdklabs/cdk-from-cfn#1367](https://github.com/cdklabs/cdk-from-cfn/pull/1367): fix: avoid empty Python guards for conditional resources
- [vyncint/termlens#793](https://github.com/vyncint/termlens/pull/793): fix(cli): detect JSON screens after leading whitespace
- [pymeasure/pymeasure#1595](https://github.com/pymeasure/pymeasure/pull/1595): Clarify how to clone your PyMeasure fork
- [Automattic/harper#4991](https://github.com/Automattic/harper/pull/4991): fix(git-commit): skip conventional commit prefixes when linting
<!-- profil:birlesen:bitir -->

<!-- projeler:basla -->
## Projects

### Featured / Öne çıkanlar

- [look-before-you-code](https://github.com/KemalG-u/look-before-you-code): A skill and PreToolUse gate that makes AI coding agents (Claude Code, Codex) look for existing solutions before writing new code. _Last activity: 2026-11-25._
- [oss-ai-policy-check](https://github.com/KemalG-u/oss-ai-policy-check): Find a GitHub repository's AI contribution policy, with every line linked at a pinned commit. _Last activity: 2026-11-25._
- [signed-agent-mailbox](https://github.com/KemalG-u/signed-agent-mailbox): Durable, optionally HMAC-signed message box between Claude Code and Codex sessions. Python stdlib only. _Last activity: 2026-11-25._
- [soz-agent-capsule](https://github.com/KemalG-u/soz-agent-capsule): Windows capsule and local server that runs a coding agent, verifies "done" with approved checks (evidence gate) and a rule-based guard. _Last activity: 2026-11-25._
- [subagent-tiers](https://github.com/KemalG-u/subagent-tiers): Reusable Claude Code agent definitions with a guide for matching work to evidence, risk and review needs. _Last activity: 2026-11-25._
- [prove-it-review](https://github.com/KemalG-u/prove-it-review): Agent skill and reviewer subagent that make coding agents prove a delivery with fresh evidence before calling it done. _Last activity: 2026-11-24._

### Active development / Geliştiriliyor

- [ajanmuhendis](https://github.com/KemalG-u/ajanmuhendis): FastAPI + SQLite backend and dashboard JS slice of a Turkish AI-learning site (progress, XP, quiz), a base for a future agent-engineering studio. _Last activity: 2026-11-25._
- [content-package-studio](https://github.com/KemalG-u/content-package-studio): Local single-user workbench that turns frozen sources into reviewed X post drafts and verifiable ZIP packages, with revisions, approvals and no publishing path. _Last activity: 2026-11-25._
- [muhendisal](https://github.com/KemalG-u/muhendisal): Free Turkish-language course for becoming an AI engineer with the Anthropic API: 78 pages (MkDocs Material), four reference projects, optional FastAPI progress backend. _Last activity: 2026-11-25._
- [llm-balance-monitor](https://github.com/KemalG-u/llm-balance-monitor): Daily balance check for DeepSeek, Moonshot and OpenRouter API credit, with JSON history and threshold warnings. _Last activity: 2026-11-25._
- [preinstall-gate](https://github.com/KemalG-u/preinstall-gate): Local app to inspect an AI tool, skill or MCP server before installing it: source analysis, gated trial runs, plus reusable model-gateway and project-memory modules. _Last activity: 2026-11-25._
- [jev-demo](https://github.com/KemalG-u/jev-demo): Next.js demo UI of a decision lab (routing, risk, priority) with fixed example rules; no model runs. Independent, not affiliated with Jev. _Last activity: 2026-11-25._

And 7 smaller experiments in [the full repository list](https://github.com/KemalG-u?tab=repositories).

### Experiments & archive / Deneyler

- [model-laboratuvari](https://github.com/KemalG-u/model-laboratuvari): SQL schema and a checker that detects speaker leakage across train/dev/test splits in speech datasets. _Last activity: 2026-11-25._
- [jev-teknik-arastirma](https://github.com/KemalG-u/jev-teknik-arastirma): Independent, source-linked research on using Jev's decision API as a decision signal, with evidence limits (Turkish, EN summary). _Last activity: 2026-11-24._
- [karincaai-lightpanda-rehberi](https://github.com/KemalG-u/karincaai-lightpanda-rehberi): Turkish beginner guide to the Lightpanda headless browser with a controlled VPS benchmark against Chrome (Aug 2026). _Last activity: 2026-11-24._
- [tauri-hotkey-paste-spike](https://github.com/KemalG-u/tauri-hotkey-paste-spike): Two small Tauri v2 spikes for Windows: a global push-to-talk style hotkey that places text into the focused window via clipboard+Ctrl+V or Unicode key input. _Last activity: 2026-11-24._
<!-- projeler:bitir -->

I'm based in Turkey and also work on Turkish language tools at KarıncaAI.

I build with Claude Code and Codex: I set the rules and make the calls, the agents write the code,
and every change is tested before it goes out. Projects that carry an AI-USE file say exactly who did what.
