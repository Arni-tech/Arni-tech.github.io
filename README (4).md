# Deploying your portfolio (free, via GitHub Pages)

1. Create a new repo on GitHub, e.g. `arnav-negi.github.io` (using this exact
   name — `<your-username>.github.io` — gives you the shortest possible free
   URL) or any other name like `portfolio`.
2. Add `index.html` to the root of that repo (drag-and-drop upload works fine,
   or `git add`, `git commit`, `git push`).
3. Optional: add your résumé PDF to the same folder, named exactly
   `Arnav_Negi_Resume.pdf` — the "Download résumé" button already links to
   that filename.
4. In the repo, go to **Settings → Pages**, set the source branch to `main`
   (root folder), and save.
5. Your site goes live within a minute or two at either:
   - `https://<your-username>.github.io` (if you used the special repo name), or
   - `https://<your-username>.github.io/<repo-name>` (for any other repo name)

No build step, no framework, no cost — it's a single static HTML file.

## Making small edits later
Everything — copy, colors, layout — lives in the one `index.html` file.
Colors and fonts are defined as CSS variables near the top of the `<style>`
block (`--bg`, `--coral`, `--teal`, etc.) if you want to retheme without
hunting through the whole file.
