## [1.2.0](https://github.com/megasanjay/devmoji/compare/v1.1.0...v1.2.0) (2022-10-24)


### Features

* add technologist gitmoji ([cf1d208](https://github.com/megasanjay/devmoji/commit/cf1d20861a1e3074a1f83f975ab6605a44061bf7))

## [1.1.0](https://github.com/megasanjay/devmoji/compare/v1.0.0...v1.1.0) (2022-10-20)


### Features

* release ([6e6d820](https://github.com/megasanjay/devmoji/commit/6e6d82019e590da053758ea989d8b75f6c6c022a))


### Other

* update readme ([3b245ef](https://github.com/megasanjay/devmoji/commit/3b245ef2acf6c3fadc997ca13219ffeceade6305))
* update wording ([e041492](https://github.com/megasanjay/devmoji/commit/e0414928f3ff3a4c1e3568a5280fa4babfe155d9))

## 1.0.0 (2022-10-20)


### ⚠ BREAKING CHANGES

* **commit:** added breaking change support 😄
* devmoji can now be used as a prepare-commit-msg hook to
automagically add emojis to commit messages

### Features

* ✨ added commit linting! ([2d52f2c](https://github.com/megasanjay/devmoji/commit/2d52f2c8fe1e8c49000293e1cb9b3b13f47277d0))
* ✨ added semantic-release ([a597cd1](https://github.com/megasanjay/devmoji/commit/a597cd1167911a3cdc6d42f62e30106519bc27c0))
* ✨ added support for fixup! & match! comments ([155dee2](https://github.com/megasanjay/devmoji/commit/155dee208a4651234283884f570075aaf3eaa90e))
* ✨ added support for git hooks ([799f156](https://github.com/megasanjay/devmoji/commit/799f1569b441a2ab708ad18df46f4bd969534514))
* ✨ devmoji package ([e7e2b61](https://github.com/megasanjay/devmoji/commit/e7e2b61105bf86305d2ec632db731b22c0008370))
* ✨ monorepo setup ([dade671](https://github.com/megasanjay/devmoji/commit/dade671a3a076c2e6ff81828083c231f1a444c15))
* ✨ refactored config files and added runtime validation ([cc94e2c](https://github.com/megasanjay/devmoji/commit/cc94e2c71e7a79422dde32faab21313c60331631))
* ✨ scope to allow digit ([#126](https://github.com/megasanjay/devmoji/issues/126)) ([cb31dda](https://github.com/megasanjay/devmoji/commit/cb31ddae5899442e368f7fe8223a289371f8495a))
* update emoji list ([70509f6](https://github.com/megasanjay/devmoji/commit/70509f6ca52a0eecd7d661a51b1eec25d072b29f))
* **cli:** ✨ added cli for working with devmoji 🚀 ([8f16492](https://github.com/megasanjay/devmoji/commit/8f16492295908f26db5f5e4b93a075f516629a13))
* **commit:** 💥 ✨ added support for ! in a breaking change header ([23ec3c9](https://github.com/megasanjay/devmoji/commit/23ec3c9dc6cc260b9147cb88e748a0c3aa7d58f4))
* **config:** ✨ ⚙ ➕ devmojis for config, add, remove ([faa3aac](https://github.com/megasanjay/devmoji/commit/faa3aacc05cccb212da84459321453b91414dffe))
* ✨ we now support scope based devmojis and --color for --log ([a3df981](https://github.com/megasanjay/devmoji/commit/a3df981a205ca1def58b57e3f408274500811fa1))
* **config:** ✨ added devmoji configs ([4379667](https://github.com/megasanjay/devmoji/commit/43796674bfb9061995a687ea90b7b3c81226d015))
* **emoji:** :sparkles: added script to fetch github and gitmoji ([aecf9df](https://github.com/megasanjay/devmoji/commit/aecf9dfa41350520788e1a57657eff16b13434cd))


### Bug Fixes

* **deps:** update dependency chalk to v4 ([#49](https://github.com/megasanjay/devmoji/issues/49)) ([aefa669](https://github.com/megasanjay/devmoji/commit/aefa6691a23e43b34d78bd98aa694b07bebe3dee))
* **deps:** update dependency ts-interface-checker to v0.2.1 ([2262197](https://github.com/megasanjay/devmoji/commit/2262197a33d261930a5b51fba8d73b4bad4e35fc))
* **deps:** update dependency ts-interface-checker to v1.0.2 ([29300b6](https://github.com/megasanjay/devmoji/commit/29300b66ab4c2bb36d9decf84f7dd2bb49d692f2))
* **docs:** :memo: fixed name devmoji ([#157](https://github.com/megasanjay/devmoji/issues/157)) ([86b7d55](https://github.com/megasanjay/devmoji/commit/86b7d55bd13a1b958d80b9df229f9b74d25e8da7))
* **lint:** 🐛 detect BREAKING CHANGE in description. Fixes [#76](https://github.com/megasanjay/devmoji/issues/76) ([a3d5ab0](https://github.com/megasanjay/devmoji/commit/a3d5ab0cafd3366538ca0098669b83712d36a13d))
* **test:** 🐛 🚨 fixup for syntax error ([404dce4](https://github.com/megasanjay/devmoji/commit/404dce4dfb6ffe3dbb7846e649772cbd84176ec2))
* 🐛 --lint shouldn't fail on merge commit message (fixes [#50](https://github.com/megasanjay/devmoji/issues/50)) ([8ba3987](https://github.com/megasanjay/devmoji/commit/8ba3987e180ffd6902162a14ef2f831192e61b62))
* 🐛 🔒️ upgrade minimist which had a security vulnerability ([fc12464](https://github.com/megasanjay/devmoji/commit/fc124643a64967896bab3a5f2edf04e685a9f0c1))
* 🐛 colors are now properly disabled when not on a TTY ([36406c5](https://github.com/megasanjay/devmoji/commit/36406c5382483b650cc2141d8e05b575eed5bd94))
* 🐛 fixed callstack error for Windows ([9f411d2](https://github.com/megasanjay/devmoji/commit/9f411d28c8d71dca331c96e8b8436e5368d809fa))
* 🐛 fixed endless loop on win32 ([a3026e1](https://github.com/megasanjay/devmoji/commit/a3026e1a7742fa5ff3ccaa11fbf51cdd6f310810))
* 🐛 get --config value from Commander.opts() ([a461c2b](https://github.com/megasanjay/devmoji/commit/a461c2bb78340e3d58de3fcedbae3b84afa6b39c))
* 🐛 show correct --version ([959d216](https://github.com/megasanjay/devmoji/commit/959d2164ba2d0f4f64323d2f4dbcc768c32cedad))
* 🐛 use the color option for --log (fixes [#81](https://github.com/megasanjay/devmoji/issues/81)) ([c7370de](https://github.com/megasanjay/devmoji/commit/c7370de7e260156e8c2f97870e6564201658c49c))
* **changelog:** 🐛 fixed changelog scripts on monorepo ([da9f804](https://github.com/megasanjay/devmoji/commit/da9f8048754e16fd2cc470df628b4c49a174aa69))
* **cli:** 🐛 all output now honors --no-color ([a44e628](https://github.com/megasanjay/devmoji/commit/a44e6280510869e00a10552026839139dab0262b))
* **config:** 🐛 ⚙️ added correct search paths for config file ([63d2488](https://github.com/megasanjay/devmoji/commit/63d248832a53163ee54e3f41542d8a59326aa6ce))
* **docs:** 🐛 📚️ updated docs ([667db23](https://github.com/megasanjay/devmoji/commit/667db23c0bf1678151ed64e7d265e15c0a3584e5))
* **docs:** 🐛 📚 updated README.md ([6366bd3](https://github.com/megasanjay/devmoji/commit/6366bd3b437706a9d2d079df2ea7b711ccf943c5))
* **emoji:** 🐛 added support for colorful emoji variations ([dff0ede](https://github.com/megasanjay/devmoji/commit/dff0ede10c186cf8c3abcd8112c01ce0a506ae24))
* **emoji:** 🐛 fixed emoji variations ([2d60115](https://github.com/megasanjay/devmoji/commit/2d6011536c0b6e54980296dc4315553dfa812e63))
* **emoji:** 🐛 use unicode emoji variations when available ([c0ff022](https://github.com/megasanjay/devmoji/commit/c0ff022bb9a53f8f0187164441926a9a2ac76eba))
* **lint:** 🐛 scope and type can by any case. Fixes [#75](https://github.com/megasanjay/devmoji/issues/75) ([8138c84](https://github.com/megasanjay/devmoji/commit/8138c840cb35c8d3513e5ea3eed339337696dc75))
* 🐛 new rollup version and commanderjs ([41ae638](https://github.com/megasanjay/devmoji/commit/41ae638a22c7aae04dc699711b6c56693547169d))
* **security:** 🐛 🔒 upgraded lodash & underscore from security advisory ([d2d39be](https://github.com/megasanjay/devmoji/commit/d2d39bebfb961f1f6d7178b6c8b9fe119c3c5843))


### Documentation

* 📚 📚 first run with conventional-changlog ([6a5ccda](https://github.com/megasanjay/devmoji/commit/6a5ccdab217761d37386cd8aa66b820109676f66))
* 📚️ added badges ([4b4b22e](https://github.com/megasanjay/devmoji/commit/4b4b22e96e9311a27990fd6ed59db1cf79182c94))
* 📚️ added documentation on configuration ([04ee582](https://github.com/megasanjay/devmoji/commit/04ee5827e2d91591d3fd1936b0aaf11d24e374a9))
* 📚️ added screenshots ([0e2183d](https://github.com/megasanjay/devmoji/commit/0e2183d12b0913fc097b878b5f80adcf71df9179))
* 📚️ better docs about git commit hooks ([8f7b36a](https://github.com/megasanjay/devmoji/commit/8f7b36ab0ec7e0623f0e0a597d166749d250912e))
* 📚 created script to generate markdown tabel for the docs ([6e06cb1](https://github.com/megasanjay/devmoji/commit/6e06cb11e1bcd8ce4ee75b65078563fbd381d362))
* 📚 first run with conventional-changlog ([655a4be](https://github.com/megasanjay/devmoji/commit/655a4be3ee2a05d565bc88f490dbac3203eab898))
* 📚️ improved documentation ([f3a5bbd](https://github.com/megasanjay/devmoji/commit/f3a5bbd4f93dcfa7a6bb855e2c541a5fab99649b))
* 📚️ testing gihub releases ([3c74ce8](https://github.com/megasanjay/devmoji/commit/3c74ce8876f89618d71d3a4d90b49c1827a426da))
* 📚️ updated docs with --lint ([0348900](https://github.com/megasanjay/devmoji/commit/034890026260001c21bff5f3e0ddd25b1887884a))
* 📚 updated documentation ([ce8ca0e](https://github.com/megasanjay/devmoji/commit/ce8ca0ec3f19c720aa763f7aad4f31b879482057))
* 📚 updated README.md ([ad79999](https://github.com/megasanjay/devmoji/commit/ad7999991c4719b47e87ba05bddd780735d75321))
* 📚 updated README.md ([7bb5e70](https://github.com/megasanjay/devmoji/commit/7bb5e70d761498ed78440783a8739b4b31e19af5))
* added license [skip ci] ([d58175e](https://github.com/megasanjay/devmoji/commit/d58175ed16715d92ef1f05d7e532d904639fb77a))
* added renovate badge ([5e5cda9](https://github.com/megasanjay/devmoji/commit/5e5cda940b5ddd2c8e433b641370e9694e42823e))
* fixed config example ([9860364](https://github.com/megasanjay/devmoji/commit/9860364b8ed2311685a1a024f8998390b0717280))
* replace yarn install w/ yarn add ([#65](https://github.com/megasanjay/devmoji/issues/65)) ([f9acf3e](https://github.com/megasanjay/devmoji/commit/f9acf3eef951d638fb0d9538aa9a702122071712))
* **todo:** 📚 added todo markdown file ([24b4320](https://github.com/megasanjay/devmoji/commit/24b43203ea071b9ca6f8dc65cbc8587ec0a70814))


### Other

* update name ([0ac2801](https://github.com/megasanjay/devmoji/commit/0ac2801897fcb5179401f1fa1a458e2ad8acd813))
* **deps:** 👷 automerge minor, patch, pin and digest ([578258b](https://github.com/megasanjay/devmoji/commit/578258bdc6151c36b62eee31529fe82dc898e1c8))
* **deps:** 👷 group all non-major updates ([abe0982](https://github.com/megasanjay/devmoji/commit/abe0982a44705c145a6803f465399a8f21ac92ed))
* **deps:** 🔗 update ([979279e](https://github.com/megasanjay/devmoji/commit/979279ebf8bc052c397ff009d1e84e54d4d339f6))
* **deps:** bump ini from 1.3.5 to 1.3.8 ([#91](https://github.com/megasanjay/devmoji/issues/91)) ([79cb9cf](https://github.com/megasanjay/devmoji/commit/79cb9cf84fde05f7bb6fe124aa9d02c5f5f24acd))
* **deps:** bump marked from 1.2.0 to 2.0.0 ([#99](https://github.com/megasanjay/devmoji/issues/99)) ([f6c382b](https://github.com/megasanjay/devmoji/commit/f6c382bc59d914bb87d9c2ce63493d2647cbe335))
* **deps:** bump node-notifier from 8.0.0 to 8.0.1 ([#94](https://github.com/megasanjay/devmoji/issues/94)) ([cf87590](https://github.com/megasanjay/devmoji/commit/cf875905f4f4af7b6329e7ed94caa656c184dce8))
* **deps:** bump npm-user-validate from 1.0.0 to 1.0.1 ([#69](https://github.com/megasanjay/devmoji/issues/69)) ([19ea27c](https://github.com/megasanjay/devmoji/commit/19ea27c6f03ad6e12305310df45d7ec144191457))
* **deps:** bump ssri from 6.0.1 to 6.0.2 ([#104](https://github.com/megasanjay/devmoji/issues/104)) ([27d1d3f](https://github.com/megasanjay/devmoji/commit/27d1d3f8a8c2a9aa729c676820858479138c16b5))
* **deps:** update actions/cache action to v2 ([#71](https://github.com/megasanjay/devmoji/issues/71)) ([a91dbc4](https://github.com/megasanjay/devmoji/commit/a91dbc4523cea6625085452755cc1a4a7df94b03))
* **deps:** update actions/checkout action to v2 ([#72](https://github.com/megasanjay/devmoji/issues/72)) ([717ad15](https://github.com/megasanjay/devmoji/commit/717ad15695555e5876f8acdd8bded57af09cf1dd))
* **deps:** update actions/setup-node action to v2 ([#93](https://github.com/megasanjay/devmoji/issues/93)) ([7cf6c17](https://github.com/megasanjay/devmoji/commit/7cf6c1732628eba9ca3698800532075b337f8222))
* **deps:** update all non-major dependencies ([#12](https://github.com/megasanjay/devmoji/issues/12)) ([2f7236f](https://github.com/megasanjay/devmoji/commit/2f7236ff70936fdf20d7b721c8f168f41692d757))
* **deps:** update all non-major dependencies ([#14](https://github.com/megasanjay/devmoji/issues/14)) ([e2e724b](https://github.com/megasanjay/devmoji/commit/e2e724b4a5b9a3fc30ef4dcb2288c754b8c0409c))
* **deps:** update all non-major dependencies ([#15](https://github.com/megasanjay/devmoji/issues/15)) ([3df8504](https://github.com/megasanjay/devmoji/commit/3df85041b1e9bbe5faf06572cb9f5c5043b48657))
* **deps:** update all non-major dependencies ([#22](https://github.com/megasanjay/devmoji/issues/22)) ([e2b9050](https://github.com/megasanjay/devmoji/commit/e2b90501127b60b0073f0c16bf8b66c664f93b79))
* **deps:** update all non-major dependencies ([#24](https://github.com/megasanjay/devmoji/issues/24)) ([32bebd2](https://github.com/megasanjay/devmoji/commit/32bebd2bd6b997b8a0f86ccaa933dc12ff0aa964))
* **deps:** update all non-major dependencies ([#27](https://github.com/megasanjay/devmoji/issues/27)) ([570ef92](https://github.com/megasanjay/devmoji/commit/570ef928462d2eedf5554e1de14db1c3c81bf42e))
* **deps:** update all non-major dependencies ([#29](https://github.com/megasanjay/devmoji/issues/29)) ([02fd806](https://github.com/megasanjay/devmoji/commit/02fd8062fabe841067515582640279387651a59d))
* **deps:** update all non-major dependencies ([#30](https://github.com/megasanjay/devmoji/issues/30)) ([b5491a5](https://github.com/megasanjay/devmoji/commit/b5491a54eeb4f8e6a3773736aff8f2cb16921759))
* **deps:** update all non-major dependencies ([#33](https://github.com/megasanjay/devmoji/issues/33)) ([1ae0e03](https://github.com/megasanjay/devmoji/commit/1ae0e03fec7fffde8ed4f2c17ae397d96b0a5426))
* **deps:** update all non-major dependencies ([#34](https://github.com/megasanjay/devmoji/issues/34)) ([f3fe5ab](https://github.com/megasanjay/devmoji/commit/f3fe5ab3f9cf9f2b2c00a4eb8bcb2cdf9eae67c7))
* **deps:** update all non-major dependencies ([#37](https://github.com/megasanjay/devmoji/issues/37)) ([acc0753](https://github.com/megasanjay/devmoji/commit/acc07530c7775ec3e3a958ce09df57e2d12ddb24))
* **deps:** update all non-major dependencies ([#45](https://github.com/megasanjay/devmoji/issues/45)) ([777695a](https://github.com/megasanjay/devmoji/commit/777695ad92d76a2a9455d1895e7b5af711b5d5cf))
* **deps:** update all non-major dependencies ([#47](https://github.com/megasanjay/devmoji/issues/47)) ([1eb8c52](https://github.com/megasanjay/devmoji/commit/1eb8c52db68ea51c58d11b25195197022b12b3e1))
* **deps:** update all non-major dependencies ([#48](https://github.com/megasanjay/devmoji/issues/48)) ([42431e0](https://github.com/megasanjay/devmoji/commit/42431e0829c37ab7d4e6bb326fc83984e3bd8260))
* **deps:** update all non-major dependencies ([#70](https://github.com/megasanjay/devmoji/issues/70)) ([7b8b05a](https://github.com/megasanjay/devmoji/commit/7b8b05a37c017ad183293194794a97fd608e0380))
* **deps:** update all non-major dependencies ([#77](https://github.com/megasanjay/devmoji/issues/77)) ([fe86d3c](https://github.com/megasanjay/devmoji/commit/fe86d3c5d25c46b4ae5c0d353c6fc7b26ba3fd62))
* **deps:** update all non-major dependencies ([#80](https://github.com/megasanjay/devmoji/issues/80)) ([48596c4](https://github.com/megasanjay/devmoji/commit/48596c4c69bb5e51b8d5dc1c8ff2d96ad967d418))
* **deps:** update all non-major dependencies ([#82](https://github.com/megasanjay/devmoji/issues/82)) ([f61c156](https://github.com/megasanjay/devmoji/commit/f61c15634256b8fc0613468ca3164a77af007294))
* **deps:** update all non-major dependencies ([#90](https://github.com/megasanjay/devmoji/issues/90)) ([a779c80](https://github.com/megasanjay/devmoji/commit/a779c80cb7955d06e5941aaf8a0e2d99cc2b3199))
* **deps:** update all non-major dependencies to v2.24.0 ([#43](https://github.com/megasanjay/devmoji/issues/43)) ([205fbc3](https://github.com/megasanjay/devmoji/commit/205fbc334b83be45fc130c4dc6062ed99966fe33))
* **deps:** update dependency @rollup/plugin-commonjs to v16 ([#73](https://github.com/megasanjay/devmoji/issues/73)) ([d5be625](https://github.com/megasanjay/devmoji/commit/d5be6256e07e6ace240b75ad60cf7774d6a3ac63))
* **deps:** update dependency @rollup/plugin-commonjs to v17 ([#83](https://github.com/megasanjay/devmoji/issues/83)) ([c82d733](https://github.com/megasanjay/devmoji/commit/c82d733e5f1072d6fc80f149484a60d72152e814))
* **deps:** update dependency @rollup/plugin-commonjs to v19.0.1 ([86d9acc](https://github.com/megasanjay/devmoji/commit/86d9accccaa541c47587cb7f0c77f01b0c6618b2))
* **deps:** update dependency @rollup/plugin-commonjs to v19.0.2 ([a391b29](https://github.com/megasanjay/devmoji/commit/a391b299d92f915ec7da9b9d0cff3ebe8c48247c))
* **deps:** update dependency @rollup/plugin-node-resolve to v10 ([#74](https://github.com/megasanjay/devmoji/issues/74)) ([5202cc6](https://github.com/megasanjay/devmoji/commit/5202cc6c1c342965d32ac6fae4a2948fc8821ef4))
* **deps:** update dependency @rollup/plugin-node-resolve to v11 ([#84](https://github.com/megasanjay/devmoji/issues/84)) ([76f15ad](https://github.com/megasanjay/devmoji/commit/76f15ad485631e6b0ae6d57bf8324493bdb5bc47))
* **deps:** update dependency @rollup/plugin-node-resolve to v11.2.1 ([03defe1](https://github.com/megasanjay/devmoji/commit/03defe1c32a2348043cbee4470478c2fd131b3fa))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.1 ([dfde36f](https://github.com/megasanjay/devmoji/commit/dfde36f6bdd038c2675f093b883f54763b820c8f))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.2 ([49134e1](https://github.com/megasanjay/devmoji/commit/49134e129d5d182d54cff4ec7eaf1f1aa8dd4fc3))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.3 ([a016fd4](https://github.com/megasanjay/devmoji/commit/a016fd4ab5bb73265c93075c1b91a13eab048941))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.4 ([916adf8](https://github.com/megasanjay/devmoji/commit/916adf8b1c5009d86f74cd2aa24029f1fe8ccc0b))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.5 ([b5aa706](https://github.com/megasanjay/devmoji/commit/b5aa706a8d8de42aec9b878b91fc492a77171845))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.6 ([d95075e](https://github.com/megasanjay/devmoji/commit/d95075e0200435201d818d3bab42216c07a99bba))
* **deps:** update dependency @rollup/plugin-typescript to v3 ([#18](https://github.com/megasanjay/devmoji/issues/18)) ([c9a7a16](https://github.com/megasanjay/devmoji/commit/c9a7a1638e69bf809bf4f20683587bdcc2a25e0d))
* **deps:** update dependency @rollup/plugin-typescript to v8 ([#85](https://github.com/megasanjay/devmoji/issues/85)) ([5a10ee9](https://github.com/megasanjay/devmoji/commit/5a10ee924cc4d807a2bcccdbc2a7e390fb5e0ea4))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.1 ([3639584](https://github.com/megasanjay/devmoji/commit/36395847b7f897ad54468ed571660ff88bf09431))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.3 ([6ea0511](https://github.com/megasanjay/devmoji/commit/6ea051119c5d3f8ea13a3844bb34c5c4a9c6f7bd))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.4 ([37bbac5](https://github.com/megasanjay/devmoji/commit/37bbac5dc7299bce26e44d8519a2c787fbe74361))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.5 ([b2893e2](https://github.com/megasanjay/devmoji/commit/b2893e2adc9d709e951e8a7ef63b67d82763ed81))
* **deps:** update dependency @semantic-release/git to v9.0.1 ([2a77cd0](https://github.com/megasanjay/devmoji/commit/2a77cd00b6777c03748a0a8b95e6e08644d67953))
* **deps:** update dependency @types/jest to v25 ([#16](https://github.com/megasanjay/devmoji/issues/16)) ([555f6fe](https://github.com/megasanjay/devmoji/commit/555f6fefb6d02706426043436a39b27890daf30c))
* **deps:** update dependency @types/jest to v25.1.2 ([#28](https://github.com/megasanjay/devmoji/issues/28)) ([818cfbb](https://github.com/megasanjay/devmoji/commit/818cfbbc398e911888765c88e837b2a96ff1cc29))
* **deps:** update dependency @types/jest to v26.0.24 ([2efeb33](https://github.com/megasanjay/devmoji/commit/2efeb33fb716d911c4369d902ba369653550b65f))
* **deps:** update dependency @types/node to v13.7.0 ([#26](https://github.com/megasanjay/devmoji/issues/26)) ([7e6f547](https://github.com/megasanjay/devmoji/commit/7e6f54708c2b23afaf714caa1ecbd6262d229773))
* **deps:** update dependency @types/node to v14.14.44 ([ea2306f](https://github.com/megasanjay/devmoji/commit/ea2306f64e0042089f8212c448dbd64ba7087144))
* **deps:** update dependency @types/node to v14.14.45 ([d748c98](https://github.com/megasanjay/devmoji/commit/d748c98b1e9f12f443cdd5b0745c5d4b9f6cde82))
* **deps:** update dependency @types/node-fetch to v2.5.10 ([8015efd](https://github.com/megasanjay/devmoji/commit/8015efd8268f042499f745288cde55ec19c4e9a5))
* **deps:** update dependency @types/node-fetch to v2.5.11 ([02d4050](https://github.com/megasanjay/devmoji/commit/02d4050685d148fd9d5467bbb17308ac863824fd))
* **deps:** update dependency @types/node-fetch to v2.5.12 ([ab949cc](https://github.com/megasanjay/devmoji/commit/ab949cc53700e56382062842ddbf91c74707c26c))
* **deps:** update dependency concurrently to v6.2.1 ([c70bffb](https://github.com/megasanjay/devmoji/commit/c70bffba6d1ff16082f123cfcd077951d6942220))
* **deps:** update dependency concurrently to v6.2.2 ([ef0fbd0](https://github.com/megasanjay/devmoji/commit/ef0fbd0540cacd33f38fec521e30568ba7746536))
* **deps:** update dependency conventional-changelog-conventionalcommits to v4.6.1 ([6b9dfe2](https://github.com/megasanjay/devmoji/commit/6b9dfe237ac890fb01ccc71ea272d4907898bea8))
* **deps:** update dependency conventional-changelog-conventionalcommits to v4.6.3 ([ef024ef](https://github.com/megasanjay/devmoji/commit/ef024ef0cc63a2f5c2cd8ca7479952be47547978))
* **deps:** update dependency eslint-config-prettier to v6.10.0 ([#21](https://github.com/megasanjay/devmoji/issues/21)) ([364a982](https://github.com/megasanjay/devmoji/commit/364a98240d1ba631284b166b7c0a119047a98a66))
* **deps:** update dependency eslint-config-prettier to v7 ([#88](https://github.com/megasanjay/devmoji/issues/88)) ([0e36770](https://github.com/megasanjay/devmoji/commit/0e367707b351f55005d5a6280e8335bf2d85b749))
* **deps:** update dependency eslint-plugin-jest to v24.3.7 ([acca395](https://github.com/megasanjay/devmoji/commit/acca395ce45d1c576612c6804a912bc894e20229))
* **deps:** update dependency eslint-plugin-prettier to v3.4.1 ([b230d3f](https://github.com/megasanjay/devmoji/commit/b230d3f261b4c6d63ebab14a10e5de0127dc8218))
* **deps:** update dependency jest to v27.0.5 ([f358217](https://github.com/megasanjay/devmoji/commit/f358217ee71bc05ba02cfcc70d3f158f306192f9))
* **deps:** update dependency jest to v27.0.6 ([2bd8343](https://github.com/megasanjay/devmoji/commit/2bd8343cf2ed0a9a20822fd5f86fdec738d679e6))
* **deps:** update dependency minimist to v1.2.6 [security] ([9e7ecb7](https://github.com/megasanjay/devmoji/commit/9e7ecb71f691801cb852954042c18188268dc1e2))
* **deps:** update dependency node-fetch to v2.6.2 ([6a0bc67](https://github.com/megasanjay/devmoji/commit/6a0bc67ce0e97b81fe7bab51c610c2b369fb295c))
* **deps:** update dependency node-fetch to v2.6.3 ([899e3b5](https://github.com/megasanjay/devmoji/commit/899e3b5dbf0567112a8716b334f26d957da3207b))
* **deps:** update dependency node-fetch to v2.6.4 ([e4adb3a](https://github.com/megasanjay/devmoji/commit/e4adb3add9afeb4fcea36abf6d73fafc51f0be58))
* **deps:** update dependency node-fetch to v2.6.5 ([f6121be](https://github.com/megasanjay/devmoji/commit/f6121be035b3f7ec8bc39df9e4421d4383dc3016))
* **deps:** update dependency node-fetch to v2.6.6 ([23d00ce](https://github.com/megasanjay/devmoji/commit/23d00ce106e2889117318333a8a4a92118b66de1))
* **deps:** update dependency node-fetch to v2.6.7 [security] ([3239b8c](https://github.com/megasanjay/devmoji/commit/3239b8c30908ad8fd1474710395b728719c184fe))
* **deps:** update dependency prettier to v2 ([#46](https://github.com/megasanjay/devmoji/issues/46)) ([975c593](https://github.com/megasanjay/devmoji/commit/975c593b265449f27a097da3f7782083ee8e6029))
* **deps:** update dependency prettier to v2.3.2 ([cac6b1a](https://github.com/megasanjay/devmoji/commit/cac6b1afea42aaaddc57286bd069706202a268a6))
* **deps:** update dependency rimraf to v3.0.1 ([#20](https://github.com/megasanjay/devmoji/issues/20)) ([7e208a9](https://github.com/megasanjay/devmoji/commit/7e208a9c72ca68f2346f48542f51ebaae2316d45))
* **deps:** update dependency rollup to v1.29.1 ([#6](https://github.com/megasanjay/devmoji/issues/6)) ([49285e3](https://github.com/megasanjay/devmoji/commit/49285e324af6a219c6df888a51d3ee9d8b73b7a4))
* **deps:** update dependency rollup to v1.31.1 ([#31](https://github.com/megasanjay/devmoji/issues/31)) ([21fc914](https://github.com/megasanjay/devmoji/commit/21fc91463dc38e2e865ca3f39a3995936afb26e0))
* **deps:** update dependency rollup to v2 ([#35](https://github.com/megasanjay/devmoji/issues/35)) ([7ab9605](https://github.com/megasanjay/devmoji/commit/7ab9605f035dd66c01670cdcb7deef4ef5c46461))
* **deps:** update dependency rollup to v2.1.0 ([#44](https://github.com/megasanjay/devmoji/issues/44)) ([7928c85](https://github.com/megasanjay/devmoji/commit/7928c856c7f81320e218860d97cbf61fd2da7922))
* **deps:** update dependency rollup to v2.52.2 ([de72adb](https://github.com/megasanjay/devmoji/commit/de72adb5b267585e366543b9379eabd724552821))
* **deps:** update dependency rollup to v2.52.3 ([b757eb0](https://github.com/megasanjay/devmoji/commit/b757eb0bc7e1d17060a3949dfb08dcbdf88f8bbf))
* **deps:** update dependency rollup to v2.52.4 ([3b41411](https://github.com/megasanjay/devmoji/commit/3b414119d733f2dbed4e50362e1b9c4fc4c7f6d4))
* **deps:** update dependency rollup to v2.52.6 ([f22a6ec](https://github.com/megasanjay/devmoji/commit/f22a6ec1aba42af7f2a20149dd7e48eaa0a03f11))
* **deps:** update dependency rollup to v2.52.7 ([17b8fc1](https://github.com/megasanjay/devmoji/commit/17b8fc1bbe8718a7078b0b1610127e1e7d12138f))
* **deps:** update dependency rollup to v2.52.8 ([308b6d5](https://github.com/megasanjay/devmoji/commit/308b6d5705a4b2cead61648bc3e66158b46db58d))
* **deps:** update dependency rollup-plugin-sizes to v1.0.4 ([235dac2](https://github.com/megasanjay/devmoji/commit/235dac2f9648be491dfd41107a551ff814630104))
* **deps:** update dependency semantic-release to v17 ([#17](https://github.com/megasanjay/devmoji/issues/17)) ([7b497af](https://github.com/megasanjay/devmoji/commit/7b497affef959b7a4929e7340bafb1a3a57356ac))
* **deps:** update dependency semantic-release to v17.0.2 ([#25](https://github.com/megasanjay/devmoji/issues/25)) ([4b0b17a](https://github.com/megasanjay/devmoji/commit/4b0b17a45fd1daec5ef6b05947ed1e82a1e98118))
* **deps:** update dependency semantic-release to v17.4.5 ([e7e5455](https://github.com/megasanjay/devmoji/commit/e7e5455c027c27e3c2827356739602e792b9b08f))
* **deps:** update dependency semantic-release to v17.4.6 ([1230c19](https://github.com/megasanjay/devmoji/commit/1230c19de0bf68ff87aaaa93b65055ca32dc02c4))
* **deps:** update dependency semantic-release to v17.4.7 ([0374380](https://github.com/megasanjay/devmoji/commit/0374380add03e9d2cae5c386b2390edab550a009))
* **deps:** update dependency ts-interface-builder to v0.3.2 ([ec0fdc9](https://github.com/megasanjay/devmoji/commit/ec0fdc90dbab4cb378ff7bd762228e460bf456c0))
* **deps:** update dependency ts-interface-builder to v0.3.3 ([7c6392f](https://github.com/megasanjay/devmoji/commit/7c6392fde15d255194c944fc8202adf40846c9c1))
* **deps:** update dependency ts-jest to v25.1.0 ([#23](https://github.com/megasanjay/devmoji/issues/23)) ([8c3214b](https://github.com/megasanjay/devmoji/commit/8c3214bb1e69110d07f98520145b0c18ee81253e))
* **deps:** update dependency ts-jest to v27.0.4 ([d678ebe](https://github.com/megasanjay/devmoji/commit/d678ebe52bb4ffeb74064ca15c2a02ed9c706e3b))
* **deps:** update dependency ts-jest to v27.0.5 ([09eaea7](https://github.com/megasanjay/devmoji/commit/09eaea7e96d89001f60394e0479b3c0777c36f66))
* **deps:** update dependency ts-jest to v27.0.6 ([52461cf](https://github.com/megasanjay/devmoji/commit/52461cf5d50656e570405025e825690264e73b3f))
* **deps:** update dependency ts-jest to v27.0.7 ([eecdf4c](https://github.com/megasanjay/devmoji/commit/eecdf4c3b6accb078f6a16bc9badf82b0615d970))
* **deps:** update dependency typescript to v4.2.4 ([33b64ce](https://github.com/megasanjay/devmoji/commit/33b64ce72c8752c7886c1a50f5a0fde87920e8da))
* **deps:** update dependency typescript to v4.3.5 ([b58ee42](https://github.com/megasanjay/devmoji/commit/b58ee42e9886496a23020c4b0083eae22f22a8ad))
* **deps:** update jest ([1fe0cf2](https://github.com/megasanjay/devmoji/commit/1fe0cf246461ec8e0d43406ca932fab59c295b2f))
* **deps:** update jest ([#13](https://github.com/megasanjay/devmoji/issues/13)) ([51ac0a8](https://github.com/megasanjay/devmoji/commit/51ac0a8cc72ae29e9b9affb3c271d841f1b1f472))
* **deps:** update semantic-release monorepo ([#19](https://github.com/megasanjay/devmoji/issues/19)) ([18c2f33](https://github.com/megasanjay/devmoji/commit/18c2f33e11919ae9c0b90f88d7192b54090e75ae))
* **github:** 👷 added semantic-release ([486e1a6](https://github.com/megasanjay/devmoji/commit/486e1a6eaeeacbbc33df018af55bea4dd85b6719))
* **github:** 👷 run semantic-release only on master ([8fb91ca](https://github.com/megasanjay/devmoji/commit/8fb91cabf927cbd38ac3f7bed94d2bcf9aee89ef))
* **github:** 👷 run semantic-release only on master ([57b0611](https://github.com/megasanjay/devmoji/commit/57b061136456f05f55dd887c484be1ceac6437c7))
* **github:** 👷 run semantic-release only on master ([fa7d061](https://github.com/megasanjay/devmoji/commit/fa7d061fc5e9101ab608984424a5b720f5391035))
* **github:** 👷 use node 12.x LTS version ([22b627f](https://github.com/megasanjay/devmoji/commit/22b627f01f44e6c54c6d1093c374eaacc41ca79b))
* **maintenance:** 🔧 updated deps and fixed some linting errors ([169198f](https://github.com/megasanjay/devmoji/commit/169198f3d95375f4f83672156a3bdc5b004b6141))
* **release:** 2.1.10 [skip ci] ([67f4f44](https://github.com/megasanjay/devmoji/commit/67f4f442c7a82e73a03b2768f5bd014f08af7017)), closes [#65](https://github.com/megasanjay/devmoji/issues/65)
* **release:** 2.1.11 [skip ci] ([2f13356](https://github.com/megasanjay/devmoji/commit/2f133568a4eed843d876c7bcf753202ed074995e)), closes [#76](https://github.com/megasanjay/devmoji/issues/76) [#75](https://github.com/megasanjay/devmoji/issues/75) [#69](https://github.com/megasanjay/devmoji/issues/69) [#71](https://github.com/megasanjay/devmoji/issues/71) [#72](https://github.com/megasanjay/devmoji/issues/72) [#70](https://github.com/megasanjay/devmoji/issues/70) [#73](https://github.com/megasanjay/devmoji/issues/73) [#74](https://github.com/megasanjay/devmoji/issues/74)
* **release:** 2.1.12 [skip ci] ([21eb689](https://github.com/megasanjay/devmoji/commit/21eb689bbc26b3f596c0ea1d91c312936e2ba8ed)), closes [#81](https://github.com/megasanjay/devmoji/issues/81) [#77](https://github.com/megasanjay/devmoji/issues/77) [#80](https://github.com/megasanjay/devmoji/issues/80)
* **release:** 2.1.13 [skip ci] ([46d45d5](https://github.com/megasanjay/devmoji/commit/46d45d58231e1afe5d6d2402ccb794c464eb5627)), closes [#82](https://github.com/megasanjay/devmoji/issues/82) [#83](https://github.com/megasanjay/devmoji/issues/83) [#84](https://github.com/megasanjay/devmoji/issues/84) [#85](https://github.com/megasanjay/devmoji/issues/85) [#88](https://github.com/megasanjay/devmoji/issues/88)
* **release:** 2.1.2 [skip ci] ([69e9c2c](https://github.com/megasanjay/devmoji/commit/69e9c2cc99572c391aa382e8e478ba66cd17a8bf)), closes [#12](https://github.com/megasanjay/devmoji/issues/12) [#6](https://github.com/megasanjay/devmoji/issues/6) [#13](https://github.com/megasanjay/devmoji/issues/13)
* **release:** 2.1.3 [skip ci] ([4792f8f](https://github.com/megasanjay/devmoji/commit/4792f8f77759a9f30f955efb600b0b436a4f0bae))
* **release:** 2.1.4 [skip ci] ([97279ea](https://github.com/megasanjay/devmoji/commit/97279ea285b186a2507df699ddcbb4f542fe585c)), closes [#14](https://github.com/megasanjay/devmoji/issues/14)
* **release:** 2.1.5 [skip ci] ([032c1f6](https://github.com/megasanjay/devmoji/commit/032c1f6860c8c1979f9235fd348f82c75e211fe4)), closes [#15](https://github.com/megasanjay/devmoji/issues/15) [#22](https://github.com/megasanjay/devmoji/issues/22) [#24](https://github.com/megasanjay/devmoji/issues/24) [#27](https://github.com/megasanjay/devmoji/issues/27) [#29](https://github.com/megasanjay/devmoji/issues/29) [#30](https://github.com/megasanjay/devmoji/issues/30) [#33](https://github.com/megasanjay/devmoji/issues/33) [#18](https://github.com/megasanjay/devmoji/issues/18) [#16](https://github.com/megasanjay/devmoji/issues/16) [#28](https://github.com/megasanjay/devmoji/issues/28) [#26](https://github.com/megasanjay/devmoji/issues/26) [#21](https://github.com/megasanjay/devmoji/issues/21) [#20](https://github.com/megasanjay/devmoji/issues/20) [#31](https://github.com/megasanjay/devmoji/issues/31) [#35](https://github.com/megasanjay/devmoji/issues/35) [#17](https://github.com/megasanjay/devmoji/issues/17) [#25](https://github.com/megasanjay/devmoji/issues/25) [#23](https://github.com/megasanjay/devmoji/issues/23) [#19](https://github.com/megasanjay/devmoji/issues/19)
* **release:** 2.1.6 [skip ci] ([e0ab1c0](https://github.com/megasanjay/devmoji/commit/e0ab1c0ff3b5762e2a891ea273fdfa58c7ac4a37)), closes [#34](https://github.com/megasanjay/devmoji/issues/34) [#37](https://github.com/megasanjay/devmoji/issues/37)
* **release:** 2.1.7 [skip ci] ([e25a9f5](https://github.com/megasanjay/devmoji/commit/e25a9f585ff875887654a5c070d4b3027f127c00)), closes [#45](https://github.com/megasanjay/devmoji/issues/45) [#47](https://github.com/megasanjay/devmoji/issues/47) [#43](https://github.com/megasanjay/devmoji/issues/43) [#46](https://github.com/megasanjay/devmoji/issues/46) [#44](https://github.com/megasanjay/devmoji/issues/44)
* **release:** 2.3.0 [skip ci] ([578928f](https://github.com/megasanjay/devmoji/commit/578928f97fb9caf36118483619c43614838658dd)), closes [#126](https://github.com/megasanjay/devmoji/issues/126)
* **renovate:** 👷 group eslint and jest deps ([248a8db](https://github.com/megasanjay/devmoji/commit/248a8db9116aa7c14d9a2efb2438290ccab9a1ff))
* **renovate:** 👷 rules order ([1c1dc10](https://github.com/megasanjay/devmoji/commit/1c1dc10fd7cb9bdce6da0992b8a4bfc384aa8ddd))
* 👷 added support for [skip ci] ([7b6d374](https://github.com/megasanjay/devmoji/commit/7b6d3747a38a99ca7343318f1bec45bcdbbe368a))
* 👷 added support for [skip ci] ([5f428db](https://github.com/megasanjay/devmoji/commit/5f428db0a74cbee2503ab4400a52dd9875417d27))
* 🚨 fixed linting errors ([b357026](https://github.com/megasanjay/devmoji/commit/b35702639e415be038f72110f69243c588dcb2a6))
* **commit:** 🎨 better colors for formatting ([f7c32d4](https://github.com/megasanjay/devmoji/commit/f7c32d4b461ef22ca74141068bb70bd24cc7067e))
* **deps:** :wrench: added chalk.js ([e12d4c4](https://github.com/megasanjay/devmoji/commit/e12d4c42d89d7502a80a6d06720c7d3e2ca352fa))
* **deps:** 🔗 ➖ dependency on old lodash which has a 🔒 advisory ([55ee2c4](https://github.com/megasanjay/devmoji/commit/55ee2c4341e28e77898543c3b5d1d45e7dc71686))
* **deps:** 🔗 remove commitlint ([5d7a2b3](https://github.com/megasanjay/devmoji/commit/5d7a2b3de65a6cabbebcda77b480f252f11ce8ec))
* **deps:** 🔗 yarn upgrade --latest ([fce0b20](https://github.com/megasanjay/devmoji/commit/fce0b208122efabfb475f505c51d7f432858d6fe))
* **deps:** add renovate.json ([#1](https://github.com/megasanjay/devmoji/issues/1)) ([f0ff483](https://github.com/megasanjay/devmoji/commit/f0ff48314ad506f773cc66029c3ae69ce71115f8))
* **deps:** pin dependencies ([#2](https://github.com/megasanjay/devmoji/issues/2)) ([a9ed571](https://github.com/megasanjay/devmoji/commit/a9ed5714f163f91f3ff1f47d6d8b22d748a026b2))
* **deps:** update dependency @types/jest to v24.9.1 ([#3](https://github.com/megasanjay/devmoji/issues/3)) ([09ad222](https://github.com/megasanjay/devmoji/commit/09ad2220c1aff6d96601ad2f71854e8ae8500040))
* **deps:** update dependency @types/node to v13.5.0 ([#4](https://github.com/megasanjay/devmoji/issues/4)) ([50034b9](https://github.com/megasanjay/devmoji/commit/50034b9d6095b1128734d32078d867df2e531fdb))
* **deps:** update dependency copyfiles to v2.2.0 ([#5](https://github.com/megasanjay/devmoji/issues/5)) ([9dda192](https://github.com/megasanjay/devmoji/commit/9dda19261b13fa09cbb60797ddb50a5ff0078d1f))
* **docs:** 📦 📚 automatically copy changelog and readme to root ([08e040c](https://github.com/megasanjay/devmoji/commit/08e040c0f351765c2c392e6082ddfbfbba2f59b6))
* **emoji:** 🔨 generate ES6 modules instead of json files ([c9f5fed](https://github.com/megasanjay/devmoji/commit/c9f5fed0f6db47da650e24e15429c716e13cd757))
* **jest:** 🚨 added cli mock for jest ([035a320](https://github.com/megasanjay/devmoji/commit/035a320d08f08c3d0b00a2d7e66dd2edb8de0533))
* **release:** 🚀 1.0.0 ([5f60cc6](https://github.com/megasanjay/devmoji/commit/5f60cc64d5c63555d11cf490b1437fc29c204692))
* **release:** 🚀 1.0.1 ([36e2b56](https://github.com/megasanjay/devmoji/commit/36e2b562f5c5af34961ea4838d520a44f9134f9b))
* **release:** 🚀 1.1.0 [skip ci] ([3776e9b](https://github.com/megasanjay/devmoji/commit/3776e9bd7c06d990cfbc78703b1950cb49cfd116))
* **release:** 🚀 1.1.1 [skip ci] ([ffcdc27](https://github.com/megasanjay/devmoji/commit/ffcdc27a7bb9f0bffbc8472fd1570031a272e53b))
* **release:** 🚀 1.2.0 [skip ci] ([de836ac](https://github.com/megasanjay/devmoji/commit/de836acba96bd423ef60cb566bbd5d4be3798a6c))
* **release:** 🚀 1.2.1 [skip ci] ([c4f3632](https://github.com/megasanjay/devmoji/commit/c4f36320288bf4c8cc3c3ed3d98658c6830eddc1))
* **release:** 🚀 1.2.2 [skip ci] ([8dce6f0](https://github.com/megasanjay/devmoji/commit/8dce6f0f365f2ce9898f28b0e764b3e49cc7c152))
* **release:** 🚀 2.0.0 [skip ci] ([0632d04](https://github.com/megasanjay/devmoji/commit/0632d04b9491ff72a58ab577134fef02aaff75c0))
* **release:** 🚀 2.0.1 [skip ci] ([80d8ab0](https://github.com/megasanjay/devmoji/commit/80d8ab0d14c47203997eae5cf168a96fb12fb6cc))
* **release:** 🚀 2.0.2 [skip ci] ([b221be5](https://github.com/megasanjay/devmoji/commit/b221be57854ca1a564a02f26ab67d7fd371169d9))
* **release:** 🚀 2.1.0 [skip ci] ([f06c3a4](https://github.com/megasanjay/devmoji/commit/f06c3a40043fdf2ef7f171fc5a945a5904d9d293))
* **release:** 🚀 2.1.1 [skip ci] ([2bfe23a](https://github.com/megasanjay/devmoji/commit/2bfe23af43fe35fdfcbdb79d099cef82fe9ac1c1))
* **release:** 2.1.8 [skip ci] ([d6a47fd](https://github.com/megasanjay/devmoji/commit/d6a47fd7b82bbe15bd3fe164629076148691e591)), closes [#49](https://github.com/megasanjay/devmoji/issues/49) [#48](https://github.com/megasanjay/devmoji/issues/48)
* **release:** 2.1.9 [skip ci] ([b4195b8](https://github.com/megasanjay/devmoji/commit/b4195b8c410ed7c0f3b6e4bcc770c81c08b14328)), closes [#50](https://github.com/megasanjay/devmoji/issues/50)
* **release:** 2.2.0 [skip ci] ([6e407b6](https://github.com/megasanjay/devmoji/commit/6e407b6d4336ffce1929438c743f3a5adc108f57)), closes [#91](https://github.com/megasanjay/devmoji/issues/91) [#90](https://github.com/megasanjay/devmoji/issues/90)
* **release:** 2.2.1 [skip ci] ([32188b3](https://github.com/megasanjay/devmoji/commit/32188b32a7b817cd6730a77e22d2b2e07cd3bced)), closes [#99](https://github.com/megasanjay/devmoji/issues/99) [#94](https://github.com/megasanjay/devmoji/issues/94) [#104](https://github.com/megasanjay/devmoji/issues/104) [#93](https://github.com/megasanjay/devmoji/issues/93)
* **release:** 2.3.1 [skip ci] ([798c80b](https://github.com/megasanjay/devmoji/commit/798c80b14816af85025ddb62ed5c1a6391046199))
* **release:** 2.3.2 [skip ci] ([95e9faa](https://github.com/megasanjay/devmoji/commit/95e9faa30586f39b3b29923272017fe7505dd3b9)), closes [#157](https://github.com/megasanjay/devmoji/issues/157)
* **update:** 🔧 updated deps ([fc8b67c](https://github.com/megasanjay/devmoji/commit/fc8b67cf918fc5bc2b948821c90c65a24cf06c86))
* :wrench: added devmoji and commitlint ([cf19c03](https://github.com/megasanjay/devmoji/commit/cf19c03e0e421da2676a69deb37c47b04b052514))
* ♻️ don't use a monorepo ([288f1d5](https://github.com/megasanjay/devmoji/commit/288f1d5add6f1ecce3d6c37a454a2352144db59b))
* ⚡ configured vscode debugging support ([1e0876a](https://github.com/megasanjay/devmoji/commit/1e0876adfe7056285057d3b924f90d8cbeede0b5))
* 🎨 fixed linting errors for all src and __tests__ source files ([2a93269](https://github.com/megasanjay/devmoji/commit/2a9326954366068885105c80607f2a6f434940a8))
* 🎨 prettier 2.0 ([1cd11ed](https://github.com/megasanjay/devmoji/commit/1cd11ed4cb9cf99e4e8db3e1bc8e3d4ab3d7e977))
* 🎨 Prettier 2.0 ([3228033](https://github.com/megasanjay/devmoji/commit/32280336699adb9af9bc29641b093cb1faf4fec1))
* 👷 added standard-version ([451f698](https://github.com/megasanjay/devmoji/commit/451f6982e0da945fcfe255039d425356c762f76e))
* 📦 added build tasks ([f6e10d6](https://github.com/megasanjay/devmoji/commit/f6e10d68602c2edeaf2ccee11d2a465b4d9dc970))
* 📦 added rollup build scripts ([f8754a5](https://github.com/megasanjay/devmoji/commit/f8754a59ff3fee2c0f3c1e5aaa006d4c1f32b0dd))
* 📦 don't push created lib to git during release ([d3d9fad](https://github.com/megasanjay/devmoji/commit/d3d9fad38c29a617ef9ccfb3730025b738d409d0))
* 📦 push changes in root CHANGELOG.md to git on release ([cffee3c](https://github.com/megasanjay/devmoji/commit/cffee3c58d59d13356cb9c5b88aba6c83fff349f))
* 📦️ stuff ([6bc02d8](https://github.com/megasanjay/devmoji/commit/6bc02d82627036124faf5d0806fa95eb82167b6c))
* 📦 tsconfig ([853d4ad](https://github.com/megasanjay/devmoji/commit/853d4ad8e69d47fa62cc54f397245c979ce0c237))
* 📦️ updates for Husky 5 ([bbc5f60](https://github.com/megasanjay/devmoji/commit/bbc5f60320c650c6a733ea138851efe8408b529e))
* 📦️ use husky instead of yorkie for git hooks ([4e280ec](https://github.com/megasanjay/devmoji/commit/4e280ecb70ab2a8ade7890a6b105f2a405e1252c))
* 🔧 changelog bump ([6fc1a8c](https://github.com/megasanjay/devmoji/commit/6fc1a8c8b2de7c700d92fa93a4778ef927233f12))
* 🔧 updated release.config.js ([7e365ce](https://github.com/megasanjay/devmoji/commit/7e365ce57e61dae7c58f59d5b73bc6b59cc2303c))
* 🔨 moved emoji json files under src ([eb92152](https://github.com/megasanjay/devmoji/commit/eb9215215dd92000f313515c97a85243c63011fd))
* 🔨 moved scripts to src/scripts ([59a0c3e](https://github.com/megasanjay/devmoji/commit/59a0c3e350719066d8f5ed8f6584da3105b939b3))
* added Github Actions ([3cc16dd](https://github.com/megasanjay/devmoji/commit/3cc16dd5f2e11f88b2295c3ed660b957289efe99))
* **release:** 🚀 2.0.3 [skip ci] ([e7a674e](https://github.com/megasanjay/devmoji/commit/e7a674e4631d1fe9ae635098c6b7759d235fe54f))
* 🔨 use esnext module import syntax ([87ea673](https://github.com/megasanjay/devmoji/commit/87ea67366e74fc6d8d45e1ac407ad97675033fd0))
* 🚨 implemented a bunch of test scripts ([ac0e078](https://github.com/megasanjay/devmoji/commit/ac0e0789e972bfec066cffbf53c2ca90183adc2b))
* 🚨 never use color when running inside jest ([3a892f9](https://github.com/megasanjay/devmoji/commit/3a892f963b5625d76fde1173d02bb2a3ed761515))

### [2.3.2](https://github.com/folke/devmoji/compare/v2.3.1...v2.3.2) (2021-10-22)


### Bug Fixes

* **docs:** :memo: fixed name devmoji ([#157](https://github.com/folke/devmoji/issues/157)) ([86b7d55](https://github.com/folke/devmoji/commit/86b7d55bd13a1b958d80b9df229f9b74d25e8da7))


### Other

* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.6 ([d95075e](https://github.com/folke/devmoji/commit/d95075e0200435201d818d3bab42216c07a99bba))
* **deps:** update dependency ts-jest to v27.0.6 ([52461cf](https://github.com/folke/devmoji/commit/52461cf5d50656e570405025e825690264e73b3f))
* **deps:** update dependency ts-jest to v27.0.7 ([eecdf4c](https://github.com/folke/devmoji/commit/eecdf4c3b6accb078f6a16bc9badf82b0615d970))

### [2.3.1](https://github.com/folke/devmoji/compare/v2.3.0...v2.3.1) (2021-10-12)


### Bug Fixes

* **deps:** update dependency ts-interface-checker to v1.0.2 ([29300b6](https://github.com/folke/devmoji/commit/29300b66ab4c2bb36d9decf84f7dd2bb49d692f2))


### Other

* **deps:** update dependency @rollup/plugin-commonjs to v19.0.1 ([86d9acc](https://github.com/folke/devmoji/commit/86d9accccaa541c47587cb7f0c77f01b0c6618b2))
* **deps:** update dependency @rollup/plugin-commonjs to v19.0.2 ([a391b29](https://github.com/folke/devmoji/commit/a391b299d92f915ec7da9b9d0cff3ebe8c48247c))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.1 ([dfde36f](https://github.com/folke/devmoji/commit/dfde36f6bdd038c2675f093b883f54763b820c8f))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.2 ([49134e1](https://github.com/folke/devmoji/commit/49134e129d5d182d54cff4ec7eaf1f1aa8dd4fc3))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.3 ([a016fd4](https://github.com/folke/devmoji/commit/a016fd4ab5bb73265c93075c1b91a13eab048941))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.4 ([916adf8](https://github.com/folke/devmoji/commit/916adf8b1c5009d86f74cd2aa24029f1fe8ccc0b))
* **deps:** update dependency @rollup/plugin-node-resolve to v13.0.5 ([b5aa706](https://github.com/folke/devmoji/commit/b5aa706a8d8de42aec9b878b91fc492a77171845))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.3 ([6ea0511](https://github.com/folke/devmoji/commit/6ea051119c5d3f8ea13a3844bb34c5c4a9c6f7bd))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.4 ([37bbac5](https://github.com/folke/devmoji/commit/37bbac5dc7299bce26e44d8519a2c787fbe74361))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.5 ([b2893e2](https://github.com/folke/devmoji/commit/b2893e2adc9d709e951e8a7ef63b67d82763ed81))
* **deps:** update dependency @semantic-release/git to v9.0.1 ([2a77cd0](https://github.com/folke/devmoji/commit/2a77cd00b6777c03748a0a8b95e6e08644d67953))
* **deps:** update dependency @types/jest to v26.0.24 ([2efeb33](https://github.com/folke/devmoji/commit/2efeb33fb716d911c4369d902ba369653550b65f))
* **deps:** update dependency @types/node-fetch to v2.5.11 ([02d4050](https://github.com/folke/devmoji/commit/02d4050685d148fd9d5467bbb17308ac863824fd))
* **deps:** update dependency @types/node-fetch to v2.5.12 ([ab949cc](https://github.com/folke/devmoji/commit/ab949cc53700e56382062842ddbf91c74707c26c))
* **deps:** update dependency concurrently to v6.2.1 ([c70bffb](https://github.com/folke/devmoji/commit/c70bffba6d1ff16082f123cfcd077951d6942220))
* **deps:** update dependency concurrently to v6.2.2 ([ef0fbd0](https://github.com/folke/devmoji/commit/ef0fbd0540cacd33f38fec521e30568ba7746536))
* **deps:** update dependency conventional-changelog-conventionalcommits to v4.6.1 ([6b9dfe2](https://github.com/folke/devmoji/commit/6b9dfe237ac890fb01ccc71ea272d4907898bea8))
* **deps:** update dependency eslint-plugin-jest to v24.3.7 ([acca395](https://github.com/folke/devmoji/commit/acca395ce45d1c576612c6804a912bc894e20229))
* **deps:** update dependency eslint-plugin-prettier to v3.4.1 ([b230d3f](https://github.com/folke/devmoji/commit/b230d3f261b4c6d63ebab14a10e5de0127dc8218))
* **deps:** update dependency jest to v27.0.5 ([f358217](https://github.com/folke/devmoji/commit/f358217ee71bc05ba02cfcc70d3f158f306192f9))
* **deps:** update dependency jest to v27.0.6 ([2bd8343](https://github.com/folke/devmoji/commit/2bd8343cf2ed0a9a20822fd5f86fdec738d679e6))
* **deps:** update dependency node-fetch to v2.6.2 ([6a0bc67](https://github.com/folke/devmoji/commit/6a0bc67ce0e97b81fe7bab51c610c2b369fb295c))
* **deps:** update dependency node-fetch to v2.6.3 ([899e3b5](https://github.com/folke/devmoji/commit/899e3b5dbf0567112a8716b334f26d957da3207b))
* **deps:** update dependency node-fetch to v2.6.4 ([e4adb3a](https://github.com/folke/devmoji/commit/e4adb3add9afeb4fcea36abf6d73fafc51f0be58))
* **deps:** update dependency node-fetch to v2.6.5 ([f6121be](https://github.com/folke/devmoji/commit/f6121be035b3f7ec8bc39df9e4421d4383dc3016))
* **deps:** update dependency prettier to v2.3.2 ([cac6b1a](https://github.com/folke/devmoji/commit/cac6b1afea42aaaddc57286bd069706202a268a6))
* **deps:** update dependency rollup to v2.52.2 ([de72adb](https://github.com/folke/devmoji/commit/de72adb5b267585e366543b9379eabd724552821))
* **deps:** update dependency rollup to v2.52.3 ([b757eb0](https://github.com/folke/devmoji/commit/b757eb0bc7e1d17060a3949dfb08dcbdf88f8bbf))
* **deps:** update dependency rollup to v2.52.4 ([3b41411](https://github.com/folke/devmoji/commit/3b414119d733f2dbed4e50362e1b9c4fc4c7f6d4))
* **deps:** update dependency rollup to v2.52.6 ([f22a6ec](https://github.com/folke/devmoji/commit/f22a6ec1aba42af7f2a20149dd7e48eaa0a03f11))
* **deps:** update dependency rollup to v2.52.7 ([17b8fc1](https://github.com/folke/devmoji/commit/17b8fc1bbe8718a7078b0b1610127e1e7d12138f))
* **deps:** update dependency rollup to v2.52.8 ([308b6d5](https://github.com/folke/devmoji/commit/308b6d5705a4b2cead61648bc3e66158b46db58d))
* **deps:** update dependency semantic-release to v17.4.5 ([e7e5455](https://github.com/folke/devmoji/commit/e7e5455c027c27e3c2827356739602e792b9b08f))
* **deps:** update dependency semantic-release to v17.4.6 ([1230c19](https://github.com/folke/devmoji/commit/1230c19de0bf68ff87aaaa93b65055ca32dc02c4))
* **deps:** update dependency semantic-release to v17.4.7 ([0374380](https://github.com/folke/devmoji/commit/0374380add03e9d2cae5c386b2390edab550a009))
* **deps:** update dependency ts-interface-builder to v0.3.2 ([ec0fdc9](https://github.com/folke/devmoji/commit/ec0fdc90dbab4cb378ff7bd762228e460bf456c0))
* **deps:** update dependency ts-jest to v27.0.4 ([d678ebe](https://github.com/folke/devmoji/commit/d678ebe52bb4ffeb74064ca15c2a02ed9c706e3b))
* **deps:** update dependency ts-jest to v27.0.5 ([09eaea7](https://github.com/folke/devmoji/commit/09eaea7e96d89001f60394e0479b3c0777c36f66))
* **deps:** update dependency typescript to v4.3.5 ([b58ee42](https://github.com/folke/devmoji/commit/b58ee42e9886496a23020c4b0083eae22f22a8ad))

## [2.3.0](https://github.com/folke/devmoji/compare/v2.2.1...v2.3.0) (2021-06-18)


### Features

* ✨ scope to allow digit ([#126](https://github.com/folke/devmoji/issues/126)) ([cb31dda](https://github.com/folke/devmoji/commit/cb31ddae5899442e368f7fe8223a289371f8495a))


### Bug Fixes

* **test:** 🐛 🚨 fixup for syntax error ([404dce4](https://github.com/folke/devmoji/commit/404dce4dfb6ffe3dbb7846e649772cbd84176ec2))


### Other

* 🚨 fixed linting errors ([b357026](https://github.com/folke/devmoji/commit/b35702639e415be038f72110f69243c588dcb2a6))
* **deps:** update dependency @types/node to v14.14.45 ([d748c98](https://github.com/folke/devmoji/commit/d748c98b1e9f12f443cdd5b0745c5d4b9f6cde82))
* **update:** 🔧 updated deps ([fc8b67c](https://github.com/folke/devmoji/commit/fc8b67cf918fc5bc2b948821c90c65a24cf06c86))

### [2.2.1](https://github.com/folke/devmoji/compare/v2.2.0...v2.2.1) (2021-05-10)


### Bug Fixes

* **deps:** update dependency ts-interface-checker to v0.2.1 ([2262197](https://github.com/folke/devmoji/commit/2262197a33d261930a5b51fba8d73b4bad4e35fc))


### Other

* **deps:** bump marked from 1.2.0 to 2.0.0 ([#99](https://github.com/folke/devmoji/issues/99)) ([f6c382b](https://github.com/folke/devmoji/commit/f6c382bc59d914bb87d9c2ce63493d2647cbe335))
* **deps:** bump node-notifier from 8.0.0 to 8.0.1 ([#94](https://github.com/folke/devmoji/issues/94)) ([cf87590](https://github.com/folke/devmoji/commit/cf875905f4f4af7b6329e7ed94caa656c184dce8))
* **deps:** bump ssri from 6.0.1 to 6.0.2 ([#104](https://github.com/folke/devmoji/issues/104)) ([27d1d3f](https://github.com/folke/devmoji/commit/27d1d3f8a8c2a9aa729c676820858479138c16b5))
* **deps:** update actions/setup-node action to v2 ([#93](https://github.com/folke/devmoji/issues/93)) ([7cf6c17](https://github.com/folke/devmoji/commit/7cf6c1732628eba9ca3698800532075b337f8222))
* **deps:** update dependency @rollup/plugin-node-resolve to v11.2.1 ([03defe1](https://github.com/folke/devmoji/commit/03defe1c32a2348043cbee4470478c2fd131b3fa))
* **deps:** update dependency @rollup/plugin-typescript to v8.2.1 ([3639584](https://github.com/folke/devmoji/commit/36395847b7f897ad54468ed571660ff88bf09431))
* **deps:** update dependency @types/node to v14.14.44 ([ea2306f](https://github.com/folke/devmoji/commit/ea2306f64e0042089f8212c448dbd64ba7087144))
* **deps:** update dependency @types/node-fetch to v2.5.10 ([8015efd](https://github.com/folke/devmoji/commit/8015efd8268f042499f745288cde55ec19c4e9a5))
* **deps:** update dependency rollup-plugin-sizes to v1.0.4 ([235dac2](https://github.com/folke/devmoji/commit/235dac2f9648be491dfd41107a551ff814630104))
* **deps:** update dependency typescript to v4.2.4 ([33b64ce](https://github.com/folke/devmoji/commit/33b64ce72c8752c7886c1a50f5a0fde87920e8da))
* **deps:** update jest ([1fe0cf2](https://github.com/folke/devmoji/commit/1fe0cf246461ec8e0d43406ca932fab59c295b2f))

## [2.2.0](https://github.com/folke/devmoji/compare/v2.1.13...v2.2.0) (2021-02-24)


### Features

* ✨ added support for fixup! & match! comments ([155dee2](https://github.com/folke/devmoji/commit/155dee208a4651234283884f570075aaf3eaa90e))


### Bug Fixes

* 🐛 get --config value from Commander.opts() ([a461c2b](https://github.com/folke/devmoji/commit/a461c2bb78340e3d58de3fcedbae3b84afa6b39c))


### Other

* **deps:** 🔗 update ([979279e](https://github.com/folke/devmoji/commit/979279ebf8bc052c397ff009d1e84e54d4d339f6))
* 📦️ updates for Husky 5 ([bbc5f60](https://github.com/folke/devmoji/commit/bbc5f60320c650c6a733ea138851efe8408b529e))
* **deps:** bump ini from 1.3.5 to 1.3.8 ([#91](https://github.com/folke/devmoji/issues/91)) ([79cb9cf](https://github.com/folke/devmoji/commit/79cb9cf84fde05f7bb6fe124aa9d02c5f5f24acd))
* **deps:** update all non-major dependencies ([#90](https://github.com/folke/devmoji/issues/90)) ([a779c80](https://github.com/folke/devmoji/commit/a779c80cb7955d06e5941aaf8a0e2d99cc2b3199))

### [2.1.13](https://github.com/folke/devmoji/compare/v2.1.12...v2.1.13) (2020-12-09)


### Other

* **deps:** update all non-major dependencies ([#82](https://github.com/folke/devmoji/issues/82)) ([f61c156](https://github.com/folke/devmoji/commit/f61c15634256b8fc0613468ca3164a77af007294))
* **deps:** update dependency @rollup/plugin-commonjs to v17 ([#83](https://github.com/folke/devmoji/issues/83)) ([c82d733](https://github.com/folke/devmoji/commit/c82d733e5f1072d6fc80f149484a60d72152e814))
* **deps:** update dependency @rollup/plugin-node-resolve to v11 ([#84](https://github.com/folke/devmoji/issues/84)) ([76f15ad](https://github.com/folke/devmoji/commit/76f15ad485631e6b0ae6d57bf8324493bdb5bc47))
* **deps:** update dependency @rollup/plugin-typescript to v8 ([#85](https://github.com/folke/devmoji/issues/85)) ([5a10ee9](https://github.com/folke/devmoji/commit/5a10ee924cc4d807a2bcccdbc2a7e390fb5e0ea4))
* **deps:** update dependency eslint-config-prettier to v7 ([#88](https://github.com/folke/devmoji/issues/88)) ([0e36770](https://github.com/folke/devmoji/commit/0e367707b351f55005d5a6280e8335bf2d85b749))


### Documentation

* 📚️ better docs about git commit hooks ([8f7b36a](https://github.com/folke/devmoji/commit/8f7b36ab0ec7e0623f0e0a597d166749d250912e))

### [2.1.12](https://github.com/folke/devmoji/compare/v2.1.11...v2.1.12) (2020-11-30)


### Bug Fixes

* 🐛 use the color option for --log (fixes [#81](https://github.com/folke/devmoji/issues/81)) ([c7370de](https://github.com/folke/devmoji/commit/c7370de7e260156e8c2f97870e6564201658c49c))


### Other

* 🎨 fixed linting errors for all src and __tests__ source files ([2a93269](https://github.com/folke/devmoji/commit/2a9326954366068885105c80607f2a6f434940a8))
* **deps:** update all non-major dependencies ([#77](https://github.com/folke/devmoji/issues/77)) ([fe86d3c](https://github.com/folke/devmoji/commit/fe86d3c5d25c46b4ae5c0d353c6fc7b26ba3fd62))
* **deps:** update all non-major dependencies ([#80](https://github.com/folke/devmoji/issues/80)) ([48596c4](https://github.com/folke/devmoji/commit/48596c4c69bb5e51b8d5dc1c8ff2d96ad967d418))

### [2.1.11](https://github.com/folke/devmoji/compare/v2.1.10...v2.1.11) (2020-11-12)


### Bug Fixes

* **lint:** 🐛 detect BREAKING CHANGE in description. Fixes [#76](https://github.com/folke/devmoji/issues/76) ([a3d5ab0](https://github.com/folke/devmoji/commit/a3d5ab0cafd3366538ca0098669b83712d36a13d))
* **lint:** 🐛 scope and type can by any case. Fixes [#75](https://github.com/folke/devmoji/issues/75) ([8138c84](https://github.com/folke/devmoji/commit/8138c840cb35c8d3513e5ea3eed339337696dc75))


### Other

* **deps:** bump npm-user-validate from 1.0.0 to 1.0.1 ([#69](https://github.com/folke/devmoji/issues/69)) ([19ea27c](https://github.com/folke/devmoji/commit/19ea27c6f03ad6e12305310df45d7ec144191457))
* **deps:** update actions/cache action to v2 ([#71](https://github.com/folke/devmoji/issues/71)) ([a91dbc4](https://github.com/folke/devmoji/commit/a91dbc4523cea6625085452755cc1a4a7df94b03))
* **deps:** update actions/checkout action to v2 ([#72](https://github.com/folke/devmoji/issues/72)) ([717ad15](https://github.com/folke/devmoji/commit/717ad15695555e5876f8acdd8bded57af09cf1dd))
* **deps:** update all non-major dependencies ([#70](https://github.com/folke/devmoji/issues/70)) ([7b8b05a](https://github.com/folke/devmoji/commit/7b8b05a37c017ad183293194794a97fd608e0380))
* **deps:** update dependency @rollup/plugin-commonjs to v16 ([#73](https://github.com/folke/devmoji/issues/73)) ([d5be625](https://github.com/folke/devmoji/commit/d5be6256e07e6ace240b75ad60cf7774d6a3ac63))
* **deps:** update dependency @rollup/plugin-node-resolve to v10 ([#74](https://github.com/folke/devmoji/issues/74)) ([5202cc6](https://github.com/folke/devmoji/commit/5202cc6c1c342965d32ac6fae4a2948fc8821ef4))
* **maintenance:** 🔧 updated deps and fixed some linting errors ([169198f](https://github.com/folke/devmoji/commit/169198f3d95375f4f83672156a3bdc5b004b6141))

### [2.1.10](https://github.com/folke/devmoji/compare/v2.1.9...v2.1.10) (2020-10-01)


### Documentation

* replace yarn install w/ yarn add ([#65](https://github.com/folke/devmoji/issues/65)) ([f9acf3e](https://github.com/folke/devmoji/commit/f9acf3eef951d638fb0d9538aa9a702122071712))

### [2.1.9](https://github.com/folke/devmoji/compare/v2.1.8...v2.1.9) (2020-04-09)


### Bug Fixes

* 🐛 --lint shouldn't fail on merge commit message (fixes [#50](https://github.com/folke/devmoji/issues/50)) ([8ba3987](https://github.com/folke/devmoji/commit/8ba3987e180ffd6902162a14ef2f831192e61b62))


### Other

* 🎨 prettier 2.0 ([1cd11ed](https://github.com/folke/devmoji/commit/1cd11ed4cb9cf99e4e8db3e1bc8e3d4ab3d7e977))
* 🎨 Prettier 2.0 ([3228033](https://github.com/folke/devmoji/commit/32280336699adb9af9bc29641b093cb1faf4fec1))

### [2.1.8](https://github.com/folke/devmoji/compare/v2.1.7...v2.1.8) (2020-04-09)


### Bug Fixes

* **deps:** update dependency chalk to v4 ([#49](https://github.com/folke/devmoji/issues/49)) ([aefa669](https://github.com/folke/devmoji/commit/aefa6691a23e43b34d78bd98aa694b07bebe3dee))


### Other

* **deps:** update all non-major dependencies ([#48](https://github.com/folke/devmoji/issues/48)) ([42431e0](https://github.com/folke/devmoji/commit/42431e0829c37ab7d4e6bb326fc83984e3bd8260))

### [2.1.7](https://github.com/folke/devmoji/compare/v2.1.6...v2.1.7) (2020-03-24)


### Bug Fixes

* 🐛 🔒️ upgrade minimist which had a security vulnerability ([fc12464](https://github.com/folke/devmoji/commit/fc124643a64967896bab3a5f2edf04e685a9f0c1))


### Other

* **deps:** update all non-major dependencies ([#45](https://github.com/folke/devmoji/issues/45)) ([777695a](https://github.com/folke/devmoji/commit/777695ad92d76a2a9455d1895e7b5af711b5d5cf))
* **deps:** update all non-major dependencies ([#47](https://github.com/folke/devmoji/issues/47)) ([1eb8c52](https://github.com/folke/devmoji/commit/1eb8c52db68ea51c58d11b25195197022b12b3e1))
* **deps:** update all non-major dependencies to v2.24.0 ([#43](https://github.com/folke/devmoji/issues/43)) ([205fbc3](https://github.com/folke/devmoji/commit/205fbc334b83be45fc130c4dc6062ed99966fe33))
* **deps:** update dependency prettier to v2 ([#46](https://github.com/folke/devmoji/issues/46)) ([975c593](https://github.com/folke/devmoji/commit/975c593b265449f27a097da3f7782083ee8e6029))
* **deps:** update dependency rollup to v2.1.0 ([#44](https://github.com/folke/devmoji/issues/44)) ([7928c85](https://github.com/folke/devmoji/commit/7928c856c7f81320e218860d97cbf61fd2da7922))

### [2.1.6](https://github.com/folke/devmoji/compare/v2.1.5...v2.1.6) (2020-03-15)


### Bug Fixes

* 🐛 new rollup version and commanderjs ([41ae638](https://github.com/folke/devmoji/commit/41ae638a22c7aae04dc699711b6c56693547169d))


### Other

* **deps:** update all non-major dependencies ([#34](https://github.com/folke/devmoji/issues/34)) ([f3fe5ab](https://github.com/folke/devmoji/commit/f3fe5ab3f9cf9f2b2c00a4eb8bcb2cdf9eae67c7))
* **deps:** update all non-major dependencies ([#37](https://github.com/folke/devmoji/issues/37)) ([acc0753](https://github.com/folke/devmoji/commit/acc07530c7775ec3e3a958ce09df57e2d12ddb24))

### [2.1.5](https://github.com/folke/devmoji/compare/v2.1.4...v2.1.5) (2020-03-10)


### Other

* **deps:** update all non-major dependencies ([#15](https://github.com/folke/devmoji/issues/15)) ([3df8504](https://github.com/folke/devmoji/commit/3df85041b1e9bbe5faf06572cb9f5c5043b48657))
* **deps:** update all non-major dependencies ([#22](https://github.com/folke/devmoji/issues/22)) ([e2b9050](https://github.com/folke/devmoji/commit/e2b90501127b60b0073f0c16bf8b66c664f93b79))
* **deps:** update all non-major dependencies ([#24](https://github.com/folke/devmoji/issues/24)) ([32bebd2](https://github.com/folke/devmoji/commit/32bebd2bd6b997b8a0f86ccaa933dc12ff0aa964))
* **deps:** update all non-major dependencies ([#27](https://github.com/folke/devmoji/issues/27)) ([570ef92](https://github.com/folke/devmoji/commit/570ef928462d2eedf5554e1de14db1c3c81bf42e))
* **deps:** update all non-major dependencies ([#29](https://github.com/folke/devmoji/issues/29)) ([02fd806](https://github.com/folke/devmoji/commit/02fd8062fabe841067515582640279387651a59d))
* **deps:** update all non-major dependencies ([#30](https://github.com/folke/devmoji/issues/30)) ([b5491a5](https://github.com/folke/devmoji/commit/b5491a54eeb4f8e6a3773736aff8f2cb16921759))
* **deps:** update all non-major dependencies ([#33](https://github.com/folke/devmoji/issues/33)) ([1ae0e03](https://github.com/folke/devmoji/commit/1ae0e03fec7fffde8ed4f2c17ae397d96b0a5426))
* **deps:** update dependency @rollup/plugin-typescript to v3 ([#18](https://github.com/folke/devmoji/issues/18)) ([c9a7a16](https://github.com/folke/devmoji/commit/c9a7a1638e69bf809bf4f20683587bdcc2a25e0d))
* **deps:** update dependency @types/jest to v25 ([#16](https://github.com/folke/devmoji/issues/16)) ([555f6fe](https://github.com/folke/devmoji/commit/555f6fefb6d02706426043436a39b27890daf30c))
* **deps:** update dependency @types/jest to v25.1.2 ([#28](https://github.com/folke/devmoji/issues/28)) ([818cfbb](https://github.com/folke/devmoji/commit/818cfbbc398e911888765c88e837b2a96ff1cc29))
* **deps:** update dependency @types/node to v13.7.0 ([#26](https://github.com/folke/devmoji/issues/26)) ([7e6f547](https://github.com/folke/devmoji/commit/7e6f54708c2b23afaf714caa1ecbd6262d229773))
* **deps:** update dependency eslint-config-prettier to v6.10.0 ([#21](https://github.com/folke/devmoji/issues/21)) ([364a982](https://github.com/folke/devmoji/commit/364a98240d1ba631284b166b7c0a119047a98a66))
* **deps:** update dependency rimraf to v3.0.1 ([#20](https://github.com/folke/devmoji/issues/20)) ([7e208a9](https://github.com/folke/devmoji/commit/7e208a9c72ca68f2346f48542f51ebaae2316d45))
* **deps:** update dependency rollup to v1.31.1 ([#31](https://github.com/folke/devmoji/issues/31)) ([21fc914](https://github.com/folke/devmoji/commit/21fc91463dc38e2e865ca3f39a3995936afb26e0))
* **deps:** update dependency rollup to v2 ([#35](https://github.com/folke/devmoji/issues/35)) ([7ab9605](https://github.com/folke/devmoji/commit/7ab9605f035dd66c01670cdcb7deef4ef5c46461))
* **deps:** update dependency semantic-release to v17 ([#17](https://github.com/folke/devmoji/issues/17)) ([7b497af](https://github.com/folke/devmoji/commit/7b497affef959b7a4929e7340bafb1a3a57356ac))
* **deps:** update dependency semantic-release to v17.0.2 ([#25](https://github.com/folke/devmoji/issues/25)) ([4b0b17a](https://github.com/folke/devmoji/commit/4b0b17a45fd1daec5ef6b05947ed1e82a1e98118))
* **deps:** update dependency ts-jest to v25.1.0 ([#23](https://github.com/folke/devmoji/issues/23)) ([8c3214b](https://github.com/folke/devmoji/commit/8c3214bb1e69110d07f98520145b0c18ee81253e))
* **deps:** update semantic-release monorepo ([#19](https://github.com/folke/devmoji/issues/19)) ([18c2f33](https://github.com/folke/devmoji/commit/18c2f33e11919ae9c0b90f88d7192b54090e75ae))


### Documentation

* fixed config example ([9860364](https://github.com/folke/devmoji/commit/9860364b8ed2311685a1a024f8998390b0717280))

### [2.1.4](https://github.com/folke/devmoji/compare/v2.1.3...v2.1.4) (2020-01-27)


### Bug Fixes

* 🐛 fixed endless loop on win32 ([a3026e1](https://github.com/folke/devmoji/commit/a3026e1a7742fa5ff3ccaa11fbf51cdd6f310810))


### Other

* **deps:** update all non-major dependencies ([#14](https://github.com/folke/devmoji/issues/14)) ([e2e724b](https://github.com/folke/devmoji/commit/e2e724b4a5b9a3fc30ef4dcb2288c754b8c0409c))

### [2.1.3](https://github.com/folke/devmoji/compare/v2.1.2...v2.1.3) (2020-01-25)


### Other

* **github:** 👷 run semantic-release only on master ([8fb91ca](https://github.com/folke/devmoji/commit/8fb91cabf927cbd38ac3f7bed94d2bcf9aee89ef))
* **github:** 👷 run semantic-release only on master ([57b0611](https://github.com/folke/devmoji/commit/57b061136456f05f55dd887c484be1ceac6437c7))
* **github:** 👷 run semantic-release only on master ([fa7d061](https://github.com/folke/devmoji/commit/fa7d061fc5e9101ab608984424a5b720f5391035))


### Documentation

* 📚️ testing gihub releases ([3c74ce8](https://github.com/folke/devmoji/commit/3c74ce8876f89618d71d3a4d90b49c1827a426da))

### [2.1.2](https://github.com/folke/devmoji/compare/v2.1.1...v2.1.2) (2020-01-25)


### Documentation

* 📚️ added badges ([4b4b22e](https://github.com/folke/devmoji/commit/4b4b22e96e9311a27990fd6ed59db1cf79182c94))
* added license [skip ci] ([d58175e](https://github.com/folke/devmoji/commit/d58175ed16715d92ef1f05d7e532d904639fb77a))
* added renovate badge ([5e5cda9](https://github.com/folke/devmoji/commit/5e5cda940b5ddd2c8e433b641370e9694e42823e))


### Other

* **deps:** 👷 automerge minor, patch, pin and digest ([578258b](https://github.com/folke/devmoji/commit/578258bdc6151c36b62eee31529fe82dc898e1c8))
* **deps:** 👷 group all non-major updates ([abe0982](https://github.com/folke/devmoji/commit/abe0982a44705c145a6803f465399a8f21ac92ed))
* **deps:** update all non-major dependencies ([#12](https://github.com/folke/devmoji/issues/12)) ([2f7236f](https://github.com/folke/devmoji/commit/2f7236ff70936fdf20d7b721c8f168f41692d757))
* **deps:** update dependency rollup to v1.29.1 ([#6](https://github.com/folke/devmoji/issues/6)) ([49285e3](https://github.com/folke/devmoji/commit/49285e324af6a219c6df888a51d3ee9d8b73b7a4))
* **deps:** update jest ([#13](https://github.com/folke/devmoji/issues/13)) ([51ac0a8](https://github.com/folke/devmoji/commit/51ac0a8cc72ae29e9b9affb3c271d841f1b1f472))
* **github:** 👷 added semantic-release ([486e1a6](https://github.com/folke/devmoji/commit/486e1a6eaeeacbbc33df018af55bea4dd85b6719))
* **github:** 👷 use node 12.x LTS version ([22b627f](https://github.com/folke/devmoji/commit/22b627f01f44e6c54c6d1093c374eaacc41ca79b))
* **renovate:** 👷 group eslint and jest deps ([248a8db](https://github.com/folke/devmoji/commit/248a8db9116aa7c14d9a2efb2438290ccab9a1ff))
* **renovate:** 👷 rules order ([1c1dc10](https://github.com/folke/devmoji/commit/1c1dc10fd7cb9bdce6da0992b8a4bfc384aa8ddd))
* 👷 added support for [skip ci] ([7b6d374](https://github.com/folke/devmoji/commit/7b6d3747a38a99ca7343318f1bec45bcdbbe368a))
* 👷 added support for [skip ci] ([5f428db](https://github.com/folke/devmoji/commit/5f428db0a74cbee2503ab4400a52dd9875417d27))
* 🔧 updated release.config.js ([7e365ce](https://github.com/folke/devmoji/commit/7e365ce57e61dae7c58f59d5b73bc6b59cc2303c))

## [2.1.1](https://github.com/folke/devmoji/compare/v2.1.0...v2.1.1) (2020-01-25)


### Bug Fixes

* 🐛 fixed callstack error for Windows ([9f411d2](https://github.com/folke/devmoji/commit/9f411d28c8d71dca331c96e8b8436e5368d809fa))

# [2.1.0](https://github.com/folke/devmoji/compare/v2.0.3...v2.1.0) (2020-01-25)


### Features

* ✨ added commit linting! ([2d52f2c](https://github.com/folke/devmoji/commit/2d52f2c8fe1e8c49000293e1cb9b3b13f47277d0))

## [2.0.3](https://github.com/folke/devmoji/compare/v2.0.2...v2.0.3) (2020-01-22)


### Bug Fixes

* 🐛 show correct --version ([959d216](https://github.com/folke/devmoji/commit/959d2164ba2d0f4f64323d2f4dbcc768c32cedad))

## [2.0.2](https://github.com/folke/devmoji/compare/v2.0.1...v2.0.2) (2020-01-22)


### Bug Fixes

* 🐛 colors are now properly disabled when not on a TTY ([36406c5](https://github.com/folke/devmoji/commit/36406c5382483b650cc2141d8e05b575eed5bd94))

## [2.0.1](https://github.com/folke/devmoji/compare/v2.0.0...v2.0.1) (2020-01-16)


### Bug Fixes

* **docs:** 🐛 📚️ updated docs ([667db23](https://github.com/folke/devmoji/commit/667db23c0bf1678151ed64e7d265e15c0a3584e5))

# [2.0.0](https://github.com/folke/devmoji/compare/v1.2.2...v2.0.0) (2020-01-16)


### Bug Fixes

* **config:** 🐛 ⚙️ added correct search paths for config file ([63d2488](https://github.com/folke/devmoji/commit/63d248832a53163ee54e3f41542d8a59326aa6ce))
* **emoji:** 🐛 added support for colorful emoji variations ([dff0ede](https://github.com/folke/devmoji/commit/dff0ede10c186cf8c3abcd8112c01ce0a506ae24))
* **emoji:** 🐛 fixed emoji variations ([2d60115](https://github.com/folke/devmoji/commit/2d6011536c0b6e54980296dc4315553dfa812e63))
* **emoji:** 🐛 use unicode emoji variations when available ([c0ff022](https://github.com/folke/devmoji/commit/c0ff022bb9a53f8f0187164441926a9a2ac76eba))


* feat(commit)!: 💥 ✨ added support for ! in a breaking change header ([23ec3c9](https://github.com/folke/devmoji/commit/23ec3c9dc6cc260b9147cb88e748a0c3aa7d58f4))


### BREAKING CHANGES

* added breaking change support 😄

## [1.2.2](https://github.com/folke/devmoji/compare/v1.2.1...v1.2.2) (2020-01-15)

## [1.2.1](https://github.com/folke/devmoji/compare/v1.2.0...v1.2.1) (2020-01-15)


### Bug Fixes

* **docs:** 🐛 📚 updated README.md ([6366bd3](https://github.com/folke/devmoji/commit/6366bd3b437706a9d2d079df2ea7b711ccf943c5))

# [1.2.0](https://github.com/folke/devmoji/compare/v1.1.1...v1.2.0) (2020-01-15)


### Bug Fixes

* **cli:** 🐛 all output now honors --no-color ([a44e628](https://github.com/folke/devmoji/commit/a44e6280510869e00a10552026839139dab0262b))


### Features

* **config:** ✨ ⚙ ➕ devmojis for config, add, remove ([faa3aac](https://github.com/folke/devmoji/commit/faa3aacc05cccb212da84459321453b91414dffe))

## [1.1.1](https://github.com/folke/devmoji/compare/v1.1.0...v1.1.1) (2020-01-15)


### Bug Fixes

* **security:** 🐛 🔒 upgraded lodash & underscore from security advisory ([d2d39be](https://github.com/folke/devmoji/commit/d2d39bebfb961f1f6d7178b6c8b9fe119c3c5843))

# [1.1.0](https://github.com/folke/devmoji/compare/v1.0.1...v1.1.0) (2020-01-15)


### Features

* ✨ added semantic-release ([a597cd1](https://github.com/folke/devmoji/commit/a597cd1167911a3cdc6d42f62e30106519bc27c0))

# 0.0.0 (2020-01-14)


### Features

* ✨ added support for git hooks ([799f156](https://github.com/folke/devmoji/commit/799f1569b441a2ab708ad18df46f4bd969534514))
* ✨ refactored config files and added runtime validation ([cc94e2c](https://github.com/folke/devmoji/commit/cc94e2c71e7a79422dde32faab21313c60331631))
* ✨ we now support scope based devmojis and --color for --log ([a3df981](https://github.com/folke/devmoji/commit/a3df981a205ca1def58b57e3f408274500811fa1))
* **cli:** ✨ added cli for working with devmoji 🚀 ([8f16492](https://github.com/folke/devmoji/commit/8f16492295908f26db5f5e4b93a075f516629a13))
* **config:** ✨ added devmoji configs ([4379667](https://github.com/folke/devmoji/commit/43796674bfb9061995a687ea90b7b3c81226d015))
* **emoji:** :sparkles: added script to fetch github and gitmoji ([aecf9df](https://github.com/folke/devmoji/commit/aecf9dfa41350520788e1a57657eff16b13434cd))
* ✨ devmoji package ([e7e2b61](https://github.com/folke/devmoji/commit/e7e2b61105bf86305d2ec632db731b22c0008370))


### Performance Improvements

* ⚡ configured vscode debugging support ([1e0876a](https://github.com/folke/devmoji/commit/1e0876adfe7056285057d3b924f90d8cbeede0b5))


### BREAKING CHANGES

* devmoji can now be used as a prepare-commit-msg hook to
automagically add emojis to commit messages
