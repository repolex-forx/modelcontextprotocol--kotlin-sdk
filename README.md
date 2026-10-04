# Repolex Knowledge Graph of modelcontextprotocol/kotlin-sdk

RDF knowledge graph data for [modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/kotlin-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 382e27b0ee5bfd3dad89c9fbc34fff1984e16ecd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 382e27b0ee5bfd3dad89c9fbc34fff1984e16ecd.nq.gz
│   └── repolex
│       └── 382e27b0ee5bfd3dad89c9fbc34fff1984e16ecd
│           └── chunk-001.nq.gz
└── blob
    ├── 000ac12ff3851694b85d6c571ea0a7adb4de807d.nq.gz
    ├── 001a25575d5e151c4e466c2612c34369c1546645.nq.gz
    ├── 00b443a039efe079933f2a154ef3b533fb87c4ca.nq.gz
    ├── 01eb1f7df2175fe14c172fe5c66fa1170952d872.nq.gz
    ├── 02964296fb1004f54f32c9e003820a763d7674b6.nq.gz
    ├── 03754c4c3d9206f5c9ef69e41990dfe26a05251e.nq.gz
    ├── 03ef3ef9a3ad4c89d5d95420165cd9b66b0ff1a4.nq.gz
    ├── 0591a5bbab9e1d9ea0dd2f1c38eb68ddec1108a7.nq.gz
    ├── 05ce3709862cbc556707d07c14e62ae81253a87a.nq.gz
    ├── 062e66014ab05b8615fc600ec81d8a124b56d37e.nq.gz
    ├── 074e6f962ca78ad9f365db519569df78179afc23.nq.gz
    ├── 0807c53d96ee886c3f0e89d6a7b22c76d22c3da1.nq.gz
    ├── 081434295440917b28643bf5ad662ad761371419.nq.gz
    ├── 098250073a9bb6f958cb1af6a9d3b76b81ba683f.nq.gz
    ├── 0a188c8bedb708fad65f7a64a6742d81423c41d4.nq.gz
    ├── 0c0cc78c7ad41348a7bb3db6be440d1d470f5f8d.nq.gz
    ├── 0c5fbe317c376ebbd5ecbba592cd8d20e2e0bbcf.nq.gz
    ├── 0c61e13b7805b1bd752d9d682292c5f2290996bc.nq.gz
    ├── 0c695041ee7975168f448b1c77bc62e5af59f5c9.nq.gz
    ├── 0c79bb97dc02c423ec18695af1ccd1b026504a1f.nq.gz
    ├── 0cc4143512dd1d12e280a7d1409af9e9a59a4fd2.nq.gz
    ├── 0cde506be6a7b6e2a1cdd6fd0ccfab8c6dfa1ad0.nq.gz
    ├── 0d0db42f6f66f1dd4a10a7e11d0d14dd48fdd8d6.nq.gz
    ├── 0d8b2b7c8f8bc939b8fdf7b081e3819edf4fc21b.nq.gz
    ├── 0dc3cd8e321c8b3cf7b2b2e090c43c59e6a047cf.nq.gz
    ├── 0ffe8a34b111acfad7dc860829de4346eb789f60.nq.gz
    ├── 10dbe5b885e19c181591edde3d0e5e349867ecd5.nq.gz
    ├── 12309fad7a106a272c7253308686d090340e8e9d.nq.gz
    ├── 1290cb0fac54aa3e69311a4eb97a0670b54a86a3.nq.gz
    ├── 13551379b93f29eb3a84b5ecf110170254145b6e.nq.gz
    ├── 137d05450b42a93085511e01c6940a188cfced83.nq.gz
    ├── 13bf2724bcbc56888a51af772a4cae5c4c0ff28f.nq.gz
    ├── 142d59c7723394e4ba913d43a1ede2f0a266f0bf.nq.gz
    ├── 14af5461df822752388f3f2b6076cefd5a1e94d7.nq.gz
    ├── 16141d375a3104293e64e53fc42688d0dff9cf84.nq.gz
    ├── 161edc7c7904dcc09c0c8148e4d63f6ae0a7e56d.nq.gz
    ├── 1738ac5a039464a68916f9f5448499ce02113372.nq.gz
    ├── 176a398f3639b8323e4b673c2d54927aa3537616.nq.gz
    ├── 1824ad012fda3bdf3569e527ff3f6f1d5186dd27.nq.gz
    ├── 185054bef9dfb083b7ab2db43908ffa173a0f48e.nq.gz
    ├── 1857ef1a303bb7554dbed809ac5566895ad64878.nq.gz
    ├── 1898636c8f0e8b15e33583701091233c103cbf12.nq.gz
    ├── 18f0cfe1e82ba662bcf1bbc72c76abb359bc046a.nq.gz
    ├── 191a65ea0cd992801b594f45ae32df4918f638d8.nq.gz
    ├── 198de8a3ed65e5d9c02cd5a6047b25e302ffdc32.nq.gz
    ├── 1afa0e69a3d11c8ebffd538e36ee1fe6df04b1cb.nq.gz
    ├── 1bb73e6ea2dc0162ef5eb1d5bf57e5f65610e426.nq.gz
    ├── 1c7409709d1ae7d69aad237c0e32de776262c04c.nq.gz
    ├── 1cd3e6b242bd7931c833b9bf0a746dc6cf2c2ed4.nq.gz
    ├── 1dee706f71ae4a693b9dcceccc3b9c5f862c3bea.nq.gz
    ├── 1eb53291415062ed921fff6a607745844c584194.nq.gz
    ├── 1f0f54e3c69acef90f7c1124bed72c866c5a031a.nq.gz
    ├── 1f93d1237481c50a4bded54b9d44656ae1059a64.nq.gz
    ├── 2012bec27a998926afea429eb62b0e3e71eb7f1b.nq.gz
    ├── 21e0925c341511ce51858cc0d8ef8715013d16a1.nq.gz
    ├── 2336c1337d4119758d4c066a792b8c68ffe36598.nq.gz
    ├── 23fdfcc0dc1803666378bf67a65c05f9c5126805.nq.gz
    ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
    ├── 24a59763f5b2c91b64250a782b40d364330fb6e4.nq.gz
    ├── 2683b75277afcf6ddb2d907440f2826415e17d10.nq.gz
    ├── 27013d3b2620e9022c5977c0c419506cae215387.nq.gz
    ├── 2741e5877923014c0b3deef36846153c54c4807e.nq.gz
    ├── 27856d72442579b13657ca66f8fca5876b940388.nq.gz
    ├── 279254ebb3e1995458587d719ad8a0ae87c20615.nq.gz
    ├── 27fee2f739873e2ea1a1f2d5bfa1998a8d8ee28f.nq.gz
    ├── 29d3c99837d97d68492d128d60fe88266fe5adb6.nq.gz
    ├── 2a471472dee6fed50d04fe39dde436f86c42c263.nq.gz
    ├── 2a4723c7ef947d1b9aced28cc1b25d13fb21ca0b.nq.gz
    ├── 2a85c74a55acc20051702b5a27b4817135250d69.nq.gz
    ├── 2b4aa9908bacc71d020c9818747842dc8ffe89be.nq.gz
    ├── 2bd36512d5ff1fe132f288da99d3aee4b99e9b57.nq.gz
    ├── 2c2dbe3dd148fe348fcfd63c42bb909a849cc6db.nq.gz
    ├── 2c6fed66a1eb690bc19b3baec186978392c2ceb6.nq.gz
    ├── 2d02b34d7ac857fdf5c77ec473ea6a4be2bd5bc7.nq.gz
    ├── 2d06799d19fbd5a0cbe2fdc02596f51b87981b57.nq.gz
    ├── 2d5fd288616f16dd0fe853cd78785d4a3e6e8bc2.nq.gz
    ├── 2d89df248afeb3194fdda63bccdb90695723afd8.nq.gz
    ├── 2e091ba5bc2a01ec6ec6791fc279f67c7b03b622.nq.gz
    ├── 2eac13d46e24dc2d6e705fe9635fc4bfeb024444.nq.gz
    ├── 307fce3c9e00fc6ab38816012a7a050d1f57b0f5.nq.gz
    ├── 31274995e843027260095831c9ceceed8e536e90.nq.gz
    ├── 32cead691631427b9e2eab6c97d73636eb33ad11.nq.gz
    ├── 32f55c9caa5a96e04f5e99065c98bb359da4253e.nq.gz
    ├── 32fd550e776a162c8f6ebfabc8cc37331f4a65de.nq.gz
    ├── 33202147bb49ae3165a9ca6b8278c3a11ba0f6bf.nq.gz
    ├── 33b69ceb009379c699f02cf36148b649da843022.nq.gz
    ├── 3484453b433a4c8f912dbbc09f0b3ec2bd247f4e.nq.gz
    ├── 35a1e9802634c808db0e843e541671d72646ab41.nq.gz
    ├── 36b7e372dc701d97a624d5c98239f18879336843.nq.gz
    ├── 37a57b76c10baa078698048642c33a76132ce98b.nq.gz
    ├── 3c1419e849eb62f99614f943763b948f40fca554.nq.gz
    ├── 3c36808b91bb9c833824a7faa3571b340d6c8ba8.nq.gz
    ├── 3c5e3ede1dfede0a6f43929762f1d7ed2ca7d012.nq.gz
    ├── 3d225cddb966c640b42bf61b0fe32d42cf021e6d.nq.gz
    ├── 3d33c213243aff65f883c0d085560b2e031e6ef0.nq.gz
    ├── 3dcc9d811376276f2614a1c027a61989edd14a79.nq.gz
    ├── 3ded6a3bfa836c63d35cf9dd0283ee75f48a57e9.nq.gz
    ├── 3e2a15041a05f28d5c287aac4569c6ef0a090e61.nq.gz
    ├── 40aa51743389c25f771236f358d9b35512903a43.nq.gz
    ├── 40b401395c9cd10b0fecf389411a0e0738291c18.nq.gz
    ├── 41f2b03791fa482b9fdc32a71324f13a72628dca.nq.gz
    ├── 42093c8b6988f93aaa917177f029cfc674c0bec4.nq.gz
    ├── 42c2b8fb6992eaaca2d8ff515565f8bfd86be704.nq.gz
    ├── 452333b86acd9a2141852f2073c9a28b97ce3592.nq.gz
    ├── 470ae23de5d7d1ca6dc8edf9404e0644bc8dd459.nq.gz
    ├── 4752ff50b6fb54ee0a89ebdad5e873f238be8dc9.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4908da5802846fb91ccbc84e5646624ae9396a15.nq.gz
    ├── 492ec42b71ca38f4ab3fa14bf3b07ade4747ff23.nq.gz
    ├── 494d66c0c7d25dc1245edc9636a2d3c2eec30b95.nq.gz
    ├── 4964f20d280b58c9e2cba3c16173f9012abcca18.nq.gz
    ├── 4a057cefa0a15dd5934caa0a8fe20c27aac71755.nq.gz
    ├── 4a942a4f024be3d57f1b598220af0085fde0dd29.nq.gz
    ├── 4afb1f4ab37e7656297aa9f78cab73636df0419e.nq.gz
    ├── 4bc75a0e3fc5224070e9e4632139d41a1b8ae6c1.nq.gz
    ├── 4cb7a6c8bcee9e17a02e1aecddd8aeaef1d72231.nq.gz
    ├── 4daab4651572621c7543302775a212b432084b64.nq.gz
    ├── 4e5673b20f28346e79cae67af15f2a7e6c76e265.nq.gz
    ├── 4e6fd6303985024adabedfbdaff9cdd1963781b3.nq.gz
    ├── 4f14d0321adcb21831c19afb4d95b46a40d047e9.nq.gz
    ├── 4f8fc2b03935747e0c8658733e9613e4a2f028ff.nq.gz
    ├── 4f9dff6a0839e6336794f9fa34954a104b5fbf22.nq.gz
    ├── 4fb46dc304b16c612cc47fad7413fa4708bc3a4b.nq.gz
    ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
    ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
    ├── 539ced4379b0aa49a545bc406ccf4237b571ac03.nq.gz
    ├── 549028881aa0f5897691698c9990f0d0fd6211cf.nq.gz
    ├── 54a095301c6a1851b85c948f645c8710fa3998eb.nq.gz
    ├── 559a770d1446d5c707a79bb1986554c24f450f13.nq.gz
    ├── 5679351a9612ad6ac9920598941c059fc24ed45d.nq.gz
    ├── 56a9045f2b2cfed59b8835cf2f96f32606cfad87.nq.gz
    ├── 5714602673f825deda0fc3b82d9339773ebf4882.nq.gz
    ├── 57980d38d7d4949e755a1fa0dae9e499ee1440a5.nq.gz
    ├── 57a803541b413c57bb50cc29097676aa7f9c993e.nq.gz
    ├── 58ccf5c4593b43cb1c855a3062abea07d2ac3f98.nq.gz
    ├── 58e3c678030f16e3e1c1a5b1d170fa8c5d6973cd.nq.gz
    ├── 5b09b425611864027ecf468a0f6cc02d41e9f34e.nq.gz
    ├── 5d7054b7350bbf77a0a3489e1591ab297d35df37.nq.gz
    ├── 5dc44ba28895e3ca4f1b40d27013556e72277ba2.nq.gz
    ├── 5fde250e5f856c509f287e7a83e8300dacb516fe.nq.gz
    ├── 60a9d3b12471354dc8213f2455e1ebf9ff94463f.nq.gz
    ├── 60e3d1cd3f10af115b57ce3240e5025a2aa5f866.nq.gz
    ├── 61774cb6b6a99470636fe3ce41dc9aad0d29c67a.nq.gz
    ├── 623fdfc95b3168f275147a4c4e3e67b83b7baf6a.nq.gz
    ├── 62971394965d8e9df48bc9ec59f3fe2546cead0b.nq.gz
    ├── 63448b02c9c0fe2caaea94038187c8af0714d42b.nq.gz
    ├── 636fe1fb616c5a050509977cc53076459e1f7c70.nq.gz
    ├── 63adaa1eca2b53e1e349b7b80e2fd8a317ca2d9c.nq.gz
    ├── 65f4429f6b006071a4a85dc88649d98b69c56abe.nq.gz
    ├── 6628455c0ad8b782110a340a6cdab4d29b06a215.nq.gz
    ├── 67770a7473f79df33c3ec1386037be85af2f57ac.nq.gz
    ├── 67d9a9fe79463937597742f15b0e12f694fb1dc1.nq.gz
    ├── 68254266a516cce9ed33d641f3f3e68e57958991.nq.gz
    ├── 6a3a9c257bdc371d5fc56649816b7a51e2dc810c.nq.gz
    ├── 6a9015bdaf6284f5ba89205bbe462184e0f096b9.nq.gz
    ├── 6b093a4aceca63bfea6a73fa350fce66958cd042.nq.gz
    ├── 6b5f9ab8988c8b1e5172806d068dcc7b02891df1.nq.gz
    ├── 6c591e4fd31b1cfecb6fe9be495595ca98d65a46.nq.gz
    ├── 6c691120b3eade13ef0f936794c5dadba4cc2816.nq.gz
    ├── 6df352abe47e9c7adbdd8039f1c06db14432ac68.nq.gz
    ├── 6df606dba3917ab210181d2a28ccb06cc794b235.nq.gz
    ├── 6f7711fa228d5813c5e4e2e26328df8c618a7c74.nq.gz
    ├── 705ee7c81f30e691bd2c65d98ec5613259faeea7.nq.gz
    ├── 71932c39896bb1580c7f9f80eea3d6d1287facc6.nq.gz
    ├── 730507b53caa55f1b2e48ed0d4075378b101d920.nq.gz
    ├── 7363561ae68d4eae15f2e4c70fe75d2d99cd446b.nq.gz
    ├── 73979db5f125d8124823c6b245c8678a6577e0d4.nq.gz
    ├── 73ab612c47647172ae5a12454baf961ba82be183.nq.gz
    ├── 73b6bb2a919770196a43a24ca8aeed13cb68e293.nq.gz
    ├── 7401e0ba71beb126246a0562633e41ba4511583f.nq.gz
    ├── 7463a9ef4a63d13c9a4d89cedb9d4d35a43e0284.nq.gz
    ├── 75d435800bb9b2cae02d57e2dd2f8f901f2ee01e.nq.gz
    ├── 7ad4931340c052817839402d431b052643a531ef.nq.gz
    ├── 7ad7bce9f51956e5fb35af05dc0ae66c2a66e410.nq.gz
    ├── 7b54e1d2ddb55c1fea777837b8ac767c27682272.nq.gz
    ├── 7b969057bf06b935311f4376f6b43df329b2e1e7.nq.gz
    ├── 7ba8de12ed67a649677f0c3d48c5f28f89646cdc.nq.gz
    ├── 7c929e787f7aa98b8c493999fc911f2d36446024.nq.gz
    ├── 7cc26851fbb583e94b62de19541d95d6b7de17fe.nq.gz
    ├── 7d2f59520826687d14db1d8c8ed3efd010cf757c.nq.gz
    ├── 7d885fb30aa351bc0e67fbffa506302f7cf2beed.nq.gz
    ├── 7e10420ae722e62f210937584f55ed4adb7951e3.nq.gz
    ├── 7e10904a910560dc9b356f4560e12c024f53255a.nq.gz
    ├── 7ee4f9e54ee659f50180605d29c0fc954f3fea64.nq.gz
    ├── 7f13d01b3b029d062a80df3c154d4f00d22602f6.nq.gz
    ├── 805579c50cd108b579bd1dad840c18c4046812f1.nq.gz
    ├── 8102cf60f21efa36d0410885301208196772f19e.nq.gz
    ├── 8138e52fe1b7b8b9e37b8fb32b6d0431979be9f2.nq.gz
    ├── 815e5f631e533c69560e318edcedfdca968f2d17.nq.gz
    ├── 82086480089b88ec44f1974ddf8d875375d4c6f5.nq.gz
    ├── 824317133c0324122f406ddb77760b5ea87040d4.nq.gz
    ├── 8280404df29ea5274615b96facada0694f8f66f1.nq.gz
    ├── 82dc5e73eb0fd61b5026b8bd3cfd689ffbbde78f.nq.gz
    ├── 8718dec48d8748947229d62ffd43f58be44afe09.nq.gz
    ├── 8843d208ff7412edf74fb6ada20bd6c000696049.nq.gz
    ├── 886f3f76f09c25c8dada7e1e746346bbbf7364c6.nq.gz
    └── 88c465d75575046a16c23e84f90ea7a68fbeedd4.nq.gz

8 directories, 200 files
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

[modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk)

---
*Parsed on 2026-10-04 by [repolex](https://repolex.ai)*
