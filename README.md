# Getting Started with Codex for Non-Developers

**The companion guide to JJ Englert's beginner Codex walkthrough.**

If you are not an engineer and want to get real outcomes with Codex, this repo gives you the exact setup and workflow system to do that.

You will get:
- a beginner-friendly setup path
- a complete non-engineer workspace structure
- copy/paste templates for context files
- starter skills you can adapt to your work
- prompts for research, content packaging, and QA
- a weekly automation starter
- global instructions + MCP setup checklists

This guide is designed around one core outcome: **Do More with AI**.

---

## Watch the Video

[![Watch: OpenAI Codex for Non-Developers](https://img.youtube.com/vi/MavnuV0NRwU/maxresdefault.jpg)](https://www.youtube.com/watch?v=MavnuV0NRwU)

- YouTube: https://www.youtube.com/watch?v=MavnuV0NRwU

---

## Table of Contents

| # | Section | What You'll Get |
|---|---------|----------------|
| -- | [What Is Codex?](#what-is-codex) | Plain-English explainer |
| -- | [Quick Start Checklist](#quick-start-checklist) | Setup sequence in 5 minutes |
| 1 | [Quick Codex Tour](#tip-1-quick-codex-tour) | Desktop/web/mobile/CLI and first setup |
| 2 | [Folder Structure + Context](#tip-2-build-folder-structure--context-first) | The base system for better output |
| 3 | [Skills (Add + Create)](#tip-3-add-skills-and-create-your-own) | Reusable workflows by folder |
| 4 | [Local vs GitHub](#tip-4-local-vs-github) | Simple decision framework |
| 5 | [Threads, Handoff, Commit](#tip-5-threads-handoff-commit-no-jargon) | Stay in flow without restarting |
| 6 | [Research in 15 Minutes](#tip-6-research-in-15-minutes) | Competitor and pattern analysis |
| 7 | [Full Content Package](#tip-7-turn-one-idea-into-a-full-content-package) | One input to many outputs |
| 8 | [3 Sub-Agent QA Pass](#tip-8-run-a-3-sub-agent-quality-pass) | Better final output before publish |
| 9 | [Weekly Automation](#tip-9-set-up-one-weekly-automation) | Repeatable momentum |
| 10 | [Slash Commands + Modes](#tip-10-use-slash-commands-fast--plan-mode) | Faster control in plugin/CLI |
| -- | [Templates Folder](#templates-in-this-repo) | Everything ready to copy |
| -- | [Common Mistakes](#common-mistakes-to-avoid) | What slows beginners down |
| -- | [Follow JJ](#follow-jj) | X and YouTube |
| -- | [Next Steps](#next-steps) | How to level up from here |

---

## What Is Codex?

Codex is an agent workflow experience from OpenAI.

In plain English: you assign tasks, Codex executes, and you review results.

It is not only for developers. Non-engineers can use it for:
- content
- GTM
- research
- customer support
- operations

You can also orchestrate multiple agents in parallel across your workflow.

> JJ note: this setup is part of my ChatGPT subscription (about $20/month at recording time).

---

## Quick Start Checklist

- [ ] Open Codex (desktop/web)
- [ ] Add Global Instructions (use `templates/prompts/global-instructions.md`)
- [ ] Connect your key MCP servers/tools (use `templates/checklists/mcp-setup-checklist.md`)
- [ ] Create local workspace folders (`01_Research`, `02_Drafts`, `03_Assets`, `04_Publish`, `05_Archive`)
- [ ] Add context files from `templates/context`
- [ ] Add one skill from `templates/skills`
- [ ] Run the research prompt from `templates/prompts`
- [ ] Run the content package prompt from `templates/prompts`
- [ ] Run the 3 sub-agent QA prompt from `templates/prompts`
- [ ] Set one weekly automation from `templates/prompts`

---

## Tip 1: Quick Codex Tour

Goal: remove confusion fast.

Cover:
- Web/desktop/mobile/CLI in one minute
- Global Instructions first
- MCP servers/tools second
- First small task to verify setup

Quick line for beginners:
- "Web/mobile assign work. Desktop refines work. CLI is optional day one."

---

## Tip 2: Build Folder Structure + Context First

Use this structure:

```text
project-workspace/
├── 01_Research/
├── 02_Drafts/
├── 03_Assets/
├── 04_Publish/
└── 05_Archive/
```

Add context files from this repo:
- `templates/context/audience.md`
- `templates/context/voice.md`
- `templates/context/offers.md`
- `templates/context/goals.md`

Why it matters:
- better context
- shorter prompts
- cleaner outputs

---

## Tip 3: Add Skills (and Create Your Own)

Skills = reusable instruction playbooks.

Start with one per folder:
- Research skill
- Draft skill
- Assets skill
- Publish skill

Use templates in `templates/skills/` and customize.

Custom skill framework:
1. Name
2. When to use
3. Inputs required
4. Output format
5. Quality checklist

---

## Tip 4: Local vs GitHub

Simple rule:
- Use **Local** for private drafts and early iteration
- Use **GitHub** when work is shared, long-lived, or needs version history

If other people touch it, push it.

---

## Tip 5: Threads, Handoff, Commit (No Jargon)

- One thread per deliverable
- New thread only when outcome changes
- Handoff = continue the same task on another surface/device
- Commit = save point in local history
- Push = sync/share commits to GitHub

Memory line:

> Same deliverable, same thread, same workspace.

---

## Tip 6: Research in 15 Minutes

Use the prompt in `templates/prompts/research-brief.md`.

Ask for:
- hook patterns
- structure patterns
- content gaps
- concrete recommendations

Output should be one brief you can execute immediately.

---

## Tip 7: Turn One Idea Into a Full Content Package

Use `templates/prompts/full-content-package.md`.

Generate in order:
1. script draft
2. title options
3. thumbnail brief
4. description
5. X post

Then move to QA before publish.

---

## Tip 8: Run a 3 Sub-Agent Quality Pass

Use `templates/prompts/sub-agent-qa-pass.md`.

Run 3 personas:
- Clarity Editor
- Audience Strategist
- Skeptical Reviewer

Merge into one fix list:
- what to cut
- what to tighten
- what to prove

---

## Tip 9: Set Up One Weekly Automation

Use `templates/prompts/weekly-automation.md`.

Starter automation:
- every Monday
- generate 3 video ideas
- include mini research summary
- save to `01_Research`

Keep automation output structured and easy to review.

---

## Tip 10: Use Slash Commands (Fast + Plan Mode)

Slash commands help with fast control.

Useful ones to demo:
- `/mode` (switch between fast and plan)
- `/status`
- `/review`
- `/local`
- `/cloud`

Important:
- slash commands are built-in controls
- custom workflow behavior belongs in Skills

---

## Templates in This Repo

### Context
- `templates/context/audience.md`
- `templates/context/voice.md`
- `templates/context/offers.md`
- `templates/context/goals.md`

### Skills
- `templates/skills/research-skill.md`
- `templates/skills/script-skill.md`
- `templates/skills/assets-skill.md`
- `templates/skills/publish-skill.md`
- `templates/skills/skill-template.md`

### Prompts
- `templates/prompts/research-brief.md`
- `templates/prompts/full-content-package.md`
- `templates/prompts/sub-agent-qa-pass.md`
- `templates/prompts/weekly-automation.md`
- `templates/prompts/global-instructions.md`

### Checklist
- `templates/checklists/publish-readiness-checklist.md`
- `templates/checklists/mcp-setup-checklist.md`

---

## Common Mistakes to Avoid

- Skipping folder/context setup
- Writing giant vague prompts
- Starting new threads for the same deliverable
- Publishing first draft output
- Never saving reusable skills/prompts

---

## Follow JJ

- X: https://x.com/jjenglert
- YouTube: https://www.youtube.com/@10x-Builder

Follow on X or subscribe on YouTube if you want the next resource when it drops.

---

## Next Steps

1. Copy the templates into your workspace
2. Customize context + one skill
3. Run Tips 6 -> 9 end-to-end once
4. Save your improved prompt/skill versions
5. Repeat weekly and compound

If this guide helps you, star the repo and share it with one non-engineer builder.
