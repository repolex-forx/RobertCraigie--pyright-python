# Repolex Knowledge Graph of RobertCraigie/pyright-python

RDF knowledge graph data for [RobertCraigie/pyright-python](https://github.com/RobertCraigie/pyright-python), parsed by [repolex](https://repolex.ai).

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
lexq download RobertCraigie/pyright-python
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 81b795a41ddcc3c77218d8c8e406983e39852285
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 81b795a41ddcc3c77218d8c8e406983e39852285.nq.gz
│   └── repolex
│       └── 81b795a41ddcc3c77218d8c8e406983e39852285
│           └── chunk-001.nq.gz
├── blob
│   ├── 008878aa8c68cd0fdb671312a78b11be608718f0.nq.gz
│   ├── 09a0267614588bdd01ec9733c5361995b94b1765.nq.gz
│   ├── 0afa6e241b4a59ad223697212d5b4f76682acd2b.nq.gz
│   ├── 13c9b1deee88d05b09e8d44628e73b364ef0da8d.nq.gz
│   ├── 1a852eb905ac7f994051cedf282a426f13b931f8.nq.gz
│   ├── 2382ec0106b0a862b4bf6935141dba5fcfc67ca1.nq.gz
│   ├── 2fd17e71274dbd9c7f11fc4a302a4748882eb6f0.nq.gz
│   ├── 350c86e9c12ef56191c0dfb5c89aa80eb90309af.nq.gz
│   ├── 4506749bdd254887a06f17be40a62e020ebf3625.nq.gz
│   ├── 4665883c76d9d70bc5a8de5d7efa5c770ff3a6ac.nq.gz
│   ├── 47f85d7357fe3a9eaee58ae5f2457c6c5d9dc040.nq.gz
│   ├── 4a7f98048820109f1f070368bd010b84ff53434d.nq.gz
│   ├── 4dc864d40cbd4540090661eba94c46198f017f65.nq.gz
│   ├── 5973d35b9479257e8dec5c0146c6049cc90d10e7.nq.gz
│   ├── 59f99e8af15899b4de1e2cb373c247cbba3c6563.nq.gz
│   ├── 63ff15d650705b0846b46efe42387c505049a402.nq.gz
│   ├── 69f4d4f7e057ca881a279412153dc8f4a22bd66b.nq.gz
│   ├── 6e05b2d381cc3eb320d7b60133bbfa77662a1d38.nq.gz
│   ├── 77315a27045e3cf62ac560f16b4ca30a91e0e6a9.nq.gz
│   ├── 787350f72d53b9dd0f1dce08c372c33ccf63f4e7.nq.gz
│   ├── 78b525be7e245e35564f9de30d04f72d264635eb.nq.gz
│   ├── 8afbefe8d878a5769d67dc0cb3ec28bff30b14a7.nq.gz
│   ├── 8db5069d6210fba7f990b64b394f7ec4c4604017.nq.gz
│   ├── 905e20c64c5adb540b551bf0b1b80f3916c5d51f.nq.gz
│   ├── 977042c703076b4802fbcd6a89a2186c2e2e6929.nq.gz
│   ├── 97cbd1570005706454186838ba94277771c73b87.nq.gz
│   ├── 9dd6446ac111c1a7bb199bb9dc92cb4baca9f037.nq.gz
│   ├── a81c8ee121952cf06bfaf9ff9988edd8cded763c.nq.gz
│   ├── b4a24790dbfca0f08a38585ef86f78499ca77a6f.nq.gz
│   ├── c3862dd5a003a00a3ea552e5d1439c0c537489ab.nq.gz
│   ├── c67d0aa63a1a7b43d5bc98b7d2b7151b648f08e8.nq.gz
│   ├── d2a3d8588270d55cdd3fff72bb2e09e3a290bddb.nq.gz
│   ├── d3eaa66d86bdad550819e06e52b4de94cec1722d.nq.gz
│   ├── d57847b97bcba786e92c63ccc11f1ead00e1096d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e811ff008c3c190a2264a895661cbb0a6f0a4c7a.nq.gz
│   ├── e876f9c9d2cdeaeff9a560284b1584b36f2349b3.nq.gz
│   ├── ec0df06a1eb83465488afa4bdfd7b9ca80e332c6.nq.gz
│   └── f8c2f839a18c47d0c1724588c605fc2a310a2cff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 81b795a41ddcc3c77218d8c8e406983e39852285.nq.gz
├── filetree
│   └── 81b795a41ddcc3c77218d8c8e406983e39852285.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 49 files
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

[RobertCraigie/pyright-python](https://github.com/RobertCraigie/pyright-python)

---
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
