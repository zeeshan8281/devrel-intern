# devrel-intern

> **You just hired a full DevRel team. They live in your terminal. They never sleep. They don't ask for equity.**

```bash
npm install -g devrel-intern
```

Type `/devrel-intern` in Claude Code. Watch five specialists show up and get to work.

---

## What is this?

You know how great DevRel teams have a content writer who actually understands APIs, a community manager who doesn't sound like a corporate bot, a researcher who tracks what competitors are doing, a developer advocate who builds real demos, and an analyst who doesn't just make up numbers?

**This is all five of them. In one command. Briefed on your product. Ready instantly.**

No hiring. No onboarding. No Slack messages going unread for three days.

---

## The Team

### ✍️ Content Writer
Writes developer content that developers actually want to read. Tutorials that lead with a real problem. Changelogs that say "you can now do X" instead of "we implemented Y". Newsletters people open. Talk abstracts that get accepted.

### 🤝 Community Manager
Handles every developer touchpoint without sounding like a support ticket system. GitHub issues, Discord threads, Twitter/X replies, forum posts — warm, honest, unblocking. Flags recurring questions before they become a docs crisis.

### 🔬 Technical Researcher
Tracks the ecosystem so you don't have to. Competitor DevRel analysis, trend reports, developer pain point mapping from community signals. Delivers findings in one page with a TL;DR and confidence level — not a 40-slide deck.

### 📣 Developer Advocate
Builds the stuff that makes developers say "oh damn." Demo scripts. Sample apps with READMEs that actually make sense. Onboarding email sequences. Hackathon briefs. Holds a hard standard: time to hello world must be under 5 minutes.

### 📊 Analytics Reporter
Turns real DevRel data into decisions. The key word is **real** — this agent refuses to invent metrics. You give it numbers, it gives you insights, gaps, and a recommended action list with owners and deadlines.

---

## How It Works

### First run
```
/devrel-intern
```

You get a 5-question onboarding interview. One question at a time, no forms, no YAML. Your answers get saved to `.devrel-intern/context.md` — so every agent is permanently briefed on your product, audience, tone, and priorities.

### Every run after that
```
Welcome back! I'm briefed on [Your Product]. What do you need today?
```

The team already knows who you are.

### Just describe the task
```
Write a tutorial on streaming responses from our API
```
```
Respond to this GitHub issue — developer says our SDK breaks on Node 18
```
```
Research what Stripe, Twilio and Resend are doing for developer onboarding
```
```
Build a hackathon brief for ETHGlobal with $5k in prizes
```
```
Synthesize this NPS data into something I can share with the product team
[paste data]
```

The coordinator picks the right agent(s), they read your context, and they deliver.

---

## Multi-Agent Tasks

Some tasks need the whole crew. The team coordinates — not just dumps separate outputs.

**Product launch?**
> Content Writer writes the blog post → Community Manager drafts the Discord announcement → Developer Advocate outlines the demo → each one references what came before it.

**Ecosystem positioning piece?**
> Technical Researcher maps the landscape → Content Writer uses those findings to write the post.

One coherent deliverable. Every time.

---

## Context Stays Fresh

Team context is saved to `.devrel-intern/context.md` in your project directory. Commit it or gitignore it — your call.

When things change:
```
update team context — we just launched a new SDK and our priorities shifted
```

The coordinator re-asks only what changed, shows you a summary card, and saves the update.

---

## The Analytics Reporter Rule

Every other AI tool will confidently generate a metrics report with completely made-up numbers. This one won't.

The Analytics Reporter asks for your actual data first. If you don't have it, it gives you a blank template — clearly labeled as such — so you fill it in before sharing it with anyone.

No hallucinated KPIs. No fictional growth curves.

---

## What Gets Written to Disk

```
.devrel-intern/
  context.md    # your team briefing
```

That's it.

---

## Install

```bash
npm install -g devrel-intern
```

Requires [Claude Code](https://claude.ai/code). After installing, restart Claude Code and type `/devrel-intern`.

---

## The 15 Things This Team Can Do

1. Developer blog posts (tutorials, deep dives, announcements)
2. API & SDK documentation
3. Changelogs developers actually read
4. GitHub issue responses (empathetic + technical)
5. Discord / Slack / forum replies
6. Twitter/X threads for developer audiences
7. Ecosystem trend reports
8. Competitor DevRel analysis
9. Developer pain point mapping
10. Conference talk abstracts & speaker pitches
11. Demo scripts & sample app READMEs
12. Developer onboarding sequences
13. Hackathon briefs, bounty specs, grant copy
14. Developer newsletters
15. Developer feedback → product team insight reports

---

## License

MIT

---

<p align="center">
  Built with Claude Code &nbsp;·&nbsp; <a href="https://www.npmjs.com/package/devrel-intern">npm</a>
</p>
