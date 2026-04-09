
# Tailoring Guide

This site is plain static HTML, so you can edit it with VS Code, Notepad, or GitHub's web editor.

## Main files
- `index.html` → About / homepage
- `research.html` → Research page
- `teaching.html` → Teaching page
- `cv.html` → CV page
- `assets/css/style.css` → colors, fonts, spacing, layout
- `images/profile.png` → your headshot
- `files/Zeyang_Xue_CV.pdf` → your CV PDF

## Most common edits

### 1. Change the homepage bio
Open `index.html` and edit the text inside the `<section class="hero">` and the `<section class="section">` below it.

### 2. Add or remove research projects
Open `research.html`.
Copy one `<article class="card">...</article>` block and change the title and description.

### 3. Update teaching later
Open `teaching.html` and replace the placeholder cards with courses, TA roles, or a teaching statement.

### 4. Replace your photo
Overwrite `images/profile.png` with your own file using the same filename.

### 5. Replace your CV
Overwrite `files/Zeyang_Xue_CV.pdf` with your real CV using the same filename.

### 6. Change colors or spacing
Open `assets/css/style.css`.
The easiest values to change are near the top:
- `--accent` for link/button color
- `--accent-2` for hover color
- `--text` for body text color
- `--max` for page width

## GitHub Pages setup
Upload the contents of this folder to the root of your repository.
In GitHub Pages settings, use:
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Important
Do not upload the outer folder itself. The repo root should directly contain:
- `index.html`
- `research.html`
- `teaching.html`
- `cv.html`
- `404.html`
- `assets/`
- `images/`
- `files/`
- `.nojekyll`
