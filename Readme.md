# Extractor Webpack Plugin

[![NpmVersion](https://img.shields.io/npm/v/extractor-webpack-plugin.svg)](https://www.npmjs.com/package/extractor-webpack-plugin)

A plugin that executes the main compilation asset and allows you to emit more compilation assets.

## Install

```
npm i --save-dev extractor-webpack-plugin
```

```
yarn add --dev extractor-webpack-plugin
```

Be aware that this plugin will overwrite `output.filename` and `output.libraryTarget` of the webpack config.
Also be aware that if you use it together with babel you'll have to set `loose: true` and `modules. 'commonjs'` in your `.babelrc`-file.
