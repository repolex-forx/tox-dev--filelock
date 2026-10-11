# Repolex Knowledge Graph of tox-dev/filelock

RDF knowledge graph data for [tox-dev/filelock](https://github.com/tox-dev/filelock), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/filelock
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4c6f32f2797b2883bbcb0cca1ee81211d3e09c12
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4c6f32f2797b2883bbcb0cca1ee81211d3e09c12
│           └── chunk-001.nq.gz
├── blob
│   ├── 05b77c8ab92babec6be0fafc1f5c05320aae42ec.nq.gz
│   ├── 05d2a5764330dd43275c3f2e733b398f4fa049c6.nq.gz
│   ├── 05d2da29b395dc0a99cee80cfa0610be8af7aabb.nq.gz
│   ├── 0833956690e5b7f33b71deea8eff4cd3146adea0.nq.gz
│   ├── 089179e12dcd5b54c4996adb7bb2411440a43fa4.nq.gz
│   ├── 0a4dfadf28343a42b1117eed9d31ed2f139b9d68.nq.gz
│   ├── 0a5f451d086f575e37675a23e57a2912abe83bbd.nq.gz
│   ├── 0d28b80b9a9d2a07af2f6a329a19873b148ee61a.nq.gz
│   ├── 0eee137b07170b6dd7f0c80896e81565c5d31588.nq.gz
│   ├── 1318a6de70042f70c3a74d13ce95e0f8746e4856.nq.gz
│   ├── 153b6c5826bd56880d8f7907114eb42a1c4aa0b8.nq.gz
│   ├── 1866ff99bb58c9cd67a46462e2fb73a6e4439450.nq.gz
│   ├── 18f9b67df3b64868bc6928ccf857c056655c3ccd.nq.gz
│   ├── 1e095373b5336101947c181a69dc1c6492d65db2.nq.gz
│   ├── 1fde97a79178a65b3a8219a04127eb537c775716.nq.gz
│   ├── 1fe0165a5e2765576e9bba1f3d14b22d069a295d.nq.gz
│   ├── 27cc98248f1014c2ae92e32fafd218eab9cf49ba.nq.gz
│   ├── 291919c0b6f41d014767f6c877af9f7595fcff99.nq.gz
│   ├── 2a8bb8ebe87a9ea84b820aecfe038ea64f9a14df.nq.gz
│   ├── 2b2a38e34f79e15a8bed26ee1da29e02e7233ff1.nq.gz
│   ├── 32feec59802c4731757f779d669c777956febfe5.nq.gz
│   ├── 36af37c124b611f3e6e3bcb6c3c626b2f9a369fa.nq.gz
│   ├── 37e472cad0c07b63dddf31014a9f07622404d446.nq.gz
│   ├── 397f9a5767b7d0b8272a9be6c1c4db7a43a05d08.nq.gz
│   ├── 3aa2b314842eb6928ee1ff03baa9e7215ead2b75.nq.gz
│   ├── 3d4c5ae476b8ab831f4585f4b534c57d1fc8467e.nq.gz
│   ├── 3ebca2153080f436a3f587adccdfdfc5c2cb88fb.nq.gz
│   ├── 404abe990e72cf1802f3322114fb2ed19d438c33.nq.gz
│   ├── 40ef7a39bb2e58411380e673e281fbeaa7fa9613.nq.gz
│   ├── 41b734f813ad93d66509b4dcee734a989948d928.nq.gz
│   ├── 44909c82cda9043c75516e6a1a8192b697df1aa4.nq.gz
│   ├── 44f072dd5a02e6f78a29cafd793b0bca1d9c9018.nq.gz
│   ├── 490dd037ea225acd111a4826ba64acc90db9c671.nq.gz
│   ├── 4a564de294040984862ba4bdcda0408398086b4e.nq.gz
│   ├── 4f5168ce545d36fa4fcde69f6c69251f6d04fbe7.nq.gz
│   ├── 506980c2cda0ab1d2f97ef560247366f8c4014f9.nq.gz
│   ├── 5102b02243604816a42e9e7ee7a791c1ed203276.nq.gz
│   ├── 535215db08c44451edf410cddc408fe6e3aed213.nq.gz
│   ├── 57533b8adaf100cecd7dca8021181e275ad751b4.nq.gz
│   ├── 5806cd1d61cbe0e8c126bc32d66c5da862cbc7bb.nq.gz
│   ├── 599ba7e0c4812635ad46bc8021f64b9751eaa1f8.nq.gz
│   ├── 5d813e43fcb67e60322590884a301540a864b785.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6163c5eeba75e141b6c7296505b402bddb612533.nq.gz
│   ├── 61a2fcb2cb78e5187d869754caa3b446d8bb2b92.nq.gz
│   ├── 61b7d999d356c242d7c83805c0fe3e6181e618e3.nq.gz
│   ├── 61d122e4a8fe33d182211ec52a9f86b5583067f1.nq.gz
│   ├── 6252fb73e3362d2e8a5edf4e1afa4b6bd927ed06.nq.gz
│   ├── 6770be6154ca9942b2bf96ff0fd0b91e09b8a574.nq.gz
│   ├── 69d0cfd202c019ca1d5a92d59faf9a1380c61930.nq.gz
│   ├── 6b101d30688cd0530cc1db88a9ba8de565940015.nq.gz
│   ├── 6f4495fa297b1e8ed8f5c4bd70212794fbcd84b1.nq.gz
│   ├── 702aaf1210e4c2fbced328d1584d19c34ff1cdd9.nq.gz
│   ├── 71bdf87e66d3ad9fb8a26758fcc873fc77cbc4dc.nq.gz
│   ├── 71e3691ab18765f5e1e37fa4c0fe39d6a7297d4f.nq.gz
│   ├── 73ba30054569a59e7ac3b43bf1037bf21dc0bfb8.nq.gz
│   ├── 74899161983f9b543b8bbd0fdad06456c3ac5c57.nq.gz
│   ├── 76a1f882f13f7b8f4c4bde65a4d22b9e4a56ec9d.nq.gz
│   ├── 790ce0bcddf4ecc540b59905a689d05c61756897.nq.gz
│   ├── 84f75c677ff34eae0517277c88167b0ef0db1642.nq.gz
│   ├── 8c0458370fc8133226f53bf129af4244f36b1bf4.nq.gz
│   ├── 8d4482f558c5b3111aba8dd081fdf7035a0f3d95.nq.gz
│   ├── 902a32bbea9913fe8efd938aab0bcb7433e96b1f.nq.gz
│   ├── 943e47c978997111a1c5990b71ee560f66fecfd1.nq.gz
│   ├── 9468440f398fbc4495fbe65d1d008f6ef4627d80.nq.gz
│   ├── 9599b1e28fe6ba35e9d3cc610d6e41aaecba9dae.nq.gz
│   ├── 988f1fe0252f6c6c2133abf38cab5e609d157b5c.nq.gz
│   ├── 9c9159de8e617b3d2b35d10006382e37b4964ce9.nq.gz
│   ├── 9cf4f9c55419ebeaa496e7d79c56106a5f61a043.nq.gz
│   ├── 9d17f56fd0f3f477e74a5802e00b87bdfdc4a211.nq.gz
│   ├── 9d4b986df7ff1c7b43c41c985f439c01a9ce6d99.nq.gz
│   ├── 9dc63d51ab3954e64830de83db4805fa8953b696.nq.gz
│   ├── a321eff58c6094bd4819cfe1d267525e960b1066.nq.gz
│   ├── a3805c5a3c31474e4862eef379868f041560c98c.nq.gz
│   ├── a6350e6fa2bb6ca829d096c4131983a084e7b062.nq.gz
│   ├── a96a19419501e424c0cfd07b037223cebf45a0e0.nq.gz
│   ├── ab91b0b98a59e28077a959d3e1beb6cbcb6e695d.nq.gz
│   ├── ac420441e3ca04cb02f6284cb74944853591d1e7.nq.gz
│   ├── acd548c7285c40b8c5b7b232dc29e8baefec4b0a.nq.gz
│   ├── b34643e3e50be1a275d028d594bac9492d92bf0a.nq.gz
│   ├── b44fb6b17a0fa753888cb9da7f2853d35951cba5.nq.gz
│   ├── b454e2e2906834df9cef24818e2f790d08fbe8c0.nq.gz
│   ├── b4dead42933d10990fedf7f911d191556a30192f.nq.gz
│   ├── b65c7755ad3177f12f74da50f351bf3e5e83ae99.nq.gz
│   ├── b9a5aa4c0e2c6278aa8a7324360812ca9116c5ec.nq.gz
│   ├── b9e32d7bffbe65aa46c5e54d9b241808301d9ee0.nq.gz
│   ├── ba2b1a6b05bd376b42d4705e5aca9fda46dcf236.nq.gz
│   ├── be6ed6c9d33b5e65c14dc7d26b9a9fadba1e1447.nq.gz
│   ├── c0e17aca1e562cb94f928a6897515a455c71e7d3.nq.gz
│   ├── c1fa0f907fd069de7c9c4dd8374e3696a8514498.nq.gz
│   ├── c27926b93a45766c7d97f3f1dd3f12169223dcf1.nq.gz
│   ├── c93bd221b2e819e7bda9723969200d078662b839.nq.gz
│   ├── c9482d41575c181f5b6b2f2aa1c30663cc3e9baf.nq.gz
│   ├── ccf8a237b650bcae75641418fcf901a87068ab7a.nq.gz
│   ├── cda928e26f7a2f1e4c2d330d559ccdd08adaa49d.nq.gz
│   ├── cf48a5d4520d0a6043d2f863f7ef7175b499e99d.nq.gz
│   ├── cfa864f4fa4326427afe9613da80a4cd5f411fc4.nq.gz
│   ├── d072d2571ce3e08d370e14ad660ccce3d2f8bc50.nq.gz
│   ├── d24bd347d51e5e83d5f0e3dfa2c6011e12b21453.nq.gz
│   ├── d2cbf377c95b67d9edd94aef10954100a0ea8da2.nq.gz
│   ├── d39d90ba579ec84ee6714e7720042cb36460a0da.nq.gz
│   ├── d7f623ca06c8c4afb5979f9a1035f28156e7eb09.nq.gz
│   ├── db2ef82d4a4fae9a59d6991dd0b671786353618e.nq.gz
│   ├── dc8ca78b5fd45a7eacfd1af5c584532c735e37cd.nq.gz
│   ├── e380d031cf1ec8072cc7fe2a8b930ffe81d26172.nq.gz
│   ├── e389313fbad2fe42f9f1c138b8f9edf7abf758b7.nq.gz
│   ├── e622acb26d366172562c2a488a03bf5d5639d6ef.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7cbd0cd600da6fb42ba626c4ea2f695b3fbc659.nq.gz
│   ├── ec1bddea8c352c8f5de0b81da63a10a6424a198e.nq.gz
│   ├── f107d568e585879c6359e42e600fcceee808d40f.nq.gz
│   ├── f1ce879b6024167959e7c667ed0987be186e1f16.nq.gz
│   ├── f3f02edef2e266afed338e7f2d23da24f49039e9.nq.gz
│   ├── f55bbb25e7171e52fdcca2e1a96424b7a076cee5.nq.gz
│   └── f831ee6bb9053d9471133b6e86197b36f5962a98.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4c6f32f2797b2883bbcb0cca1ee81211d3e09c12.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[tox-dev/filelock](https://github.com/tox-dev/filelock)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
