# .NET Ecosystem Review

[**LIVE**](https://tomashubelbauer.github.io/net-ecosystem-review)

![](https://github.com/tomashubelbauer/net-ecosystem-review/workflows/.github/workflows/main.yml/badge.svg)

This repository collects a leaderboard of .NET repositories on GitHub with over
1000 stars.

Also check out my other ecosystem reviews:

- [JavaScript ecosystem review](https://github.com/TomasHubelbauer/js-ecosystem-review)
- [TypeScript ecosystem review](https://github.com/TomasHubelbauer/ts-ecosystem-review)
- [Node ecosystem review](https://github.com/TomasHubelbauer/npm-ecosystem-review)

## Running

```sh
# Serve the `data/` route handled by `proxy` in `package.json` of `cra`
cd docs
npx serve .
```

```sh
cd cra
npm start
```

## To-Do

Provide another view with a chart showing stars of each project on a line chart.

Load notes for each item from README.md by parsing it and looking for headers
which match the item name. This way I can keep the notes in prose but also have
them show up in the web app.

Display another chart which is not total but a change record-to-record.
