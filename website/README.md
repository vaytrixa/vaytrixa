# VAYTRIXA website

A React + Vite studio website.

## Run locally

Install Node.js 20 or later, then run `npm install` and `npm run dev`. Run `npm run build` to create the static site in `dist`.

## Publish free on GitHub Pages

1. Create a public repository on GitHub and upload the entire VAYTRIXA project folder, including the root `.github` folder and `website/package-lock.json`; exclude `node_modules` and `dist`.
2. In the repository, open **Settings → Pages**, and set **Build and deployment → Source** to **GitHub Actions**.
3. Push to the `main` branch. The included workflow builds and publishes the site. Check the Actions tab for its progress.
4. A repository named `<username>.github.io` is served at `https://<username>.github.io/`; other repositories use `https://<username>.github.io/<repository>/`. The relative asset paths support both.

The contact buttons open the visitor's email application addressed to vaytrixa@gmail.com. No form backend is required. Replace the project placeholder when there is real work ready to share.

## Project organization

- `src/`: React components and styles.
- `public/`: static website assets, including the favicon.
- `../logo/`: original supplied logo image. The website copy is `public/vaytrixa-logo.png`.
- `../.github/workflows/`: GitHub Pages deployment workflow.
- `dist/`: generated production build; recreated by `npm run build`.
- `node_modules/`: installed dependencies; recreated by `npm install`.
