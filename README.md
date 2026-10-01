# Repolex Knowledge Graph of block/ai-rules

RDF knowledge graph data for [block/ai-rules](https://github.com/block/ai-rules), parsed by [repolex](https://repolex.ai).

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
rlex download block/ai-rules
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2c1cd16d05f47053eb3f059f87524f7b6ee1a1f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b2c1cd16d05f47053eb3f059f87524f7b6ee1a1f.nq.gz
│   └── repolex
│       └── b2c1cd16d05f47053eb3f059f87524f7b6ee1a1f
│           └── chunk-001.nq.gz
├── blob
│   ├── 0367d2331a2cbfb3dadb43da08affe106a235c28.nq.gz
│   ├── 07238e7f8584cfa96f052189be61d6a6f507ab58.nq.gz
│   ├── 09b7f685942edca10cf761ff7381475635356c2c.nq.gz
│   ├── 0beacd3dc1645c8cb114b573e0bbbe590586f2a2.nq.gz
│   ├── 10f2e64f21d543dd07495fb113d631b7dae2b5bc.nq.gz
│   ├── 11dcc0e2a1ca77ebaa65c38b886531b96c8db2b8.nq.gz
│   ├── 1ae205ca88878dad1e40ed99d85f3f0daff6ae95.nq.gz
│   ├── 1afa2ff404eff6960586d46361f4bbe33e173449.nq.gz
│   ├── 1b1d06b9a2800514b98e8e23602185430b63ab5d.nq.gz
│   ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
│   ├── 1c8fb46422428be6d0989fb717f848af4ccc7b94.nq.gz
│   ├── 22c8da5ca58b7f52de6ed0b4d3e1608d57af0c06.nq.gz
│   ├── 2369aae748a5ecdf9c0baf1fb359c0b7c61165ce.nq.gz
│   ├── 25c05a9ded6f25c37c7bf5e4f5d02455b96f438a.nq.gz
│   ├── 29767715e390b89b8d8ede09217a7aefe6dac9ea.nq.gz
│   ├── 2b15952e48d0f29a8c7d4745b33b9a2070545d18.nq.gz
│   ├── 2f0f1574e10adadbd9122f3d96b1e5535a57fa3f.nq.gz
│   ├── 30169106346888f6ded1c6de543fbef08af3ae24.nq.gz
│   ├── 314e28d33996c6d914c16519d838353a4dfdb8a9.nq.gz
│   ├── 31559b7d115e3c105b328cce9b9dcd9774025061.nq.gz
│   ├── 333eae474586f200a1a649b4b9eedad904242ad4.nq.gz
│   ├── 33c411344ccef017e726e8d4347fab241e0505f6.nq.gz
│   ├── 358f39b31000a69a4e11987d594a18ac6b71b02a.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3ca40faec3bd488029692e1a1ef1de3b6bed907e.nq.gz
│   ├── 3d9685a0d1fd66c7d3fb04fc8a6b0df498ac6d8b.nq.gz
│   ├── 41c699a2c33e940ad4135d5b09196e373e0b0cbb.nq.gz
│   ├── 42b0ffd92d12dc197c3e5f3527b60f57a0e83077.nq.gz
│   ├── 4354b6223a5211d92900824a3ef3ee6909c44856.nq.gz
│   ├── 443d407f88ff21c05217ac92593c59f42e42b71e.nq.gz
│   ├── 45d3e751fb0638ae1c90e784f0c6cd7ad5ce00a2.nq.gz
│   ├── 4691e035fe864e937e151668795fa71357d0e57d.nq.gz
│   ├── 47d9d3de7316f429e88a0fef294574767a2175a6.nq.gz
│   ├── 4985548953551ede59474fb6f99ad6d8bc310711.nq.gz
│   ├── 4b07dcf9af976514f3894ecf212aefac96157cb6.nq.gz
│   ├── 4d5e2350a1922d7c3e8cfd99d9aef69c5e11e6ef.nq.gz
│   ├── 536093b05b718525cf7880d5492070ebbe981987.nq.gz
│   ├── 5790b964c297dd59b32670c9ea57109a53611427.nq.gz
│   ├── 588900cdb079fa1086a666f0f4caf669a3d3567c.nq.gz
│   ├── 58a992d63b29619e08923088abde45735ca5fdde.nq.gz
│   ├── 5955513dfcfa7a1515086db839ea1cbe65679539.nq.gz
│   ├── 5cf8c78775dabe652d69ff4a54281ef052fc2afa.nq.gz
│   ├── 641ccd07f4f96a2df42cd12b1af46d3376271714.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6fbd5959edbc502711666407f082861b4d8d7eb3.nq.gz
│   ├── 733c821b96c23cc05585aedbf76b99711161f03e.nq.gz
│   ├── 737b333f49738de9c07081d54a9d09aa52062048.nq.gz
│   ├── 747ca3bdc30a4966236c42b9a4523e37c2854b10.nq.gz
│   ├── 75bc89a0faf77c4aceafd68f3401f4b378e810c2.nq.gz
│   ├── 788fb94a77a01981590efbd11151e8267fee284e.nq.gz
│   ├── 78f154f045688b998a462ec4b9c043d6beec6096.nq.gz
│   ├── 7a7f14d616d22ec5338c21f22d322d60521fdac4.nq.gz
│   ├── 7a9d54e889edd1ce475172add8337a2014931a16.nq.gz
│   ├── 7cf018a18e1810f996120fee07e2aeb49fa513dd.nq.gz
│   ├── 7e310a9f2c0ffc115bb27b185310ca9b46b81f65.nq.gz
│   ├── 7edcec50c15e4f9767aeb1034a929cceffb54d06.nq.gz
│   ├── 828ac238cbc757310219c924e676472522760ffa.nq.gz
│   ├── 88374742c38950070e5a767a7612c4b938a4174f.nq.gz
│   ├── 8be9ea6a3b579c96e6ac04dfb27c29761c16f702.nq.gz
│   ├── 906ee94ca6891416a56b8a1df9e0bbcc0000429d.nq.gz
│   ├── 93263d79ca289390a7ba5ff5412e4d1e7fb7ba3b.nq.gz
│   ├── 9421467f113a2c67d84aab321ab6e925b77a8ec1.nq.gz
│   ├── 96e12fc293edc36bce3ad696af1e93b6a24fd2c2.nq.gz
│   ├── 98fa941e69fa9d8976e4ce0c4b999dcfa11f901e.nq.gz
│   ├── 9dba849ab9ce148ae202d9fee8db15d4faf520eb.nq.gz
│   ├── 9ed5bd336a600aa8a2e98c81616cdd09ca1a3bd8.nq.gz
│   ├── 9fabf8277e8bf35fdc1f0187a91e10bc49ddbd87.nq.gz
│   ├── a24a8878d5d7976e5393aab34acd24e28a057cdf.nq.gz
│   ├── af4da334dea3980bde11689bf072b55c2ddf7886.nq.gz
│   ├── b034dbd2cf6bcf2e6fb1a0ffd4d9ae723e691651.nq.gz
│   ├── b0461f41ba12e0778c19986ceaf4a68d9f0ad4bf.nq.gz
│   ├── b1442a9012c32765f0486f14b00f8f45f52ec447.nq.gz
│   ├── b387b0b5370f086ad070f3b84489e5838125a93e.nq.gz
│   ├── b52e385de7c4337cafa4ec4942a5bfea13ad5d1a.nq.gz
│   ├── b748b4afed974a852922b4bd55f3f53a43639a82.nq.gz
│   ├── b7db4f1e403f7044ad493767385a76c8cc01eeab.nq.gz
│   ├── b8873d058338364d8d4311fd9552694cef317262.nq.gz
│   ├── bac41974d078265980ba5af2fa8d96f64f5a6913.nq.gz
│   ├── bacef6b1662ab5245899e5956e12df8d4634c001.nq.gz
│   ├── c07cce6118c2c70ee205ae624ff7c37e4507a417.nq.gz
│   ├── c3b31ebd2f0f21c9523b99a7662e32714c9978b6.nq.gz
│   ├── c896d6a372782ad2bfff0b8ef2971fd341557310.nq.gz
│   ├── cab893b64c694d8280bc8b7160eaa0c942b6c2b8.nq.gz
│   ├── cc17d794d8718ff258b63659cd8931a1cb004e08.nq.gz
│   ├── cd67b9038d9aa0065e448695562516cd1580c38d.nq.gz
│   ├── d1e7cc2b223b7577ba27ae93206b24d650500359.nq.gz
│   ├── d1eafad1b365865cbb45a9e749a5526b2d8f5918.nq.gz
│   ├── d380a3d9a20994fab4bd7d77e4b8ebb50aba2e3c.nq.gz
│   ├── de8229fe1a39eb8f3df93e4cdbd049cb6992c62e.nq.gz
│   ├── e65b461438017217a38e1eb9f41f01d8f087cb01.nq.gz
│   ├── e889550ba4cbc92a720527042e5f6e7a303bfcbc.nq.gz
│   ├── e9a02fa0c7851bd03a7624d79260d9c0041971fd.nq.gz
│   ├── ebf799fcfb0197c82743b55ae226ee2d3030e4f7.nq.gz
│   ├── eec0af0acbfa199c120ee66067562527521c04e0.nq.gz
│   ├── eed72f64202502a4918239ed1537c896cef3b31b.nq.gz
│   ├── ef1ab99b90ca89845cbdaf55e71f6db5cda5775e.nq.gz
│   ├── f460ee56e72d62abe6b14ee89200fb4bfa2f3285.nq.gz
│   ├── f6774caf4e16c73296323a22ac59fe5c4c336b5b.nq.gz
│   ├── f76266984e618f241f25c412420af73b56e2ed0e.nq.gz
│   ├── f8a08f691860332699c5ac56e6883ea1787a1290.nq.gz
│   ├── fa46fc0c813704ee0d4f24005bdbff9332af763e.nq.gz
│   ├── fe28214d3352b0ed40820a4999317694c8b1ef57.nq.gz
│   ├── ff76e94e02a5850aa890c560e9ebd14d042760a7.nq.gz
│   └── fffe8796f3e5218a2ff97f0d73464085e34f34fc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b2c1cd16d05f47053eb3f059f87524f7b6ee1a1f.nq.gz
├── filetree
│   └── b2c1cd16d05f47053eb3f059f87524f7b6ee1a1f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 114 files
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

[block/ai-rules](https://github.com/block/ai-rules)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
