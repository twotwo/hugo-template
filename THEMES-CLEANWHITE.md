# Hack CleanWhite

## Base Line

6eda4aa Jun 10, 2024

`hugo server --disableFastRender -D --contentDir themes/cleanwhite/exampleSite/content -t cleanwhite`

## Hack the Template

1. Fix Content Type: `grep post\" themes/cleanwhite/layouts/* -r`
2. Modify Font Family

Corresponding modified:
    modified:   themes/cleanwhite/layouts/_default/archive.html
    modified:   themes/cleanwhite/layouts/partials/category.html
    modified:   themes/cleanwhite/layouts/partials/portfolio.html
    modified:   themes/cleanwhite/static/css/hugo-theme-cleanwhite.min.css

## Launch Example Site

```bash
# Copy example site files
cp -r themes/cleanwhite/exampleSite/* .
# Lauch Server
hugo server --disableFastRender -D
```
