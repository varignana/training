# Functional Path

A browser-based workout tracker, published with GitHub Pages.

**Live site:** https://varignana.github.io/training/

## Run it locally

This is a static website: it has no build step and no dependencies to install.

Open `index.html` in a browser to test it locally. For changes that depend on server behaviour later, use a local development server instead.

## Project structure

```text
index.html   The entire app: page structure, styles, and JavaScript behaviour
```

The app keeps workout data in the browser's local storage. The export/import controls let a user back up and restore that data.

## Development workflow

1. Create a small, named change (for example, `fix/timer-reset`).
2. Make the smallest change that solves the problem.
3. Test the affected behaviour locally.
4. Review the Git diff before saving it.
5. Commit the change with a clear message.
6. Push to GitHub and verify the GitHub Pages site.

Do not push changes directly to the public site until they have been reviewed and tested.


