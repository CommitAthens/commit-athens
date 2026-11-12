# Commit Athens: Submissions

Every team puts its project in its own folder under `teams/`.

## How to submit

1. Pick a folder name for your team: lowercase, dashes, no spaces. Example: `teams/blue-owls/`
2. Copy `teams/_template/README.md` into your folder and fill it in.
3. Add your code next to it.

### No git? Use the website

1. Open the `teams` folder on GitHub.
2. Click **Add file → Create new file**.
3. In the name box type `your-team-name/README.md` and paste the filled-in template.
4. Commit. Then use **Add file → Upload files** inside your folder to drag in the rest of your project.

### With git

```bash
git clone https://github.com/CommitAthens/commit-athens.git
cd commit-athens
cp -r teams/_template teams/your-team-name
# edit teams/your-team-name/README.md and add your code
git add teams/your-team-name
git commit -m "Add your-team-name"
git push
```

## Rules

- Only touch your own team folder.
- Never commit API keys or passwords. Use a `.env.example` with fake values instead.
- Push before the deadline. Anything pushed after it will not be judged.
