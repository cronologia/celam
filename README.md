# CELAM — Cronologia

A compiled static website documenting the chronology of **CELAM** (Consejo
Episcopal Latinoamericano y Caribeño, founded 1955) as an **institution**:
founding, General Conferences and Assemblies, presidencies, structures and
reforms. Interpretation disputes live in the sibling
[`tl`](https://github.com/cronologia/tl) project.

Part of the [Cronologia](https://cronologia.github.io) family; built from the
[`core`](https://github.com/cronologia/core) template. Single JSON source of
truth (`data/chronology.json`), zero-dependency build, GitHub Pages.

```bash
node scripts/validate-data.js && node --test && node build.js
```

Publish: Settings → Pages → GitHub Actions + Actions variable
`ENABLE_PAGES=true` (with `main` as default). [MIT](LICENSE).
