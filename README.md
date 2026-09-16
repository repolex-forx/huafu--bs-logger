# Repolex Knowledge Graph of huafu/bs-logger

RDF knowledge graph data for [huafu/bs-logger](https://github.com/huafu/bs-logger), parsed by [repolex](https://repolex.ai).

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
lexq download huafu/bs-logger
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6f110735ec8f47cc77dd39fd2adcf03336b82883
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6f110735ec8f47cc77dd39fd2adcf03336b82883.nq.gz
│   └── repolex
│       └── 6f110735ec8f47cc77dd39fd2adcf03336b82883
│           └── chunk-001.nq.gz
├── blob
│   ├── 116a6d1ae2c7dcfa878196015b89a819bdbe6cf2.nq.gz
│   ├── 14c323d90954088259cbe3f4f657110297139551.nq.gz
│   ├── 18ea6f58fb54250d2e260ac66ed7728fdf5a99f2.nq.gz
│   ├── 19364b81d170aae84a2fec024a46992203dbdfa2.nq.gz
│   ├── 1a28a6359057be50491277c96521dc398fd6d5bf.nq.gz
│   ├── 25b0f7caef3e2b3679396866a46d509e5d3f5375.nq.gz
│   ├── 29b32d23426ddc2f3f38c0011f410034f901fa52.nq.gz
│   ├── 2a2795b26254227fd6c27ab6afa89f3b29b90fe0.nq.gz
│   ├── 2e5d397a78db4c515d3eaef6400b897fe8998214.nq.gz
│   ├── 34993692c9510cedd818c572a27dbc3d9e0e7469.nq.gz
│   ├── 390305047533b4a1a18edf4eacb70a45569ec600.nq.gz
│   ├── 39367e02a4c2b1fbdf42cbaa5e515edd9d79948f.nq.gz
│   ├── 3c3a65c85b5c207e2625d7a929f9e708d452ca89.nq.gz
│   ├── 4066ed6c0df960527c263efb5f991213484dcff4.nq.gz
│   ├── 48ccd2e1aad4537e6853dba5e08ac324a047f9c1.nq.gz
│   ├── 4a312244cb4cec2e50867dc3166c34f44eb95dd0.nq.gz
│   ├── 4a5b465ecb5dabf3a6bbeea512d66eb9e80f968e.nq.gz
│   ├── 4cdbb9c08da31a76a7ff21b55d109518dba259e1.nq.gz
│   ├── 618ea92be98ec61f42a9a18a0de62d2f7c1f997a.nq.gz
│   ├── 68c7f76dd455b19e81f558eb84ede3b023ae93c6.nq.gz
│   ├── 733c7b17eb959c564ba02d5dd49065df02335da6.nq.gz
│   ├── 785efb805b80cac1ab5cc26c9c59b9ed0d9c3886.nq.gz
│   ├── 80ddc748dc1c02ad2f281544027aab72d904ac38.nq.gz
│   ├── 8fc25868be9e0ef188b4116311b8f81819949738.nq.gz
│   ├── a55d68c62895832456269ace8052aed0ca8d5cf5.nq.gz
│   ├── ab2f535c5cec389a06c261726f6dd5ef504a6b46.nq.gz
│   ├── ab78ed6401a6d645f3c6c28dc10b88e012a60371.nq.gz
│   ├── bb734b42fc40bb4d679649f13d70f347f5f5a3ac.nq.gz
│   ├── c885264e3f01b365151e6c3fef0a9abbd566dd3a.nq.gz
│   ├── d03ca9a2087fcf760f33b1cbba678dcc22411f4b.nq.gz
│   ├── d05a2c832c717282bbf83725d39aa01a0580a48a.nq.gz
│   ├── d20f34ad3d8d53229a0f496e78d3250dc37b708c.nq.gz
│   ├── d5f1a7896eb18757ce3a94e2fc535b216fb328cd.nq.gz
│   ├── da29027be1cfd6c5fb535f6a7c3815542b0164f3.nq.gz
│   ├── deaf210f35aeecf04c4672df98223686afbb5d88.nq.gz
│   ├── e2936eaa15cc73e9d080ccffc70ca71669f9e835.nq.gz
│   ├── eed2106708e5e528fe9e6bbc217b7362d6f72be4.nq.gz
│   ├── fdecda686d44e409547b8d200a7b061714d45027.nq.gz
│   └── ff49248967c19ed255eb68c4c578441042b73f4a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 6f110735ec8f47cc77dd39fd2adcf03336b82883.nq.gz
├── filetree
│   └── 6f110735ec8f47cc77dd39fd2adcf03336b82883.nq.gz
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

[huafu/bs-logger](https://github.com/huafu/bs-logger)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
