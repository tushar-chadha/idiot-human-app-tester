# Idiot Human App Tester

An [Agent Skill](https://agentskills.io) that tests your app as an extremely lazy, impatient, first-time user. It reads your project's Markdown docs to learn the intended features and funnels, then drives the real UI to find confusing screens, abandonment risks and irritating bugs. It suggests simpler journeys, applies fixes when you authorize them, and checks that the fixes work.

It is one `SKILL.md` file, so it works in any agent that supports Agent Skills.

## Install

### Claude Code (plugin)

```
/plugin marketplace add tushar-chadha/idiot-human-app-tester
/plugin install idiot-human-app-tester@idiot-human-app-tester
```

### Any agent (Claude Code, Codex, Cursor, Gemini CLI, GitHub Copilot, OpenCode and more)

```bash
npx skills add tushar-chadha/idiot-human-app-tester
```

Add `-g` to install it for every project, or `-a <agent>` to pick the agent.

### By hand

Download `idiot-human-app-tester.zip` from the [latest release](../../releases/latest) and unzip it into your agent's skills folder:

| Agent | One project | Every project |
|---|---|---|
| Claude Code | `.claude/skills/` | `~/.claude/skills/` |
| Agents that read the shared folder (Codex, Cursor, Gemini CLI, Copilot and others) | `.agents/skills/` | see your agent's docs |

## Use

In Claude Code, run `/idiot-human-app-tester`. In any agent, you can also just ask it to test your app as a lazy first-time user.

The skill itself is [`skills/idiot-human-app-tester/SKILL.md`](skills/idiot-human-app-tester/SKILL.md).

## License

MIT
