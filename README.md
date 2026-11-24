# Narottaman Gangadaran — Portfolio

A responsive static portfolio for ML engineering job applications. Built with HTML, CSS, and vanilla JavaScript. No build process or paid hosting required.

## Publish to GitHub Pages (recommended)

1. Sign in to GitHub as `narottaman`.
2. Create a **public** repository named **`narottaman.github.io`** (exact spelling).
3. Upload **the contents of this folder** (`index.html`, `styles.css`, `script.js`, `assets/`) to the root of the new repository. Do **not** upload the outer `narottaman-portfolio` folder as an extra level.
4. Open the repository **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, then choose **main** and **/(root)**. Save.
6. After GitHub Pages finishes publishing, visit **https://narottaman.github.io**.
7. Add the URL to your resume, LinkedIn profile, GitHub profile, and applications.

### Command-line alternative

After creating the empty `narottaman.github.io` repository on GitHub:

```bash
cd narottaman-portfolio
git init
git add .
git commit -m "Launch personal portfolio"
git branch -M main
git remote add origin https://github.com/narottaman/narottaman.github.io.git
git push -u origin main
```

Then enable Pages as described above. If Git asks for authentication, use GitHub's supported browser/credential manager or GitHub CLI; don't put a personal access token in your commands or repository.

## Update the site

Edit `index.html` for content, `styles.css` for appearance, and `assets/` for images and the resume. Commit and push changes to `main`; GitHub Pages republishes automatically.

## Local preview

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing

- Verify project descriptions and numerical results match your latest resume and repositories.
- Replace `assets/Narottaman_Resume.pdf` with your newest resume when updated.
- Check the ProQuest thesis link and all GitHub project URLs.
- Only publish photos and contact details you're comfortable sharing publicly.
- Optionally add a custom domain later in GitHub Pages settings.

This repository intentionally has no API keys, credentials, backend services, or dependencies.
