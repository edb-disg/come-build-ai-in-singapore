# Come Build AI in Singapore

Dashboard of technical AI roles at companies hiring in Singapore, built by EDB for NeurIPS 2026 (Sydney, 6–12 December).

## Files

| File | What it is |
|---|---|
| `index.html` | The page layout (locked 14 Nov 2026) |
| `data.js` | All companies, roles, role types and company types. Edit this file to update the data. |
| `edb-logo.png` | EDB logo shown beside the title |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

## Publish on GitHub Pages

1. On GitHub, create a new **public** repository, for example `come-build-ai-in-singapore`.
2. Choose **Add file → Upload files**, drag in all four files above and commit to `main`.
3. Open **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the page is live at `https://edb-disg.github.io/come-build-ai-in-singapore/`.

## Updating the data

Replace `data.js` in the repository (Add file → Upload files) and commit. The page updates within a few minutes. The layout file does not need to change.

## Project notes

- Roles open to people based in Singapore are listed first; companies with none show their remote roles.
- Technical roles only, with titles as each company posts them.
- Roles at EDB key accounts marked "Checked" come from the daily key-account hiring tracker; others come from public job listings.
- Six role types (alphabetical) and thirteen company types, each defined in `data.js`.
