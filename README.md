# GitHub Pages: Angular

A starter Angular 15 app used to try out deploying Angular to GitHub Pages.

**Live site:** https://ghorbel37.github.io/gh-pages-ng/

## How it's deployed

GitHub Pages serves the `docs/` folder of the `main` branch. The app is built with the repository name as base path, and the build output is placed in `docs/`:

```bash
npm install
ng build --base-href /gh-pages-ng/
```

Then copy the contents of `dist/my-app-ng/` into `docs/` and push. GitHub Pages publishes the new version automatically.

## Run locally

```bash
ng serve
```

Then open `http://localhost:4200/`.

## Related experiments

- [gh-pages-html-test](https://github.com/Ghorbel37/gh-pages-html-test): the same with plain HTML
- [gh-pages-react](https://github.com/Ghorbel37/gh-pages-react): the same with a React + Vite app
