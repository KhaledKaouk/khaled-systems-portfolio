# Khaled Kaouk — Systems Engineering Portfolio

A responsive, static portfolio with a terminal-inspired visual style.

## Structure

```text
.
├── index.html
├── assets/
│   ├── style.css
│   ├── main.js
│   └── favicon.svg
└── projects/
    ├── sql-editor.html
    ├── server-labs.html
    ├── vim-ai.html
    ├── market-sim.html
    ├── freelance-platform.html
    └── travel-platform.html
```

## Run locally

No build step or package manager is required.

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Publish with GitHub Pages

1. Create a new **public** repository named `KhaledKaouk.github.io`.
2. Upload the contents of this folder (not the folder itself).
3. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
4. Wait for the site to publish at `https://KhaledKaouk.github.io`.

The portfolio repository is separate from your private project repositories. Do not add source code, credentials, customer information or private infrastructure details.

## Before publishing

- Replace or confirm contact details and social links in `index.html`.
- Add real screenshots or demo links only after checking that they contain no secrets or customer data.
- Replace each project's "Evidence to add" notes with verified details.
- Do not claim performance improvements, supported technologies or production usage without evidence.
- The current copy is intentionally conservative because detailed implementation facts have not yet been supplied.
