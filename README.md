# 8jo.tokyo LP migration

This repository is a static snapshot of `https://8jo.tokyo/` prepared for GitHub hosting.

## Contents

- `index.html`: exported top page
- `_nuxt/`: JS/CSS bundle required by the page
- `assets/`: image assets localized from the original host
- `CNAME`: custom domain setting for GitHub Pages
- `.nojekyll`: required so GitHub Pages serves `_nuxt/`

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Push this directory as the repository root.
3. In GitHub, open `Settings -> Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Select the branch and `/ (root)`.
6. Confirm the custom domain is `8jo.tokyo`.
7. Point the DNS records for `8jo.tokyo` to GitHub Pages if they are not already set.

## Notes

- This is a static migration of the current LP as of 2026-03-25.
- Some font resources remain external to keep the export small.
