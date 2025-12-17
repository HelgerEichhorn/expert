# Changelog

## [0.1.0](https://github.com/HelgerEichhorn/expert/compare/v0.1.0...v0.1.0) (2025-12-17)


### ⚠ BREAKING CHANGES

* add CLI flag handling ([#185](https://github.com/HelgerEichhorn/expert/issues/185))

### Features

* add CLI flag handling ([#185](https://github.com/HelgerEichhorn/expert/issues/185)) ([b8a08e7](https://github.com/HelgerEichhorn/expert/commit/b8a08e75d52d008639b69b8a6998bd54bada8a50))
* epmdless clustering ([#205](https://github.com/HelgerEichhorn/expert/issues/205)) ([b89bb4c](https://github.com/HelgerEichhorn/expert/commit/b89bb4c42b2305adadeb6cb4b71ac1ca1394ec5d))
* epmdless deployments ([#167](https://github.com/HelgerEichhorn/expert/issues/167)) ([2f4b85a](https://github.com/HelgerEichhorn/expert/commit/2f4b85a65313c8644680f9524db4cde42b77de3f))
* on the fly engine builds ([#24](https://github.com/HelgerEichhorn/expert/issues/24)) ([54c007c](https://github.com/HelgerEichhorn/expert/commit/54c007c9a9cfd04e86b99e39a98116d305f248a4))


### Bug Fixes

* add lsp logging when failing to find an elixir executable ([#169](https://github.com/HelgerEichhorn/expert/issues/169)) ([d72de91](https://github.com/HelgerEichhorn/expert/commit/d72de91e9956f4efa7476b86a70fd57f5ebadc8a))
* better handling of native&lt;-&gt;lsp conversions ([#34](https://github.com/HelgerEichhorn/expert/issues/34)) ([a8960bd](https://github.com/HelgerEichhorn/expert/commit/a8960bdbc5421b2159a0a30586ef0b5cb684959f))
* bring back completions for things defined in test files ([#32](https://github.com/HelgerEichhorn/expert/issues/32)) ([3240bf7](https://github.com/HelgerEichhorn/expert/commit/3240bf7ee3d00f7c31686351bda36bcba4a80cb4))
* clamp start_char for comletion prefix ([#239](https://github.com/HelgerEichhorn/expert/issues/239)) ([a07091b](https://github.com/HelgerEichhorn/expert/commit/a07091b9adfbd5fcd1569cb37bf38d2165ebd1fb))
* Crash when typing english ([#742](https://github.com/HelgerEichhorn/expert/issues/742)) ([7d8dff9](https://github.com/HelgerEichhorn/expert/commit/7d8dff978cf7d1e36e6c1bfd2b79dcc371e19e4b)), closes [#741](https://github.com/HelgerEichhorn/expert/issues/741)
* Current module not identified in defimpl ([#665](https://github.com/HelgerEichhorn/expert/issues/665)) ([543012e](https://github.com/HelgerEichhorn/expert/commit/543012ef1ae8e42b8a36ed1589f16e4e11dc37d0))
* disable shell sessions when fetching the PATH ([#177](https://github.com/HelgerEichhorn/expert/issues/177)) ([5208307](https://github.com/HelgerEichhorn/expert/commit/52083079ac6bdd20047d39527ffc017c1cd2ced4))
* do not clamp character recvd from client ([#123](https://github.com/HelgerEichhorn/expert/issues/123)) ([7294dd9](https://github.com/HelgerEichhorn/expert/commit/7294dd94658419de2fbc7974b30cd5a56b0475c3))
* don't convert to_lsp twice in server specific messages ([#190](https://github.com/HelgerEichhorn/expert/issues/190)) ([c107ac0](https://github.com/HelgerEichhorn/expert/commit/c107ac0e8c7fb5f95eea6029feefe62c60468472))
* don't sometimes hang ([4ff90cf](https://github.com/HelgerEichhorn/expert/commit/4ff90cf5fa8f3cb6012e8f82933386e23e5f2704))
* Edge case for module loading ([#738](https://github.com/HelgerEichhorn/expert/issues/738)) ([e283265](https://github.com/HelgerEichhorn/expert/commit/e283265ce4b3739253c54affe3dbb18c9107c4e3))
* elixir path discovery ([#248](https://github.com/HelgerEichhorn/expert/issues/248)) ([16d8ea8](https://github.com/HelgerEichhorn/expert/commit/16d8ea8396cb43ba10fcfc1ee9dfbbd356aee112))
* **engine:** handle failing build script ([#188](https://github.com/HelgerEichhorn/expert/issues/188)) ([5521631](https://github.com/HelgerEichhorn/expert/commit/5521631f852aa186ebc419231c13a2051fd29591))
* Erlang function calls in pipes were incorrectly formatted ([#476](https://github.com/HelgerEichhorn/expert/issues/476)) ([a3565a7](https://github.com/HelgerEichhorn/expert/commit/a3565a731b87f2a90f93a19b5c88c15d5e091586)), closes [#475](https://github.com/HelgerEichhorn/expert/issues/475)
* Exclude expert dependencies from completions based on project dependencies ([be66b2a](https://github.com/HelgerEichhorn/expert/commit/be66b2ab1ad32436deacd49023be6256c866aa9d))
* fix release-all command ([87e74d4](https://github.com/HelgerEichhorn/expert/commit/87e74d4e35e5fddd56e7670cf6cf9403d725ee62))
* fixup namespacing and packaging ([#29](https://github.com/HelgerEichhorn/expert/issues/29)) ([c4b41aa](https://github.com/HelgerEichhorn/expert/commit/c4b41aae6ce5ec15f665d9199fdfadd60178af42))
* formatting format incorrectly when contain special character ([#252](https://github.com/HelgerEichhorn/expert/issues/252)) ([77ddb4f](https://github.com/HelgerEichhorn/expert/commit/77ddb4fef1e0b71244cdf74187eb652eac2bf41d))
* Function definition extractor chokes on macro functions ([#682](https://github.com/HelgerEichhorn/expert/issues/682)) ([2df8e25](https://github.com/HelgerEichhorn/expert/commit/2df8e256e423437b78bc7ad3539231be4f2beae0)), closes [#680](https://github.com/HelgerEichhorn/expert/issues/680)
* give proper argument to `TaskQueue.add/2` in Server.handle_message ([#791](https://github.com/HelgerEichhorn/expert/issues/791)) ([c6b544a](https://github.com/HelgerEichhorn/expert/commit/c6b544a7a2a695c2dd0f3bb94e2e17d739db976e))
* handle string ids in requests ([#120](https://github.com/HelgerEichhorn/expert/issues/120)) ([4ff90cf](https://github.com/HelgerEichhorn/expert/commit/4ff90cf5fa8f3cb6012e8f82933386e23e5f2704))
* include erlang source files when packaging engine ([1987803](https://github.com/HelgerEichhorn/expert/commit/1987803d223ee3e166456e00226265a865ce3484))
* Invalid reads for requests that contain multi-byte characters ([#661](https://github.com/HelgerEichhorn/expert/issues/661)) ([2f88465](https://github.com/HelgerEichhorn/expert/commit/2f884657c68ac4cd4e84f5f047d9257958595114))
* let the system figure out the elixir version for the project ([#162](https://github.com/HelgerEichhorn/expert/issues/162)) ([8cfcc40](https://github.com/HelgerEichhorn/expert/commit/8cfcc403c293d35508b38196b04cbef9f172df30))
* make sure asdf shims are in the PATH ([#87](https://github.com/HelgerEichhorn/expert/issues/87)) ([26cfc3f](https://github.com/HelgerEichhorn/expert/commit/26cfc3fba339579a242e544bca56b05aad89931b))
* Module suggestion was incorrect for files with multiple periods ([#705](https://github.com/HelgerEichhorn/expert/issues/705)) ([15fcd50](https://github.com/HelgerEichhorn/expert/commit/15fcd5096a5f82d55615e39abf60a2ba5d9c7407)), closes [#703](https://github.com/HelgerEichhorn/expert/issues/703)
* nil.__struct__/0 is undefined when receiving shutdown ([#250](https://github.com/HelgerEichhorn/expert/issues/250)) ([7f286c5](https://github.com/HelgerEichhorn/expert/commit/7f286c535f2e98903f91d043a37443311189a399))
* **nix:** use eval release command ([#199](https://github.com/HelgerEichhorn/expert/issues/199)) ([e62e878](https://github.com/HelgerEichhorn/expert/commit/e62e8788a20c858b0817f681fc0b8584a28e883c))
* Non-string test names crash exunit indexer ([#676](https://github.com/HelgerEichhorn/expert/issues/676)) ([46cb595](https://github.com/HelgerEichhorn/expert/commit/46cb595082e855eb5d84a61886ed1b289a0873bf)), closes [#675](https://github.com/HelgerEichhorn/expert/issues/675)
* properly log when engine fails to initialize ([#244](https://github.com/HelgerEichhorn/expert/issues/244)) ([9acfaf3](https://github.com/HelgerEichhorn/expert/commit/9acfaf3912fa163e4065588dd06237abe5f872b0))
* properly set the mix env when building expert ([48ea7c1](https://github.com/HelgerEichhorn/expert/commit/48ea7c13bfdbf1ac6e89fdd42ee03fcf16265379))
* remove erts from extra_applications ([#202](https://github.com/HelgerEichhorn/expert/issues/202)) ([b3ce6ec](https://github.com/HelgerEichhorn/expert/commit/b3ce6ec692d0d0b44700f0cb13f8e5b823bf471d))
* remove escape sequences from PATH in fish ([#237](https://github.com/HelgerEichhorn/expert/issues/237)) ([8d35cde](https://github.com/HelgerEichhorn/expert/commit/8d35cdeedf6a28677f936832bcb57192f1c4065c))
* Resolve doesn't recognize zero-arg defs as functions ([#606](https://github.com/HelgerEichhorn/expert/issues/606)) ([fe5259b](https://github.com/HelgerEichhorn/expert/commit/fe5259b5c378744be747963ed0bea94c0e832327)), closes [#604](https://github.com/HelgerEichhorn/expert/issues/604)
* revert "feat: epmdless deployments ([#167](https://github.com/HelgerEichhorn/expert/issues/167))" ([#180](https://github.com/HelgerEichhorn/expert/issues/180)) ([7cf09a7](https://github.com/HelgerEichhorn/expert/commit/7cf09a7f5af785fae48ff8d3b714bd74fc989c61))
* revert dev server ([#48](https://github.com/HelgerEichhorn/expert/issues/48)) ([33ce4d1](https://github.com/HelgerEichhorn/expert/commit/33ce4d19bf193fee1c5566fe36e5f67f159c48a0))
* stop sending genlsp datastructures to engine ([#31](https://github.com/HelgerEichhorn/expert/issues/31)) ([c9ad9ad](https://github.com/HelgerEichhorn/expert/commit/c9ad9ad4995957c5f04e3b173bbbf9a84fb8e2de))
* Stutter when completing inside string interpolations ([#464](https://github.com/HelgerEichhorn/expert/issues/464)) ([481b324](https://github.com/HelgerEichhorn/expert/commit/481b324b674bfc2974b1a39707c4efd837de2c55)), closes [#462](https://github.com/HelgerEichhorn/expert/issues/462)
* support Fish shell's space-separated PATH format ([#172](https://github.com/HelgerEichhorn/expert/issues/172)) ([9091f81](https://github.com/HelgerEichhorn/expert/commit/9091f8195d614184f5c4adc42e706519a03e827e))
* trim any quotes wrapping PATH when elixir is managed by mise ([#82](https://github.com/HelgerEichhorn/expert/issues/82)) ([5467143](https://github.com/HelgerEichhorn/expert/commit/54671434bf5fa74dbf18fcb5894fe4c02441876b))
* trim PATH returned by shell ([#213](https://github.com/HelgerEichhorn/expert/issues/213)) ([94b4c9b](https://github.com/HelgerEichhorn/expert/commit/94b4c9bf82a0dc2209cfbe193ed5c5760b2dcb55))
* use correct build directory when namespacing expert ([cb8fcf1](https://github.com/HelgerEichhorn/expert/commit/cb8fcf193924828751de290863106b579648cd80))
* use dynamic registrations and start project node asynchronously ([#30](https://github.com/HelgerEichhorn/expert/issues/30)) ([5b1cce8](https://github.com/HelgerEichhorn/expert/commit/5b1cce8258f6d3551a6665c9ea617388512ca4c0))
* use project directory when building engine ([#203](https://github.com/HelgerEichhorn/expert/issues/203)) ([0583a2e](https://github.com/HelgerEichhorn/expert/commit/0583a2ea880edd2a64a8ce267784e07060fe2283))
* utf8_prefix should take into account empty lines ([#164](https://github.com/HelgerEichhorn/expert/issues/164)) ([db048ed](https://github.com/HelgerEichhorn/expert/commit/db048ed85729a555380c4bc335643623346e985f))


### Miscellaneous Chores

* release as 0.1.0 ([2b81ff1](https://github.com/HelgerEichhorn/expert/commit/2b81ff18f1076b2275b45f4546775a4a74614091))

## Unreleased
No changes yet
