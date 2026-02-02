# Contributing

This list is generated from YAML. **Do not edit `README.md` directly.**

## How to contribute

1. **Add or edit entries** in `data/`. One file per item; filename = slug (e.g. `adala.yml`).
2. **Categories** are in `meta/categories.yml`. Use `main_category: open-source` or `closed-source`.
3. **CI** runs [alternbits/opendata](https://github.com/alternbits/opendata) on push/PR. The action validates and compiles; CI will auto-commit the generated README when it changes.
4. Ensure alphabetical order is maintained when adding new entries.

## Data file (`data/{slug}.yml`)

Required: **name**, **slug** (match filename), **url**, **oneliner**, **main_category**.  
Optional: description, position, categories, date_added, date_modified, review.

## Full docs

Data format, meta options, badges, footer: [alternbits/opendata CONTRIBUTING](https://github.com/alternbits/opendata/blob/main/CONTRIBUTING.md).
