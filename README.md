# Zeyang Xue — Academic Website

Personal academic website hosted on GitHub Pages.

## File Structure

```
├── index.html        Main (and only) webpage
├── bu-logo.png       Boston University logo shown in the header
├── assets/
│   ├── photo.jpg     Your headshot (YOU ADD THIS)
│   └── cv.pdf        Your CV PDF  (YOU ADD THIS)
└── README.md         This file
```

## Setup Instructions

1. **Create the GitHub repo**
   - Go to github.com → New Repository
   - Name it exactly `<your-username>.github.io` (e.g. `zeyangxue.github.io`)
   - Set it to **Public**

2. **Add your files**
   - Drop your headshot into `assets/` as `photo.jpg`
   - Drop your CV into `assets/` as `cv.pdf`
   - If the filenames differ, update the references in `index.html`

3. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - Go to repo Settings → Pages
   - Source: Deploy from branch → `main` → `/ (root)`
   - Save. Your site will be live at `https://<your-username>.github.io` within a minute.

## Customization Checklist

- [ ] Add headshot → `assets/photo.jpg`
- [ ] Add CV → `assets/cv.pdf`
- [ ] Update Google Scholar link in `index.html`
- [ ] Update LinkedIn link in `index.html`
- [ ] Replace placeholder abstracts with real ones
- [ ] Add paper links (SSRN, journal DOIs)
- [ ] Edit bio paragraph (interests, personal details)
- [ ] Optional: add a `CNAME` file if using a custom domain
