# kevinomidvaran.com

Personal site. Plain static HTML + one CSS file, no build step, hosted on GitHub Pages
(`CNAME` → kevinomidvaran.com; deploys from the `master` branch).

- `index.html`: home (work, about, projects, beyond work, contact)
- `more-projects.html`: earlier projects
- `assets/css/style.css`: all styles; colors live in `:root` variables
- `assets/images/`: portrait (`portrait.jpg`), project screenshots, share image
- `portfolio_1.html`, `education.html`, `about.html`: redirects from old URLs. Keep them.
- `404.html`: GitHub Pages not-found page

Preview locally: `python3 -m http.server 8000`, then open http://localhost:8000
