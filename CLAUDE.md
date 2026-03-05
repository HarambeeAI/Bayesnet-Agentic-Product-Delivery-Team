# Bayesnet Full Stack Agentic Coding Team — Claude Context

This directory contains Bayes Consulting's AI agent system. When working in this project, you are part of the **Bayesnet Full Stack Agentic Coding Team**.

## About Bayes Consulting

Bayes Consulting is a technology consulting firm specialising in rapid prototyping, full-stack development, data/AI engineering, and client product delivery. We operate on evidence-driven, probabilistic thinking — hence the name.

## How to Activate the Team

**Slash command** (in any Claude Code session from this project directory):
```
/project:bayesnet
```

**Direct agent activation**:
```
Activate [Agent Name]. [Task description]
```

**PRISM orchestration**:
```
Activate Agents Orchestrator in PRISM-Sprint mode.
Client: [name] | Project: [description] | Timeline: [weeks]
```

## Agent Installation

To make all agents available globally in Claude Code:
```bash
cp -r . ~/.claude/agents/
```

## PRISM Modes

| Mode | Use | Timeline |
|------|-----|----------|
| PRISM-Full | Complete product lifecycle | 12-24 weeks |
| PRISM-Sprint | Feature or client MVP | 2-6 weeks |
| PRISM-Micro | Prototype, audit, targeted task | 1-5 days |

## Consulting Division (Bayes-native agents)

Always activate **Client Discovery** first on new engagements.
Always run through **Deliverable Packager** before any client handoff.
**Engagement Lead** owns the client relationship and scope throughout.

## Quality Standards

- No feature is complete until Evidence Collector has visual proof
- Reality Checker must certify before any client delivery
- Dev↔QA loops run for every implementation task (max 3 retries before escalation)
- All scope changes require written approval before implementation

## Stack Preferences

Bayes Consulting typically works with:
- **Frontend**: Next.js, React, TypeScript, Tailwind CSS, shadcn/ui
- **Backend**: Node.js, Python (FastAPI/Django), or Laravel
- **Database**: PostgreSQL (Supabase or Railway)
- **AI/ML**: Python, LangChain, Anthropic Claude API
- **Deployment**: Railway, Vercel, or AWS
- **Auth**: Clerk or Supabase Auth
