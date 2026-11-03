# Siva — DevOps Engineer Portfolio

A responsive, dark-theme portfolio built with plain HTML, CSS and JavaScript. No build tools or framework are required.

## 1. Personalize before publishing

Search the project for these placeholders and replace them:

- `Siva` — your preferred display name.
- `YOUR_EMAIL@example.com` — your professional email address.
- `https://www.linkedin.com/` — your LinkedIn profile URL.
- `https://github.com/` — your GitHub profile URL and project repository links.
- `Hyderabad, India` — update your location if you prefer.
- `assets/resume.pdf` — add your current resume PDF at this exact path.

The project descriptions are suggested portfolio demonstrations based on your DevOps experience. Only publish them as completed projects after you have built them and can explain the implementation. Add repository links, architecture diagrams and measurable outcomes where you have evidence.

## 2. Preview locally

Open `index.html` in a browser, or run a local web server from this directory:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## 3. Publish using GitHub Pages

### Create the repository

1. Sign in to GitHub and create a new **public** repository.
2. Name it exactly `YOUR-GITHUB-USERNAME.github.io` for a user-site URL.
3. Do not initialize with a README if you plan to push this existing project as-is.

### Push the website

Run these commands from the project directory. Replace the URL with your own repository URL:

```bash
git init
git add .
git commit -m "Create DevOps portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/YOUR-GITHUB-USERNAME.github.io.git
git push -u origin main
```

### Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Click **Save**.

After GitHub Pages finishes deploying, visit:

`https://YOUR-GITHUB-USERNAME.github.io/`

Allow a few minutes for the first deployment. Future pushes to `main` publish updates automatically.

## 4. Update your portfolio

Edit `index.html` for content, `style.css` for visual design, and `script.js` for interactions. Then run:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

## Notes

- This is a static website; it does not require a server-side application.
- The font is loaded from Google Fonts. If you prefer no external font request, remove the Google Fonts links from `index.html`; the CSS has fallback fonts.
- Do not publish passwords, API keys, private company information, customer details or confidential screenshots.
