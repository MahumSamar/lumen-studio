# Lumen Studio

Static Lumen Studio prototype. The deployable site is in `public/`, with the font in `public/assets/`. The footer artwork (still image and looping video) is loaded directly from Higgsfield URLs.

To deploy updates from this folder:

```sh
npx wrangler pages deploy public --project-name lumen-studio --branch main
```
