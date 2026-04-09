# Repolex Knowledge Graph of typicode/husky

RDF knowledge graph data for [typicode/husky](https://github.com/typicode/husky), parsed by [repolex](https://repolex.ai).

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
lexq download typicode/husky
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 799e84b716d0e03db80db5d5b0dcdd15b9d555fc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 799e84b716d0e03db80db5d5b0dcdd15b9d555fc.nq.gz
│   └── repolex
│       └── 799e84b716d0e03db80db5d5b0dcdd15b9d555fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 03c9fde1c3addf66cae4eddb44e845f964dfc363.nq.gz
│   ├── 049c9dc4e89fd8fbe1ca07d8ccbc0a8ce28f98b9.nq.gz
│   ├── 05741a87f03c7688ffa8b7296c6a85ce45f0b559.nq.gz
│   ├── 05fc710b3d4541f3ab6ecc473e5bf60a6719616c.nq.gz
│   ├── 07052a046bf601ab9fe0663908d7e2c6e3581aa5.nq.gz
│   ├── 13ecf4d0edcacbdc55fd0b3ec6e0397badcaf328.nq.gz
│   ├── 145150c051407719d768ab72f9919509371f2e7d.nq.gz
│   ├── 174c968837d8fa4eb174806ed7ada9b20daf8b50.nq.gz
│   ├── 1d03b798b5d34e48b223141723351c0ddd15b293.nq.gz
│   ├── 1fc807ac3ffa42ca3dee4dc8bd4d1bda04ad3a6b.nq.gz
│   ├── 20ed889161c7da39102861b70b6997d307ee6b7d.nq.gz
│   ├── 244311baa08bcb859bc8f06333fed8e86260dca1.nq.gz
│   ├── 25c081b149453a0373e07980099076e6552c999d.nq.gz
│   ├── 28e0d591253e43f367326eb91adfe5774c93779d.nq.gz
│   ├── 294bf0d5f7de11fe372679286573032f4dde0e86.nq.gz
│   ├── 2a4cd301ca9bf102c05985b3da00674a6dad84bd.nq.gz
│   ├── 2c0f99203f6b0133c6a8b45416bf57a205c3c8d4.nq.gz
│   ├── 2e2edc187b9c1f87b17a64bfeabbccc168944fee.nq.gz
│   ├── 2f15a6822f9631e331a3d6317c50abdcbaa435de.nq.gz
│   ├── 325e8565ba166a600e6b6b968b29ffe882432a1c.nq.gz
│   ├── 39634fbc0fed1002779de336ffcb689947884157.nq.gz
│   ├── 3c5c7563bae039a4c2073f27947630b6a7cc534d.nq.gz
│   ├── 405cda7dab3dc59734133b6df48b3eff15fe6367.nq.gz
│   ├── 49559e288531e2b865e9f43aa93e0c085a6589c4.nq.gz
│   ├── 512137b6e39345cbb0524d2cb895b7a404bea7be.nq.gz
│   ├── 57a398ddc0939c8c343950725e338aef616082ce.nq.gz
│   ├── 60b25f80d788ce59aebba04ff00bd9ef5b0bddb3.nq.gz
│   ├── 658983e3d238311b6206fd98258420000bfc6d56.nq.gz
│   ├── 6763b14350f1568fb72298130df31dac07056c4e.nq.gz
│   ├── 6d7f087fe022d995374376b8554d79039ab89dab.nq.gz
│   ├── 719dbbbfe14539a63b76b6e64d08df6d226f83fc.nq.gz
│   ├── 72a5495a823e1cee4843542ce1532f66546b01ac.nq.gz
│   ├── 75e90bf3e21e951677215946ba5f7ff6ef47218a.nq.gz
│   ├── 76efb35e19f6e1112bddc6b9f24becb4361ef096.nq.gz
│   ├── 778fb0b7106025b89bd5c11dc5343fc7e82cc8b3.nq.gz
│   ├── 78171a7442b844e901a9a0e8663e219191073f8a.nq.gz
│   ├── 8079e733a4928cecdd246fafc33dc09d9a992b6e.nq.gz
│   ├── 80f6aac79d2a97ded5da5a1f209e1e9cff3a789f.nq.gz
│   ├── 84847607b3a2ca7bb0c949f8029fc3309d939e4d.nq.gz
│   ├── 8dc29c69fa837a37c731198d47c4d21b90685f09.nq.gz
│   ├── 93b6bdafa970e3dcc5257807980481bf4ebbc9c3.nq.gz
│   ├── 9a4184528d6ea4ab2f86c9690270cea83308d5f3.nq.gz
│   ├── 9cbcece4f6f44a9c6e868f941e7ae1ec08e43723.nq.gz
│   ├── 9d373e3863ee8dd7c84a82ea1bf4ff4593ca42a4.nq.gz
│   ├── a30f64b36f05db0b7c309c6cc719adc18800389b.nq.gz
│   ├── b240269b16c8c55259e60a2dbb9515260ca38da5.nq.gz
│   ├── b9d3810bd03383dc259d7dcc2443c49d3ac2efe9.nq.gz
│   ├── bea622a8039b13abd52729e112dac81cf906e92b.nq.gz
│   ├── bebf0d50dc52548ab0cb2d937fffdd0e3de0bd15.nq.gz
│   ├── bedce1b6212b906fb8b64778e18bbd4990ab5c0a.nq.gz
│   ├── bf7c8964081d7b5bf726888b67ad93b7586d022c.nq.gz
│   ├── c48012b6d8f1545157d518157f15d3ede0b10a35.nq.gz
│   ├── d177a35e7dde01dce22aa893a722fe96079fbaf9.nq.gz
│   ├── ddefaf3d953d88bac2d1fb6c7c375cac59e0381d.nq.gz
│   ├── ee5474d1b89cc2d7a97de3ffe0ad8a24aefe9df9.nq.gz
│   ├── f7c631453f8bffb6e614bdc85418358455a7f712.nq.gz
│   ├── f7d2bd23f20fe3c7f03292549906a172eeecfe5b.nq.gz
│   ├── fdf509ad9a74e76a7b5ef9f3661cc686d4f62e99.nq.gz
│   └── ff513ea27e34be304d989f76a6c678a5553a837a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 799e84b716d0e03db80db5d5b0dcdd15b9d555fc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 68 files
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

[typicode/husky](https://github.com/typicode/husky)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
