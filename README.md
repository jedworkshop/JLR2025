# JLR2025

https://jedworkshop.github.io/JLR2025

Source of the "NLP2025 Workshop on Japanese Language Resources" website.

## How to edit

- Setup
  - `npm install`
- Edit
  - Edit the markdown file `src/index.md`
- Build
  - `npm run build`
  - => Static files created under `docs/`
- Publish  
  - Push to the `main` branch of this repository
  - => Files under `docs/` served as https://jedworkshop.github.io/JLR202 by GitHub Pages

## GitHub Actions

`Actions` -> `Workflows` "Deploy eleventy with GitHub Pages" -> `Run workflow`
で`src`内ファイルを`docs`に変換しつつ、GitHub Pagesを更新する。

## Dependencies

- [11ty/eleventy](https://github.com/11ty/eleventy)
- [sindresorhus/modern-normalize](https://github.com/sindresorhus/modern-normalize)
