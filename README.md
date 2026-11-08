# Repolex Knowledge Graph of canonical/kafka-operator

RDF knowledge graph data for [canonical/kafka-operator](https://github.com/canonical/kafka-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/kafka-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6f1d8af2642834150509d9cf88998936a82b9d4c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6f1d8af2642834150509d9cf88998936a82b9d4c
│           └── chunk-001.nq.gz
└── blob
    ├── 00c4d028572e13181642876cff50b472be0c0328.nq.gz
    ├── 01193acb47a5ef48190f1826e582d371c30e751d.nq.gz
    ├── 020438eff37ea6663a1a5d026b716876c8c15578.nq.gz
    ├── 02c0b3979c13f5adc595a9e32342bfa236f00b4e.nq.gz
    ├── 047450cc697e03f17c9646b95e67e5df291e1bca.nq.gz
    ├── 049409625db82c127c16adea80d42391312bed58.nq.gz
    ├── 05fd7f4476a8406e59595ceefa4f06442eb0b22d.nq.gz
    ├── 07147d636129b3048545ff09371cf03e718cebca.nq.gz
    ├── 07e0b48cbd1569fbf0e610fa77b6a4e96330574f.nq.gz
    ├── 08723b9e43cb5147d9ad8a0ace21ff1d6d7ddc26.nq.gz
    ├── 08a9c332d39e9097e6a31b9b7bb9a4b409a56372.nq.gz
    ├── 0961bc30035925eeea6fbe7e0003722a5f7f0904.nq.gz
    ├── 096918629019ad243714dfecf2af3fcc483d7600.nq.gz
    ├── 09f323c39636a7ab51f4cb52e133ae7a9dec0d78.nq.gz
    ├── 09f357f7c0c7504618dd63110589728baee92647.nq.gz
    ├── 0a2f68f805582a9dcbd33500933cfe5ba34a6c79.nq.gz
    ├── 0ac9bfba1a33c4b41d128f2b5505cc8dd45fd20f.nq.gz
    ├── 0b680d508757e960bfc1e7190cc29509514d1562.nq.gz
    ├── 0c2958d2cd1a885f2590ac56995bb792eb0d753d.nq.gz
    ├── 0c62237ef77a57ef0f87cfafef786ca6231144e2.nq.gz
    ├── 0d156cd4c7996abbb4c946b940379e60abfdb506.nq.gz
    ├── 0d2d1d100c8dc49c232cc59fb26cf713f763a330.nq.gz
    ├── 0d4d13827aa8c2e59070707fa8f8ca232b753be9.nq.gz
    ├── 11aa4096eb508eb10d425682a622fe8c7a8d0590.nq.gz
    ├── 12beb3220ea2cc1cb2dec067133896f26e61ad10.nq.gz
    ├── 13b51a3051b95ac5d9218b2da5db4d67fb77bf9d.nq.gz
    ├── 145ced76791d476d14d0069107d875e2db338061.nq.gz
    ├── 151abab736aabbeb2eaf87b1d679f32fb0ba2905.nq.gz
    ├── 16b0159f577591d02713fbd0a7585f4c8adf1a42.nq.gz
    ├── 16b04e36caa5d361055a367df4aa1a75ee2aabb3.nq.gz
    ├── 16b40a0548fdd5a6cbaf0ab71e702a0474564594.nq.gz
    ├── 17194509fb030d20e6e42396fc64e35ac2988b5c.nq.gz
    ├── 171eda905f085723e23be04cd6875704632cba7e.nq.gz
    ├── 189fb2b15d0a54fc0723b12806d781e66a5325cd.nq.gz
    ├── 18de6f1a047ceb174f2ef0226d996506f41ad9bc.nq.gz
    ├── 19698e524c6b0029cd4b74894df801dacb42b087.nq.gz
    ├── 19dd576cd7242b9496cff11c368fa44b0f24df2f.nq.gz
    ├── 19e43e7b666ea4bd7dd33fe9b365e379c2104d32.nq.gz
    ├── 1a3f3789c10ae63a6114401f1167395efd25a3f6.nq.gz
    ├── 1ae12641bd20d9c123500cb81859c1ffa5195a10.nq.gz
    ├── 1c603088e1073d3ddc4ce5f2cf5e7864188d1020.nq.gz
    ├── 1c6e9c1678336edc3c5d0af73e0bb31a14be8adc.nq.gz
    ├── 1c788aa40f9814332ee620c18cb9ed93e84fceae.nq.gz
    ├── 1cea2539868de6d183ec3e3246d94846dc15ed08.nq.gz
    ├── 1dbfb42d9077691d1480e37cb2b5d3e64eb2546a.nq.gz
    ├── 1de05338f779e4044f4e2e6aa0e725b48493b6bb.nq.gz
    ├── 1e806832cf9b166b829018addb975439474ff43a.nq.gz
    ├── 1e8182153c71813a530ddb3049a650a45a85170e.nq.gz
    ├── 1ede2fe0518a15478d5fe347c587ed58b2a373db.nq.gz
    ├── 20c40ae094b71625ae5a1c16a5f2989943f649ec.nq.gz
    ├── 22df105f8dac1f1e48217b7983f5e6e33bfec7da.nq.gz
    ├── 23770e2b5d4fd533842e4eb7664b955a1c640fca.nq.gz
    ├── 249316c88a06759b5c6accfec45f7028cf57f046.nq.gz
    ├── 24d0900785305d29617676d330cd998184a4e53d.nq.gz
    ├── 251a19d061f694a4959b0d91a24c048088f89ff8.nq.gz
    ├── 2530ef0a40ec6edae4118568cdf4cec1842e58fd.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26af2183d1845550f715e35b1cfd3999a3bf88dc.nq.gz
    ├── 26fb30511632092cc350532d6d6ec66af6352956.nq.gz
    ├── 270208d7a2bbdc1649ac7b5c62137f7c5d8b9934.nq.gz
    ├── 282ea85c636943dcd1eac98614889a56298013b0.nq.gz
    ├── 283f56642a160cb8f671542eff3cf1034764ac78.nq.gz
    ├── 28950e67b2c2807d8e35259f04a534de992bf154.nq.gz
    ├── 289f008c63c162b66e70e8ef37e9c2ddb65d6aa3.nq.gz
    ├── 29e02fb8e154c09d4994bc3ff6cc1c924188f1e0.nq.gz
    ├── 29e1fa3e44a773c8bb874ff5fe94ec81a39f619c.nq.gz
    ├── 29ede242ff455a64fa253000d80487a0bb723248.nq.gz
    ├── 2ab295677dd8aeb34a2bfaa2eed78ae400e6aeb9.nq.gz
    ├── 2bb8941c91796075462b20545b71db59a2639400.nq.gz
    ├── 2c2834b573b99eede94152b22a8c8f3b81c67a88.nq.gz
    ├── 2e3df4fbf4a38173e9f519a8e4ff6d882ae0c6db.nq.gz
    ├── 2ede4c2d5b6218437ef9be3786acae00ecdb1616.nq.gz
    ├── 2f53f75720acf1633db86e66c0129b362a6528aa.nq.gz
    ├── 2fd79e31559b76563769d46ca30d442070b2a1f3.nq.gz
    ├── 3014a84f49e5da629a320e61b44bb11e73fea385.nq.gz
    ├── 304d1ec90b7db49ab50ec37c240c306cec6376d6.nq.gz
    ├── 307b5f2ec4afd37039c61500decced8f538bc94d.nq.gz
    ├── 3089aeaa2a6cd198a966eaa9809df5eade9010d2.nq.gz
    ├── 309ee12fd2c113853b8b270761c68193c3c8978c.nq.gz
    ├── 30f8c77968c19187fd8f9b2ea923298b7d89840a.nq.gz
    ├── 32a089c2e9772ed875bba28490826f98a74b0200.nq.gz
    ├── 32dfe56f0f6c9f8ee13d9d385bbdb7fea13ada21.nq.gz
    ├── 33c6dd8e29d0eafc7040b7377c1baea36dd2a2e7.nq.gz
    ├── 33eca966b785f7d73ee42b6b126bd23aa7d2b840.nq.gz
    ├── 358c08de4501a9874b06a6fca97a65aa0296ccda.nq.gz
    ├── 35d25fd0e0e0e8e2f793e0581e5c575df9cd7ebf.nq.gz
    ├── 35f8b25ab0fb504288544a7c3d2d21420ecf6765.nq.gz
    ├── 365fa5ebc465c95fff12f84f2f4c4104e5fc196a.nq.gz
    ├── 375c690dd606784ab7180208315a9044ba236597.nq.gz
    ├── 39630a820434484b82e049b2827f186239b83021.nq.gz
    ├── 39eb09748690dccc32ec2cd36191418f8155c315.nq.gz
    ├── 3a3a3e50241168988e1fbac85a1fc1a91889f122.nq.gz
    ├── 3c702d2aee087bf6f9add8b8779e62ec8de9d71e.nq.gz
    ├── 3c752d4cf7b8d03ae205c62b874225b755d95e03.nq.gz
    ├── 3e00cbfd93373816c6b71a5e4557c19c864cedab.nq.gz
    ├── 3f65b687a7eaebc0d94839e226ffc5524251c58b.nq.gz
    ├── 4039fc210b0c9ebe72a13f57eed4c03d46afa5c9.nq.gz
    ├── 410e4efe4641527065f5603a9e8e8a63cae9532a.nq.gz
    ├── 414e63f19b3f4b6d22c3d1f5b0e7966a6eb36a9f.nq.gz
    ├── 417077b72fe5b7327a0a2f2e30eec0769a57b59f.nq.gz
    ├── 421cff47346e0d21dc0386c7706744718e5ae619.nq.gz
    ├── 430e3edfabc5d4bf750ff7ad3495befd36346af6.nq.gz
    ├── 4394e763b19e88dd47caba798f1eb002817b4a74.nq.gz
    ├── 43ba4092ece109699ae9ac4d1a3406bc7ce46b2d.nq.gz
    ├── 44adda71b5702e116dfc5be455b7ecaec03ff41e.nq.gz
    ├── 44db1d8d9ecccfe41a0dc686a1e7067c6b93321e.nq.gz
    ├── 44edfbc12f018054758aa8e00fb71146b865a7c6.nq.gz
    ├── 45f2092f8deaee934ff7028f6a8e6e4664612747.nq.gz
    ├── 4937b95be8d497d72c12f4b83517207f189ad972.nq.gz
    ├── 4b05f5d47b9b656d9370779331a66d6d3c860466.nq.gz
    ├── 4d0ef61a732ccc499486ec30acaaba858a8d951b.nq.gz
    ├── 4ddabe3c60ec8e2bbe3b2c140c20b9aba2f56b44.nq.gz
    ├── 4e4e9964f5ec377150ef51ddb2035cf59e6d5b98.nq.gz
    ├── 4ef74d364df35c62f9f8a93a446f673d97d87bdd.nq.gz
    ├── 50192618bf090874a626a2bd3a8784ee6a2500c5.nq.gz
    ├── 5055a7d1729bac0ecd97fe927c24c617b71bc74c.nq.gz
    ├── 50644c4403dbebfcc218e22350234a2e773c30a5.nq.gz
    ├── 50699127fd92057536dfebc6ccd1c4edc1d2addb.nq.gz
    ├── 50f408d2962674bfc66df5d35b5b88dbab8dc093.nq.gz
    ├── 51831b4ace6f5ef19d1e8c39f72aaa7054114446.nq.gz
    ├── 536277de82ed4cdc7306112348641427ab1c7c79.nq.gz
    ├── 549637fd5838eae766274d76fe794cd41cdf5e94.nq.gz
    ├── 54a343367d16b2027c9ede84825a11cd0c2dec62.nq.gz
    ├── 54c94e5e2871070184c74f7fdd0007ac753dd289.nq.gz
    ├── 55017db782ca804627a2a9071b5258a6a0f68b96.nq.gz
    ├── 5541c67e6bf5f6e81bcddc6cc6b0bcc42253777b.nq.gz
    ├── 557e39a22adfe5f03c6d9faf2f8353b206acc29a.nq.gz
    ├── 56b4eb920fa0819e4b0d3b762d31589681e545da.nq.gz
    ├── 56ecf7cd97ef751babbdb864cfad78326993e0a8.nq.gz
    ├── 57a263e88b6491d3c55d1e151b75f45a10a418ee.nq.gz
    ├── 5950764e0555df5608ebc71157507ebb9824ff3a.nq.gz
    ├── 5a15145e4d56fcb861307fa205960a5e6f185908.nq.gz
    ├── 5a5d857a9712db060a9c00367e78be83abb5c78f.nq.gz
    ├── 5a7d4ce306013bc7742622b347b7da5cafe7351f.nq.gz
    ├── 5cc97eefac557a78853c050bd889aebbf32d692f.nq.gz
    ├── 5cd0ffd4b26fd51a7638ab84829f17f52033523f.nq.gz
    ├── 5d06ef1ceab0c0a2b87900422e90f4d61596b944.nq.gz
    ├── 5da67d1ad0e9ed820e148f1fd877ee2995ab3e22.nq.gz
    ├── 5e572622bd3ea82a79f641f5325a40f967effe1d.nq.gz
    ├── 5f32dc1b205ec1039b1b20dc83869022e49164c1.nq.gz
    ├── 60287bae16c381380599023d19be9ea5f3cfcc4f.nq.gz
    ├── 61cbb070fccabedcc52c8caeb6668060da2f53bd.nq.gz
    ├── 62bcb72a5d2f9fd7cdd33fd75271fc65b976038b.nq.gz
    ├── 62cc00962dad5dc2353efb948fee3e0bf990caf0.nq.gz
    ├── 661e328cea60aaacf8fa7d8c26ea0d0cd96c7f40.nq.gz
    ├── 663fafd7d6d2edccf56c1692493a060bf28a0ce6.nq.gz
    ├── 672494498d69cec7ef9d2e2bce49bd6b72766f47.nq.gz
    ├── 67c1a4c9f32fdcc19e8eb0e82a1557298a14db9b.nq.gz
    ├── 67cfae19e418dea7ac0f3411ffb9422f9219cf7e.nq.gz
    ├── 680d1679b49b0bf15ec534451522607845a294b1.nq.gz
    ├── 6b3f759f8ca4029535dbc0e20e417de72322339a.nq.gz
    ├── 6b610ce112aae3fa53cccade3e6935c026db69d2.nq.gz
    ├── 6bb6de10908c89bfe3204b633da2fdf9e1ff715c.nq.gz
    ├── 6bd8f091c8fa5fedf6c7ac2991fe51b3f706c595.nq.gz
    ├── 6c00ab4f861f5505d15c0f635bc68900ea5aa0e1.nq.gz
    ├── 6c5caadf0471e02d092368935b00d18d54155623.nq.gz
    ├── 6cd1e52707b845a1e008d1709bf0ec4003d7442d.nq.gz
    ├── 6cde15e4d0185f88bca6238376e0b70b64a6a16b.nq.gz
    ├── 6d381d376108dcadb095add17e6434eb9421e3a5.nq.gz
    ├── 6da135aec058191f7f2800ffaaddc2f6a62dd7ab.nq.gz
    ├── 6e65aabbf7cf68bb1385ee398474dc3081b45cc5.nq.gz
    ├── 702521d98c0662361340d9fe8eaf2c0f85478573.nq.gz
    ├── 7079243d613e1c60b22f8e0fc45d0c1295414a42.nq.gz
    ├── 70ac3edc754d2d419c83245a0c8af6c0a77fd1f3.nq.gz
    ├── 71cdee39cb58230c14bacdb21bf6350afef65785.nq.gz
    ├── 71e44ce0a02fdd11386a8b77c8f1980ba09d2fbb.nq.gz
    ├── 72b23a84959c38cbc6d30b92cbe16823baf91b68.nq.gz
    ├── 73b5401cb4667e8776298fe7e054c5f6419346b3.nq.gz
    ├── 742eb594ed18b962f116e38d81c744916f3daf70.nq.gz
    ├── 745f996788f12c00c6836eae6e75bbaf09a49f7b.nq.gz
    ├── 749c9416a8298e9f39a34d66ea0bbf7a75e1a63f.nq.gz
    ├── 74c5855ec5e4be45a825ada846147be6a64d965c.nq.gz
    ├── 74cf4c74bd2c59e4e7a279ff8f339c6dd3077b2a.nq.gz
    ├── 755cbb4f222e99a695e66bd5ea02ce837ff22c5a.nq.gz
    ├── 7588cc15c11e8b00b2300e5447af855a1e229c43.nq.gz
    ├── 7620f62e5708639ff069248a284f425c0384e2d4.nq.gz
    ├── 76d1a8f142f4ea34d47e99eb9185e2a8dc6ad04d.nq.gz
    ├── 7719af014e3742fc914c56a809ddc0e7e64308a3.nq.gz
    ├── 78840e96ec7d3f19d1a5c14c7d0cff3df858b790.nq.gz
    ├── 791c365b1e3b6ae397374d96e48e6d5be66bfc73.nq.gz
    ├── 797be2499f4423c6438a0009bdb5bf159fbbcb5c.nq.gz
    ├── 7aae26c108d0a2f4b8c4f2f6a52522848bcb3463.nq.gz
    ├── 7adc8e767870cec631fb9e30b0e185c11eb86061.nq.gz
    ├── 7ca86b91ed9e344212e2a3b62b423490ddf3bc66.nq.gz
    ├── 7d812794d315df0e1ed2ca0faf87fa6b5cc68722.nq.gz
    ├── 7df87e24a0355ccdcce02cccd1f09eaae18a3a49.nq.gz
    ├── 7e9d50461abcf8053278e38c1eb264abc49fac0d.nq.gz
    ├── 7f036e42c1d5231ac57028acdb2205eefdb652ab.nq.gz
    ├── 8032abc5a46fedc25e1344062cc6740146ea2a7f.nq.gz
    ├── 81762c909b8b0003aed86346e57fc7826e4c3519.nq.gz
    ├── 825d8bef94acb1ab412dda15befe29e13653699f.nq.gz
    ├── 88a4e899a8dc8c41bce5d0a49ffb6dd8ed647896.nq.gz
    ├── 88b54e95e5dba6dc8f7d30c2c78015ee121835c1.nq.gz
    ├── 898f855cb7ba0c8944061bb0c72bfc1ef19c996a.nq.gz
    ├── 89dab8e6470974114fb89d8f5ad46aa923f2bd6e.nq.gz
    ├── 8b58848ec798bf190b43146ac52321acc5207041.nq.gz
    ├── 8c36b153e102bafb813ca01a7bf8152de87ff3d0.nq.gz
    └── 8cab71336fee34dfee11cb67dcfc82dd34df6172.nq.gz

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

[canonical/kafka-operator](https://github.com/canonical/kafka-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
