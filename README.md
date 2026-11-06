# Mohammad Hosseini — academic research website

A single-page academic website built with static HTML and CSS. The portrait was supplied by the owner.

Website: https://mohamad-hoseini.github.io/

## Update the site

- Edit the introduction, research summaries, publications and contact details in `docs/index.html`.
- Change typography, colors and mobile layout in `docs/styles.css`.
- Replace `docs/assets/Mohammad_Hosseini_CV_Public.pdf` to update the downloadable CV without changing the links.
- Commit and push changes to `main`. GitHub Pages republishes the site automatically.

Use the CV as the source of truth and distinguish submitted work from accepted publications. The public PDF excludes the personal phone number and uses the owner's approved broad description of ongoing intracranial foundation-model research. Personal CVs, editable CV sources and review files are not included in this repository.

## Local preview

```powershell
python -m http.server 4388 --bind 127.0.0.1 --directory docs
```

Open http://127.0.0.1:4388/. Stop the server with Ctrl+C.

## Hosting

GitHub Pages is configured to deploy from branch `main`, folder `/docs`. Keep `docs/.nojekyll` so GitHub serves the static files directly. No build tools or package installation are required.

After updates, check the live page and CV download.
