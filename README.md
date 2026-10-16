# Repolex Knowledge Graph of glue-viz/bqplot-linlog

RDF knowledge graph data for [glue-viz/bqplot-linlog](https://github.com/glue-viz/bqplot-linlog), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/bqplot-linlog
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e83e7326a05aade9cede950794b732d9191d5ac9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e83e7326a05aade9cede950794b732d9191d5ac9
│           └── chunk-001.nq.gz
├── blob
│   ├── 098ba38803519a56bbbd3bbe9b58a898b4be5eed.nq.gz
│   ├── 0bc09cff7670bb882e7e81959f7c9df347ea91bb.nq.gz
│   ├── 124b95f8f687de706d0c78b96a7efb3a86878726.nq.gz
│   ├── 1693d9683ee497cac156db38957f1f7481d9fbc0.nq.gz
│   ├── 171561cd9f1db12604b920823b8dad8dd7b5ece7.nq.gz
│   ├── 20887820b01589d4292c87cb13e076f15e3f0395.nq.gz
│   ├── 2de85709e31dfcc517fae18d1ac9c65bd9a8bec2.nq.gz
│   ├── 3b7429871daf2c482ca1e88c0bdecb3c235f83cd.nq.gz
│   ├── 3ced3581bb601ae91b1e1da4b8f4f520855a065e.nq.gz
│   ├── 4044d5580c7f203d050ff1adb6cf8d1e93e68045.nq.gz
│   ├── 48ee137a343d0f7bc16745a157d1b02a7db3c7e6.nq.gz
│   ├── 4cde75709042f15c207aacd0c5008068b7d53e0b.nq.gz
│   ├── 4d9f4c118fda3bec9f5099fcc45e947bee8dab1d.nq.gz
│   ├── 4f30f59ea796d777a314d2c5ccc7a5652ca1244d.nq.gz
│   ├── 557bc373404620c24c942229d606bc145aae7e87.nq.gz
│   ├── 586acb28dc675e09468f394f73f46ecabade4cd8.nq.gz
│   ├── 5a391e674f07de8e63d8ba56117da3950dadf724.nq.gz
│   ├── 5da44cd175c8d81b98d79976c721a5de17743e93.nq.gz
│   ├── 6aa8cb764fd754711d0eb0b241b66c8d2159c844.nq.gz
│   ├── 72b3b239339f14c47caed7018f53705b5800f544.nq.gz
│   ├── 742804993b10774fc6cd31f4d10170c4e56bd648.nq.gz
│   ├── 771060ed41bdf9c07537d2e1c2fefea64b9c3073.nq.gz
│   ├── 7d1acf85346dd7abfde676e1eda2f9693f502e0a.nq.gz
│   ├── 80478d0c5e3ed265e8be6e1e841979355f079c8e.nq.gz
│   ├── 873da50bbc1d3f163c01d3251ad988602a700d46.nq.gz
│   ├── 88e9ec03794bd6a7a74399b8b3153ccb365ac45c.nq.gz
│   ├── a0d9b80dc54e03e28e29aad3f14f47f8e3248392.nq.gz
│   ├── a7dfcd8f3bba7e4fcdfb65beebb4c6df8c2e4cb5.nq.gz
│   ├── ac253b9406de4da1aef18f1c648f4c36acce6f8f.nq.gz
│   ├── b02fc9f41e6f9f370a8222cb9d22a80d47b21be6.nq.gz
│   ├── b3fd5d799ea0575d3de1007b1c15ba3ce63c0d53.nq.gz
│   ├── bdccc12065cf736eeb87d4ff69656cb088c06f3c.nq.gz
│   ├── c664ee5ff363e82cf0c1890d0ca6e91d8486da44.nq.gz
│   ├── c8f4a142a4996666355f0e82b0c5ff34684fb98c.nq.gz
│   ├── d29068f742d9bcb64a0771ed4d5d84894cb197b6.nq.gz
│   ├── d3f56e5fd15dcfc966afa1aa9dd1992666648129.nq.gz
│   ├── d4b4987fc1cd4f2d0f4483a0b8d19974df3e36c2.nq.gz
│   ├── db3031278f81e3f0c6e9ac586c17cf6430edcb6e.nq.gz
│   ├── df7053eff68c1380c1c131b6851d0617cff4ccf1.nq.gz
│   ├── e18e7cc792812d60bd2889229f8880bad2442d91.nq.gz
│   ├── e321128a5c2c039e96f050e24226b8a593403d5d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec058ac673a4e6fa19c145de20c66ab694336cb8.nq.gz
│   └── fcebfd14fb10868541eecdec81a4788092a8cb4e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e83e7326a05aade9cede950794b732d9191d5ac9.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 51 files
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

[glue-viz/bqplot-linlog](https://github.com/glue-viz/bqplot-linlog)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
