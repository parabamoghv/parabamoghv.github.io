# Personal Website Template

This is a simple static website for a CV, general cover letter, publications, and project showcase. It is designed to work directly with GitHub Pages.

## Edit Your Content

- Update `index.html` with your name, biography, CV entries, cover letter, publications, projects, and contact links.
- Replace `assets/cv.pdf` with your real CV PDF. If you do not want a PDF download button yet, remove or edit the `Download CV` link in `index.html`.
- Adjust colors and spacing in `styles.css`.

## Preview Locally

Open `index.html` directly in your browser, or run a tiny local server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish With GitHub Pages

1. Create a new repository on GitHub.
   - For a personal site at `https://YOUR-USERNAME.github.io`, name it `YOUR-USERNAME.github.io`.
   - For a project site, use any repo name such as `portfolio`.

2. Connect this local repo to GitHub:

```powershell
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git branch -M main
git push -u origin main
```

3. Enable GitHub Pages:
   - Open the GitHub repository in your browser.
   - Go to `Settings` > `Pages`.
   - Under `Build and deployment`, choose `Deploy from a branch`.
   - Select branch `main` and folder `/root`.
   - Click `Save`.

4. Wait a minute or two. GitHub will show the public URL on the Pages settings screen.

## Common Follow-Ups

- If you use the special repo name `YOUR-USERNAME.github.io`, your site URL is usually `https://YOUR-USERNAME.github.io`.
- If you use a normal project repo, your site URL is usually `https://YOUR-USERNAME.github.io/YOUR-REPO/`.
- Every time you edit the site, publish updates with:

```powershell
git add .
git commit -m "Update website content"
git push
```
