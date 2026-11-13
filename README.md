# Learn from Tasks

A Codex agent that reviews completed tasks, identifies techniques that worked in at least two independent tasks, and turns them into reusable skills. Each candidate must pass an independent run on a new synthetic task before publication.

## Set up in Codex

1. Copy the repository's `SKILL.md` to `~/.codex/skills/learn-from-tasks/SKILL.md`. If you use a custom Codex home, put it in that home's `skills/learn-from-tasks` directory.
2. Open a local Codex desktop chat. The review needs access to local Codex chat history and an independent subagent for validation. For GitHub publication, sign in to GitHub CLI and authorize publication under your own account in Codex's instructions.
3. Paste the prompt from [AUTOMATION.md](AUTOMATION.md) into the chat. For recurring reviews, use the same prompt when setting up a weekly automation in that chat.

The automation keeps a local checkpoint between reviews. It reports published skills, the synthetic task each passed, and the observed result. Review evidence stays local. Published repositories contain the reusable instructions and any synthetic examples or helpers needed by the skill.
