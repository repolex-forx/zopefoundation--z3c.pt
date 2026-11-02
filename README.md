# Repolex Knowledge Graph of zopefoundation/z3c.pt

RDF knowledge graph data for [zopefoundation/z3c.pt](https://github.com/zopefoundation/z3c.pt), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/z3c.pt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 33396926cb9ba9a014318883e6f4f9de4ccc6b04
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 33396926cb9ba9a014318883e6f4f9de4ccc6b04
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c85f5f2961101129b80b781a2173b05568a1c1.nq.gz
│   ├── 03388722dd90ccd399b65e3210870611ce4ccfc0.nq.gz
│   ├── 0be5e902b87577ddf974f3c48118c9cb5cc97dd2.nq.gz
│   ├── 0eda7ab53e2521bb401202c4c467c2b0e23542e4.nq.gz
│   ├── 16ae81b87c45e8ab9e2e0937ae637fb61a7f2f51.nq.gz
│   ├── 24abe20450f9d4d1ac597f73f41cf7828de1429b.nq.gz
│   ├── 2806c164989aa9137a6c1860716ae9abccef75ad.nq.gz
│   ├── 28578e2c3f59b2a3c8b964cd5313e0b203e7b533.nq.gz
│   ├── 2a6db51c46338b83904ac1b4911744ab2cfabfbf.nq.gz
│   ├── 36dff8a15435b71d9fcda52de846b72b48cd137e.nq.gz
│   ├── 37b81180e9e07eae8d8b32728a5b90599f73a5f4.nq.gz
│   ├── 3c4f0826ca7482ae97752c1f857c2e0d2977fa91.nq.gz
│   ├── 47e2a6790aeb4cd990f371fd8a87a221c1aca199.nq.gz
│   ├── 4ac62f3906a12bb0ee912d0802e796a33afdf5b9.nq.gz
│   ├── 4fcf82cc5e6de90ad87ed08a91d7fad7a705bf40.nq.gz
│   ├── 623fa469a6a921299e79918b06678a76f9042013.nq.gz
│   ├── 62459277e2c118b424650ee91da069e2e7159be2.nq.gz
│   ├── 62d24ee26646d1b17b0069392e15c2364d17d4f3.nq.gz
│   ├── 724255e2acd0bb5ead2524fa3dbfd7ba6f8595b2.nq.gz
│   ├── 7353fa2d99e3762e14d2bfafda1faad7c2b81363.nq.gz
│   ├── 7aa4a014ea0dfe3f591bf1383a8bb10ce05e8b04.nq.gz
│   ├── 7ab98ae726a825ab1259fa12fca5c06d29a7d323.nq.gz
│   ├── 7eef95cfc16e34d86a822bbf2aee43f193f4ff01.nq.gz
│   ├── 801718f6a566b1bf71046f819e8876b9d318770a.nq.gz
│   ├── 8c95e162b38d07ee5c1ece2db3e868ce7302d27f.nq.gz
│   ├── 95e290048cf972393918f3388c41cccc06b7e007.nq.gz
│   ├── 95f89aa8140d0eb74cfe897bfedd917f87a7ada3.nq.gz
│   ├── 9b5a319c4585148f9b2b5f63ba9c0b0209bebd6d.nq.gz
│   ├── a04afc470e47c36948000aed41b8441c88fe4b6c.nq.gz
│   ├── a6b15dbc60f7fbe152fc3b70f142ab68d07e431b.nq.gz
│   ├── ae7a161f9413d996124a1b566bceb635c1b304de.nq.gz
│   ├── b8581dd898cbb33e63961b4d181ff0ffbe5d03ee.nq.gz
│   ├── c1c71a9f6884d96a28f2a3fb90ef01028279ed3f.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cc7beec9fcdfb773955658b418e5563825ace9ba.nq.gz
│   ├── d25a2776822c0e2c490ef3d10069f639ff817477.nq.gz
│   ├── d34fc07d5b1ebbf1f3317bd8bcf205d5f6e60ef8.nq.gz
│   ├── dbc1316d0853f025526b9d850a6bf29b72cf62db.nq.gz
│   ├── e184fd8f41cbc229060cf69967d916bf6e2ddf2a.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e43456b4d7926c1f4ccdb9bb89f082ea1e5b43be.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7435defa8646c7a5d5c19529d2f2899bea107e5.nq.gz
│   ├── eab05ba7214edb86777bcfb7e5329f446586786e.nq.gz
│   ├── ed2c8f9c5d0ce86298e164915d8318a59c48d076.nq.gz
│   ├── ef19043a7a91826e5fb16ea731119c16296584b2.nq.gz
│   ├── f507feda73c43de02c9268ef502bc4c3a2ebf32d.nq.gz
│   ├── f64e71ae6e908f44f30d020def6a7afc120c23e1.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   └── ff2752bbb7dbb7fb4884382418cb760a74ec4bd5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 33396926cb9ba9a014318883e6f4f9de4ccc6b04.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[zopefoundation/z3c.pt](https://github.com/zopefoundation/z3c.pt)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
