# Landing Page

This repository contains a static Tailwind CSS landing page ready to be deployed to **GitHub Pages**. All of the assets and the `index.html` file now live at the repository root so GitHub Pages can serve them directly.

## Project structure

- `index.html` – single-page landing experience powered by the Tailwind CDN.
- `hero.png` – hero illustration referenced by the page.
- `LICENSE` – MIT license from the original template.

## Preview locally

You can open `index.html` directly in your browser, or serve it with a simple local server:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push the repository to GitHub.
2. In your repository settings, open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Set **Branch** to `main` (or your default branch) and **Folder** to `/ (root)`.
5. Save. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`.

If you use a custom domain, add your DNS records and configure it in the same **Pages** settings panel.

## Customization

- Update copy, colors, and CTA links in `index.html`.
- Replace `hero.png` with your own asset (keep the filename or update the `src` in the HTML).
- Tailwind is loaded from the CDN; if you need a custom build, swap the stylesheet link for your generated file.

## Image attribution

[Hero vector created by freepik.com](https://www.freepik.com/free-vector/isometric-education-illustration_3940819.htm#page=1&query=isometric%20plane&position=1).

## License

Copyright 2018-2022 Astrava.Solutions Ltd. Code released under the MIT license.
