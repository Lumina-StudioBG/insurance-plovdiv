# Застраховки Пловдив

A generic Bulgarian insurance brokerage demo for Plovdiv. Static HTML, CSS and JavaScript with six separate product pages, claims guidance and a Plovdiv city map.

No existing brokerage's telephone, street address, office hours, office photograph or Google Business profile is used. The illustrations and visual theme are retained. Contact details can be supplied by a future brokerage. Forms are local demonstrations and do not send requests.

## Preview

```sh
python -m http.server 8080 --directory dist
```

Website: https://alexandermarkovdev.github.io/insurance-plovdiv/

## Publish

Run `powershell.exe -NoProfile -ExecutionPolicy Bypass -File scripts/publish.ps1` to build the GitHub Pages copy, push the source to `main` and publish the prepared files to `gh-pages`. GitHub Pages serves that branch automatically. Authentication uses the signed-in GitHub CLI; no credentials are stored in this repository.

The original website and repository remain separate. This repository starts with a clean history containing only this generic demo.
