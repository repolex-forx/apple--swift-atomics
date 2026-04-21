# Repolex Knowledge Graph of apple/swift-atomics

RDF knowledge graph data for [apple/swift-atomics](https://github.com/apple/swift-atomics), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-atomics
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b601256eab081c0f92f059e12818ac1d4f178ff7
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b601256eab081c0f92f059e12818ac1d4f178ff7.nq.gz
│   └── repolex
│       └── b601256eab081c0f92f059e12818ac1d4f178ff7
│           └── chunk-001.nq.gz
├── blob
│   ├── 03800f1c9a9d25f46970d271a06630de8a57db0b.nq.gz
│   ├── 06bda94c3d771f5bd426c9cbc78490a6a4258ab7.nq.gz
│   ├── 0a048074d6ed881051e030103c4f6792400c02a8.nq.gz
│   ├── 0af13fa1b03902728eeafb12bfe7c9cb76425e1d.nq.gz
│   ├── 0ce7900099666217adc8c0a626c9994598a58d3f.nq.gz
│   ├── 104920d6f01523a3f520eb7a89ec102dd78f646b.nq.gz
│   ├── 1073ba7f00e19a76cd7980320462fe070dfa1e90.nq.gz
│   ├── 10e8feef33b091c6295d5cd6a578dea34dc0cb1a.nq.gz
│   ├── 1239850f331ab3eb13becb015fb1688a7c005996.nq.gz
│   ├── 133c63d3e417c64756ebf1c09a9e785faccf855d.nq.gz
│   ├── 1486d151db1cf14e6371c98d83030039ce331d50.nq.gz
│   ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
│   ├── 1959e0af82bda6d167a55393bd95b2062b11021f.nq.gz
│   ├── 19b8870a0811354743db7cc80bc1f5af5028e7fa.nq.gz
│   ├── 1b0ebda4111b245d64cd90d60ba298ac87efeffa.nq.gz
│   ├── 2251659f2e1e051986ceea11c4d2ad6a2f20081f.nq.gz
│   ├── 2677efa7f34dcd8c116e4907aa81807689cae2e3.nq.gz
│   ├── 275bb20deb376a6077b4cadd8dbb41cc6df2019b.nq.gz
│   ├── 29dc3f2923fefbdb7c866625e226559425f2c964.nq.gz
│   ├── 2a3df4a0aaae2a86783a161939d298902bc9a8f6.nq.gz
│   ├── 2aff4850e30cbc878082e447074a82921f7b90cc.nq.gz
│   ├── 2b0a6035582f1c83c23011c1190bb23846a824fe.nq.gz
│   ├── 2d0088a21091e21cb7a12b377858519449497280.nq.gz
│   ├── 2e697e8dbdde5b2c209959a760f8b9a0380733f3.nq.gz
│   ├── 300993162dbf1d15258ba3eb87fdabbae39c0a3e.nq.gz
│   ├── 30f482aebcf2a8697fbe9d87c052aea98f48818c.nq.gz
│   ├── 3107e9007d27e44c2bee60f7f867e9614aa8c9af.nq.gz
│   ├── 348e749e4d3a5523091aac5c9b9d2f86ad6d1526.nq.gz
│   ├── 397df571f8bba153092b1481ecba02059b5b68c4.nq.gz
│   ├── 39ab68e9c6899b3aeac3a416963324fc3aad3f02.nq.gz
│   ├── 3a5a4805334db59cfb4c910381977dbe1627c264.nq.gz
│   ├── 3ab33240b4a11a7fcdd65205f6fa53b9567f1577.nq.gz
│   ├── 402de1935e69b8f7701a9406910fb0140b49dbdc.nq.gz
│   ├── 454d5e523ba4aa28fa47ba82273835576ce6481b.nq.gz
│   ├── 45dd4ddc27dc222291e1fce5d1de86bfbd52b62a.nq.gz
│   ├── 460254b37e6b0e02527e19c20e10ca2566aae74a.nq.gz
│   ├── 466bda5142c5ece0e9ea21d6a426f399fb01a41e.nq.gz
│   ├── 4e2803f1caf9812ecfe72d7412a9aa6fefa0f194.nq.gz
│   ├── 4ed7662e3fa7a1a91dcc18e83d075ea9099a875b.nq.gz
│   ├── 541f2eab80bfda8fff793a163581d9300e5f365a.nq.gz
│   ├── 552b95a10ab2591486caa03c64b7e6d5a3f9a3f3.nq.gz
│   ├── 583831b370402957cceb6daf2c5a04f261b402c2.nq.gz
│   ├── 58ab77a0138d968dd3bfc680b44c7f0af2c2b6b7.nq.gz
│   ├── 58eaf9086dce7bd83a6e51dd99125f937d0954f4.nq.gz
│   ├── 5aace102f02942576d950d076c0b293ec2532da2.nq.gz
│   ├── 5bdb294f682f8669e8bbc83e8b85a1ceec0c05f1.nq.gz
│   ├── 5c406568f21a93754fb69991a7523672713426db.nq.gz
│   ├── 5cb8e686acdcb5156803209be1bee4d0a8537c19.nq.gz
│   ├── 5e103b79d3e0a89926f3027c3de59f5f7489a99b.nq.gz
│   ├── 5eaf25616e4dbcdd7b589ab6eee2a08c0427795e.nq.gz
│   ├── 61b0c78195f2d00acaf658000eeca6ad406a3a29.nq.gz
│   ├── 61b4e80f04829b25eba3022d858689038daa8a1a.nq.gz
│   ├── 649374d1b06da330b9d1490f5a7a4dcd3bb6ad85.nq.gz
│   ├── 66efb1ca11876c36201196fcf06af37a7689677b.nq.gz
│   ├── 675ee4e900b49a1611c3f0c570a298f93bd0bfb7.nq.gz
│   ├── 6a1c484e01a0d5199bcbb254c910d52827fd036f.nq.gz
│   ├── 6dbe8814936b6928b17e191be2f82ebaa8224849.nq.gz
│   ├── 705a62e17b2d704e3c9f8b7658fa58570a87ebe1.nq.gz
│   ├── 7075b18cac6a3639af2e27bc21c8b2cb1aa7afa7.nq.gz
│   ├── 71e1ad76d1157ceb23dbfadc25fc65b0a1966c3c.nq.gz
│   ├── 765bf6f452bce1b34bdca2c57e8ea06efdc4d961.nq.gz
│   ├── 79206f8d20a30e5674dc39fa3116da4a4ff52465.nq.gz
│   ├── 79c92060dffc2c8e870801faf2488db47dd85095.nq.gz
│   ├── 7a2a8782eb2c70cc2b2e0f6d7de101e8656aa25e.nq.gz
│   ├── 7ad4b92089ff018c2a76609fc4aa4531f1e34f2a.nq.gz
│   ├── 7bb0aeee5ec0ab9147649d253bb9a230b5c46092.nq.gz
│   ├── 7e2a029d6d65dc04aee8e57b263664c6f3e10494.nq.gz
│   ├── 7f3100859ea3609dfc843a19f5a5cb52573c1959.nq.gz
│   ├── 807ab370fc9f57ce5243bcb31b0ec92bd71ba512.nq.gz
│   ├── 8206bd8a0c647180f9751375fc80d6d3df391117.nq.gz
│   ├── 828ab7a87f32f605ebfdc158327165c65ef19b67.nq.gz
│   ├── 82dae384e343deaf44dea46b891de8707c049f4d.nq.gz
│   ├── 837fae736818895293683e0c852b4ee748fd2e3b.nq.gz
│   ├── 8383ffb6d2371d0f1b84724bb1343e573153ccb7.nq.gz
│   ├── 875037ad25612e5ca0a33cfa50f186941a1203e8.nq.gz
│   ├── 87ca1dffe2601236e0f582533080a80797677a4a.nq.gz
│   ├── 89041da05241b0c2bbbd13be85387b34c96f6cb1.nq.gz
│   ├── 8b498858fa8d6b02618182570160c6ada5f487c6.nq.gz
│   ├── 8ef38e424d8daf560e806124633367bdf06ba867.nq.gz
│   ├── 8fcc1f214af1365573620d1d7251fbdac0826729.nq.gz
│   ├── 8fec84a103b02612cb600993b48d872ce19791c2.nq.gz
│   ├── 9155f5db9b2d20b4ac74f89143942999008c855d.nq.gz
│   ├── 919434a6254f0e9651f402737811be6634a03e9c.nq.gz
│   ├── 928ad4761279410db378dd2875aebd0b7a3f4df6.nq.gz
│   ├── 934be2f2cf66b9683db37a294ba9047a18f7762c.nq.gz
│   ├── 9ad2995d007cb929316bd99fedd39f49d9722681.nq.gz
│   ├── 9ccb6e80cd32715140dd61df02f1fb468c182815.nq.gz
│   ├── a0011d1a90d41db922f14d72d218bbfb2d7e8039.nq.gz
│   ├── a29aa82ec22637cc7928ac6326a9a75cf258a75c.nq.gz
│   ├── a553bb31caf548cfc1fe79dbfc60c4d3978e8334.nq.gz
│   ├── aaa38b450f5bd2e0c61db5f213b3dda4b1130149.nq.gz
│   ├── aafeab1d33d8bf9f9c32d212e9fbe1ebd71a02a1.nq.gz
│   ├── ac0dfe2aaa6ddcad7ea10a122b1486931c112592.nq.gz
│   ├── ac83607266f1bae53c41a7103344cf00f63579e4.nq.gz
│   ├── ae1bd4187c0b1b2bbb3ae9bc39bb450166c6f7b7.nq.gz
│   ├── ae6b4893022a17f01b8c2c749d231b461cf34d52.nq.gz
│   ├── af7bf01cb4917d9436fe922e1e6c24f9e9f52ee7.nq.gz
│   ├── b07f4966e85a088d4cee8f22ceb300c87f59762e.nq.gz
│   ├── b13104cb23d64c5d234e02622d9019fcbf528bec.nq.gz
│   ├── b1c1744ead41eec6f3b102fd6aacd1d8121dd29e.nq.gz
│   ├── b4b1a44013ba7f2cee847586340015ad74df8a8b.nq.gz
│   ├── b6b90220fd3ee4f7a4df5aba0f260a9e05ef68bc.nq.gz
│   ├── bc0aad9e76e33e5efc2cf8d2ced913edf833fa22.nq.gz
│   ├── bcdda511deb0454b6b2ffd5562b45b7146afddd9.nq.gz
│   ├── bd16d4118c1914ad88fbf2adee2232794c100b5e.nq.gz
│   ├── beeaf93714db6daf0f1104d78e3db8f6d355b6d4.nq.gz
│   ├── bff5f7065f358f65fb88564c01087576a9a7080e.nq.gz
│   ├── c2e02d6cefa9120a7727a2b18d76f4f9cb6e7def.nq.gz
│   ├── c34290a02b2a97d78b7b3d8afc28e12c6d8e04a0.nq.gz
│   ├── c34bd0543ad901366a85be2276b283becc1aab2a.nq.gz
│   ├── c48ecbd62c6908e77d85a3a7de48eac7a4b78b8f.nq.gz
│   ├── c5fd5b8741cd0f86dc499e11cf7b6c7ea9e81202.nq.gz
│   ├── c63271d4e926c3e41c448db9d0b3eeefc24e7fdd.nq.gz
│   ├── c7a373d537cc5c86dc9f06264ee85d57fc2892ae.nq.gz
│   ├── c847351fa4dac521145a731c5dad192215a4672e.nq.gz
│   ├── cce19475288eadbc7976e05e9559e0b2db29b029.nq.gz
│   ├── cd444a28512bb84df239878d42ec16c09779d453.nq.gz
│   ├── cf02697e12ac34cf117ff9688c82fdf1ced118a1.nq.gz
│   ├── d546f3d7810cd4ad1313fce33de6328a99059cab.nq.gz
│   ├── d56d13b6ad2252641dec06347dafc3a19a1dc40c.nq.gz
│   ├── d5aff2cd00db7a1612fb2cfdd6d6125ccd222c41.nq.gz
│   ├── d66a1f201a23ca0ae4c18c1b1c54727e5e5718f8.nq.gz
│   ├── dbad2fc2221ec73cc0e7f3f49a767a44506df7fb.nq.gz
│   ├── dd62b5168b5b49f77ce95dada914cac6abac80cf.nq.gz
│   ├── dd7bac371021117d1819ad3aa2cd92002e02526f.nq.gz
│   ├── dda74f6e164e3bc86baf3648bd792a12e3c4474f.nq.gz
│   ├── ddeff52063d29e4c13b7f4cd9f571b95a107ffd9.nq.gz
│   ├── e0c8222c0cd24fe19d439c04736c387be7c14c75.nq.gz
│   ├── e3058dba6ce43892eff42dc077e71b7d85cb874c.nq.gz
│   ├── e36bf969f0cb9a57caf42b70ec3d73de116a7023.nq.gz
│   ├── e3af0b7d8f3adfa9146a647373bead4fb6b4da7a.nq.gz
│   ├── e5b8d31bda99346824dbccf0a140e929f15ed1c6.nq.gz
│   ├── e69f2d16011681f1222b3dd3cdd1e61f28cc8ec5.nq.gz
│   ├── e91e35703200fca3196d13a9677e157fe4f79480.nq.gz
│   ├── eb28ed95e1e26e6d167b98daae44bb0e4b5465ae.nq.gz
│   ├── eb8e76da11817a336c667ab699c3e3dcd7e91e0c.nq.gz
│   ├── ed88c36a8faaac67cd7de183656d073c4cc55ade.nq.gz
│   ├── ef6ed878901017b08bc1d6bbe3bdf5df3a186226.nq.gz
│   ├── f00c3f2b3b8f31a5a0c16603c6269107ae875624.nq.gz
│   ├── f2d37b4f8de3173ebd0c77b0254311766fef8115.nq.gz
│   ├── f3c47ef803227b5dda6e8e421b20d25a112404de.nq.gz
│   ├── f40f19bf79961f16ba16450e3c336d1289ea974f.nq.gz
│   ├── f50c664bf556185bc58d09ce7dd17088a0a77155.nq.gz
│   └── f6739c97cf28ea2d638a75f45f704a3b816adb98.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b601256eab081c0f92f059e12818ac1d4f178ff7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 153 files
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

[apple/swift-atomics](https://github.com/apple/swift-atomics)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
