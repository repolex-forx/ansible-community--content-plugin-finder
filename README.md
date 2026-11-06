# Repolex Knowledge Graph of ansible-community/content-plugin-finder

RDF knowledge graph data for [ansible-community/content-plugin-finder](https://github.com/ansible-community/content-plugin-finder), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/content-plugin-finder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 671352e136d357e17c19e2bbc2dcc853d38c2e69
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 671352e136d357e17c19e2bbc2dcc853d38c2e69
│           └── chunk-001.nq.gz
├── blob
│   ├── 004b14525dd58b0a703408bc74a6d79eb591fa7e.nq.gz
│   ├── 01fcdee7aea0235274b1cc5c698b78c9240a089b.nq.gz
│   ├── 09c31861443cbbc90735a314f3745c4222d7754b.nq.gz
│   ├── 09cdec16687ec48295da5a2737f4e27f0a1426f9.nq.gz
│   ├── 0a01dfb83c7793a7f56441ac8c25c332c2130640.nq.gz
│   ├── 132334dd1773392191b1a8520225959a51c9f54e.nq.gz
│   ├── 175762d7c82041a92feedacf5d3f25964da783b5.nq.gz
│   ├── 1d48cc6436079d9e8c3eabab6009438a6ab98df7.nq.gz
│   ├── 2ba88c3f82dbb72d301af69989b9282dd838c40f.nq.gz
│   ├── 2c719f2a5ff01da3c8702e2ebac95434fd70f9e7.nq.gz
│   ├── 2eb8f9e4ab0442d9f10686e60a750ab0d512e838.nq.gz
│   ├── 3353d499f899cb21c4ede438f51a549afce6c405.nq.gz
│   ├── 33fbf5528990bcc1d6c5ed30d8b3591743a60257.nq.gz
│   ├── 36d43c1c55207b79c8b6ce9e8ba7eadad24ce5fd.nq.gz
│   ├── 386f68d108d8102acc675d50ed852d87d845694a.nq.gz
│   ├── 390f250af7317d287eebb0f948ac43cf870344e2.nq.gz
│   ├── 39857ca05fafccbd3cb31c9a69edca749bd50bc5.nq.gz
│   ├── 3c6d2d67e529dc47b2ee8ee189c26a7993788e8a.nq.gz
│   ├── 40ecaf21b499c9194fddfc0d54e299ebdce5517e.nq.gz
│   ├── 41c9cf4500765298a4a4db323321bfacceb69a29.nq.gz
│   ├── 43b9631c17c0241949627fc7bfc6457953d06e73.nq.gz
│   ├── 45b83c35eef8aa5222936a0a33e3119365679990.nq.gz
│   ├── 466bde1d6e24f47456fdcc5df13f7cba1ac56720.nq.gz
│   ├── 47afa02d4b680e9c743b3eb8514008892c587cd2.nq.gz
│   ├── 4d860f5ac479cb809b8c691453d0700d452e35ed.nq.gz
│   ├── 570085edadf27814af892bf1dd5a5caa5570b94a.nq.gz
│   ├── 577dbf55b8e15037354bf282934af2a872371850.nq.gz
│   ├── 57fce559013dbbdeb2b507a2c9e440b99c038d3f.nq.gz
│   ├── 5ac405917b1c04b2bd9d6bef06a5e645c002d0bb.nq.gz
│   ├── 609d78407d561b74baa3ca8f01b0d306c645e915.nq.gz
│   ├── 6e78c8eb9c23d4d5ddf735aa961c7609881b5a51.nq.gz
│   ├── 70c66e777140a9047da559ac34f6fa15b3b66f26.nq.gz
│   ├── 71525f3e2cff017eceb0fbeb55102279b3368b47.nq.gz
│   ├── 768fc55ffe023e0d5e83775d0c7d703801e60896.nq.gz
│   ├── 79990e5a2755f14643b9b1965dc0706f05f1126b.nq.gz
│   ├── 7adfa0f989e7324575835e4f3683ebef4264e72e.nq.gz
│   ├── 829d82347818b50b82cc4dea581a5224570ebcb4.nq.gz
│   ├── 82ae5f79208010b386627814e1540fc5c71964f7.nq.gz
│   ├── 87cb664c055fb4a3065f7efcb3d4fba475e948f8.nq.gz
│   ├── 8978a3dbc44207be5129967e2be225288d8cdf44.nq.gz
│   ├── 8a31343407a400eeea55a86330ed6eecd1efd65b.nq.gz
│   ├── 8b68729767036be6987408dace6918e3fdbabf21.nq.gz
│   ├── 919c70ffb4250cc5cc2364134c84aa31aaf516bd.nq.gz
│   ├── a3dd59e67cb27947a68b9db83bb2c01633b39592.nq.gz
│   ├── a4adb478efcaf20b36533168b0c2713bb2c99f01.nq.gz
│   ├── a4b0d1fc68b255ebc482a76bbea956f7092c3ea5.nq.gz
│   ├── a730aad3e507a7ab81ca56fd74245c2c82e2e329.nq.gz
│   ├── a97ece874eecd8c8a8db82c88f37db1f30b570d5.nq.gz
│   ├── ae0acbe8f633d21a7d75f844a63b17d087219522.nq.gz
│   ├── b5c3196755330ec888eee14c38c0e3e0c51fbb9e.nq.gz
│   ├── b718b9fbeb96c11614c822681b0a338146a7c7d5.nq.gz
│   ├── bafbf158eb1792539263e829a419a58a76d01971.nq.gz
│   ├── be3d3453adef933e4c14c3e2edc6a82c0b7d57ef.nq.gz
│   ├── bf8176c1ee332798736ec40ec1ceee09fadb38eb.nq.gz
│   ├── c20eaf5493f1bd077435460371e72eac0c7dc185.nq.gz
│   ├── c3e9a078c4981b50569ad4b4a15a24a54193af06.nq.gz
│   ├── c589139b33a75d70b15c26b6e2825a360cb81a8f.nq.gz
│   ├── c6dd5eaa0f9b0e009cdfe10d44d7620a3fbb40f2.nq.gz
│   ├── ce60e66667270049b99513d72088da88cd6c9f08.nq.gz
│   ├── d08d36bbcac53cdafbf5990e94c811adebb51e77.nq.gz
│   ├── d300726c3bb6daa7d6babb9d907a6ea891735072.nq.gz
│   ├── d41a8b17a931da4d9c7a5465094c117a98046cc7.nq.gz
│   ├── d8325ae74bfa1fda771ea335ddd3082226ee5503.nq.gz
│   ├── d95020b883d2e6ed6bdd34d1fe73e4ff7e0d319d.nq.gz
│   ├── db4523ee67f60ff1738d3ed53a5f025012c3196f.nq.gz
│   ├── dc3a6aa166acf51f1d507b174add686674463ce3.nq.gz
│   ├── dc6cfd83f6f413fdfb611fb1d435bdbe91779960.nq.gz
│   ├── e0f00da49ae40da0fee83798c28c2297f841b403.nq.gz
│   ├── e15523b39f3ed214719ba23b3932f801b978afab.nq.gz
│   ├── efbb789249d9496d6b826e97488fa86f8cf8ee78.nq.gz
│   ├── f13aceea08d1d5f4bb14b2a5023b35f5c8a889d5.nq.gz
│   ├── f49a4e16e68b128803cc2dcea614603632b04eac.nq.gz
│   └── ff426873ffa140a260cbf0597b391c2f26e46f07.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 671352e136d357e17c19e2bbc2dcc853d38c2e69.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[ansible-community/content-plugin-finder](https://github.com/ansible-community/content-plugin-finder)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
