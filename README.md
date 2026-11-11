# barq-website

The website for [Barq (برق)](https://github.com/barq-lang/barq): static HTML, no build step.

| Page | |
|------|---|
| [index.html](index.html) | Marketing site |
| [docs/index.html](docs/index.html) | Documentation site |
| [admin/index.html](admin/index.html) | Admin dashboard (design) |

Open `index.html` in a browser, or serve the folder: `python3 -m http.server`.

## Design system

- Colours: Forest Green `#15803D` to Royal Blue `#4F46E5` gradient; the admin uses a light theme with a black sidebar.
- Fonts: Sora (headings), Inter (text), JetBrains Mono (code).
- The docs site uses the same tokens as the marketing site.

The language spec itself lives in the [barq repo's docs/](https://github.com/barq-lang/barq/tree/main/docs); this site presents it.

## Publishing

GitHub Pages works as is: Settings → Pages → deploy from the `main` branch, root folder.

## License

MIT
