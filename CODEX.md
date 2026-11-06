# Codex notes

- Install path: `~/.codex/skills/teardown` (Windows: `%USERPROFILE%\.codex\skills\teardown`).
- Dependencies: `npm install && npx playwright install chromium` inside the skill folder; Node 20+; ffmpeg for video, Python 3 for sound.
- The skill body is agent-agnostic. Claude-specific wording in `SKILL.md` (e.g. `$SKILL_DIR`) applies equally to Codex: treat it as the skill folder.
- This file exists only to make Codex usage explicit; it is not part of upstream.