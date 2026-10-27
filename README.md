# Idiot Human App Tester

A Claude Code skill that tests your app as an extremely lazy, impatient, first-time user. It reads your project's Markdown docs to learn the intended features and funnels, then drives the real UI to find confusing screens, abandonment risks and irritating bugs. It suggests simpler journeys, applies fixes when you authorize them, and checks that the fixes work.

## Install

Download `idiot-human-app-tester.zip` from the [latest release](../../releases/latest) and unzip it into your skills folder:

```bash
# for one project
unzip idiot-human-app-tester.zip -d .claude/skills/
# or for every project
unzip idiot-human-app-tester.zip -d ~/.claude/skills/
```

Or clone this repo and copy the `idiot-human-app-tester/` folder there.

## Use

In Claude Code, run `/idiot-human-app-tester`, or ask Claude to test your app as a lazy first-time user.

The skill itself is [`idiot-human-app-tester/SKILL.md`](idiot-human-app-tester/SKILL.md).

## License

MIT
