# example-cli-github-action

[![ci](https://github.com/relative-ci/example-cli-github-action/workflows/ci/badge.svg)](https://github.com/relative-ci/example-cli-github-action/actions?query=workflow%3Aci)
[![RelativeCI](https://badges.relative-ci.com/badges/o1LoGhgroz0LFHx4sTuM?branch=master)](https://app.relative-ci.com/projects/o1LoGhgroz0LFHx4sTuM)

> [@relative-ci/agent](https://github.com/relative-ci/agent) CLI setup example for [Github Action](https://github.com/features/actions)


## Example app

Basic webpack setup:
- `Javascript`: babel with `@babel/preset-env` and `@babel/preset-react`
- `CSS`: `postcss`(`autoprefixer`, `cssnano`), `css-modules`, `mini-css-extract`
- assets:
  - `public`: `copy-webpack-plugin`
  - `src`: `file-loader`
  - `inline.svg`: - `svgr`
