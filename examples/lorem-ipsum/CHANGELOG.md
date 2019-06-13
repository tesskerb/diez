# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [10.0.0-alpha.4](https://github.com/stristr/diez/compare/v10.0.0-alpha.3...v10.0.0-alpha.4) (2019-06-13)


### chore

* **ios:** rename `UIImage` getter on `Image` to `uiImage` ([#137](https://github.com/stristr/diez/issues/137)) ([7bbd9f5](https://github.com/stristr/diez/commit/7bbd9f5))


### Features

* **docs:** add getting started docs for iOS ([#132](https://github.com/stristr/diez/issues/132)) ([f67f039](https://github.com/stristr/diez/commit/f67f039))
* **examples:** use hot updates in lorem-ipsum android example ([#136](https://github.com/stristr/diez/issues/136)) ([8cabfc4](https://github.com/stristr/diez/commit/8cabfc4))


### BREAKING CHANGES

* **ios:** The `image` property getter that returns a `UIImage` on the `Image` extension has been renamed `uiImage`.





# [10.0.0-alpha.3](https://github.com/stristr/diez/compare/v10.0.0-alpha.2...v10.0.0-alpha.3) (2019-06-10)

**Note:** Version bump only for package lorem-ipsum





# [10.0.0-alpha.2](https://github.com/stristr/diez/compare/v10.0.0-alpha.1...v10.0.0-alpha.2) (2019-06-10)

**Note:** Version bump only for package lorem-ipsum





# [10.0.0-alpha.1](https://github.com/stristr/diez/compare/v10.0.0-alpha.0...v10.0.0-alpha.1) (2019-06-10)


### Bug Fixes

* **createproject:** simplify `lorem-ipsum` web example ([#120](https://github.com/stristr/diez/issues/120)) ([085d1b0](https://github.com/stristr/diez/commit/085d1b0))


### Features

* **compiler:** enable fully ejectable Diez SDKs for Android and web ([#97](https://github.com/stristr/diez/issues/97)) ([4b57a8e](https://github.com/stristr/diez/commit/4b57a8e))
* add script that generates example templates for createproject ([#115](https://github.com/stristr/diez/issues/115)) ([943513c](https://github.com/stristr/diez/commit/943513c))
* **createproject:** shore up the behavior of `diez create` ([#126](https://github.com/stristr/diez/issues/126)) ([17d0202](https://github.com/stristr/diez/commit/17d0202))
* **examples:** add android example to lorem-ipsum ([#113](https://github.com/stristr/diez/issues/113)) ([12797c8](https://github.com/stristr/diez/commit/12797c8))
* **examples:** add web example to lorem-ipsum ([#114](https://github.com/stristr/diez/issues/114)) ([eee18f8](https://github.com/stristr/diez/commit/eee18f8))


### Performance Improvements

* **cli:** reduce the dependency weight of the `diez` CLI ([#86](https://github.com/stristr/diez/issues/86)) ([94dbee0](https://github.com/stristr/diez/commit/94dbee0))


### BREAKING CHANGES

* **compiler:** the `diez compile` command no longer uses an `--outputPath/-o` flag for directing SDK output to a specified directory nor a `--devMode/-d` flag for running "hot", and instead builds SDKs into `build/` in unique directories per project/target like `build/diez-poodle-surf-ios`.





# [10.0.0-alpha.0](https://github.com/diez/diez/compare/v1.0.0-beta.5...v10.0.0-alpha.0) (2019-05-08)


### Features

* **generation:** add basic code generation abilities for design sources ([#74](https://github.com/diez/diez/issues/74)) ([6f0b80f](https://github.com/diez/diez/commit/6f0b80f))