# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Generated by [`auto-changelog`](https://github.com/CookPete/auto-changelog).

## [9.8.4](https://github.com/netlify/build/compare/framework-info-v9.8.3...framework-info-v9.8.4) (2023-03-01)


### Bug Fixes

* **framework-info:** detect gatsby typescript project ([#4895](https://github.com/netlify/build/issues/4895)) ([3978402](https://github.com/netlify/build/commit/39784024f631ff22b998ac731bcd9b6bd807a576))

## [9.8.3](https://github.com/netlify/build/compare/framework-info-v9.8.2...framework-info-v9.8.3) (2023-02-27)


### Bug Fixes

* **framework-info:** add missing types in package.json ([#4873](https://github.com/netlify/build/issues/4873)) ([b03c28e](https://github.com/netlify/build/commit/b03c28ea812724c01bd54e04f6bf19fd0a2f6247))

## [9.8.2](https://github.com/netlify/build/compare/framework-info-v9.8.1...framework-info-v9.8.2) (2023-02-17)


### Bug Fixes

* Updated logos to correct file name ([#4867](https://github.com/netlify/build/issues/4867)) ([08dbacb](https://github.com/netlify/build/commit/08dbacbb0aa2173b609c93083d47b391c40c8b19))

## [9.8.1](https://github.com/netlify/build/compare/framework-info-v9.8.0...framework-info-v9.8.1) (2023-02-09)


### Bug Fixes

* respect manual order of frameworks ([#4858](https://github.com/netlify/build/issues/4858)) ([45c0cf2](https://github.com/netlify/build/commit/45c0cf2b3fbc669a0c39f7b0529fce741b25106b))

## [9.8.0](https://github.com/netlify/build/compare/framework-info-v9.7.2...framework-info-v9.8.0) (2023-02-09)


### Features

* export getFrameworkById ([#4852](https://github.com/netlify/build/issues/4852)) ([ff37e4c](https://github.com/netlify/build/commit/ff37e4c0ae5775fe7748b0e12c14df159b592709))


### Bug Fixes

* migrate framework-info to TS and vitest and enable more strictness ([#4819](https://github.com/netlify/build/issues/4819)) ([5acb25b](https://github.com/netlify/build/commit/5acb25b3e1e8cd6d5fa85fdb76baea5a34a1131b))
* Revert "fix: update Solid Start default port ([#4845](https://github.com/netlify/build/issues/4845))" ([#4851](https://github.com/netlify/build/issues/4851)) ([eea7d29](https://github.com/netlify/build/commit/eea7d29d7535cb7252b9e806b3d4987954710c30))

## [9.7.2](https://github.com/netlify/build/compare/framework-info-v9.7.1...framework-info-v9.7.2) (2023-02-01)


### Bug Fixes

* update Solid Start default port ([#4845](https://github.com/netlify/build/issues/4845)) ([e5f4c12](https://github.com/netlify/build/commit/e5f4c12b67b1be521d0feb36148dbc82c6f59f8a))

## [9.7.1](https://github.com/netlify/build/compare/framework-info-v9.7.0...framework-info-v9.7.1) (2023-01-18)


### Bug Fixes

* Correctly handle missing node_modules ([#4828](https://github.com/netlify/build/issues/4828)) ([2e9ff5c](https://github.com/netlify/build/commit/2e9ff5ca8ad17ea234e06956f662f0beee8d33a7))

## [9.7.0](https://github.com/netlify/build/compare/framework-info-v9.6.0...framework-info-v9.7.0) (2023-01-16)


### Features

* install framework runtime ([#4812](https://github.com/netlify/build/issues/4812)) ([5abc39d](https://github.com/netlify/build/commit/5abc39dfd074bfda52fef3222ee9d73c2ed98403))


### Bug Fixes

* correct default sveltekit publish directory ([#4823](https://github.com/netlify/build/issues/4823)) ([fbc98fd](https://github.com/netlify/build/commit/fbc98fdc1efea1b720dfe0e15b7a1a6879e52e20))

## [9.6.0](https://github.com/netlify/build/compare/framework-info-v9.5.3...framework-info-v9.6.0) (2023-01-10)


### Features

* add build system detection ([#4763](https://github.com/netlify/build/issues/4763)) ([73bdb7b](https://github.com/netlify/build/commit/73bdb7bed7347cf6a8c4d729142c322297a0dce8))
* move framework-info into build packages ([#4783](https://github.com/netlify/build/issues/4783)) ([d37cbc4](https://github.com/netlify/build/commit/d37cbc48e4524ef486b3e408ae4e38125618a49c))


### Bug Fixes

* **deps:** update dependency @netlify/edge-bundler to v4.1.0 ([#4696](https://github.com/netlify/build/issues/4696)) ([f7044e0](https://github.com/netlify/build/commit/f7044e013804096dfb61ba0459226ff6d702ddf3))

## [9.5.3](https://github.com/netlify/framework-info/compare/v9.5.2...v9.5.3) (2022-12-06)


### Bug Fixes

* support new 11ty config files ([#848](https://github.com/netlify/framework-info/issues/848)) ([3aa65f8](https://github.com/netlify/framework-info/commit/3aa65f8ad65984ff3477e61d859cdc5d5dc5ac8a))

## [9.5.2](https://github.com/netlify/framework-info/compare/v9.5.1...v9.5.2) (2022-11-21)


### Bug Fixes

* **deps:** update dependency ajv to v8.11.2 ([#839](https://github.com/netlify/framework-info/issues/839)) ([4d7e59f](https://github.com/netlify/framework-info/commit/4d7e59f9e8b74edb07f2ec3f995143c781932587))
* handle version for frameworks which are not detected by npm package ([#842](https://github.com/netlify/framework-info/issues/842)) ([5735d2e](https://github.com/netlify/framework-info/commit/5735d2e298e6637c65add9680cbccac0c0245f51))

## [9.5.1](https://github.com/netlify/framework-info/compare/v9.5.0...v9.5.1) (2022-11-10)


### Bug Fixes

* updated Remix framework info that was missing ([#836](https://github.com/netlify/framework-info/issues/836)) ([e594ddf](https://github.com/netlify/framework-info/commit/e594ddfc84df0cfdb292176fc61d26cd3c115722))

## [9.5.0](https://github.com/netlify/framework-info/compare/v9.4.0...v9.5.0) (2022-11-01)


### Features

* update next.js logos ([#825](https://github.com/netlify/framework-info/issues/825)) ([213ec23](https://github.com/netlify/framework-info/commit/213ec23ad22ee5826a9fd1e3a81264d7107bd095))


### Bug Fixes

* update filepaths ([#831](https://github.com/netlify/framework-info/issues/831)) ([308b2a6](https://github.com/netlify/framework-info/commit/308b2a65446240d456dbb0c5dfda03b5c76972e0))
* update the files entry in package.json ([#828](https://github.com/netlify/framework-info/issues/828)) ([259f6c0](https://github.com/netlify/framework-info/commit/259f6c0efb250a915192723afccb5f7d8f55ff96))

## [9.4.0](https://github.com/netlify/framework-info/compare/v9.3.0...v9.4.0) (2022-10-27)


### Features

* detect installed version of framework ([#822](https://github.com/netlify/framework-info/issues/822)) ([8f4c78a](https://github.com/netlify/framework-info/commit/8f4c78a66f04b39da1f19422e42d7e4739af6d54))
* migrate from webpack to vite ([#819](https://github.com/netlify/framework-info/issues/819)) ([13430d9](https://github.com/netlify/framework-info/commit/13430d9deaa7ac739a622ba950bf7eac6cd5fd56))


### Bug Fixes

* changed the Vite port to the new Vite default port 5173 ([#792](https://github.com/netlify/framework-info/issues/792)) ([664e6df](https://github.com/netlify/framework-info/commit/664e6df4062da80cffd583d45b3e6364da47bc0f))
* **deps:** update dependency semver to v7.3.8 ([#820](https://github.com/netlify/framework-info/issues/820)) ([33d106e](https://github.com/netlify/framework-info/commit/33d106e08bdb1e9ec5cdcfb7862a1c6f02a353aa))
* use correct icon for Remix framework ([#811](https://github.com/netlify/framework-info/issues/811)) ([9a6fb03](https://github.com/netlify/framework-info/commit/9a6fb037d137100b8f58617e9c643cbf2256ccee))

## [9.3.0](https://github.com/netlify/framework-info/compare/v9.2.0...v9.3.0) (2022-10-04)


### Features

* add a light-theme friendly logo for harp ([#812](https://github.com/netlify/framework-info/issues/812)) ([7cfce5a](https://github.com/netlify/framework-info/commit/7cfce5a5a33e709d06d61c84cf11d9cf5d698330))
* add detection for SolidJS ([#813](https://github.com/netlify/framework-info/issues/813)) ([b06c7df](https://github.com/netlify/framework-info/commit/b06c7df5ea262a41d35cc07602144f97680ea6d5))
* replace parcel logo name with parcel icon ([#808](https://github.com/netlify/framework-info/issues/808)) ([8a6260f](https://github.com/netlify/framework-info/commit/8a6260fd0360ccaefc3ecdb14b307b228e4c18d0))

### Bug Fixes

* updated SvelteKit framework info ([#818](https://github.com/netlify/framework-info/issues/818))
  ([acd85cf](https://github.com/netlify/framework-info/commit/acd85cf798a7f9ab169dc5e62dd5543e0c185d29))

## [9.2.0](https://github.com/netlify/framework-info/compare/v9.1.1...v9.2.0) (2022-08-09)


### Features

* add framework logos where available ([#802](https://github.com/netlify/framework-info/issues/802)) ([a6a1a22](https://github.com/netlify/framework-info/commit/a6a1a22ba150ce9864f8d3f7e10b98f2f9c03ef7))
* add Gatsby logo to returned framework info ([#797](https://github.com/netlify/framework-info/issues/797)) ([2a1ee73](https://github.com/netlify/framework-info/commit/2a1ee739535e0ebb209d14c56f4205db2229de9c))


### Bug Fixes

* fixed typo in qwik excluded dependency ([#805](https://github.com/netlify/framework-info/issues/805)) ([8a4352d](https://github.com/netlify/framework-info/commit/8a4352d1540556ad85c282bd24a0436243e07561))

## [9.1.1](https://github.com/netlify/framework-info/compare/v9.1.0...v9.1.1) (2022-07-17)


### Bug Fixes

* **deps:** update dependency is-plain-obj to v4.1.0 ([#781](https://github.com/netlify/framework-info/issues/781)) ([3ca96f2](https://github.com/netlify/framework-info/commit/3ca96f2fe34da0ce26b50d1801fd5e6f7c45dd38))

## [9.1.0](https://github.com/netlify/framework-info/compare/v9.0.2...v9.1.0) (2022-06-14)


### Features

* add specific vite-powered frameworks ([#777](https://github.com/netlify/framework-info/issues/777)) ([fa305fe](https://github.com/netlify/framework-info/commit/fa305fea08363c13bd39a1cc4ba0530a4e8cac60))


### Bug Fixes

* **deps:** update dependency ajv to v8.11.0 ([#741](https://github.com/netlify/framework-info/issues/741)) ([179f9ec](https://github.com/netlify/framework-info/commit/179f9ec549e903354eab3ae949075256aaac27bd))
* **deps:** update dependency locate-path to v7.1.1 ([#775](https://github.com/netlify/framework-info/issues/775)) ([2eaafa1](https://github.com/netlify/framework-info/commit/2eaafa1ab64cd422667c119b365039cc85339958))
* **deps:** update dependency semver to v7.3.6 ([#748](https://github.com/netlify/framework-info/issues/748)) ([9b91402](https://github.com/netlify/framework-info/commit/9b914026cf6ec4d147236bf1c2aea40b8f352057))
* **deps:** update dependency semver to v7.3.7 ([#753](https://github.com/netlify/framework-info/issues/753)) ([27854a3](https://github.com/netlify/framework-info/commit/27854a3d8af478c7f4c40cdeff7054d941749a96))

### [9.0.2](https://github.com/netlify/framework-info/compare/v9.0.1...v9.0.2) (2022-02-21)


### Bug Fixes

* **deps:** update dependency locate-path to v7.1.0 ([#709](https://github.com/netlify/framework-info/issues/709)) ([236e473](https://github.com/netlify/framework-info/commit/236e4734b064ccf058125b181d585cbfeaf05521))
* **deps:** update dependency read-pkg-up to v9.1.0 ([#710](https://github.com/netlify/framework-info/issues/710)) ([b7e075f](https://github.com/netlify/framework-info/commit/b7e075f3fd79ffb65a93e12ede75d9bfdceaf8aa))

### [9.0.1](https://github.com/netlify/framework-info/compare/v9.0.0...v9.0.1) (2022-02-07)


### Bug Fixes

* **deps:** update dependency ajv to v8.10.0 ([#697](https://github.com/netlify/framework-info/issues/697)) ([a21770a](https://github.com/netlify/framework-info/commit/a21770ae786bcf0ed5ed91d627b395976612d106))
* **deps:** update dependency filter-obj to v3 ([#699](https://github.com/netlify/framework-info/issues/699)) ([5a32463](https://github.com/netlify/framework-info/commit/5a324633cacbef197bf4f0d0b0f61670a8645026))
* **deps:** update dependency is-plain-obj to v4 ([#700](https://github.com/netlify/framework-info/issues/700)) ([3db4a32](https://github.com/netlify/framework-info/commit/3db4a32f0b9d20149823f82246dc85b845f5aac0))
* **deps:** update dependency locate-path to v7 ([#701](https://github.com/netlify/framework-info/issues/701)) ([dac0c7b](https://github.com/netlify/framework-info/commit/dac0c7b93fcff1ae7d647b9f8d3795a07af65917))
* **deps:** update dependency p-filter to v3 ([#691](https://github.com/netlify/framework-info/issues/691)) ([5143fd1](https://github.com/netlify/framework-info/commit/5143fd1859b731e6ad09d6e73badeb48cecc1f57))
* **deps:** update dependency p-locate to v6 ([#692](https://github.com/netlify/framework-info/issues/692)) ([14a0feb](https://github.com/netlify/framework-info/commit/14a0feb415b078771d0cf36d2a9e16fadcc7c4c0))
* **deps:** update dependency read-pkg-up to v9 ([#703](https://github.com/netlify/framework-info/issues/703)) ([f7dd862](https://github.com/netlify/framework-info/commit/f7dd8623dfdbadadc3edc2bf5d33c372c38d4e40))

## [9.0.0](https://github.com/netlify/framework-info/compare/v8.0.2...v9.0.0) (2022-01-19)


### ⚠ BREAKING CHANGES

* use pure ES modules (#577)

### Miscellaneous Chores

* use pure ES modules ([#577](https://github.com/netlify/framework-info/issues/577)) ([2d3cf6a](https://github.com/netlify/framework-info/commit/2d3cf6a610bedb9dd8938d2b7e9ac6fe17247db0))

### [8.0.2](https://github.com/netlify/framework-info/compare/v8.0.1...v8.0.2) (2022-01-17)


### Bug Fixes

* **deps:** update dependency ajv to v8.9.0 ([#670](https://github.com/netlify/framework-info/issues/670)) ([9e29378](https://github.com/netlify/framework-info/commit/9e29378ab7adee8e692b5e158e4bef1a938f26f7))

### [8.0.1](https://github.com/netlify/framework-info/compare/v8.0.0...v8.0.1) (2022-01-12)


### Bug Fixes

* **remix:** use correct configuration ([#663](https://github.com/netlify/framework-info/issues/663)) ([e35f96e](https://github.com/netlify/framework-info/commit/e35f96eaa410274153a4436638cc74a9f9acc747))

## [8.0.0](https://github.com/netlify/framework-info/compare/v7.0.0...v8.0.0) (2022-01-10)


### ⚠ BREAKING CHANGES

* add Remix, make dev port optional (#658)

### Features

* add Remix, make dev port optional ([#658](https://github.com/netlify/framework-info/issues/658)) ([0c4e5bd](https://github.com/netlify/framework-info/commit/0c4e5bdb80af49fc37f15626a2d0acb8d3d20b11))

## [7.0.0](https://www.github.com/netlify/framework-info/compare/v6.1.0...v7.0.0) (2021-12-14)


### ⚠ BREAKING CHANGES

* drop support for `next` < 10.0.9 and @netlify/plugin-nextjs < 4.0.0 (#606)

### Features

* drop support for `next` < 10.0.9 and @netlify/plugin-nextjs < 4.0.0 ([#606](https://www.github.com/netlify/framework-info/issues/606)) ([5949a88](https://www.github.com/netlify/framework-info/commit/5949a886f90ea4d0cf645a2a7d357af4ae9db359))


### Bug Fixes

* remove `--ignore-scripts` from `npm publish` in prereleases ([#589](https://www.github.com/netlify/framework-info/issues/589)) ([481d3e5](https://www.github.com/netlify/framework-info/commit/481d3e5a308a804188a5d8ceb772f7a48268e4e2))

## [6.1.0](https://www.github.com/netlify/framework-info/compare/v6.0.0...v6.1.0) (2021-12-06)


### Features

* process JSON files at build time ([#578](https://www.github.com/netlify/framework-info/issues/578)) ([c1eaed6](https://www.github.com/netlify/framework-info/commit/c1eaed6b28de9d4136a40ae023c656b138641cf8))

## [6.0.0](https://www.github.com/netlify/framework-info/compare/v5.11.0...v6.0.0) (2021-11-24)


### ⚠ BREAKING CHANGES

* drop support for Node 10 (#571)

### Bug Fixes

* **deps:** update dependency ajv to v8.8.0 ([#562](https://www.github.com/netlify/framework-info/issues/562)) ([27d37d8](https://www.github.com/netlify/framework-info/commit/27d37d81f63c36c5a5a3260bb3a084cb18aa00c7))


### Miscellaneous Chores

* drop support for Node 10 ([#571](https://www.github.com/netlify/framework-info/issues/571)) ([576368d](https://www.github.com/netlify/framework-info/commit/576368de4545a7b6d6e2361e929fedc4bb893dad))

## [5.11.0](https://www.github.com/netlify/framework-info/compare/v5.10.0...v5.11.0) (2021-10-11)


### Features

* add Nuxt 3 ([#445](https://www.github.com/netlify/framework-info/issues/445)) ([39f9e3f](https://www.github.com/netlify/framework-info/commit/39f9e3fff4370a23f1d62f76cc07bfda3b20e59b))

## [5.10.0](https://www.github.com/netlify/framework-info/compare/v5.9.2...v5.10.0) (2021-10-11)


### Features

* **gatsby:** set node version to 14 for build and functions ([#413](https://www.github.com/netlify/framework-info/issues/413)) ([c4bd400](https://www.github.com/netlify/framework-info/commit/c4bd400647e389c4f4d0454a5f1926cb6e8d84da))

### [5.9.2](https://www.github.com/netlify/framework-info/compare/v5.9.1...v5.9.2) (2021-09-20)


### Bug Fixes

* **deps:** update dependency ajv to v8.6.3 ([#407](https://www.github.com/netlify/framework-info/issues/407)) ([7c67a75](https://www.github.com/netlify/framework-info/commit/7c67a759d2f507d43bd7058806dbb5cf87b1d159))

### [5.9.1](https://www.github.com/netlify/framework-info/compare/v5.9.0...v5.9.1) (2021-08-18)


### Bug Fixes

* **sveltekit:** specify better output location ([#380](https://www.github.com/netlify/framework-info/issues/380)) ([9b9acea](https://www.github.com/netlify/framework-info/commit/9b9acea4f8505243275e957f166dacda220a5a2d))

## [5.9.0](https://www.github.com/netlify/framework-info/compare/v5.8.0...v5.9.0) (2021-08-17)


### Features

* **gatsby:** precompile functions in develop ([#378](https://www.github.com/netlify/framework-info/issues/378)) ([74f5831](https://www.github.com/netlify/framework-info/commit/74f58312c75e6e8e89ebbfa3ec6d80419a2dc120))

## [5.8.0](https://www.github.com/netlify/framework-info/compare/v5.7.3...v5.8.0) (2021-08-03)


### Features

* add auto installed plugin for gatsby ([#299](https://www.github.com/netlify/framework-info/issues/299)) ([d93a1c6](https://www.github.com/netlify/framework-info/commit/d93a1c605c65582e31d86ce97a2c3d2c0366be32))

### [5.7.3](https://www.github.com/netlify/framework-info/compare/v5.7.2...v5.7.3) (2021-08-02)


### Bug Fixes

* **dev:** add list of excluded dev commands ([#363](https://www.github.com/netlify/framework-info/issues/363)) ([f5c9bb6](https://www.github.com/netlify/framework-info/commit/f5c9bb6eefbf36e183144a97ed0a34301eed5ec0))

### [5.7.2](https://www.github.com/netlify/framework-info/compare/v5.7.1...v5.7.2) (2021-07-13)


### Bug Fixes

* **dev-detection:** prioritize dev over serve ([#348](https://www.github.com/netlify/framework-info/issues/348)) ([6667e9f](https://www.github.com/netlify/framework-info/commit/6667e9f5cade41fc8b556d800ce1e8e1a8fd2e2d))

### [5.7.1](https://www.github.com/netlify/framework-info/compare/v5.7.0...v5.7.1) (2021-07-12)


### Bug Fixes

* sort framework ids when reporting an error ([#342](https://www.github.com/netlify/framework-info/issues/342)) ([e315dfb](https://www.github.com/netlify/framework-info/commit/e315dfb2f41cb2c5840a38ca581b19b36694e83d))

## [5.7.0](https://www.github.com/netlify/framework-info/compare/v5.6.1...v5.7.0) (2021-07-12)


### Features

* add Astro ([#338](https://www.github.com/netlify/framework-info/issues/338)) ([53a30bb](https://www.github.com/netlify/framework-info/commit/53a30bbff14c828e3641cdbc7c325355cd15b73f))

### [5.6.1](https://www.github.com/netlify/framework-info/compare/v5.6.0...v5.6.1) (2021-07-11)


### Bug Fixes

* **framework-vite:** remove HTTP polling ([#340](https://www.github.com/netlify/framework-info/issues/340)) ([d5245cd](https://www.github.com/netlify/framework-info/commit/d5245cd65983fcc974d1099f2f4fca92f981b8af))

## [5.6.0](https://www.github.com/netlify/framework-info/compare/v5.5.0...v5.6.0) (2021-07-05)


### Features

* add Zola ([#326](https://www.github.com/netlify/framework-info/issues/326)) ([2f571d9](https://www.github.com/netlify/framework-info/commit/2f571d908f82bc7b555c38d5cf5be790b5600c63))


### Bug Fixes

* **deps:** update dependency ajv to v8.6.1 ([6051f44](https://www.github.com/netlify/framework-info/commit/6051f443995fa54f3e54cfa20e3f88a539b855a5))

## [5.5.0](https://www.github.com/netlify/framework-info/compare/v5.4.0...v5.5.0) (2021-06-30)


### Features

* add detection of Next with Nx ([#327](https://www.github.com/netlify/framework-info/issues/327)) ([16f2c41](https://www.github.com/netlify/framework-info/commit/16f2c413d7b0dfef7146dafadf51ac7d8a15c43c))

## [5.4.0](https://www.github.com/netlify/framework-info/compare/v5.3.0...v5.4.0) (2021-06-27)


### Features

* add WMR ([#315](https://www.github.com/netlify/framework-info/issues/315)) ([393e950](https://www.github.com/netlify/framework-info/commit/393e95039958b6830e9890d478020f68acde2bc8))

## [5.3.0](https://www.github.com/netlify/framework-info/compare/v5.2.0...v5.3.0) (2021-06-15)


### Features

* add SvelteKit ([#308](https://www.github.com/netlify/framework-info/issues/308)) ([95d1ca9](https://www.github.com/netlify/framework-info/commit/95d1ca9a6f94bf76d5aa8494ee6f433ed236c15d))

## [5.2.0](https://www.github.com/netlify/framework-info/compare/v5.1.4...v5.2.0) (2021-06-13)


### Features

* Add Cecil ([#300](https://www.github.com/netlify/framework-info/issues/300)) ([7019a64](https://www.github.com/netlify/framework-info/commit/7019a6431bc6e69cb54c6143ceda6b8c2311c66c))

### [5.1.4](https://www.github.com/netlify/framework-info/compare/v5.1.3...v5.1.4) (2021-06-07)


### Bug Fixes

* **deps:** update dependency ajv to v8.6.0 ([cd263e8](https://www.github.com/netlify/framework-info/commit/cd263e8664df09753594bb8d98fcb6e0f34ee2b8))

### [5.1.3](https://www.github.com/netlify/framework-info/compare/v5.1.2...v5.1.3) (2021-06-02)


### Bug Fixes

* **nuxt:** update name ([#283](https://www.github.com/netlify/framework-info/issues/283)) ([f5486e5](https://www.github.com/netlify/framework-info/commit/f5486e569fe77af56e7f770103bcc51785899012))

### [5.1.2](https://www.github.com/netlify/framework-info/compare/v5.1.1...v5.1.2) (2021-05-31)


### Bug Fixes

* **jekyll:** add additional config files ([#281](https://www.github.com/netlify/framework-info/issues/281)) ([461aebb](https://www.github.com/netlify/framework-info/commit/461aebbf3ad7d56689890171dafbea01ae32845b))

### [5.1.1](https://www.github.com/netlify/framework-info/compare/v5.1.0...v5.1.1) (2021-05-31)


### Bug Fixes

* **deps:** update dependency is-plain-obj to v3 ([#277](https://www.github.com/netlify/framework-info/issues/277)) ([ec61f07](https://www.github.com/netlify/framework-info/commit/ec61f075605196c228d9829159689165f3eb64dd))
* **deps:** update dependency locate-path to v6 ([#278](https://www.github.com/netlify/framework-info/issues/278)) ([66fb671](https://www.github.com/netlify/framework-info/commit/66fb671ee1364b67384aa39f5e9f06b089a30f31))
* **deps:** update dependency p-locate to v5 ([#279](https://www.github.com/netlify/framework-info/issues/279)) ([1d1718a](https://www.github.com/netlify/framework-info/commit/1d1718a0ef18bb61fc12182b68d4946b2292aafa))

## [5.1.0](https://www.github.com/netlify/framework-info/compare/v5.0.0...v5.1.0) (2021-05-30)


### Features

* **frameworks:** Adds framework detection json for RedwoodJS ([d62f8ba](https://www.github.com/netlify/framework-info/commit/d62f8ba6895295d69638ff47446e0a1e7aa9131a))

## [5.0.0](https://www.github.com/netlify/framework-info/compare/v4.1.1...v5.0.0) (2021-05-27)


### ⚠ BREAKING CHANGES

* drop support for Node.js 8 (#258)

### Miscellaneous Chores

* drop support for Node.js 8 ([#258](https://www.github.com/netlify/framework-info/issues/258)) ([80c626e](https://www.github.com/netlify/framework-info/commit/80c626e98cb6d2801639f4b78a0b2007b6b68474))

### [4.1.1](https://www.github.com/netlify/framework-info/compare/v4.1.0...v4.1.1) (2021-05-14)


### Bug Fixes

* **deps:** update dependency ajv to v8.4.0 ([deb2935](https://www.github.com/netlify/framework-info/commit/deb2935b34da5df822501da6ba6022fc0552908a))

## [4.1.0](https://www.github.com/netlify/framework-info/compare/v4.0.1...v4.1.0) (2021-05-11)


### Features

* add Blitz.js support ([#243](https://www.github.com/netlify/framework-info/issues/243)) ([fb01ff5](https://www.github.com/netlify/framework-info/commit/fb01ff504f4a399405c5e1f8916f3413f468d2db))

### [4.0.1](https://www.github.com/netlify/framework-info/compare/v4.0.0...v4.0.1) (2021-05-09)


### Bug Fixes

* **deps:** update dependency ajv to v8.2.0 ([#231](https://www.github.com/netlify/framework-info/issues/231)) ([4c1b29d](https://www.github.com/netlify/framework-info/commit/4c1b29db48623f862e4cec72a983cca4064bc96a))

## [4.0.0](https://www.github.com/netlify/framework-info/compare/v3.3.0...v4.0.0) (2021-04-26)


### ⚠ BREAKING CHANGES

* **bin:** remove the cli execution

### Miscellaneous Chores

* **bin:** remove the cli execution ([7f09120](https://www.github.com/netlify/framework-info/commit/7f0912062774f0ee06ad10e47c885f402971a953))

## [3.3.0](https://www.github.com/netlify/framework-info/compare/v3.2.1...v3.3.0) (2021-04-06)


### Features

* **frameworks:** add Vite ([#206](https://www.github.com/netlify/framework-info/issues/206)) ([15ca31a](https://www.github.com/netlify/framework-info/commit/15ca31a62ac4c16e48e0c5cef199d00c097fd5d5))

### [3.2.1](https://www.github.com/netlify/framework-info/compare/v3.2.0...v3.2.1) (2021-03-29)


### Bug Fixes

* **deps:** update dependency ajv to v8 ([#192](https://www.github.com/netlify/framework-info/issues/192)) ([7c81511](https://www.github.com/netlify/framework-info/commit/7c8151152d024ac145a1bfe4d7ac7878eb071e70))

## [3.2.0](https://www.github.com/netlify/framework-info/compare/v3.1.3...v3.2.0) (2021-03-16)


### Features

* add static assets directory ([#177](https://www.github.com/netlify/framework-info/issues/177)) ([e830e07](https://www.github.com/netlify/framework-info/commit/e830e0764a85c03034e2d6dbdd1d0c0247666d42))

### [3.1.3](https://www.github.com/netlify/framework-info/compare/v3.1.2...v3.1.3) (2021-03-01)


### Bug Fixes

* support browsers without globalThis ([#152](https://www.github.com/netlify/framework-info/issues/152)) ([2f7306d](https://www.github.com/netlify/framework-info/commit/2f7306dce002301bc114d1770591221e1c3c6149))

### [3.1.2](https://www.github.com/netlify/framework-info/compare/v3.1.1...v3.1.2) (2021-02-24)


### Bug Fixes

* Update the build command and directory for Angular.js ([edd9212](https://www.github.com/netlify/framework-info/commit/edd9212d4b2dc33265ee96510f9aa4c47e2753ac))

### [3.1.1](https://www.github.com/netlify/framework-info/compare/v3.1.0...v3.1.1) (2021-02-18)


### Bug Fixes

* fix `files` in `package.json` ([1751eab](https://www.github.com/netlify/framework-info/commit/1751eabdb96dab3b68b16b07055ce0a5893d14f5))

## [3.1.0](https://www.github.com/netlify/framework-info/compare/v3.0.0...v3.1.0) (2021-02-11)


### Features

* **dev:** add polling strategies ([#125](https://www.github.com/netlify/framework-info/issues/125)) ([4c553e8](https://www.github.com/netlify/framework-info/commit/4c553e8be40f6b01948ccbeb56ee58f86dd6bfb0))

## [3.0.0](https://www.github.com/netlify/framework-info/compare/v2.3.0...v3.0.0) (2021-02-10)


### ⚠ BREAKING CHANGES

* rename title to name (#139)
* rename name property to id (#137)

### Features

* rename name property to id ([#137](https://www.github.com/netlify/framework-info/issues/137)) ([bf298d2](https://www.github.com/netlify/framework-info/commit/bf298d2ce4e4ca010a4cf05642aac952f0afa675))
* rename title to name ([#139](https://www.github.com/netlify/framework-info/issues/139)) ([2b444e0](https://www.github.com/netlify/framework-info/commit/2b444e071b4a2b5c82afa639240c7014bc3a865c))

## [2.3.0](https://www.github.com/netlify/framework-info/compare/v2.2.0...v2.3.0) (2021-02-10)


### Features

* add frameworks titles ([#134](https://www.github.com/netlify/framework-info/issues/134)) ([4aec35e](https://www.github.com/netlify/framework-info/commit/4aec35e7917d98a27ac9fe9f8c0b35b652fad594))

## [2.2.0](https://www.github.com/netlify/framework-info/compare/v2.1.1...v2.2.0) (2021-02-08)


### Features

* add nodeVersion option ([#124](https://www.github.com/netlify/framework-info/issues/124)) ([647f94b](https://www.github.com/netlify/framework-info/commit/647f94b15c642c65c6cd1d74396ac17c8d02c8e4))

### [2.1.1](https://www.github.com/netlify/framework-info/compare/v2.1.0...v2.1.1) (2021-01-25)


### Bug Fixes

* remove duplicate plugins entry from grunt.json ([#116](https://www.github.com/netlify/framework-info/issues/116)) ([2721217](https://www.github.com/netlify/framework-info/commit/2721217dfa4f9525f02465dfdc89006b5b6bdd83))

## [2.1.0](https://www.github.com/netlify/framework-info/compare/v2.0.0...v2.1.0) (2021-01-25)


### Features

* add plugins detection ([#111](https://www.github.com/netlify/framework-info/issues/111)) ([db4e8f5](https://www.github.com/netlify/framework-info/commit/db4e8f5eaeb3f7f05f7f2c82ec94fdc8312322d2))

## [2.0.0](https://www.github.com/netlify/framework-info/compare/v1.1.2...v2.0.0) (2021-01-07)


### ⚠ BREAKING CHANGES

* rename watch to dev (#96)
* add build command detection (#92)

### Features

* add build command detection ([#92](https://www.github.com/netlify/framework-info/issues/92)) ([4d5c35e](https://www.github.com/netlify/framework-info/commit/4d5c35ee948f5a97a0896cb1907a58a85ca6588b))


### Bug Fixes

* **docs:** update readme ([#98](https://www.github.com/netlify/framework-info/issues/98)) ([8c734df](https://www.github.com/netlify/framework-info/commit/8c734df7bdf30e5cdf7e2bf49860671901edc45b))
* rename watch to dev ([#96](https://www.github.com/netlify/framework-info/issues/96)) ([58aadd5](https://www.github.com/netlify/framework-info/commit/58aadd50f66bf54e43adf6c5fc2c6a0b8ae65965))
* sort preferred scripts ([#99](https://www.github.com/netlify/framework-info/issues/99)) ([d7d9093](https://www.github.com/netlify/framework-info/commit/d7d9093dde7b69a959a14280647b4de0b67f616a))
* **create-react-app:** update build directory ([#94](https://www.github.com/netlify/framework-info/issues/94)) ([54222d5](https://www.github.com/netlify/framework-info/commit/54222d52ed4e18bca3322744277b3ce4d372fd09))

### [1.1.2](https://www.github.com/netlify/framework-info/compare/v1.1.1...v1.1.2) (2020-12-20)


### Bug Fixes

* **eleventy:** update watch command ([#74](https://www.github.com/netlify/framework-info/issues/74)) ([26a3b71](https://www.github.com/netlify/framework-info/commit/26a3b71c04d02c0a1d1baa3dbbc69745adc6683d))
* **watch-command:** return watch commands in consistent order ([#76](https://www.github.com/netlify/framework-info/issues/76)) ([eb9de6d](https://www.github.com/netlify/framework-info/commit/eb9de6db1c1a1f2e9e9660a3e6c5ea79e561c679))

### [1.1.1](https://www.github.com/netlify/framework-info/compare/v1.1.0...v1.1.1) (2020-12-17)


### Bug Fixes

* **angular:** update watch command ([#72](https://www.github.com/netlify/framework-info/issues/72)) ([fb5425f](https://www.github.com/netlify/framework-info/commit/fb5425f49fcd11eac1043a0a620300be53870628))

## [1.1.0](https://www.github.com/netlify/framework-info/compare/v1.0.0...v1.1.0) (2020-12-16)


### Features

* make the library browser compatible ([#58](https://www.github.com/netlify/framework-info/issues/58)) ([b172413](https://www.github.com/netlify/framework-info/commit/b17241389e4ead400b8f7bfddd35496b260d6f25))

## [1.0.0](https://www.github.com/netlify/framework-info/compare/v0.3.2...v1.0.0) (2020-12-15)


### ⚠ BREAKING CHANGES

* remove ignoredWatchCommand option (#59)

### Code Refactoring

* remove ignoredWatchCommand option ([#59](https://www.github.com/netlify/framework-info/issues/59)) ([defd809](https://www.github.com/netlify/framework-info/commit/defd80956006a0b3ff65e265115d662c4bd8b679))

## [v0.3.2](https://github.com/netlify/framework-info/compare/v0.3.1...v0.3.2)

### Merged

- chore(deps): update dependency @netlify/eslint-config-node to v2
  [`#60`](https://github.com/netlify/framework-info/pull/60)
- chore(deps): lock file maintenance [`#61`](https://github.com/netlify/framework-info/pull/61)

## [v0.3.1](https://github.com/netlify/framework-info/compare/v0.3.0...v0.3.1) - 2020-12-10

### Merged

- fix: add missing frameworks to main.js [`#57`](https://github.com/netlify/framework-info/pull/57)

## [v0.3.0](https://github.com/netlify/framework-info/compare/v0.2.0...v0.3.0) - 2020-12-10

### Merged

- chore: add commit linting [`#55`](https://github.com/netlify/framework-info/pull/55)
- chore: add pr labeler [`#54`](https://github.com/netlify/framework-info/pull/54)
- chore: fix version script [`#53`](https://github.com/netlify/framework-info/pull/53)
- feat: add quasar-v0.17 [`#52`](https://github.com/netlify/framework-info/pull/52)
- feat: add docusaurus v2 [`#51`](https://github.com/netlify/framework-info/pull/51)
- fix(docusaurus): add missing BROWSER env variable [`#50`](https://github.com/netlify/framework-info/pull/50)
- chore: gitignore vscode [`#49`](https://github.com/netlify/framework-info/pull/49)
- fix(jsdoc): use typedef instead of dot notation [`#48`](https://github.com/netlify/framework-info/pull/48)
- chore: apply eslint config node [`#47`](https://github.com/netlify/framework-info/pull/47)
- fix(contributing): use correct repo name [`#45`](https://github.com/netlify/framework-info/pull/45)
- chore: use eslint config node [`#46`](https://github.com/netlify/framework-info/pull/46)
- chore(deps): lock file maintenance [`#43`](https://github.com/netlify/framework-info/pull/43)
- chore(deps): lock file maintenance [`#39`](https://github.com/netlify/framework-info/pull/39)
- chore(deps): lock file maintenance [`#38`](https://github.com/netlify/framework-info/pull/38)
- chore(deps): lock file maintenance [`#37`](https://github.com/netlify/framework-info/pull/37)
- chore(deps): lock file maintenance [`#36`](https://github.com/netlify/framework-info/pull/36)
- github tools: fix fossa workflow file [`#35`](https://github.com/netlify/framework-info/pull/35)
- chore(deps): lock file maintenance [`#34`](https://github.com/netlify/framework-info/pull/34)
- Add `--fail` flag to `curl` for Codecov [`#33`](https://github.com/netlify/framework-info/pull/33)

### Commits

- Fix lock file [`a1d7de4`](https://github.com/netlify/framework-info/commit/a1d7de4c64f9e70f14635aab7aaa3f71d15aa3e4)
- fix github actions workflow file for fossa
  [`9ab34c1`](https://github.com/netlify/framework-info/commit/9ab34c165dd8efeb582a94f16f0f842c52a6f3dc)

## [v0.2.0](https://github.com/netlify/framework-info/compare/v0.1.3...v0.2.0) - 2020-10-29

### Merged

- Add `hasFramework()` [`#31`](https://github.com/netlify/framework-info/pull/31)
- chore(deps): update dependency eslint-config-prettier to v6.14.0
  [`#29`](https://github.com/netlify/framework-info/pull/29)
- Add `is-plain-obj` to `renovate.json5` [`#28`](https://github.com/netlify/framework-info/pull/28)
- chore(deps): update dependency eslint-config-prettier to v6.13.0
  [`#26`](https://github.com/netlify/framework-info/pull/26)
- chore(deps): update dependency ajv to v6.12.6 [`#25`](https://github.com/netlify/framework-info/pull/25)
- chore(deps): update dependency gh-release to v4.0.3 [`#24`](https://github.com/netlify/framework-info/pull/24)
- Add `del` to `renovate.json5` [`#23`](https://github.com/netlify/framework-info/pull/23)
- chore(deps): update dependency eslint-plugin-import to v2.22.1
  [`#21`](https://github.com/netlify/framework-info/pull/21)
- chore(deps): update dependency eslint-config-prettier to v6.12.0
  [`#20`](https://github.com/netlify/framework-info/pull/20)
- chore(deps): update dependency gh-release to v4.0.2 [`#19`](https://github.com/netlify/framework-info/pull/19)
- chore(deps): update dependency auto-changelog to v2.2.1 [`#18`](https://github.com/netlify/framework-info/pull/18)
- Add `yargs` to `renovate.json5` [`#17`](https://github.com/netlify/framework-info/pull/17)
- chore(deps): update dependency ajv to v6.12.5 [`#14`](https://github.com/netlify/framework-info/pull/14)
- chore(deps): update dependency gh-release to v4 [`#15`](https://github.com/netlify/framework-info/pull/15)
- chore(deps): lock file maintenance [`#13`](https://github.com/netlify/framework-info/pull/13)
- chore(deps): lock file maintenance [`#11`](https://github.com/netlify/framework-info/pull/11)
- chore(deps): lock file maintenance [`#9`](https://github.com/netlify/framework-info/pull/9)
- chore(deps): lock file maintenance [`#6`](https://github.com/netlify/framework-info/pull/6)

### Commits

- Merge pull request #30 from netlify/renovate/actions-checkout-2.x
  [`7dbe1c0`](https://github.com/netlify/framework-info/commit/7dbe1c03f020ce1dc703b58a756039160078bfe5)
- chore(deps): update actions/checkout action to v2
  [`b9086ab`](https://github.com/netlify/framework-info/commit/b9086ab3a30d727c5e3f7c966fb6772be7a5f2e1)
- Merge pull request #10 from netlify/renovate/lock-file-maintenance
  [`6d87bdf`](https://github.com/netlify/framework-info/commit/6d87bdf9971c5bec2614d9cc4d82c27b596fb88d)

## [v0.1.3](https://github.com/netlify/framework-info/compare/v0.1.2...v0.1.3) - 2020-08-07

### Commits

- Dummy commit [`6e2dc72`](https://github.com/netlify/framework-info/commit/6e2dc72a98986b239e5549731f2904e97908bdcd)

## [v0.1.2](https://github.com/netlify/framework-info/compare/v0.1.1...v0.1.2) - 2020-08-07

## [v0.1.1](https://github.com/netlify/framework-info/compare/v0.1.0...v0.1.1) - 2020-08-07

## v0.1.0 - 2020-08-07

### Merged

- github tools: add fossa license scanning [`#1`](https://github.com/netlify/framework-info/pull/1)

### Commits

- Init [`fc3e3d7`](https://github.com/netlify/framework-info/commit/fc3e3d76dae04fb1f017eb1b11567d2a8f298125)
- Add frameworks [`03ed590`](https://github.com/netlify/framework-info/commit/03ed59041abcbc10fcd9ffbe9bc212bd9f955470)
- chore(deps): lock file maintenance
  [`6bc61ba`](https://github.com/netlify/framework-info/commit/6bc61baae3968974d4496faed01c84efd38feb74)