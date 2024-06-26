# Changelog

## [1.22.1](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/compare/v1.22.0...v1.22.1) (2024-05-27)


### Bug Fixes

* correct config of maven assembly plugin ([#116](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/116)) ([380799b](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/380799bb65c7e9f299a3570f831eeb31d01f09eb)), closes [#109](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/109)
* create_search_index_statement equals ([#114](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/114)) ([6ea341e](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/6ea341e0ad24448048835dc0fc0548be811796c2)), closes [#111](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/111)
* **deps:** bump commons-cli:commons-cli from 1.7.0 to 1.8.0 ([#112](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/112)) ([c9ec7a1](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/c9ec7a1fb2f5be59f72c09cb3f8c0dedafaca7ed))
* **deps:** bump org.codehaus.mojo:build-helper-maven-plugin ([#110](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/110)) ([0fbc5db](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/0fbc5db72812bf462c1541545aba893d98b58b61))
* **deps:** bump org.codehaus.mojo:exec-maven-plugin from 3.2.0 to 3.3.0 ([#113](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/113)) ([f63a7c8](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/f63a7c846fa009c247d814e5d3a85d94edc60ebb))

## [1.22.0](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/compare/v1.21.0...v1.22.0) (2024-05-14)


### Features

* Add support for FLOAT32 column type ([e5ee7c1](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/e5ee7c15f5e0b07ad03ea73e3edf1c598d956e75))
* Support for diffs on Create Search Index ([#104](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/104)) ([5a567ed](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/5a567ed6abf3f3ba5e0beb33a50d793162c06f28))


### Bug Fixes

* **deps:** bump com.google.errorprone:error_prone_core ([#108](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/108)) ([4a4c0ad](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/4a4c0adabc9f0f5994bfa71f8fe3a233fd563f5f))
* **deps:** bump com.google.guava:guava from 33.1.0-jre to 33.2.0-jre ([#107](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/107)) ([548e2cb](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/548e2cb5552f4a7f0d7a1ec00d8493dd972c0347))

## [1.21.0](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/compare/v1.20.0...v1.21.0) (2024-05-01)


### Features

* Update parser to handle RENAME and SYNONYM ([#101](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/101)) ([49a08fd](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/49a08fda9f2359027256c345708c6e7819cc7607))


### Bug Fixes

* Compilation issues with error-prone on JDK16+ ([#100](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/100)) ([7e98200](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/7e9820066cd2478ac73a348483c952c99780b3c3))
* **deps:** bump com.google.errorprone:error_prone_core ([#99](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/99)) ([b51fa4c](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/b51fa4c613e95049b32ca63233d1438abe4ab030))
* **deps:** Bump com.google.errorprone:error_prone_core from 2.25.0 to 2.26.1 ([#93](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/93)) ([1c1cb59](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/1c1cb59b489391e82b764f7a29c519a9c492cde3))
* **deps:** Bump com.google.guava:guava from 33.0.0-jre to 33.1.0-jre ([#92](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/92)) ([1dd2837](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/1dd2837b69534fc4d94af8cdafac2ca53035563d))
* **deps:** bump commons-cli:commons-cli from 1.6.0 to 1.7.0 ([#98](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/98)) ([e9a3514](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/e9a35148362fbf380909f3e69d750185809b2c92))
* **deps:** Bump org.apache.maven.plugins:maven-compiler-plugin ([#95](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/95)) ([226e5a2](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/226e5a2880a736339b9080690190bbfed8daa4da))
* **deps:** Bump slf4j.version from 2.0.12 to 2.0.13 ([#96](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/96)) ([e4b0471](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/e4b047185df82452a999c32e62d135084fa75b0c))
* Update dependabot.yml to add conventional commit prefix ([f0a4cb7](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/f0a4cb77f81ece7cef76cdc4fc3b8c85115c76d8))
* Update dependabot.yml to add conventional commit prefix ([97243fa](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/97243fa3952f344231ad30dff15ba14af8dc40b3))

## 1.20.0 (2024-03-11)


### Features

* Add handling for updating stored columns on indexes ([eea1b22](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/eea1b222f1532b942c2b31b1377d4eba090e5c86))


### Bug Fixes

* library should released as 1.20.0 ([#91](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/issues/91)) ([efd280c](https://github.com/cloudspannerecosystem/spanner-schema-diff-tool/commit/efd280cc64d217443d8a19660aec8677339da65e))
