# GitHub Workflow for Flutter App

## 1. Create a GitHub repository
- Go to GitHub and create a new repository.
- Do not initialize it with a README if you already have local files.

## 2. Connect the local project to GitHub
Run these commands in the project folder:

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
git branch -M main
git push -u origin main
```

## 3. Push future changes
After editing your app:

```bash
git add .
git commit -m "Describe your changes"
git push origin main
```

## 4. Pull updates from GitHub
If you or someone else updates the repository:

```bash
git pull origin main
```

## 5. Recommended workflow
- Work locally.
- Commit often.
- Push to GitHub regularly.
- Pull before starting new work if the remote changed.
