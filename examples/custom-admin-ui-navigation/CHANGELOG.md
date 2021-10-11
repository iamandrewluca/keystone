# @keystone-next/example-custom-navigation-component

## 5.0.3

### Patch Changes

- [#6744](https://github.com/keystonejs/keystone/pull/6744) [`0ef1ee3cc`](https://github.com/keystonejs/keystone/commit/0ef1ee3ccd99f0f3e1f955f03d00b1a0f238c7cd) Thanks [@bladey](https://github.com/bladey)! - Renamed branch `master` to `main`.

- Updated dependencies [[`73544fd19`](https://github.com/keystonejs/keystone/commit/73544fd19b865be9fbf3ea9ae68fae5f039eb13f), [`0ef1ee3cc`](https://github.com/keystonejs/keystone/commit/0ef1ee3ccd99f0f3e1f955f03d00b1a0f238c7cd), [`930b7129f`](https://github.com/keystonejs/keystone/commit/930b7129f37beb396bb8ecc8a8dc9f1b3615a7e0), [`fac96cbd1`](https://github.com/keystonejs/keystone/commit/fac96cbd14febcc01bdffbecd1aceee391f6a20a), [`3d289eb3d`](https://github.com/keystonejs/keystone/commit/3d289eb3d00c3e6a0c26ce962fb0f942a08c400a), [`bed3a560a`](https://github.com/keystonejs/keystone/commit/bed3a560a59d4fe787f3beebd65f8148453aae35), [`930b7129f`](https://github.com/keystonejs/keystone/commit/930b7129f37beb396bb8ecc8a8dc9f1b3615a7e0), [`6e4a0cf56`](https://github.com/keystonejs/keystone/commit/6e4a0cf56ce35b2446db7970763c55446de3db0e), [`d64bd4a7f`](https://github.com/keystonejs/keystone/commit/d64bd4a7f3da87e13e9cac41f0eb9757b771835f), [`abeceaf90`](https://github.com/keystonejs/keystone/commit/abeceaf902c231aabe9cf3a383ecf29c09b8f4dd), [`704f68b38`](https://github.com/keystonejs/keystone/commit/704f68b38f970860137380e21c36e04d2c51a7a4), [`576f341e6`](https://github.com/keystonejs/keystone/commit/576f341e61b31bbcf076ba70002d137c7b7ff9a9)]:
  - @keystone-next/keystone@26.1.0

## 5.0.2

### Patch Changes

- [#6409](https://github.com/keystonejs/keystone/pull/6409) [`3ece149e5`](https://github.com/keystonejs/keystone/commit/3ece149e53066661c57c56fdd1467003c5b11c06) Thanks [@timleslie](https://github.com/timleslie)! - Upgraded Apollo Server to [Version 3](https://www.apollographql.com/docs/apollo-server/migration/).

  The Apollo documentation contains a full list of breaking changes introduced by this update.
  You can configure the Apollo Server provided by Keystone using the [`graphql.apolloConfig`](https://keystonejs.com/docs/apis/config#graphql) configuration option.

  The most prominant change for most users will be that the GraphQL Playground has been replaced by the Apollo Sandbox.
  If you prefer to keep the GraphQL Playground, you can configure your server by [following these instructions](https://www.apollographql.com/docs/apollo-server/migration/#graphql-playground).

- Updated dependencies [[`5c0163e09`](https://github.com/keystonejs/keystone/commit/5c0163e0973e5fee9b1e2c2b1f2834284858a509), [`7f5caff60`](https://github.com/keystonejs/keystone/commit/7f5caff60308112ded832db4703f33eaae00ce24), [`480c875d1`](https://github.com/keystonejs/keystone/commit/480c875d11700f9eb23f403a5bb277aa94c38ce7), [`3ece149e5`](https://github.com/keystonejs/keystone/commit/3ece149e53066661c57c56fdd1467003c5b11c06), [`d0e3c087e`](https://github.com/keystonejs/keystone/commit/d0e3c087e49310774b9538dfa5d2432c00381db0), [`21c5d1aa9`](https://github.com/keystonejs/keystone/commit/21c5d1aa964a19657d4ba7eb913e8ca292bf1714), [`8bbba49c7`](https://github.com/keystonejs/keystone/commit/8bbba49c74fd4b7cf2560613c9cf6bcaddb11a6f), [`42268ee72`](https://github.com/keystonejs/keystone/commit/42268ee72707e94a6197607d24534a438b748649), [`d9e18613a`](https://github.com/keystonejs/keystone/commit/d9e18613a4136f1c1201a197e47d9d4bde292cd2), [`e81947d6c`](https://github.com/keystonejs/keystone/commit/e81947d6ccb0b541387519898fdbbf09274d4c9f), [`5d3fc0b77`](https://github.com/keystonejs/keystone/commit/5d3fc0b77c92efc69d725f943626d8d76a28e799), [`3cfc2a383`](https://github.com/keystonejs/keystone/commit/3cfc2a3839142dd3ccdbf1dd86768257e9acc0dc), [`1da120a38`](https://github.com/keystonejs/keystone/commit/1da120a388a80585e897a06b81b027b7d8011902), [`499c00b44`](https://github.com/keystonejs/keystone/commit/499c00b44b4b378285ed21a385da799b4af0af82), [`eb1a89f3c`](https://github.com/keystonejs/keystone/commit/eb1a89f3c13d4e80516cc372cef3dc505ef864f3), [`4da935870`](https://github.com/keystonejs/keystone/commit/4da935870374414e83900949cc70fce0d4b6de19), [`1faddea9d`](https://github.com/keystonejs/keystone/commit/1faddea9d285c70d2d867958bc5ab2bbfb44dbd6), [`7de13bce3`](https://github.com/keystonejs/keystone/commit/7de13bce32630ee2478a9894e801020c520c64a9), [`271e5d97b`](https://github.com/keystonejs/keystone/commit/271e5d97bc2e4548ce039a568278f9f7569aa41a), [`0218a4215`](https://github.com/keystonejs/keystone/commit/0218a421576fb3ceb38eb5f38223a9ef0af4c4d2), [`273ee446a`](https://github.com/keystonejs/keystone/commit/273ee446a6d3e22c4d01c530d33282df362a6f1b), [`14bfa8a9b`](https://github.com/keystonejs/keystone/commit/14bfa8a9b33fae4c5eb3664ca23bb88850df5e50), [`8bbba49c7`](https://github.com/keystonejs/keystone/commit/8bbba49c74fd4b7cf2560613c9cf6bcaddb11a6f), [`a645861a9`](https://github.com/keystonejs/keystone/commit/a645861a9562748cf3e9786e37acea67c4a0cc17), [`581e130cf`](https://github.com/keystonejs/keystone/commit/581e130cf2a833c2b363801a32f4791bc1c7c62c), [`689d8ecaa`](https://github.com/keystonejs/keystone/commit/689d8ecaa9e93eedc80084aafc319a0396efc593), [`144f7f8e4`](https://github.com/keystonejs/keystone/commit/144f7f8e4e13ec547865927cb224fea7165b98b7), [`f963966ab`](https://github.com/keystonejs/keystone/commit/f963966ab138a315a8f18d83ed7a676f7423a51d), [`b76974736`](https://github.com/keystonejs/keystone/commit/b76974736132a71d693b3e325ffa009d395840a4), [`47c8b53ce`](https://github.com/keystonejs/keystone/commit/47c8b53ce44b7ad34ba40501a257a2b679cdee05), [`a95da1d81`](https://github.com/keystonejs/keystone/commit/a95da1d812574fd17d1fa8bc324415da558a9d9d), [`1b0a2f516`](https://github.com/keystonejs/keystone/commit/1b0a2f516d7d9ffce2e470dcd9ea870a3274500b), [`7621d0db7`](https://github.com/keystonejs/keystone/commit/7621d0db75033b68a510d5f6c9b03d9418980e73), [`67492f37d`](https://github.com/keystonejs/keystone/commit/67492f37dd9fbcd94234c15a072e9c826fa7a665), [`002e1d88b`](https://github.com/keystonejs/keystone/commit/002e1d88b0908c2e1215c1181724b2bc1cc57538), [`ca48072b4`](https://github.com/keystonejs/keystone/commit/ca48072b4d137e879e328c93b703a8364562db8a), [`10c61bd44`](https://github.com/keystonejs/keystone/commit/10c61bd44176ffa7d0e446c28fd9f12ed54790f0), [`1659e1fe5`](https://github.com/keystonejs/keystone/commit/1659e1fe5e0f394df058b3a773ea62bf392fa8db), [`3b9732acd`](https://github.com/keystonejs/keystone/commit/3b9732acd8cd597fa9c70128a2e7129ed02e6775), [`c2b124f8e`](https://github.com/keystonejs/keystone/commit/c2b124f8e4b283022ec473d9e5f32f37de639cf0), [`4048991ba`](https://github.com/keystonejs/keystone/commit/4048991ba7db234a694287000beaf2ea052cd24e), [`79e2cc3aa`](https://github.com/keystonejs/keystone/commit/79e2cc3aa79a90358a6ce1281a8ad5f5632ac185), [`1f952fb10`](https://github.com/keystonejs/keystone/commit/1f952fb10710b7fae6a88112310b25a09ab330ea), [`1b0a2f516`](https://github.com/keystonejs/keystone/commit/1b0a2f516d7d9ffce2e470dcd9ea870a3274500b), [`4e485a914`](https://github.com/keystonejs/keystone/commit/4e485a914cfbc6c4b5ef9eeca9157bf654469b2d), [`3ee4542a8`](https://github.com/keystonejs/keystone/commit/3ee4542a884d8135299178950ab47bb82907bcd9), [`e84f8f655`](https://github.com/keystonejs/keystone/commit/e84f8f6550cff4fbca69982e0371d787e67c8915), [`ca48072b4`](https://github.com/keystonejs/keystone/commit/ca48072b4d137e879e328c93b703a8364562db8a), [`e747ef6f3`](https://github.com/keystonejs/keystone/commit/e747ef6f31590799fa332e1f011b160a443fbeb4), [`5e62702ba`](https://github.com/keystonejs/keystone/commit/5e62702ba3934bf8effb5dce65466017dd868610), [`b00596d3f`](https://github.com/keystonejs/keystone/commit/b00596d3f8b64cddc46ec9e5e4e567dd67264253), [`80cd31303`](https://github.com/keystonejs/keystone/commit/80cd313033b339d90b5e640b252a357a4d60fbcd), [`c8aca958b`](https://github.com/keystonejs/keystone/commit/c8aca958b3650f10011370e0c00b01cb681bb212), [`232c512a0`](https://github.com/keystonejs/keystone/commit/232c512a05250cb8a9c26b70969afe4106e2f8ac), [`8631917d1`](https://github.com/keystonejs/keystone/commit/8631917d14778468652abb8eda06802d2469646c), [`b6c8c3bff`](https://github.com/keystonejs/keystone/commit/b6c8c3bff9d3d98f743c47c015ae27e63db0271e), [`bf5874411`](https://github.com/keystonejs/keystone/commit/bf58744118320493325b3b48aadd007e12d5c680), [`398c08529`](https://github.com/keystonejs/keystone/commit/398c085295d992658a9e7e22aae037f55528c258), [`47cee8c95`](https://github.com/keystonejs/keystone/commit/47cee8c952c1134e503bff54e61dcd48c76b5429), [`9f0a4cc1f`](https://github.com/keystonejs/keystone/commit/9f0a4cc1f6d5133e92a0d326e285152d18689173), [`838845298`](https://github.com/keystonejs/keystone/commit/8388452982277b10c65ff89be442464761a680a7), [`11fb46c91`](https://github.com/keystonejs/keystone/commit/11fb46c918e508cc182d5bd22f069b9329edadba)]:
  - @keystone-next/keystone@26.0.0

## 5.0.1

### Patch Changes

- [#6432](https://github.com/keystonejs/keystone/pull/6432) [`0a189d5d0`](https://github.com/keystonejs/keystone/commit/0a189d5d0e618ee5598e9beaccea0290d2a3f8d9) Thanks [@renovate](https://github.com/apps/renovate)! - Updated `typescript` dependency to `^4.4.2`.

- Updated dependencies [[`2a901a121`](https://github.com/keystonejs/keystone/commit/2a901a1210a0b3de0ccd22ca93e9cbcc8ed0f951), [`3008c5110`](https://github.com/keystonejs/keystone/commit/3008c5110a0ebc524eb3609bd8ba901f664f83d3), [`3904a9cf7`](https://github.com/keystonejs/keystone/commit/3904a9cf73e16ef192faae833f2f39ed05f2d707), [`32f024738`](https://github.com/keystonejs/keystone/commit/32f0247384ecf3bce5c3ef14ad8d367c9888459f), [`2e3f3666b`](https://github.com/keystonejs/keystone/commit/2e3f3666b5340b8eb778104a1d4a3f4d52be6528), [`44f2ef60e`](https://github.com/keystonejs/keystone/commit/44f2ef60e29912f3c85b91fc704e09a7d5a15b22), [`9651aff8e`](https://github.com/keystonejs/keystone/commit/9651aff8eb9a51c0fbda6f51b1be0fedb07571da), [`9c5991f43`](https://github.com/keystonejs/keystone/commit/9c5991f43e8f909e576f6b51fd87aab3bbead504), [`069265b9c`](https://github.com/keystonejs/keystone/commit/069265b9cdd5898f4501535793f56debaa247c1c), [`4f36a81af`](https://github.com/keystonejs/keystone/commit/4f36a81afb03591354acc1d0141eff8fe54ff208), [`c76bfc0a2`](https://github.com/keystonejs/keystone/commit/c76bfc0a2ad5aeffb68b8d2006225f608e855a19), [`bc9088f05`](https://github.com/keystonejs/keystone/commit/bc9088f0574af27be6a068483a789a80f7a46a41), [`ee54522d5`](https://github.com/keystonejs/keystone/commit/ee54522d513a9376c1ed1e472a7ff91657e4e693), [`32f024738`](https://github.com/keystonejs/keystone/commit/32f0247384ecf3bce5c3ef14ad8d367c9888459f), [`bd120c7c2`](https://github.com/keystonejs/keystone/commit/bd120c7c296c9adaaefe9bf93cbb384cc7528715), [`595922b48`](https://github.com/keystonejs/keystone/commit/595922b48c909053fa9d34bb1c42177ad41c72d5), [`8f2786535`](https://github.com/keystonejs/keystone/commit/8f2786535272976678427fd13758e63b2c59d955), [`b3eefc1c3`](https://github.com/keystonejs/keystone/commit/b3eefc1c336a9a366c39f7aa2cf5251baaf843fd), [`0aa02a333`](https://github.com/keystonejs/keystone/commit/0aa02a333d989c30647cd10e25325d4d2db61be6), [`bf9b5605f`](https://github.com/keystonejs/keystone/commit/bf9b5605fc684975d9e2cad604c8e0d978eac40a), [`3957c0981`](https://github.com/keystonejs/keystone/commit/3957c098131b3b055cb94b07f1ce55ec82640908), [`af5e59bf4`](https://github.com/keystonejs/keystone/commit/af5e59bf4215aa297495ae603239b1e3510be39b), [`cbc5a68aa`](https://github.com/keystonejs/keystone/commit/cbc5a68aa7547ea55d1254ee5c3b1e543cdc78e2), [`32f024738`](https://github.com/keystonejs/keystone/commit/32f0247384ecf3bce5c3ef14ad8d367c9888459f), [`783290796`](https://github.com/keystonejs/keystone/commit/78329079606d74a2eedd63f96a985116bf0b449c), [`0a189d5d0`](https://github.com/keystonejs/keystone/commit/0a189d5d0e618ee5598e9beaccea0290d2a3f8d9), [`944bce1e8`](https://github.com/keystonejs/keystone/commit/944bce1e834be4d0f4c79f35cd53ccbabb92f555), [`e0f935eb2`](https://github.com/keystonejs/keystone/commit/e0f935eb2ef8ac311a43423c6691e56cd27b6bed), [`2324fa027`](https://github.com/keystonejs/keystone/commit/2324fa027a6c2beabef4724c69a9ad05338a0cf3), [`f2311781a`](https://github.com/keystonejs/keystone/commit/f2311781a990c0ccd3302ac8e7aa889138f70e47), [`88b03bd79`](https://github.com/keystonejs/keystone/commit/88b03bd79112c7d8f0d41c592c8bd4bb226f5f71), [`0aa02a333`](https://github.com/keystonejs/keystone/commit/0aa02a333d989c30647cd10e25325d4d2db61be6), [`5ceccd821`](https://github.com/keystonejs/keystone/commit/5ceccd821b513e2abec3eb24278e7c30bdcdf6d6), [`fd744dcaa`](https://github.com/keystonejs/keystone/commit/fd744dcaa513efb2a8ae954bb2d5d1fa7f0723d6), [`489e128fe`](https://github.com/keystonejs/keystone/commit/489e128fe0835968eda0908b199a8867c0e72a5b), [`bb0c6c626`](https://github.com/keystonejs/keystone/commit/bb0c6c62610eda20ae93a6b67185276bdbba3248)]:
  - @keystone-next/keystone@25.0.0

## 5.0.0

### Major Changes

- [#6185](https://github.com/keystonejs/keystone/pull/6185) [`bc00c0a17`](https://github.com/keystonejs/keystone/commit/bc00c0a17b41a9ef016ec41b59ac394013be916d) Thanks [@gwyneplaine](https://github.com/gwyneplaine)! - Initial version of the custom-admin-ui-navigation example.

### Patch Changes

- Updated dependencies [[`e9f3c42d5`](https://github.com/keystonejs/keystone/commit/e9f3c42d5b9d42872cecbd18fbe9bf9d7d53ed82), [`5cd8ffd6c`](https://github.com/keystonejs/keystone/commit/5cd8ffd6cb822dbee8555b47846a5019c4d2b1c3), [`1cbcf54cb`](https://github.com/keystonejs/keystone/commit/1cbcf54cb1206461866b582865e3b1a8fc728f18), [`a92169d04`](https://github.com/keystonejs/keystone/commit/a92169d04e5a1a98deb8e757b8eae3b06fc66450), [`5cd8ffd6c`](https://github.com/keystonejs/keystone/commit/5cd8ffd6cb822dbee8555b47846a5019c4d2b1c3), [`b696a9579`](https://github.com/keystonejs/keystone/commit/b696a9579b503db86f42776381e247c4e1a7409f), [`f3014a627`](https://github.com/keystonejs/keystone/commit/f3014a627060c7cd86440a6937da5caecfd023a0), [`092df6678`](https://github.com/keystonejs/keystone/commit/092df6678cea18d639be16ad250ec4ecc9250f5a), [`5cd8ffd6c`](https://github.com/keystonejs/keystone/commit/5cd8ffd6cb822dbee8555b47846a5019c4d2b1c3), [`6da56b80e`](https://github.com/keystonejs/keystone/commit/6da56b80e03c748a621afcca6c1ec2887fef7271), [`4f4f0351a`](https://github.com/keystonejs/keystone/commit/4f4f0351a056dea9d1614aa2a3a4789d66bb402d), [`697efa354`](https://github.com/keystonejs/keystone/commit/697efa354b1066b3d4b6eb757ca704b458f45e93), [`c7e331d90`](https://github.com/keystonejs/keystone/commit/c7e331d90a28b2ed8236100097cb8d34a11fabe2), [`3a7a06b2c`](https://github.com/keystonejs/keystone/commit/3a7a06b2cc6b5ea157d34d925b15494b471899eb), [`272b97b3a`](https://github.com/keystonejs/keystone/commit/272b97b3a10c0dfada782171d55ef7ac6f47c98f), [`78dac764e`](https://github.com/keystonejs/keystone/commit/78dac764e1860b33f9e2bd8cee6015abeaaa5ec4), [`399561b27`](https://github.com/keystonejs/keystone/commit/399561b2769ddd8f3d3fdf29838f5784404bb053), [`9d361c1c8`](https://github.com/keystonejs/keystone/commit/9d361c1c8625e1390f837b7318b63547d686a63b), [`0dcb1c95b`](https://github.com/keystonejs/keystone/commit/0dcb1c95b5200750cc8649485425f2ae40d023a3), [`94435ffee`](https://github.com/keystonejs/keystone/commit/94435ffee765824091899242e4a2f73c7356b524), [`5cd8ffd6c`](https://github.com/keystonejs/keystone/commit/5cd8ffd6cb822dbee8555b47846a5019c4d2b1c3), [`56044e2a4`](https://github.com/keystonejs/keystone/commit/56044e2a425f4256b66475fd3b1a6342cd6c3bf9), [`f46fd32b7`](https://github.com/keystonejs/keystone/commit/f46fd32b7047dbb5ea2566859f7ecee8db5b0b15), [`874f2c405`](https://github.com/keystonejs/keystone/commit/874f2c4058c9cf006213e84b9ffcf39c5bf144e8), [`8ea4eed55`](https://github.com/keystonejs/keystone/commit/8ea4eed55367aaa213f6b4ffb7473087498e39ae), [`e3fe6498d`](https://github.com/keystonejs/keystone/commit/e3fe6498dc36203d8080dff3c2e0c25f6c98733e), [`1030296d1`](https://github.com/keystonejs/keystone/commit/1030296d1f304dc44246e895089ac1f992e80590), [`3564b342d`](https://github.com/keystonejs/keystone/commit/3564b342d6dc2127ae591d7ac055af9eae90543c), [`8b2d179b2`](https://github.com/keystonejs/keystone/commit/8b2d179b2463d78b082182ca9afa8233109e0ba3), [`e3fefafcc`](https://github.com/keystonejs/keystone/commit/e3fefafcce6f8bf836c9bf0f4d931b8200ba41c7), [`4d9f89f88`](https://github.com/keystonejs/keystone/commit/4d9f89f884e2bf984fdd74ca2cbb7874b25b9cda), [`686c0f1c4`](https://github.com/keystonejs/keystone/commit/686c0f1c4a1feb609e1584aa71738709bbbf984e), [`8187ea019`](https://github.com/keystonejs/keystone/commit/8187ea019a212874f3c602573af3382c6f3bd3b2), [`d214e2f72`](https://github.com/keystonejs/keystone/commit/d214e2f72bae1c798e2415a38410d6063c333e2e), [`f5e64af37`](https://github.com/keystonejs/keystone/commit/f5e64af37df2eb460c89d89fa3c8924fb34970ed)]:
  - @keystone-next/fields@14.0.0
  - @keystone-next/keystone@24.0.0
  - @keystone-next/types@24.0.0