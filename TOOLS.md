# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## What Goes Here

Things like:

- Camera names and locations
- SSH hosts and aliases
- Preferred voices for TTS
- Speaker/room names
- Device nicknames
- Repo/workspace conventions
- Anything environment-specific

## Examples

```markdown
### Cameras

- living-room → Main area, 180° wide angle
- front-door → Entrance, motion-triggered

### SSH

- home-server → 192.168.1.100, user: admin

### TTS

- Preferred voice: "Nova" (warm, slightly British)
- Default speaker: Kitchen HomePod
```

## Why Separate?

Skills are shared. Your setup is yours. Keeping them apart means you can update skills without losing your notes, and share skills without leaking your infrastructure.

---

## Davinci orchestration defaults (Andrew)

- Claude Code is the execution engine (with `davinci-framework` plugin: https://github.com/andrewkim-gif/davinci-framework).
- Per-task workspace: `~/Desktop/work/<task-folder>`
- GitHub org/user: https://github.com/andrewkim-gif
- Preferred stack: Next.js + (optional) Go + Vercel + Supabase
- During active runs: send progress updates about every ~5 minutes.
- Stop immediately on: “그만”, “멈춰”, “그만해”.

Add whatever helps you do your job. This is your cheat sheet.
