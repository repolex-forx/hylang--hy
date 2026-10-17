# Repolex Knowledge Graph of hylang/hy

RDF knowledge graph data for [hylang/hy](https://github.com/hylang/hy), parsed by [repolex](https://repolex.ai).

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
rlex download hylang/hy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 219db3cf7b01353c1688af89aef3eb473905a965
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 219db3cf7b01353c1688af89aef3eb473905a965
│           └── chunk-001.nq.gz
├── blob
│   ├── 022c543476dc926b8845a7a75a5b038a8ee979d8.nq.gz
│   ├── 023cd993ab6181290d9a4b853c7ecceac24e25be.nq.gz
│   ├── 0439703034a5ea395db3e0a303513dbd03aebf82.nq.gz
│   ├── 05cd0d4e537d5e02910a2914434b5cb3a700cfec.nq.gz
│   ├── 068827d1e64a4f57a82d325f3109af2b09964d06.nq.gz
│   ├── 0b9b3c37ad7cf306ae206456caa5eddfcade0c34.nq.gz
│   ├── 0bd404966aaa316fbceb5b6706711d3918cc827d.nq.gz
│   ├── 0e058ba9a46b84c7adf8e695bd83f730b34ae707.nq.gz
│   ├── 0e259d42c996742e9e3cba14c677129b2c1b6311.nq.gz
│   ├── 0ec1683e23b1c786672797013adadd5160f518d4.nq.gz
│   ├── 0ff21ce0955cbf9941851e476a80aa0b9b738888.nq.gz
│   ├── 110727f1b98c522238aac251bc91484dca6a1b4b.nq.gz
│   ├── 1122aae4bc456b374ab3e84ad4ec5f722edabe96.nq.gz
│   ├── 118b8ae91b62750150b3629d84c6e5353e8a1e54.nq.gz
│   ├── 1194cbb6beca2aec234cd79f79d0352343475aae.nq.gz
│   ├── 11b6e05fe4021646c4921334f6219320220786ca.nq.gz
│   ├── 128643ae1745efe30eb5321e63485791a2f5ee4e.nq.gz
│   ├── 1570db62db265a1095b17a589b7e688433a5ddd2.nq.gz
│   ├── 181d7ecd65e79c2c540e451941b23a952a54fef7.nq.gz
│   ├── 188bf6bcee9257bdff2e62aac2ccec1db7140b89.nq.gz
│   ├── 1e255b360afe6b77c1923d8ad1a81401c67ed270.nq.gz
│   ├── 1e688f7f786fb2f46de0088471dc2d297c871026.nq.gz
│   ├── 20f7df2794338721edbfb2f48091adf007032041.nq.gz
│   ├── 28ddd3c2e7e4289f3c85aba77be777f5e3ac4879.nq.gz
│   ├── 2902aa116580d9b11bd61c70f043f5dfb55b8c97.nq.gz
│   ├── 2b46ff451214bd9147b46fd01ee8e17bcadbe6c2.nq.gz
│   ├── 2b8094eae670080d82fdb2c11a468dcd4fd964dd.nq.gz
│   ├── 2d27712284562ac31d19332178c5f40757200a49.nq.gz
│   ├── 2d55c2b851b07364bfada5e1f199149930d5f7a6.nq.gz
│   ├── 2eab75b487d60b7d45df4145aa6008cda5621267.nq.gz
│   ├── 2f4951dcf22871cb954b5f2f02b68352edf3e2dd.nq.gz
│   ├── 304afb74eb4620f3b6025c3b590b7dbe79c5da21.nq.gz
│   ├── 306d46cb845792867223fd3d10706036f9009f5d.nq.gz
│   ├── 38b9044176baa481f9e5d4be7aa0a3a53c2814cb.nq.gz
│   ├── 392c1365179cf36a4d3a6215274f27d8f8371e3e.nq.gz
│   ├── 3b9c867fbf833f844fdd98bc359ec554d07680d1.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3e74462dbcb6697c9fa652c39b6bdab711646c4f.nq.gz
│   ├── 3fd7b4db009dde240b777031f399c2a3e8794151.nq.gz
│   ├── 41981f689439e6b93e0f3fecbfcf3303ac5ec5a9.nq.gz
│   ├── 42859f65653e1b915817640239a2e761adfec5e2.nq.gz
│   ├── 44d9e46fa2902db96dce60c42de00ab0a6445615.nq.gz
│   ├── 4572241689c1bfecf1be3bdda96de0533fdcd1bb.nq.gz
│   ├── 462748f8fcd44ce0e31365a733708751963078a6.nq.gz
│   ├── 4650ec32e72ba3fea9db5909b87fe1549072e06b.nq.gz
│   ├── 46a85d9ec4115c239356480e19136676846e56e4.nq.gz
│   ├── 478c87bf47759050106d55bffb77510100fc624a.nq.gz
│   ├── 48422c2afab35a6688a115b86bef8a5446fd24d0.nq.gz
│   ├── 498e54e43244b518735b62959a06083ec5fbcdbc.nq.gz
│   ├── 4a603aa6e12d825d4adb77b33da20731a12a16e9.nq.gz
│   ├── 4bef411a522005f1b2e534da535fae37038867e1.nq.gz
│   ├── 4da2359d95891aacf0a86ec18f85675d261ec455.nq.gz
│   ├── 516fb8e19f13a50da174c568ede11d038cabbef7.nq.gz
│   ├── 521fd2785b214d83ca5da7e0ca1db8892c71236c.nq.gz
│   ├── 527674c857bb234b75421381e9c40a9d884237e2.nq.gz
│   ├── 538c38c4f69558472e5604f1dd375bff7124e901.nq.gz
│   ├── 538d6f526dc365f864a9706d0819a9463158529e.nq.gz
│   ├── 59d7284e4e70814b261b0e1b6541bacf37d05f90.nq.gz
│   ├── 5a422f6137cfce0cf2d17c03748958f1ae7fb632.nq.gz
│   ├── 5ede05bd52524c4b754f563020bf995fa64497ae.nq.gz
│   ├── 5f361c8e79dc21892fc95f4371e58bce015dca35.nq.gz
│   ├── 5f7d92fc4ef4eee7c37c3377230ca17d2add90e8.nq.gz
│   ├── 5f97411e83893c3a3508ad95334a208b008ab655.nq.gz
│   ├── 61b0fab7bdee531c4870bce92b0c84f077e84756.nq.gz
│   ├── 61df38e02ffb9ab51d91056bf6d9fce8e2d8becd.nq.gz
│   ├── 65acc664689878422fbda0b372e84f8cd11ae444.nq.gz
│   ├── 68a8f38f996014cce392265f2f0c9ea63ea1a470.nq.gz
│   ├── 6a2e18f3f69c10bea662da2ce65c76cc9208ef9a.nq.gz
│   ├── 6aef34c316af7227afe5a6423703e37c2a16ec20.nq.gz
│   ├── 6b8710a711f3b689885aa5c26c6c06bde348e82b.nq.gz
│   ├── 6d2818a2973619d92f5d242dd9d474e490938b65.nq.gz
│   ├── 6d28734aad53995934a300bbde0d8a328ace5558.nq.gz
│   ├── 6d8df883894ca11b62e795861a4138b0dd1b2d7c.nq.gz
│   ├── 6dc927db91a7cdcee384fbbd4fc25f2fb1080bf8.nq.gz
│   ├── 6e88ab027ca5d8223b0379e8c3bcd32d792f906e.nq.gz
│   ├── 7041e75b47d2776bc8a5167f1d6a1c0d69e6f093.nq.gz
│   ├── 732a9133e50c862d90b7dc3eaaa78e15b6143f1a.nq.gz
│   ├── 74d03ae921be79f3bf3e2cf4c6852b14b66ab29d.nq.gz
│   ├── 76868ca4b4908ebd1ae581d6a80984a3c6783de6.nq.gz
│   ├── 76a047ad21ffb730fc8088fb1634bfddcbb5bc2f.nq.gz
│   ├── 7a8391e15c6354d298f9c680556a0e3766123e9f.nq.gz
│   ├── 7b04dca870d73037ed5a78cd1fafd4eb3cd3215f.nq.gz
│   ├── 815d86d89c84f2d3d1d22fcad47d0c05ffb86c9d.nq.gz
│   ├── 81d0492ddfdbf2aba48c4a30da9f0f863b632e81.nq.gz
│   ├── 84922df500991df3492177bcc53bec655dea307b.nq.gz
│   ├── 84d96b6bd18bff6ef4671380542128c5564ec334.nq.gz
│   ├── 8518d49940adfbf1982f28f190fa10d84fc9407a.nq.gz
│   ├── 872a2ced61cf672195fdfa3ac87e873822023fcd.nq.gz
│   ├── 87d18b2224137d0cceb06e6fe01abbb1f1ce679f.nq.gz
│   ├── 8c036bfb29f99a645e55a3f70b6049aa43c30c12.nq.gz
│   ├── 8d18233c476d34bd2089c0ef31ed4e68a8552b73.nq.gz
│   ├── 8df30bc89114e07b6f1a4df748526b56c9e9fc93.nq.gz
│   ├── 8f16ebdbb4ff15e90ec19ada7cc7769462d04d60.nq.gz
│   ├── 8f6fcc5ccd1d25d92f45091ad34728e96053a36f.nq.gz
│   ├── 8f9c8c852b2514fa58081bf476d7d5f63727934a.nq.gz
│   ├── 90a24b5b13976566f49f61b5e94c2221cdd66f9c.nq.gz
│   ├── 93af26a2d6725fe1574f8cc15e13e067e4153e5b.nq.gz
│   ├── 94c2c6b7218e43641d52f8e047a119664d7b6758.nq.gz
│   ├── 957833f017a27e2e71a7541916c1fe37851fdff8.nq.gz
│   ├── 96b2e78de0b7df29e6ac5f6ab8c0c88195fb05b2.nq.gz
│   ├── 97d2cbacae718210b6ca420853dbd0f7b851b03e.nq.gz
│   ├── 97d86bed0dfbfc917620051bc7d93342392676f9.nq.gz
│   ├── 9a93429dca2e5d2495d77e77c1c9c728a3e316e8.nq.gz
│   ├── 9ad85154503d3d9e50e49206975f8da7af55f492.nq.gz
│   ├── 9b15f0e6e1f2929a70a9fe2a536c88a98bd09de0.nq.gz
│   ├── 9e0ae6a8a35107f3cad18f46f156d009095dfcdc.nq.gz
│   ├── a566b8af2a071b3af3d1cada075e05ffd99ad60f.nq.gz
│   ├── aaf3aa3457e9534428f6b0140dfcddf9b883042b.nq.gz
│   ├── b1bfab597fe54c446a9b534a7a89ae595c426a2d.nq.gz
│   ├── b4aba34f3c5b78060cbd5651ea65fb12ee47ae8f.nq.gz
│   ├── b6a3c9cfe66b9db3fd7c227745dcdc36a5ef9a38.nq.gz
│   ├── b72c0816faac750431222683fe1bdb0784554d30.nq.gz
│   ├── b9d37f398583812a188c4523cda46a308b5646c7.nq.gz
│   ├── ba76b671621f2c6fc2c485ce6228d1ccac2fc0ef.nq.gz
│   ├── baa427a0029da913d1741201ddf626e2db377158.nq.gz
│   ├── bc732e9583159d02b44ee33604989ad67ded93a9.nq.gz
│   ├── bd4494ca06f246e1788535803c2369b5b9247b35.nq.gz
│   ├── bf0b0d0405c09296f18b1ec3e8b6b0b47c08102f.nq.gz
│   ├── c3fc8f39dc4c12cf713980d7fdc7aa2a525a1ab8.nq.gz
│   ├── c5120a67ceba9e0d39b6a4fbd429c0074281e134.nq.gz
│   ├── c5879a43598e6f428d3e069d48a0dca939f2dc2f.nq.gz
│   ├── c69267432373affd856b7a5e33456487e98233e0.nq.gz
│   ├── c9c2bc80f0015dbde860e6487c2f43f63bf8be69.nq.gz
│   ├── cbe3a32066241f7b4b42611f10384293b0284f98.nq.gz
│   ├── ccaf2938e64aa1a7b821a34e4fa45bd5b5c52351.nq.gz
│   ├── cdd0e293fdf80ec589432d8fba112ca26885bbad.nq.gz
│   ├── cde8c85cf537079f48a349a2ad4797a8aa412ad3.nq.gz
│   ├── d2dc6696116ef31b7faeda51a1d895aa8d9496b9.nq.gz
│   ├── d33d913f0a56d6bf3ebf7ad127540112b15922f3.nq.gz
│   ├── d4aeac21f7447ab77520064463fc88e1bee9b763.nq.gz
│   ├── d6d2d4997e6d424f4982d9f9de331b8ceb775f9d.nq.gz
│   ├── d870a4d24d041d2571aa993f162cde1d2271f6bb.nq.gz
│   ├── da9162bd5326f8488531e9d9306208ff3f91b05d.nq.gz
│   ├── dab7ee77b698ef4224833420888b175aa47e8fd7.nq.gz
│   ├── db49d892275153e5022b98d481dd5a3172b1d227.nq.gz
│   ├── e02a47299a9adeb2a75e2fc0036d7979010f2db7.nq.gz
│   ├── e076dcb2e47a7b62790822c6aed9a136a77b23ce.nq.gz
│   ├── e16d28c6be8c9277f9aabc8f3d4d4921bab69f71.nq.gz
│   ├── e1e9f75472d66e9cdc468143043c54f9c8aa332f.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── e36295da99c40cc36e13867d1f95c6f26c4b4096.nq.gz
│   ├── e470e399a24af3f92ca2fd3ac6232fab5faa0b4c.nq.gz
│   ├── e58f2bc2a05fe5238caf3ea8b36064b1e129344b.nq.gz
│   ├── e5d76d6090847eeb469d3acc72fbb2d6c0c70495.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea559ddc358619fe3b0fcb19d5030efc8537bb44.nq.gz
│   ├── ec89babfe2e051909f4e7ab6e812a455e65638b6.nq.gz
│   ├── ecb6d585f6bbe172ee120ad9de83d78bc57f9ee1.nq.gz
│   ├── ed7b82ebc7ef9f1c37ee655822305b052bbf1a99.nq.gz
│   ├── ee62bd078c825b9aca79b845ec5545cda2831731.nq.gz
│   ├── f0824845572642d9fc3f65b2cb5361ba3504e736.nq.gz
│   ├── f13d928f4fb22bec37ab5102951bd537381ee338.nq.gz
│   ├── f4a9c1bfcb4d2d3f49998a7d22326b4e519e70ab.nq.gz
│   ├── f56d9e372a0c151dd2eb6d517df6a04aef20a250.nq.gz
│   ├── f7732063997a1a1761579b3f4bcb693f1b1907ea.nq.gz
│   ├── f8639fba009784b0284788df3ae3ba73177f8f68.nq.gz
│   ├── f8aa26be2b5f64d3bfce728bff0ae76a733f6c3f.nq.gz
│   ├── f95c361532df115e4bfcf8a8dcca13e5c6cbf6e0.nq.gz
│   ├── fa80786a8672503365fe31110848af6f186f32fb.nq.gz
│   ├── fac7f3588e26d3eb8b75724a53a53e1e4618d4cd.nq.gz
│   ├── fc533cc85bca17c8eb938d899b5dc82a947323ee.nq.gz
│   ├── fc7635fe001dc5e269e8c9fa8fc26caee9bf3e05.nq.gz
│   └── fe308894b0c30005d420ba128f9951c797d9f19f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 219db3cf7b01353c1688af89aef3eb473905a965.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 171 files
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

[hylang/hy](https://github.com/hylang/hy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
