### This is a modified copy of the @blockly/dev-scripts package.
### It is modified to support the @mit-app-inventor/blockly-block-lexical-variables package.
### The most notable changes are:
### 1. The `blockly-scripts build` command now creates 4 bundles: core.js, blocks.js, generators.js and index.js
### 2. This modified package uses `yarn` workspaces so that users can reference this single package via a GitHub reference such as the following in a package.json file:
### `"@blockly/dev-scripts": "git@github.com/mit-cml/blockly-samples.git#commit=ba1d277599b38e1556f45a3d0296c31b0bd43951&workspace=@blockly/dev-scripts"`

## The following is the original README text:

# @blockly/dev-scripts [![Built on Blockly](https://tinyurl.com/built-on-blockly)](https://github.com/google/blockly)

This package includes scripts and configuration files used by Blockly plugins.

## Available Scripts

### `blockly-scripts start`

Runs the package in development mode.

Open [http://localhost:3000/test](http://localhost:3000/test) to view the test
playground in the browser. The page will reload if you make edits.

### `blockly-scripts build`

Builds the package into the `dist` directory.

### `blockly-scripts clean`

Deletes the `dist` and `build` directories if they exist.
