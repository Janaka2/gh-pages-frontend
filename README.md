# GitHub Pages Frontend

Static site that calls your Hugging Face backend.

## Configure

- When testing locally, paste your backend URL into the input:
  `https://your-username-your-space-name.hf.space`

- For production, you can hardcode the backend URL in the JS if you prefer and remove the input.

## Enable GitHub Pages

Repo → Settings → Pages →
- Source: **Deploy from a branch**
- Branch: **main** (or `gh-pages`), Folder: **/** (root)
Save and wait for the green checkmark. Your site will be served at:
`https://<your-username>.github.io/<this-repo>/`
