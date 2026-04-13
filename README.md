# Claude Skills

Personal collection of skills and rules for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Rules

Rules are passive instructions that shape how Claude behaves in every session. Drop them into `~/.claude/rules/` to activate.

| Rule | What it does |
|---|---|
| [English Coaching](rules/english.md) | Corrects grammar mistakes in real-time, adds Chinese translations, and coaches non-native speakers to write more naturally |

## Installation

One-liner to install any rule:

```bash
curl -o ~/.claude/rules/english.md https://raw.githubusercontent.com/Kutius/claude-skills/main/rules/english.md
```

Claude Code will automatically load it in every session. No restart needed.

## Uninstall

```bash
rm ~/.claude/rules/english.md
```

## Structure

```
rules/          # Passive rules (always active)
skills/         # Active skills (slash commands) — coming soon
```
