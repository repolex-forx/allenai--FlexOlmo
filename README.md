# Repolex Knowledge Graph of allenai/FlexOlmo

RDF knowledge graph data for [allenai/FlexOlmo](https://github.com/allenai/FlexOlmo), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/FlexOlmo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 65e9b46b43ecb6ae66995b9d97b375c4b4dfd70c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 65e9b46b43ecb6ae66995b9d97b375c4b4dfd70c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01afad5b8c71930b883a646bc0c847e9952dd3fd.nq.gz
│   ├── 031e858a05ba9241dbf5c590a52a5a44b19eddee.nq.gz
│   ├── 0c24fab4292d1afc81ca27a116103d4dde16e3ba.nq.gz
│   ├── 0e31215b7c339cd0a94fd073ebf2bd51396f4ccf.nq.gz
│   ├── 0e58421d2e95407e7d5f5db8afae0dfd60af7487.nq.gz
│   ├── 120f61f2ba62df5c9fcbf1f6950b5c635e790e78.nq.gz
│   ├── 126d04ce5ca5d6479e9cbd59bdad13ce7e04b420.nq.gz
│   ├── 13a9598045aff70a1014322c1893c9a33049c640.nq.gz
│   ├── 1706ace4501e77e93f9ccb617dd5936d75dce70a.nq.gz
│   ├── 180b328eeded1efb6d4db1203fb854498e839f29.nq.gz
│   ├── 1be35d88031d595f0943b3d57458359a8b2fb4d3.nq.gz
│   ├── 1c2b505329683e0b44e1d0791a43f64a2c12a041.nq.gz
│   ├── 1c4712ef73cf1c603e08bce0cb45d4ac9039269f.nq.gz
│   ├── 1c8ef1141525aedcd8f87477c3f86a2bd0f34203.nq.gz
│   ├── 1f1cce49c18658af621c90423e41096d2f0f37ab.nq.gz
│   ├── 21122ca366b5245a27f510118109071d8a7411a7.nq.gz
│   ├── 22ce89db1ffe67413cdd03c43f4a7419c223a91b.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 27166ff68d46d213cb9e8f7acf0bf7c7fbd499f9.nq.gz
│   ├── 2d36a917b4dc2743a9d016f1b83b4051d4cfe206.nq.gz
│   ├── 2d71c0115ae6aea6a7c52d50081cb6e9e0c44052.nq.gz
│   ├── 2d7ad6b621304b1d5140eeb879c11cc29e7d6a6a.nq.gz
│   ├── 2dda966a3902f02177f2f05a90f945f222940baa.nq.gz
│   ├── 3302814e5df5dbb984af5df9bfc58e212f704672.nq.gz
│   ├── 3422f6be332adde5d4173867f65ed035e3ce7d9f.nq.gz
│   ├── 3552eb563fb1c01fa15b435eb0af29e6428be06c.nq.gz
│   ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
│   ├── 389ce4c4d34bb403a957460cc92e45d03928dcd7.nq.gz
│   ├── 3a1d96dfdde60e0c1f26b5e8a065ea1bbc036b0e.nq.gz
│   ├── 3a281a349017bdca593122d5ad6a40683f232962.nq.gz
│   ├── 3a2da4c4526f2ac4d5e39d340690a4716b184ffb.nq.gz
│   ├── 3a5f787cf1df9e85f32dbdc8d01a510adc00695b.nq.gz
│   ├── 3b096510cd78d87d4ce229f5edc7fdc6f8cb0bd0.nq.gz
│   ├── 3bce73f0dc07500014d9cf9048ebcd19a5c905a0.nq.gz
│   ├── 3f72a8a714a5107e284f835ac3a89159626d5c75.nq.gz
│   ├── 40cbb529b74f8af116c1653a5a839f54492f84e4.nq.gz
│   ├── 42b994c5b539ec319def4ef461cb908c192008e3.nq.gz
│   ├── 42e2d38b524fc53a4d9392d4f0cdb7875514ac6d.nq.gz
│   ├── 45ff7df0b868722b0a33d6db533307309c74806a.nq.gz
│   ├── 4643bb0e5544694b6150209d9822598c76a2fe4c.nq.gz
│   ├── 485d8126b926f2fe41c134a4a80557e13dddb655.nq.gz
│   ├── 49008f25c2920a6361c083454705374a9a7bbbfc.nq.gz
│   ├── 4ae6d1c319859f34840631e8bc27f3dc39e74f7e.nq.gz
│   ├── 4f86a08ab43e12fd62a21d04740533c02ef065a9.nq.gz
│   ├── 50747070ab224949001423f3f1ddafe47befaf81.nq.gz
│   ├── 50a1dd815966bc3cd9b79b3aab98461688e8791d.nq.gz
│   ├── 51bc08ec806eb9587502d538b7a1807abe865c97.nq.gz
│   ├── 53439675365d7c96d1422d77e591e4c9b3ec3ec6.nq.gz
│   ├── 57d5bbe904fcfd6c1d5be8c30bded596155547c1.nq.gz
│   ├── 5a5a1c3231200d3d6dda5fa7eb8ac7ee57692957.nq.gz
│   ├── 5b17fe534107b8fe2fc895915521bfbf0949f5c8.nq.gz
│   ├── 5d50a8f53dcb78579f2024d637512698c0fd5bb2.nq.gz
│   ├── 5d87b8c30542be6167d38ff8d227261b8d5d40b6.nq.gz
│   ├── 5f251752b814f7941a8d8dc91ef15bf48aa32d2a.nq.gz
│   ├── 63e8d99e5a73d1cc17027e8f19de9d94c7595252.nq.gz
│   ├── 64873457ff9f99ab4dd72578576de73ce8f82623.nq.gz
│   ├── 668ac8d4ccf2429a134c58736939bbcd02865522.nq.gz
│   ├── 673aac3a6263695e1a3888a334dbbff72d6aaefb.nq.gz
│   ├── 67d30701b97ebb33bac2c744536b159120077acd.nq.gz
│   ├── 68c5a0988f769f42f464ec2cf64e6c5065e8b54d.nq.gz
│   ├── 6ad69abdc839566b40b8b4ef82c1fd007ea9af20.nq.gz
│   ├── 6d3b7a46715e32e937e77144ae3f0151f8d9bcac.nq.gz
│   ├── 6f96e7bf527e3a18ca8678ba26137d513fb83133.nq.gz
│   ├── 6f9b972a2ef075f66b467ad9ab89c1330a664b4b.nq.gz
│   ├── 6fcf05b4b76f8b9774c317ac8ada402f8a7087de.nq.gz
│   ├── 73fc038a82ac00add8fa04b682da198ca240d8e2.nq.gz
│   ├── 74f8fe22699732e3dc7ad07dbb0bf7852005f0b7.nq.gz
│   ├── 7703f2371b7184d00c23335554daaa7bc88516c9.nq.gz
│   ├── 79af0270bd8d41a1bedcac0ad623a2c7454d1840.nq.gz
│   ├── 8398e53d3e058a3ceff8d92fe8280aacbbc82018.nq.gz
│   ├── 86bd249ad1b9b1c3a245c12d60a0dd9cfde38375.nq.gz
│   ├── 8777eb2cae290959f93f578194802d46c34c1c11.nq.gz
│   ├── 899be252ddc80e9f2c3252d8f0667915fdb67bd8.nq.gz
│   ├── 8ef3f03a446453875f4d5de04b697a1be17179e4.nq.gz
│   ├── 8f56191592ad9bb1c60764a7c2bd543f8a493157.nq.gz
│   ├── 96b73eb6846dd82dea7eaaf3dc218eeff6452a27.nq.gz
│   ├── 96c390d444906606ac381efce1a4296936272ff2.nq.gz
│   ├── 98f2b700a80d21f48ffcae8ab86bc81b8da239f5.nq.gz
│   ├── 9d1baaffbbc902fa6408ac69dcb6428e09304da0.nq.gz
│   ├── 9d335fa5d902d2547916b279655031e32554165c.nq.gz
│   ├── a17996c1cccda50ee67cef4ce19091be1439bd40.nq.gz
│   ├── a3f8992bc715108c10df0edfbab0516e363af762.nq.gz
│   ├── a4de0bff1812fbfd1f17622f746ab2bb18ec1ec1.nq.gz
│   ├── a51b256cfa3407770ab2f7fbfee9a87a99dd25b6.nq.gz
│   ├── a6a659490dcd093224be285166c417aafbec028b.nq.gz
│   ├── a86abf10fb95ca6096719a6c2af514c58390042b.nq.gz
│   ├── abcec8c01fdce22fca906e18324f3110f494a225.nq.gz
│   ├── af91813cfa06157b3014e1c2d2c70cf76219ddd5.nq.gz
│   ├── b4e93c9ef924337dc3fbe882c48d4b4127cce015.nq.gz
│   ├── b5b92839a37839161ee332916aed8c6fd180fb52.nq.gz
│   ├── b5cf9d0d15e591f7943827686b3f28064e07c9f2.nq.gz
│   ├── b7227515b5b21e0f01b0fc58cb1b76056eb4c0eb.nq.gz
│   ├── b7aac8717d115d15be9a040bb08dac0d560f57dd.nq.gz
│   ├── bac77130dee477480c49a75ec938f3e3271a2de2.nq.gz
│   ├── bb1c7e8873d031bfed9466b0e795b860dfd17801.nq.gz
│   ├── bdb241a8392a3fc5b74cdc1bdc8b26d1d9a8962f.nq.gz
│   ├── c41078cdc17f62cafd4750885a0f034168a561f4.nq.gz
│   ├── c650418d7d4124433c87a419a72c6840b111c71f.nq.gz
│   ├── c6e9c9cd03c756cb66c44f6646df1172b77bb931.nq.gz
│   ├── c7200be4e5771584d7eef11486da5bd056910999.nq.gz
│   ├── c9febaacc44fb73dad53c9a6788e3cbb1e8aa68a.nq.gz
│   ├── cbc8ef6eef9936dfcfefe44a5a8bf7875a55f45c.nq.gz
│   ├── d120be86638b02482a6822307541dcecca15f204.nq.gz
│   ├── d3cab9dd80d01662b088fb85a52dd0939f864328.nq.gz
│   ├── d537ddf0b50181fd1ce7dcda238f982d894b9f73.nq.gz
│   ├── d915fcec66b332c9c669ec01f2144ab1e625fbdc.nq.gz
│   ├── d9aa405be20a32b258aba1a96738141a5eca9733.nq.gz
│   ├── daed292d92e26b945f147490faa606f29ed50522.nq.gz
│   ├── dc277621582e57dc487b383ac1163c6b68595abe.nq.gz
│   ├── dcc51976dcab30b27a008165b44434f493f53f83.nq.gz
│   ├── ddcffb5758e398af726988f89d580643bce1bdcd.nq.gz
│   ├── e3cd65deeb9f1a3c29af223c1b8e22328c2c9bb5.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82bc882616a2fff238ce066718f3ddbb30c4aa9.nq.gz
│   ├── ed780a53d5cee31f526ad62f2f136d858d275a30.nq.gz
│   ├── f03ae29dcc5233116e7aec8507cf8406c5cb1354.nq.gz
│   ├── f3cde04f14c654d23a08c02f72f7343b194c4bd9.nq.gz
│   ├── f3dfb08d36626620bea8dcf9aa7e99d38fea8250.nq.gz
│   ├── f50bc60a58caeebf95919518ea98126f4ec9a194.nq.gz
│   ├── f6053523ab6f54bfb9679ac74e721bc7f671db50.nq.gz
│   ├── f78329ffdd86baa988c15f497e7bd2ae313cb8b5.nq.gz
│   ├── fa4c62db4b14c6c69861a191e4bcfc7febd95652.nq.gz
│   ├── fa667b0b3ffc666546b6b18b86ee85b23ec9dc6d.nq.gz
│   └── fc1b58b135437dd743e82a2111e61c01b13965ae.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 65e9b46b43ecb6ae66995b9d97b375c4b4dfd70c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 132 files
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

[allenai/FlexOlmo](https://github.com/allenai/FlexOlmo)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
