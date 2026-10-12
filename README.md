# HYF Presentations

Workshop presentations for HackYourFuture, hosted on GitHub Pages.

- [All presentations](https://vadimtofan.github.io/HYF-Presentations/)
- [Intro to JavaScript · Week 1](https://vadimtofan.github.io/HYF-Presentations/intro-to-javascript-week1/)
- [Intro to JavaScript · Week 2](https://vadimtofan.github.io/HYF-Presentations/intro-to-javascript-week2/)

Each presentation has its own folder containing an `index.html` entry page.
Keep images and other presentation assets in that same folder and reference
them with relative paths.

## Add a presentation

1. Create a folder named for the presentation, such as
   `intro-to-javascript-week2/`.
2. Place the presentation HTML inside that folder as `index.html`.
3. Add a link to the root `index.html` presentation list, using the relative
   folder path, such as `intro-to-javascript-week2/`.
4. Commit and push the changes to `main`. GitHub Pages automatically deploys
   from the repository root on that branch.
5. Check that the **pages build and deployment** workflow succeeds, then open
   the new presentation URL.

For Week 2, the URL will be:
`https://vadimtofan.github.io/HYF-Presentations/intro-to-javascript-week2/`.

The root `.nojekyll` file lets GitHub Pages publish the static files directly.
No package installation or custom build step is needed.
