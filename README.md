# lomi-legal

Public hosting for legal documents of the [Lomi](https://github.com/BruckAssefa/lomi) dating app.

## Live URLs

- Landing: <https://bruckassefa.github.io/lomi-legal/>
- Privacy Policy: <https://bruckassefa.github.io/lomi-legal/privacy/>
- Terms of Service: <https://bruckassefa.github.io/lomi-legal/terms/>

These URLs are referenced from inside the Lomi app (Help & Support screen) and from the App Store listing.

## How it works

GitHub Pages serves the contents of this repo's `main` branch via Jekyll using the `jekyll-theme-minimal` theme. Each `.md` file uses front-matter `permalink:` to give it a clean URL.

## Updating the legal text

1. Edit `privacy.md` or `terms.md`
2. Update the **Effective date** and **Last updated** at the top
3. Commit and push to `main`
4. GitHub Pages rebuilds within ~1 minute

Keep these files in sync with `PRIVACY_POLICY.md` and `TERMS_OF_SERVICE.md` in the private `lomi` app repo.

## Contact

`lomiteam@outlook.com`
