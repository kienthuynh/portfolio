# Personal website

A single static HTML page. No dependencies or build step.

## Content

Edit `index.html` to update the name, description, and links.
Replace `resume.pdf` beside `index.html` whenever you update your resume.

## Preview

Open `index.html` in a browser, or run this command from the repository:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## GitHub Pages

1. Commit and push these files to `main`.
2. In the repository's **Settings > Pages**, select **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.

The default project URL will be <https://kienthuynh.github.io/portfolio/>.
The `.nojekyll` file tells GitHub Pages to serve the files without Jekyll processing.

See [GitHub's publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
