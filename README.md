# Repolex Knowledge Graph of digitalbazaar/pyld

RDF knowledge graph data for [digitalbazaar/pyld](https://github.com/digitalbazaar/pyld), parsed by [repolex](https://repolex.ai).

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
lexq download digitalbazaar/pyld
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 012c10567e9097ca23449bf7037c27ba0ada3dae.nq.gz
│   │   ├── 2ada0161fa56e52e18efc44eab8ad4ad2f5220f0.nq.gz
│   │   ├── 2f64b1926a3b8b62478ec2d20e74f2a5690ec1d0.nq.gz
│   │   ├── 4a4457b912d313a553411cf87e436661d87554e9.nq.gz
│   │   ├── 4d0f199953fb6ce8aaa9e8efae109fec9d14644e.nq.gz
│   │   ├── 81875979fabb24edd77af809f58e371c07b3a1fc.nq.gz
│   │   ├── 977e41b54ec36a95057038031f6028a9148017b4.nq.gz
│   │   ├── b65533153b19121a903b8d2175f688dbfe56a1da.nq.gz
│   │   └── df0ef242b30cb52b562e0a0499a3da748f14715b.nq.gz
│   ├── dataflow
│   │   ├── 012c10567e9097ca23449bf7037c27ba0ada3dae.nq.gz
│   │   ├── 2ada0161fa56e52e18efc44eab8ad4ad2f5220f0.nq.gz
│   │   ├── 2f64b1926a3b8b62478ec2d20e74f2a5690ec1d0.nq.gz
│   │   ├── 4a4457b912d313a553411cf87e436661d87554e9.nq.gz
│   │   ├── 4d0f199953fb6ce8aaa9e8efae109fec9d14644e.nq.gz
│   │   ├── 81875979fabb24edd77af809f58e371c07b3a1fc.nq.gz
│   │   ├── 977e41b54ec36a95057038031f6028a9148017b4.nq.gz
│   │   ├── b65533153b19121a903b8d2175f688dbfe56a1da.nq.gz
│   │   └── df0ef242b30cb52b562e0a0499a3da748f14715b.nq.gz
│   ├── lsp
│   │   ├── 012c10567e9097ca23449bf7037c27ba0ada3dae.nq.gz
│   │   ├── 2ada0161fa56e52e18efc44eab8ad4ad2f5220f0.nq.gz
│   │   ├── 2f64b1926a3b8b62478ec2d20e74f2a5690ec1d0.nq.gz
│   │   ├── 4a4457b912d313a553411cf87e436661d87554e9.nq.gz
│   │   ├── 4d0f199953fb6ce8aaa9e8efae109fec9d14644e.nq.gz
│   │   ├── 81875979fabb24edd77af809f58e371c07b3a1fc.nq.gz
│   │   ├── 977e41b54ec36a95057038031f6028a9148017b4.nq.gz
│   │   ├── b65533153b19121a903b8d2175f688dbfe56a1da.nq.gz
│   │   └── df0ef242b30cb52b562e0a0499a3da748f14715b.nq.gz
│   └── repolex
│       ├── 012c10567e9097ca23449bf7037c27ba0ada3dae.nq.gz
│       ├── 2ada0161fa56e52e18efc44eab8ad4ad2f5220f0.nq.gz
│       ├── 2f64b1926a3b8b62478ec2d20e74f2a5690ec1d0.nq.gz
│       ├── 4a4457b912d313a553411cf87e436661d87554e9.nq.gz
│       ├── 4d0f199953fb6ce8aaa9e8efae109fec9d14644e.nq.gz
│       ├── 977e41b54ec36a95057038031f6028a9148017b4.nq.gz
│       ├── b65533153b19121a903b8d2175f688dbfe56a1da.nq.gz
│       └── df0ef242b30cb52b562e0a0499a3da748f14715b.nq.gz
├── blob
│   ├── 013c59abbd9bd6b5c5f781c53e971a7b4d29bf0d.nq.gz
│   ├── 020528601696e7f4088c692722458d5bf36f6175.nq.gz
│   ├── 022ac422f8e7f99d4f6bf66ca8b2704b45828356.nq.gz
│   ├── 08ed0d344f78c3691337f033d9483ca1e2b308d4.nq.gz
│   ├── 0d5a7dbbfb601bf3d3b6efc8f1d07c71652a8341.nq.gz
│   ├── 0df8c89a18f6539fb54aa1e2fc2cab1be33c16d4.nq.gz
│   ├── 0f7438b242206a67ccbc6f3afb72670762c73c50.nq.gz
│   ├── 11efc0b249005c4974c35c56d6c3e1318f44f9d2.nq.gz
│   ├── 132af3fb21a21bf0b75399c80610d9be3c140d4c.nq.gz
│   ├── 1afbedba92b33c6b418c343f7b4c6948318eb197.nq.gz
│   ├── 1dff7a4e073611ab61b0d0e54fdbef3d96060308.nq.gz
│   ├── 1ec060a9e04bf983ff8ae6838486f147f80ab635.nq.gz
│   ├── 28a66eaefc6cd690f5d2fdbfc302be26eff06e02.nq.gz
│   ├── 291939b64785b34a96c01c8e02744df1ab6926a0.nq.gz
│   ├── 2c43a3714a07b86d528efd54b0a3dd005c83b2b0.nq.gz
│   ├── 2f7872d9e150f272b2b1ce53a600f5bddbd80850.nq.gz
│   ├── 33741a0848e859cf91d6fa82dd939ed40dbdf9fe.nq.gz
│   ├── 33b041a22fdd1d1294f56838cfa10282d9f115c7.nq.gz
│   ├── 3519c8d4fa90f17c3eb0a4a182f110185c579d26.nq.gz
│   ├── 38c3d7b17ff047600e46f7c9065176178fcaa312.nq.gz
│   ├── 391c27d0dd079a144259764e481e6fbf733a8a90.nq.gz
│   ├── 3ba8d1ab8fa95b0f72a4ae903ee9932b00e8767d.nq.gz
│   ├── 3d58879206035f12a40ab771a9e4c431e4c3bc4b.nq.gz
│   ├── 3ee87edc423d363598e2d6b94f31a3863f3404b4.nq.gz
│   ├── 3f02bb3a33c7a81dbec76ac0b9b13a5f0d1e0638.nq.gz
│   ├── 3f67a234387335cde87faa66a027bde094d57b3c.nq.gz
│   ├── 40d008ed921140a20314f4ec48167ced8f925744.nq.gz
│   ├── 41eecff448091325143dbd0cfc173ea3e2c75937.nq.gz
│   ├── 4246bd7ad6892cbf4d5d1e7a185e3ad895aef0ae.nq.gz
│   ├── 42e915c39670e9dcf97d99509db84875670dcec6.nq.gz
│   ├── 440702bebae9bb2b5876f60b45e04aeb7245abde.nq.gz
│   ├── 44c322b276a614584cd409efc3c3bcc35fc8a792.nq.gz
│   ├── 4bc7fcdf34615bbb4405e4536ba4d6cdbf361ecc.nq.gz
│   ├── 5053e54979a8ee6d1d11bd3ff3d9c4a0bcaafd5a.nq.gz
│   ├── 5266a89bc6245d85efae918f4827a54ee35e753c.nq.gz
│   ├── 5a9f32043b31394623ac27f2153263724e0fa236.nq.gz
│   ├── 5adb1ae7e49ed9f7477d561d919e6ffacbca1344.nq.gz
│   ├── 5be6b43d422b10dc43c49b7f67876150f7450ab2.nq.gz
│   ├── 5e37e5442abfa6c4304270cfb8c7577c1fe7ade0.nq.gz
│   ├── 5ee30fd56035cc4f8a926ae0e73eb00ba478db13.nq.gz
│   ├── 5f98a1f647c5cec9bfd2ff28ef368e605b93970f.nq.gz
│   ├── 60a6351cbe4904306194b62ac09c29b7c30be570.nq.gz
│   ├── 66e43d80ae60c412f2efac612a9a98a0310eab08.nq.gz
│   ├── 6714cbbfd8c2f6c11bfd5e731623129d472b9478.nq.gz
│   ├── 67a5795a6fb8f6e73826354d950f8c842973ee00.nq.gz
│   ├── 68354c7a4939513a8b2a6cbe4f740195958ab1ee.nq.gz
│   ├── 6e0b5d813c64b046907384e297c0292d3071c653.nq.gz
│   ├── 6f7570ec747dec1fab5dfbec94f2a8dafb3c11b3.nq.gz
│   ├── 70b82304686c5632e18efc850fea02b0f1fe7107.nq.gz
│   ├── 737c1c27035e2f73ca087ec3f50164713258bed8.nq.gz
│   ├── 75aeb3bd99933ceeb992033b250ffe66eb696ecc.nq.gz
│   ├── 77f42e1d33ed47adfe746cafa52fcfc67713aed8.nq.gz
│   ├── 78c5f8ba244f8e41d14680095ea4fc584ec4bcd9.nq.gz
│   ├── 7bce289f04ea6c8f5cc3ac161a29cf53e4f90f67.nq.gz
│   ├── 81f4b8e01461777aa9344d7ae2c06231fb1df9f2.nq.gz
│   ├── 8330c53a3278868318a8bb42c77cf9f88b8b12ac.nq.gz
│   ├── 87e32c75e6308a09649f4273fbafd434c5b9e7d9.nq.gz
│   ├── 887170bd5bd03897876ef64975d58c882a46d985.nq.gz
│   ├── 888c94f492b9e79e53af09898c16c938f5cd5529.nq.gz
│   ├── 8b2099dc02b5cddfaddcced144d2f94e95a8f2f2.nq.gz
│   ├── 8c7fb3e0a372ada0568ec2af8345b7a291b13cdd.nq.gz
│   ├── 8fa042b78ed4774b2a0c3f243123e20c1fc240ea.nq.gz
│   ├── 92cacd285355271487b7e379dba6ca60f9a554a4.nq.gz
│   ├── 9e92aa18067c7915fc574da9d73b5c1c8ad58397.nq.gz
│   ├── 9e986d7d1aa561f802a0f980a7de735095522e0e.nq.gz
│   ├── a12016feeffd30ee6c888f7781331ef19b110ca4.nq.gz
│   ├── a22d85e93dc2db8a913177d834a68870543a7908.nq.gz
│   ├── a244a4aa8332de1c13dbd8882adbf5b54284a5c7.nq.gz
│   ├── a24b446afb58b214d580c841f9775f292820e396.nq.gz
│   ├── a5e5e7a53645e3a53d3b6f7dbbd1e59563ae5df5.nq.gz
│   ├── a8f045604d8c1b1b2c4cda22d6b305a4210e931f.nq.gz
│   ├── b04721fd11ef208ef978728a450c54222fea88c7.nq.gz
│   ├── b0b781e0240254d1c72231fbd5631e06739e59d5.nq.gz
│   ├── b329ba8cd22aef59398dbcde27db42d810589c6f.nq.gz
│   ├── b596e81a771eba94a8a5d569a80020f102e7bb9c.nq.gz
│   ├── b78ab7829955a6307f6c9850fdaf79e9aa77ce1f.nq.gz
│   ├── b7b2d1ca02818c258143cc549568f82cae46350d.nq.gz
│   ├── ba95135564c6f2f980a8daaf64b3e84730dcbe35.nq.gz
│   ├── bba0235e8937aded2a19bf6ed66326faef2b5d49.nq.gz
│   ├── bc15e24fc73de8dd97c90dec4263a6885e7d2d53.nq.gz
│   ├── bdafde9e1ab02cdd496186fe80d5be2462fa5c0b.nq.gz
│   ├── c2873c3c59ba3e476dece7a67a087ec693d5edbd.nq.gz
│   ├── c4bf2b85af5f7aef151721195ce345a2f81c2024.nq.gz
│   ├── c525510b14a88230fe955e3f95b643854c3b5cb5.nq.gz
│   ├── c5c939cf2d4ec4768bec568e4b4796c10215c711.nq.gz
│   ├── c8e7193e1e13ef358cffd0dd15d31c6d703b2417.nq.gz
│   ├── cc9e4d6ec48d86c53d0bec84beb9370ea4692401.nq.gz
│   ├── cf02f0a8507a9d23e256fd501579dee491d4c8f1.nq.gz
│   ├── d306fbbe52ccdd9b6f80009997b1bbfef93e0f1f.nq.gz
│   ├── d38a71d39a22a109c0450f8c6773d0bd9f618cd2.nq.gz
│   ├── d6b066635e6469594a27214dccbcce3c1c5143c0.nq.gz
│   ├── de3380ae4084c5401d9ae10fee92c27b22229d4b.nq.gz
│   ├── e5e8834304db3c791721146740aa74e9db35e4e2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9748bb90fb154b6d8f01fdee2a6234725a5d4fb.nq.gz
│   ├── ef32266c64493320e884c75bbcc17e00df821a96.nq.gz
│   ├── ef967629230e68c51dd4141fa217a59b274c26b2.nq.gz
│   ├── efc1d2cae6edddcdf1613a2551fa301b28814d57.nq.gz
│   ├── f2293605cf1b01dca72aad0a15c45b72ed5429a2.nq.gz
│   ├── f4e5432a89c3595d67018a008ccbc9230463145f.nq.gz
│   ├── f990eba89ce883d130779220c9a652bd726f28e9.nq.gz
│   ├── fa7bcabde21f9587ee7c6a6504b0c6e2fecdff85.nq.gz
│   ├── fbae730880a7e3dcfba4f968e92dd5bbaddb6bc9.nq.gz
│   ├── fbfda26cef9496e467347dacc6cd66f261a802e2.nq.gz
│   └── fe2dd9b8fceadc5616d3867bb0f5e72b7e909a0f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 012c10567e9097ca23449bf7037c27ba0ada3dae.nq.gz
│   ├── 2ada0161fa56e52e18efc44eab8ad4ad2f5220f0.nq.gz
│   ├── 2f64b1926a3b8b62478ec2d20e74f2a5690ec1d0.nq.gz
│   ├── 4a4457b912d313a553411cf87e436661d87554e9.nq.gz
│   ├── 4d0f199953fb6ce8aaa9e8efae109fec9d14644e.nq.gz
│   ├── 81875979fabb24edd77af809f58e371c07b3a1fc.nq.gz
│   ├── 977e41b54ec36a95057038031f6028a9148017b4.nq.gz
│   ├── b65533153b19121a903b8d2175f688dbfe56a1da.nq.gz
│   └── df0ef242b30cb52b562e0a0499a3da748f14715b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 154 files
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

[digitalbazaar/pyld](https://github.com/digitalbazaar/pyld)

---
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
