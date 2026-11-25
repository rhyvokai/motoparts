# Prompt Log — MotoParts

## 1 — Project setup with README, .gitignore, and prompt log
- Prompt: Set up the MotoParts repository with README.md describing the preloved motorcycle parts community problem and FR-01, .gitignore, and PROMPT_LOG.md.
- Result: Created README.md, .gitignore, and PROMPT_LOG.md on branch main.
- Verified: All three files exist and render cleanly in VS Code.
- Commit: f78cff0

## 2 — Build core MotoParts preloved motorcycle parts marketplace (FR-01)
- Prompt: Build single-file MotoParts app where any user with an account can sign in/register, post preloved motor parts to Sell, Trade, or Give away with compatible motorcycle model and condition, and lock claimed/purchased parts immediately in localStorage.
- Result: Created index.html with Rider Account Access, Sell/Trade/Give posting form, preloved parts grid, immediate locking on claim, and localStorage persistence.
- Verified: Registered users can post parts; claiming a part marks it Locked/Taken and disables the button across refresh.