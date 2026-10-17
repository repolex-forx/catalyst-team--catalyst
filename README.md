# Repolex Knowledge Graph of catalyst-team/catalyst

RDF knowledge graph data for [catalyst-team/catalyst](https://github.com/catalyst-team/catalyst), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download catalyst-team/catalyst
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e99f90655d0efcf22559a46e928f0f98c9807ebf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e99f90655d0efcf22559a46e928f0f98c9807ebf
│           └── chunk-001.nq.gz
└── blob
    ├── 000ce2b0fa08a7e14c6612351bb7e2e8a97b15bf.nq.gz
    ├── 018519ae197366e6cbb93213f99827860a9409ea.nq.gz
    ├── 018d14b91fe128d53e1e6201c9a8d299be566a9d.nq.gz
    ├── 019ab62477564e9eefdfcdf1e6fe926994cab45b.nq.gz
    ├── 022c408d320b875e33e472745a69c2bc70b6d7b2.nq.gz
    ├── 024539458dab40273eda7474493b1ff6596db759.nq.gz
    ├── 046a6bd1f6f00be44ddecd734bfb5ea940411b72.nq.gz
    ├── 050e9eeda077c53d4a8d7882177d783855e943e4.nq.gz
    ├── 0552a3e0c4cb450f20c24060cba008502deef3c6.nq.gz
    ├── 05a21f2f1761f5d0232ef1e959e65b0738695c51.nq.gz
    ├── 05c3e20b99c71c16530d0de26df23d08faf86fcd.nq.gz
    ├── 05c64f383c2942f6e69efd1137cc595c800a5524.nq.gz
    ├── 05e73b036806f5f9a0a60c3cf901c2d11f467ceb.nq.gz
    ├── 074d684b8c67ab8e41dc960c9fdfe4077a483494.nq.gz
    ├── 075c7d7c05b10e2dce71f6dee6fd1c342e72841e.nq.gz
    ├── 080b2443492b34f6c006f205a8049e1757e2fcbc.nq.gz
    ├── 081789e266b2b4df307913c1d4d2bc3536dc67a3.nq.gz
    ├── 08bf0c8cd07602b20f1867629ea14a54dd90ac02.nq.gz
    ├── 08ca5d8af5778657bcdec0b01e629b0de5970271.nq.gz
    ├── 09c5d5c3d3ab054197467a2fb9f1da174367074d.nq.gz
    ├── 0bb7e0b0771c8abcf00b2b44304735f9e836ae4a.nq.gz
    ├── 0beb0b30c96143fb1e45cf49e3c673ab5813cc6a.nq.gz
    ├── 0d67690e9be75b3b55ae9a0af162f48bc480efc9.nq.gz
    ├── 0deff76a75e9bfe27af88444363d8661ca4234e2.nq.gz
    ├── 0e4ab0970cc29f29dcda1603d0c67f4eb8ca38c0.nq.gz
    ├── 0e5bcdfad395371ddaaa6306b534629d52a38688.nq.gz
    ├── 0e8961f357932c6f57b68ab9acb081d4fe8c71fd.nq.gz
    ├── 0fd60fefb795d83f4e1535f3de385eb859add7eb.nq.gz
    ├── 116bfa6c9a0dc5b0f81d2334ed30511a20d43e41.nq.gz
    ├── 11ed38a24171892235640ea17f581bf906b2a6e1.nq.gz
    ├── 11f43bd0a55d9dd850056e039c508724a3eb62ca.nq.gz
    ├── 1243dd5003e32d2a72901414df3d1407f35b806f.nq.gz
    ├── 13a19eb056758c950332c44e03a5b1af1e170c3a.nq.gz
    ├── 140d6ace3c7f24bdd55d7dd684e5d04ec820d519.nq.gz
    ├── 143fdec56727a38679caf01a83acadfcea62824e.nq.gz
    ├── 149c33be4a5e564af6035607f7a09bd6d7c1cff9.nq.gz
    ├── 14b80296d8bdea93b005142c99e4364ab21f0b61.nq.gz
    ├── 15a088fa4639b5a65950c57060fae58d3eb2c6e1.nq.gz
    ├── 163d3a67271e48acd1cd5b0798821f6ccf1f2952.nq.gz
    ├── 164de35ab252294ba4626eef4207b25d30daf2a4.nq.gz
    ├── 1671b9408dc54fe7cf990805cb091436c4783985.nq.gz
    ├── 172f53752ee43cb6b182239ecb4d759f9790c605.nq.gz
    ├── 17990bbae93d7288a80f7010eba8c9186f37cd8c.nq.gz
    ├── 17ba146fbf601deac731cfbfd1d3ff6babf54d16.nq.gz
    ├── 1a054d56e9777ea1329fd2902f4ac0237bcd067a.nq.gz
    ├── 1a39bb669b588cd65847ffe090346fbce66ec4d2.nq.gz
    ├── 1a8874b43dc43db63a31d6fee695af0b0762889d.nq.gz
    ├── 1b06dbd22e97e4c289eeea84fe3ec76e97fc85e8.nq.gz
    ├── 1b659a53af3fad105e0f5b331db528a9ac6e2f9a.nq.gz
    ├── 1c37e08a2814f22173b8f576e4d66f6882d21e10.nq.gz
    ├── 1c6a2cbc7935160fc3da609154cf26647d27208b.nq.gz
    ├── 1d4388461416c126b26b5385a6a07fe7e2b46d3a.nq.gz
    ├── 1d4c2a8b3aa0a68553f72c5d8fcff82e812291d9.nq.gz
    ├── 1d4e9ee5bec3f0a30cc051ac85e1e39c2d296122.nq.gz
    ├── 1d9dd947266028c0ae834540d0177e4603f33e63.nq.gz
    ├── 1e039293bc0d11ae08db9d29f7add4af34d1e931.nq.gz
    ├── 1e1ffe7220ee0b753c43a5a077c6b10ebbacab84.nq.gz
    ├── 1e6a8a6af6a4bc33c9c107e58c4f0fdbabee86cd.nq.gz
    ├── 1eed2245d08a9839c639fe24284bcc85780b2c86.nq.gz
    ├── 1ff9f0320799d6a29521c014ce7ba97e83368045.nq.gz
    ├── 2004d43df4107cd848be2783c9a771d6729c61e8.nq.gz
    ├── 2261c6564ab0af492609ef11eadab63bb8349f99.nq.gz
    ├── 226e3a8564719131ec51f4a1e3be6a0fd2659c18.nq.gz
    ├── 22c42f2e454fea8bd9a1f44762db1c757e66b0fd.nq.gz
    ├── 22dfca2fad79da71016a76abc460a3f9d849acbb.nq.gz
    ├── 22e05a3c29178e417a4fa216dbd369182f772dbd.nq.gz
    ├── 233e30b9a9badad260eecd4ce22b5789ff29a5e6.nq.gz
    ├── 241701d935dbf601c223e0fb8a93eb9d2a1b8349.nq.gz
    ├── 242447d3da40821725cff2d9d179d2463aa646ad.nq.gz
    ├── 244635ea77a6dfd83ee9b7b721e6d80a3bfca767.nq.gz
    ├── 248f64a117cebbf03d58b2bcdbeac5bb8eee3ac6.nq.gz
    ├── 24cedc9aa1fb9cf96e7567327d33e179dcd2e76e.nq.gz
    ├── 24fd64ec3205fd0a35afe1e61d58c5c220f52ab2.nq.gz
    ├── 2661530086277bc0f57fd1bea4734d96cfc18d1d.nq.gz
    ├── 26a90e4158787293aa729c60b3a7059f7ac07238.nq.gz
    ├── 26c306284fa76ed357f1a95173f67df8b6b398fc.nq.gz
    ├── 272ca69fd1d252646edad412671b7ff3328c855a.nq.gz
    ├── 2750f4cb358571bd1d5f8cd2cfea22aec25d33a9.nq.gz
    ├── 27ac8b0c812b28443a9c7da79632d3eb7f50c71c.nq.gz
    ├── 27d544f1fb52a86a9f6b02476d1cc798b8ceb927.nq.gz
    ├── 2952ef870bd60b07632afd9ea2c7faf3de3b3e25.nq.gz
    ├── 295d620145d0aad124353f7ab7b39ed3d827cbe0.nq.gz
    ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
    ├── 29935dc0991a47981bdca5f89548c8528d28487a.nq.gz
    ├── 2a2e7fafb323be030921b76ed4d82807bf2f87bf.nq.gz
    ├── 2a5e0a3b295c0291828e798337c88c579749c333.nq.gz
    ├── 2a79108c44f8b1dbaea335c70717763655725dc2.nq.gz
    ├── 2a85ddbb94d93df77a36bc38263a7f0430c3f7a7.nq.gz
    ├── 2abe53a27a090991195f9a7fe5ac9b3587cde568.nq.gz
    ├── 2ac6dc0a444d6c2ab0ec189692b289fc4ee4a3ca.nq.gz
    ├── 2bcdd20a8a7ba98838697012ed7486cf4344162e.nq.gz
    ├── 2bff8732320bc72294384a841f72af22dd264d36.nq.gz
    ├── 2cc5077ac99086b31925687d858b245486baafb7.nq.gz
    ├── 2e1dbe75f6ab70f27c5deac7ae1d02d37030fad6.nq.gz
    ├── 2f48e1d6fb968a28da6ea202b50803ae7a58e03e.nq.gz
    ├── 2f7ae1787951293582e9f3c12fff88a44f4ca686.nq.gz
    ├── 3000f59cb730efdaf12c411ba903b969f7facf3c.nq.gz
    ├── 30d1403d524b534953a1e2aa605e2d72cfc3b23f.nq.gz
    ├── 31612f53940802a631a423072435de916c69e230.nq.gz
    ├── 323e98262524808b65b3f06991008385ae48cc8c.nq.gz
    ├── 3293b1c0f4cb139273cc2a62026323f225aef315.nq.gz
    ├── 3365ce1bf6995ca6195fb363ec8f57d7703de330.nq.gz
    ├── 33a797eff1c1cee46dea5e8808bef85c9a2ad5b7.nq.gz
    ├── 34fd4e2f04469e5a401254eb4e093b44a9902b20.nq.gz
    ├── 35503317e55da7b1d4e8347e7f1b229183a8e466.nq.gz
    ├── 360a96ae4b5eedb6d10170ebee4050ab2cd279e2.nq.gz
    ├── 3619593c6b20107900673bc239a1730ac21cc2e3.nq.gz
    ├── 39762f2c7949cf22038dfa8b1fd58f81f804ce8a.nq.gz
    ├── 3986a3455a7bafb9c99d010e45d285422e841895.nq.gz
    ├── 398d2f7ca1f94eb9a84de25a99e80a6801cfd4bf.nq.gz
    ├── 3990da95f3ff718070f88f5ff8e763c91bf3ab34.nq.gz
    ├── 39971d684aae590ac1217eec9c1d32afa7bbd796.nq.gz
    ├── 39af4d45175c058e7bb0f3b77d29a825821f1926.nq.gz
    ├── 3a3e2dbf5ec85f1ea38556ca296cc4550aa296ba.nq.gz
    ├── 3a51229938d1aa45d6cdb4cb8769afeeec9442a2.nq.gz
    ├── 3ad28a86c0ac069c4e04d8ccd01c8a7f6a5f0bd1.nq.gz
    ├── 3be15313dba491f52758ebba1a2b3b70e7c06f84.nq.gz
    ├── 3c903eeb962041cbe0387bad8bf6f0aa6ed567e2.nq.gz
    ├── 3d5fb90d96592e41d29c554d433a2c31b9a7ecea.nq.gz
    ├── 3db40c73f7412fb32cb7d5b671ff2e921de48dc9.nq.gz
    ├── 3e1785c8da9752afd7f1f30a04a597acddab7038.nq.gz
    ├── 3eda29c4a6da348485efe24c2da362dee402a6a1.nq.gz
    ├── 402f876aefa79e5a6138e696fa120780712376d1.nq.gz
    ├── 408fcdee7dd26fdbd67d85b14588fd60c70c04e2.nq.gz
    ├── 419f382e9984edaa5f0b01af228c1e76a9715a45.nq.gz
    ├── 41d94cde3a7fe1be4f0120ae84bf4285531c72d0.nq.gz
    ├── 422a7a4a0cd2e03ab84ab89205d0343b80cd68f8.nq.gz
    ├── 427cf1632ebfc972229c2eab7da6f96e1ad677e8.nq.gz
    ├── 4294a1b54ef003c3e64ca2c8163e344c8003b2b0.nq.gz
    ├── 4371fc300b4045efd2d005c91113c4e37b187be8.nq.gz
    ├── 4518d490e28abe78784fa44e5d99bccf4b8ea580.nq.gz
    ├── 4523e92b0ac7a4e4cdf58060f096fee167a9c4f6.nq.gz
    ├── 4699fd112e1c2e5e8edf1e1f41dc6f3bc091c087.nq.gz
    ├── 4751b11786ce61081b537cc391508d3278f5606c.nq.gz
    ├── 47f319922636ad5dae13313d3392188298bf1586.nq.gz
    ├── 481ad035be59815e12507fc48035aef414426204.nq.gz
    ├── 488242a05ca61a84dd54825e6410240f53a79070.nq.gz
    ├── 4a15f00f46d57c144a0475f2eebb8d1f0a5f4937.nq.gz
    ├── 4a7fff80030efef3d817067adc66b884ee7f29dd.nq.gz
    ├── 4ad0c6f3212fe40c8d4672d6075b35a795efc666.nq.gz
    ├── 4b294da27771c49f01d9defb020b517e4570ebf0.nq.gz
    ├── 4b3094a3271523fa7f87205f4dbc703efa009acc.nq.gz
    ├── 4b8d8324808b7d1fabc3b40f533981c468caa2b2.nq.gz
    ├── 4bbf0c81399735b08f7c84520fad7ffceff82ccf.nq.gz
    ├── 4c9a539f509311a2667a7c0446401b0f4d853f1c.nq.gz
    ├── 4cfc7645b80ddf7384d32e804081751f0c081ede.nq.gz
    ├── 4d145df238513bff5c655ca4cca5020d0c17b141.nq.gz
    ├── 4e606517d4ee199463a2dc13ba70818fdfd093fb.nq.gz
    ├── 4e9c360288399fb90164ccf173817bc3b4075457.nq.gz
    ├── 4ffafac7ccb2320205861d442206221f439a250c.nq.gz
    ├── 5010bb6ec22c9caba5f4c70c7beb577605e0604e.nq.gz
    ├── 50508f471cd79b7684fd17cbb2bd982440704d72.nq.gz
    ├── 523ddd9d63f3cc4f72841954c521a0757a79930a.nq.gz
    ├── 525223853a12c6683d9ffc89b48df9ebcf694790.nq.gz
    ├── 5273390967fc08420affebd7b670799fdb8ce9c7.nq.gz
    ├── 546bacce2658cacd03f89d5c29134427e6947bac.nq.gz
    ├── 54b5e3b08ab21c08a35295397651a49bbfda90c2.nq.gz
    ├── 54e88c8ef003f5a428ac62ae95e856806bf08665.nq.gz
    ├── 560071e984614665367c2ca33d64be59c5bd3e2f.nq.gz
    ├── 566b49257165a35ec1486c058dd11f8ba90d77a0.nq.gz
    ├── 575e250d8a8ad0937ee15e8e21d9839525b79ab5.nq.gz
    ├── 577a0e85ae80692da73525358c5f7eb124d2ef71.nq.gz
    ├── 5958a4870be504e191e5ccf445269e36bb136a36.nq.gz
    ├── 59786ae05961a89b237f303abfa8aee0e2129a55.nq.gz
    ├── 59e25ea38ca3e79574b311ab19471a1bf6655d99.nq.gz
    ├── 5a0a8183834619d02fcafcf7fed21fe3c8b93776.nq.gz
    ├── 5a2b1457922a72bc09282fa8cc3e19fc913852df.nq.gz
    ├── 5b8d0a741d4a882b30af445745def0a255ed82d5.nq.gz
    ├── 5be8ba9f7f4ba97e8dd88e2a51c88e4ac6715d1e.nq.gz
    ├── 5c42f1dfb9a54baca7f611024b99356da060db41.nq.gz
    ├── 5c4a59fd4ab6dc248a1ff53adc7b05c17efd6093.nq.gz
    ├── 5cf34b4cba4f588be7c0dfe5841235e11ec70c16.nq.gz
    ├── 5dabee667ef2b6026f6b20708cdd4e4693c7454a.nq.gz
    ├── 5ef3d67ce5c889002229164a06ed442f98e0058f.nq.gz
    ├── 5f2eedd9dc9af5c13200029e927c24a6a5163348.nq.gz
    ├── 5f3653234f71242cf0234609472c85376375f0bf.nq.gz
    ├── 5f396bdbb1dc5ca22a727179fc2c0de933a2a286.nq.gz
    ├── 6047d5a789b294425db664c2d6fd2c3f3316cc2d.nq.gz
    ├── 610c6924bb249149ca4358ef694a2096714a79d2.nq.gz
    ├── 634b3fdfe91de3d2552c6849fcfd8eade5586a92.nq.gz
    ├── 63638be5257ba6f33a3eed89203709e0ae14dc4b.nq.gz
    ├── 63ce8242defd10e63a0e63fa1fc563462f123527.nq.gz
    ├── 63fbb1f13d1d91f6148cef1451100288dfc13c4c.nq.gz
    ├── 64bdd95f308315ef93bc998897ea89626152146e.nq.gz
    ├── 652373a7dd4c66924dac22a046f553685a4bb257.nq.gz
    ├── 662ecf0fc00eb6584c1682082fcd647902bc8a71.nq.gz
    ├── 66e26b383a26fd1a9581963398f73db3b7fc153c.nq.gz
    ├── 672da9cb8f2ddb8aa478ec14598d52089176639e.nq.gz
    ├── 6820e338fa761be0ad41a50132ec0aa8bf982534.nq.gz
    ├── 683a70c044a36e613b3519a28f45b8ef3657ec67.nq.gz
    ├── 68a7357e31423361a88e45582d4d9f4831d35328.nq.gz
    ├── 68eb6f5a02bcd161aa6722b4861e0f638ee3277e.nq.gz
    ├── 69ab31d796ad9a32560e8c6fec2f9dde535855b2.nq.gz
    ├── 6a9cd5dfb84770c6ab7a1be72aa4ac7efbb743d9.nq.gz
    ├── 6aa1b6f481cf5efbc69b0cf61ce74abe86da7c7f.nq.gz
    ├── 6ab7a64c2295ed1bc67b63b1aa75f485ecbb2ff3.nq.gz
    ├── 6b15efa79cecf7c9031d95c1ef6e84b2b48f68ec.nq.gz
    └── 6b32ad7dd0c368b5cf3aedfaeb62abada0bdfc8d.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[catalyst-team/catalyst](https://github.com/catalyst-team/catalyst)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
