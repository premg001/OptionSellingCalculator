# Option Averaging Calculator

A single-file calculator. Everything (HTML, CSS, JavaScript) is in `index.html`. Nothing is saved or sent anywhere; it all runs in your browser.

## 1. Use it locally in VS Code

1. Download `index.html` and `README.md` into one folder, for example `option-calculator`.
2. Open VS Code, choose **File → Open Folder**, and select that folder.
3. Right-click `index.html` and choose **Open with Live Server** (install the "Live Server" extension if needed), or just double-click `index.html` to open it in your browser.

## 2. Put it on Git

Open the VS Code terminal (**Terminal → New Terminal**) in the folder, then run:

```bash
git init
git add index.html README.md
git commit -m "Add option averaging calculator"
git branch -M main
```

Create an empty repository on github.com (no README), then connect and push:

```bash
git remote add origin https://github.com/YOUR_USERNAME/option-calculator.git
git push -u origin main
```

## 3. Host it free with GitHub Pages

1. In the repo on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Select branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute your site is live at `https://YOUR_USERNAME.github.io/option-calculator/`.

## 4. Updating later

```bash
git add index.html
git commit -m "Update calculator"
git push
```

## Notes

- Keep the repo private if you don't want others to see your numbers. GitHub Pages on a free account needs a public repo; for a private repo, use Netlify or Cloudflare Pages.
- The page loads Tailwind CSS from a CDN, so it needs internet access.
- Lot sizes and margins are inputs you set. Confirm them with your broker and exchange.
- This is an analytical tool, not financial advice.
