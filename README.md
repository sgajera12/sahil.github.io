# Portfolio Site

Personal portfolio for GitHub Pages.

## Setup

1. Create a repo named `yourusername.github.io` on GitHub
2. Clone it locally: `git clone https://github.com/yourusername/yourusername.github.io.git`
3. Copy all these files into that repo folder
4. Push:
   ```
   git add .
   git commit -m "initial portfolio"
   git push origin main
   ```
5. Go to repo Settings > Pages and confirm source is set to `main` branch
6. Visit `https://yourusername.github.io` -- it may take 30-60 seconds to go live

## TODO before pushing

- Replace `yourusername` in all links (search the HTML files)
- Replace `your.email@wpi.edu` with your real email
- Add your resume PDF to `assets/resume.pdf`
- Fill in undergrad education details in `index.html`
- Optionally add project screenshots to `assets/` and reference them in the cards
- Update publication details in `research.html` when available

## File structure

```
.
├── index.html          # Home page (hero, about, skills, contact)
├── projects.html       # Projects page
├── research.html       # Research page
├── css/
│   └── style.css       # All styling
├── js/
│   └── script.js       # Scroll animations, mobile nav
├── assets/             # Images, resume PDF, screenshots
│   └── resume.pdf      # Your resume (add this)
└── README.md
```
