# Karen & Marvin — Wedding

Wedding website for **December 22, 2026** in Mumbai, India.

---

## Publish to GitHub and GitHub Pages

### 1. Create a new repository on GitHub

1. Go to [github.com/new](https://github.com/new).
2. Name the repo (e.g. `wedding` or `karen-marvin-wedding`).
3. Choose **Public**.
4. Do **not** add a README, .gitignore, or license (you already have files locally).
5. Click **Create repository**.

### 2. Push your site from your computer

In Terminal, from the **Wedding** folder, run:

```bash
cd /Users/karencardoz/Wedding

# Initialize git (if not already)
git init

# Add all files
git add .

# First commit
git commit -m "Wedding website"

# Add your GitHub repo as remote (replace YOUR_USERNAME and YOUR_REPO with your actual repo name)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub (use main branch)
git branch -M main
git push -u origin main
```

Use your GitHub username and the repo name you chose in step 1 for `YOUR_USERNAME` and `YOUR_REPO`.

### 3. Turn on GitHub Pages

1. On GitHub, open your repo.
2. Go to **Settings** → **Pages** (left sidebar).
3. Under **Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / **Folder**: `/ (root)`
4. Click **Save**.

After a minute or two, your site will be live at:

**https://YOUR_USERNAME.github.io/YOUR_REPO/**

Example: if your username is `karencardoz` and the repo is `wedding`, the URL is:

**https://karencardoz.github.io/wedding/**

You can share this link with guests.
