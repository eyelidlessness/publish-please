# Publish, please!
Safe and highly functional replacement for `npm publish`.

[![Build Status](https://travis-ci.org/inikulin/publish-please.svg?branch=master)](https://travis-ci.org/inikulin/publish-please)
[![npm version](https://img.shields.io/npm/v/publish-please.svg)](https://www.npmjs.com/package/publish-please)
[![Dependency Status](https://david-dm.org/inikulin/publish-please.svg)](https://david-dm.org/inikulin/publish-please)


## Validate your package before publishing to the registry

There are numerous ways to "shoot yourself in the foot" using `npm publish`. 

`publish-please` enables you to check that what will be sent to the registry is valid, free of vulnerabilities and free of useless files.

Before running `npm publish`,  run this command at the root of your project folder:

```sh
npx publish-please --dry-run
```

This example shows up that you are about to push your test files to the registry:

![dry-run-demo-with-errors](media/dry-run-with-errors.gif)

[to be continued]