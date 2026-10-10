# Repolex Knowledge Graph of litestar-org/pytest-databases

RDF knowledge graph data for [litestar-org/pytest-databases](https://github.com/litestar-org/pytest-databases), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/pytest-databases
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bbefed54771662ef24c3eaff93a61da9937717cf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bbefed54771662ef24c3eaff93a61da9937717cf
│           └── chunk-001.nq.gz
├── blob
│   ├── 02ba7a652f6cee75223ab63d61b687b8afe4b332.nq.gz
│   ├── 0561420f642c70cf96300bbe1934f0dbb59fe8d9.nq.gz
│   ├── 057cbff9297053c2d03880e7233fd79a68d7c71e.nq.gz
│   ├── 09fa13ff44ce2d5234201db7836444e83a6cd65f.nq.gz
│   ├── 0aee10ca0967c43b5c9441ab79b0b534912c16c9.nq.gz
│   ├── 0be04f577d31aa404669def1dbc288d0a0b935d4.nq.gz
│   ├── 0c1b0d8861e045d777f5a727bc26e5c518114572.nq.gz
│   ├── 0d6387aa914cf5a2404183e4f22d5af460494696.nq.gz
│   ├── 0e7be0638f89a816bc866e07fd9fb693cb9ea702.nq.gz
│   ├── 0f26c2a7d3e59a8ac3f8da59dd45eaf094ff9141.nq.gz
│   ├── 0f689a1af48651d1ebfa2ca7c646df5947c7111c.nq.gz
│   ├── 106c352e9434b940b6cbbd7066293c7670ea231a.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 16b3c8b01af1c7761626fecccd9456e6a889e3e9.nq.gz
│   ├── 1d2ec9f24d4a06d45df0d54a590e658bc428c8ae.nq.gz
│   ├── 1e74fae8efa9ed9e78665dee17720f38b3e11cf8.nq.gz
│   ├── 208223183089f4bf0e3fde6471b8de6b639a138a.nq.gz
│   ├── 22952c986374d911c568c30446f08e85943e731a.nq.gz
│   ├── 2730bd1698013545fdaa777902d11da33a030ff1.nq.gz
│   ├── 28628dac12c05f4a9e93777f8763e4561b0374a2.nq.gz
│   ├── 29a2d1e2c6833ff6dc0a38ebaa45e28a1c718997.nq.gz
│   ├── 2aff340b903cd6cc064faca630ed7d1989953f09.nq.gz
│   ├── 3115d1d1f9bfdc6b126fda10423907f21525fa91.nq.gz
│   ├── 316876d7cdef398e415c56553f2cfdd3f104f0e0.nq.gz
│   ├── 32fefb18fe32e05ffcf1c603279b3a9d1d64d685.nq.gz
│   ├── 33fdc6dcbf2645f079d7be6ceeb8409dff8be8a5.nq.gz
│   ├── 3ee06df2acc9fd2162db2aacf51ddc604c51fc02.nq.gz
│   ├── 442f7583ef07b7d3f20006445ba3a6f8122373e9.nq.gz
│   ├── 458ff078623cf17018bc8750faf310ad1c415797.nq.gz
│   ├── 465c0171bd897633587b28b29671e9d58d82781c.nq.gz
│   ├── 4704678bfa7446749a00bc1ce6e82b3094abad5f.nq.gz
│   ├── 493486ceee7c061894b8141a43e5d878c3b7a69d.nq.gz
│   ├── 49cc53967caad33c66f4ac965e7924b4173fbdfd.nq.gz
│   ├── 4c0715161b812d1b7d336770f683a79f8308a3d8.nq.gz
│   ├── 4f91b8d569d6d37a29da678d80c56e19497f7741.nq.gz
│   ├── 51c44302b469314794b060683d2adf3fa1205800.nq.gz
│   ├── 53f6bb3a02b201e912798400ba6333e8fa4c5930.nq.gz
│   ├── 569289dfb0e67e563e8b2ebe03c4f9bf4f860a7d.nq.gz
│   ├── 57df36435e6add5d5f51aa93f29739acb7d10cf0.nq.gz
│   ├── 609400415260c02c1c56bb357684844c34b432e9.nq.gz
│   ├── 621fac428ee766a4c256a12c78193a74979cfd5c.nq.gz
│   ├── 639683aa9a6ec8bf0e42f42f321df015f55474a2.nq.gz
│   ├── 656720a6b6b47a19ea772b7799f1553e8e02b79e.nq.gz
│   ├── 66e68d781c4047ffc682a866267cfc5b26270a50.nq.gz
│   ├── 6c03f675f7ac6755d3bf3a29e3b0eec1494e069a.nq.gz
│   ├── 6e1e1f58e82d950c6143f64e7e072950f1db7b75.nq.gz
│   ├── 7a8b294058df5cf131a25506c7c3d477a88b7cff.nq.gz
│   ├── 7e70c8038c29842b3a1bdcbc4f6607ec9b487f20.nq.gz
│   ├── 810791dced9fe9bc52e345f422cf1efd80a59954.nq.gz
│   ├── 87791594177fac888e676cb2cbb877c2d3837793.nq.gz
│   ├── 87f927c4a80759e29652ad412355ac1187d31957.nq.gz
│   ├── 88be9fde1fe8d921f4256c4c8174b11fe35865da.nq.gz
│   ├── 8a4d81c18449ed4c6c979dc5c9c4d492c795f80e.nq.gz
│   ├── 8adf0231d00d05b38b7b021bd7e22216f9258c4b.nq.gz
│   ├── 8ae1407c8fdec0c88d7fe075bf6a062e37f52b2f.nq.gz
│   ├── 8b32e1cd5630f697a27e0687b88d946f037d10e6.nq.gz
│   ├── 93a6d8a3432bf1f3ede13edb46a3eeecfbd84ae3.nq.gz
│   ├── 94aa5740c79a8dd4fcb2e2943cda1476f918971c.nq.gz
│   ├── 976e7c95180d87c3b015067cf884abf31482caa6.nq.gz
│   ├── 98fa3d05a04e15c74f7045c0f80c8c6431db7f09.nq.gz
│   ├── 9962470c2ba5aa2d0beac3552eb60a12c50e465f.nq.gz
│   ├── 9bd3f59c600cb97bbf3aac799d65cfbe57edf592.nq.gz
│   ├── a236f9a3ab24f03ea71c6fad9a08b9bf15bd5b7d.nq.gz
│   ├── a32c5eeb1c86b021b40d134b1d1491e29f16141b.nq.gz
│   ├── a5bad8eefbc604e3f9ac0716888b900fb15853ef.nq.gz
│   ├── a8b591893fe3936ec68f37ea44299844882a3786.nq.gz
│   ├── abfb43346eafda41ade475e5607ed12b280d9164.nq.gz
│   ├── ac46473a3b576b64f71471f72fc3054127030549.nq.gz
│   ├── ad11f19d00865a19969543c135731baca28ae70e.nq.gz
│   ├── b38f44a1230ffc034e6707921296b496290398d5.nq.gz
│   ├── bbb6ae86a18e0267bb43791b865c8f8970dadb42.nq.gz
│   ├── bbd440e7a11cd492aeadbc4fe999f354366866df.nq.gz
│   ├── c2a81ea6211600daf28e03df311ac9cb36853be8.nq.gz
│   ├── c69432bbc2ded27d11d3bd19e675078eb4cec0d8.nq.gz
│   ├── c9bfdcc4fddcf28a97cd3f8203e9cda43891fa21.nq.gz
│   ├── cac74ebe8cf486e42462ba400c7db57262daf9f4.nq.gz
│   ├── cb3f89a123a5eeed4dc9513def0039765a2b689a.nq.gz
│   ├── cdfead133f8e57cbe8b0d1124fdbf63819cc55b2.nq.gz
│   ├── ce4d8928204d52ec1b0d3a3b299bfb858d5a5ff4.nq.gz
│   ├── cfd57a4dec2c421b98c83813e99d468702e709ff.nq.gz
│   ├── d5812f1f2a1288f3ed928957c07089ef1fa2870d.nq.gz
│   ├── d7f464c91da435b76532a7d75a492fba0cfe004f.nq.gz
│   ├── d82e2c7b3f2350c9485bbdedbad3dee0fe51a325.nq.gz
│   ├── d9a797fd80952d7b689e4961eb68a82f043cd938.nq.gz
│   ├── dd3274a4e6a3d5eed9583fef81fa0a0ec12df27a.nq.gz
│   ├── dd58bdaefb3929a8c8660335d76337206c72d1da.nq.gz
│   ├── de72f7425e30c616990ed463794ca8e06ef5c1d4.nq.gz
│   ├── df0484d30ea670b3cdac043e44691842d5307b85.nq.gz
│   ├── e1ed6b79b0e513552f85563fdc5b723acb2da5a6.nq.gz
│   ├── e2d28e4e6ec267f096704daba58852aab13fccdb.nq.gz
│   ├── e3e1a7604fed779061c0e91b10d31a995e52332c.nq.gz
│   ├── e47dea2ea32d34071233c58343c24ad95003ca82.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e872d9626182d8f94fa9ccbc178086884f844fa9.nq.gz
│   ├── e96f7681e0ec96a66c5fc5b32e6a11fc36c5885c.nq.gz
│   ├── ec84a771b7b068c5e4d4bcb66f150b981f146e06.nq.gz
│   ├── ed314dc6bd0a46ebeb08922ba24c9d795a39f229.nq.gz
│   ├── ed6309c84ddb7ec4e590b7b25f3300c3e5507b38.nq.gz
│   ├── ee32e267f3134dc3cab118734d458bb70908bdf1.nq.gz
│   ├── fdff60490eea83f685d6f8f878218ce181c46bbe.nq.gz
│   └── ffe7a6f00f15d7d2498296d9fd240630d1c2c385.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bbefed54771662ef24c3eaff93a61da9937717cf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 109 files
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

[litestar-org/pytest-databases](https://github.com/litestar-org/pytest-databases)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
