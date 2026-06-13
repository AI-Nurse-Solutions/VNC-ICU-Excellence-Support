# Excellence Support Committee — VNC ICU

The website for the **Excellence Support Committee**, the backbone of shared governance in the VNC ICU. It presents the committee's mission, vision, and approach, and delivers the three-module onboarding program as short text-and-graphics pages.

🔗 **Live site (once published):** `https://<your-username>.github.io/<repo-name>/`

## What's inside

| File | Purpose |
|------|---------|
| `index.html` | Landing page — mission, vision, approach, and program overview |
| `module-1.html` | Module 1 · Foundational Alignment |
| `module-2.html` | Module 2 · Empowering Agency Through Collaboration |
| `module-3.html` | Module 3 · Facilitative Guidance & Collaborative Planning |
| `assets/styles.css` | Shared "clinical & calm" design system |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

The site is fully static — plain HTML and CSS with inline SVG graphics. No build step, no dependencies.

## View locally

Just open `index.html` in any browser, or run a tiny local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Publish to GitHub Pages

From this folder:

```bash
# 1. create the repo on GitHub first (empty, no README), then:
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

Then on GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / root → Save.** Your site goes live at the URL above within a minute or two.

## Editing content

All copy lives directly in the HTML files. To change the look, edit the CSS variables at the top of `assets/styles.css` (colors, spacing, fonts).

---

*Equip · Guide · Elevate.*
