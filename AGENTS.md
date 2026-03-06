# AGENTS

## Repository Hygiene
- Always use a dedicated linked git worktree for any code change, PR review, or PR fix. Never work from the primary checkout.
- Never make code changes on `main` or `master`. Create a topic branch in a worktree first.
- Before editing, run `bash scripts/hygiene_check.sh` from the repo root if the script exists.
- Prefer `bash scripts/new_worktree.sh <branch-name>` to create task branches in `../_worktrees/`.
- Before commit or push, run the narrowest relevant test command for the repo and then `bash scripts/hygiene_check.sh` again.
- If repo state changes unexpectedly, stop and inspect `git status`, `git branch --show-current`, and `git reflog --date=iso -5` before continuing.
- Before push, run `bash scripts/review_guard.sh` and `bash scripts/validate_repo.sh` in addition to `bash scripts/hygiene_check.sh`.
