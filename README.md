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
│   │   ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│   │   ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│   │   ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│   │   ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│   │   ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│   │   ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│   │   ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│   │   ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   │   └── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
│   ├── lsp
│   │   ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│   │   ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│   │   ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│   │   ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│   │   ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│   │   ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│   │   ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│   │   ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   │   └── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
│   └── repolex
│       ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│       ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│       ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│       ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│       ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│       ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│       ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│       ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│       ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│       ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│       ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│       ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│       ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│       ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│       ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│       ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│       └── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
└── blob
    ├── 002133624dcc3950b99276e135b3402853596fd2.nq.gz
    ├── 002e1d374c15f9ef8d56d92fec79fafaec15dee3.nq.gz
    ├── 005fa5c0bc83c3a9e7071ec11d90721013e12ad4.nq.gz
    ├── 006629093bffc5425fe24e2d5d39cfb35e93485e.nq.gz
    ├── 008762cd202c75c6ab6de63342a7465b5ed06465.nq.gz
    ├── 009a6a302ae9557102c78654512f7af713f02f02.nq.gz
    ├── 009c2a9741f52ea562beded4b125ef34d94cd019.nq.gz
    ├── 00aa44c0bd006db4b3ea7eb078829579a60c5530.nq.gz
    ├── 00d31b349c3649acb6318edb7fc65b72d8f87dca.nq.gz
    ├── 00f121f04ed0cc61f993c958d37d5fee896a27f2.nq.gz
    ├── 0138c6593b5250b7c1fe1c23a024549b48628190.nq.gz
    ├── 018d3e33e3a172be447c5a681e7292b2a54c6cab.nq.gz
    ├── 01e3f9d29c33cca1cca5261152d9894acd4fead4.nq.gz
    ├── 022ff711dd0a0565b6907d058f73532ef1161ca4.nq.gz
    ├── 02679a75c31093b684890d718f62c5aeab6335c7.nq.gz
    ├── 02ae0c090281a7f8c02c64256361558435f497d9.nq.gz
    ├── 02b940b0c2d943ac27f5092ded14f98a40bbcd8e.nq.gz
    ├── 02d32e18f0c4ec77b79d37c49d247ceafde0a92c.nq.gz
    ├── 02d3750ee405b6faa11ab0baf58f657fffbdbf6d.nq.gz
    ├── 03075d75a7ef71fc10a28231284212af96c85c4c.nq.gz
    ├── 031aa649a550c5c19414f5bffdbac2f293490236.nq.gz
    ├── 032264086cf3fa3fcc858369fc5afcdef82293c2.nq.gz
    ├── 032f683ca211f396c7669011e0623dc3ad4b30bf.nq.gz
    ├── 033efe5c8f79a6ee06c04f457a9bd2e815cc3a86.nq.gz
    ├── 03e1b108b2111e2c54c8c5c81f50e5fa3891b87e.nq.gz
    ├── 03e27ece513650632c53582aa4299d405357746f.nq.gz
    ├── 04247f88e404c1770d64289ca9d57a93cb0a182c.nq.gz
    ├── 0425a3632868ff777e2f6db0c273dab12771af9e.nq.gz
    ├── 0441c3215eb11667d312bbdc2e7ba79e89119981.nq.gz
    ├── 0455b72553365fa2e640a9595f30081a3e981510.nq.gz
    ├── 04707f473661ceb4470fb7d3c87bc3d3cc87b2dd.nq.gz
    ├── 047117f091e578f7234f1d3a2e0810a0569a8fa6.nq.gz
    ├── 047f0d2a1b9ca8097b03714e72c4983ef739b86e.nq.gz
    ├── 0481c93dd2185ee08914de7f2a99f929a1b2710a.nq.gz
    ├── 048c69d2213bb5e99831e205de77b245d93b3c2d.nq.gz
    ├── 04e1bd0d20a6a2880fb532c9517a3d2a422e7ac0.nq.gz
    ├── 04e2ee19b490f175fc1f5ff8e7cb28517e7f2595.nq.gz
    ├── 0578ffdd5d2edbf5adaff72ca1f117c69d18a099.nq.gz
    ├── 05801675179e8acc593aae0fce6ecb5f2b94e0aa.nq.gz
    ├── 058de7b8e4cf3573bd53e85892bf928ea7d857b2.nq.gz
    ├── 05b42c4ca557d029811b7eb6386df1ef9586b8c2.nq.gz
    ├── 06e50e31f1e0c3adac1a5ad448c4d1b63292844c.nq.gz
    ├── 0710931354312054004ca4ff293de49f47c37b61.nq.gz
    ├── 0715cf087680464ece819632d61527928f5bd60c.nq.gz
    ├── 0725c39c209fd312afa9a5cb99a1299d4fbc8d7d.nq.gz
    ├── 0743f088eeb090bd09d80feaaa6769772c78641d.nq.gz
    ├── 07aa2296442881fdefcac271bdd720fb0089ec8e.nq.gz
    ├── 07c29762cbf10c19afaf25c2aaea5c8ba417e976.nq.gz
    ├── 07c2a5802b2864d395ac7f4c720749a8f2d42e02.nq.gz
    ├── 07c65ce995c13c5925a558bb35d624cb2e0d05d4.nq.gz
    ├── 07d6defbfcacd0ba79b975e8d0a405e1b0f5d228.nq.gz
    ├── 07f017b9be660ec23e42d0f58b77236655bddaa7.nq.gz
    ├── 083a5eaa2de5143ed6fbb7493241738f94392836.nq.gz
    ├── 084e59badb049c9090041054945de5a065faa7c7.nq.gz
    ├── 087ce286214d1eb78c029a0c1c76393b0b574f76.nq.gz
    ├── 088fa97e24029d5e1a365ba55e580110290c0c79.nq.gz
    ├── 08ae43dce4501c9643f85280eb3a6a89aaf07d51.nq.gz
    ├── 08c0b9f7a7584a6e634b6fed91afb0e50eef6416.nq.gz
    ├── 08cdc96f31b4214e2450daf7f6ac065b8f3d9cd8.nq.gz
    ├── 08ef4543dc96f7aa9a9b3c1d5d410972124e3921.nq.gz
    ├── 09023a38d2e25f665b3ebde9bb72c2816c0cac26.nq.gz
    ├── 091799fd467a660b045bf06f710add3c3557cb39.nq.gz
    ├── 095407e291f29bba491d634c2dea31e53ab64f9c.nq.gz
    ├── 09c6c7de34adfb22574b41f3693e8a6977e8333b.nq.gz
    ├── 09ce92669954e109275d19ac14b8fa644a026ea4.nq.gz
    ├── 0a0ba4c00520bc5d1a92c584189930a4abc92d1d.nq.gz
    ├── 0a8796b011a5ea85b382b5ade55514902c47a795.nq.gz
    ├── 0a94794cb8117bf516e09a124d3b2dc11f80f4b4.nq.gz
    ├── 0ab3b6f5a2ccc61893d6fbc42b8b0cc4fd6aab83.nq.gz
    ├── 0ac18015d6fd4eb6ea417600e9d79c04d2702f9e.nq.gz
    ├── 0ac94e444e58935b060097a6e9935a29eccc373e.nq.gz
    ├── 0b0ab1ee2f19b1045367c35581ce849ec9b9e2b1.nq.gz
    ├── 0b4beb1e192560cfd38227ed0668754548631627.nq.gz
    ├── 0b5cd31332f500f07da5ab63ee4d652980417019.nq.gz
    ├── 0b82cd8cce5fcab2b4ec990cd3822447cb16d55c.nq.gz
    ├── 0b83d42e82569d39c6807533dc3902fdd65a29a3.nq.gz
    ├── 0bd983d9369f13491b9e166d941490df57a107bd.nq.gz
    ├── 0bdd9775b48d9d6959b473766e20386f5dabf33d.nq.gz
    ├── 0c39ba775e35220103119986b766fe004c2ae285.nq.gz
    ├── 0c6c2e162881483ac38a7470b2a32436fc8eb9e7.nq.gz
    ├── 0c763a1a8e9aec7fb33fd3ab0be4f811e986cca9.nq.gz
    ├── 0c7b0090e2a8f3bfe998c78c5e324911cf734ef6.nq.gz
    ├── 0c9f8760bdbad4b5d0b1db69d664aee3bcbfe221.nq.gz
    ├── 0cde55ed6535028fa48104cc80ca5473bf5893cb.nq.gz
    ├── 0ce1f46c173d71fe83aa9b79bda09e25c05a4ba9.nq.gz
    ├── 0d172f8597581a65b0141efa3a604db5e398cb62.nq.gz
    ├── 0d525b95bf104bba8dd257c3b6f32d16f22c15b2.nq.gz
    ├── 0d715a4eda03604fdf7ab50fd0e078354406b85f.nq.gz
    ├── 0d80b938ca04cbb466403ee784ad13e1fb6b6204.nq.gz
    ├── 0dd785a3bf1eb11bc7b130747bc15f079ffc4a5e.nq.gz
    ├── 0ddbe53eaf8a929c6ae59fd7598f06678d5c8d22.nq.gz
    ├── 0df8582f6993f10199c9551ca3d835e48bd1d517.nq.gz
    ├── 0e051eb8d0d2e3c6265d946861c2472708853e63.nq.gz
    ├── 0e15c4e997f24bfa95ba3a5e7afc6caff9e8e3c7.nq.gz
    ├── 0e20c3c9c91a57d0ef08bdbe8453e6593384c02c.nq.gz
    ├── 0e27ad3a65d177e5eb1fa78048e7ce85d0918f54.nq.gz
    ├── 0e2e8e3b74d2a764f321046dc2af4fc5ad9d7a1a.nq.gz
    ├── 0e2fba51c8f330d6e407bb68180882fc48848f2b.nq.gz
    ├── 0e37affcf562cfcc3c59a93dbc367a16c9f1ae37.nq.gz
    ├── 0e7c600286e36089c3d698fa13892e4fa4d1b144.nq.gz
    ├── 0eb8066b0c9d990f34d957a5ca663292e98346b7.nq.gz
    ├── 0f20853b357087465e4228c7c9a4e29a7de3eb66.nq.gz
    ├── 0f536ffa6ac061e53c9e3448fc7a59d634325b0a.nq.gz
    ├── 0f5e2a5155f6266113aa5735c7a4d9216e17a7cb.nq.gz
    ├── 0f5ec152108153555c42abbcb53a024c79dfa984.nq.gz
    ├── 0f673f368b77b2ea9fb0f66bd76f5cf30ccfa1cd.nq.gz
    ├── 0feb34a17a92dbfabfe5636cdd79c17e3522525a.nq.gz
    ├── 10052dca073de9ce2ae58eb2c76c3dd8e5ddf407.nq.gz
    ├── 102feadbd2a45a39a9066e297aa7823f447d5131.nq.gz
    ├── 1032dc65302aa9a32c6e51f424c3b160506a61a5.nq.gz
    ├── 1062bbacf66f9cb575d8c7854810ff21cc0131da.nq.gz
    ├── 106c8518c31c67227c44690d3f3322a30a1d601c.nq.gz
    ├── 107c33c1eaf0b7ca88feeea222363a76733400b8.nq.gz
    ├── 1098b3095b6cc7a2460f45a7d1d33b9b2d2042c8.nq.gz
    ├── 10f13f795632ac70fa0c61e89ab896d000bd5146.nq.gz
    ├── 10fc3ac1093608583e0c6514e6dff72ef28207c2.nq.gz
    ├── 1133efbbda085818fbbfc6befc359e74c37e8573.nq.gz
    ├── 114553f5ef6ebd5e386bfa6bbaab10fc71d48d20.nq.gz
    ├── 11514ff46e986b74a68d67b14b2b183b25ab4dfd.nq.gz
    ├── 118e3866389ab664d74344cd9f1fc796617a1248.nq.gz
    ├── 11b068a0c48134253699e1d557daec63ef4b04c7.nq.gz
    ├── 11b665914b4e4c296b60e8c5539af2dcc363b5fc.nq.gz
    ├── 11e55618d9f878872b2a832c0342dfebdae36651.nq.gz
    ├── 11e8b1e1a1689f0e1baf7f730df78d3921e004e8.nq.gz
    ├── 121d45d41cdeb63c26eb7d5e4e797cfbd11c275e.nq.gz
    ├── 12581eb7afbc231e02476c125ccb9e289e6f3024.nq.gz
    ├── 12970e6d715de061c2200af3b1a9a63ea647990f.nq.gz
    ├── 1307de5438cd9cd47e5279e7eb6a00ee76fe7a60.nq.gz
    ├── 1340cae9980d2a67e75e4451e095d1a4fd47907a.nq.gz
    ├── 136b7e49468ab928d9d14848607125d9c8b63a6f.nq.gz
    ├── 1378544ba5ab316eb30d3953a07307fe6683ae01.nq.gz
    ├── 13a8ed7b0c0a0768ffd7ec012a57e57bc16d16c4.nq.gz
    ├── 13c1fc64658fc25b52abffde347f9b810686e8ee.nq.gz
    ├── 13c6a6d9afef50a03d032186689327ea518a78f8.nq.gz
    ├── 140bd39f27be2d01104b15b0275b270313e6a3b8.nq.gz
    ├── 143556a0557f7d8dd11aebd8cbf4f5a675c168c2.nq.gz
    ├── 146c61e8a7e9c880890faa5d1d4ae9fe8354bb96.nq.gz
    ├── 149691c4f766503bf738a35981669af3161594bb.nq.gz
    ├── 149baa43542ac29e0e711ead9331c2abd9294eb6.nq.gz
    ├── 14a2ee1d0fd160c03fc18bdd07c4a7d6014e9700.nq.gz
    ├── 14d7cac945c8ec07ab972c5559904a401f970923.nq.gz
    ├── 14e2bc81c9b237b378ea7539ed52b74f3db2f079.nq.gz
    ├── 151881567623b8a95719a914b153a67c20509fef.nq.gz
    ├── 1519caffe83506ae989b00cf8b52bb749eebcd36.nq.gz
    ├── 151e75e0533fb95a56a8dfd71c65b021beeff4e8.nq.gz
    ├── 15384ee25955d3ccf9156230f0f9c2ef723429e7.nq.gz
    ├── 153c2409baa525984d8c826665590a5d345d66bf.nq.gz
    ├── 156a88934ca1b4bf41ee744ffb78f799a92b4143.nq.gz
    └── 1585269a635ff5cf4135d03ab8fba10fe1002b40.nq.gz

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
*Parsed on 2026-03-22 by [repolex](https://repolex.ai)*
