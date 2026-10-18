# Repolex Knowledge Graph of jaraco/calendra

RDF knowledge graph data for [jaraco/calendra](https://github.com/jaraco/calendra), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/calendra
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cd3de1b04dcb850f7addae54d231a93e3bc71b9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cd3de1b04dcb850f7addae54d231a93e3bc71b9a
│           └── chunk-001.nq.gz
└── blob
    ├── 0037a90a956ba86d2ffa3c1d24a77e6d898922d2.nq.gz
    ├── 018d636ee441fa627d7b5d6ec050f8ebd81c2549.nq.gz
    ├── 01fb88d27ee102cec5b55778a593e947291f07cf.nq.gz
    ├── 03a11fd31433a996467d5cddf7dcda520710d91e.nq.gz
    ├── 03c79d76cb42f316599f6a6046a8172f0d6a18c5.nq.gz
    ├── 07682c6b4a5f8460cf3de5e816ffe9f110c8c6be.nq.gz
    ├── 07702a2c579d32aec8cc5c4c1999740479fe5ad0.nq.gz
    ├── 091708bac8a148f53e7c885328f78429207f638b.nq.gz
    ├── 09d0e2f03243f7b347dc220fca156846c43cd221.nq.gz
    ├── 0cd5475b7b9c3204851f078968d91470c7d03bde.nq.gz
    ├── 0e6c8306e5454e8c48379ea41859ff2a57b0e1c6.nq.gz
    ├── 0f370d176f52e887ac194220e842badaa9583e08.nq.gz
    ├── 0f5c349932971e45f8dda1d7c954cdb0ae4499f6.nq.gz
    ├── 0f68b87da8aa272f23232190d40762c276a4bdfe.nq.gz
    ├── 108c341aa4e85032e94cb43d223703a6d899e4c6.nq.gz
    ├── 10bd97546fb2cc3fa3d9457e56c36e818a03a4d4.nq.gz
    ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
    ├── 11209d067a9263861c9d57d361e698080767fe90.nq.gz
    ├── 1309e3c1a260a5ad90f6ddf6b285e445bed86d30.nq.gz
    ├── 13a1d6bf9f7a84c3e9d4f16ed16d8b09f39725f9.nq.gz
    ├── 149e9bc5f8ea1578e6d948004a121ba8fd813866.nq.gz
    ├── 176495d4c1d397a390ef667a7d7b47393e0f932c.nq.gz
    ├── 189771747f6c07ff5f36096332c64d6d0a1a296c.nq.gz
    ├── 1a868758326ecefaa5f7fed773bc1b5c1a6ae62e.nq.gz
    ├── 1b1b59bf3acabb40de67d9968b0e666a7e95939a.nq.gz
    ├── 1bef9f0b5f18c8ebfd065885ec8c8944efb37714.nq.gz
    ├── 1bf13dab6a34e98ac948ebb3ab33b2ddde2d8586.nq.gz
    ├── 1d8371cc04b3ee39568b23c9cbe6bda692a426fb.nq.gz
    ├── 1dd96a8401dcdcf64cee306c4137975af3ede2f1.nq.gz
    ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
    ├── 1f47496eaacb01d1c69fcc8098a0a402b503aba6.nq.gz
    ├── 1fae6567fbd7f5fd1962689abb9f4f65cf2659a9.nq.gz
    ├── 20026652a05f70be068e6ca6adc6d6e3256e3268.nq.gz
    ├── 2081185ed565e0101ffe16a51735cf5e5cf7bd25.nq.gz
    ├── 20db1744744ef2178fc28d2e388711a4258a06f8.nq.gz
    ├── 213b69a6bb6d6f96d0fa5fbe907ba7432e7b8e04.nq.gz
    ├── 25d92b2cabbd26aa0128a54fc97ee00b881b6be0.nq.gz
    ├── 28b44eb60344a3cbc3ef342096b4560caae6d6ef.nq.gz
    ├── 28dce1d376647ef5aebbc8441d7e0d9abd2b5fe9.nq.gz
    ├── 299867fd97c5f1f36a3bdc5a2877fdc256d9b5ba.nq.gz
    ├── 29cae303b6a1860d739269b5cc0194ffce0cb4d1.nq.gz
    ├── 2e194b6627476c265b539a19237f7a289e137cfc.nq.gz
    ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
    ├── 302f8aade73d75a3fccf5a96da8b8871e4764a81.nq.gz
    ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
    ├── 34e0c1c507235ec29d29d03c509de25862576c78.nq.gz
    ├── 3756fe62886cdaf55206a0a68f313060126630c2.nq.gz
    ├── 393662cf38b94b021b405b8bc1e6ddad681b998c.nq.gz
    ├── 39d4d8d561da38ab4eef51006c7582baf666df98.nq.gz
    ├── 3ab0c7700ecab670b866021b82dff119431d3b58.nq.gz
    ├── 3cb16eed02a8a73f89583fa8200e13cdab460c84.nq.gz
    ├── 3cecd918c1d2270fd9f44375b61101245e4a1e91.nq.gz
    ├── 3d8fb754d128f849b588baa42f303615a1748572.nq.gz
    ├── 40430a40376cf42fbfcde5186a7b4eead93be351.nq.gz
    ├── 406bc60abbf2094d8afeaf357ad2e91e432e7f7e.nq.gz
    ├── 424c8b029e3ebbd0c0d57036be35b69ae2583c75.nq.gz
    ├── 43163d592cd66dc4559de4cf3a0a076686cb01cf.nq.gz
    ├── 470eb5f4e1b7a132098ed77e4e0dd6f0da8a78e6.nq.gz
    ├── 490e117e8d0edb01e7e0f8a6cd0318bb918042ec.nq.gz
    ├── 4b0744091efea7bc3bb242032bd38c763a0ba550.nq.gz
    ├── 4cc05f21c13b1adbe5cfd069d29a6d85e2c5a015.nq.gz
    ├── 50917e45795eefe5e7caf1628d4f9b46464bd41b.nq.gz
    ├── 50f97601671f2d13254fc40adfa83aed054224c2.nq.gz
    ├── 51739ad9daaae38ec70ec38ceb29935897d8019e.nq.gz
    ├── 52921f7a8f33f4d0a6e4f174d769e8348fa93e3c.nq.gz
    ├── 53abe956725f9ae369a6b2baf5fc14c8309a4326.nq.gz
    ├── 53d39151a086d954f4232a1af5fa299ebcae8103.nq.gz
    ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
    ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
    ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
    ├── 57d4942594502ca9aa1a37ccdb2c98570048bc1e.nq.gz
    ├── 58b4cd7d1df91cc2046d14ee354b06559f835b13.nq.gz
    ├── 59603a41afbd08384f432a40ee2f1e00c7992bf5.nq.gz
    ├── 59c55f513669b34ba35c3b56de69165117982c96.nq.gz
    ├── 5a2b3ad6a1beb6c4b53d99dfcfe12a3fd3420bbe.nq.gz
    ├── 5a98a3a5cbe9a86beb2042c9843ddb09413a0d08.nq.gz
    ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
    ├── 5ecc9ba13dea132b9f7cf61291211da095dff346.nq.gz
    ├── 601dfa7100553989a86e25d473456902c2d4f354.nq.gz
    ├── 624796d08ba20e74dd6db53e94af33b09a26c2d6.nq.gz
    ├── 64dd7ebbfc9e55f506a3c11a84e9e58556a6ce2c.nq.gz
    ├── 659988081399f14cb5e05750589f633f70660801.nq.gz
    ├── 6681ee5145fda40262ba2edf3f4022ffe36fc0d7.nq.gz
    ├── 6825387567991e12b767aced73cd25101ce53682.nq.gz
    ├── 683c351e47c007c8d7bae203e378e7bbddb42b2e.nq.gz
    ├── 683d4ad226b796cbc6db8979a7646d3a4b075a28.nq.gz
    ├── 68ab73c4b7f0de065b7a7e9867bbeffe5fed187e.nq.gz
    ├── 68eddbbe3f2c302eb947c9d3b51d27cea450fd8b.nq.gz
    ├── 6932bd05ce5d3e2f863d4f7908e4a44b58a10011.nq.gz
    ├── 6d6baa1d5c14e93d8455f4826db279b0a2d97f17.nq.gz
    ├── 6f7775072bcc1c947a80de9ca39c577d0a29f71e.nq.gz
    ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
    ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
    ├── 7458d9b1e70fca6ef0ccf67e06accc326ae5f600.nq.gz
    ├── 745a1fb9c912c4277b0cbf15c5919c9f30545e2c.nq.gz
    ├── 754ee86dd250ea5b37680e1af9d7c9e0fa500714.nq.gz
    ├── 76ee25eff2004a22bb7d4385568f4093233dd8e2.nq.gz
    ├── 77fc5bb342073f55c723e2857339344fe41b2213.nq.gz
    ├── 785fe642fb07af7715d8c17738025cfba52d99b4.nq.gz
    ├── 78b445a7c44d697a8a214aac3c84bfc926b91a42.nq.gz
    ├── 795bcc37fdc2452a992c78d00df630fe119979c5.nq.gz
    ├── 79c0f0ba0d8f862ce444fd123c0f25307ddd6bff.nq.gz
    ├── 7c60f07025be976fa56320e4bd2d5b0df19c2567.nq.gz
    ├── 80586b405d3442efbaa3e112d6885fcbcf605565.nq.gz
    ├── 809d3078c2dbaf3e80ddbe551922470461c09197.nq.gz
    ├── 815417091a5a6a2affece0230a7af2a8beef8232.nq.gz
    ├── 83be52c78335c9ad8c0e559220404ad14cdec33c.nq.gz
    ├── 84430ba173fbea1634b26eb981a2d4517a0fd00d.nq.gz
    ├── 84f3d9da70e2b7b6527ffed5cc971410d25b384f.nq.gz
    ├── 85aa68f7a13bf4f3be655f313c6f58e15e847ccd.nq.gz
    ├── 85f383f445a4ab1e87e29d1b8f40afe816fc6079.nq.gz
    ├── 8931e94b53d0e6253024e8507af416d81ff76ed5.nq.gz
    ├── 8ba14c7a06da012cfeba5d860660c46ef5a688e3.nq.gz
    ├── 8ba24d39fccf745cf193a9313e6f0347c33e72ba.nq.gz
    ├── 8c331e2f60361ed6ec5af3db35ec2dacb8794cb4.nq.gz
    ├── 8cb0fa1a7cfb5ed234970c70849a66b7be0ca5d7.nq.gz
    ├── 8e868f26806c989255a0bd7f25c59f20938c9cae.nq.gz
    ├── 90c47434e02a96b55b517ef5f9fe8fe56a620ba5.nq.gz
    ├── 916897ffe3891f48ecfc1d3beec3cc9fd3c74ec8.nq.gz
    ├── 92eaaeba30d11e8b0e41b412e1fef3427a61e843.nq.gz
    ├── 9380324e18317ec79cdfecea0d37adedfbe76ad2.nq.gz
    ├── 97c492ce54643634f65f5cc5185b986016379ebb.nq.gz
    ├── 97c598921865c0afc4b8243a9b7f764007ff6d69.nq.gz
    ├── 9891c8f30b5c5f2dd7e5e143151893dc6a0313e0.nq.gz
    ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
    ├── 9b526f7fd50f4c500c80a4054a968a6be905079d.nq.gz
    ├── 9ca4e1ce66dbf75418f55f1cb029b989b5e98ae1.nq.gz
    ├── 9cf3ace7f6a871d5793d134c83dac29c764c5697.nq.gz
    ├── 9dde45d219c1a4e4faeaec3ed9bd9a73d73a452b.nq.gz
    ├── 9f99b43363c85ee5f718b67bb00aae634cf35914.nq.gz
    ├── a0bd29f16daad7476574b48c3d044b2996a24d47.nq.gz
    ├── a1a9c4ff441444ec52013b499538eeb4ec0618b5.nq.gz
    ├── a28f7eee1b8605eccb0f4559d480497fe1a72c89.nq.gz
    ├── a43cae5d288bee3e6ba0274a34a66353d7414fe2.nq.gz
    ├── a4426d49749893d7b78940b4d2aae4dfa93a6729.nq.gz
    ├── a5359415dd2680959a9109994588944508dcbef1.nq.gz
    ├── a8c729f5dcd6a5eac936fe4f89cb47589f45fd1c.nq.gz
    ├── a8cb7f3ad71ece32210654c67cf412a50b4a5750.nq.gz
    ├── aa6fb47633f7c9b8136baf3a88414848a0734e07.nq.gz
    ├── ac43ff170764edc95ad39d7fcbd1044aae3d6c1e.nq.gz
    ├── adec29324beb5e997547f85dac531b0cb1b10685.nq.gz
    ├── af1adc35cd5f49910e873a73f8423cace2916f7b.nq.gz
    ├── afba0b4434f1fad04c96453f90e84bfcfef7af35.nq.gz
    ├── afc34b43bfca4bafc8ebe3c1b918b64bfdf1bc6f.nq.gz
    ├── b0f6b9133c047d31b2e1d57ed38d5045da6d48d1.nq.gz
    ├── b128eb5723d4e3a1000a68a2b69b8169c87ec332.nq.gz
    ├── b350602a0be2a828621a9c13de057b76bd19d1eb.nq.gz
    ├── b596d67066efa36e48f98d5c47567938579684db.nq.gz
    ├── b59c594510ddd23fce013838e451fde02f3080f5.nq.gz
    ├── b5e3497e495cdc6d1da1d89739942a59254e2e9f.nq.gz
    ├── b68c28f353c148ee27d1655c259fd2ce6f0e376e.nq.gz
    ├── b7a50b248085d5889b9c7dd4ff1d4d7f092188bf.nq.gz
    ├── b7dac86bbea9eeaf615c673a50bd0a9cab06c460.nq.gz
    ├── b831e294a9cb67cebb0a5ca1c596cec52cba164c.nq.gz
    ├── b8a7f37c8856b847db74d933a149159af76ef873.nq.gz
    ├── bb5ce7968104184d78c5b27b7cbd7002d6f27971.nq.gz
    ├── bc8ab109799653c5e59470e99710e25a52e31336.nq.gz
    ├── bdb7bf13b68bca210aff611150100a0482f6ba3f.nq.gz
    ├── c2dddb203212293193a0a7a80f88a7d68a446044.nq.gz
    ├── c59f13f763d881ee7a00aab27c5a501cbb42b9b9.nq.gz
    ├── c710781464e5ef1cde37fc221ab727293f9c1620.nq.gz
    ├── c7ce1d501050796762fb8298c6d624adcc4bd300.nq.gz
    ├── c9790bc407c8a3806b14da20c41127dd0853a0c5.nq.gz
    ├── caef6453e20b85f2a0c309c96460d358b7fd1316.nq.gz
    ├── cb5308cabd761512509a849e64d9e0228e2bf061.nq.gz
    ├── cd12216940d1c66773ebc759b3f35782693e2554.nq.gz
    ├── cd1fa1cfa2af59513b4e5aba91ece4a7879e8883.nq.gz
    ├── cf5e795f7d333c9556a4694070ed1a7da9b9556d.nq.gz
    ├── cffb5468bae2db380e282a990da0c4af5cf9ba13.nq.gz
    ├── d03206b389eec9562441323d60e43d1920f60c89.nq.gz
    ├── d04659e89f72024990ed807b27e6424fe13291a7.nq.gz
    ├── d073c3c7616c8e3a7c1c4a0edd9b734bcc324f00.nq.gz
    ├── d187d73e33814d9c1b9034fba2e79ccab586ff5a.nq.gz
    ├── d33f0f7d02d7ee104298d4c762bc8ea156a9eb63.nq.gz
    ├── d4600833d5095901fa75ab1c2854e99ec4d7f4df.nq.gz
    ├── d483217e662d5debb0cce012aa91be0e77c6a2d8.nq.gz
    ├── d584add91978da5f1ddfc8276954f6c89e1e3dd1.nq.gz
    ├── d6327cf1b145c1b28b9a5bee01e157b5c363bae4.nq.gz
    ├── d6e65c7bad6fff43a29b1f1c426ec50970bbfe68.nq.gz
    ├── dac150782f862afe6f35b2c55bde066eccd4af47.nq.gz
    ├── db793ba47b5461c8d6db1362b7c2388ad139c627.nq.gz
    ├── dc3b6a539ffa5c45f44627029e8839c7e3b080c5.nq.gz
    ├── dd5478c238283a76029e5aec37a11b521a3add8c.nq.gz
    ├── ddc9bb9b56c130f7939b7cf8763a669b2fd98070.nq.gz
    ├── ddd8881b1f1a2b78661d78a30908ee63ba8157c8.nq.gz
    ├── dfe3319ffa80d215c944ff854349698324c538a1.nq.gz
    ├── e040229f8741ad634ec04a6c582d607ca7f0f01b.nq.gz
    ├── e16cfbf6fa6da9ea44777f5d9f5b6fe7da21bf20.nq.gz
    ├── e24455880652605d4bad7e11f4cd9b7e62e92731.nq.gz
    ├── e3a52ae2b5a1402f89900f9506db02ce9b26cab3.nq.gz
    ├── e3fd94f091b2072ac16f7ad43501dc4f955d25d9.nq.gz
    ├── e60a2b41c476eea00d4138658f0994e0602be721.nq.gz
    ├── e63f338188ccf483a1225711aa054954d1336daa.nq.gz
    ├── e68f619f3dcd133985c2c1e4c82530697492b331.nq.gz
    ├── e7376c98d058b04ec556a28d4c761ce405b48651.nq.gz
    ├── e7e79be39abee35f7f60c451046e708af3cab50d.nq.gz
    ├── ed7773ef61f710a08bd828e22598d357f3859f37.nq.gz
    └── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz

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

[jaraco/calendra](https://github.com/jaraco/calendra)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
