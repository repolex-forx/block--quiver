# Repolex Knowledge Graph of block/quiver

RDF knowledge graph data for [block/quiver](https://github.com/block/quiver), parsed by [repolex](https://repolex.ai).

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
rlex download block/quiver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 86b09b2af1f7f48b656fa8dcca2ef6eb44c6e72e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 86b09b2af1f7f48b656fa8dcca2ef6eb44c6e72e.nq.gz
│   └── repolex
│       └── 86b09b2af1f7f48b656fa8dcca2ef6eb44c6e72e
│           └── chunk-001.nq.gz
├── blob
│   ├── 005ee5a315a4768dd8e699826c4de9e1b0286519.nq.gz
│   ├── 0d835b928a3785bb71efd696bfa36110b375412f.nq.gz
│   ├── 0d9c7e655049a11b7a06642a1482440b0d319a63.nq.gz
│   ├── 0f9294bc6526ac1194ca154f8ff3f7ab3f0fa985.nq.gz
│   ├── 18d969ab4761d7fc22763d72c1aa372ec4c99ba4.nq.gz
│   ├── 1daa80ba66ca2048408993aa8aafb660d7de521d.nq.gz
│   ├── 213a2b09f1139dc4b8836d711d45908b1a9b396b.nq.gz
│   ├── 28cee027fd31eb50d53d562e217c1c911846653e.nq.gz
│   ├── 2c1f94a074774dacc3e1cc7cd02c9e19f1d3abf9.nq.gz
│   ├── 2e4d63ec5a2ff1007b7f88436df58bdb25139f08.nq.gz
│   ├── 30185ed08b926d27f3353ea8b9c10a2e56f6efbb.nq.gz
│   ├── 30f24f088594ec107a2120cb3850f050e8520419.nq.gz
│   ├── 321ec53d1c62379dd9794f445d493987b2b54007.nq.gz
│   ├── 330e0e96375ec1ed06132d7e0860b9f7fef48a3a.nq.gz
│   ├── 35bd76efca79861729ca895dce5727abc8c01937.nq.gz
│   ├── 383f4511d444516caed0fd113ee8a2b640cd2290.nq.gz
│   ├── 3a457e588bc00eb05cef1040a96728195b0121e3.nq.gz
│   ├── 3ac2612d8b81016a656f22b02caa54f8160b3cf7.nq.gz
│   ├── 3b191fb4efa5ec3e2cd156e539de8a69536b7488.nq.gz
│   ├── 3ef792012efab3b4a482ce4dd84fe6eb4b9be4b3.nq.gz
│   ├── 4829a98a2d47ee00b720b432fd17c93edfac6e48.nq.gz
│   ├── 4a8c52a53e45bd0b1126637062cb91b03b52bc29.nq.gz
│   ├── 4b9bfe2ed0cf5723d2e21f2a893df6b60230b426.nq.gz
│   ├── 503fe5015a7bb6da8079226d94efd169669a2032.nq.gz
│   ├── 53e4e3eb9f610a83e18ef9b33cf01350efd443e0.nq.gz
│   ├── 624d1385bbed90e6ddff4fd61ff56d7bffaa8690.nq.gz
│   ├── 62a195ec061cf43d40c46761cb22b5f4a2b6abbc.nq.gz
│   ├── 6a4cd2258411c900d5524a0a49e620780218940e.nq.gz
│   ├── 6f951f61ff22e1379b26946375caa7204cd9d57c.nq.gz
│   ├── 74c69f2247fc33c7b8fc612bc3a3ee289bbcfb85.nq.gz
│   ├── 763609482d49056c7fec4b51aa45631fca8c1bd1.nq.gz
│   ├── 7c085710f494e3190950078bb3a8ce13b5d4797c.nq.gz
│   ├── 7de4143e0a221083b97ad8052f672734a25f91d8.nq.gz
│   ├── 8430d31e13f1c2e1de194db9dc7d51b221db2667.nq.gz
│   ├── 856911d4e9c8200599d5b626920a565cc534d7f0.nq.gz
│   ├── 8ae8e92f26d223d016b21a4ae74f4daf5fc14791.nq.gz
│   ├── 8fb7368d47fb835edd3df160644bad46795c1d67.nq.gz
│   ├── 90c9e53e0c00990422a0317d12f29c04c5ec48e6.nq.gz
│   ├── 96eebfb7f7c55d7f1704bc5cdf14af2d1bd6b071.nq.gz
│   ├── 9c84a170f02376af71f2a55d5156fa83f8d985f2.nq.gz
│   ├── 9d12dad3b1fd3fec73cb076046cf195caa4b1fb9.nq.gz
│   ├── a4a00765f5ce361f2316e6b21aafa4035b6f9f73.nq.gz
│   ├── aa2e591dbc3c25ae73d24be406ad882b174bcebc.nq.gz
│   ├── adcb54ebff5c4c752d8d05d4af60fc830ab5940a.nq.gz
│   ├── b058065f2fabde7315ec3dbe0bd37f5c5181b1b3.nq.gz
│   ├── b22ed698af56ef7939dde710acf2539ad09ad40d.nq.gz
│   ├── b84895f6416ec8d9f0cd9e1a863891a91ed5bcb9.nq.gz
│   ├── ba1af933bf4571830659c885908a74e8671292f0.nq.gz
│   ├── bbe84ab3d19d584b2ea6d233af201efc7eb28a48.nq.gz
│   ├── bcad5f321ff5fb5d6b243c8c239ebf11d2f2a92b.nq.gz
│   ├── bcf26824aa2a7db56db91bce5e04b8bdb9006e42.nq.gz
│   ├── bd13c859ba57eb398bd853c1e09b38c6159f9d41.nq.gz
│   ├── be0ea44de4b347c597cd7144ae18fb81c474becc.nq.gz
│   ├── bee4fc293b51744c834c46ac1256f3d57f43f908.nq.gz
│   ├── c16321b48e7f2aa442a4407d997da015ef1b9250.nq.gz
│   ├── c17bfc78365dd223c70e7dc956880cd5e451f820.nq.gz
│   ├── c414b043e94c8bf8d971758fd7b29da76d4318a8.nq.gz
│   ├── c8c407fcf058d58d02f93efa91541cd5216ba54a.nq.gz
│   ├── cea1b0f44a8555cb7e37be746951faf9f767117e.nq.gz
│   ├── d37fe8786f66b054973470634050c5b856d20da1.nq.gz
│   ├── d3a18757b945163df04668a87e84efdc4ec30282.nq.gz
│   ├── d70aeacfbc3c9139371e8e4ec6b64409d485f3f7.nq.gz
│   ├── deb4706b8e72d3bff2a8917e8c4c6d310d1677ac.nq.gz
│   ├── e546692670a97d652a47e8e44b4000c850b734fb.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f2278332e28c51dc2fefc258881c1afb8f87fde0.nq.gz
│   ├── f51541e84893a5e982b69aad81b5490a3bad72c0.nq.gz
│   ├── f677e040c7be834726a70e20b874a6f7a1cf122b.nq.gz
│   ├── f7ffdad10a58d9fb4b74852a972ef4d09ba6e781.nq.gz
│   ├── f9e7ec59bf709d8cee82a8ce1b2572e7c01404d0.nq.gz
│   └── fa281762201d004b095ffb7aece75dcf23a68f8f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 86b09b2af1f7f48b656fa8dcca2ef6eb44c6e72e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 80 files
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

[block/quiver](https://github.com/block/quiver)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
