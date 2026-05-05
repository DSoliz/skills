# Skills

A collection of custom skills for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## What are skills?

Skills are reusable prompt files that extend Claude Code's behavior. Each skill lives in its own directory under `skills/` and contains a `SKILL.md` file defining the skill's instructions.

## Available Skills

| Skill | Command | Description |
|-------|---------|-------------|
| [Pirahã](skills/piraha/SKILL.md) | `/piraha` | Restructures Claude's output to follow Pirahã language constraints — minimal, direct, no nesting. |

## Installation

Clone this repo and add the skills to your Claude Code configuration:

```bash
git clone <repo-url> ~/repos/skills
```

Then reference the skill directory in your Claude Code settings or install it via the CLI.

## Adding a New Skill

1. Create a directory under `skills/` with your skill name.
2. Add a `SKILL.md` file inside it with the skill's prompt and instructions.
3. Update this README with the new skill.

