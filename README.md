# Repolex Knowledge Graph of embedchain/embedchain

RDF knowledge graph data for [embedchain/embedchain](https://github.com/embedchain/embedchain), parsed by [repolex](https://repolex.ai).

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
rlex download embedchain/embedchain
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0724291bd864cf807e88ee8981c8226644e8fb42
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0724291bd864cf807e88ee8981c8226644e8fb42
│           └── chunk-001.nq.gz
└── blob
    ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
    ├── 00daa05bdf0644f66107cb3097056087e8eb47aa.nq.gz
    ├── 00f2d38d8063d0c6b219c0081e51888063b0c55e.nq.gz
    ├── 0240f24bd1ac1cb410093b458f96b0fcbd546c59.nq.gz
    ├── 02789f05608e5e4fc6927f25bf743f7c834ea106.nq.gz
    ├── 02ef7d6d617476970bca1af988765e986fb65a1a.nq.gz
    ├── 035e105d99681d3435637046d625328827d0d87d.nq.gz
    ├── 03d597bc48659445780ddd7a197402adaab7571f.nq.gz
    ├── 0457038b2accd9db27920871638921d0a06f6dd0.nq.gz
    ├── 051bd3167d01fc450b6d1b3f5308ea9d7c6b7cd6.nq.gz
    ├── 052325d719a1b8b74362ee15d481b37def8c9304.nq.gz
    ├── 055ef222287eaceb3edb712f28b4cf002070b457.nq.gz
    ├── 056a7bc6161b33170bcec9b649205dd452320a03.nq.gz
    ├── 060b2f11d14f57a668ad5fa6a784fb29b3ea54d5.nq.gz
    ├── 08135196d4eaec9c6a108b5b57a1dc9195fe84da.nq.gz
    ├── 08b9a3fbe3c7201aa307ddac62437ceabcf69466.nq.gz
    ├── 09593abba31c5629b89e35b00200811138209cac.nq.gz
    ├── 09b285cac3093d0019344b384852385f889de937.nq.gz
    ├── 09dcbc837bce7805bdd3d084ebbbef00215c7ea9.nq.gz
    ├── 09e76c75f7356de09b537e52a46f75664b851680.nq.gz
    ├── 0ac01de2b3b360b3874ba113ca60770a2878c94b.nq.gz
    ├── 0aeb58270a3138f09d6d8653750869a3632d4499.nq.gz
    ├── 0b953d260b9dd60a4ee37e775a3cc1331b526a34.nq.gz
    ├── 0c272e9ff33d52562b0d3c121a3f2a49089781f5.nq.gz
    ├── 0c35fb630f9d993540bd1b17a9958c43eb35af54.nq.gz
    ├── 0c9474eaa0fc110af65fceb188c5132db20ce97b.nq.gz
    ├── 0ca1c63a9cae9f660cfc2b58f1e68c66464ec2c5.nq.gz
    ├── 0d4f006fcf2739a9ed2e3c6c4e5d783f457094d7.nq.gz
    ├── 0de8553834413e32b05fcc352555a0f287c42975.nq.gz
    ├── 0df88638abff4dc8a4c3a6e307c7d95c84f7e15b.nq.gz
    ├── 0e20bf1ffb943369960be8a5d93420d5cc2d0da6.nq.gz
    ├── 0e2dc6c6a92617a1bb2a61804b20f10d18881b70.nq.gz
    ├── 0e6aed4f36ffb258042a4434989bd0520b383ff2.nq.gz
    ├── 10cbee109fb427c1516cd8e14849778b926a512e.nq.gz
    ├── 11038737dfd47e01003ec8e57996321ac5043fe0.nq.gz
    ├── 1163ed5261eed5616932f1cc8c3c454dc3993f54.nq.gz
    ├── 11afb74324463b69cd933370c7976097f9ca4e1c.nq.gz
    ├── 11b7a2c401ce7cdd5df688fbdc606eb98b3e8272.nq.gz
    ├── 141f6018e8efd4e52edca1c521d274d14b68e635.nq.gz
    ├── 14414205d163b3df49ec7227bacdbe39c9b640a2.nq.gz
    ├── 150128518ecb1a60fd80fb908f03d0406b1eb5e4.nq.gz
    ├── 165c0c675c28b12ca619075a0ea5bed252c12137.nq.gz
    ├── 168d1a1a505d38321ec219df6d07056ad7e92986.nq.gz
    ├── 16a1139fee6efa09492ddfaa3446df98699a4caa.nq.gz
    ├── 1725e5f4b2da0baa0e624c8741ee6fa41ed7bd11.nq.gz
    ├── 17384c368c71a29c9b88ee643cf251ea008f583b.nq.gz
    ├── 1838be6327144eaf47c688bcf6ffb87faf9cc116.nq.gz
    ├── 1854cf41fce66ae46da2a1c0b39e9850a40af1f2.nq.gz
    ├── 18aa050c9969f139ebc5abc08231aff946f45c46.nq.gz
    ├── 18b7f68ec334de04710b371136ede1ff0932ed2c.nq.gz
    ├── 1941c3e8f8d567c2de7079d7121d0ddb136e0e47.nq.gz
    ├── 1968e88d281624db86ba599cf14ef343ed77dd24.nq.gz
    ├── 1a1a89ba08858b79194732e7e61e7b110390ed4b.nq.gz
    ├── 1a44ac3a13f8c7115951978325059e92e2c16910.nq.gz
    ├── 1aae65483642f1b0f108683df11609ef36aecc02.nq.gz
    ├── 1b3be0840f3f6a2bc663b53f4b17d05d2d924df6.nq.gz
    ├── 1b65e1436a30f58a59ccded4d2001b95d121a028.nq.gz
    ├── 1c44857758d972c58754ed6352217158a4f15204.nq.gz
    ├── 1d757329ed82250ab4be5dab67218abea6b7f830.nq.gz
    ├── 1dac26073c62d48f19bea2229637bae145b948a5.nq.gz
    ├── 1e3ce4dbb7f58edcf67f77e05006b3d258f878b8.nq.gz
    ├── 1e99f59ea6281e9969321e468bd3bb7fc6c9dc9e.nq.gz
    ├── 1eea4d936333bd23a995e3fd04686c0f2374bba7.nq.gz
    ├── 1f99e8561c813ef8c3ba585fab7bd46b21d73e71.nq.gz
    ├── 20c36af8d554cc1226567d81fa02b161fd610699.nq.gz
    ├── 220cb481f3b42b171309cc419b96f150bb6e1b4c.nq.gz
    ├── 224099be2ba45bd798102f3897a46f692fd6ff27.nq.gz
    ├── 228ef383313b41453f11e8234c1d903341f11c4c.nq.gz
    ├── 239604e9da2c35934cf1772fd52fc929e92ae56c.nq.gz
    ├── 248ca95720e9b7165ee7c34c2ffc8176a8b3b3a4.nq.gz
    ├── 24cd868a36511accb07636055805ec978df11876.nq.gz
    ├── 2521a105c104aa120e13306a7e02937d31394476.nq.gz
    ├── 2528a79feaac69c364ddfc1c82bcbffd2a2a82dc.nq.gz
    ├── 2587cca737f95d1b53fda6702b1d51462d1641f9.nq.gz
    ├── 260a12d8c179ad88807803279b5cdb2b75250ce0.nq.gz
    ├── 2793bf6a5559f0e624f9ee85452e72bb5188b34f.nq.gz
    ├── 28456494f476a749b19f4f2c9168d71815a14e46.nq.gz
    ├── 29adbb27eca558dd082f55ff6b0aba76b66d47ef.nq.gz
    ├── 2a57e05267ed2b2529cb5526d9fe885a67afc325.nq.gz
    ├── 2aa85f04c79dc0bc11b6ee3137398f72744b8f75.nq.gz
    ├── 2ad8035b48b3cd91cae079903276d96dfcf1a973.nq.gz
    ├── 2b0c688be3cb16201fcec134bc025aaaa5fbb094.nq.gz
    ├── 2b48f032707aeff26b97649702bfb98026803bae.nq.gz
    ├── 2b6c5286ed318c3bb40cb84dd7fc4ba928f2d10f.nq.gz
    ├── 2beda10ff7bb9e37eef6ed174d64c9e843fe670f.nq.gz
    ├── 2cbc9a73ebef30b5f2ed4fdcffc35d4560ef243e.nq.gz
    ├── 2cd95a06d1016f288f5243bc12e963287cd6bfb2.nq.gz
    ├── 2d027817ba663c576929de55a4fcba10a4e2750f.nq.gz
    ├── 2d386a055141bc3521c51d9298f457d3a2c45846.nq.gz
    ├── 2d4a834735aaee1da38336d89b3cf99c2a873d17.nq.gz
    ├── 2dcc403c6e0cb137d483d42083a2096ae7a5cc7d.nq.gz
    ├── 2e7af2b7f1a6f391da1631d93968a9d487ba977d.nq.gz
    ├── 2eb7ec036916d9a45aad3696597308f0440c4b5a.nq.gz
    ├── 2f3fc6967beddecf6443b3d4bce831c6590d89ae.nq.gz
    ├── 2faad881862180991511b48b2c6e0757cc24c90b.nq.gz
    ├── 302129c18802e1d8bfc76b48cda3ac412dc3f2d9.nq.gz
    ├── 30272b884b9ea61464061d739e2fbb1e7d5f0815.nq.gz
    ├── 3090c1d519482849529ea15709de8d08673a1f88.nq.gz
    ├── 30a6700150dc1671442b4ef4e9bef3b785052194.nq.gz
    ├── 30e032630364f0df7a6dc5cd52461fcb82d76e5c.nq.gz
    ├── 3131ab57c2c83cdb57dfae5c6ef75f4fce0374d9.nq.gz
    ├── 316b78e5322c9d2c807c3fe20cfa44c18df1939b.nq.gz
    ├── 31a26b2fee7fa8a2b746a6a84d021e5e2d937b64.nq.gz
    ├── 31cab70de3ee283c105a8c64d38445eae8cfc964.nq.gz
    ├── 326f37802fadb29b3738e057d288c0bc235e2e8c.nq.gz
    ├── 32cc05df7faac14be3f54c93b10b8f72b22098b5.nq.gz
    ├── 33503d32abf0a23f6958c36d9a90c9f37f962498.nq.gz
    ├── 3353a8cfc49aac31a44b9a0fce0946061e9be1bc.nq.gz
    ├── 34372df52ac8cd5f51f49f5c05776e4203fd5012.nq.gz
    ├── 35e00c97d67cba3b9fc6978a6e27dc4e1dfab665.nq.gz
    ├── 35e38ecf59b2a5fe7c3be0c98c6eb14773783f7c.nq.gz
    ├── 3655cb8cf3ac43942d3b631491b1415295c4d521.nq.gz
    ├── 3668d68ddd6f54a47f1a5f9afdc087cadae86a98.nq.gz
    ├── 36746b50e14da932c634ebf2626ef459c6df7b60.nq.gz
    ├── 37d140b28343848685e11e68ed3da740cd8cae66.nq.gz
    ├── 37f89b79e00a2b031e90663964f78477f90c3750.nq.gz
    ├── 38317253f71bdf82dbef80499daad333de80162a.nq.gz
    ├── 38d4c061a1b52bf0ea4d9780dd730be60d620aed.nq.gz
    ├── 38e5a59e1244ce726cd030ac4a70343a58112009.nq.gz
    ├── 38f61dc454502509199f5564e037ef1824792c84.nq.gz
    ├── 3a5ab8b87a69e1a47fc64d775871eb2b3d73d2e4.nq.gz
    ├── 3ab44331871d758e2983c5172ca5f9d3d46ebe0e.nq.gz
    ├── 3c21d6f2684e738b028bbe973988075479f3396e.nq.gz
    ├── 3c9ab6742d08d879791460efec9960bb2216b65e.nq.gz
    ├── 3ca1dc3dec87fed7881a9300a9684b1461cb38af.nq.gz
    ├── 3cb5efa707a417296afe067e68f06e542100bf96.nq.gz
    ├── 3d441c1a5d097562aa4febc512b02d23c6ff7642.nq.gz
    ├── 3db5cf238e81bc8bfcde93e06870cd1809b78f9b.nq.gz
    ├── 3e44034ad5beec72965a90ce9671509b87f6a36d.nq.gz
    ├── 3e8cf1b7495fc8080993929f658b00919e0773d5.nq.gz
    ├── 3ea9ad867ba6d6015018066697ba91cb6ed5de0e.nq.gz
    ├── 3ea9cc4f0c2151543e189252e4a5e283101436f7.nq.gz
    ├── 3f5d9a7909a0fe7625bf114f25cd37f060c061de.nq.gz
    ├── 3ff16853eabc32f7ba4a998e7e868ec58f5c9bc5.nq.gz
    ├── 418172c3c757ca9c28e967eee20d8039eff25878.nq.gz
    ├── 41f744240e6d017fd3cc47fec5cfbaf46caf8f4f.nq.gz
    ├── 423ca9c00cc45dfdae36396b47361dc0e7137b9f.nq.gz
    ├── 42a225e14b61a30d9947b4c7e76bc4eb5affebf1.nq.gz
    ├── 4371c1ffeaa570135f45022f2b8f30ee5a1ccba5.nq.gz
    ├── 43fb170eb8320ea4d17e6a44b9d573d5987f96ae.nq.gz
    ├── 444fa02223f28f0f5d672b7735e05f8c44d1563d.nq.gz
    ├── 4468d7912896dad511f47d73a3d3e3e90bcc1f16.nq.gz
    ├── 4513b4f5811e34c1170673511e2152f759d7120e.nq.gz
    ├── 46ccfb20637c740277acbcad8291f1b2a959eb93.nq.gz
    ├── 4730184da82853f4f034cc415a73a4fb7ec09c0d.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4827fcc4ba823ee305ff329a722af5aa5ab1810c.nq.gz
    ├── 485833dad7914111933dfe5a73b174fcccd94912.nq.gz
    ├── 48c164d329d38cf8685267770e59b84cd30726c5.nq.gz
    ├── 49eb8861b9e729223adb64d945b92235e892857e.nq.gz
    ├── 49fae53d53ab002ac3096be8557b80fd56496996.nq.gz
    ├── 4aa840212dc4fad8762c9e27711f142acd169ce2.nq.gz
    ├── 4b7456b184e7588ee358909a2f15f5a311457f3e.nq.gz
    ├── 4e5be585ddca609789185ad8fc41fee160129f8d.nq.gz
    ├── 4f043f03057a09dc495fbd1b863339c7594b0bba.nq.gz
    ├── 501a434f7ef44d32d353102fbdaf69f54028db80.nq.gz
    ├── 50ba822478efa79f6c0e8729f1bdebb3625e1c5c.nq.gz
    ├── 5159ee6984df0626e6730d67369a6ba9f4539f38.nq.gz
    ├── 51d2ebcfd7249d447e9c011029e19435bc4eef56.nq.gz
    ├── 51e507ba9d08bcdbb1fb630498f1cbdf2bf50093.nq.gz
    ├── 52576aca090dfe380dd17bb12749e980de48bd21.nq.gz
    ├── 53c7fb82630045a99bc6dced85a3d6da04fc6c40.nq.gz
    ├── 552607c15bed3c3bcfddd0cb27d87ea50799c1d5.nq.gz
    ├── 5642da3023ecb38ae751c8e23f7791a143a92ed3.nq.gz
    ├── 566596c31232e1c17bb264ba22e182bcdcacf8a6.nq.gz
    ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
    ├── 56815d5562a4250d0b742f2ec6699b7dc86f71a2.nq.gz
    ├── 56bf7add1c9129fd061288cd2c61294c3e0e9516.nq.gz
    ├── 57760f2ee48c8b165fe72fee64542d3d90eec97d.nq.gz
    ├── 578e18b16112a46bd3b5914922c4281ed7404a44.nq.gz
    ├── 57a7a3efcd4d079b831a5bac5d068e1cf894281b.nq.gz
    ├── 580228aa9d03ff8e5db89b1d6241828d88437713.nq.gz
    ├── 586bf9030cf7b929aadfe08df56cba6ac74c10c6.nq.gz
    ├── 59324401d4541cb8ca72addd37c44674593daab3.nq.gz
    ├── 59569fd21ff96cae4929f1afe6532948eb54e7ad.nq.gz
    ├── 59f0cc864a155978f0633223684093e98d0f36ba.nq.gz
    ├── 5a91120254e811b05eac53768b97c8c6c4a5df2c.nq.gz
    ├── 5abe9f948ea136bccd96bc5e298ba350f9812e36.nq.gz
    ├── 5b2be1c30cf5c9673a4ba7f3473f59b38e313170.nq.gz
    ├── 5bd5512436cc6f3cbd5ce03d10808d3e6eef067b.nq.gz
    ├── 5c67c876ac3a2cf4489ad7c7066ae9abfa41f17c.nq.gz
    ├── 5cf52066707f4447e916a8b29118456a15a58305.nq.gz
    ├── 5fe46f8bfa264727552da5cee9b2736260494645.nq.gz
    ├── 6063ad0a7c5df351c94f1cb1bc83c1b9db3800ac.nq.gz
    ├── 61043dee06f9b5905b3cea32ad77535960492e7c.nq.gz
    ├── 615cd0f8fce3c6c79e72fe91c3056c071c369a34.nq.gz
    ├── 616de9d02d30c98070390fc7f43210f7c0404db0.nq.gz
    ├── 618fa3917948423cb5dbb4696684f7e8d6cfc28d.nq.gz
    ├── 631eaa2d933989a4c63513a2c88d8f52e40c6407.nq.gz
    ├── 647e6fe4f069db0dad7e71aff5ae02cd0529e801.nq.gz
    ├── 64882e898fb748e842dabb4ed86e5300731c52cf.nq.gz
    ├── 64c1a7255161e4e2aabfea23a26e4bc24e132a90.nq.gz
    ├── 64ccbc7206b14ac9766e8fbc3fdc7c9c93104f48.nq.gz
    ├── 65e364ea33d6a6f2bce9c55d76510f1e22f2c7ba.nq.gz
    ├── 65e7c2ba5347c6a13f38fd60d9d9ff2f51bf72f4.nq.gz
    ├── 65fafd40e47bfbbf708ebca8fb8dbcd515fd539e.nq.gz
    ├── 66eb731164a7705bd4c90012c5eafacfcd0c6521.nq.gz
    └── 6788512dd35f4fce015b02f7b17095fd9fc3dc13.nq.gz

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

[embedchain/embedchain](https://github.com/embedchain/embedchain)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
