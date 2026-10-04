# National Seniors Coalition — Website (one page)

The whole site is a single page: `index.html`, plus your logo in `images/logo.png`.
The menu (Home, Why Choose Us, About Us, Individual Plans, Contact Us) scrolls to each section.

## Putting it on GitHub Pages
1. Create a repository on GitHub.
2. Click **Add file → Upload files** and drag in `index.html`, the `images` folder, and the `docs` folder together. Commit.
3. Go to **Settings → Pages → Deploy from a branch → main / (root)** and save.
4. In a minute or two the site is live at `https://<your-username>.github.io/<repo-name>/`.
5. To use nationalseniors.com, enter it under **Settings → Pages → Custom domain** and follow GitHub's DNS instructions.

## Swapping in your own photos
The demo photos are free Pexels images loaded from pexels.com.
1. Upload your photo into the `images` folder (e.g. `images/hero.jpg`).
2. In `index.html`, find the `<img src="https://images.pexels.com/...">` you want to replace and change it to `src="images/hero.jpg"`.
There's a comment in the About Us section marking where a photo of Brad goes.

## Changing colors
Near the top of `index.html`, inside `<style>`, the first lines set the colors:
`--navy` (main), `--gold` (buttons), `--red` (accent lines and labels). Change a hex code there and it updates everywhere.

## Post-65 fact sheet
The PDF lives at `docs/post-65-retiree-plans.pdf` and its preview image at `images/post-65-preview.jpg`.
Upload the `docs` folder along with `index.html` and `images`. To swap in a newer fact sheet, upload it with the same file name.
