# Repolex Knowledge Graph of jupyter-server/jupyter_releaser

RDF knowledge graph data for [jupyter-server/jupyter_releaser](https://github.com/jupyter-server/jupyter_releaser), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/jupyter_releaser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 46ef93177dcaad76034e9baf9e39cff17e41942a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 46ef93177dcaad76034e9baf9e39cff17e41942a
│           └── chunk-001.nq.gz
├── blob
│   ├── 005414a9c82f92a7a1a6e8f9fecc5492bbcf00a2.nq.gz
│   ├── 05b4b6826cd846341a5d56ad99095cca734b2685.nq.gz
│   ├── 05d5313a5950979cb6ca7f77503ff6e91b96a475.nq.gz
│   ├── 079ab5a32188eb489eac401a929b531ac2b24665.nq.gz
│   ├── 07b8365ce9cd1da822d1db415394ba6777cf781a.nq.gz
│   ├── 08b6840f5602c4fa7fb1ca1df139e90b558f7d64.nq.gz
│   ├── 0ed82270308735e33ed5dc78d3455920c1f1bf82.nq.gz
│   ├── 0f65d10bf37915110037f4de18f28efd54868e42.nq.gz
│   ├── 14e66a7627cc9d9f0aab4e3b43c84fe158b02009.nq.gz
│   ├── 15c5b1d207adcde642efc94a68a44775b64ab450.nq.gz
│   ├── 16b5e91bdcebea9f50139c1c2413d45a89755701.nq.gz
│   ├── 17947663205f2a42a4608885dcb9d9bd530ed7a1.nq.gz
│   ├── 1862a1bb954f877545bdd30eaf554d5adb2a0209.nq.gz
│   ├── 194e9190239cac970d8f32603745d62bc6d08289.nq.gz
│   ├── 1b6543e36ee63f487c1b92fd66c864f6c9fa5233.nq.gz
│   ├── 1eae94954879f9b1048ea49bac9ff76cb503a953.nq.gz
│   ├── 2202903210b8f822885934cc3793c583fbfa2f7a.nq.gz
│   ├── 221a5265bbb1e3314bad08e2010f98cf4af9c1ea.nq.gz
│   ├── 260fe49c71a2623269a9c584b84fa9ce39f4aa94.nq.gz
│   ├── 2a704ee7d5bbcb58ec5546de7dd240f004c9dc6c.nq.gz
│   ├── 3267df407ea7c181b26c6078898ba2d2b04de42a.nq.gz
│   ├── 330b704eaddb2d2b4a6168baa5ec20fa624cf203.nq.gz
│   ├── 3575db1440d5d93fd2f12ba400896c766ec95221.nq.gz
│   ├── 369bc8ba021d2aec4efa257aa1c038a120e9771d.nq.gz
│   ├── 373857061287b9d596c6a42d9be2eac2cff12992.nq.gz
│   ├── 37e942e1a1ad3b1f817ff9e926be6d5165ae8671.nq.gz
│   ├── 3e890e9cab21e32e56cd2d03ba3d1026816182a8.nq.gz
│   ├── 40496da4b222fd118c1b1499bb64f36d098f86b6.nq.gz
│   ├── 40761c2476851bc2ba97ba08bbdea9d51ee93066.nq.gz
│   ├── 4093a3fe959867506ead7165b801884642c531cd.nq.gz
│   ├── 497b5e8dcf1780301cb808e4dc9d3f318b731403.nq.gz
│   ├── 4b8025b104188902a306eab9cb7fc9034d100dab.nq.gz
│   ├── 4eb36f219afa21d0c32030ddc88a6167df9557b4.nq.gz
│   ├── 50c97a47edc492618ffa663ea72797d4e90df48c.nq.gz
│   ├── 53054c742ed0c760b643f72db8ca261b9bc8d5bc.nq.gz
│   ├── 5da11561712206ab86ec2546527f0c2a5a8ddc9c.nq.gz
│   ├── 60af4c5f16741c7c2fe17cdd9718ae5f6d56d8a4.nq.gz
│   ├── 632f6a56c942bce4eed84a3dece317da2eacaed5.nq.gz
│   ├── 6396fffe0e3af287b412f9b74b4dc9662f40dc2c.nq.gz
│   ├── 67ecd988641591ea0ab8cda684d8ff78e9157810.nq.gz
│   ├── 680a6f33c270f77e5a95c8b9b30e6ce8ac4352db.nq.gz
│   ├── 6e48db6aebd3de4d36ae410488a99b4d558068fe.nq.gz
│   ├── 7225a6e2458bab607faf5a44414eb174969e1596.nq.gz
│   ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
│   ├── 75840d8cf0aa1fc5afb78dcad72b9c0cf47c675b.nq.gz
│   ├── 7d59117d5c060cab1819f7733fef4f8e323a7793.nq.gz
│   ├── 7f7b4b49243b4dbf0388c38883096eb978724ca0.nq.gz
│   ├── 7fc052692de054286e2baee8ae9b11861ed8a930.nq.gz
│   ├── 805a8dfb68c463488634204abfc1d833e49b2b32.nq.gz
│   ├── 8153c4d2c62c69f1761bb85cb3aadfb558a712f6.nq.gz
│   ├── 81a3610c5314f1c781ec7fbd1dd4293f44e01320.nq.gz
│   ├── 81fc82d2094e8693b657f3766c723f91e780a9df.nq.gz
│   ├── 8341d7cd7ae6c10be7c0108798e093d2e9d3a029.nq.gz
│   ├── 88b57051bf1091c8d893e777fd44d3f8f00158cf.nq.gz
│   ├── 8de9dfb385ab53aa1ef826dbf9df30b4b7ce3a4c.nq.gz
│   ├── 8ec872ad863875b199bc9bdf4b1aa7dade2576f4.nq.gz
│   ├── 8f463b8076128c50935438da2d733373dc6bd332.nq.gz
│   ├── 993cc8f74a7a3df79faf3c8d7d96b66d63862def.nq.gz
│   ├── 9aebb803870fa5d7fc3055345cdc3b18697c1a58.nq.gz
│   ├── aa55015aa9aa51a49a435bef31b7fef2bbc70ee6.nq.gz
│   ├── ad9f9bebd16281f09d9061d82257858edbfbcf74.nq.gz
│   ├── aed1ebcd4f88518ac8e17011a2db069cb132e242.nq.gz
│   ├── b0ea6ba5e088979384a14f068e7c9ef5bf4d74a1.nq.gz
│   ├── b59e97a3dc9ad1e5e7147b1b8c2ddce8f6470cc8.nq.gz
│   ├── b8ee1fcf09230ddcc633c9e61597bc87ce4e2921.nq.gz
│   ├── bbca2b730b50eb915f4fbd708c339c25a55acbd9.nq.gz
│   ├── bed8edf3f3a669a1d662aaf9568c3fff65cbf49a.nq.gz
│   ├── c1881060de286b6e65824cf42d336f09ad37ce7e.nq.gz
│   ├── c1dcd6b552b215263a82dfa284d6181bbdf2a52c.nq.gz
│   ├── c28fa338be2143f989c569c8719f85423af44302.nq.gz
│   ├── c463e65ade07a271207fbe829878f54b51c8debd.nq.gz
│   ├── ceb8a98f079212564226bdb442e61cde7dcdb85d.nq.gz
│   ├── da62488212413887392217bcf3b36938238a97c7.nq.gz
│   ├── db03a3ec13fe5623904d8857b9424faa90725ab0.nq.gz
│   ├── ded5b1bacadd5f82ffb1295f798b6bdd6a0ad85a.nq.gz
│   ├── e59de9250e283a4ce896dc450071f718238ef75f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e868c29fc4b03de1ffb87f61b3ade585d62c289b.nq.gz
│   ├── e96f34c57901ef1757394ad23d1e62fec816b11f.nq.gz
│   ├── ea42eb795daa5cba6b105f8133c2e0d06e476371.nq.gz
│   ├── edc08dfe12b25c711a3df794e8b3bf0141edd78c.nq.gz
│   ├── f185fa579f4a324e467280bba144b33bb071e2e7.nq.gz
│   ├── f8422fb8aa755fd1fec14315a09d2038d720090a.nq.gz
│   ├── f8dce335ac96c8e8544d816ac3f351af7c690c86.nq.gz
│   ├── fcdd3e88b66ec9b10362685146ef2a36088e54f3.nq.gz
│   └── fd465b8eab23d5d5e6d7bf88bed4a04c836fe608.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 46ef93177dcaad76034e9baf9e39cff17e41942a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[jupyter-server/jupyter_releaser](https://github.com/jupyter-server/jupyter_releaser)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
