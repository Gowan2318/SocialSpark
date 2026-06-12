# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

SocialSpark is a social media platform. The tech stack and architecture will be documented here as the project develops.

## Git Workflow

**Commit and push to GitHub after every meaningful unit of work — no exceptions.** The user depends on this history to roll back if anything breaks. Do not batch work across multiple tasks before committing; commit as you go.

- Remote: `https://github.com/Gowan2318/SocialSpark` (account: Gowan2318)
- Branch: `main`
- `gh` CLI is at `C:\Program Files\GitHub CLI` — add to PATH before use: `$env:PATH = $env:PATH + ";C:\Program Files\GitHub CLI"`
- Commit message style: imperative mood, concise subject line (e.g. `Add user auth`, `Fix feed pagination`)
- Always push immediately after committing: `git push origin main`

### When to commit

Commit after each of these — do not wait until everything is done:
- A new feature or page is added
- A bug is fixed
- A component or utility is created or meaningfully changed
- Any configuration or dependency change

### Commit sequence

```powershell
# Add to PATH if needed
$env:PATH = $env:PATH + ";C:\Program Files\GitHub CLI"

git add <specific files>
git commit -m "Short imperative description of what changed"
git push origin main
```
