# Repolex Knowledge Graph of PrefectHQ/prefect-cloud

RDF knowledge graph data for [PrefectHQ/prefect-cloud](https://github.com/PrefectHQ/prefect-cloud), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect-cloud
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dd3c8da4d51758e944b59edaa1d313ceffc8ae51
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dd3c8da4d51758e944b59edaa1d313ceffc8ae51
│           └── chunk-001.nq.gz
├── blob
│   ├── 07bf79c5d4215481b82be88760701b370e8dd09d.nq.gz
│   ├── 0ed076479127119bcaaf08e1144ffc61a31a0d92.nq.gz
│   ├── 1646a0918501ce4e1e5312fac8a9e33b6a28e46e.nq.gz
│   ├── 164ab28c12221895a5757d869528bb798655fc7a.nq.gz
│   ├── 1a7e6d761b45afca2f53aa38eefa6f6b9e33edf9.nq.gz
│   ├── 1be923de30a471a5bb1849cad239edc30ba489ce.nq.gz
│   ├── 20cd9aaf249b24481186381b92c62dab3047a55c.nq.gz
│   ├── 239a6e81d666a9fb3ad15c6ae999acda54bc1274.nq.gz
│   ├── 24eec221b5a25c98eb56434c9c38713d7046d961.nq.gz
│   ├── 2aa9714a97f2b95d3ec39d2c48818adf530c9511.nq.gz
│   ├── 2ab546986fbd5517ae2afdd25a6e9dd30d208eaf.nq.gz
│   ├── 2b99b86debcfa9fb694d0d594ba04178ddbac8f7.nq.gz
│   ├── 321ed5839f3379b5f572e222a00cc8960c1cf98b.nq.gz
│   ├── 32d5a29074dcfafef8630a0553c1218d44a2eb9f.nq.gz
│   ├── 37e06632e56fb76f5659ab2eab51cb7f332731e4.nq.gz
│   ├── 462831cd694bc17a4fccfa5f2f14402334508c9a.nq.gz
│   ├── 49bcd1649984e8da196bd28a889a2b96bbe17160.nq.gz
│   ├── 4b0c8406c7d4e22d4a3d903fee445f73d20cc7b7.nq.gz
│   ├── 4c5c56d9c370af3fe94552cb4f7b1ce0df434ed4.nq.gz
│   ├── 51a48a3f3b7b61196e0bf3814e9708c829bd007d.nq.gz
│   ├── 5e3707f214110d517dd050142a8da86cd165b1df.nq.gz
│   ├── 6195d3a29ad0f1245974034a875e54110dc16756.nq.gz
│   ├── 69e857d30104cd810443f9fdc1b9795ea4c29195.nq.gz
│   ├── 6bcbf9136b6db11a8a0a4fb5ccf610cbe9c99821.nq.gz
│   ├── 6ebe42a5dba31254c5a0da1a78b0fab67ca149a3.nq.gz
│   ├── 719cb2c9822a63b949c0856a4675060273fdf0a3.nq.gz
│   ├── 72f07d7afd68f07acb86cd6f026377b47275cf89.nq.gz
│   ├── 769abe923def8ae0c43ece40b7ca6fed8fb59189.nq.gz
│   ├── 782d202c6af7c6eca197d62b7497248d71da8bfb.nq.gz
│   ├── 790c63f642ba8db024e5b7f116987e8315acac61.nq.gz
│   ├── 7c99ab0c8e015242600fa4874cb4f78ae84ca994.nq.gz
│   ├── 7f33886b327210e4d9d58c14ac3b70f71db7f382.nq.gz
│   ├── 8155113978f66f36f0b5c9c3296c8607d64923f7.nq.gz
│   ├── 8a78280dafb776dce97a2d185f53219f81dedd79.nq.gz
│   ├── 8b6c7df50e0a9698446fc90f96dfa807d37f651b.nq.gz
│   ├── 90985546972b156f1af1be5169726a284ca0c9ad.nq.gz
│   ├── 942544e9fceedd4cfe326e3ba1de2dc9a4c65c98.nq.gz
│   ├── 94c659a3fa4f4cf6b276821f465858e4fbea20a2.nq.gz
│   ├── 987b028fc3970f4f6435e4e2023afd2b2204bdc0.nq.gz
│   ├── 9bd4d064c0c0b8aba1bd42f5d327a34d2095cf75.nq.gz
│   ├── a46e037a3dae53c8aa982b5a1c9ce8b0bbbc3976.nq.gz
│   ├── ac66cb2c1e48bce51b487069e8bc82e9024deadf.nq.gz
│   ├── ad433158806204f178549721e8bd299a9a787f3d.nq.gz
│   ├── b24723f7bc02c5f526216614efd1510caeec3b83.nq.gz
│   ├── b2b44b449bbd74ea811b4ca96362d5de34170f3a.nq.gz
│   ├── b6e1a54f8f345e565d88ec976fa59c83e7b8214d.nq.gz
│   ├── bb337914d8586e40e409f50997d4fe7fbfc19b00.nq.gz
│   ├── bb43333613712b9348f0d7c6ae0d2673fcf6dc10.nq.gz
│   ├── bf2f28ce428a7e5cae040025db48e3ff79a14bb5.nq.gz
│   ├── cf2b779f40bcb4e1426bbf3903af846d93173f27.nq.gz
│   ├── d0bfcd322c89adaba536b19e99784d3255d1421c.nq.gz
│   ├── d28723156aeb2b6ef21016b93ada0d7d7271e820.nq.gz
│   ├── d460ebd7779d4bb2958ac1e738fd18de2da6c6b3.nq.gz
│   ├── da1b7daa3c85628325ab0a56c7f6566504be0b0e.nq.gz
│   ├── da68aa293bbc3a21e0a155745eba6895b5ec2661.nq.gz
│   ├── dc2675e7403b4eb3571649abb59c67927fa7a3fb.nq.gz
│   ├── e26f39ce5466cbc534dbe8e28824afae1fbbf9a8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c306b764a5af7b4b660ea085906e0d281a3efa.nq.gz
│   ├── e71379f759ab9ffa6d383fa00130dd69e7cddbe4.nq.gz
│   ├── eb7b96f3089a805e30c05898c6058103570a33d4.nq.gz
│   ├── f30307b3ac09d334274ca562fad3eb8750b5af8b.nq.gz
│   └── f3abad5c0732850bc9d12b7c20f1d299403bca57.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dd3c8da4d51758e944b59edaa1d313ceffc8ae51.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 70 files
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

[PrefectHQ/prefect-cloud](https://github.com/PrefectHQ/prefect-cloud)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
