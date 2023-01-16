# Changelog

All notable changes to this project will be documented in this file. See [Convential Commits](https://www.conventionalcommits.org/en/v1.0.0/#specification) for commit guidelines.

## [3.1.6-agent-debug-20230116-213150-3920987.0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.5-0...v3.1.6-agent-debug-20230116-213150-3920987.0) (Mon Jan 16 2023)

## [3.1.5-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.4-0...v3.1.5-0) (Mon Jan 16 2023)

### Fixes

- add a hard http timeout and destroy socket if it doesn't close on it's own [cbc4493](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/cbc4493afd17091f630a4ee46adbf0896f476783)

## [3.1.4](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.4-0...v3.1.4) (Mon Jan 16 2023)

## [3.1.4-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.3-0...v3.1.4-0) (Fri Jan 13 2023)

### Fixes

- increase Quantel Gateway HTTP Keep-Alive to 60s [effc11a](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/effc11a7e143384089aac7aadf8de90256f1386f)

## [3.1.3-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.2-0...v3.1.3-0) (Thu Jan 12 2023)

### Fixes

- improve timeout reporting [32f38d1](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/32f38d1464df0c527221deca81b24b234036709f)

## [3.1.2-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.1-0...v3.1.2-0) (Thu Jan 12 2023)

### Fixes

- use keep-alive, but longer [f83f73c](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/f83f73ca6f45cd46ff02494c7fa449be41c5a721)

## [3.1.1-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.1.0...v3.1.1-0) (Thu Jan 12 2023)

### Fixes

- do not use keepAlive in Quantel Gateway [327b41d](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/327b41de06c5b325741b073097143586d00dcd9d)

## [3.1.0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.0.4...v3.1.0) (Thu Jan 12 2023)

### Features

- configurable call timeout [5194a8d](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/5194a8d096ce33f79d10786b6cc04ec6bda38913)

## [3.0.4](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.0.3...v3.0.4) (Wed Jan 11 2023)

### Fixes

- cancel the socket if there is an error (#8) [bf7b46b](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/bf7b46b929fbb7f45c84749a6bd63192e2ad06aa)
- extend call timeout [9afda16](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/9afda16c772b74888c9d20b4ef229cdff8ff78fd)

## [3.0.3](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.0.2...v3.0.3) (Wed Jan 11 2023)

### Fixes

- remove automatic retries in requests [8f44740](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/8f44740ed0b8227b1f97ed260635947cdbdb70db)

## [3.0.2](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.0.1...v3.0.2) (Mon Jan 09 2023)

### [3.0.1](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v3.0.0...v3.0.1) (2023-01-09)

### Bug Fixes

- remove Node 12.x from workflows ([63344e9](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/63344e98aef9e9c76427417eaf81b0e46aa7a804))

## [3.0.0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.5...v3.0.0) (2023-01-09)

### ⚠ BREAKING CHANGES

- update got, upgrade node requirement to Node 14

### Features

- update got, upgrade node requirement to Node 14 ([bd5f322](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/bd5f322b4caf8ddbedbc1096d2a4f067eacf1b06))

### [2.0.5](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.4...v2.0.5) (2022-07-05)

### Bug Fixes

- increase HTTP timeout ([2521239](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/252123980500e5f5e0efeee5992038a3cc50faa9))
- limit the amount of created concurrent connections ([#5](https://github.com/nrkno/tv-automation-quantel-gateway-client/issues/5)) ([c460f04](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/c460f04fa7af4610939a67561d6a08aee03d979d))

### [2.0.4](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.3...v2.0.4) (2021-09-29)

### [2.0.3](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.3-0...v2.0.3) (2021-09-29)

### [2.0.3-0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.2...v2.0.3-0) (2021-09-29)

### Bug Fixes

- better error [release] ([d05eac3](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/d05eac342a0c1cbaac8410be3dc8596ae670c892))

### [2.0.2](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.1...v2.0.2) (2021-05-12)

### Bug Fixes

- dont require serverId ([a6ca5a2](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/a6ca5a277b9a8db2d4d76eeb196052a3143f2674))
- make serverId be settable during the lifetime of the QuantelGateway class ([a4b66b5](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/a4b66b551ca51e8c63d8bf2ebe180f8bee79792c))
- refactor to remove the underscore dependency ([adaa6ab](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/adaa6ab0f66f9a2132c981f04860ef3fc91f7acc))

### [2.0.1](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v2.0.0...v2.0.1) (2021-03-19)

### Bug Fixes

- type error [release] ([855e834](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/855e83442e8a2c138d8e7a6b06b32d6e9e6d2fae))

## [2.0.0](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.12...v2.0.0) (2021-03-19)

### ⚠ BREAKING CHANGES

- change how ISA url:s are handled. All ISA urls (both master & slaves) are now handled in a single array

### Features

- change how ISA url:s are handled. All ISA urls (both master & slaves) are now handled in a single array ([fce28cc](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/fce28cc4bdf4d668372037dd400b5284ef2eef33))

### Bug Fixes

- store ISAUrlMaster and ISAUrlBackup in their unaltered form, and expose them via getters. ([6ebb058](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/6ebb05861debd526a039c5d0833b5df1f1db4fee))

### [1.0.12](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.11...v1.0.12) (2020-08-26)

### Bug Fixes

- handle received http error responses [release] ([911d5cb](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/911d5cbb09234f17f14240dd415a6b556687f96c))

### [1.0.11](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.9...v1.0.11) (2020-08-25)

### Bug Fixes

- got requests should resolve with full details, not body only ([ffd8ab4](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/ffd8ab406e860fd67f4c6a78ba4c421a34e51d4d))

### [1.0.10](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.9...v1.0.10) (2020-08-25)

### Bug Fixes

- got requests should resolve with full details, not body only ([ffd8ab4](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/ffd8ab406e860fd67f4c6a78ba4c421a34e51d4d))

### [1.0.9](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.8...v1.0.9) (2020-08-19)

### Bug Fixes

- apparently, 404 messages doesn't start with 404 anymore ([cc67054](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/cc67054c9890d31d9540667a2cab738b464b016b))

### [1.0.8](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.7...v1.0.8) (2020-06-10)

### Bug Fixes

- align with updates to TSR's copy of quantel gateway ([1e08eda](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/1e08edab92b0bc4fc2bbece6d134fabf6d69e461))

### [1.0.7](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.6...v1.0.7) (2020-05-26)

### Bug Fixes

- [release] revert to Typescript 3.8.x - 3.9.x is not fit for purpose yet ([d8c2ad6](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/d8c2ad62f097f2de258e6e719791e93c97bf270f))

### [1.0.6](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.5...v1.0.6) (2020-05-26)

### [1.0.5](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.4...v1.0.5) (2020-05-26)

### [1.0.4](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.3...v1.0.4) (2020-05-26)

### Bug Fixes

- [release] include typings ([ca18d85](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/ca18d85bc5b394aae566aff602208adece6c1a12))

### [1.0.3](https://github.com/nrkno/tv-automation-quantel-gateway-client/compare/v1.0.2...v1.0.3) (2020-05-19)

### 1.0.2 (2020-05-18)

### Bug Fixes

- ensure all required scripts are in package.json ([f63dff5](https://github.com/nrkno/tv-automation-quantel-gateway-client/commit/f63dff5de2259635f31e5fe19aa35e049b8617ca))
