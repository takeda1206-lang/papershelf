# Papershelf

A personal single-file web app for keeping study HTML files on a private shelf.

- The app itself (this repo) contains no data — only generic code served via GitHub Pages.
- Documents and sticky notes live in a separate **private** repository, accessed from the browser through the GitHub API with a fine-grained personal access token stored locally on each device.
- Sticky notes are stored in `shelf.json` in the data repository; the HTML files themselves are never modified.
