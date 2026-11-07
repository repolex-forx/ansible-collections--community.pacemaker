# Repolex Knowledge Graph of ansible-collections/community.pacemaker

RDF knowledge graph data for [ansible-collections/community.pacemaker](https://github.com/ansible-collections/community.pacemaker), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.pacemaker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9868faf273896a01af2e3662330a5023c1438492
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9868faf273896a01af2e3662330a5023c1438492
│           └── chunk-001.nq.gz
├── blob
│   ├── 002e13ed6cd0ed124a365c15b9d9579c0216c7f8.nq.gz
│   ├── 0164155b81025416095f31a4732098ec238e6476.nq.gz
│   ├── 01bb0a20e357edf017eed5af10455c378ceeb2ed.nq.gz
│   ├── 08c3ba7ccafb057a2bfd1f4f219cf3c18b72c914.nq.gz
│   ├── 0aaa12884d1dc73cc6b0a9de57b5b49b5684ede8.nq.gz
│   ├── 14d79f8afc68c0f15c3aff5ca21f733845553f05.nq.gz
│   ├── 150e123d0c8133f9e30c160e849e24dc903d01f5.nq.gz
│   ├── 15147e22fd5b290591e6f3263f9b3836487622e2.nq.gz
│   ├── 16995f26aa6a19b262a7919ec011b4c204ff4767.nq.gz
│   ├── 297a0407109df43985a44f4773355302571968bf.nq.gz
│   ├── 2abdaca563660791592998039959e779d582e1e6.nq.gz
│   ├── 2bbbd593206a808e4a8dd0b4e7762a055df1435a.nq.gz
│   ├── 30827ed47b79f6bccf5b6f62b3f762ba107ce6c7.nq.gz
│   ├── 324dfbca53519e763cce8767b348902562a18ca8.nq.gz
│   ├── 3376db5a767d5ec2b72f09f93397091afbca0741.nq.gz
│   ├── 34fde7adda7bd45a0b4f19b90f13b8cf605b3295.nq.gz
│   ├── 475dde47f1cb663e9e04dd88e0fc1f892d42a9af.nq.gz
│   ├── 479d8c0abd6e0555226e6465a401dce2d84aa189.nq.gz
│   ├── 4bd7551badfd79ffa58402992151b1abfae4bd42.nq.gz
│   ├── 51601c06c7bcc564d98e0da459baf93195e789b6.nq.gz
│   ├── 56d4767cf33e438fc33d2bdca58201861d71a43c.nq.gz
│   ├── 5c4b109783f2bd9e151a4d61ef4b2711caff5a85.nq.gz
│   ├── 5d751457100e3f928007cfac3ad1f9e396a1f909.nq.gz
│   ├── 673dcc11f2dd25a64ea9470d9d35f4d59a79f710.nq.gz
│   ├── 6a44bde9efa4cd86633d646404195d964fc7ca8f.nq.gz
│   ├── 6b57cfacff423a19984d2173ef51038cb6dfd6d5.nq.gz
│   ├── 6f03002ea8f868e8734f7a4bc62de6409215a484.nq.gz
│   ├── 718e176ffc5202a27ea0468b112fc7d8592cdc4d.nq.gz
│   ├── 71f942520e6f6d7040cddcc20ba170d2342405fb.nq.gz
│   ├── 7c937f87e006c2df52b660d3c3de28e748f5917c.nq.gz
│   ├── 82f9b74d9c314441cd2e4f710abe79653e970d92.nq.gz
│   ├── 83a7a1a7c649b4fcd586b02bb9dec06a95926c03.nq.gz
│   ├── 869ed75a30964cc171dd89c01a041969d38462d6.nq.gz
│   ├── 88276760562cb58bb9bc47fa890e8a3df1125b9b.nq.gz
│   ├── 88bfaa220bb20e3b519dbc970d880cb97c742ef1.nq.gz
│   ├── 89699587f68651607244c61dd4501f45b442bb2f.nq.gz
│   ├── 95607927d80d9d0e0349ad04aa3b06c9be2e0205.nq.gz
│   ├── 967ab78d7b4d0ab72bfd2514f23041a47826fe01.nq.gz
│   ├── 96e4f7fbbfced9dec46894e848cbf44562d3eb21.nq.gz
│   ├── 9b1e33284647677868bbf7be944479f20cfa62e5.nq.gz
│   ├── 9b3dd25ca2603c026d1477d6343f832117d22248.nq.gz
│   ├── 9ca8713edf7d78affc26a5e208a7899c51ff0896.nq.gz
│   ├── 9dccf7ef174657345b77b37626c52cdc0390117f.nq.gz
│   ├── 9e0e1890dbd0639c796d853e33d4a82089c97a0f.nq.gz
│   ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
│   ├── b4a17dec0383181a3caed73fc87775df337d0eee.nq.gz
│   ├── b886cdbbda214b644d674e67ac7edd6dfcb0ab6b.nq.gz
│   ├── c0b7aa94f68746c3319abd829623d75d9a1bad21.nq.gz
│   ├── c7109ffe3f2de6c4df51669f42db1ea29921103e.nq.gz
│   ├── c9666edb5444de9366ac4b2abb03a66b21e9bc32.nq.gz
│   ├── c9e9bd38daae9afdea0ac56984b5a4ea23ac902a.nq.gz
│   ├── cafc88c66c98933b4939e1e443de0bc7f743fd36.nq.gz
│   ├── cd5e326c4c6221f1e2812a0ed722d7b5421f7a84.nq.gz
│   ├── ce7eca1d6eb6eea3acfb62aab3da7dce6d66b683.nq.gz
│   ├── d273d04a111aa71d33d579a0302c59f7c932efe5.nq.gz
│   ├── d36d15e8128faa59e17ad2c53a152246d84e40a2.nq.gz
│   ├── d5e10945c17eb2813af060615e08e3ae3ed822e0.nq.gz
│   ├── d760eb5977fa8263affaab195608b0fbc56b128f.nq.gz
│   ├── d9ba8643c64d47dfae0d2545471ae022579f5e67.nq.gz
│   ├── dcf61e39c81a7f250ab3c040ed9ca579d996764c.nq.gz
│   ├── dd6664055f917ebc62e623cadc14186b7dda1168.nq.gz
│   ├── e511d1959a744e7b172d207417902974e2f17442.nq.gz
│   ├── e636fb521901428cc1162227558e6ea5ac953c8d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6f32813af8a30248bd1ddef899250f3f0b71d86.nq.gz
│   ├── ea42c11f3ef5abaa7a42ae8978ce6d31b2013481.nq.gz
│   ├── ec1bac9d3e531b45098c3a8144f787ec75c1dcab.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f4735d367e72097c7e2c1c584edec1ddf3f6bcc4.nq.gz
│   ├── f5c4ba71746c90c02dd5450f63483cca3c215ae2.nq.gz
│   ├── f7768565c27781db1456c96bc350bdaf45677067.nq.gz
│   ├── fc08542f34838bdf3a76c94273f1085b8d587d22.nq.gz
│   └── fe77f678708ed585bf704a5ee930886b39f15dad.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9868faf273896a01af2e3662330a5023c1438492.nq.gz
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

[ansible-collections/community.pacemaker](https://github.com/ansible-collections/community.pacemaker)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
