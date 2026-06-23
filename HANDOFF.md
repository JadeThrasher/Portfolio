# Handoff — Deploy portfolio to GitHub

## What this is
Jade Savoia's design portfolio — a static HTML/CSS site (no build step). Files:
`index.html`, `project.html`, `project-2.html`, `project-3.html`, `project-4.html`,
`styleguide.html`, `tokens.css`, `README.md`.

## Current state
- This folder is already a **git repository** with one commit on the **`main`** branch.
- Author identity is set to: Jade Savoia <jadecharvelle@gmail.com>.
- No remote is configured yet. Nothing has been pushed.

## What's left to do
1. Create a new GitHub repository named **`portfolio`** under Jade's account.
2. Add it as the `origin` remote and push `main`.
3. (Optional) Enable **GitHub Pages** (Settings → Pages → Source: `main`, root) to put it online.
4. (Optional) Point a custom domain at the Pages site.

## Quick commands (for a developer / Claude Code)
```bash
# from this folder, with GitHub CLI:
gh repo create portfolio --public --source=. --remote=origin --push

# or, after creating an empty repo named "portfolio" on github.com:
git remote add origin https://github.com/<username>/portfolio.git
git push -u origin main
```

## Note
Jade is a designer with no coding experience — please handle the git/GitHub steps
directly rather than handing back commands, and confirm before anything destructive.
