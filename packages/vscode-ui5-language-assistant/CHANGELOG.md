# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.1.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/v3.0.1...v3.1.0) (2021-10-10)

### Features

- add src/manifest.json path to jsonValidation ([#425](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/425)) ([f4aaf33](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/f4aaf333aeb17c1238747990e549edfa674830b6))

## [3.0.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/v3.0.0...v3.0.1) (2021-06-01)

**Note:** Version bump only for package vscode-ui5-language-assistant

# 3.0.0 (2021-06-01)

### Bug Fixes

- logging level scope changed, `resource`--> `window` ([a47abd0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/a47abd00c72a16a7cce960ddce4ad0a400c4c236))
- **vscode-ext:** more specific fileMatch patterns for manifest.json schema ([#297](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/297)) ([0eb9b6d](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/0eb9b6d205b9a1d12cf5559e6b1299e708b5819f))
- support namespace in aggregation name ([#150](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/150)) ([cff718b](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/cff718b4a2cfddc01cc5e44bd42eca68a8831832))
- **vscode-ui5-language-assistant:** full schema v1.19 ([#49](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/49)) ([b5592c3](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/b5592c307a86d72408463868b218ef60989c2ff0))

### Features

- add settings to include deprecated and experimental APIs ([#143](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/143)) ([fad2d9b](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/fad2d9b0c998fa2a1f3d8d4cd7ba8e997d24d30b))
- logging for language server ([#348](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/348)) ([7e2c30a](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/7e2c30a86cef9b239856dbef6df0f8785a210fc1))
- manifest.json state management ([#224](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/224)) ([da2682e](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/da2682e474ff13d42ad913a6c7e57bb65d546f66))
- non stable id quick fix ([#266](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/266)) ([c564db4](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/c564db4ed7a5ec9e026be0f10a72c734a366c3f7))
- set schema configuration for manifest.json ([#192](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/192)) ([7e7880a](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/7e7880af58a52f59241b956faa77f757a310b95f))
- suggest UI5 namespaces in xmlns attributes values ([#17](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/17)) ([46c84c4](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/46c84c4c5e2030fea255895a06cecbb5828fe31b))
- use github.com/sap/ui5-manifest schema ([#218](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/218)) ([ee8eef0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/ee8eef061f73ffac18ec9dee8dc119c11761e17b))

### Performance Improvements

- **language-server:** cache downloaded resources ([#50](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/50)) ([de8d7d5](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/de8d7d5e38c76666cc2590a885127b202096f289))

### Reverts

- remove Theia manifet.json via settings.json workaround ([#220](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/220)) ([4ca8eb9](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/4ca8eb92c509a78ccc1f6ea9acac76cccdbc4fee))

## [1.7.2](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.7.1...vscode-ui5-language-assistant@1.7.2) (2021-05-04)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.7.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.7.0...vscode-ui5-language-assistant@1.7.1) (2021-01-03)

### Bug Fixes

- logging level scope changed, `resource`--> `window` ([a47abd0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/a47abd00c72a16a7cce960ddce4ad0a400c4c236))

# [1.7.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.6.1...vscode-ui5-language-assistant@1.7.0) (2020-12-30)

### Features

- logging for language server ([#348](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/348)) ([7e2c30a](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/7e2c30a86cef9b239856dbef6df0f8785a210fc1))

## [1.6.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.6.0...vscode-ui5-language-assistant@1.6.1) (2020-08-27)

### Bug Fixes

- **vscode-ext:** more specific fileMatch patterns for manifest.json schema ([#297](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/297)) ([0eb9b6d](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/0eb9b6d205b9a1d12cf5559e6b1299e708b5819f))

# [1.6.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.5.1...vscode-ui5-language-assistant@1.6.0) (2020-08-12)

### Features

- non stable id quick fix ([#266](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/266)) ([c564db4](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/c564db4ed7a5ec9e026be0f10a72c734a366c3f7))

## [1.5.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.5.0...vscode-ui5-language-assistant@1.5.1) (2020-07-15)

**Note:** Version bump only for package vscode-ui5-language-assistant

# [1.5.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.4.1...vscode-ui5-language-assistant@1.5.0) (2020-07-08)

### Features

- manifest.json state management ([#224](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/224)) ([da2682e](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/da2682e474ff13d42ad913a6c7e57bb65d546f66))

## [1.4.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.4.0...vscode-ui5-language-assistant@1.4.1) (2020-07-02)

### Reverts

- remove Theia manifet.json via settings.json workaround ([#220](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/220)) ([4ca8eb9](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/4ca8eb92c509a78ccc1f6ea9acac76cccdbc4fee))

# [1.4.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.3.0...vscode-ui5-language-assistant@1.4.0) (2020-06-30)

### Features

- use github.com/sap/ui5-manifest schema ([#218](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/218)) ([ee8eef0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/ee8eef061f73ffac18ec9dee8dc119c11761e17b))

# [1.3.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.2.0...vscode-ui5-language-assistant@1.3.0) (2020-06-29)

### Features

- set schema configuration for manifest.json ([#192](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/192)) ([7e7880a](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/7e7880af58a52f59241b956faa77f757a310b95f))

# [1.2.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.8...vscode-ui5-language-assistant@1.2.0) (2020-06-17)

### Features

- add settings to include deprecated and experimental APIs ([#143](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/143)) ([fad2d9b](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/fad2d9b0c998fa2a1f3d8d4cd7ba8e997d24d30b))

## [1.1.8](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.7...vscode-ui5-language-assistant@1.1.8) (2020-06-03)

### Bug Fixes

- support namespace in aggregation name ([#150](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/150)) ([cff718b](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/cff718b4a2cfddc01cc5e44bd42eca68a8831832))

## [1.1.7](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.6...vscode-ui5-language-assistant@1.1.7) (2020-05-20)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.6](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.5...vscode-ui5-language-assistant@1.1.6) (2020-05-20)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.5](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.4...vscode-ui5-language-assistant@1.1.5) (2020-05-20)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.4](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.3...vscode-ui5-language-assistant@1.1.4) (2020-05-06)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.3](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.2...vscode-ui5-language-assistant@1.1.3) (2020-04-23)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.2](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.1...vscode-ui5-language-assistant@1.1.2) (2020-04-07)

**Note:** Version bump only for package vscode-ui5-language-assistant

## [1.1.1](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.1.0...vscode-ui5-language-assistant@1.1.1) (2020-04-07)

### Bug Fixes

- **vscode-ui5-language-assistant:** full schema v1.19 ([#49](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/49)) ([b5592c3](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/b5592c307a86d72408463868b218ef60989c2ff0))

### Performance Improvements

- **language-server:** cache downloaded resources ([#50](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/50)) ([de8d7d5](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/de8d7d5e38c76666cc2590a885127b202096f289))

# [1.1.0](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/compare/vscode-ui5-language-assistant@1.0.0...vscode-ui5-language-assistant@1.1.0) (2020-04-01)

### Features

- suggest UI5 namespaces in xmlns attributes values ([#17](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/issues/17)) ([46c84c4](https://github.com/sap/ui5-language-assistant/tree/master/packages/vscode-ui5-language-assistant/commit/46c84c4c5e2030fea255895a06cecbb5828fe31b))

# 1.0.0 (2020-03-31)

**Note:** Version bump only for package vscode-ui5-language-assistant
