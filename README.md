# Stylelint browser bundle

Bundle stylelint and its dependencies into a single file, suitable for running in a browser environment.

The bundle exposes stylelint's Node API as a global function `StylelintBrowserBundle()`.

# Getting started

- Include the bundle in an html page `<script  src="dist/stylelint-browser-bundle.js"></script>`

- Call `StylelintBrowserBundle()`


# How it works

Webpack is used to bundle stylelint and its dependencies into a single file. The build config ignores or replaces unnecessary and incompatible dependencies.
