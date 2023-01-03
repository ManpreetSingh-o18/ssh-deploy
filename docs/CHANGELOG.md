## [4.0.4](https://github.com/easingthemes/ssh-deploy/compare/v4.0.3...v4.0.4) (2023-01-03)


### Bug Fixes

* update sub dependencies ([2a32c8d](https://github.com/easingthemes/ssh-deploy/commit/2a32c8dcde2d64394a3577decdd9c902f37a30f8))

## [4.0.3](https://github.com/easingthemes/ssh-deploy/compare/v4.0.2...v4.0.3) (2023-01-03)


### Bug Fixes

* update v3 e2e test ([450bf42](https://github.com/easingthemes/ssh-deploy/commit/450bf423f388777bde052ad7b5bc24eca392434d))

## [4.0.2](https://github.com/easingthemes/ssh-deploy/compare/v4.0.1...v4.0.2) (2023-01-03)


### Bug Fixes

* add githubWorkspace as default source root ([3ef66d0](https://github.com/easingthemes/ssh-deploy/commit/3ef66d0be999ee45434505e8bedea4f8b5b5a909))

## [4.0.1](https://github.com/easingthemes/ssh-deploy/compare/v4.0.0...v4.0.1) (2023-01-03)


### Bug Fixes

* fix default source if empty ([9f191f4](https://github.com/easingthemes/ssh-deploy/commit/9f191f42633c4a0f66054f0fc229c9e30a08f00c))

# [4.0.0](https://github.com/easingthemes/ssh-deploy/compare/v3.4.3...v4.0.0) (2023-01-03)


### Bug Fixes

* rebuild ([2169399](https://github.com/easingthemes/ssh-deploy/commit/2169399fef9a60a2fea1ab03cce4ec8c2371e5c2))


### Performance Improvements

* update default rsync options ([2be7efb](https://github.com/easingthemes/ssh-deploy/commit/2be7efb376866327c1d1209f51eb43f34f07b354))


### BREAKING CHANGES

* Default rsync options updated to speed up default deployments.
from `rltgoDzvO` to `-rlgoDzvc -i`

## [3.4.3](https://github.com/easingthemes/ssh-deploy/compare/v3.4.2...v3.4.3) (2023-01-03)


### Bug Fixes

* move e2e tests typo branch name ([6d3554b](https://github.com/easingthemes/ssh-deploy/commit/6d3554b01e9a05de9a9d2b30274bee411a4986ed))

## [3.4.2](https://github.com/easingthemes/ssh-deploy/compare/v3.4.1...v3.4.2) (2023-01-03)


### Bug Fixes

* Update changelog ([765f5ff](https://github.com/easingthemes/ssh-deploy/commit/765f5ffd3153c76442521c61c04656cafc182731))

## [3.4.1](https://github.com/easingthemes/ssh-deploy/compare/v3.4.0...v3.4.1) (2023-01-03)


### Bug Fixes

* move e2e tests to main branch ([0069fae](https://github.com/easingthemes/ssh-deploy/commit/0069faea9ff3ea3cdd095b0f2663c9e2bcd97480))

# [3.4.0](https://github.com/easingthemes/ssh-deploy/compare/v3.3.4...v3.4.0) (2023-01-03)


**Full Changelog**: https://github.com/easingthemes/ssh-deploy/compare/v3.1.0...v3.4.1

### Features

* Add SSH remote script support -  before and after rsync ([2cd8a82](https://github.com/easingthemes/ssh-deploy/commit/2cd8a820e22135b7002fbe6a47cf33f99e2d337b))
* Add multi source and multi target support ([73a65ec](https://github.com/easingthemes/ssh-deploy/commit/73a65ec97c5046a53f6b4c40823be5fd3826ede0))
* Add SSH_CMD_ARGS support ([51a0063](https://github.com/easingthemes/ssh-deploy/commit/51a00631e2b91983fb610ca2157a673b9ae03c95))
* Add manual inputs for e2e test ([8f71595](https://github.com/easingthemes/ssh-deploy/commit/8f715957ab9283ab2934dd1e5be9d78f2eaf3fae))

### Bug Fixes

* Add visible Rsync CMD for debugging ([91b6d28](https://github.com/easingthemes/ssh-deploy/commit/91b6d280aee6a7ae666a11426fb356406f4a25a5))
* log buffer from rsync stdout ([8e19e0d](https://github.com/easingthemes/ssh-deploy/commit/8e19e0d6bc9b1c332925ce0268ad64b50728fae5))
* fix e2e yaml step name ([5c13615](https://github.com/easingthemes/ssh-deploy/commit/5c13615d4b7b0bda47f622ac5f4444484d8bcdb4))

## [3.3.4](https://github.com/easingthemes/ssh-deploy/compare/v3.3.3...v3.3.4) (2023-01-02)


### Bug Fixes

* Add visible Rsync CMD for debugging ([91b6d28](https://github.com/easingthemes/ssh-deploy/commit/91b6d280aee6a7ae666a11426fb356406f4a25a5))

## [3.3.3](https://github.com/easingthemes/ssh-deploy/compare/v3.3.2...v3.3.3) (2023-01-02)


### Bug Fixes

* log buffer from rsync stdout ([8e19e0d](https://github.com/easingthemes/ssh-deploy/commit/8e19e0d6bc9b1c332925ce0268ad64b50728fae5))

## [3.3.2](https://github.com/easingthemes/ssh-deploy/compare/v3.3.1...v3.3.2) (2023-01-02)


### Bug Fixes

* Add manual inputs for e2e test ([8f71595](https://github.com/easingthemes/ssh-deploy/commit/8f715957ab9283ab2934dd1e5be9d78f2eaf3fae))

## [3.3.1](https://github.com/easingthemes/ssh-deploy/compare/v3.3.0...v3.3.1) (2023-01-02)


### Bug Fixes

* Log rsync command ([85f4a96](https://github.com/easingthemes/ssh-deploy/commit/85f4a967435d7d44edf2fea628c9f59db5e890ee))

# [3.3.0](https://github.com/easingthemes/ssh-deploy/compare/v3.2.0...v3.3.0) (2023-01-02)


### Features

* Add SSH_CMD_ARGS support ([51a0063](https://github.com/easingthemes/ssh-deploy/commit/51a00631e2b91983fb610ca2157a673b9ae03c95))

# [3.2.0](https://github.com/easingthemes/ssh-deploy/pull/94/files) (2023-01-02)


### Features

* Add SSH remote script support -  before and after rsync ([2cd8a82](https://github.com/easingthemes/ssh-deploy/pull/94/files))
* feat: add sshCmdArgs option
* feat: add onStderr and onStdout logs
* feat: Add RSYNC_STDOUT env variable
* feat: Update emojis

### Bug Fixes

* fix: remove _unsafe _dirname
* fix: Add promise instead of callback
* fix: improve logs
* fix: Add simple command exists instead of a plugin
* fix: add non interactive install
* fix: Improve reject messages
* fix: update workflow actions


## [3.1.1](https://github.com/easingthemes/ssh-deploy/compare/v3.1.0...v3.1.1) (2023-01-02)


### Bug Fixes

* use main branch for e2e testes ([21451fe](https://github.com/easingthemes/ssh-deploy/commit/21451fec978a02b55672490a2c11c6c17995ff95))

# [3.1.0](https://github.com/easingthemes/ssh-deploy/compare/v3.0.1...v3.1.0) (2022-12-31)


### Features

* add e2e tests ([40f855a](https://github.com/easingthemes/ssh-deploy/commit/40f855a08b4911c3f54b7a45306af355c6d87277))

## [3.0.1](https://github.com/easingthemes/ssh-deploy/compare/v3.0.0...v3.0.1) (2022-10-28)


### Bug Fixes

* readme update ([80a7f53](https://github.com/easingthemes/ssh-deploy/commit/80a7f53ec918930fd23f0524fec0b1d4f52183bf)), closes [#67](https://github.com/easingthemes/ssh-deploy/issues/67)

# [3.0.0](https://github.com/easingthemes/ssh-deploy/compare/v2.2.11...v3.0.0) (2022-10-28)


### Bug Fixes

* plugins versions ([2f40dde](https://github.com/easingthemes/ssh-deploy/commit/2f40dde84fde36f5b9b81ededd7090c5159d9885))


* Merge pull request #83 from easingthemes/feature/#82-update-node-version ([76660a8](https://github.com/easingthemes/ssh-deploy/commit/76660a8456dbf26e6328674e25d083941ddd645e)), closes [#83](https://github.com/easingthemes/ssh-deploy/issues/83) [easingthemes/feature/#82](https://github.com/easingthemes/feature//issues/82)


### BREAKING CHANGES

* update to use nodeJS v16

## [2.2.11](https://github.com/easingthemes/ssh-deploy/compare/v2.2.10...v2.2.11) (2021-05-28)


### Bug Fixes

* remove change npm to public ([3c36af7](https://github.com/easingthemes/ssh-deploy/commit/3c36af7577e5aee231cea5a01bb6cc83717d0e74))

## [2.2.10](https://github.com/easingthemes/ssh-deploy/compare/v2.2.9...v2.2.10) (2021-05-27)


### Bug Fixes

* add assets to semantic-release git ([0867b12](https://github.com/easingthemes/ssh-deploy/commit/0867b12954dee2b8a2cccb7dfea3b8f3aa62d679))

## [2.2.9](https://github.com/easingthemes/ssh-deploy/compare/v2.2.8...v2.2.9) (2021-05-27)


### Bug Fixes

* change npm to public ([191c82d](https://github.com/easingthemes/ssh-deploy/commit/191c82d9b441e26cf43f81041376dbf5ecdc1647))

## [2.2.8](https://github.com/easingthemes/ssh-deploy/compare/v2.2.7...v2.2.8) (2021-05-27)


### Bug Fixes

* update npm package name ([9c4e411](https://github.com/easingthemes/ssh-deploy/commit/9c4e4119ad64792e5435e4dbe574c56a3e70839c))

## [2.2.7](https://github.com/easingthemes/ssh-deploy/compare/v2.2.6...v2.2.7) (2021-05-27)


### Bug Fixes

* minify dist ([87551c3](https://github.com/easingthemes/ssh-deploy/commit/87551c38936fc91c0fbe3346ca43319d8098ac09))

## [2.2.6](https://github.com/easingthemes/ssh-deploy/compare/v2.2.5...v2.2.6) (2021-05-27)


### Bug Fixes

* add NPM token ([2197bc6](https://github.com/easingthemes/ssh-deploy/commit/2197bc60ef7870d4bd494966b314eabec1615bd7))

## [2.2.5](https://github.com/easingthemes/ssh-deploy/compare/v2.2.4...v2.2.5) (2021-05-27)


### Bug Fixes

* semantic-release/npm update config ([40096bf](https://github.com/easingthemes/ssh-deploy/commit/40096bf22459d1dd82172d2bd20c0c149e70b1e1))

## [2.2.4](https://github.com/easingthemes/ssh-deploy/compare/v2.2.3...v2.2.4) (2021-05-27)


### Bug Fixes

* add branch instead of a version in a readme ([8218c8e](https://github.com/easingthemes/ssh-deploy/commit/8218c8ed9514d772933e1ab4d1c725a7c05e149f))

## [2.2.3](https://github.com/easingthemes/ssh-deploy/compare/v2.2.2...v2.2.3) (2021-05-27)


### Bug Fixes

* codeql yaml syntax update ([87ad671](https://github.com/easingthemes/ssh-deploy/commit/87ad6713b53d454bd7ad6c4576cea7b2e3e2f4f3))

## [2.2.2](https://github.com/easingthemes/ssh-deploy/compare/v2.2.1...v2.2.2) (2021-05-27)


### Bug Fixes

* codeql build ([5e456a4](https://github.com/easingthemes/ssh-deploy/commit/5e456a475a15096d08ccd2aff2734b3f1250b308))

## [2.2.1](https://github.com/easingthemes/ssh-deploy/compare/v2.2.0...v2.2.1) (2021-05-27)


### Bug Fixes

* add package json auto updates ([ce56d75](https://github.com/easingthemes/ssh-deploy/commit/ce56d75fc1b62a99d72ffba70dcb24fcc3b6b3df))

# [2.2.0](https://github.com/easingthemes/ssh-deploy/compare/v2.1.7...v2.2.0) (2021-05-27)


### Bug Fixes

* only=prod package json ([95f4dc8](https://github.com/easingthemes/ssh-deploy/commit/95f4dc8069045c1f5f726e00cb519b46e4f14267))
* replace i with ci ([50d1f57](https://github.com/easingthemes/ssh-deploy/commit/50d1f576f95c0d7e8ce99fb1b2ab68b2594973e5))
* update ncc ([20a0cae](https://github.com/easingthemes/ssh-deploy/commit/20a0cae1ae81bcc430507363e800342976307a81))
* update plugins ([b2adc00](https://github.com/easingthemes/ssh-deploy/commit/b2adc00c92f129aef41ae46441411c2bebc0dbe4))
* update plugins ([a50a999](https://github.com/easingthemes/ssh-deploy/commit/a50a999528b503846cc7fdf26210f710bd95565a))


### Features

* add semantic-release-action ([ac3c9b5](https://github.com/easingthemes/ssh-deploy/commit/ac3c9b51d5cb52f4add40e2fc2dcc5e970153afc))
