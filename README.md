# Claude Skills

Personal collection of skills and rules for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Rules

Rules are passive instructions that shape how Claude behaves in every session. Drop them into `~/.claude/rules/` to activate.

| Rule | What it does |
|---|---|
| [English Coaching](rules/english.md) | Corrects grammar mistakes in real-time, adds Chinese translations, and coaches non-native speakers to write more naturally |

## How to use

Copy any rule file to your Claude Code rules directory:

```bash
cp rules/english.md ~/.claude/rules/english.md
```

Claude Code will automatically load it in every session.

## Structure

```
rules/          # Passive rules (always active)
```

More skills coming as I build them.
