# clark515.github.io

Personal notes & blog — built with [VitePress](https://vitepress.dev/).

Live site: <https://clark515.github.io>

## Local development

```bash
npm install
npm run dev       # preview at http://localhost:5173
npm run build     # build into docs/.vitepress/dist
```

## Deploy

Auto-deployed via GitHub Actions on push to `master` / `main`. See [.github/workflows/deploy.yml](.github/workflows/deploy.yml).

## Structure

```
docs/
├── .vitepress/
│   └── config.mts      # site config
├── index.md            # home
├── about.md            # about page
└── posts/              # articles
    ├── index.md
    └── YYYY-MM-DD-<slug>.md
```

## License

Content © Clark. Code MIT.
