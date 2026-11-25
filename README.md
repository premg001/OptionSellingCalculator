# Option Averaging Calculator

A single-file calculator. Everything (HTML, CSS, JavaScript) is in `Option_Averaging_Simple.html`. Nothing is saved or sent anywhere; it all runs in your browser.

## 1. Use it locally in VS Code

1. Download `Option_Averaging_Simple.html` and `README.md` into one folder, for example `option-calculator`.
2. Open VS Code, choose **File → Open Folder**, and select that folder.
3. Right-click `Option_Averaging_Simple.html` and choose **Open with Live Server** (install the "Live Server" extension if needed), or just double-click it to open it in your browser.

## 2. Put it on Git

Open the VS Code terminal (**Terminal → New Terminal**) in the folder, then run:

```bash
git init
git add Option_Averaging_Simple.html README.md
git commit -m "Add option averaging calculator"
git branch -M main
```

Create an empty repository on github.com (no README), then connect and push:

```bash
git remote add origin https://github.com/YOUR_USERNAME/option-calculator.git
git push -u origin main
```

## 3. Host it free with GitHub Pages

The included GitHub Actions workflow deploys the site automatically whenever you push to the `main` branch. After the first deployment, open [the calculator](https://premg001.github.io/OptionSellingCalculator/Option_Averaging_Simple.html).
If prompted, enable GitHub Pages for the repository and allow GitHub Actions to deploy it.

## 4. Updating later

```bash
git add Option_Averaging_Simple.html
git commit -m "Update calculator"
git push
```

## Notes

- Keep the repo private if you don't want others to see your numbers. GitHub Pages on a free account needs a public repo; for a private repo, use Netlify or Cloudflare Pages.
- The page loads Tailwind CSS from a CDN, so it needs internet access.
- Lot sizes and margins are inputs you set. Confirm them with your broker and exchange.
- This is an analytical tool, not financial advice.
