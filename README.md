# MyAIAssistant landing

Static landing page (RU/EN switch) for GitHub Pages.

- `index.html` is the whole site.
- `assets/demo-ru.mp4`, `assets/demo-en.mp4`: demo videos.
- `assets/presentation-ru.pdf` and `assets/slides/`: client presentation (Russian).

## Before publishing

Replace `YOUR_BOT_NAME` in `index.html` (two links, `https://t.me/YOUR_BOT_NAME`) with the real bot username.

## Publish on GitHub Pages

1. Create a repository and push this folder to the `main` branch.
2. Repository Settings, Pages, Source: `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. The site opens at `https://<user>.github.io/<repo>/`. Add `#en` to the link to open the English version.
