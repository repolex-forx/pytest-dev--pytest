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
│   │   ├── 07e870dc1494b923b6f6588330598164c391612e.nq.gz
│   │   ├── 172d46abd07e422bf3eb812c6b7048f150be1438.nq.gz
│   │   ├── 1830de2c136fb4cb6b07d53bec7fefa065bd8c2f.nq.gz
│   │   ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│   │   ├── 2b8f4214c30e20c6cddcf81069ef928b1e975e1a.nq.gz
│   │   ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│   │   ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│   │   ├── 448f1c0d9ccabfe5b63af81117cdb1b8a11bd750.nq.gz
│   │   ├── 4b395d56cc9e706fe9f9e9478626e6f38a02d8ce.nq.gz
│   │   ├── 4d21274a29f89c925922c5535166046e40c5a5b7.nq.gz
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 50c8218501f84ed3863d805a77b027e4c9351dc2.nq.gz
│   │   ├── 527bc472a8b1a68705bc6f38efd2914a16ea2ab3.nq.gz
│   │   ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│   │   ├── 60cdb875ed17f1e6ca0b189a4bc2cb12de5835f4.nq.gz
│   │   ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│   │   ├── 69fc6987adae78966a983eeecb8b7661d908cb48.nq.gz
│   │   ├── 6ad16936bbdcdf18a933f7a44d8438176d39ab6f.nq.gz
│   │   ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│   │   ├── 7dad3cb1577faa1e3f85d7acedf2261ea02aeaf4.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 87b4cb283ffa559cab6bcd1d86d6a9f61fb5ac0b.nq.gz
│   │   ├── 8c7ae7f7a5beb922443a73c9946f459ebd1cda52.nq.gz
│   │   ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── a056b41070b453da78a8eebeed83f7de18249e19.nq.gz
│   │   ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│   │   ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│   │   ├── b5955c59793b924a14e3ab185f38d690cef32fb3.nq.gz
│   │   ├── b83a3bcc80c85513b875866416306228a6a0e057.nq.gz
│   │   ├── bb6e9848b3a8770b199a085d3341d498bd7b50d1.nq.gz
│   │   ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│   │   ├── d4d213f83dca2d99fe29722ae32c94fd46f4fdaa.nq.gz
│   │   ├── d6f10d502cab1e488d212ae2f0eed98e6f447741.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   ├── e5eaf02e19116192693f563b41878cf89ad218ed.nq.gz
│   │   ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│   │   ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   │   ├── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
│   │   └── f9927e457b2f3f4a010287dcdecc180d66753c9b.nq.gz
│   ├── lsp
│   │   ├── 07e870dc1494b923b6f6588330598164c391612e.nq.gz
│   │   ├── 172d46abd07e422bf3eb812c6b7048f150be1438.nq.gz
│   │   ├── 1830de2c136fb4cb6b07d53bec7fefa065bd8c2f.nq.gz
│   │   ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│   │   ├── 2b8f4214c30e20c6cddcf81069ef928b1e975e1a.nq.gz
│   │   ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│   │   ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│   │   ├── 448f1c0d9ccabfe5b63af81117cdb1b8a11bd750.nq.gz
│   │   ├── 4b395d56cc9e706fe9f9e9478626e6f38a02d8ce.nq.gz
│   │   ├── 4d21274a29f89c925922c5535166046e40c5a5b7.nq.gz
│   │   ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│   │   ├── 50c8218501f84ed3863d805a77b027e4c9351dc2.nq.gz
│   │   ├── 527bc472a8b1a68705bc6f38efd2914a16ea2ab3.nq.gz
│   │   ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│   │   ├── 60cdb875ed17f1e6ca0b189a4bc2cb12de5835f4.nq.gz
│   │   ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│   │   ├── 69fc6987adae78966a983eeecb8b7661d908cb48.nq.gz
│   │   ├── 6ad16936bbdcdf18a933f7a44d8438176d39ab6f.nq.gz
│   │   ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│   │   ├── 7dad3cb1577faa1e3f85d7acedf2261ea02aeaf4.nq.gz
│   │   ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│   │   ├── 87b4cb283ffa559cab6bcd1d86d6a9f61fb5ac0b.nq.gz
│   │   ├── 8c7ae7f7a5beb922443a73c9946f459ebd1cda52.nq.gz
│   │   ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│   │   ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│   │   ├── a056b41070b453da78a8eebeed83f7de18249e19.nq.gz
│   │   ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│   │   ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│   │   ├── b5955c59793b924a14e3ab185f38d690cef32fb3.nq.gz
│   │   ├── b83a3bcc80c85513b875866416306228a6a0e057.nq.gz
│   │   ├── bb6e9848b3a8770b199a085d3341d498bd7b50d1.nq.gz
│   │   ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│   │   ├── d4d213f83dca2d99fe29722ae32c94fd46f4fdaa.nq.gz
│   │   ├── d6f10d502cab1e488d212ae2f0eed98e6f447741.nq.gz
│   │   ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│   │   ├── e5eaf02e19116192693f563b41878cf89ad218ed.nq.gz
│   │   ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│   │   ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│   │   ├── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
│   │   └── f9927e457b2f3f4a010287dcdecc180d66753c9b.nq.gz
│   └── repolex
│       ├── 07e870dc1494b923b6f6588330598164c391612e.nq.gz
│       ├── 172d46abd07e422bf3eb812c6b7048f150be1438.nq.gz
│       ├── 1830de2c136fb4cb6b07d53bec7fefa065bd8c2f.nq.gz
│       ├── 222a08ec03e1ea3879d4f96c6fe02a8fdec2f3b9.nq.gz
│       ├── 2b8f4214c30e20c6cddcf81069ef928b1e975e1a.nq.gz
│       ├── 2e36e2619fbe564b37a6657d4370b01e6805c8cd.nq.gz
│       ├── 365459295967b317b1c3765b2692ed29c3d10d95.nq.gz
│       ├── 448f1c0d9ccabfe5b63af81117cdb1b8a11bd750.nq.gz
│       ├── 4b395d56cc9e706fe9f9e9478626e6f38a02d8ce.nq.gz
│       ├── 4d21274a29f89c925922c5535166046e40c5a5b7.nq.gz
│       ├── 4f50ae13364037f581c417d9acbb56b1a30f69b4.nq.gz
│       ├── 50c8218501f84ed3863d805a77b027e4c9351dc2.nq.gz
│       ├── 527bc472a8b1a68705bc6f38efd2914a16ea2ab3.nq.gz
│       ├── 53dc59511391a8a7d4cf2f9a3ce0b0fb8adc31df.nq.gz
│       ├── 60cdb875ed17f1e6ca0b189a4bc2cb12de5835f4.nq.gz
│       ├── 6756416d694ed4aa25cd7298419feaffce584eef.nq.gz
│       ├── 69fc6987adae78966a983eeecb8b7661d908cb48.nq.gz
│       ├── 6ad16936bbdcdf18a933f7a44d8438176d39ab6f.nq.gz
│       ├── 7cb096373bc2a3312ed4c1ebdfde1a0d35a7dbb8.nq.gz
│       ├── 7dad3cb1577faa1e3f85d7acedf2261ea02aeaf4.nq.gz
│       ├── 7fabb3df69fa06f57b2b0c4eb2ec5ef7325b396c.nq.gz
│       ├── 87b4cb283ffa559cab6bcd1d86d6a9f61fb5ac0b.nq.gz
│       ├── 8c7ae7f7a5beb922443a73c9946f459ebd1cda52.nq.gz
│       ├── 98cd8edb7197309ab54d24d6d4e1ac4079071a63.nq.gz
│       ├── 9d5b313aad3f5610356385aa6b7f007362abc3c0.nq.gz
│       ├── a056b41070b453da78a8eebeed83f7de18249e19.nq.gz
│       ├── a127767da68a8f4fbee251fa9cbff657cfb5744e.nq.gz
│       ├── a94afc6b5efa730fbd647d75f1e00d7debe656b7.nq.gz
│       ├── b5955c59793b924a14e3ab185f38d690cef32fb3.nq.gz
│       ├── b83a3bcc80c85513b875866416306228a6a0e057.nq.gz
│       ├── bb6e9848b3a8770b199a085d3341d498bd7b50d1.nq.gz
│       ├── caf5bdbf8935f108fa0078aabedd7bed46a76ee5.nq.gz
│       ├── d4d213f83dca2d99fe29722ae32c94fd46f4fdaa.nq.gz
│       ├── d6f10d502cab1e488d212ae2f0eed98e6f447741.nq.gz
│       ├── e0bca8fe519e143ab320c4567fe5de9dad8cf6e8.nq.gz
│       ├── e5eaf02e19116192693f563b41878cf89ad218ed.nq.gz
│       ├── e80714d7017e74c41c0a6195518a3d0c760e5cd4.nq.gz
│       ├── f522838c77470b0f7d8bcdc7ed6b4e3f0407e422.nq.gz
│       ├── f741d6a01ee5441e957b577abf6b7b712fdb1250.nq.gz
│       └── f9927e457b2f3f4a010287dcdecc180d66753c9b.nq.gz
└── blob
    ├── 002133624dcc3950b99276e135b3402853596fd2.nq.gz
    ├── 002e1d374c15f9ef8d56d92fec79fafaec15dee3.nq.gz
    ├── 0033474693b6416cb848531f52702f2ac57d8167.nq.gz
    ├── 0042b274bd451468a3158612c91694b6e5477a5a.nq.gz
    ├── 005fa5c0bc83c3a9e7071ec11d90721013e12ad4.nq.gz
    ├── 0060ca747b03ee77a5e93c76557021f668a0c895.nq.gz
    ├── 006629093bffc5425fe24e2d5d39cfb35e93485e.nq.gz
    ├── 00848cc9d57856a395aa5d1d1aa4b8d07f9eff19.nq.gz
    ├── 008762cd202c75c6ab6de63342a7465b5ed06465.nq.gz
    ├── 009a6a302ae9557102c78654512f7af713f02f02.nq.gz
    ├── 009c2a9741f52ea562beded4b125ef34d94cd019.nq.gz
    ├── 00aa44c0bd006db4b3ea7eb078829579a60c5530.nq.gz
    ├── 00c9001d25cc330e4b75a74bcd91ded04d646311.nq.gz
    ├── 00d31b349c3649acb6318edb7fc65b72d8f87dca.nq.gz
    ├── 00d4c2135d2eca808035379c1d3c880176539f91.nq.gz
    ├── 00f121f04ed0cc61f993c958d37d5fee896a27f2.nq.gz
    ├── 01056d6840a6757b7546fdd93b009a2dbfb74633.nq.gz
    ├── 0115059759ffea2fccd603384d002bcb9293cf2a.nq.gz
    ├── 0138c6593b5250b7c1fe1c23a024549b48628190.nq.gz
    ├── 018d3e33e3a172be447c5a681e7292b2a54c6cab.nq.gz
    ├── 01e38b88cd187b74991a03c7b230af47500ab5a8.nq.gz
    ├── 01e3f9d29c33cca1cca5261152d9894acd4fead4.nq.gz
    ├── 01e6a4840c612755e93c1981a1b88009ac8b0a48.nq.gz
    ├── 022ff711dd0a0565b6907d058f73532ef1161ca4.nq.gz
    ├── 024c2998d84ff8a34b650131f636a16d73619f85.nq.gz
    ├── 026122d349366034a2a1776fa412950d3b9a6ac9.nq.gz
    ├── 0261ec1560dac302b8ce075d9f26e13ccd946fd3.nq.gz
    ├── 02679a75c31093b684890d718f62c5aeab6335c7.nq.gz
    ├── 0280ac654e2c6e61b492d184e98ed9eba835fae7.nq.gz
    ├── 02abe7659bb37b3f88973d840c98ebc68bbaba29.nq.gz
    ├── 02ae0c090281a7f8c02c64256361558435f497d9.nq.gz
    ├── 02b940b0c2d943ac27f5092ded14f98a40bbcd8e.nq.gz
    ├── 02bbabb6ff0b3f0bdb70d1f676b063ab77896160.nq.gz
    ├── 02d32e18f0c4ec77b79d37c49d247ceafde0a92c.nq.gz
    ├── 02d3750ee405b6faa11ab0baf58f657fffbdbf6d.nq.gz
    ├── 03075d75a7ef71fc10a28231284212af96c85c4c.nq.gz
    ├── 0310018350e7a16ad174e6bc0c945d4673bdd67a.nq.gz
    ├── 031aa649a550c5c19414f5bffdbac2f293490236.nq.gz
    ├── 032264086cf3fa3fcc858369fc5afcdef82293c2.nq.gz
    ├── 032f683ca211f396c7669011e0623dc3ad4b30bf.nq.gz
    ├── 033342e9983c58cfd0eb240643a3fd9c6b9e5fee.nq.gz
    ├── 033efe5c8f79a6ee06c04f457a9bd2e815cc3a86.nq.gz
    ├── 038c7c81e93ca47a681b7783b82e008ce78125fe.nq.gz
    ├── 03a6f703bbf6797f40c4bf62e56b2eb914b853eb.nq.gz
    ├── 03b6e8c83410c8a0a37ebdd961522192146ae4c1.nq.gz
    ├── 03e1b108b2111e2c54c8c5c81f50e5fa3891b87e.nq.gz
    ├── 03e27ece513650632c53582aa4299d405357746f.nq.gz
    ├── 03e68d6d3d619bc35c253ada39dbbd3793432149.nq.gz
    ├── 03e9b67800e22afae65ebf17e9ae31e1b6288cb1.nq.gz
    ├── 04247f88e404c1770d64289ca9d57a93cb0a182c.nq.gz
    ├── 0425a3632868ff777e2f6db0c273dab12771af9e.nq.gz
    ├── 0441c3215eb11667d312bbdc2e7ba79e89119981.nq.gz
    ├── 0442955f0a7ead98ea040943cab1cbb36fa7cbe0.nq.gz
    ├── 0448cf65cc5906aa272f15a44b58544b25468c32.nq.gz
    ├── 0455b72553365fa2e640a9595f30081a3e981510.nq.gz
    ├── 04707f473661ceb4470fb7d3c87bc3d3cc87b2dd.nq.gz
    ├── 047117f091e578f7234f1d3a2e0810a0569a8fa6.nq.gz
    ├── 0472ac3386704db86de152695900cdc48fcee570.nq.gz
    ├── 047f0d2a1b9ca8097b03714e72c4983ef739b86e.nq.gz
    ├── 0481c93dd2185ee08914de7f2a99f929a1b2710a.nq.gz
    ├── 048c69d2213bb5e99831e205de77b245d93b3c2d.nq.gz
    ├── 04afb6e101a68822f7581633d3ded98069f0d05f.nq.gz
    ├── 04e1bd0d20a6a2880fb532c9517a3d2a422e7ac0.nq.gz
    ├── 04e2ee19b490f175fc1f5ff8e7cb28517e7f2595.nq.gz
    ├── 04e6ae1058f38112d7540961506c220323ccfefd.nq.gz
    ├── 04fcbbd0d5b05480b4213aaef5d405fa1fc7571a.nq.gz
    ├── 0501ee20006837792bf333f4a46ffcda181989c7.nq.gz
    ├── 051a6da73876d4e960db024490107f5896fcd376.nq.gz
    ├── 05573ad68e7d596dff7a3a01ac5331b72d5b3ee5.nq.gz
    ├── 0578ffdd5d2edbf5adaff72ca1f117c69d18a099.nq.gz
    ├── 05801675179e8acc593aae0fce6ecb5f2b94e0aa.nq.gz
    ├── 05858eb854b49c95f94b01f339143e63a62e5930.nq.gz
    ├── 058de7b8e4cf3573bd53e85892bf928ea7d857b2.nq.gz
    ├── 05a0730e3ed5b5e27a84d6e2ae366df5ec8dd620.nq.gz
    ├── 05ac490bf389259112451a0d894aa09412f02426.nq.gz
    ├── 05b42c4ca557d029811b7eb6386df1ef9586b8c2.nq.gz
    ├── 05b8d477cd199feb4959a34d2f609354f6ca1d72.nq.gz
    ├── 05d547c213eb9a58fa5bc41b2bbd17db29a4ca44.nq.gz
    ├── 05e89de690734445395a8081ea0edc7867e1695a.nq.gz
    └── 061497b385ede5849fc4be26c39e658ec71b139d.nq.gz

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
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
