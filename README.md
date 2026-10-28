# Repolex Knowledge Graph of databrickslabs/discoverx

RDF knowledge graph data for [databrickslabs/discoverx](https://github.com/databrickslabs/discoverx), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/discoverx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 176ae3351be20629e15ced7d251d785f242b5be0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 176ae3351be20629e15ced7d251d785f242b5be0
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ec2dcdb258ff4ac0d27adadc25f4c00d466238.nq.gz
│   ├── 02fda99599c757ec1b8383f88fd7c60170fd18be.nq.gz
│   ├── 08638ed465dcc98d3039ee46055690ec63428ef8.nq.gz
│   ├── 09034945b2418a44e92ab9aa1b6dcc183959bf82.nq.gz
│   ├── 0ab54fcc0afef00b2ffb8287166216eb75058ad8.nq.gz
│   ├── 192c88eb1986aab52bf2fa9863d16ec567d9d08b.nq.gz
│   ├── 1b8645b61d9638989fc3aea04e074bb2cd50827c.nq.gz
│   ├── 269639a4944be6c8b088669264552e7e8b0a8649.nq.gz
│   ├── 26c614f954a77a4fd5b87c90ba5105361c7f171f.nq.gz
│   ├── 2767593dcd17d3185a3a6b9523dd8ae5a358fd8d.nq.gz
│   ├── 2d70a3848c2b82b6551417e5a637d095644b2ecf.nq.gz
│   ├── 31ca684ee725fdf4e46bf7356b7dc44d9f36cfa5.nq.gz
│   ├── 361035614c865d3db8afa552dafd82bad3964d67.nq.gz
│   ├── 368e52b4ce8d651f44b346411255666f39f4d472.nq.gz
│   ├── 3f97fd79b6184e728f3ea1488ff2e5d0730d6c43.nq.gz
│   ├── 44d8a113b2139f2063c8e2d443f8185744ab1433.nq.gz
│   ├── 4c7e1a9639f2eab7966c698d3a592fd39c31af89.nq.gz
│   ├── 4cac62ddb53450abd2dae824f36ca2ddb65cebd0.nq.gz
│   ├── 4f92d3e7def82b36509c12f2e7abdc5c412889ec.nq.gz
│   ├── 54ecbadc9cdcaa7d6f82bf7b2291e2f94c81ff19.nq.gz
│   ├── 58f321524031c40b839690065fdaf083cc95bf38.nq.gz
│   ├── 6247838aebfe2732ca1477f78eb8706420e16eb4.nq.gz
│   ├── 63aea52013de81036a2fbe083290aadbb2a7440e.nq.gz
│   ├── 68809d4379dd2b2f7b43b25169efa9626c99d514.nq.gz
│   ├── 6e57350d40364788f4048e57dac93843490f0075.nq.gz
│   ├── 766f72bec7aa471d106c03ad8e44d8884889f454.nq.gz
│   ├── 76f8361cc01ee2888c71f40ba80ef14bb02af35c.nq.gz
│   ├── 781307805c73016559c0d49dcb3c466cca70913d.nq.gz
│   ├── 7b098c45a13613fbb76457d4b680e4e50fdeb481.nq.gz
│   ├── 7d3c94030b46aca47ba0d19e1bcaf8f34d02a7c4.nq.gz
│   ├── 8003cde8471c9137448297114560147ee9fae210.nq.gz
│   ├── 8338abcc9e4df3669462b036344b35c6519feddb.nq.gz
│   ├── 87d79046d692b2e816e7d847f69daa6a59c02743.nq.gz
│   ├── 8d712172f2cc63460246b79a444a486531999413.nq.gz
│   ├── 9166f45afa7004c0847c4076ecb0ae6b41e72055.nq.gz
│   ├── 9233b4d878177b520eeb82772a51a89ade35335a.nq.gz
│   ├── 967a243e5e0abd95acc529c86142d8ea1799b6a0.nq.gz
│   ├── 9894ab436c77e0213717c77fefc7467208bdb9dd.nq.gz
│   ├── 9b19f563566ad6291c2c74e1d5440bec673e46c5.nq.gz
│   ├── 9b92a5abc3e086ad7725912274bf87083eaddffe.nq.gz
│   ├── a0844343aa42ba2eed03d0a7f568d26b712a21d6.nq.gz
│   ├── a0f2c7b3feebbacd58c0a4117bcca97f93e70747.nq.gz
│   ├── a59f36131485c8f5045e5bcf617f7a40d6423e81.nq.gz
│   ├── aca1ebb825e0a4a4383be7c8b527a9a4a1f0f9e7.nq.gz
│   ├── bf41e4c09d5fd6fdca67c20bdcbf95b90e4ccd8f.nq.gz
│   ├── c311231ff5fe14483d8b0d8c1c4db6b00a3c7db6.nq.gz
│   ├── cbba2653bd743ad36898dc572854e967854bd410.nq.gz
│   ├── ce83fb17caa5b2963513b7e33fdf2aaaeea6d813.nq.gz
│   ├── d252f52c82e52b81e9c2d3eada56b58a90b5d9fc.nq.gz
│   ├── d3226ca4f9d6f09d2b25638a2444dc2e08f77abb.nq.gz
│   ├── d840d3cf0b8937b70ea8410a73e9f482c66dcfff.nq.gz
│   ├── dc30b46566e0c538ad0ce27d42e1eea1eef0d54e.nq.gz
│   ├── dc6d2f3ba7c77982162242fefd94b8256df57da4.nq.gz
│   ├── e3abacfb2e4344c998c4f0e1f1baa6ce1b6b9bf3.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e765058af326f427d96cd6dbd83dd33cf184969d.nq.gz
│   ├── e9e7d41214fbc5e516e4af8445c6bfcf0bfd0e66.nq.gz
│   ├── ebeee87364bb549ea8011f846dc7bfca53e5bea4.nq.gz
│   ├── ee407ec08f07ef7b7a778f44e1b6bbfd9f03fbe8.nq.gz
│   ├── ef471202c086e25066dce5b25f141985404b55ad.nq.gz
│   ├── f4867121fd915391f9e4cfe3b9a4f857fdb580ec.nq.gz
│   ├── f5af6c80a9d0c4be1092015279e4a785d7f2ad05.nq.gz
│   ├── f739702a619c113a9e283547823b0d92e76852ce.nq.gz
│   ├── f94f7f7e1ba5d503ce55e2d2a2ed4f09f8c9eaf5.nq.gz
│   ├── fba2f20b62138ceee677c32dc2f53d9904f7a289.nq.gz
│   └── fd531197142a8aa7bcc309918cb4624bb9103de5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 176ae3351be20629e15ced7d251d785f242b5be0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[databrickslabs/discoverx](https://github.com/databrickslabs/discoverx)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
