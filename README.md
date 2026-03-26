# Self-Healing Project Template

This is a **GitHub template repository**. When you create a new repo from this template, it automatically includes:

## What's Included

### `CLAUDE.md` — 52 Operational Rules
Loaded automatically by Claude Code. Governs all AI agent behavior including:
- Self-healing pipeline mandates
- Verification protocols (no untested work ships)
- Anti-hallucination protocol
- Security rules
- Error classification requirements

### `rules/RULES.md` — Full Rules Reference
The complete, detailed version of all 52 rules with context and examples.

### `infrastructure/templates/self-healing-pipeline.md`
Fill-in-the-blank template for building self-healing pipelines with:
- **Layer 1**: Preflight health checks
- **Layer 2**: Auto-fix loop (detect → fix → recheck, max 2 retries)
- Error classification (Transient, Environmental, Data, Logic, Resource)
- 95%+ self-healing target

### `infrastructure/templates/security-layers.md`
4-layer security model:
1. Plugin security gate
2. Recurring automated scans
3. Critical file protection
4. System health monitoring

## Usage

1. Click **"Use this template"** when creating a new repo
2. All files are automatically included
3. Customize the templates for your specific project

## Source

Derived from [josh-oc-project](https://github.com/jbellsolutions/josh-oc-project) — the full AI agent team framework.
