# Repolex Knowledge Graph of thombashi/DataProperty

RDF knowledge graph data for [thombashi/DataProperty](https://github.com/thombashi/DataProperty), parsed by [repolex](https://repolex.ai).

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
rlex download thombashi/DataProperty
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e3f5cc0acd857ef68e245b3e52cfa105640784bd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e3f5cc0acd857ef68e245b3e52cfa105640784bd
│           └── chunk-001.nq.gz
├── blob
│   ├── 088edded65da9d7a0f04adac7927ebb6cf72504d.nq.gz
│   ├── 08d0d59c12fceb50338b47a2f16ea5eb4228f285.nq.gz
│   ├── 0bc9ea444ab1ac9fa3ceb814d5aa378ecb50b0ab.nq.gz
│   ├── 0f46c25d995e7072a9f71e792b66e755260c7e84.nq.gz
│   ├── 0f97b678f2c770205588223ad603cbc176e36255.nq.gz
│   ├── 10124ac0c01dcb6edec32d8fb86e90430280ea63.nq.gz
│   ├── 1180b99ede8de9063db6a324254b63abbca51d99.nq.gz
│   ├── 13aac8e87fb08e3d8747feb4ff9c7a8be06cd57c.nq.gz
│   ├── 20c9887c300d60cc1fcbb662e1e19f375f284d02.nq.gz
│   ├── 2472fec88975058d1b138dd648fba345079ad84c.nq.gz
│   ├── 2b25b5cd805ecd3412a69f6558b189dae382e9d8.nq.gz
│   ├── 33a960a479da60f64a24c63bb0ff45fc745a47a6.nq.gz
│   ├── 3550e7681cb74b699e0856bee5bad141ba288ca2.nq.gz
│   ├── 40757c5abcbf8c6f1b90952694eee5aae4576101.nq.gz
│   ├── 40d3fa4d4138581c278c89194efef826784c7ea2.nq.gz
│   ├── 4a828f2bcf3d9ecbcfd6c0aaeaf9227e4edd4f17.nq.gz
│   ├── 4dca5154128ce812926cddc12c3c623050a0a8d7.nq.gz
│   ├── 4e4f84b6c29037306cdb56e03e6c0172ed95719c.nq.gz
│   ├── 517d754ea589b46096166afe6ef54e5533ce17e8.nq.gz
│   ├── 543576395cabcc830071aa8d3e9f5c68663aebe5.nq.gz
│   ├── 575bf6eef4d0dcbb82cde639ede74d9159720b28.nq.gz
│   ├── 58d8f39fce3a67b2a72fd26d83881587a3a5b975.nq.gz
│   ├── 7613d9ad3398e90c06709e06f93bace62801d6e8.nq.gz
│   ├── 76bc6a7ba68be3ce73b817ebe5e5fdfeb9b13788.nq.gz
│   ├── 76de7a9272153eb182102ce1af2ad57471e9b1ed.nq.gz
│   ├── 778b2ca2c50af5c6e4b3a48ec6e9b59443dd2f9e.nq.gz
│   ├── 77cd05a5b6c966d5b06f4c60ce4bc8cd34971445.nq.gz
│   ├── 784941375501f6dd8895c1eb3da19f75b83fa229.nq.gz
│   ├── 792321caff7c3601cd3efcffccd137848b72ab83.nq.gz
│   ├── 7d8a318349fc4cdacf4397fcabc62b5fe3e2552a.nq.gz
│   ├── 7ea2140a661954cadcdb76d1b1bc06eb24879eb8.nq.gz
│   ├── 7f0b689b66d220d744b0ffab887c75b707cdcc94.nq.gz
│   ├── 81ab44fad68d40ddcb3f1a7ba147308be965dbad.nq.gz
│   ├── 955a454b5fe0dbcba783213b011a5df47d311ac4.nq.gz
│   ├── 99bd8f65d96c48e82e081b075cee85c51f1401c2.nq.gz
│   ├── 9d0b900fc0d059f49b468888f3beed31ef9644d8.nq.gz
│   ├── a0a9b3c8dd05ba1b14f3d3ea07bedaff0a8b3c04.nq.gz
│   ├── a9819c252bd494ecc3d3a6b8df900cea77e95727.nq.gz
│   ├── ad0f293ce2a288057ea07297e21504c7669edfd0.nq.gz
│   ├── af2ff6d54dfd57bdea24e51fc39722ae07b14491.nq.gz
│   ├── b4b6c0f32d16ba4ca406c4af1be16f7cce67a73d.nq.gz
│   ├── b8a41db48568eb8a8b840310eb0603d9e24e7e03.nq.gz
│   ├── ba2547dfa0cb4bc9bfcdba946c6c848c703d3602.nq.gz
│   ├── bab43415753cf5029310fda35ad6cae661e9b153.nq.gz
│   ├── bce701c6ffd30c1d4ce227ba1797c8637c969b4b.nq.gz
│   ├── beb08988c3b9ad602ba5ac7a361514252ee2dbef.nq.gz
│   ├── dff22531cbfa858b3dcdb7911b62b5579e2cb2bf.nq.gz
│   ├── e5390e32b0759821c103f23e566fd15aeda5089a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e98d3e830b8174a7f784067d28cc74ee0d92f8f9.nq.gz
│   ├── f4fb49f80251d86d34cd3833fb013a90062b32c2.nq.gz
│   ├── f78a93ac55f0cd6c65ab59d20a675ff25c8a5a55.nq.gz
│   └── ff3ab01cdcd2ee06713dad8a2df5ac6aa81f0eb0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e3f5cc0acd857ef68e245b3e52cfa105640784bd.nq.gz
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

[thombashi/DataProperty](https://github.com/thombashi/DataProperty)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
