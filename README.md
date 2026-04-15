# Repolex Knowledge Graph of gorakhargosh/watchdog

RDF knowledge graph data for [gorakhargosh/watchdog](https://github.com/gorakhargosh/watchdog), parsed by [repolex](https://repolex.ai).

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
lexq download gorakhargosh/watchdog
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 76c091dc8841de1d1a1cd6511bb509fe4f058de6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 76c091dc8841de1d1a1cd6511bb509fe4f058de6.nq.gz
│   └── repolex
│       └── 76c091dc8841de1d1a1cd6511bb509fe4f058de6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0185ceb8f35d959423f1fa0918b531285035ce74.nq.gz
│   ├── 0372a189324001916d695bc00d9ca20fce09b265.nq.gz
│   ├── 0f75b1ce0e4f187545de6cd838ad9ac7a3c2d506.nq.gz
│   ├── 1247e1f874ee9c6e3784977d9f8c47f63e3e6b4a.nq.gz
│   ├── 1439205ecb077761db497c1d2b3617cadc4ed73a.nq.gz
│   ├── 155ba6b737d4b1a37f5f226756dbcba62b8cf67e.nq.gz
│   ├── 16e326b4ae9326d54577f578f4b4445c9a8d26f5.nq.gz
│   ├── 186765ffb1bb62241d16157823bb2665939a851d.nq.gz
│   ├── 18a9b4f6d1c2928a3e38ce353243a62e33933e69.nq.gz
│   ├── 1cddd8422ba0700e30ec4469d2f702a7d4824ece.nq.gz
│   ├── 1df5b69d9f8696b2dcf75f9e6767557d223a3356.nq.gz
│   ├── 257e16e7b16c39751963781c1d37fc11b22489b5.nq.gz
│   ├── 266947a8d8756b6e430ce5f189eff412ac19fd19.nq.gz
│   ├── 270a436a21af900aef29d0d1690519a069bccfb8.nq.gz
│   ├── 2f9d0c6ffa3c3fda21803bbf38ea853e75a12332.nq.gz
│   ├── 30280819c60816874b92ee9af7726f162c1ffafc.nq.gz
│   ├── 30cb21caff9c686e11c6420064d039f37eb1ff02.nq.gz
│   ├── 33cbd25dda6eaf205c541e56cedf9ddf8d62cc4c.nq.gz
│   ├── 3c11d152c0302ad28794c3a415ab43b3ecf8a8d2.nq.gz
│   ├── 3d1f7e9b1eb7dd03bd58a52aa0728f2b590aaa0a.nq.gz
│   ├── 47537d9536fc8f77e31b55aa20a9c08ad77c983d.nq.gz
│   ├── 47ef98c3ac69d3aebb7a06979552eb4c91cf3b3f.nq.gz
│   ├── 4aea83a0d1382a750ea303217474c855c35c5681.nq.gz
│   ├── 4faa9450b29c4626153cb48fd6fd120dbd9a4ccc.nq.gz
│   ├── 4ff9217d341584b2d2bc119506b6789a6a58593d.nq.gz
│   ├── 50cb3c02282a0d14b540434f3a9cd00300014ac6.nq.gz
│   ├── 5871757cf3eec9a069e7138c747b3d723cfea0d6.nq.gz
│   ├── 5c94e525902e41f52b6362a87172b848e0778f1c.nq.gz
│   ├── 5d0aa28ae68b1740a47b9823f26d4980f34234fc.nq.gz
│   ├── 61c7f61c260cb29be99298131760dbe557d94d16.nq.gz
│   ├── 637d98885c5267896033ba4aed1d5d45f774c92b.nq.gz
│   ├── 6399a095a7e7d5fa19b72e9e9106002c9acf0f91.nq.gz
│   ├── 6aca8e425fe83c688bc2e9020ebf3a594598d09c.nq.gz
│   ├── 6d608215bdef91a1224a4be4f549d96c362cf2d2.nq.gz
│   ├── 759a9b0d9d1bd227025fc8ce569b53439772e46f.nq.gz
│   ├── 79e54098bb4ca59ae9705d743258e8c342f82502.nq.gz
│   ├── 828f4650ec0b242ad1bbe21e64e3aa90f759665b.nq.gz
│   ├── 85a6fbdcac8ffc3d787312860bd165c986b927f6.nq.gz
│   ├── 863f47b098c7b3b529696a7319a36a1b6e526ace.nq.gz
│   ├── 8669b595ec7beb00c43e456d7885aded514fd48a.nq.gz
│   ├── 89e0be14231dc2ab54ccf58592ee4d0894baf83c.nq.gz
│   ├── 8a0849d15664e944504cc6084e5c2e6f2caa74e2.nq.gz
│   ├── 8b63354a2f3fb45f8f332fe610b9dd76e6c049c5.nq.gz
│   ├── 8c3fed3232160b1d6e47313b0f3244b94e87ddcd.nq.gz
│   ├── 8d0b5099512477e35c4727b2d153d9a13c2b2eb7.nq.gz
│   ├── 8e1876f6a2bc12c11999a2299d8b03b9332d1098.nq.gz
│   ├── 9586861e7243b58fa1eaa859843dbaac1e9b0034.nq.gz
│   ├── 95b479ae6be56e13aa020b28a42813e90d6a3797.nq.gz
│   ├── 96a0350f892845eeacac0222754e95348e3c17bb.nq.gz
│   ├── 9994e91e296734209cafd62bbe68e3ec22655643.nq.gz
│   ├── a07aee5cf4451d28e74f940a7f4fe72f02b72b9c.nq.gz
│   ├── a528e7e4d3fc21ed6f4d60f4bc3d7c6535e71cc7.nq.gz
│   ├── ac7d770e018528091a3e689974d3ff68002d295c.nq.gz
│   ├── b0f4ce5240e7133c871d113dff2b4338b7e688f5.nq.gz
│   ├── b12c23cf25839bf39594126de7fead9bb209e4fb.nq.gz
│   ├── b59ae9a3f16d20a92205a5664320ef5007a19d9e.nq.gz
│   ├── b66c2ff299519878de31b4ae866779cae7428cfe.nq.gz
│   ├── b84e0b3c8468ff4672c6f1c5a88cb28c3eb067d7.nq.gz
│   ├── b993b6d2c17dccf08d2e3e6a8c60bd7b8bf6e324.nq.gz
│   ├── bd69b264f34fd686219c77ff0bda1a3a5b6140d6.nq.gz
│   ├── c1abcd60d3fc230b13bd724c6617677038551ac1.nq.gz
│   ├── c78a085739d9f44256d3b4ef2f830b2ddc75a21a.nq.gz
│   ├── cd85212321941a8f710a0cc4a51d74730d5560ec.nq.gz
│   ├── ce3957418de5fbbd7bb4c731d6ef5031bab4abaa.nq.gz
│   ├── d05f8790482b47fe6a920c2ee9fba805a10d60c8.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6f0f4119b13d77ffa243c316ffa22503e20fbdf.nq.gz
│   ├── d8e2bf1dfa971ee649ddc169a0c5d8de3cb335e1.nq.gz
│   ├── d9569733354904f057b29535a842521f0628db14.nq.gz
│   ├── da4c5588a12e3a0cd9fc71d5c01bdbb379b31e5f.nq.gz
│   ├── db430235088d2b35fbb84303d1818bce2bb80f23.nq.gz
│   ├── dbbd661c61735496ae1e921b39631cc42b6a3c9a.nq.gz
│   ├── e1fa55573788430111fe89a0a9318a034d8cc929.nq.gz
│   ├── e20a4dbd980b571e9d238f2961dc577752830112.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7879563c96b71ab428f942e8f4cce435cdb5a4e.nq.gz
│   ├── e85fa6348536c08a2a4ba59fab4ddee09e501071.nq.gz
│   ├── e8d3fd8e43678ac23d2d5fd73e8ed471af70f77b.nq.gz
│   ├── e8f05c3449285368d1f6c242da9d85d9749d596a.nq.gz
│   ├── ec6d7156792fa48e094478b07551832d0a88f29b.nq.gz
│   ├── ed8f776efb8f11bc1538c66e28c6beeee201a765.nq.gz
│   ├── f500266a5bbd688c436bd7fcd6091cd78dfded6f.nq.gz
│   ├── f542974a041ef5d27ea9c6cd4113a8827dfb68bd.nq.gz
│   ├── f98c0b07a9d9dd2bcb8ea8a1013e0f8c60edfbe1.nq.gz
│   └── ff69b0b35e677a8873d2e8d28f2857100f8f4c36.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 76c091dc8841de1d1a1cd6511bb509fe4f058de6.nq.gz
├── filetree
│   └── 76c091dc8841de1d1a1cd6511bb509fe4f058de6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 95 files
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

[gorakhargosh/watchdog](https://github.com/gorakhargosh/watchdog)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
