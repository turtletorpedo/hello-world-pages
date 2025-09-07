# Hello World — GitHub Pages (Beginner friendly)

This is a minimal GitHub Pages starter site that shows "Hello, World!" and instructions to get you publishing quickly.

## Files included
- `index.html` — the page you'll see when visiting the site.
- `LICENSE` — MIT license (optional).
- `.nojekyll` — prevents GitHub Pages from using Jekyll processing.

## Quick publish (push-and-enable)
1. On GitHub, go to the repository → Settings → Pages (or "Pages" in the left sidebar).
2. Under "Build and deployment", set "Source" to branch `main` and folder `/(root)`, then click "Save".
3. Your site will be published at:

   https://turtletorpedo.github.io/hello-world-pages/

   (It may take a minute to appear.)

## Create locally and push (if you prefer)
1. Clone the repo:
   ```bash
   git clone https://github.com/turtletorpedo/hello-world-pages.git
   cd hello-world-pages
   ```
2. Copy the files into the repository root, then:
   ```bash
   git add .
   git commit -m "Add GitHub Pages hello world site"
   git push origin main
   ```

## Extras I can add
- A GitHub Actions workflow to publish from a branch (gh-pages).
- A `CNAME` file and DNS steps for a custom domain.
- Small content edits, images, or styling changes.

If you'd like me to make any edits before publishing, tell me which changes to make.