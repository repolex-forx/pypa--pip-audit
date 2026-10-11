# Repolex Knowledge Graph of pypa/pip-audit

RDF knowledge graph data for [pypa/pip-audit](https://github.com/pypa/pip-audit), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/pip-audit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 828e77a4d4aa6bee8d315681db6928771d951a7c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 828e77a4d4aa6bee8d315681db6928771d951a7c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0799db9cce233fd9d92f2e22e42c56908fced80c.nq.gz
│   ├── 079db0335a78adfccbf5806eb99d3a750118012d.nq.gz
│   ├── 0800d3bafa38f81b874a122793e1dc45653db04e.nq.gz
│   ├── 0b8dba148e86028779c634c4bf95aa31b2180e38.nq.gz
│   ├── 0d5eb2ea2ad940c9fe7b71b00f1dbfdca8058858.nq.gz
│   ├── 11c437452b5dd955cb58a35b6f8570447f66dc1a.nq.gz
│   ├── 128650eed00242b38cd0249e216fc9a12f596af0.nq.gz
│   ├── 12cb39d3c7b6e545f3e0b7ce6c60d08aeb9c56bf.nq.gz
│   ├── 1e0533f9cd2f790daaa2d9cbc31bd0e83d02078f.nq.gz
│   ├── 1feb0dad35334d360cd2b3f554831b2debddf485.nq.gz
│   ├── 21bfaaaa1dedf14973e8aa2b171081691bf6edbd.nq.gz
│   ├── 21d9ccb719b6d0a69ef5b6596118ba3d27691737.nq.gz
│   ├── 2f56050805684411a8e178e651f4c9e8e547039b.nq.gz
│   ├── 31666295daa83443ffe4906b675bc74d264f18c7.nq.gz
│   ├── 3a2af179bc1515cb45ef20db5af87dfd6b34f31d.nq.gz
│   ├── 3ae19ed532390df20525c0207183accdb4e22093.nq.gz
│   ├── 3bd6d55d5d30577721710039959d6807c1b9569f.nq.gz
│   ├── 3ff7a95abc38bd9a268ba281eb3a1dee3c1ea010.nq.gz
│   ├── 43694e8fc81a28fb1b58a2636820763c467accac.nq.gz
│   ├── 4392508e058a20eb1e7b0367c82250b07faef0a1.nq.gz
│   ├── 462530ac0bcc0e3cc14d756c90456c3681737135.nq.gz
│   ├── 4c3882ad8cfd65af1cb1647e908d30691c41d6aa.nq.gz
│   ├── 4cf152c24ec6bc5ea0d593289caa62b9a9638953.nq.gz
│   ├── 504f6d485c533b798026b2db8926aed62c5db19e.nq.gz
│   ├── 53fe54ddeadede378b15cbb05bc6d1c5f5713400.nq.gz
│   ├── 55d02c1164293cac5a37aa90d360e737d1da56de.nq.gz
│   ├── 561e58baf958bbf3d8c8b9cf3436da9ebb812995.nq.gz
│   ├── 56bfc1256d08ba5bf0fa1de18b293a8ac474162b.nq.gz
│   ├── 57cec452a27c0b2e5a959b547e13a5fdc2470d05.nq.gz
│   ├── 60c9e065d7161bf8d3dbbc916fb6e73ce6643222.nq.gz
│   ├── 640380fdc92aedf5ca7b6250d89f853b4d679f58.nq.gz
│   ├── 697f11e2309fcefd75c2392d096dbcbb03c4df1d.nq.gz
│   ├── 6de6a61493a9165c628e024a8c757eb66271789a.nq.gz
│   ├── 721b0b04b9e287ec5db8f5a812656c6c4ee260ef.nq.gz
│   ├── 73b5bd389a6079fde6f06385d33e86bf30f29efb.nq.gz
│   ├── 7747af3b9fd9ddcd2e7379ca8e008eacf8517137.nq.gz
│   ├── 77964e0cce1adcea9ba5e30c1981bee88a087fc4.nq.gz
│   ├── 8541ac0a6b675e9d8bc6d9e9418d07498763d824.nq.gz
│   ├── 86a7452921d3ec9af07c2d81adaae203a3764137.nq.gz
│   ├── 90c1deccc13dcc8f9bd26cf57d81548929e9acd9.nq.gz
│   ├── 935d4bb0e6c539fd1be6967dd7b3c4b281a94c87.nq.gz
│   ├── 94f41d9f1a6d822841305f5b164fb4992d594649.nq.gz
│   ├── 9847517ebe0e08fe8eb782756f91d68f283a0bc1.nq.gz
│   ├── 99d601fe396d6223acd99e45d9bfc69360eacef7.nq.gz
│   ├── 9b1ec254aca3e414ec2022fd28850d2489b326ef.nq.gz
│   ├── 9f07739a0f42f5cc270a13c973d750e220c7364c.nq.gz
│   ├── a5b5060ea2e2bc4a36489a1bbd26f0b44252ccc1.nq.gz
│   ├── a61d8bdfc93796c09ecdfe2910307c6d03feb231.nq.gz
│   ├── a6be8a70675d3d6c00bfe7969770e37e8e83f8d7.nq.gz
│   ├── a8f0faa7d145a3c7033d5f941e77ff98560ecc33.nq.gz
│   ├── a9d11b702bc5f919e07041f9058b8d4d399a64dd.nq.gz
│   ├── abd5ae810be128452c0244321dfea596f9f5b0b4.nq.gz
│   ├── abf2f24675e4dad2d97cca6995c0772084cfde94.nq.gz
│   ├── b3b5f855ab05c19681b24e450b00ea0e727a84bd.nq.gz
│   ├── b6537bb522840bbedfc1a3e102a55f44423f2646.nq.gz
│   ├── b93d61fbf8f113b21ddf154a96e905d81b13fdaa.nq.gz
│   ├── c59ae530d47a963c5cf3ed66cd42dd34dd89192d.nq.gz
│   ├── c9a5a510d9f595dc13d7581164af32de7361b937.nq.gz
│   ├── cdae908819a7416d014b8b750090e77babcc83c5.nq.gz
│   ├── cef93e6558d4e21adc5410677a32db225f42705b.nq.gz
│   ├── d851586dabd7811265bd1c4d652463f753d465ff.nq.gz
│   ├── d92417d998abef298f1c4bceb441da81c245d2ee.nq.gz
│   ├── d933e6716192e30d8bce3a127a7f8e11c4341630.nq.gz
│   ├── dc5c63307d60ec23190c8873f3ce1e1ce7c57ff0.nq.gz
│   ├── dde1d0ba91703631d78121c132b2214e58e75a3e.nq.gz
│   ├── e5e0358fac3a2c035ab83da09ca72fce5899b456.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6cac8323327c3b3f285492214ba28d2177d504e.nq.gz
│   ├── ebfea93e2b1fd200a5988b8161136d4c2a357dbe.nq.gz
│   ├── ed3812b8d3835829ad901ff0b02aa3ded70e1105.nq.gz
│   ├── f3df8c963f25b94c6fac2271bbe44a8a49b68352.nq.gz
│   ├── f433b1a53f5b830a205fd2df78e2b34974656c7b.nq.gz
│   ├── f46fa22d11ee39e4344340bf23b6168f10df785c.nq.gz
│   ├── f5dd1f34ea6beb3a49b5f79e62bb7c9aeed8880b.nq.gz
│   ├── f749d1b5a7d024c9c1509b98f778589bfdb4464e.nq.gz
│   ├── f763a76a2bfcffcf001eddca407fa754c8c1b536.nq.gz
│   └── fb489eb89701eb94471d6b74146eabf50f1ee206.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 828e77a4d4aa6bee8d315681db6928771d951a7c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[pypa/pip-audit](https://github.com/pypa/pip-audit)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
