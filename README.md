# Repolex Knowledge Graph of prettier/pretty-quick

RDF knowledge graph data for [prettier/pretty-quick](https://github.com/prettier/pretty-quick), parsed by [repolex](https://repolex.ai).

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
lexq download prettier/pretty-quick
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 50557591c65e5e1757f0899b48a4e510b6ee4d9d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 50557591c65e5e1757f0899b48a4e510b6ee4d9d.nq.gz
│   └── repolex
│       └── 50557591c65e5e1757f0899b48a4e510b6ee4d9d
│           └── chunk-001.nq.gz
├── blob
│   ├── 00653193d13952286e86ecbcfa99ce11d172dd2c.nq.gz
│   ├── 09091b382a1a0e88d74202d62b93789791b587eb.nq.gz
│   ├── 13234c157c0877a3edc9eb60e1cafa161569075d.nq.gz
│   ├── 27eb50f8138a05d6e9787a344c630dc17e60c0a6.nq.gz
│   ├── 34ac721b19395f0a96fbf1efcd427c41e31b8c14.nq.gz
│   ├── 34d756f3f1b0e6348c71c997b6c899832f92ba22.nq.gz
│   ├── 3871456de1e304975d48bb2ba35a0649b2019da0.nq.gz
│   ├── 3c032078a4a21c5c51d3c93d91717c1dabbb8cd0.nq.gz
│   ├── 3efdea49739a7bc9eccc85d3ab693062ef9d3111.nq.gz
│   ├── 3f53038f0d8abcabafa521999cf9fdbc0c773a03.nq.gz
│   ├── 40deae8356d549c35f5a3d1ea502c81019ecc9ff.nq.gz
│   ├── 4292f1efde9d14884d9ebeac2ee39e0139442176.nq.gz
│   ├── 45463becdd5d5c76dc2f459be1f32477d1b53eeb.nq.gz
│   ├── 4d349f9827a93761527e027c63972f8dbdb720ab.nq.gz
│   ├── 542b504551df02036891355d051a4784ac57bd8f.nq.gz
│   ├── 54eb855a2a22943bfb26abaf771680c8cc0ab549.nq.gz
│   ├── 5f1fea790c7114da325c497c31c6c2846b342571.nq.gz
│   ├── 69fc8bf0a063b01db24915dabc8ecc605abfd33f.nq.gz
│   ├── 6dde96372e1205ff919785b716043df0b27dc6f7.nq.gz
│   ├── 6e344aed1f53c841379daab16a9c6192bc056475.nq.gz
│   ├── 6fc8c74cfce6373d4e0fd448c26a094e650d486f.nq.gz
│   ├── 7357916c205baf14bfe955993b5355939b300701.nq.gz
│   ├── 7c3f55dbcf38f9134af5077bfb6dbb4da8586610.nq.gz
│   ├── 8392fe51f9271f013e494e6cbb5e38060f42eac9.nq.gz
│   ├── 8d3aae41f4a1bf8d05daac36e2113fbf3e9558f0.nq.gz
│   ├── 9ea52f721b36ca65f95f88d7b1a416411fe4a886.nq.gz
│   ├── a009400a0bf5a5c526bacf49a602ba99b8950493.nq.gz
│   ├── a5174ed25d615083d57a17afaa950f95b42fa32d.nq.gz
│   ├── aba70ec40301b68cd6b73b9f3c8380f329e37375.nq.gz
│   ├── abd85eca5f1de4f0b7902140e1a53ff762c2a49e.nq.gz
│   ├── b333359b1365f17a752f80c0cc6127ac3d7d3d9d.nq.gz
│   ├── bed19b0fa7c2114189255674347274fe43ae60e2.nq.gz
│   ├── bf1ea0c8784459c8ac9abf33c329afea453e2ffb.nq.gz
│   ├── c200595e5243bbc45d827c7e3befa44512526750.nq.gz
│   ├── c240f121764f9c1bf3e4c561e4f5e15ecd0b7dfb.nq.gz
│   ├── c3c2be311887387436d541e060c4f4362e4c4548.nq.gz
│   ├── cb4136c7987c4f7dd121ad3b20d113cf775e4073.nq.gz
│   ├── cc109204df74aac012b505673bb8c912b794ae33.nq.gz
│   ├── cef5f2b6b0a44b1e6233728a27fa945477fb839e.nq.gz
│   ├── cf9055cb4d4997ad8882340ae9515daec4f9c7a8.nq.gz
│   ├── e1ab929f5aca15587229844b19f66a9b4273ad7b.nq.gz
│   ├── e5b6d8d6a67ad0dca8f20117fbfc72e076882d00.nq.gz
│   ├── e661f1ef15b0251be81333a3d098d94f0dca2048.nq.gz
│   ├── e903e53fcedb0b5b2e9f696fdea65784ed2f60c6.nq.gz
│   ├── f39103e69d8097eda87c2140d053e479aee1a444.nq.gz
│   └── f8b4ff955224aeda162e4cf93fb1a4ba9698926d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 50557591c65e5e1757f0899b48a4e510b6ee4d9d.nq.gz
├── filetree
│   └── 50557591c65e5e1757f0899b48a4e510b6ee4d9d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 56 files
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

[prettier/pretty-quick](https://github.com/prettier/pretty-quick)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
