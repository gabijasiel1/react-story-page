# React Static Page with Git/GitHub

Assignment: React app with a static story page and Git/GitHub workflow practice.

## Quick start

1. Go into the app folder: `cd story-app`
2. Install dependencies (if needed): `npm install`
3. Start the app: `npm start`
4. Open [http://localhost:3000](http://localhost:3000)

See **story-app/README.md** for full project description and setup steps.

## GitHub workflow (to do on your side)

1. **Create a new repository on GitHub**  
   On GitHub: New repository → name it (e.g. `react-story-page`) → Create (no need to add README if you already have one).

2. **Clone the repository locally** (if you started from GitHub first):
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```
   If this project was created locally first (as here), you can instead add GitHub as a remote:
   ```bash
   cd "React Static Page with GitGitHub"
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```

3. **Commit and push** (from the repo root or from `story-app` depending on where you want the React app to live):
   - If your repo root is this folder (with `story-app` inside):
     ```bash
     git add .
     git commit -m "Add React story app - Tortoise and the Hare"
     git branch -M main
     git push -u origin main
     ```
   - Note: `story-app` was created with its own git repo; you may want to remove `story-app/.git` and add `story-app` contents to the parent repo, or push only the contents of `story-app` to the GitHub repo. Choose one structure and stick to it.

4. **Submit** the GitHub repository URL (e.g. `https://github.com/YOUR_USERNAME/YOUR_REPO_NAME`) as required.
