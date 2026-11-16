# Peter Muchai's portfolio

An accessible portfolio introducing Peter Muchai as an engineer. The complete five-paragraph work narrative lives here; the separate GitHub profile README contains only a short introduction and grouped technology badges. The portfolio includes an avatar sidebar, professional links and the approved narrative, without project listings or timelines.

The README presentation is inspired by [Baobear520](https://github.com/Baobear520), and the sidebar summary by [daria-stanilevici](https://github.com/daria-stanilevici). This is an independent profile, not a copy of their text. Light/dark themes, responsive layouts and reduced-motion preferences are supported.

**Site:** https://pmuchai.github.io

## Local preview

From this directory:

```powershell
python -m http.server 8080 --bind 127.0.0.1
```

Open http://127.0.0.1:8080. No build, packages, analytics, fonts or external scripts are required. The avatar and Shields.io badge images are embedded, so the website does not make runtime image requests. The GitHub README uses the standard hosted Shields.io badges.

## Publish

Enable GitHub Pages from **Settings > Pages > Deploy from a branch > main > / (root)**.

The `.nojekyll` file serves the site directly. The publishing helper in the parent delivery folder creates the profile/site repositories and enables this setting.

## Edit

Update the narrative in `index.html` and keep the profile README in sync. Sidebar values are recorded in the parent folder's `Profile-settings.json`; update the website and GitHub account settings to match. The site respects system color preference, supports manual theme switching, and works without JavaScript.

Keep the profile grounded in the CV and verified experience. Do not add internal documents, private contact details from the source CV, nonpublic operational metrics or unsupported claims. The CV itself is not included in this site.
