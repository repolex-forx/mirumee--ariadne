# Repolex Knowledge Graph of mirumee/ariadne

RDF knowledge graph data for [mirumee/ariadne](https://github.com/mirumee/ariadne), parsed by [repolex](https://repolex.ai).

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
rlex download mirumee/ariadne
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 08c97a86577f012d510241c457eedf16b3dffdcf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 08c97a86577f012d510241c457eedf16b3dffdcf
│           └── chunk-001.nq.gz
└── blob
    ├── 00d7102fed1db0c173ae9e93c25f42836c255fb3.nq.gz
    ├── 00f49a48153c1fd68d77dc6cdd8918512fca17b1.nq.gz
    ├── 00fc4765d6c0fb97549ffc0a9054aba3607d78a1.nq.gz
    ├── 0105dbae6180f1409488e5a15aa5b61f4664bbfb.nq.gz
    ├── 010903203c987c652b97678bcab3f814dca580ea.nq.gz
    ├── 013d14a9d922d49532b4515c6d8a043f3242e69a.nq.gz
    ├── 01b59cd4dc0f92a1617c7fc3688a3d0466948f5f.nq.gz
    ├── 03633900f793489d4589fa5064d437bfe56f931f.nq.gz
    ├── 0610c51c894edd317a12be09b698b0e59bafc628.nq.gz
    ├── 06c1f850260d3390718006b95fab955424a2885a.nq.gz
    ├── 077ecd59b89200bfebfadf63c70ff3fbd3d8e299.nq.gz
    ├── 079a3e5ce5bad2081152390c7c58237d5502bb3c.nq.gz
    ├── 07da1f63bbce30223b077e9ad72cb49375d16d17.nq.gz
    ├── 07e100ee38802f3e4e69fd0ec8528fd33bb01f62.nq.gz
    ├── 07f549d73db8b0dd727c39e9c606e49c41d06693.nq.gz
    ├── 088d1deb995568da905d848100abf95fb6f3c60b.nq.gz
    ├── 0a47a73e73f82844b4878ef8bf1efb2e8f9d22da.nq.gz
    ├── 0a894dc562fc88f0cd230037428c3e3dadd9a263.nq.gz
    ├── 0aa347b4b3e0117fded9a2b40610b6f5e83cd18a.nq.gz
    ├── 0aafe8a2d425c547a85bb54f3dc1858f2603ab60.nq.gz
    ├── 0c3298b7fdd03d427447ced7a954d102d732ca9d.nq.gz
    ├── 0c6f16c074589ead600924682612eea3f3445de3.nq.gz
    ├── 0cea58353afa1692152ce11d86b1de3f07458bdf.nq.gz
    ├── 0d0b666d2f4d20a7227dc9c8dc0624fdefb116a0.nq.gz
    ├── 0e43887dde8e2d82314fd8af7de6100730e620fd.nq.gz
    ├── 0f01fc24b2aeddc5ff22873c049d142a8132ec02.nq.gz
    ├── 11eb11b1f77ca67d1b0aab82293196ef89eee978.nq.gz
    ├── 11fa2e4475d2318e324314c6d234444ad24d553d.nq.gz
    ├── 121bbdb71a999e9bab7b781ba8c6d39d0e2a67d9.nq.gz
    ├── 126669d7495625cf4be2e7b61e66eb00c9ffa457.nq.gz
    ├── 133332c16bdc9214e64331b4a79eb680508678b2.nq.gz
    ├── 146ae0419811a51f725ad424ba8f6e8bf5c159fc.nq.gz
    ├── 149e40c05e91dbaf9f31e82911a925f8a9b07be3.nq.gz
    ├── 158fdcd08f24c572731f80fb4a9a9c8f7aa47561.nq.gz
    ├── 15c83c744b3e6911b6eedbf86be8807dc324ef86.nq.gz
    ├── 163a98554ab16a745a75f3a695e4102aab8b6c16.nq.gz
    ├── 166dd3b6979dcce4cbcf9c6e17c8a620f558ae62.nq.gz
    ├── 167465ad41b95273930200af1751bd92e10ea7cd.nq.gz
    ├── 169524c1968e59e1c25a1be028a0c3322580d8a4.nq.gz
    ├── 18265b28f17d73349d6e99183e44737b3b82bff2.nq.gz
    ├── 1828dbecf4700a02f7f13cf3788105d3acfb6741.nq.gz
    ├── 190a946ce216409f23a1f7d3fc5f6d4e1b9c8382.nq.gz
    ├── 1a0d276055e1972bb6e261d9dc91ca1b00ba7c6b.nq.gz
    ├── 1a1a386bee18cc3f161eb0dae053077d56665267.nq.gz
    ├── 1ab98bed0448ea7be9a229c16bf796972924513b.nq.gz
    ├── 1ae5dcbae08c391a896ede3ed11d3b9f139e6daa.nq.gz
    ├── 1bb3c4c8887eb16b2d0ae44c2bb3035479cd9102.nq.gz
    ├── 1cdf6a7f9f50d7ce6e0f5c7c02c2a6ef60c8b45b.nq.gz
    ├── 1d233eee455fd9536b4dc148ce1b8d12f5261f4b.nq.gz
    ├── 1d86891f9fbbadf9ae73d19af2ca31d911e11b24.nq.gz
    ├── 1e1cccfd060b9ad8e51df618681e998ae5afade9.nq.gz
    ├── 1e9933db2a0f3863da991470bb8c2b62a30f78e6.nq.gz
    ├── 1f7c5c869728f86603616fb69699af7b67b857f1.nq.gz
    ├── 1f95568a86e5c1dd8a36761c1d99bdbe572a2c06.nq.gz
    ├── 20fd3d245e4f49a27b3a941b53c04e5b3f19dfa5.nq.gz
    ├── 215ca8ec147b5c09a0b7440b2212567bb2ce0333.nq.gz
    ├── 21a587674115c4bef0620a7f0c5358300bc99122.nq.gz
    ├── 21bb28f5794866c6a84275ee530735b6c015abf0.nq.gz
    ├── 21de1a1f6dbe20f4cb2483ed25ef38165c52dff2.nq.gz
    ├── 22b3a1b8dc37a5b0cfa1381daa84caaf1c093fa3.nq.gz
    ├── 239535e1aaad1077963d22698a7dc4a64debdada.nq.gz
    ├── 23bef7e91d335068037cd0e7ab0b7774a6acb9e3.nq.gz
    ├── 24e9593d30a23d5ac4409ea92b2b2350fd0cbf8b.nq.gz
    ├── 25cc87061a77a7b58a750c4fac3b3ad2aba27fed.nq.gz
    ├── 25ecba580d9529af32941b9103fee20fb86f5bbb.nq.gz
    ├── 261486504a4488c1d09ae42cbec8caaef74cd5c5.nq.gz
    ├── 262737378010031c1f180ae5353889932f09c656.nq.gz
    ├── 267d089641af97c8c17a7d06ae1fd46d2115d7ee.nq.gz
    ├── 2748b23005a7b5f5a29cf4c2d6806c962d8954e2.nq.gz
    ├── 27a5094cdaed57d8b9ce49266576d30122157ce9.nq.gz
    ├── 27e34b4171c7f833a2c0158832adec7f5d92d415.nq.gz
    ├── 2967935adc7ace75e55ad5c7b4404c556abdb1f3.nq.gz
    ├── 2a418e97c052d1494f70c724e0a73cb01d638ddd.nq.gz
    ├── 2a5fcefbc8faba0d6b6c9d107504d94bd3f6db10.nq.gz
    ├── 2aa8d279ab7cde404931dad2ec882a6360a696b5.nq.gz
    ├── 2b82014dd82cfb5b87310006796e9756cf9d8325.nq.gz
    ├── 2baa87f31f3545843a90f2fccc4e329febe98dd0.nq.gz
    ├── 2d3dda89227c3d53295d06ca268f2dd38c23d3a3.nq.gz
    ├── 2d5ebe7d48fc11d87444f50a475032b003c0c88d.nq.gz
    ├── 2dc8e5911b3bc551aca3dde0017637092e6ea4fa.nq.gz
    ├── 2ea9d04e7a1cb593ff780bb12d36ff1675d875a9.nq.gz
    ├── 2ed5816c1281425cd9c969e51168f863c472d523.nq.gz
    ├── 2f5691bb80ad11fa8312aa459a8e306ac559d3c3.nq.gz
    ├── 2f70917a30c234e1d90149f075c511a56bcaadb8.nq.gz
    ├── 302aa931c6d9748fc4380816cf1ca6f5e3c494ad.nq.gz
    ├── 306d4b6bfc12a54f87b65b7ef815a5ea50972686.nq.gz
    ├── 3074d8e5ea8aedbc6ba6331d775d74c2fc50735d.nq.gz
    ├── 310a939e49c87b99a7496a2d077ca4f0d93c0464.nq.gz
    ├── 31afe6a3a3b8a78b4916b767ce85e9fa390e06dc.nq.gz
    ├── 32da912267575a9b94b4bc13087268f1c7e0cf62.nq.gz
    ├── 33cf08b87bbbae5733306a70a6fded4f2427bde9.nq.gz
    ├── 344104d18be559c332b070fa51f728e05f7bed12.nq.gz
    ├── 349b8caeebc1a79a548ba80900908f9d94fd9fb6.nq.gz
    ├── 35ecd31e8366bea5d9cde840685745aecea349c5.nq.gz
    ├── 372d26dba8a7de80f6287ba9381637ce15ee9138.nq.gz
    ├── 3789112dd0f4b8401c4569f14e9c6e58e93a1f39.nq.gz
    ├── 37e0b73371819534788400e10270ff81091fce9c.nq.gz
    ├── 3815b72f39fb0a18c8341643fe679e4e7a2f1e80.nq.gz
    ├── 38d38c9e90ea9d535dd90eea2d73e17da229f6d5.nq.gz
    ├── 38d6eed96a55ffe2618f3576194b049c08b6e64f.nq.gz
    ├── 39b23b287d6e267cdd17a6eef226423ced940e1b.nq.gz
    ├── 39bc4afff36c6cba69618bcd0c6a5efa894a6d99.nq.gz
    ├── 39d464359732314e8b53a776a72fb9bd383c88ee.nq.gz
    ├── 3a2545039086176cd76e6b6271eb64124d728927.nq.gz
    ├── 3a2d9abd38e8cae7c2030bcc1931a318372a0f9c.nq.gz
    ├── 3af9fd38680b8d4332bc11d65f96ee94fa49baab.nq.gz
    ├── 3bc8e46df3a8fc4b4a10889175d68ebebed5a837.nq.gz
    ├── 3c42079dc8380bcd889ce037a5e5991065398c04.nq.gz
    ├── 3c9f6cf066671f0bbb556d429954f8738d9821e6.nq.gz
    ├── 3cab6bc47382d17ae9d297599dc24e02826ad220.nq.gz
    ├── 3e51367230215a7179956090fbbb386a364e14b5.nq.gz
    ├── 3f10b4172cbf7b62d7c9ff918b0ad18edd2a8d31.nq.gz
    ├── 3fb8a51a399792a4993c57f3525ae672f8c7d71b.nq.gz
    ├── 3fbc9a066cee459e0ed21ef59c48e93cbeb9c8cd.nq.gz
    ├── 3feab798cd584ccd67585167b557c971509ff52d.nq.gz
    ├── 400d969ba7adf4a86474a2190bd326c6e3d358fb.nq.gz
    ├── 4058a2a65306671cda17abdf30db75afbc9bfa62.nq.gz
    ├── 4145df6f3da7b3f87b9d62480d147ed4b90f0716.nq.gz
    ├── 42c6ad7cdf46864f3db8c646776faa73ba43b3d9.nq.gz
    ├── 440db147d96b327f8d6ac8b5d3d052cecc15e6e7.nq.gz
    ├── 4466f9604e43bc2b0120293090389a06d765d907.nq.gz
    ├── 44b9fd73f1abcb18c4a277ee04ca6b11df156b1e.nq.gz
    ├── 44d18d92fc774fa29753eb112dd6c1983918fa6e.nq.gz
    ├── 44e58124214c2af41fb12927422b1f3706ff1ac3.nq.gz
    ├── 44f085d80eb34ac7755606034012904a4064e11b.nq.gz
    ├── 45a40e678e550896df0f26c7a033265fdd788deb.nq.gz
    ├── 45ac4f181b723a0838951f4dc89c675f47c56a8b.nq.gz
    ├── 46a9c48b50e733b72bf9d02f8ce9db1838d8db1f.nq.gz
    ├── 47dc3e3d863cfb5727b87d785d09abf9743c0a72.nq.gz
    ├── 4803184bba0f35b47133ec91772c2f5eab220f99.nq.gz
    ├── 48372abe8ab8d3dde034672ee377c42a82554209.nq.gz
    ├── 484ba6332bea2c2a5ae3b1cf5c18e1a038019998.nq.gz
    ├── 4858bfed67ef8493b963b52c3f99db6ef2885823.nq.gz
    ├── 48b3302708f4474a4cda4b0d2dfe780b27dca2bc.nq.gz
    ├── 48bdf227f5dd245743d7ecb25ebfc8a1dd79f25d.nq.gz
    ├── 48dc5f9f28621ad3d9f824af40007dbf3be6a5f5.nq.gz
    ├── 4917f673317ce2801ee721ebd66d7c8904a8b34e.nq.gz
    ├── 492cc66982641bb9dd229f5e1546e85bc4d82f2d.nq.gz
    ├── 498cd8f9e1ccab8d3b0182e1d5002f1682fdba1a.nq.gz
    ├── 49909173fd570b9c65b19cc7f170f2ebc56a20c7.nq.gz
    ├── 49b9871d3301ff4a58c34056bc8878bd6e264460.nq.gz
    ├── 4a3aa552e8ad6020ea04e21c7f68996333825d20.nq.gz
    ├── 4abed25797c51c371190be63c115aebdcd5951d3.nq.gz
    ├── 4acca9a9222a4e5062ce0b5b6143c11910db1bb4.nq.gz
    ├── 4c030ad1149182c3747140e088dec386b3ad1d20.nq.gz
    ├── 4c8bf6b8c5917fbe8745110935b4ea5ba04aae6a.nq.gz
    ├── 4ce983eb6eefd10e0546fee94e16a8cfa8d95526.nq.gz
    ├── 4d42000a3abe37bbefa485f6ceaaff7e2378b2b4.nq.gz
    ├── 4dccd93f26d205fdf9015eaf18be88eca11f3479.nq.gz
    ├── 4e45a908bacdea0315a95bffb08a62e8c379c6eb.nq.gz
    ├── 4e5ff795b4973cd26ec525a9217ef9ebb0633d25.nq.gz
    ├── 4e783b6d6b908f20ed5c05141bd121a5f93c5c66.nq.gz
    ├── 4ece1778aa6f3f8bd342fb0cc5b39a90687ab118.nq.gz
    ├── 4ed313f10946731f765302cfc5bd33939cd58623.nq.gz
    ├── 503877e5c2665d315812d4ff1b4f2cd06d5cdbdd.nq.gz
    ├── 505539ed87c3c0140cf05d65074ee9ad25ad4ab8.nq.gz
    ├── 51075485e4eef50556e0712dcb10be9246b14de3.nq.gz
    ├── 5171aca6ee037cea57aec080770df68b370f0ec6.nq.gz
    ├── 51bbb2a5ae9159804c07b91322d9edbce9c13b32.nq.gz
    ├── 52ba9b056790bd08ac0e528d12e02a0c35f818d3.nq.gz
    ├── 532a376822ad36e4784e1464cb0051d58ba07c9c.nq.gz
    ├── 533dcdccb93d3285fd16216d5c9760e39f79d49e.nq.gz
    ├── 534e1c5b0773e9a6c003c22d56628a843aa65404.nq.gz
    ├── 53a42df89908a39ac1d07ba1f7a4c882ea8459a6.nq.gz
    ├── 53b959b4a4937613dfa9d174f0d15462ec3e6d6c.nq.gz
    ├── 543b1a27f9239bf686e382645db5b9fc97680c02.nq.gz
    ├── 545d9646f5f87c4074cf92f28920d8a603e1be70.nq.gz
    ├── 5514334f496c106ebba38ad41bbaad90d5b10e33.nq.gz
    ├── 56f3b6cb3e7e4e825e3f72b9035bc86f2bfdfa49.nq.gz
    ├── 57d2e3769b5ec69b8299efaec4f22889bad94d5b.nq.gz
    ├── 58056260606dcb1ace40ce76cd8bc8d9bddcd5c1.nq.gz
    ├── 583934e061ca6e2a7934684d3a67f7870439c786.nq.gz
    ├── 583cbfa8c45ce625be81da621155e500eb02bb49.nq.gz
    ├── 58b24d935909876de32ade5e2c07188fef971783.nq.gz
    ├── 5947afff1f5e5c60fb8a8d8b1c3583d19d4e4bce.nq.gz
    ├── 5969d264c4a75be18700209ea602c4c07e5f2004.nq.gz
    ├── 59b76e9c1201011a04c0d7221639633a9c745922.nq.gz
    ├── 5a6e45ff55c0da62a9ea0ca5a604c71dab8861d7.nq.gz
    ├── 5c053aa6238e76b310346d08d98d87788508f073.nq.gz
    ├── 5c0a58cb37700b852568e331fbf143ef0456a34e.nq.gz
    ├── 5ceeafb67540eb6c706edd8c6b8bb594b1408fa4.nq.gz
    ├── 5d30d057155b755e509c9cb431a4e51c8b1eb98e.nq.gz
    ├── 5d39d31ee18fe19d71217eb40f50b8895f81680a.nq.gz
    ├── 5da37ea281fc2f1a16341b552968d44c5f7e1d2c.nq.gz
    ├── 5de50887b6dfd900d9ad3b9ddf133dd18ca4520c.nq.gz
    ├── 6086c91dd1de12da401230b8cc89e13881fe2677.nq.gz
    ├── 6090b6d6097de1b7b73cd7d5418f5e00906b68ed.nq.gz
    ├── 60c0ffd4439f25a9206cba6a11d7fc46a3f14b24.nq.gz
    ├── 617e908ebb8ad0fc9d723c6e88f5c5d679faffbd.nq.gz
    ├── 619455aeada74f48bd933d2cb5d959656e56e903.nq.gz
    ├── 63d203b1bdadda56f11245b1b1e0f09f28c22570.nq.gz
    ├── 63f29d8c00cca0b5f6a3a6d5196db9f1e1635a0a.nq.gz
    ├── 65042c215a2fc2217fcafadf7e73da9e7ac1d77a.nq.gz
    ├── 655cb9fb3b25651230bd9e954606d7a798bb3fab.nq.gz
    ├── 6572b94898481eb66481824b6983a94aa6b00c17.nq.gz
    ├── 667985c36adc709bc4e5c3d2ffb44b605dc5252d.nq.gz
    ├── 667d08baf92b0f3dbc04b776504ad2ef5e9d755e.nq.gz
    └── 66855034e533102a4a4102efac6f245779bf0ddf.nq.gz

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

[mirumee/ariadne](https://github.com/mirumee/ariadne)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
