# example-cli-github-action-pull-request

[![Push](https://github.com/relative-ci/example-cli-github-action-pull-request/actions/workflows/push.yaml/badge.svg)](https://github.com/relative-ci/example-cli-github-action-pull-request/actions/workflows/push.yaml)
[![Pull Request](https://github.com/relative-ci/example-cli-github-action-pull-request/actions/workflows/pull-request.yaml/badge.svg)](https://github.com/relative-ci/example-cli-github-action-pull-request/actions/workflows/pull-request.yaml)
[![RelativeCI](https://badges.relative-ci.com/badges/42WyhptQLpAZMIjn4I39?branch=master)](https://app.relative-ci.com/projects/42WyhptQLpAZMIjn4I39)

> [@relative-ci/agent](https://github.com/relative-ci/agent) CLI setup example for [Github Action](https://github.com/features/actions) pull_request event


## Example app

Basic webpack setup:
- `Javascript`: babel with `@babel/preset-env` and `@babel/preset-react`
- `CSS`: `postcss`(`autoprefixer`, `cssnano`), `css-modules`, `mini-css-extract`
- assets:
  - `public`: `copy-webpack-plugin`
  - `src`: `file-loader`
  - `inline.svg`: - `svgr`
