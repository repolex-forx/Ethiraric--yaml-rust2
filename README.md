# Repolex Knowledge Graph of Ethiraric/yaml-rust2

RDF knowledge graph data for [Ethiraric/yaml-rust2](https://github.com/Ethiraric/yaml-rust2), parsed by [repolex](https://repolex.ai).

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
rlex download Ethiraric/yaml-rust2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 635ffd17f2bf3c095c8881b53441a7c3d968775f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 635ffd17f2bf3c095c8881b53441a7c3d968775f.nq.gz
│   └── repolex
│       └── 635ffd17f2bf3c095c8881b53441a7c3d968775f
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d7464f8ae1bfcfeb4d5a70e3e3ebacd54829e8.nq.gz
│   ├── 040a909514d17db66281e0ef7f53941fa68df11f.nq.gz
│   ├── 0a0951775a634b5e259bbe0f5a7f171829c5af5d.nq.gz
│   ├── 0f182a90f75bd07f3e800db12b095dad043536b0.nq.gz
│   ├── 1555dde9ef5fde912750d507322e293e096c4e30.nq.gz
│   ├── 1c3c452f3f1a440ad53e103e828da5641cf05831.nq.gz
│   ├── 24a55290230031cd5ed781c76abe14d62e6c315a.nq.gz
│   ├── 2e9ddd7577d8f3827135fb67821e954289102b53.nq.gz
│   ├── 41aa64286cccdc33d051dabc05324810091a6c5d.nq.gz
│   ├── 497dd420c8e008fc615bd16bddb212b804b282ef.nq.gz
│   ├── 5423777ae980b63150df411471599e062dd31c33.nq.gz
│   ├── 543bb48fbae10bdef8244094ce71213bd2a4ed44.nq.gz
│   ├── 544b1ec632f4f219c5c89e60d3de63992271bb2f.nq.gz
│   ├── 5b3ee4c1c3a03c0b1c0700ad98e4bb67f3161fc7.nq.gz
│   ├── 5c772eccd90c7764a008aea0dcafb778abfb3ed3.nq.gz
│   ├── 704b7b6bc276f5d33bc152077e7747d3a7e820c3.nq.gz
│   ├── 747e9b99f339c749f899e3dfb6a3029aa3763984.nq.gz
│   ├── 75e3ef56ae72a4fe1ca63a6995cd2d7ed4cd8fcc.nq.gz
│   ├── 7728a0ff870cc759b4b60e18c9b9149d90d51e06.nq.gz
│   ├── 78d16ba3fc1eed1a27d62e6d0c3da029e3e0786d.nq.gz
│   ├── 795f7bccf653b35e2ce26c7e6436d2503beac748.nq.gz
│   ├── 82f81bd0aedfde8da0c57401602689d7c2c4766d.nq.gz
│   ├── 885caab0a698d3f065e45e077876d473b28b275c.nq.gz
│   ├── 90e68e3d39af9a0573efa0aef0fb7f0049bfe81e.nq.gz
│   ├── 91b81ae66935e4e84da80d78c52ca54eaa278e77.nq.gz
│   ├── 9e211de7e4d1b707c3da1ba7802dacd7c7b7ec61.nq.gz
│   ├── a53e138bd2da7eb9b113fb0ad629ffcfe681ac9c.nq.gz
│   ├── ac33f9cb93ccfe4b6ddfe159dd0fb88d77588319.nq.gz
│   ├── afaa1e3593b0077134fbb58afcdbd29f1e270d05.nq.gz
│   ├── b585c59281b72ab7b252c6da51e0d0bad8cb55bd.nq.gz
│   ├── b9025b5bd668da02152a61fc854a2e2c1b4a0bc7.nq.gz
│   ├── b986067c585ac85eafbaf96466e64134cb1e4f52.nq.gz
│   ├── b9e990b99a388b9846c688296be9222ce09ecd8b.nq.gz
│   ├── bb50b3b3cca1cd25b1de5243e0c40a9f9410ae89.nq.gz
│   ├── c01e291f560c8caab7d7437de98f6299f69945dd.nq.gz
│   ├── c1411cb0166bb497afc7f6adff197a7e7d23f5ce.nq.gz
│   ├── ca0b5d9024102deda1e9bbc2e8c82afe86ab53f0.nq.gz
│   ├── ca554467ee1f5883bd8b344ecf10faf16123c16e.nq.gz
│   ├── cbc1e88b5210bbb45e1387e221562629b519bd0f.nq.gz
│   ├── d8526fb304790091d8d6aa612834be76ef5319d6.nq.gz
│   ├── d980bea5026ec23da191050c277ea7207ec4fc10.nq.gz
│   ├── e06bc2a880195daad2d864a25b585c060bce918b.nq.gz
│   ├── ec4d3e025582bc4323989594ae7eaf627697de5b.nq.gz
│   ├── f2d11ffbfe8d74e85db3dbf4c09e54e908b768f7.nq.gz
│   ├── f882efc4fb7f712f2d6873f053b9ff47ce9e97d7.nq.gz
│   ├── fdf2549aee7d9530beaf1f437db63f0e083b547d.nq.gz
│   └── ff311ba6fcf546a593848bd528bf4126803d5e80.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 635ffd17f2bf3c095c8881b53441a7c3d968775f.nq.gz
├── filetree
│   └── 635ffd17f2bf3c095c8881b53441a7c3d968775f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 57 files
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

[Ethiraric/yaml-rust2](https://github.com/Ethiraric/yaml-rust2)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
