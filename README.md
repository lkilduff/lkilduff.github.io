# Demography Portfolio — GitHub Pages Site

A clean, professional personal website for demographers. Built with plain HTML and CSS — no frameworks, no build tools, easy to customize.

## Quick start

### 1. Create a GitHub repository
- Go to [github.com](https://github.com) and create a new repository
- Name it `yourusername.github.io` (replace with your actual GitHub username)
- This special name tells GitHub to host it as your personal site

### 2. Upload the files
Either:
- Drag and drop `index.html` (and `resume.pdf` when ready) into the GitHub repository via the web UI
- Or clone the repo and push from your terminal:
  ```bash
  git clone https://github.com/yourusername/yourusername.github.io
  cp index.html yourusername.github.io/
  cd yourusername.github.io
  git add .
  git commit -m "Add portfolio site"
  git push
  ```

### 3. Enable GitHub Pages
- Go to your repository → Settings → Pages
- Under "Source", select `main` branch and `/ (root)` folder
- Click Save
- Your site will be live at `https://yourusername.github.io` in about a minute

---

## Customizing the site

Search for these placeholders and replace them throughout `index.html`:

| Placeholder | Replace with |
|---|---|
| `Your Name` | Your full name |
| `you@email.com` | Your email address |
| `yourusername` | Your GitHub username |
| `linkedin.com/in/yourusername` | Your LinkedIn URL |

### Sections to personalize

**Hero tagline** — Change the `<h1>` and bio paragraph to reflect your actual focus area (fertility, mortality, migration, health demography, etc.)

**About stats** — Update the three stat items (degree, projects, languages) with your real numbers

**About text** — Rewrite the three paragraphs to describe your actual background and interests

**Skills** — Remove tools you don't know, add ones you do. Keep `<span class="tag">Tool</span>` format.

**Projects** — Replace the four example projects with your real work. For each project card:
- Change the `href="#"` to a link to a GitHub repo, paper, or PDF
- Update the project type, title, description, and tool tags

**Contact** — Update the résumé link once you add `resume.pdf` to the repository

### Adding your résumé
Place a file named `resume.pdf` in the same folder as `index.html`. The download link is already wired up.

---

## File structure
```
yourusername.github.io/
├── index.html      ← your entire site (edit this)
├── resume.pdf      ← add your résumé here
└── README.md       ← this file
```

That's it — no dependencies, no npm, no build step.
