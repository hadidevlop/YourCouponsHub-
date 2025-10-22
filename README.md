# YourCouponsHub

This repository contains the static production build of the YourCouponsHub landing page. The bundle lives entirely under the project root so it can be hosted from any subdirectory without breaking asset links.

## Local preview

Use any static file server to preview the site locally:

```bash
npx serve .
```

The `index.html` file references the compiled CSS and JavaScript with relative `./assets/...` paths, so the site renders correctly whether it is served from the domain root or a nested preview URL.

