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
- Commit: c61bef8

## 3 — Add motorcycle model search and Sell/Trade/Give filter
- Prompt: Add a search bar for part names or compatible motorcycle models and a dropdown filter for All, Sell, Trade, and Give Away listings.
- Result: Added searchInput and filterTypeSelect controls and updated renderParts() to filter displayed cards in real time.
- Verified: Typing a motorcycle model or selecting Sell/Trade/Give filters the marketplace listings immediately.
- Commit: ebb322e

## 4 — Add duplicate active listing guard and minimum length validation
- Prompt: Validate that part name and motorcycle model have at least 2 characters and prevent the same rider from posting duplicate active listings for the exact same part and model.
- Result: Added 2-character minimum checks and a duplicate active listing check in the postPartForm submit handler.
- Verified: Submitting 1-character inputs or duplicate active listings for the same rider shows an error message.