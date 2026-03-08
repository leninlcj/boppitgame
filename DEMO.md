# Codex Demo: Working on `boppitgame`

This is a quick, practical demo of how Codex can help in a repository.

## 1) Ask for a change in plain English
Example prompt:

- "Explain this Arduino game loop and add comments for mode selection."

Codex can inspect files, summarize behavior, and propose edits.

## 2) Codex inspects the code
In this repo, the game logic is in `code`:

- Button input is debounced.
- LEDs move by mode (`sequential`, `bounce`, `random`).
- Pressing on green speeds up; yellow keeps pace; red slows down.

## 3) Codex makes edits and validates
Typical workflow:

1. Read files and constraints (`AGENTS.md` when present).
2. Edit code/docs.
3. Run checks (lint/tests/build if available).
4. Commit changes.
5. Open a PR with a concise summary.

## 4) What to ask Codex next
Try prompts like:

- "Add a serial debug mode to print level and LED index every second."
- "Refactor timing constants into a config section with clearer names."
- "Create a README for wiring and gameplay rules."

## 5) Why this is useful
Codex is strongest for:

- Fast iteration on small code tasks.
- Explaining unfamiliar codebases.
- Creating focused commits and PRs.

It keeps changes auditable by using normal git commits and pull requests.
