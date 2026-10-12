# Repolex Knowledge Graph of strawberry-graphql/strawberry-sqlalchemy

RDF knowledge graph data for [strawberry-graphql/strawberry-sqlalchemy](https://github.com/strawberry-graphql/strawberry-sqlalchemy), parsed by [repolex](https://repolex.ai).

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
rlex download strawberry-graphql/strawberry-sqlalchemy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e1ff9fd05906b6599af08829cd0cee41d6bced37
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e1ff9fd05906b6599af08829cd0cee41d6bced37
│           └── chunk-001.nq.gz
├── blob
│   ├── 00ace60e0185c5c5b5b9acf3ff8e26bfafaf9cd1.nq.gz
│   ├── 0213276714cc09b96ba520f9f03ec41015d0caa5.nq.gz
│   ├── 03ef215bd6cca7b88f08ba0990c314da61a7a9f4.nq.gz
│   ├── 0541f895cfb61557e391a777be4f4fd09b3c681c.nq.gz
│   ├── 10244c9254ff4edf89bcb48293a229940a18ecf0.nq.gz
│   ├── 114d03287a5ddc1979093172c9a06f15f151a9ca.nq.gz
│   ├── 132fc6a3ecc73205b1b8640fa4bcc81454ca72fa.nq.gz
│   ├── 14e46caa6b37ee96c28944bafbe1a965a882aa18.nq.gz
│   ├── 16b7af90fbb6aa43b944734db51f332af924eec1.nq.gz
│   ├── 18695f0563532c3ed9a480f87e3e63ba7bc4b832.nq.gz
│   ├── 226e6f59313909fc91249cb261f86ee5fa25daa5.nq.gz
│   ├── 28cfaacd3f8fe948b8c1cff35b5039d975fde1e2.nq.gz
│   ├── 2ddf98aff7ab624fa4f53f1a4898dcd2e881e954.nq.gz
│   ├── 31655dd9a07b91ed2ed3fae77c164bc3e37b11ac.nq.gz
│   ├── 343e38203e67b124923807cdfcf49201595d1a43.nq.gz
│   ├── 364589da5b2e4beeee34f76641f0cdf85c976cdd.nq.gz
│   ├── 365b64735eefcd75c713901502e9179450484559.nq.gz
│   ├── 38e7dfba63819f9d92930affacbcf182d1fcf8be.nq.gz
│   ├── 3989c5130411f77da5198a165361ea1b8b2fc1de.nq.gz
│   ├── 3c963632027b176c1146e6cca3b2d1aab781d766.nq.gz
│   ├── 41d71a389ffd869cbee9523e0443bad156979dd6.nq.gz
│   ├── 42309727498e7128141ded4f7151744fc50e57d6.nq.gz
│   ├── 5113efb387bc9a3d7508a6b552256fbeab448d21.nq.gz
│   ├── 52de61ee7c748d46ebad2aaa5d957c5e6393fe90.nq.gz
│   ├── 5a208ff438fc0089ec12ff9fa5f562824bea8ff1.nq.gz
│   ├── 61e51d2f1f8715b8e60bb50077791468dc05f43e.nq.gz
│   ├── 62db0e193da81c79307860e00265677e9f255387.nq.gz
│   ├── 65bdb8f6856b9477a0f0615f581372cf83351dfd.nq.gz
│   ├── 687025a2f1483745dadabf1de21c8e1bbc20c726.nq.gz
│   ├── 6e4687f81c798bdfcaa0dff46b04e1b40b083739.nq.gz
│   ├── 72384e2190d8b80aefd4cc5ebdb1a1efef967848.nq.gz
│   ├── 7275691002b0feda824a0b7ba08dd38f194be6aa.nq.gz
│   ├── 736d5228987d375a7f150e4684a9098bcefab3d7.nq.gz
│   ├── 740f723ee21d482d72091736471a6e8b55ad5b9d.nq.gz
│   ├── 76d87f6175559c6aa7de91a7c49a7609e55bd910.nq.gz
│   ├── 77f7d71ca7bbc8214d044f66d7a5173463eb485e.nq.gz
│   ├── 79308d0c134a7a87f865da89d05b35bfb1ba654c.nq.gz
│   ├── 79d0ae72abfcc883b349cbbdc1dfd2847fe245cf.nq.gz
│   ├── 8007cdac1dc65aee3c6a17a3f789e5fd019e0b4a.nq.gz
│   ├── 81995ef41390bf722c0b76444562783b1bf50c14.nq.gz
│   ├── 8338f4a5b857e043e7eb6ba12be0dce59ba039f4.nq.gz
│   ├── 871950df3f80fa9315dcec169c6af0a0a000f62e.nq.gz
│   ├── 8a68ea98a1d2f69b49c246e0185b32483c9365ef.nq.gz
│   ├── 8f51e34a0930eeb56c2da6530c8161f1f99df85a.nq.gz
│   ├── 93b7c119fd04ae96c49570333353bebf076de10f.nq.gz
│   ├── 95da59181bc842e8cdf1bbf2e31ff6978ec419c4.nq.gz
│   ├── a29b2c3d16d795e96f87d13fe8b7e992f81a0ad4.nq.gz
│   ├── a69ca6f671bdc155f6a0d81c22068c7daaa9734a.nq.gz
│   ├── bc951cf703f525babd006426d56b985825e9d41a.nq.gz
│   ├── c27247692aa13989e02c022af67957a28010713a.nq.gz
│   ├── cad2a2adde6d61ce0881e6e9ecdf546d0b506d2c.nq.gz
│   ├── cb17c98cd3be6487c9c51e7488406049cb057609.nq.gz
│   ├── cc2bc776d5389861145493bb3604da0d368a9d1e.nq.gz
│   ├── cd17547fc0e8447f3a13b34d74a012070c956784.nq.gz
│   ├── cd8e0913a8fa9ba3a03696eb3f0a03730d14a485.nq.gz
│   ├── ce258bddd5ede16d05ef3fdb977809e470f62439.nq.gz
│   ├── d0e5a34e2d50bb238845453367a84f023e280a00.nq.gz
│   ├── d2b3182a60ab2956da8e99ead3bcba0a40b2b10d.nq.gz
│   ├── d7b5a5ed299c568e9c184db770288880d5b14a32.nq.gz
│   ├── d93797aa630e9cd5fb4c02b8ecd28de5cfbae059.nq.gz
│   ├── df0abfaac923c878984b0f387e5f3519acc49f79.nq.gz
│   ├── df18f77dee61f9d1bdf322a69863cbfff2d73438.nq.gz
│   ├── e0596089f6a7064e3f0674780f6a027c446fc1b0.nq.gz
│   ├── e2b28a3987e42b745aa5bc87d2306847d35c7bb4.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80ef503b8843dd63902fde483357e778aa6f620.nq.gz
│   ├── ea9f0b4821f16a1ee3c671a4bc138d7d88fd1822.nq.gz
│   ├── ee5ec0a5987532d1208324bba3d9d42157e53305.nq.gz
│   ├── f3e42ce04b5e1f91d8e2c4a42fe10c001734d4b5.nq.gz
│   ├── fa896a913d1b158fbb69947ff73801eb6188be6e.nq.gz
│   ├── fe12cb2bc28c734b48605ba85c60e45a97e5d551.nq.gz
│   ├── fe1c983ed9e0161314b4598094d740ee4fc50a7b.nq.gz
│   └── fe440929885e8d7a3e2ebedec02f84540cbb6c8d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e1ff9fd05906b6599af08829cd0cee41d6bced37.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 82 files
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

[strawberry-graphql/strawberry-sqlalchemy](https://github.com/strawberry-graphql/strawberry-sqlalchemy)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
