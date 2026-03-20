# Repolex Knowledge Graph of pytest-dev/pytest

RDF knowledge graph data for [pytest-dev/pytest](https://github.com/pytest-dev/pytest), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pytest-dev/pytest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   └── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   ├── lsp
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   └── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   └── repolex
│       ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│       ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│       ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│       ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│       └── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
└── blob
    ├── 006629093bffc5425fe24e2d5d39cfb35e93485e.nq.gz
    ├── 008762cd202c75c6ab6de63342a7465b5ed06465.nq.gz
    ├── 009a6a302ae9557102c78654512f7af713f02f02.nq.gz
    ├── 009c2a9741f52ea562beded4b125ef34d94cd019.nq.gz
    ├── 00aa44c0bd006db4b3ea7eb078829579a60c5530.nq.gz
    ├── 00d31b349c3649acb6318edb7fc65b72d8f87dca.nq.gz
    ├── 0138c6593b5250b7c1fe1c23a024549b48628190.nq.gz
    ├── 018d3e33e3a172be447c5a681e7292b2a54c6cab.nq.gz
    ├── 022ff711dd0a0565b6907d058f73532ef1161ca4.nq.gz
    ├── 02679a75c31093b684890d718f62c5aeab6335c7.nq.gz
    ├── 02ae0c090281a7f8c02c64256361558435f497d9.nq.gz
    ├── 03075d75a7ef71fc10a28231284212af96c85c4c.nq.gz
    ├── 031aa649a550c5c19414f5bffdbac2f293490236.nq.gz
    ├── 032264086cf3fa3fcc858369fc5afcdef82293c2.nq.gz
    ├── 032f683ca211f396c7669011e0623dc3ad4b30bf.nq.gz
    ├── 033efe5c8f79a6ee06c04f457a9bd2e815cc3a86.nq.gz
    ├── 03e1b108b2111e2c54c8c5c81f50e5fa3891b87e.nq.gz
    ├── 04247f88e404c1770d64289ca9d57a93cb0a182c.nq.gz
    ├── 0425a3632868ff777e2f6db0c273dab12771af9e.nq.gz
    ├── 0455b72553365fa2e640a9595f30081a3e981510.nq.gz
    ├── 047117f091e578f7234f1d3a2e0810a0569a8fa6.nq.gz
    ├── 0481c93dd2185ee08914de7f2a99f929a1b2710a.nq.gz
    ├── 048c69d2213bb5e99831e205de77b245d93b3c2d.nq.gz
    ├── 0578ffdd5d2edbf5adaff72ca1f117c69d18a099.nq.gz
    ├── 05801675179e8acc593aae0fce6ecb5f2b94e0aa.nq.gz
    ├── 058de7b8e4cf3573bd53e85892bf928ea7d857b2.nq.gz
    ├── 05b42c4ca557d029811b7eb6386df1ef9586b8c2.nq.gz
    ├── 06e50e31f1e0c3adac1a5ad448c4d1b63292844c.nq.gz
    ├── 0715cf087680464ece819632d61527928f5bd60c.nq.gz
    ├── 07aa2296442881fdefcac271bdd720fb0089ec8e.nq.gz
    ├── 07c29762cbf10c19afaf25c2aaea5c8ba417e976.nq.gz
    ├── 07c2a5802b2864d395ac7f4c720749a8f2d42e02.nq.gz
    ├── 07c65ce995c13c5925a558bb35d624cb2e0d05d4.nq.gz
    ├── 07d6defbfcacd0ba79b975e8d0a405e1b0f5d228.nq.gz
    ├── 07f017b9be660ec23e42d0f58b77236655bddaa7.nq.gz
    ├── 084e59badb049c9090041054945de5a065faa7c7.nq.gz
    ├── 087ce286214d1eb78c029a0c1c76393b0b574f76.nq.gz
    ├── 088fa97e24029d5e1a365ba55e580110290c0c79.nq.gz
    ├── 08ae43dce4501c9643f85280eb3a6a89aaf07d51.nq.gz
    ├── 08c0b9f7a7584a6e634b6fed91afb0e50eef6416.nq.gz
    ├── 08ef4543dc96f7aa9a9b3c1d5d410972124e3921.nq.gz
    ├── 091799fd467a660b045bf06f710add3c3557cb39.nq.gz
    ├── 09c6c7de34adfb22574b41f3693e8a6977e8333b.nq.gz
    ├── 09ce92669954e109275d19ac14b8fa644a026ea4.nq.gz
    ├── 0a0ba4c00520bc5d1a92c584189930a4abc92d1d.nq.gz
    ├── 0a94794cb8117bf516e09a124d3b2dc11f80f4b4.nq.gz
    ├── 0ab3b6f5a2ccc61893d6fbc42b8b0cc4fd6aab83.nq.gz
    ├── 0b4beb1e192560cfd38227ed0668754548631627.nq.gz
    ├── 0b82cd8cce5fcab2b4ec990cd3822447cb16d55c.nq.gz
    ├── 0bd983d9369f13491b9e166d941490df57a107bd.nq.gz
    ├── 0bdd9775b48d9d6959b473766e20386f5dabf33d.nq.gz
    ├── 0c763a1a8e9aec7fb33fd3ab0be4f811e986cca9.nq.gz
    ├── 0ce1f46c173d71fe83aa9b79bda09e25c05a4ba9.nq.gz
    ├── 0d172f8597581a65b0141efa3a604db5e398cb62.nq.gz
    ├── 0d525b95bf104bba8dd257c3b6f32d16f22c15b2.nq.gz
    ├── 0d715a4eda03604fdf7ab50fd0e078354406b85f.nq.gz
    ├── 0d80b938ca04cbb466403ee784ad13e1fb6b6204.nq.gz
    ├── 0ddbe53eaf8a929c6ae59fd7598f06678d5c8d22.nq.gz
    ├── 0df8582f6993f10199c9551ca3d835e48bd1d517.nq.gz
    ├── 0e15c4e997f24bfa95ba3a5e7afc6caff9e8e3c7.nq.gz
    ├── 0e20c3c9c91a57d0ef08bdbe8453e6593384c02c.nq.gz
    ├── 0e27ad3a65d177e5eb1fa78048e7ce85d0918f54.nq.gz
    ├── 0f5e2a5155f6266113aa5735c7a4d9216e17a7cb.nq.gz
    ├── 0f673f368b77b2ea9fb0f66bd76f5cf30ccfa1cd.nq.gz
    ├── 0feb34a17a92dbfabfe5636cdd79c17e3522525a.nq.gz
    ├── 102feadbd2a45a39a9066e297aa7823f447d5131.nq.gz
    ├── 1032dc65302aa9a32c6e51f424c3b160506a61a5.nq.gz
    ├── 107c33c1eaf0b7ca88feeea222363a76733400b8.nq.gz
    ├── 1098b3095b6cc7a2460f45a7d1d33b9b2d2042c8.nq.gz
    ├── 10fc3ac1093608583e0c6514e6dff72ef28207c2.nq.gz
    ├── 1133efbbda085818fbbfc6befc359e74c37e8573.nq.gz
    ├── 114553f5ef6ebd5e386bfa6bbaab10fc71d48d20.nq.gz
    ├── 11514ff46e986b74a68d67b14b2b183b25ab4dfd.nq.gz
    ├── 118e3866389ab664d74344cd9f1fc796617a1248.nq.gz
    ├── 11b068a0c48134253699e1d557daec63ef4b04c7.nq.gz
    ├── 11b665914b4e4c296b60e8c5539af2dcc363b5fc.nq.gz
    ├── 11e8b1e1a1689f0e1baf7f730df78d3921e004e8.nq.gz
    ├── 121d45d41cdeb63c26eb7d5e4e797cfbd11c275e.nq.gz
    ├── 12581eb7afbc231e02476c125ccb9e289e6f3024.nq.gz
    ├── 12970e6d715de061c2200af3b1a9a63ea647990f.nq.gz
    ├── 1307de5438cd9cd47e5279e7eb6a00ee76fe7a60.nq.gz
    ├── 1340cae9980d2a67e75e4451e095d1a4fd47907a.nq.gz
    ├── 136b7e49468ab928d9d14848607125d9c8b63a6f.nq.gz
    ├── 13a8ed7b0c0a0768ffd7ec012a57e57bc16d16c4.nq.gz
    ├── 13c6a6d9afef50a03d032186689327ea518a78f8.nq.gz
    ├── 140bd39f27be2d01104b15b0275b270313e6a3b8.nq.gz
    ├── 143556a0557f7d8dd11aebd8cbf4f5a675c168c2.nq.gz
    ├── 146c61e8a7e9c880890faa5d1d4ae9fe8354bb96.nq.gz
    ├── 149691c4f766503bf738a35981669af3161594bb.nq.gz
    ├── 149baa43542ac29e0e711ead9331c2abd9294eb6.nq.gz
    ├── 14a2ee1d0fd160c03fc18bdd07c4a7d6014e9700.nq.gz
    ├── 14d7cac945c8ec07ab972c5559904a401f970923.nq.gz
    ├── 151881567623b8a95719a914b153a67c20509fef.nq.gz
    ├── 1519caffe83506ae989b00cf8b52bb749eebcd36.nq.gz
    ├── 15384ee25955d3ccf9156230f0f9c2ef723429e7.nq.gz
    ├── 153c2409baa525984d8c826665590a5d345d66bf.nq.gz
    ├── 1585269a635ff5cf4135d03ab8fba10fe1002b40.nq.gz
    ├── 15914551df67e470b7ffa7a2e74409bfadb5ab9b.nq.gz
    ├── 159193e75413f616090727c6fe3e4c9b7cd221bb.nq.gz
    ├── 15e506ba90599a7b7873bca06e65c1a3a4c06678.nq.gz
    ├── 1603b3e69e72f3cc1fe05741c200fcdd37582400.nq.gz
    ├── 16334c9a52b872e5a6ada7fa9b263bd6330f4812.nq.gz
    ├── 1644a83d5c170f07c1f07456852cd05f4ac98154.nq.gz
    ├── 167d16a4757a85fce918a16496419473f13ee602.nq.gz
    ├── 16992452a511ab0c4bc5348ac7e8e0ed6bbe1eb6.nq.gz
    ├── 16ba55118fa39ea4887a723b5c96232d9354ed92.nq.gz
    ├── 16e385321a2a15a7efca9bc344b9fdf2daec07e4.nq.gz
    ├── 170b2e1b588d9021a35641288c1c1032452c2a8c.nq.gz
    ├── 170fa844e3c0b6c2471d352a46308d30ce1e4b84.nq.gz
    ├── 17a9fa8774f9cb686792742153da6f59b77e770f.nq.gz
    ├── 17afdb92c69aab12b5b97bcc5110416bd0fda771.nq.gz
    ├── 1805d170809726f5519ec108a17a1de6c68775a4.nq.gz
    ├── 18a07888628c6de08b41fffe134e29f9489406ef.nq.gz
    ├── 18b055eba0a022ba5520cf8637f4dd664bbcb037.nq.gz
    ├── 18ff73d50fea767e79e965daad082087c65a67aa.nq.gz
    ├── 192edf96a0ed122327414254fb96cdf456d30dce.nq.gz
    ├── 1987647f7aeac2e5f81ba670dd6d807ebcaa7703.nq.gz
    ├── 19af970b06ee3cf05358d49deadfd72a8404147f.nq.gz
    ├── 1a59b407529f4e5e12fc2d218ecaf3daaac43a73.nq.gz
    ├── 1a9163fac1a5f6e86811f7ca2ddba7b55df4a5b1.nq.gz
    ├── 1aa8e0f0f30297d5797578ea01b44281e88244f7.nq.gz
    ├── 1abdaee46619a075f4017ce527721569a59f39d0.nq.gz
    ├── 1aeb7fc06c19438a5bbcaced030a128f202a97e5.nq.gz
    ├── 1af51deea39a3bc9928ad048af37e62fedcc07b1.nq.gz
    ├── 1b4b4ea865ffa3945fa8e4a4e3aa19c4db2446ea.nq.gz
    ├── 1b9c7480fa33a1b5051b5a89df6de581de5f7e24.nq.gz
    ├── 1bf8b5157561df9f55f8d7c3e0487e42ccec97d6.nq.gz
    ├── 1c58849203a75f0f3d9e072946042bad5b2f6a7b.nq.gz
    ├── 1d4b5dbf2d2236a3dbdb5865e137bddd62c533f5.nq.gz
    ├── 1da3b487d48c7d58f0c8c3e6295116bd76040c2f.nq.gz
    ├── 1e0e11e33021e4dad9f3eb1196d4014a472d0ef4.nq.gz
    ├── 1e20bc30c4f793a463aafaa6459de9ecc9bd8ffc.nq.gz
    ├── 1e5da4d7e2939f4f0167550502fd4ddd973ddf84.nq.gz
    ├── 1e79902dfbf64d2e8a2b2d16a34d68b67c5ee15f.nq.gz
    ├── 1e93699d2a2e832e0aa80db5f4170323ef8d9467.nq.gz
    ├── 1e9d21bb8200a450ce1f07ce21b10182e535b8d5.nq.gz
    ├── 1ea4ae8a8be60e5b1ac5af8301cd601e480fe98c.nq.gz
    ├── 1ef10deeea437d8e0cea188dbca9311fea6d74fe.nq.gz
    ├── 1f06ba8dfbed066a7a89e97ab4b6b65b04631dbf.nq.gz
    ├── 1f2894de16dde0015dbfba06127fe41b26d75f74.nq.gz
    ├── 1f2ed2a9898ac9320b35ae7dcadc6017c1358cbb.nq.gz
    ├── 1f30d217bc232a08ab8de32ca24f30765dde501a.nq.gz
    ├── 1f6218322cd83651b8e12fa4a35e30d119afe135.nq.gz
    ├── 1faf762c71563868c6bb9bab4ff1ec9464745f10.nq.gz
    ├── 1fd1eaef70d8e2390fe96977202c1a2c852c1b49.nq.gz
    ├── 1ffcb11e1d12b8ec542c6b0fad3c2caa8b736440.nq.gz
    ├── 205cb1c6dea7d4d14702610c8649e1287cdf63f2.nq.gz
    ├── 20a29bad8f4f08671e2a70abc5f9ee7d017e4fcd.nq.gz
    ├── 20f9991536c192025495177b50bb0368e148e999.nq.gz
    ├── 2107a45d55bc94f81894edcd932fdcc3e2ed6121.nq.gz
    ├── 21142223105fcbd68d2fad3a047d73ee4d6e93e6.nq.gz
    ├── 2161c52a714b27a20f335ad0788e708b3b0f7cee.nq.gz
    ├── 2188708ed4575ec6385b5b24a261e5cf506f05b2.nq.gz
    ├── 2189612a5ffe960b096756d77366bcf2713f9883.nq.gz
    ├── 21cb8913e3db3a8ff284a07ab8f8e699b354a4d6.nq.gz
    ├── 21ddba20d8c4cf56be736e8d7d82724b4aefe8a7.nq.gz
    ├── 221508d43b71eabfc5d3715764785682e3538d95.nq.gz
    ├── 2289c111cc738637fd8fcf8333c1e66172c4cb9a.nq.gz
    ├── 228ff87ff20c585823f73248eec089c891753b48.nq.gz
    ├── 22a35964b03eab7bcff5486bec37496d2645a855.nq.gz
    ├── 237e3feacc3945bec2cc6b6e0a2c27f2beb2d889.nq.gz
    ├── 23efa42ac5696d631a3084a4fce13021e0e03a89.nq.gz
    ├── 24148b1eaf710c3d3b372a170288addf4dc5e7c0.nq.gz
    ├── 244f5b61d578ffc392487d69d44f532fbbe8a24e.nq.gz
    ├── 2450b171ffaece08a8526e76bd39572decb56067.nq.gz
    ├── 25072c373211b352f12aec1f574f5a1036f8a4ea.nq.gz
    ├── 253d40fe47b337a6250288adae4bdce5e4d8782b.nq.gz
    ├── 2543f509509e1fcfb114cfcc5bb63bde2eeb64ae.nq.gz
    ├── 25761cb5c959d2e00fcf73c913259d779034eaf3.nq.gz
    ├── 25817c21572287e7bd2a888e8f1885fc04f9681a.nq.gz
    ├── 25bf9d970a4ef178fedacf6e57c3445936fc94e7.nq.gz
    ├── 25e3c52541055533c9ac5e7cd2817ee2894b58f7.nq.gz
    ├── 2602d508c7df164ea7374e7165f024f492a1fe56.nq.gz
    ├── 264549f1875ca79ad8c559333fc15e95310f1d3c.nq.gz
    ├── 26ac5f9af4f7c4cbedebea7916ce7c82964e0a41.nq.gz
    ├── 2771c03a05907a721ade1420e63dbfd4139e6d37.nq.gz
    ├── 279a0b85385843234a8beba69098dc8c98a14b8b.nq.gz
    ├── 27af42fa6808fd12adb4e523d26f6c179ade40c6.nq.gz
    ├── 27b18ea4b06ab74bcbad96f739454448fd37af3c.nq.gz
    ├── 2857f1685ce4e869769ad9ba0d63e75a295509da.nq.gz
    ├── 28c0c172f66b5c83e5af162ae4142484fe50dfb2.nq.gz
    ├── 2901872268d7a05c19dafa8a496c695c91951b64.nq.gz
    ├── 2951453fca0739a601b34ec7f02893b4a6939991.nq.gz
    ├── 29846d4a2a05addacf71f06ee8541b804e6d5e75.nq.gz
    └── 29cdfe699808d711e8888d7b14a8006d573a16ae.nq.gz

6 directories, 200 files
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

## Source repository

[pytest-dev/pytest](https://github.com/pytest-dev/pytest)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
