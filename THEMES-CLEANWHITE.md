# Hack CleanWhite

## Base Line

6eda4aa Jun 10, 2024

`hugo server --disableFastRender -D --contentDir themes/cleanwhite/exampleSite/content -t cleanwhite`

## Hack the Template

    modified:   themes/cleanwhite/layouts/_default/archive.html
    modified:   themes/cleanwhite/layouts/partials/category.html
    modified:   themes/cleanwhite/layouts/partials/portfolio.html
    modified:   themes/cleanwhite/static/css/hugo-theme-cleanwhite.min.css

### Fix Content Type

`grep post\" themes/cleanwhite/layouts/* -r`

### Modify Font Family

### Launch Server

`hugo server --disableFastRender -D --config clean-white.yaml`
