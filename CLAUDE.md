# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

SocialSpark is a social media platform. The tech stack and architecture will be documented here as the project develops.

## Git Workflow

Every meaningful change must be committed and pushed to GitHub. This is non-negotiable — the user relies on version history for rollbacks.

- Remote: `https://github.com/Gowan2318/SocialSpark` (account: Gowan2318)
- Branch: `main`
- `gh` CLI is at `C:\Program Files\GitHub CLI` — add to PATH before use: `$env:PATH = $env:PATH + ";C:\Program Files\GitHub CLI"`
- Commit message style: imperative mood, concise subject line (e.g. `Add user auth`, `Fix feed pagination`)
- Always push after committing: `git push origin main`
