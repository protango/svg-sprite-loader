# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="6.0.7"></a>
## [6.0.7](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.6...v6.0.7) (2021-05-28)


### Bug Fixes

* **utils:** Account for rule property "generator" ([#454](https://github.com/JetBrains/svg-sprite-loader/issues/454)) ([9fc86f1](https://github.com/JetBrains/svg-sprite-loader/commit/9fc86f1)), closes [#428](https://github.com/JetBrains/svg-sprite-loader/issues/428) [vuejs/vue-loader#1753](https://github.com/vuejs/vue-loader/issues/1753)



<a name="6.0.6"></a>
## [6.0.6](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.5...v6.0.6) (2021-04-23)


### Bug Fixes

* **utils:** use webpack object version if package can't be required ([f4b82c2](https://github.com/JetBrains/svg-sprite-loader/commit/f4b82c2))



<a name="6.0.5"></a>
## [6.0.5](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.4...v6.0.5) (2021-04-10)


### Bug Fixes

* **utils:** use moduleGraph in is-module-should-be-extracted.js ([6099812](https://github.com/JetBrains/svg-sprite-loader/commit/6099812))



<a name="6.0.4"></a>
## [6.0.4](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.3...v6.0.4) (2021-04-10)


### Bug Fixes

* **utils:** NormalModule for webpack 5 ([00886bc](https://github.com/JetBrains/svg-sprite-loader/commit/00886bc))



<a name="6.0.3"></a>
## [6.0.3](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.2...v6.0.3) (2021-04-10)


### Bug Fixes

* **utils:** fix 'Properties descriptionData are unknown' with webpack5 ([5a4fc6a](https://github.com/JetBrains/svg-sprite-loader/commit/5a4fc6a))
* **utils:** use moduleGraph and chunkGraph if possible ([9e25d18](https://github.com/JetBrains/svg-sprite-loader/commit/9e25d18))



<a name="6.0.2"></a>
## [6.0.2](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.1...v6.0.2) (2021-03-18)



<a name="6.0.1"></a>
## [6.0.1](https://github.com/JetBrains/svg-sprite-loader/compare/v6.0.0...v6.0.1) (2021-03-18)



<a name="6.0.0"></a>
# [6.0.0](https://github.com/JetBrains/svg-sprite-loader/compare/v5.2.1...v6.0.0) (2021-03-13)


### Bug Fixes

* **additional-assets:** adds missing method ([8db9c4d](https://github.com/JetBrains/svg-sprite-loader/commit/8db9c4d))
* **loader:** get rid of webpack--version ([54a0c6b](https://github.com/JetBrains/svg-sprite-loader/commit/54a0c6b)), closes [#437](https://github.com/JetBrains/svg-sprite-loader/issues/437) [#417](https://github.com/JetBrains/svg-sprite-loader/issues/417)


### BREAKING CHANGES

* **loader:** delete get-webpack-version.js



<a name="5.2.1"></a>
## [5.2.1](https://github.com/JetBrains/svg-sprite-loader/compare/v5.2.0...v5.2.1) (2020-12-14)



<a name="5.2.0"></a>
# [5.2.0](https://github.com/JetBrains/svg-sprite-loader/compare/v5.1.1...v5.2.0) (2020-12-14)


### Features

* update-dependency ([d93c5cf](https://github.com/JetBrains/svg-sprite-loader/commit/d93c5cf))



<a name="5.1.1"></a>
## [5.1.1](https://github.com/JetBrains/svg-sprite-loader/compare/v5.1.0...v5.1.1) (2020-12-05)



<a name="5.1.0"></a>
# [5.1.0](https://github.com/JetBrains/svg-sprite-loader/compare/v5.0.0...v5.1.0) (2020-12-05)


### Features

* add support for webpack5 ([b34b2b2](https://github.com/JetBrains/svg-sprite-loader/commit/b34b2b2))
* nodejs update ([00f4fc2](https://github.com/JetBrains/svg-sprite-loader/commit/00f4fc2))



<a name="5.0.0"></a>
# [5.0.0](https://github.com/JetBrains/svg-sprite-loader/compare/v4.3.0...v5.0.0) (2020-05-11)


### Bug Fixes

* pass proper context param to runtime generator ([c084ec7](https://github.com/JetBrains/svg-sprite-loader/commit/c084ec7)), closes [#186](https://github.com/JetBrains/svg-sprite-loader/issues/186)


### BREAKING CHANGES

* Possible breaks third-party runtime generators. Earlier `context` param was containing _path to compilation root context_, e.g. folder where webpack compilation occurs. This is wrong behaviour, because meaning of this param is a _folder where svg image is located_. So it was changed in this commit.
If your custom runtime generator breaks after this update use `loaderContext.rootContext` option instead of `context`.



<a name="4.3.0"></a>
# [4.3.0](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.7...v4.3.0) (2020-05-03)


### Features

* **outputPath:** add possibility to define output path ([2c7eceb](https://github.com/JetBrains/svg-sprite-loader/commit/2c7eceb))



<a name="4.2.7"></a>
## [4.2.7](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.6...v4.2.7) (2020-04-28)


### Bug Fixes

* move `mask` & `clipPath` elements outside symbol ([ae70786](https://github.com/JetBrains/svg-sprite-loader/commit/ae70786)), closes [#325](https://github.com/JetBrains/svg-sprite-loader/issues/325)



<a name="4.2.6"></a>
## [4.2.6](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.5...v4.2.6) (2020-04-26)



### Bug Fixes

* drop webpack version detector ([7131578](https://github.com/JetBrains/svg-sprite-loader/commit/7131578))



<a name="4.2.5"></a>
## [4.2.5](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.4...v4.2.5) (2020-04-12)


### Bug Fixes

* refers to transpiled code in svg-baker-runtime ([65ece05](https://github.com/JetBrains/svg-sprite-loader/commit/65ece05)), closes [#385](https://github.com/JetBrains/svg-sprite-loader/issues/385)



<a name="4.2.4"></a>
## [4.2.4](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.3...v4.2.4) (2020-04-12)


### Bug Fixes

* don't create additional chunk for sprite ([80ebfa3](https://github.com/JetBrains/svg-sprite-loader/commit/80ebfa3)), closes [#364](https://github.com/JetBrains/svg-sprite-loader/issues/364)



<a name="4.2.3"></a>
## [4.2.3](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.2...v4.2.3) (2020-04-08)


### Bug Fixes

* check properly when window.angular properly ([1c76824](https://github.com/JetBrains/svg-sprite-loader/commit/1c76824))



<a name="4.2.2"></a>
## [4.2.2](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.1...v4.2.2) (2020-04-02)


### Bug Fixes

* add aria-hidden attribute to sprite node for proper accessibility behaviour ([bb08665](https://github.com/JetBrains/svg-sprite-loader/commit/bb08665)), closes [#315](https://github.com/JetBrains/svg-sprite-loader/issues/315)



<a name="4.2.1"></a>
## [4.2.1](https://github.com/JetBrains/svg-sprite-loader/compare/v4.2.0...v4.2.1) (2020-01-31)


### Bug Fixes

* drop npm-shrinkwrap.json due to it causes installation of old dependencies when npm is used ([7439e61](https://github.com/JetBrains/svg-sprite-loader/commit/7439e61)), closes [#378](https://github.com/JetBrains/svg-sprite-loader/issues/378) [#379](https://github.com/JetBrains/svg-sprite-loader/issues/379)



<a name="4.2.0"></a>
# [4.2.0](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.6...v4.2.0) (2020-01-24)


### Bug Fixes

* get-webpack-version.js ([6508469](https://github.com/JetBrains/svg-sprite-loader/commit/6508469))


### Features

* add clipPath & mask to "move-from-symbol-to-root" transform defaults ([02d0c33](https://github.com/JetBrains/svg-sprite-loader/commit/02d0c33)), closes [#288](https://github.com/JetBrains/svg-sprite-loader/issues/288) [#325](https://github.com/JetBrains/svg-sprite-loader/issues/325)



<a name="4.1.6"></a>
## [4.1.6](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.5...v4.1.6) (2019-04-27)


### Bug Fixes

* incorrect items order after sorting ([ded8146](https://github.com/JetBrains/svg-sprite-loader/commit/ded8146))



<a name="4.1.5"></a>
## [4.1.5](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.4...v4.1.5) (2019-04-27)


### Bug Fixes

* replace all instances of urls in attribute ([d6fdf94](https://github.com/JetBrains/svg-sprite-loader/commit/d6fdf94)), closes [#300](https://github.com/JetBrains/svg-sprite-loader/issues/300)



<a name="4.1.4"></a>
## [4.1.4](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.3...v4.1.4) (2019-04-27)


### Bug Fixes

* incorrect detection webpack version, closes [#309](https://github.com/JetBrains/svg-sprite-loader/issues/309)
* Fix the bug of publicPath, closes  [#311](https://github.com/JetBrains/svg-sprite-loader/issues/311)
* **configuration** make possible to use `oneOf` in loader rules
* **configuration:** make default config work with yarn PnP ([dc931e2](https://github.com/JetBrains/svg-sprite-loader/commit/dc931e2))
* **runtime-generator:** fix module not found errors for custom spriteModule or symbolModule ([44bbcfe](https://github.com/JetBrains/svg-sprite-loader/commit/44bbcfe))



<a name="4.1.3"></a>
## [4.1.3](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.2...v4.1.3) (2018-10-29)


### Bug Fixes

* update svg-baker to fix security vulnerability ([4408ccd](https://github.com/JetBrains/svg-sprite-loader/commit/4408ccd))



<a name="4.1.2"></a>
## [4.1.2](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.1...v4.1.2) (2018-09-28)


### Bug Fixes

* drop webpack dependency ([6254f9c](https://github.com/JetBrains/svg-sprite-loader/commit/6254f9c))



<a name="4.1.1"></a>
## [4.1.1](https://github.com/JetBrains/svg-sprite-loader/compare/v4.1.0...v4.1.1) (2018-09-19)


### Bug Fixes

* interpolate publicPath properly ([22f10e6](https://github.com/JetBrains/svg-sprite-loader/commit/22f10e6))



<a name="4.1.0"></a>
# [4.1.0](https://github.com/JetBrains/svg-sprite-loader/compare/v4.0.0...v4.1.0) (2018-09-19)


### Features

* add ARIA attrs to whitelist symbol attributes ([4bbccab](https://github.com/JetBrains/svg-sprite-loader/commit/4bbccab)), closes [#304](https://github.com/JetBrains/svg-sprite-loader/issues/304)



<a name="4.0.0"></a>
# [4.0.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.9.0...v4.0.0) (2018-09-19)



<a name="3.9.0"></a>
# [3.9.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.8.0...v3.9.0) (2018-05-26)


### Features

* support symbol id interpolator as function ([3691d86](https://github.com/JetBrains/svg-sprite-loader/commit/3691d86))



<a name="3.8.0"></a>
# [3.8.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.7.3...v3.8.0) (2018-05-26)


### Bug Fixes

* error link in pr template ([7b6cf30](https://github.com/JetBrains/svg-sprite-loader/commit/7b6cf30))


### Features

* support `publicPath` option ([793a7bf](https://github.com/JetBrains/svg-sprite-loader/commit/793a7bf))
* support custom outputPath ([80f7520](https://github.com/JetBrains/svg-sprite-loader/commit/80f7520))



<a name="3.7.3"></a>
## [3.7.3](https://github.com/JetBrains/svg-sprite-loader/compare/v3.7.2...v3.7.3) (2018-03-19)


### Bug Fixes

* **utils:** fix linting errors ([f5239a0](https://github.com/JetBrains/svg-sprite-loader/commit/f5239a0))
* **utils:** prevent errors for modules without resources ([467daa6](https://github.com/JetBrains/svg-sprite-loader/commit/467daa6))



<a name="3.7.2"></a>
## [3.7.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.7.1...v3.7.2) (2018-03-19)



<a name="3.7.1"></a>
## [3.7.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.7.0...v3.7.1) (2018-03-12)


### Bug Fixes

* **loader:** wrong build target ([66e98f9](https://github.com/JetBrains/svg-sprite-loader/commit/66e98f9))



<a name="3.7.0"></a>
# [3.7.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.6.2...v3.7.0) (2018-03-10)


### Features

* add webpack 4 support ([20f59ca](https://github.com/JetBrains/svg-sprite-loader/commit/20f59ca))



<a name="3.6.2"></a>
## [3.6.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.6.1...v3.6.2) (2017-12-27)


### Bug Fixes

* **plugin:** prevent outer symbol ast modifications ([0c8c3d0](https://github.com/JetBrains/svg-sprite-loader/commit/0c8c3d0))



<a name="3.6.1"></a>
## [3.6.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.6.0...v3.6.1) (2017-12-25)


### Bug Fixes

* **plugin:** don't hide sprite by default ([fd629bd](https://github.com/JetBrains/svg-sprite-loader/commit/fd629bd))



<a name="3.6.0"></a>
# [3.6.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.5.4...v3.6.0) (2017-12-22)


### Features

* **plugin:** add ability to specify sprite attributes in extract mode ([a6a5e30](https://github.com/JetBrains/svg-sprite-loader/commit/a6a5e30))



<a name="3.5.4"></a>
## [3.5.4](https://github.com/JetBrains/svg-sprite-loader/compare/v3.5.3...v3.5.4) (2017-12-19)


### Bug Fixes

* **plugin:** refer to sprite file properly in plainSprite mode ([e4789a4](https://github.com/JetBrains/svg-sprite-loader/commit/e4789a4))



<a name="3.5.3"></a>
## [3.5.3](https://github.com/JetBrains/svg-sprite-loader/compare/v3.5.2...v3.5.3) (2017-12-19)


### Bug Fixes

* **loader:** drop "2 applied rules" warning ([e18f7d6](https://github.com/JetBrains/svg-sprite-loader/commit/e18f7d6))



<a name="3.5.2"></a>
## [3.5.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.5.1...v3.5.2) (2017-12-12)


### Bug Fixes

* **loader:** #203 support use in rule.oneOf ([cb3d2da](https://github.com/JetBrains/svg-sprite-loader/commit/cb3d2da))



<a name="3.5.1"></a>
## [3.5.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.5.0...v3.5.1) (2017-12-08)


### Bug Fixes

* **package:** drop postinstall script ([8a46c78](https://github.com/JetBrains/svg-sprite-loader/commit/8a46c78))



<a name="3.5.0"></a>
# [3.5.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.4.1...v3.5.0) (2017-12-08)


### Features

* **loader:** add functional type of spriteFilename ([297a957](https://github.com/JetBrains/svg-sprite-loader/commit/297a957))



<a name="3.4.1"></a>
## [3.4.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.4.0...v3.4.1) (2017-10-23)


### Bug Fixes

* **plugin:** make sprite file hash more stable ([7e9c53e](https://github.com/JetBrains/svg-sprite-loader/commit/7e9c53e))



<a name="3.4.0"></a>
# [3.4.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.3.1...v3.4.0) (2017-10-19)


### Features

* better html-webpack-plugin interop in extract mode ([8a2d63e](https://github.com/JetBrains/svg-sprite-loader/commit/8a2d63e))



<a name="3.3.1"></a>
## [3.3.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.3.0...v3.3.1) (2017-10-16)


### Bug Fixes

* **loader:** check this.cacheable existence before call it ([c1ed50a](https://github.com/JetBrains/svg-sprite-loader/commit/c1ed50a))



<a name="3.3.0"></a>
# [3.3.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.6...v3.3.0) (2017-10-16)


### Features

* **plugin:** allow to render external sprite without styles and usages ([fcf3939](https://github.com/JetBrains/svg-sprite-loader/commit/fcf3939))



<a name="3.2.6"></a>
## [3.2.6](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.5...v3.2.6) (2017-09-28)


### Bug Fixes

* **loader:** #187 support rule.oneOf config ([75df92e](https://github.com/JetBrains/svg-sprite-loader/commit/75df92e))
* **loader:** support resourceQuery in extract mode with webpack version above 1 ([6652d78](https://github.com/JetBrains/svg-sprite-loader/commit/6652d78))



<a name="3.2.5"></a>
## [3.2.5](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.4...v3.2.5) (2017-08-31)


### Bug Fixes

* **runtime:** don't encode "(", ")" and "~" symbols when replacing urls in <use> references ([388ce74](https://github.com/JetBrains/svg-sprite-loader/commit/388ce74))



<a name="3.2.4"></a>
## [3.2.4](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.3...v3.2.4) (2017-08-20)


### Bug Fixes

* preserve \`fill\` and \`stroke\` attrs when transform svg to symbol ([d845aa3](https://github.com/JetBrains/svg-sprite-loader/commit/d845aa3))



<a name="3.2.3"></a>
## [3.2.3](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.2...v3.2.3) (2017-08-18)


### Bug Fixes

* deal with deprecation warnings from webpack 3 ([d150035](https://github.com/JetBrains/svg-sprite-loader/commit/d150035))



<a name="3.2.2"></a>
## [3.2.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.1...v3.2.2) (2017-08-17)


### Bug Fixes

* **plugin:** webpack-manifest-plugin compatibility ([d88ac31](https://github.com/JetBrains/svg-sprite-loader/commit/d88ac31))



<a name="3.2.1"></a>
## [3.2.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.2.0...v3.2.1) (2017-08-16)


### Bug Fixes

* **runtime:** apply styles in dynamically appended symbols in Edge ([299bfe2](https://github.com/JetBrains/svg-sprite-loader/commit/299bfe2))



<a name="3.2.0"></a>
# [3.2.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.7...v3.2.0) (2017-08-16)


### Features

* **runtime:** add ability to create sprite from existing DOM node ([4056d7b](https://github.com/JetBrains/svg-sprite-loader/commit/4056d7b))



<a name="3.1.7"></a>
## [3.1.7](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.6...v3.1.7) (2017-08-15)


### Bug Fixes

* **runtime:** store global sprite object in window which allows to mount symbols in one place betwee ([13e3d47](https://github.com/JetBrains/svg-sprite-loader/commit/13e3d47))



<a name="3.1.6"></a>
## [3.1.6](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.5...v3.1.6) (2017-08-10)


### Bug Fixes

* **loader:** interpolate sprite filename properly ([b17e5e0](https://github.com/JetBrains/svg-sprite-loader/commit/b17e5e0))



<a name="3.1.5"></a>
## [3.1.5](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.4...v3.1.5) (2017-08-10)


### Bug Fixes

* **loader:** throw an exception if input is not valid SVG ([413246e](https://github.com/JetBrains/svg-sprite-loader/commit/413246e)), closes [#170](https://github.com/JetBrains/svg-sprite-loader/issues/170)



<a name="3.1.4"></a>
## [3.1.4](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.3...v3.1.4) (2017-08-09)


### Bug Fixes

* **loader:** quick workaround for breaking changes in webpack@3.5 (`modules` prop dropped in ConcatenatedModule) ([f15030d](https://github.com/JetBrains/svg-sprite-loader/commit/f15030d))



<a name="3.1.3"></a>
## [3.1.3](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.2...v3.1.3) (2017-08-08)


### Bug Fixes

* **loader:** throw proper error message when runtime not found ([ef83fac](https://github.com/JetBrains/svg-sprite-loader/commit/ef83fac))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.1...v3.1.2) (2017-08-05)


### Bug Fixes

* **loader:** decode entities in <style> tags ([36e6ba6](https://github.com/JetBrains/svg-sprite-loader/commit/36e6ba6))



<a name="3.1.1"></a>
## [3.1.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.1.0...v3.1.1) (2017-08-04)


### Bug Fixes

* **loader:** handle case when rule test is a function ([ace9f47](https://github.com/JetBrains/svg-sprite-loader/commit/ace9f47))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.11...v3.1.0) (2017-08-03)


### Features

* **loader:** webpack 3 module concatenation interop in extract mode ([8a79536](https://github.com/JetBrains/svg-sprite-loader/commit/8a79536))



<a name="3.0.11"></a>
## [3.0.11](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.10...v3.0.11) (2017-08-03)


### Bug Fixes

* **runtime:** pass proper old URL in Angular workaround ([fbda8a2](https://github.com/JetBrains/svg-sprite-loader/commit/fbda8a2))



<a name="3.0.10"></a>
## [3.0.10](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.9...v3.0.10) (2017-07-31)

### Configuration

* **configuration:** add support for `symbolRegExp` pattern in symbol name interpolation ([e9de712](https://github.com/JetBrains/svg-sprite-loader/commit/e9de712))



<a name="3.0.9"></a>
## [3.0.9](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.8...v3.0.9) (2017-07-31)


### Bug Fixes

* **runtime:** fix IE/Edge rendering with SVG containing 'style' elements ([dcc9e27](https://github.com/JetBrains/svg-sprite-loader/commit/dcc9e27))



<a name="3.0.8"></a>
## [3.0.8](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.7...v3.0.8) (2017-07-28)


### Bug Fixes

* **runtime:** fallback to early sprite mount when document.body appears ([a71e67a](https://github.com/JetBrains/svg-sprite-loader/commit/a71e67a))



<a name="3.0.7"></a>
## [3.0.7](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.6...v3.0.7) (2017-07-24)


### Bug Fixes

* **runtime-generator:** return symbol id string in compat mode ([7641af0](https://github.com/JetBrains/svg-sprite-loader/commit/7641af0))



<a name="3.0.6"></a>
## [3.0.6](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.5...v3.0.6) (2017-07-17)


### Bug Fixes

* **loader:** add support for issuer when matching rules ([5d21b2f](https://github.com/JetBrains/svg-sprite-loader/commit/5d21b2f))


<a name="3.0.5"></a>
## [3.0.5](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.4...v3.0.5) (2017-06-02)


### Bug Fixes

* **loader:** replace sprite filename in whole source ([d4d4429](https://github.com/JetBrains/svg-sprite-loader/commit/d4d4429))



<a name="3.0.4"></a>
## [3.0.4](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.3...v3.0.4) (2017-05-31)


### Bug Fixes

* **utils:** properly replace path to image with sprite name on Windows ([6bdd6cd](https://github.com/JetBrains/svg-sprite-loader/commit/6bdd6cd))



<a name="3.0.3"></a>
## [3.0.3](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.2...v3.0.3) (2017-05-29)


### Bug Fixes

* **configuration:** proper configurator runtime selection based on \`target\` loader context ([a7365a2](https://github.com/JetBrains/svg-sprite-loader/commit/a7365a2))



<a name="3.0.2"></a>
## [3.0.2](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.1...v3.0.2) (2017-05-24)


### Bug Fixes

* **loader:** check module request properly in isModuleShouldBeExtracted with DLL Plugin ([ffb7b04](https://github.com/JetBrains/svg-sprite-loader/commit/ffb7b04))



<a name="3.0.1"></a>
## [3.0.1](https://github.com/JetBrains/svg-sprite-loader/compare/v3.0.0...v3.0.1) (2017-05-22)


### Bug Fixes

* **runtime-generator:** runtime generator in extract mode return object instead of string ([208b6dc](https://github.com/JetBrains/svg-sprite-loader/commit/208b6dc))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/JetBrains/svg-sprite-loader/compare/v2.1.0...v3.0.0) (2017-05-21)


### Features

* **loader:** runtime exports an object in extract mode ([f0af0eb](https://github.com/JetBrains/svg-sprite-loader/commit/f0af0eb))


### Reverts

* **tools:** rollback to standart-version :) ([b948e65](https://github.com/JetBrains/svg-sprite-loader/commit/b948e65))


### BREAKING CHANGES

* **loader:** Generated runtime in extract mode is changed from string to object

ISSUES CLOSED: #123



<a name="2.1.0"></a>
# [2.1.0](https://github.com/JetBrains/svg-sprite-loader/compare/v2.0.6...v2.1.0) (2017-05-13)


### Bug Fixes

* **multiple:** update svg-baker deps ([ead7d68](https://github.com/JetBrains/svg-sprite-loader/commit/ead7d68)), closes [#101](https://github.com/JetBrains/svg-sprite-loader/issues/101) [#103](https://github.com/JetBrains/svg-sprite-loader/issues/103) [#112](https://github.com/JetBrains/svg-sprite-loader/issues/112)
* **runtime:** update svg-baker-runtime with fixed angular workaround ([1543029](https://github.com/JetBrains/svg-sprite-loader/commit/1543029)), closes [#103](https://github.com/JetBrains/svg-sprite-loader/issues/103)


### Features

* add [hash] token substitution support ([87110f4](https://github.com/JetBrains/svg-sprite-loader/commit/87110f4)), closes [#98](https://github.com/JetBrains/svg-sprite-loader/issues/98) [#111](https://github.com/JetBrains/svg-sprite-loader/issues/111)


<a name="2.0.6"></a>
## [2.0.6](https://github.com/JetBrains/svg-sprite-loader/compare/v2.0.5...v2.0.6) (2017-05-13)


### Bug Fixes

* **configure:** use `browser-sprite``browser-symbol` for `electron-renderer` target ([b9a3ed0](https://github.com/JetBrains/svg-sprite-loader/commit/b9a3ed0))


<a name="2.1.0-3"></a>
## [2.1.0-3](https://github.com/JetBrains/svg-sprite-loader/compare/v2.1.0-2...v2.1.0-3) [beta] (2017-05-10)


### Bug Fixes

* **plugin:** properly replace paths on Windows ([0c70caa](https://github.com/JetBrains/svg-sprite-loader/commit/0c70caa)), closes [#106](https://github.com/JetBrains/svg-sprite-loader/issues/106)



<a name="2.1.0-2"></a>
## [2.1.0-2](https://github.com/JetBrains/svg-sprite-loader/compare/v2.1.0-1...v2.1.0-2) [beta] (2017-05-09)


### Bug Fixes

* **loader:** symbol id interpolation ([18edd99](https://github.com/JetBrains/svg-sprite-loader/commit/18edd99))



<a name="2.1.0-1"></a>
## [2.1.0-1](https://github.com/JetBrains/svg-sprite-loader/compare/v2.1.0-0...v2.1.0-1) [beta] (2017-05-08)


### Bug Fixes

* **plugin:** properly generate symbol url in extract mode ([6af7230](https://github.com/JetBrains/svg-sprite-loader/commit/6af7230))



<a name="2.1.0-0"></a>
## [2.1.0-0](https://github.com/JetBrains/svg-sprite-loader/compare/v2.0.5...v2.1.0-0) [beta] (2017-05-07)


### Bug Fixes

* **utils:** fix default import ([0c34daa](https://github.com/JetBrains/svg-sprite-loader/commit/0c34daa))


### Features

* **interop:** extract-text-webpack-plugin & html-webpack-plugin interop ([a38fdcc](https://github.com/JetBrains/svg-sprite-loader/commit/a38fdcc))
* **interop:** extract-text-webpack-plugin with allChunks: true interoperability ([63d347d](https://github.com/JetBrains/svg-sprite-loader/commit/63d347d))
* **spritehash:** add ability to use `[spritehash]` substitution token in spriteFilename ([f9eba1b](https://github.com/JetBrains/svg-sprite-loader/commit/f9eba1b))


<a name="2.0.5"></a>
## [2.0.5](https://github.com/JetBrains/svg-sprite-loader/compare/v2.0.4...v2.0.5) (2017-05-05)
