# Repolex Knowledge Graph of agronholm/typeguard

RDF knowledge graph data for [agronholm/typeguard](https://github.com/agronholm/typeguard), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/typeguard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cb8cee7a17af49498ad2465bbbdf8bfa8bf41a53
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cb8cee7a17af49498ad2465bbbdf8bfa8bf41a53
│           └── chunk-001.nq.gz
├── blob
│   ├── 0059cf749bf8d412a876634df9eae96205695eb0.nq.gz
│   ├── 07806f8af9dd3253ebdb5710b67e73124aea4941.nq.gz
│   ├── 0d2a16729020451a7b5bedebc802e2c33cf5433f.nq.gz
│   ├── 184b93b27e6c38cd6f2f01424872ab64e0694239.nq.gz
│   ├── 1aff8d08b80f1be40bca648dc9d7426640eb5937.nq.gz
│   ├── 1b741dbfeb0a387092b8c8f4236f6c8e157ec7c6.nq.gz
│   ├── 1ca310613093737aae74e81000a9a4e56b42d6c4.nq.gz
│   ├── 1d0d80c66d788e2f8f5e24ce14249319c54054c0.nq.gz
│   ├── 1e57ebcc8feec205e9539eda1666cd78de92edd7.nq.gz
│   ├── 24835651795e4679422ec6711009308da8301da3.nq.gz
│   ├── 2490f112c1370b4907f54b6019bc1f9fbd4aa0b3.nq.gz
│   ├── 314145644c5361f4a57a555f28e28ae24ddeaad8.nq.gz
│   ├── 39d036c686a9b5915d0676a2a40b96121ed7d5e1.nq.gz
│   ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
│   ├── 3ff838d0c3592b8f641fee1dd2fc8606dec23abb.nq.gz
│   ├── 45a2f73673edab66a13ab5de206142341e996f10.nq.gz
│   ├── 47c433c8a28fb7440944059c211a8cde757b65a7.nq.gz
│   ├── 4af022e7cbd3d187d9ab9f6850b541984254c209.nq.gz
│   ├── 4b9f88817a2833a45e519365b8e9fca9095e543b.nq.gz
│   ├── 4d2be78f34c2545132cf7a7af856bdab7ebf2549.nq.gz
│   ├── 5189106abebcee0eff788cab7dd9bc8774ea5b4d.nq.gz
│   ├── 565288aa55228425a199bc51e47db77ab186417e.nq.gz
│   ├── 59324be0e637303f9d8b0d3fefcdb74b9cdda2a9.nq.gz
│   ├── 5b09fdc92ce2be6c0f82416357425412798bb943.nq.gz
│   ├── 5eae774194e4d2352e3c9f4495ee6dc2218907d1.nq.gz
│   ├── 625437a64990b5fae898c9c98fe9a7bd6be90cfb.nq.gz
│   ├── 6358bb09bcfe6adb096c6449d7a3f0ef7f075f39.nq.gz
│   ├── 670d8e62940f7cd672128ffd2668056694d43d8c.nq.gz
│   ├── 68dbc98d2e9e61f25bbe8adcea05d8df3028bced.nq.gz
│   ├── 6b887b8c9be8c1c79e028c3d4efd8e48ad4dbbec.nq.gz
│   ├── 6ccb15de312bda070dfa45e62d07c5252e2db680.nq.gz
│   ├── 7de017771142a3401a1d53487f66e0b1306f8ccf.nq.gz
│   ├── 81af366436cab38f446d8cf2a131b9b057251e99.nq.gz
│   ├── 91401895be2945c6fff5418eae74baeec40ec21a.nq.gz
│   ├── 93f7acbc186eadce5d2c49a58e76f0543619b802.nq.gz
│   ├── a3e451dc3dd4d2dbddf018f5b4c2cf62053daf7d.nq.gz
│   ├── aa76d7462d109d83266964e437b886405b9db98c.nq.gz
│   ├── c3097640147aa4ec14d22a0453cd95a6d8d74008.nq.gz
│   ├── ca8114938041aa9cd04c0d43c6eeb00d5a929043.nq.gz
│   ├── db0e1f045f021db921e8f78a6a4551bc0e4a4c1c.nq.gz
│   ├── dc8a350aa47191d760435199ab5443de1af11a9e.nq.gz
│   ├── ded927b4e01d94bf7631276e16bbc9ada59937c7.nq.gz
│   ├── e0b362860ef58284be037cce17c680320552c245.nq.gz
│   ├── e14e68cae5fca56dc11f9c1b9b41c5080ae3c9c2.nq.gz
│   ├── e4d0aeb53cd5dcac982406c662b719825a84b612.nq.gz
│   ├── e57a8422ef9e89f2a17a6839ac210b5ae0e8250d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d22d4bb418bde6c7e628f99384da32f0b046fc.nq.gz
│   ├── e7a4e294c968140f6f61bdfd113d8168920a475d.nq.gz
│   ├── ec93022f57bd683479b06c0f0067721e4fa48413.nq.gz
│   ├── eeb4c82c67ef63d74de7f9f141487cc21e28a889.nq.gz
│   ├── f01a07419b875b93f0a17f868e4b1fa55ac52b68.nq.gz
│   ├── f1e09579e1b44148855436c91c0f9fe6067d1082.nq.gz
│   ├── f358f45ab369cc0895e0130fc221ef3433b37300.nq.gz
│   └── fa8000eee7e68945f589eb083078b2d6a452e86a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cb8cee7a17af49498ad2465bbbdf8bfa8bf41a53.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 63 files
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

[agronholm/typeguard](https://github.com/agronholm/typeguard)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
