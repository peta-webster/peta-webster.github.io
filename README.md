# Yi Zhang — Academic Homepage

English academic homepage for Yi Zhang (张毅), a Ph.D. student in the Department of Industrial Engineering at Tsinghua University.

This site uses the official static HTML edition of [Minimal Light](https://github.com/yaoyao-liu/minimal-light), based on upstream commit `1ea07f39518ac44644406380c83da6f89037c4fc`. The upstream license is preserved in `LICENSE`.

## Preview locally

From this directory, run:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open `http://127.0.0.1:8765`.

## Edit content

- `index.html`: personal information, research interests, project descriptions, and links.
- `assets/css/style.css`: the original compiled Minimal Light stylesheet, including automatic dark mode.
- `assets/css/custom.css`: small profile-specific spacing and accessibility adjustments.
- `assets/img/favicon.svg`: initials used as the site icon.
- `assets/img/avatar.png`: the template's default academic avatar; replace it with a personal portrait when available.

No sample publications, CV, analytics identifier, or custom domain from the template are included. Add publications and a CV when the corresponding materials are available. The GitHub profile icon uses the same Font Awesome stylesheet as the original template.

## Publish to GitHub Pages

Upload these files to the root of `peta-webster/peta-webster.github.io`. In **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/(root)**. The `.nojekyll` file enables publishing these static files without a Jekyll build.

Expected URL: `https://peta-webster.github.io/`.

The stylesheets currently load the template's Crimson Pro and Ubuntu Mono fonts from Google Fonts; a serif or monospace fallback is used when those fonts are unavailable.
