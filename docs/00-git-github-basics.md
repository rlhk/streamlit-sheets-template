# 00 · Git and GitHub, the absolute minimum

This template is built so you never install anything. Everything happens in your browser. To make changes and watch them deploy, you need a tiny bit of git/GitHub vocabulary.

## Create a GitHub account (if you don't have one)

You only do this once.

1. Go to [github.com/signup](https://github.com/signup).
2. **Email:** one you actually check — you'll need to verify it.
3. **Password:** something you'll remember.
4. **Username:** this becomes part of every URL you'll create here (`github.com/<your-username>/…`). Pick something professional — your real name, your initials, or a stable handle you already use. Lowercase letters, numbers, and hyphens only. Hard to change later, so don't pick a joke.
5. Solve the puzzle. Click the verification link in the email GitHub sends you.
6. The "personalize your experience" page is optional — click **Skip personalization** at the bottom.
7. **Enable two-factor authentication (2FA) when prompted.** GitHub requires it for accounts that contribute code. Easiest path: install the **GitHub Mobile** app on your phone and follow the prompt to link it. Any authenticator app (Google Authenticator, 1Password, Authy) also works. Keep your phone handy whenever you sign in.

The **free plan** is all you need. Public repos, unlimited public forks, github.dev editing, and the Streamlit Cloud connection all work on the free tier. **Don't add a credit card** — none of this template costs anything.

## Concepts

- **Repository (repo)** — a folder of files, plus the full history of every change ever made to those files. Lives on GitHub. This template is one repo.
- **Commit** — a saved snapshot of the repo at a moment in time. Each commit has a short message like *"fix typo in title"*.
- **Fork** — your own personal copy of someone else's repo, hosted under your GitHub username. You make changes in your fork; the original is untouched. **You must fork this template before you can deploy it.**
- **`main`** — the default branch (history line). For now, ignore other branches — you'll commit straight to `main` in your fork.

## Fork this template

1. Open the template's GitHub page (the page you're reading this from).
2. Click **Fork** at the top right.
3. Accept the defaults; click **Create fork**.

You now have a copy at `github.com/<your-username>/streamlit-sheets-template`. Everything below happens in your fork.

## Edit one file in the browser

1. In your fork, open the file you want to change (e.g. `step1-mock/app.py`).
2. Click the **pencil icon** ✏️ at the top right of the file view.
3. Make your changes.
4. Scroll down to **Commit changes**. Write a short message ("update form title"). Click **Commit changes**.

If you've already connected your fork to Streamlit Community Cloud, the app redeploys in about a minute.

## Edit multiple files at once with github.dev

Pressing the period key (`.`) on any GitHub repo page opens [github.dev](https://github.dev) — a full code editor in your browser, no install needed. From there:

1. Open files from the file tree on the left.
2. Edit; changes are held in memory.
3. Click the **Source Control** icon (third from the top on the left bar).
4. Type a commit message, click the ✓ checkmark, then **Sync changes** (the cloud icon at the bottom) to push to GitHub.

This is the easiest way to edit several files together (e.g. when adapting the template to a new schema).

## See the history

On any file: click **History** at the top right to see every change ever made, who made it, and exactly which lines were added or removed.

## What you can ignore for now

- **Branches** other than `main` — useful later, not needed here.
- **Pull requests** — the formal way to propose changes to *someone else's* repo. You don't need this when editing your own fork.
- **`git clone`, `git push`, the terminal** — the whole point of this template is that you don't.
