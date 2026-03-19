# Repolex Knowledge Graph of rack/rack

RDF knowledge graph data for [rack/rack](https://github.com/rack/rack), parsed by [repolex](https://repolex.ai).

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
lexq download rack/rack
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0232e227b1cf3e67fbb82b2198311fa8ca618fbd.nq.gz
│   │   ├── 0cc2e00b22dffc33955ef912569f01e515a406e1.nq.gz
│   │   ├── 47a1fd73fc77f094573f4215b0fc884f4ac1c03c.nq.gz
│   │   ├── 488d67988ddfb7e13ad2f58272ee04809612cafe.nq.gz
│   │   ├── 52808700e0ade4225625c6729529e13a6b31cc2f.nq.gz
│   │   ├── 65044344e4780d80b409f9ba27df41b6307b5ff5.nq.gz
│   │   ├── 85684323f8f58409e717af91e446d257d496f8b8.nq.gz
│   │   ├── a176b537d9e083033819efbafac3271bbbde23fb.nq.gz
│   │   ├── ba8c6c2b3a5d03675ce7efc0e2308225809a74b8.nq.gz
│   │   ├── bb5f3555bd12b9065112353e829298b3b5623ceb.nq.gz
│   │   ├── d0a2084e64f394068a80ea073e1910d7c3ffa44b.nq.gz
│   │   ├── e7e064611e1004ec62b593ec993a06d967d6c72e.nq.gz
│   │   ├── e95f187b11c5f342d2de00a38ce10bc7ad435409.nq.gz
│   │   └── f5c09684fb93dbe76d7b9d0a0411d32ba5d66d04.nq.gz
│   ├── dataflow
│   │   ├── 0232e227b1cf3e67fbb82b2198311fa8ca618fbd.nq.gz
│   │   ├── 0cc2e00b22dffc33955ef912569f01e515a406e1.nq.gz
│   │   ├── 47a1fd73fc77f094573f4215b0fc884f4ac1c03c.nq.gz
│   │   ├── 488d67988ddfb7e13ad2f58272ee04809612cafe.nq.gz
│   │   ├── 52808700e0ade4225625c6729529e13a6b31cc2f.nq.gz
│   │   ├── 65044344e4780d80b409f9ba27df41b6307b5ff5.nq.gz
│   │   ├── 85684323f8f58409e717af91e446d257d496f8b8.nq.gz
│   │   ├── a176b537d9e083033819efbafac3271bbbde23fb.nq.gz
│   │   ├── ba8c6c2b3a5d03675ce7efc0e2308225809a74b8.nq.gz
│   │   ├── bb5f3555bd12b9065112353e829298b3b5623ceb.nq.gz
│   │   ├── d0a2084e64f394068a80ea073e1910d7c3ffa44b.nq.gz
│   │   ├── e7e064611e1004ec62b593ec993a06d967d6c72e.nq.gz
│   │   ├── e95f187b11c5f342d2de00a38ce10bc7ad435409.nq.gz
│   │   └── f5c09684fb93dbe76d7b9d0a0411d32ba5d66d04.nq.gz
│   ├── lsp
│   │   ├── 0232e227b1cf3e67fbb82b2198311fa8ca618fbd.nq.gz
│   │   ├── 0cc2e00b22dffc33955ef912569f01e515a406e1.nq.gz
│   │   ├── 47a1fd73fc77f094573f4215b0fc884f4ac1c03c.nq.gz
│   │   ├── 488d67988ddfb7e13ad2f58272ee04809612cafe.nq.gz
│   │   ├── 52808700e0ade4225625c6729529e13a6b31cc2f.nq.gz
│   │   ├── 65044344e4780d80b409f9ba27df41b6307b5ff5.nq.gz
│   │   ├── 85684323f8f58409e717af91e446d257d496f8b8.nq.gz
│   │   ├── a176b537d9e083033819efbafac3271bbbde23fb.nq.gz
│   │   ├── ba8c6c2b3a5d03675ce7efc0e2308225809a74b8.nq.gz
│   │   ├── bb5f3555bd12b9065112353e829298b3b5623ceb.nq.gz
│   │   ├── d0a2084e64f394068a80ea073e1910d7c3ffa44b.nq.gz
│   │   ├── e7e064611e1004ec62b593ec993a06d967d6c72e.nq.gz
│   │   ├── e95f187b11c5f342d2de00a38ce10bc7ad435409.nq.gz
│   │   └── f5c09684fb93dbe76d7b9d0a0411d32ba5d66d04.nq.gz
│   └── repolex
│       ├── 0232e227b1cf3e67fbb82b2198311fa8ca618fbd.nq.gz
│       ├── 0cc2e00b22dffc33955ef912569f01e515a406e1.nq.gz
│       ├── 47a1fd73fc77f094573f4215b0fc884f4ac1c03c.nq.gz
│       ├── 488d67988ddfb7e13ad2f58272ee04809612cafe.nq.gz
│       ├── 52808700e0ade4225625c6729529e13a6b31cc2f.nq.gz
│       ├── 65044344e4780d80b409f9ba27df41b6307b5ff5.nq.gz
│       ├── 85684323f8f58409e717af91e446d257d496f8b8.nq.gz
│       ├── a176b537d9e083033819efbafac3271bbbde23fb.nq.gz
│       ├── ba8c6c2b3a5d03675ce7efc0e2308225809a74b8.nq.gz
│       ├── bb5f3555bd12b9065112353e829298b3b5623ceb.nq.gz
│       ├── d0a2084e64f394068a80ea073e1910d7c3ffa44b.nq.gz
│       ├── e7e064611e1004ec62b593ec993a06d967d6c72e.nq.gz
│       ├── e95f187b11c5f342d2de00a38ce10bc7ad435409.nq.gz
│       └── f5c09684fb93dbe76d7b9d0a0411d32ba5d66d04.nq.gz
└── blob
    ├── 007437b6a3f108034dbfae294bdcc9b8e63afc79.nq.gz
    ├── 008d9c43fa0a1bebc1aa6c79af0ce1f0dc0d18b6.nq.gz
    ├── 00d58153d9471c1f16d5e54de5e517e69b617c82.nq.gz
    ├── 00fd68ab85084bdf44c177fd34fb9cac1c101e44.nq.gz
    ├── 010cc37b706c5bf4d2a8455be2c846f443317bd1.nq.gz
    ├── 01376d02fe5c4fabe5f4dcceaebaa236fd05df75.nq.gz
    ├── 014e22fc9961b82b4d04e9dec4c3df5f0497e008.nq.gz
    ├── 0176efc8b30d00fc8c52ce48e388a6a93a7d6531.nq.gz
    ├── 019943641abfa7047482ab6e3252a4441efa7d22.nq.gz
    ├── 019efde75e9db519ffa2651196ec90f390c4b120.nq.gz
    ├── 01c9603ee22304b769714745beab4b0ef853c438.nq.gz
    ├── 01fc321c7212ffab8c454d0eb1105a1c457a069f.nq.gz
    ├── 025d830d9d4ea0cf60f4a8e2b703a087d6483c17.nq.gz
    ├── 025fa95dbafd439a80bdbdd716b160c2266e8b94.nq.gz
    ├── 0272968f423ae09f4219fd95c19663de0a072059.nq.gz
    ├── 027d7e4045fb87d8f718f74c5ec92f66a2405ebe.nq.gz
    ├── 03a8e017c5b1ff8d50157cee0b3d47081c491cf8.nq.gz
    ├── 03cac1b2860aa701493ec09f4e1b62c8ceb40a3f.nq.gz
    ├── 03d4ee79e8566467a64283dcd1d7b7508725fc02.nq.gz
    ├── 040be2eff9d5d2eb8073565e5fbe5af7ba1a8a62.nq.gz
    ├── 044d4db375ef4b1740720432247ca4703dee0ea2.nq.gz
    ├── 046ebdb00ab1f68add574a98ac0fcc62d97db1e7.nq.gz
    ├── 04b103e2583fc41157a2720b6b04ed8c1643df5f.nq.gz
    ├── 04c22fd614adbb70ac10994fca34d7d33d821537.nq.gz
    ├── 04fdd48839864f39c4735074875af33ff69524ea.nq.gz
    ├── 054ad3d00279af18601b64f8696b4110fc22cda8.nq.gz
    ├── 056084f36db37aef49c9f39de286bcb44e6e09b9.nq.gz
    ├── 05771cb03e6690160d713229c5ab02cf61dc5c03.nq.gz
    ├── 05ce5041b6cae8c5d901fe32512630e453ed0e56.nq.gz
    ├── 063687a094aae61c490b53a50e354ec9de8d4006.nq.gz
    ├── 06918616dfdb701832668bd8422dface154b07fa.nq.gz
    ├── 06b7cada7a8d7b665714d1c3544eff601b351b10.nq.gz
    ├── 06dbc6aa5f8b75357982df77484219b574ccbde6.nq.gz
    ├── 06e75c25fcb5cb9f54945e95e5e7e233db4234b7.nq.gz
    ├── 0722f0a0e958a50a7033fa43f9ff55a23980de93.nq.gz
    ├── 0729c3f3c39f7d29975efff20fabd984f69241ac.nq.gz
    ├── 074133d5fda7d92aaa3033cd7b32f30719933819.nq.gz
    ├── 078b0970493b1bb653c2fd54ba6515a5fa1bc537.nq.gz
    ├── 07a4c56e72ce7f5bd81160d9f7851fe494f826e6.nq.gz
    ├── 07e60388069f7926eb98c91e310217b5acaa0fb9.nq.gz
    ├── 08021d0ca956dbe5f0e913e407ae5735f008f810.nq.gz
    ├── 081212d65f26a1ff37965b959dce915747205e02.nq.gz
    ├── 0839b2e9412b314cb8bb9a20f587aa13752ae310.nq.gz
    ├── 08700a761e8d79ce3803687a7e58a5c1427de43d.nq.gz
    ├── 089623f91d934ec0a958df901745f6c5c726697d.nq.gz
    ├── 08e2b358db4ad8f234e6224b19cd442b3be1b579.nq.gz
    ├── 08e3a3f7e2b0b97acfa45163f3f861738aab6bcb.nq.gz
    ├── 091a2debce1d840445375efeb76cab88bd74c357.nq.gz
    ├── 0920c4fb0c127121f458abfb9d9a18f3bb8ce6a5.nq.gz
    ├── 0945d3227814b952ddf4993590569c84f04ef8c6.nq.gz
    ├── 09eb0afb84ad48b7d6018771f5c1dacbbca1d953.nq.gz
    ├── 0a2f8ee81c87679af8d271eaa5634356af3d682b.nq.gz
    ├── 0a332df70f2a6919c530ed84fbd93dbe79f3a66e.nq.gz
    ├── 0a6d9ff11b5b0d21c67b6fe1de3018cea183d1ab.nq.gz
    ├── 0b94cc73a157b52de72fb9706079c3c2947d972b.nq.gz
    ├── 0b9c3d24a2d493219e79dfd9f86bd8100bb61e71.nq.gz
    ├── 0bf9690e79c0419875886f57425f10d8bd47ebd3.nq.gz
    ├── 0c1e1ca3e1d296af3d81d45307ce5b5c826cb992.nq.gz
    ├── 0c89b02a25eb31c6dff9df42581b7f12bfb80897.nq.gz
    ├── 0c9d060b931f1f8a624751ed5a600b90d50b292d.nq.gz
    ├── 0cbb54478a4220734cb8407d60be16834a23a033.nq.gz
    ├── 0cbd3732e0ebb4be47042e43d8489cfb5f225ca0.nq.gz
    ├── 0d0aa8f7fabe81b4b6ecaa66875bdeba59ff29d9.nq.gz
    ├── 0d1049e13cd1c1e404efb3562f20e0a025df843a.nq.gz
    ├── 0d3f961cc4f7a5dfa9c2627d8f3e3538eb3aee13.nq.gz
    ├── 0d420193d86fa6c358a0dab5272ecc2db9eab480.nq.gz
    ├── 0d8125a4ac572d1e66457479ee956c5849c8e412.nq.gz
    ├── 0d8da25078bbfb28fda8f6b7d770dbd0db1ae62d.nq.gz
    ├── 0e0ad35150ce877c5acf4c2e712531064abb99ac.nq.gz
    ├── 0e143395b999b3431a42acdc16367dc647a7baa1.nq.gz
    ├── 0e56bf538561ea09913c15ff4565f6a091194530.nq.gz
    ├── 0e7de841503714ee113e0b0f6f496cfbcb7fa433.nq.gz
    ├── 0ea1998de1aaa478e20f71cdb18a1f7f40ab62a3.nq.gz
    ├── 0ea78a1d9b998b9b35cf63a30ce178c1c6d3eb49.nq.gz
    ├── 0eb243cc6d0a8ea4f8e890a45a7d79eb580b9229.nq.gz
    ├── 0eed29f4713f58ee64c1d8dc3cb08084ced2a5b4.nq.gz
    ├── 0f27c859fb69a88fb018da78189fad7cd5462277.nq.gz
    ├── 0f5cbf729395dfd0f93f27a44e2319c0f0768b45.nq.gz
    ├── 0fb5b8f0c7c6890f2ed25814764fd45a91519675.nq.gz
    ├── 0fe7932025e9fd9f2f4edbd5491bcc999365e476.nq.gz
    ├── 10070f11380c09ab08ce34b07e676f1d248f2db4.nq.gz
    ├── 100dfd11947bb326035ff6073dedb8c38f06df4b.nq.gz
    ├── 1018af64c76045519845e62862eac2faf7861b5f.nq.gz
    ├── 1037c9fa369b716d951f32581d34182e8504fc2e.nq.gz
    ├── 10576cd4106d464c86199ba7bc3279569e5e2edb.nq.gz
    ├── 105c76747f92f4d333ee46ec58a929014c2060ad.nq.gz
    ├── 1089a690b1ad5927412554e5a6435f9012b217c7.nq.gz
    ├── 108b9d05e7ed1ce03e9478d4c70db7a068c851b0.nq.gz
    ├── 10a478326248a94c1ff8fb3e3e9ec2e138086d44.nq.gz
    ├── 10d7dbc8ebd4b87ee63a3de2b275b109bc984cb3.nq.gz
    ├── 10e561dec1ef6c049bc72c574eb39f2f67b2c457.nq.gz
    ├── 11932b1784611e723591a23f9a1dc53686074efd.nq.gz
    ├── 1199f2f18e42db06a53b943174b05417cf28c24b.nq.gz
    ├── 11a46fbe5b008de13c217a8019529c0e0eb54527.nq.gz
    ├── 11b4c6e0f6ed203df2760f027c3d4b89a5e7ba8d.nq.gz
    ├── 11dab9797dceaba1f0610d5dfedb2a6d62d71d21.nq.gz
    ├── 11e64d61f63754b6fafd68ea6be739ed78d9ac91.nq.gz
    ├── 121e5a266b7666d4d009bab04c6b9b3649a95903.nq.gz
    ├── 121f85fc91be52541bd689d2f4854718ae0c9fd6.nq.gz
    ├── 1263778df2d458483d78060efe49e4f9fe151bd3.nq.gz
    ├── 12c047fbeebb8f791250c1ef5af47c80ee9bc758.nq.gz
    ├── 12f2158196b5d69592fa7853a4023552cd76c813.nq.gz
    ├── 13365935b1b5b8d679598823f776f1b9ee5a4a89.nq.gz
    ├── 1371ca9d465aaf64cd411d47c785ade0a05a839d.nq.gz
    ├── 1375af317bda6ae0c402162f2277d602a69930e1.nq.gz
    ├── 13f37c1f303d37b1af64c16a566a935e20c5fbdd.nq.gz
    ├── 1414d19a51078963f0b642b22de8c040d2b75888.nq.gz
    ├── 143ad30a68eaa62a7c2349e727149da6a927ac15.nq.gz
    ├── 14594a20cbdb7a51db14ff9c0213ca30d769a43e.nq.gz
    ├── 14af7b3bd741bceebe8fa275a6a341624ff799e5.nq.gz
    ├── 14c3da45a58d0212de9bd6e908a184d5e56fdfcf.nq.gz
    ├── 14c3e54d350f6f6da300a57d574eff3ccfa35ef8.nq.gz
    ├── 14debe92b06fb544ac19b2f7e4ff99e91cfb3a7a.nq.gz
    ├── 14eeddd3629145b8e538f4dab227c40df0d92978.nq.gz
    ├── 1500b06ab1dfc9e5725fb002ca3da43f85388d16.nq.gz
    ├── 151bc424daf5977db95550c2f648d3d233331ac8.nq.gz
    ├── 155dbfabacb2b4a931cd0b0cd04a669511722e78.nq.gz
    ├── 15a1ab543e88c8b4bc329606fb8ce43edd80afe7.nq.gz
    ├── 15af1ac22158ebf44107c8875865672f15e165a0.nq.gz
    ├── 15ecc5869e30abb1bce02efb9a7a106da48e9251.nq.gz
    ├── 1635efa4b4b35440057cc1fa64352a8aabcc4ae8.nq.gz
    ├── 16481ab9082047152b65d00eb02bf48c7f5e3363.nq.gz
    ├── 165e66b38546d4fc62433bae448652a9bc12d2d4.nq.gz
    ├── 168e8f83b2c921fffeb4f892d8498d26fe5d96c0.nq.gz
    ├── 16e56b3c1758ec266ff333bf6ef75da30b2d7fe3.nq.gz
    ├── 16f0a6649e0f0c646f16ff6d89a5a907a23389cd.nq.gz
    ├── 16f5f283a4e1ba22fb364052f3e75f6d7997be31.nq.gz
    ├── 1739d659392c815fac70b59a81d6355f8828eb2c.nq.gz
    ├── 17b4a3497cc0a4f808db2d77584a8960c22a944d.nq.gz
    ├── 17cdb3e55cd91855ee980f112eb2f53e3167cb06.nq.gz
    ├── 17d17dfdb378149c3938f9135b54bb207d453134.nq.gz
    ├── 17f47649422c91cacead9fea634f2d8abad3cb29.nq.gz
    ├── 1808660cda251625792cf4d40b608f099305b5f7.nq.gz
    ├── 180ce46eb05444cdfd80a9afd50b8be7ae21972f.nq.gz
    ├── 1810ee9e7f2472efaf63fb26e13be11879278f68.nq.gz
    ├── 1841beb370f333398bb02c60cd6d9abaa06a86e9.nq.gz
    ├── 1868985750e36dd07f2ef31069884774dd0306af.nq.gz
    ├── 18af2b2347e8919d4b087cc448a4d088a658c369.nq.gz
    ├── 18bc84005bff671d5ae857b869e7979eadc68cc9.nq.gz
    ├── 18f9a76abf3d235191f783b5e3b3e8cc7e36094d.nq.gz
    ├── 1920685fc625dd0649b694966b133fb2232f0cd6.nq.gz
    ├── 1922402c8c26776f881d56058e35d2b1e5e6d1e6.nq.gz
    ├── 192f260f09ff8a922f820dc58a82cd4725fb3ebb.nq.gz
    └── 1964934159dadc1bce060cc40023baa27b3dde72.nq.gz

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

## Source repository

[rack/rack](https://github.com/rack/rack)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
