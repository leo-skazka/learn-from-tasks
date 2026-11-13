# Codex automation prompt

Use this prompt in a local Codex desktop chat. For recurring reviews, choose a weekly schedule in the app.

```text
Review completed local Codex tasks using $learn-from-tasks. Read the installed SKILL.md and use the desktop chat tools to find independent, verified examples of the same technique.

Keep the review checkpoint in learn-from-tasks-state.json in the local Codex home. Record deferred candidates and pending publications there so the next review can resume.

Test each candidate on a fresh synthetic task with an independent subagent. Compare against a run without the skill when that comparison can show a practical benefit. Keep unverified candidates pending.

Publish verified skills only to the public GitHub account explicitly authorized in my instructions. If no account or publishing authorization is available, keep the verified skill local and report where it is. Review every file before publishing and keep source chats and review evidence local.

Report new or updated skills with their links, the synthetic task each passed, and the observed pass criterion. Surface failures that need my action. Keep recurring runs quiet when nothing changed.
```
