# Repolex Knowledge Graph of UKPLab/emnlp2025-inferact

RDF knowledge graph data for [UKPLab/emnlp2025-inferact](https://github.com/UKPLab/emnlp2025-inferact), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/emnlp2025-inferact
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 980b72d5af356b7539ec5c2d90ebd3a99efaa16f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 980b72d5af356b7539ec5c2d90ebd3a99efaa16f
│           └── chunk-001.nq.gz
├── blob
│   ├── 015333635546f576078c03fb67d3d541fbf61af8.nq.gz
│   ├── 02f107c0ebbb839ecc4828a6db73fd3072422cfe.nq.gz
│   ├── 03f02975f3f5b5ec3dbab85e17bc8ffa3d416427.nq.gz
│   ├── 0dc60a3bab5978476153ea76c0fa120adaa45cac.nq.gz
│   ├── 13d5e9ecacffeefa1e231f6cf4503271a12e88dc.nq.gz
│   ├── 14b81dde5ec7ed0d26ea5286335e5cc6810e11f0.nq.gz
│   ├── 1c4a6cdc00776ec60345364cc238ace47da96f36.nq.gz
│   ├── 229edba242bb190698662cdce6bdacde9f0769fe.nq.gz
│   ├── 2377680d831640053291bf57bfd05f83b3e7d5ab.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2a0f0b2ec87a8796c1f3fbb5686de51b6971234c.nq.gz
│   ├── 2f7ab62a3d8d53697a5b954dcfcbcb861e02ab07.nq.gz
│   ├── 2f7b082210d6f2017727cba09a26552de4a594b7.nq.gz
│   ├── 3cc436302abcd53178654cbbc82f9e1fba9db952.nq.gz
│   ├── 44384a82026e123583b56dedd2e30cb792fd58e5.nq.gz
│   ├── 46954d3f1a2cfb252dbc09ac2b099dc4deff6574.nq.gz
│   ├── 474de749734abcbf4c60ec50077a90c59fe7174d.nq.gz
│   ├── 477a12bc8c1e08ed5f565afe6dfa85f64fbbeb16.nq.gz
│   ├── 48a92cdad5a24f2075a0812e77afcde4260e324a.nq.gz
│   ├── 4d4b7d103e0013f64e4dedd2ad0b2947cc0d11a5.nq.gz
│   ├── 4ff582c5890390f82b965c022d6285674e943ed2.nq.gz
│   ├── 52f444753894a493a780981a7bb8e7e2a748ed21.nq.gz
│   ├── 558e194e36f43c27c531fb9c561b5fef603bf0ea.nq.gz
│   ├── 55cce64d3f602ea102e6dd80d332a2428bbc7d8a.nq.gz
│   ├── 61a0f75c921204896e28a4aad870fa58fe37c627.nq.gz
│   ├── 61eb5c90d1f5b346476ecce72dd1b410d554adcd.nq.gz
│   ├── 6333978cdc67ffe9c67e576d50c093e13ed4fe96.nq.gz
│   ├── 653d4701c151bc36468c2c6e2073d5587922a24d.nq.gz
│   ├── 660a049c66c4572b5bdb2bb23ae2f8303b93cf50.nq.gz
│   ├── 68c7bfa7c7c6df847353cb934177513448a287e3.nq.gz
│   ├── 7109a700caddf77e4ffa00f23a00dfc4c329080a.nq.gz
│   ├── 71c83ab1905cad98a0a4459d9bf839c07809b13f.nq.gz
│   ├── 73442e285512e329b33e4959d4a205e93fde2285.nq.gz
│   ├── 7455e7091800ecd39399e060fa7dbb4c73441b74.nq.gz
│   ├── 77c71c38eba6c19fbd0e4c1f72b3d46b407b7d02.nq.gz
│   ├── 7863cc96aa0c5d8a64ce32f186c92a35e2a260e3.nq.gz
│   ├── 7ae92ebfc202699dba847643804096b768ec52c7.nq.gz
│   ├── 7c7a650d333f55224c57997caf39862798f09235.nq.gz
│   ├── 7d3c04c8a52ffff56055d9a159e2b1d007591125.nq.gz
│   ├── 7f1abb342c8a2851d67bbc3c100b536cb2aeef5a.nq.gz
│   ├── 80990de27dbd461291f7a4bc72b45fb18d15ff91.nq.gz
│   ├── 865745a38249343b92b9bd0118980d3920bc375a.nq.gz
│   ├── 8fa178d6639521bb2b1fd07ddee675c042b540a6.nq.gz
│   ├── 8fbd3fb234cb17750815f3b2e4e39830f4591b23.nq.gz
│   ├── 90a6d1aaeb9ce18fc83598cb4a820df2d60747b4.nq.gz
│   ├── 90fd3174b07eea44abaf8b23dcc62906c7deab24.nq.gz
│   ├── 99ea1a31ac1d382ac3bb4f0c499d26162af04d99.nq.gz
│   ├── 9b139666625c8428274b326f0934066baebf5816.nq.gz
│   ├── a1a5e6cfc3943ee931c72238bc7b4e136d6da86c.nq.gz
│   ├── a237709df5847e41e6e85d0ee2d0e11aedb06d6c.nq.gz
│   ├── a5f66bdff791e826fca24a780f50b6578d06183f.nq.gz
│   ├── a780d3fab4c734014509a889f689a14b3dc0d94b.nq.gz
│   ├── ada8a44ee3e80a40e2b5e5b922e6bc6f5a393a46.nq.gz
│   ├── adc4c869e991f56e8d9539d46a0fa18e52f652c9.nq.gz
│   ├── b3f54dbd4476713a32f1dd4426dd489c267c1c20.nq.gz
│   ├── b8e071b41bde1c8ccb7942104a9e44b8e8b22104.nq.gz
│   ├── b97d4794d5ba93558ecd14d796b3ed821a0b3216.nq.gz
│   ├── badf99b16a05d7bd1f6b748bf57f822e528f490c.nq.gz
│   ├── c02c94b5ff148759491d05e990698aa6ed702b44.nq.gz
│   ├── c194fc6489e77b903bb569bf9cd6633ffb0af960.nq.gz
│   ├── c6718de5c5ae59d2c22141a147f5afba41af9cbb.nq.gz
│   ├── c9b9049be4916d70bd2b4bd519de8af796f6a981.nq.gz
│   ├── caa6ecc8853c8723a881a9731777974c9d57201c.nq.gz
│   ├── cb194bb4d64d7af0c30be7a9eb6624966bc4fed0.nq.gz
│   ├── cb4c5cbbfbc681c3c23aefab8ddf268081a73f82.nq.gz
│   ├── d19465bada332763b5349b5a0fdd12aaaaec1009.nq.gz
│   ├── d50f27ab050eb6c5f3d7af6105b07a65b2f06817.nq.gz
│   ├── d934ecb3a569c25a0f2e592e31fb7c4e225c8c8a.nq.gz
│   ├── ddc54bc99a89702364bd0b4b198a50884c1b7ce7.nq.gz
│   ├── e1305696a2f377d40234e07e03d995fd172a0547.nq.gz
│   ├── e2892e85d07f4bdd9aae43a9df3fd0c2db5d76ed.nq.gz
│   ├── e31457a4dace31df6869747843ecea19d8320fa5.nq.gz
│   ├── e38e25e57922287b86955c25f27f571b693f3105.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6c1cd95fd7a62d54ac71c246bc02d6d044bbb49.nq.gz
│   ├── eb4b01248e402035a91d05a882e79d54a3690466.nq.gz
│   ├── ed3a9d377ba3c30e6eb8b2a35e08e8dc814a0725.nq.gz
│   ├── ee5e71dff7b639074cd30c381cfd2892abe1d165.nq.gz
│   ├── eefbc5d5afb62e3ba214aa6e0fcf2e08ddb1c6e8.nq.gz
│   ├── f2262c1cbf8e7b620fffdcfde43f88ff82bfb38e.nq.gz
│   └── ffd2722afddecf0d63a48ae1d26139638f895da9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 980b72d5af356b7539ec5c2d90ebd3a99efaa16f.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 88 files
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

[UKPLab/emnlp2025-inferact](https://github.com/UKPLab/emnlp2025-inferact)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
