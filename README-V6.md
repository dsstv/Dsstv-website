# DSS TV V6 — One-click approval editor

Replace only `index.html` and `admin/index.html` in the root of your existing `dsstv/Dsstv-website` GitHub repository. Preserve `catalog.json`, poster files, banner and all other approved artwork already on GitHub. Do NOT upload this ZIP directly into the repo: extract it first.

Open https://dsstv.github.io/Dsstv-website/admin/ and enter your repository-scoped fine-grained token (Contents read/write). Load catalog, select or create drama, enter review and choose a poster, preview, then click Approve & Publish. The editor commits poster and catalog to GitHub using the GitHub API. GitHub Pages deploys automatically. Publishing is a two-commit sequence initiated by one button, not an atomic transaction: if the catalog step fails after a poster upload, retry safely after reloading.

This editor is a PUBLIC web page and is not password protected. Keep the token private, short-lived, and restricted to the one repository. Do not paste tokens into messages, screenshots, or files. The token is held in page memory only.

Existing entries with missing poster files still need approved images uploaded through the editor. The upgrade does not fabricate or replace any approved posters.
