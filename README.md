# Sudoku Candidates PWA

A Progressive Web App with two tools:
- **Cage Calculator** — killer sudoku cage combinations
- **Sandwich Calculator** — sandwich sudoku filling combinations

---

## Deploy to GitHub Pages (free, 5 minutes)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon top-right, then **New repository**
2. Name it: `sudoku-candidates` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the files
1. On the repository page, click **uploading an existing file**
2. Drag and drop ALL of these files and folders:
   ```
   index.html
   cage.html
   sandwich.html
   manifest.json
   sw.js
   icons/
     icon-192.png
     icon-512.png
   ```
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to **Settings** (tab at top of repo)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and folder **/ (root)**
5. Click **Save**

### Step 5 — Get your URL
After about 60 seconds, refresh the Settings > Pages page. Your URL will appear:
```
https://YOUR-USERNAME.github.io/sudoku-candidates/
```

---

## Install on Android

1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL above
3. Wait for the page to fully load
4. Tap the **three-dot menu** (top right)
5. Tap **"Add to Home screen"**
6. Tap **"Install"** or **"Add"** on the prompt
7. The app icon will appear on your home screen

It will open full-screen with no browser chrome, work offline, and remember your dark/light mode preference.

---

## Notes

- The Google Fonts (JetBrains Mono) are cached after the first load, so the app works fully offline after that.
- Theme preference is saved in localStorage and persists between sessions.
- Both tools share the same theme setting via the `sk-theme` localStorage key.
- To update the app later, just replace the files on GitHub and the service worker will refresh automatically on next open.
