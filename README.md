# Repolex Knowledge Graph of coleifer/flask-peewee

RDF knowledge graph data for [coleifer/flask-peewee](https://github.com/coleifer/flask-peewee), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/flask-peewee
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3e39055bedf449feaf6fc6baa31c6373900f7828
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3e39055bedf449feaf6fc6baa31c6373900f7828
│           └── chunk-001.nq.gz
├── blob
│   ├── 070e0fe220691b57434730855b5df6db1d46b86e.nq.gz
│   ├── 0aab305c26efe3dadbff06343ed80a8329ccbffe.nq.gz
│   ├── 0abf822490743efcbc2171556aa9f6aa4406e856.nq.gz
│   ├── 0c8164bdad54d4c4a4c95fc411d7ce5893dbb9e4.nq.gz
│   ├── 0ed951b156d9caffc363378f73d8ce638302944b.nq.gz
│   ├── 10511f395b09d734c22254b8f0a85594b2d2d832.nq.gz
│   ├── 1156dae80463fd710d80ea8604d1ba3887d4d7d6.nq.gz
│   ├── 1206e49334d5a675ab94d2cde3a4980209f39ce2.nq.gz
│   ├── 1762ad51d6cbe5b92421a14dc34c98cf983c0c9f.nq.gz
│   ├── 18b3fc53ef5f78861ba7cdc38b81345688ab8091.nq.gz
│   ├── 18c720f804c6f034cdb1ee02a616cc1e271a4007.nq.gz
│   ├── 1a3bef532700e7f1a10490f3077dcbeeb17269fd.nq.gz
│   ├── 1bd09de7857d26ff4e2e4ab2b3da5491589633a5.nq.gz
│   ├── 1c6df309edc8fd9c5aaa21d4a7fb867dd73ba8ec.nq.gz
│   ├── 1d79b7f681a5629e7dea06eb0992a4a7757c8f22.nq.gz
│   ├── 1e7af40d58834a67889627a6e047e8a1186688cc.nq.gz
│   ├── 203ca20b82b2d4a688b14b172e1cbddfb98780ca.nq.gz
│   ├── 22bc54a3e0513c4d894c9803b079baf4b2836424.nq.gz
│   ├── 22c62bc56d8f81a90d7db266495f2374bd25cc8e.nq.gz
│   ├── 26821ce77b8b9fbc93894b1f212f1774c7f4f127.nq.gz
│   ├── 30ce73f12e4eb79003246a9f0a651cd0540fd420.nq.gz
│   ├── 32b8bd36a1fbf5f5ae1e7a17d9d0a9455009d0fb.nq.gz
│   ├── 3e633920d39f3809e9919ff3ab4d1b850fc860fe.nq.gz
│   ├── 3f8e94e560bb196b0e0b0951d0d219e57955ea2e.nq.gz
│   ├── 42b7e32a99a4d682ae045a4993dff6997353a207.nq.gz
│   ├── 43b26b126513285c94f597d935bc335744fb312b.nq.gz
│   ├── 45c921d5f96c7bc7a7eb61173be8f1707cb07a9d.nq.gz
│   ├── 4ae059d6331cac21036b8704ef304012870c52bb.nq.gz
│   ├── 4f5907d4f14bc483987103334d46ed746eab2027.nq.gz
│   ├── 531de8ffa5c592981e34a7c78b045d8edb4729da.nq.gz
│   ├── 54b9c58bc5ba8a1d0ec85b218f6aac05b17269c0.nq.gz
│   ├── 5f6fdf643461afac6882c104ff1ded875e0dd7e6.nq.gz
│   ├── 624ac4b0684c78d3fac92eb5534903432fbbb408.nq.gz
│   ├── 6518dc99ff4e82c76c9f4c1b7efd4ec53342d0a4.nq.gz
│   ├── 659c2f93cd25830ec50b2a327ac3c6a79192c2ee.nq.gz
│   ├── 69a1d5601188b60da51fdc3d242a8f917d888d70.nq.gz
│   ├── 6ab0eb819e3940f9c0e69c47aefd9c94fc034a0c.nq.gz
│   ├── 6bf220b44d5ef4b0990d4962ae820cc0e57016a6.nq.gz
│   ├── 6c6c351450ad45050096bfeb5b8cdefda7d65c07.nq.gz
│   ├── 723ffa727ac938fe426bb520c91b408646577078.nq.gz
│   ├── 72cc2d51c2f1d346f5cbff7b3023d4f2ee688047.nq.gz
│   ├── 77b84a252888e442fe5cfdb7e0eef6cc37cc1c5b.nq.gz
│   ├── 789433e6820872483f1aa772c4dcfe6940538ba3.nq.gz
│   ├── 793192e02d49c5d41bf9521a64c6585f75af5fb2.nq.gz
│   ├── 7ab4f4d8ce7a33fcc6a463a9be39f11f03bfc339.nq.gz
│   ├── 7d08dac06d64c9c6147ab8f7e439e0f812fb87c1.nq.gz
│   ├── 81cb90a1740caba4b6976f2afbe0980f50cddc38.nq.gz
│   ├── 840a369d68db65b32690b107e91fba20dbe4bc05.nq.gz
│   ├── 84cfb6144c0503006662502bef5ab8ebd4bc7d00.nq.gz
│   ├── 8c6aeff1dc078dceb5553e121886a1ad4fe3caf6.nq.gz
│   ├── 8fb0a8767140a68fbe4a4f14017ea88b7ce9d661.nq.gz
│   ├── 958df4422ac806343ebdd9c46d947feba0e6a16b.nq.gz
│   ├── 9b0c0d4ef0a5c423168aae53a8715049c7c0f886.nq.gz
│   ├── 9f099090665ecfe65ed4d6577b9c84bebb015ca5.nq.gz
│   ├── a8277bb9e83a198d74d38d2c857f00b567f94836.nq.gz
│   ├── ada52e4d0062a09c27726f3472f75acc49aed7b7.nq.gz
│   ├── ae7d7df842bc102886b6ae3f35df3156b81684bd.nq.gz
│   ├── b2a7b6a7e93fa0857260e92a4b02eb7c9b71a8ee.nq.gz
│   ├── b3d3ab0a0816d6ba945e65deabec688dd0334a1e.nq.gz
│   ├── b48c1fd132904689b5dfa41bba89f8b482464269.nq.gz
│   ├── b52fb68498ae350201b00657c1eae4a464fa32c2.nq.gz
│   ├── b5ca39bc1ea7d9c27dfb80b986a59acb14594468.nq.gz
│   ├── bf7f6d6d951a4ac02fa4a68d5705311c9cbbe2e8.nq.gz
│   ├── c3fcccc3560bd42061590803c50593b148544bfb.nq.gz
│   ├── c47bebbcc0d60216a2a3c9558d9daa70ed9f6293.nq.gz
│   ├── c5738ac9c26ee130c7b54ba54cf7490fdeacbe38.nq.gz
│   ├── c7071f7d7565764a9e82e156351ae814e000fc2b.nq.gz
│   ├── d21f5b7d421ee0da05cddb699581bfdab9c14970.nq.gz
│   ├── d49b3013c80ba98afbc98f607bed547ce32d7388.nq.gz
│   ├── d7ec23f4b5b3bf83ac8334a964313b2ac1feb882.nq.gz
│   ├── d8b398ce97f071e1b2f0c82ba02652218b56c813.nq.gz
│   ├── e0ac217cec3b9ac6947c96baeb1a31642b7eb4af.nq.gz
│   ├── e900ff9073b34251876c0173a92a39c78249e1d0.nq.gz
│   ├── ea5c7dcbea4822f7ed271522ababf605c1513a84.nq.gz
│   ├── ea9348d5ebb64bb5396b806184827e68dfae632a.nq.gz
│   ├── ed3936ffa12c6ae2bde280918ad2d5721eb40d18.nq.gz
│   ├── ee6990b3492ce7108fe2cd766df8cd092a34f840.nq.gz
│   ├── f25b5db00b5de166894e490608b218df5e8ddbc8.nq.gz
│   ├── f3bb9886c70d21cb05facb7295ab147cf876aabd.nq.gz
│   ├── f3f9fa2c6f2988737a1b2e5639213f9e69226136.nq.gz
│   ├── f8e3929b77e0084fca4b72b1124a2ebb06129e75.nq.gz
│   └── f9a3e86f99833bc4f8f3e9d857bbfe8674c2ff77.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3e39055bedf449feaf6fc6baa31c6373900f7828.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 90 files
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

[coleifer/flask-peewee](https://github.com/coleifer/flask-peewee)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
