# Stylelint browser bundle

Bundle stylelint and its dependencies into a single file, suitable for running in an environment without access to a file system.

The bundle exposes stylelint's Node API as a CommonJS module.

# Getting started

Using ES6:

```
import stylelintBrowserBundle from "stylelint-browser-bundle"
stylelintBrowserBundle(opts)
```

# How it works

Webpack is used to bundle stylelint and its dependencies into a single file. The build config ignores or replaces unnecessary and incompatible dependencies.
