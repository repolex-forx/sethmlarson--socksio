# Repolex Knowledge Graph of sethmlarson/socksio

RDF knowledge graph data for [sethmlarson/socksio](https://github.com/sethmlarson/socksio), parsed by [repolex](https://repolex.ai).

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
lexq download sethmlarson/socksio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e69158473125060879319368e9465d7881cee0b8
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e69158473125060879319368e9465d7881cee0b8.nq.gz
│   └── repolex
│       └── e69158473125060879319368e9465d7881cee0b8
│           └── chunk-001.nq.gz
├── blob
│   ├── 017aeec82a8ff57ec057bce004ede7adf361670b.nq.gz
│   ├── 04f196ac782bad0d3f50899e002cf4adb14aa3e3.nq.gz
│   ├── 0534e86071d4f931c7fbe6a7e1ac39b2a8c1a342.nq.gz
│   ├── 0e16707b2b3822e9bed0c023bb9b4ddfc69661a3.nq.gz
│   ├── 18124c4f3dbc724a8a1a5fe9cac2fb364ab1f9e4.nq.gz
│   ├── 2856277b987b0b66b1d2cee0071addcb78e16917.nq.gz
│   ├── 440b200ae7d1456f13cd378e0797253fad7bbe88.nq.gz
│   ├── 455dfa19587b761b82b328e782b7e985a5565ad9.nq.gz
│   ├── 4a9fbba3293919918a14b9fce3a7b4eb71c26843.nq.gz
│   ├── 4e9484c939ff0a321c07677e2dff6357ce06edfe.nq.gz
│   ├── 578b63033465eb700c5bcfbc9cb9528f6a885103.nq.gz
│   ├── 58df365c932ee57dea2685b4f4db974f925f2b11.nq.gz
│   ├── 5e90a6b7738a3a7143f140a6a51e8f97e36a1755.nq.gz
│   ├── 5f668e94ab8b8af2e1eb87620bdbdd6a0f1d0b93.nq.gz
│   ├── 6035f2cd2dbaa0e93e561ceec5f13b019161137b.nq.gz
│   ├── 73676d30e5a48d120a8a354e9dfd0378f1a3b776.nq.gz
│   ├── 90036c7694e3350565e088c7550d5f2e698ba138.nq.gz
│   ├── a4de0bff1812fbfd1f17622f746ab2bb18ec1ec1.nq.gz
│   ├── a6ace45da97648132137e3a8077a76ee2ceb0de0.nq.gz
│   ├── b3bcd986d9c33f9b0f244c7799899cf8e352fc8e.nq.gz
│   ├── b8f9fe174bb67e2a54b56d73be1f4f5398e27517.nq.gz
│   ├── bab50f0716dae772ca9e69f9f622fec498a58666.nq.gz
│   ├── c0c219be58d95f4851ae22d8869fbcc47a5d0b29.nq.gz
│   ├── c1b95eec0517f7f332c5307323729f9950a566b5.nq.gz
│   ├── c43b7d88ae0d5d60c59e99c833efa337416d634f.nq.gz
│   ├── c4e9dec3d9eae9264b991d15a7f2a66836753281.nq.gz
│   ├── c6f0e39ff5707be27b64af0d193d5cf7b6b36a0d.nq.gz
│   ├── ca6054490e8b96f75b688657d6f7ed047663c1b4.nq.gz
│   ├── ccb491383ebb0c89f536ab09fd8b34e3194e0d5c.nq.gz
│   ├── d71765030d5cb473fa5ab423fab8d82c11ee062e.nq.gz
│   ├── d7c204008fb78256bd3231f1cae0668ccadedfbf.nq.gz
│   ├── dfbc81e7c09f96b012f27790b4b8d13a727c4787.nq.gz
│   ├── e3ba32690cd877553119086dc9be0a1ad30bd717.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f5c05354c4a9a2da64ccf61331de9f6e202f95.nq.gz
│   ├── f4b30d19a1a32edd4cc5d0db47da0a737b39964f.nq.gz
│   ├── f7f2a2570715ce49c553f9d7de4a3bf9a2f6a44f.nq.gz
│   ├── fb087d2689b4642a31ea533502442424548ab6f8.nq.gz
│   └── feb314e4f283ad92d84ebd8c3cb023f45cb8a89a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e69158473125060879319368e9465d7881cee0b8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 48 files
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

[sethmlarson/socksio](https://github.com/sethmlarson/socksio)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
