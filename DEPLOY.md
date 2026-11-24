# GitHub deployment (macOS)
1. Extract ZIP and open Terminal in the extracted xss-detection-mitigation folder.
2. Review PDF and screenshots for information you do not want public.
3. Create an empty repository named xss-detection-mitigation at https://github.com/new (no README).
4. Run the following, replacing YOUR_USERNAME:

```bash
git init
git add .
git status
git commit -m "Initial XSS security project"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/xss-detection-mitigation.git
git push -u origin main
```
5. Authenticate with GitHub CLI or a personal access token if prompted.
6. Repository Settings > Pages > Deploy from a branch > main > /docs > Save.
7. Open https://YOUR_USERNAME.github.io/xss-detection-mitigation/ after deployment.

GitHub Pages hosts only the static frontend. Run the Express backend locally. Original report evidence is unchanged; new examples are not evidence of completed retests.
