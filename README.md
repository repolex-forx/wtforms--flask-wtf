# Repolex Knowledge Graph of wtforms/flask-wtf

RDF knowledge graph data for [wtforms/flask-wtf](https://github.com/wtforms/flask-wtf), parsed by [repolex](https://repolex.ai).

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
rlex download wtforms/flask-wtf
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c57f3e70df2852022a415714bc7f49113dd9b4f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7c57f3e70df2852022a415714bc7f49113dd9b4f
│           └── chunk-001.nq.gz
├── blob
│   ├── 003f05507caa06c133ba117a9ab27d396cf3f324.nq.gz
│   ├── 03d0c91f7fb36e849e8031c5aacc5d0fce213e2d.nq.gz
│   ├── 0df967347d91cbcc0cbb402d2681d5f243eec2cf.nq.gz
│   ├── 17f31785625edced09e6e8e33d8d67e7ddff764e.nq.gz
│   ├── 1b0031061bbac52f02763bd6aacdfee2809722ae.nq.gz
│   ├── 1cc0e9c5a6d2fee8d18c4f46a79ed82f93d132a7.nq.gz
│   ├── 1e2cc5b8f4bee41d9be4edc1f3b2d0980cb87170.nq.gz
│   ├── 1ecd20fca7dc826eb4f0b4152c6ef9de4a41ce02.nq.gz
│   ├── 2248278d7280dd6ecc9b8b941157574d80885b4b.nq.gz
│   ├── 233dc402d35b5be1bf39dc45524659678530583b.nq.gz
│   ├── 2c6aa3a5c9d48c426663ef8ac6a840ce4b81ddf2.nq.gz
│   ├── 2e1a6aa15e6a1e122e7844e784c9b983a8a6cf71.nq.gz
│   ├── 2efac16cf56c4db62bb0e541effdcb2443b401ad.nq.gz
│   ├── 2fa1633dce9e4a1e935d296a9bf0b270e0d037b3.nq.gz
│   ├── 3bb486826948b37a5934c4bfb7fac1fac1489191.nq.gz
│   ├── 3ed1ce6cd2f413a9ce620ec50109255c75ba7151.nq.gz
│   ├── 475326f55fe785688462a546bbb85168f0780c49.nq.gz
│   ├── 50973e063bbdbd6982fc9501221603efbc2e88f9.nq.gz
│   ├── 51e97a57477510ef7c6ba409d7ad06c99aefc590.nq.gz
│   ├── 63c3617a2d7164d30cae358c23eb3f75b5a758a1.nq.gz
│   ├── 71806bc16434e56c2ec1654e82e42baf7288f9c8.nq.gz
│   ├── 72e9b796e8442eb7bdf66a39528625964f810b16.nq.gz
│   ├── 752e76591af135b84fee887f3a25cb8d6e0ed378.nq.gz
│   ├── 856b490b9b297e5e7b9ab0f20597d25aefb11124.nq.gz
│   ├── 85f87863ef5ea8a218d93d2fd9e540050433481d.nq.gz
│   ├── 8824e05fa33a3eb4114da23e244dd07931305d4b.nq.gz
│   ├── 8d099151ed2968adf5ea5207d22ff8e7f97bfae7.nq.gz
│   ├── 90f94bc32b917f4902e37ebf40553590c3b3a521.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── 9ba3a8a02ef023c361424a9756f949571e60ef0f.nq.gz
│   ├── a53a98cf3d4b093c6696becd3df4e1c6c0660fc9.nq.gz
│   ├── b06488062f236b96f48a78d7cc2e9c695b66c002.nq.gz
│   ├── b5ea0e9c282d387e628099c3b64c5977d2619eb0.nq.gz
│   ├── b79c606e8e6a70959128dad38e1c4884d0f0cbbf.nq.gz
│   ├── c3f1a4b0ff253ec7dec9cdeecb79c508d062435d.nq.gz
│   ├── c414a9fbb28cff6c7cf25e04deee6e6c782ef964.nq.gz
│   ├── c7956ec786d63e6ffd67b8891704cdf9e8a22964.nq.gz
│   ├── c7f52e022c82fe43d6674377e5df040c82d10d79.nq.gz
│   ├── cc1185c5b16b6d5ee97e02d654628807576d0ae2.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d76b3a61440a901b865d21e5536a943dffcd52e1.nq.gz
│   ├── d869d4ca0ea63676671d292d3cc958b1a7379174.nq.gz
│   ├── def83b2d820af4172ae73aa0bbdd5aa3dfe98712.nq.gz
│   ├── e32c8029d1860bf40125d8458db3bd1c4d3f4058.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e8377cf3cfbd2991797bdc9b618630bc4269aa35.nq.gz
│   ├── ee09d59a54b8c625c75e3251ead8a54a0197811d.nq.gz
│   ├── eecb14b6295d7fe44a08e0ad315a8847e29a425b.nq.gz
│   ├── f2c547d3bb9757cba2756d07319c580ed424a824.nq.gz
│   ├── f8d81288f649d362507aeead94aff331939a579b.nq.gz
│   ├── fa34d8707645a9d4ef1931831625df0b8ecdfb7e.nq.gz
│   ├── fbbd923921a27cfc8e9615b119b3571e1a885a49.nq.gz
│   └── fdc507ff3f08cebe2d3d7730e8e795b22313a324.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7c57f3e70df2852022a415714bc7f49113dd9b4f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[wtforms/flask-wtf](https://github.com/wtforms/flask-wtf)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
