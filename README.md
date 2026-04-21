# Repolex Knowledge Graph of NousResearch/hermes-agent

RDF knowledge graph data for [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent), parsed by [repolex](https://repolex.ai).

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
lexq download NousResearch/hermes-agent
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 86960cdbb0148145890e2ee90b4e157fa899f6e1
│   │   │   ├── chunk-001.nq.gz
│   │   │   ├── chunk-002.nq.gz
│   │   │   └── chunk-003.nq.gz
│   │   └── abf1e98f6253f6984479fe03d1098173a9b065a7
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       └── chunk-003.nq.gz
│   ├── lsp
│   │   ├── 86960cdbb0148145890e2ee90b4e157fa899f6e1.nq.gz
│   │   └── abf1e98f6253f6984479fe03d1098173a9b065a7.nq.gz
│   └── repolex
│       └── abf1e98f6253f6984479fe03d1098173a9b065a7
│           └── chunk-001.nq.gz
└── blob
    ├── 0024fac624225a434828b8ed6c1249f1904ad971.nq.gz
    ├── 002776ca34413c4548f142b874fba2ab0b30bab5.nq.gz
    ├── 0028b93fa2e96d13d0616f325596cdd1b0d372f8.nq.gz
    ├── 002908d12f6de1a4c621872a5726c42261af9bbc.nq.gz
    ├── 0029376abba381c79dd54a880c287e6f4d60b945.nq.gz
    ├── 003a5a8e76333b0c344db8ba8ecadfd0bae40a0b.nq.gz
    ├── 004f8236a2bcd8afe88b68d6090c4e1f9f171cce.nq.gz
    ├── 005a657d5294af48ca89edb95fed6d4fcd7dd2c6.nq.gz
    ├── 0066d25b005e5b0d0d7514f59af36feb46538625.nq.gz
    ├── 0077295958c9e6520625c30dd93b45d4cd01c3c7.nq.gz
    ├── 0094e917c5416cdda43a5ac2a78717afeb8f506a.nq.gz
    ├── 00d91de909e660945c8140faab8869ece24da149.nq.gz
    ├── 00e13d268d66c00b38b313ac40676a4b0b8cf9e5.nq.gz
    ├── 00eca12c4f34896489b795ce3629d2e21a8cd883.nq.gz
    ├── 011ede4c16a9a8913891b501621aabb22facccbd.nq.gz
    ├── 01204e8aa68626a2985086a934d1c3b45a8cccc1.nq.gz
    ├── 012b8eb020baa0d12307804f2a894b0fc5a4603b.nq.gz
    ├── 01339608d48529dbc96a6d231bd4a2f0666edd6a.nq.gz
    ├── 013ed663538442af094d36b6eda4d849f70e0c96.nq.gz
    ├── 0151daf2a1f70be30ca3fdadea9c7795e27a00b5.nq.gz
    ├── 019c08a0fe87266d33f86fbba5bedb2b5e10ec01.nq.gz
    ├── 01af1c15a0e12b64c676e4adb75864e1f25a88fd.nq.gz
    ├── 01b6421a52e56063edb8df7c6bc8c20905e0c2ae.nq.gz
    ├── 01cff91826aa250b53191ba4e61dddb3a395c2e0.nq.gz
    ├── 01ee862073bf10b8bcba69513f711afa4eff798f.nq.gz
    ├── 020e15bd606d022b3427f73f9bb9a04d47c756a8.nq.gz
    ├── 0227c9ee14b4aac3ad3734fe7f2c0dcb9bbeed63.nq.gz
    ├── 0232846ca1cee702729d8586c69df0aba69c7c6c.nq.gz
    ├── 0234c69e4db1a7edf526beaa38ad2d37c0d29613.nq.gz
    ├── 0236b261d9e254ca1a72274fa6c7696f44eec979.nq.gz
    ├── 02814f75d39120f89ede70c1d134bdba7133c30e.nq.gz
    ├── 0288b620d2a759995f67fbc2f6a68a54d41b1102.nq.gz
    ├── 02d059194ab2ffd6d0cc320a5d778517935827dd.nq.gz
    ├── 02e44c15e340078dfe12cf49b24da46639facd4f.nq.gz
    ├── 0312424f183064c4f7d5db7a41cb464f8c509ecc.nq.gz
    ├── 035f4d01c93aa31d53e6107c00d3653b48851f1b.nq.gz
    ├── 03712c272deeb2b0da63ed8ff5a033adb24ab209.nq.gz
    ├── 039ce6b2ef7c3b56a0f796345726c25634120ee5.nq.gz
    ├── 03bae5f60245ef5999dc1b5282f2bc3b8f9f9c45.nq.gz
    ├── 03bf015c262fe2b6645c6ef056d70c378b9a3dc3.nq.gz
    ├── 041909b071456e6993c221bae0985fd8d898b74d.nq.gz
    ├── 04221d88f10bb02d48cddc027793fb918e7d3c12.nq.gz
    ├── 04224e1b36d6ce0f22cb8ac96acc197d65749e0b.nq.gz
    ├── 042e46f7bf9ab4b4e20d5255e78ebd38af66b963.nq.gz
    ├── 04350bfab84ed96c574b2a513ea5dcaf2bdd308b.nq.gz
    ├── 043c6b5551bdba30857b96753df0fd99afd76187.nq.gz
    ├── 045b64abc41e4b8f2d19cf0fd74a91308188483c.nq.gz
    ├── 047117fa7ef062cf5d97a606da6d8705bef2295c.nq.gz
    ├── 0472bdbac94fe74b70fe48f694b8f4c5352ada7d.nq.gz
    ├── 047783202345ebc55c6647fbe979cc78fc71d1ba.nq.gz
    ├── 0490aad9ce12e44d3851bd27264d34c39ad816f0.nq.gz
    ├── 04abcc40e470bf303cf63782f8a29a259a34ada8.nq.gz
    ├── 04ad703c9e44d8cc9fe379ee7174d0e45b57da09.nq.gz
    ├── 04c2848c50ccf3aa4d3c683c5b79dfc6eaaa2383.nq.gz
    ├── 04d35e3c93602ef32fd89bd770e51d430ab7b8c6.nq.gz
    ├── 04e6347955cf8874748ffea0e886d0c61dd300ca.nq.gz
    ├── 04f90c74c40b02671f2e6fa5d644e86d4b79507e.nq.gz
    ├── 056511699e593d46f3e0b77c478f8d3832b252d2.nq.gz
    ├── 057bb13611f26ce1714228973785dbf288db3c2e.nq.gz
    ├── 058678d36a998bead4cf64c0a741cae508b84e06.nq.gz
    ├── 059b94f77c3b7c10e766047be6a25d7cff8f2a3f.nq.gz
    ├── 059cb598a93f3425a8e9537a29288b9b6feb2917.nq.gz
    ├── 05be88c2c65b350e4ca395a0fa22520ec1514efe.nq.gz
    ├── 0633b73231d20e88df999ff7b12846cfe308adc1.nq.gz
    ├── 0637a088a01e8ddab3bf3fa98dbe804cbde1a0dc.nq.gz
    ├── 0637a7db0dedaa436cd0b0146e7cb564c373a1d4.nq.gz
    ├── 0638452f0b318c091cb59aec7a3f7e4c159cc5ff.nq.gz
    ├── 064fd9b675432efe83e286bee4e53b228cfeba29.nq.gz
    ├── 0668acb523da0c78eb39d6041f8205c5dd88815d.nq.gz
    ├── 0668f931945175ca8535db25cc27fa603920cc3c.nq.gz
    ├── 067393273ad51d8299708d73684a3249fb73ec2a.nq.gz
    ├── 067ecc4cff76df98b297f1251edca0dbbac12c6e.nq.gz
    ├── 06f7a0e3ea4ac34727d948d468fbf8cd6a36556b.nq.gz
    ├── 074b8e2d45d898c07e3e72df8e72670d92ee016c.nq.gz
    ├── 074ba8dec7fe59ffff1f4d598b4b056430259d73.nq.gz
    ├── 076d37ae0753148b3ac9d56cf48bb5a5ffd15337.nq.gz
    ├── 07d3a3ab33420ff5501a0a77079819e3b6f24d61.nq.gz
    ├── 07d46af6462608036dc8f7a4cbba3a448ee06c70.nq.gz
    ├── 07e569bed952acc3f1b1c3104814274cc0f976d5.nq.gz
    ├── 07e9484d4ddbe1e5d2086931e4e5de6c1399fa1d.nq.gz
    ├── 07efbcf4a64fbd8c3e061bd880d96ca006f48eb0.nq.gz
    ├── 0873d3d29c9518a4fb001fe099c9216feb98f643.nq.gz
    ├── 08bed89ff36fa877a42b75c0ba9a30a756691d2b.nq.gz
    ├── 08da40a685e8ceff43f1c927f3aae5d41a0c1e70.nq.gz
    ├── 08e8fa6a19cc772baf8727e04a7fe4fa92400a90.nq.gz
    ├── 08ed34269496aa38ef27b97af2e823d862fb16b8.nq.gz
    ├── 08efacda0ca98319f5cfaea91a9033361997f8b6.nq.gz
    ├── 08fc96e9fe45c3b1a5945f32040898954dbb648e.nq.gz
    ├── 0915d150d682df24ae053ce2cf5e0a734c7d43aa.nq.gz
    ├── 0963877461b7585a010a6b62292493d62efe9152.nq.gz
    ├── 096ef9d3f36be0ecf67af6def2ed329deb72184c.nq.gz
    ├── 0976533b1b4b1192503c66128e72e2aff1461d8c.nq.gz
    ├── 0991b6d1b9dbbbbbb638b92432319bcbfd60250f.nq.gz
    ├── 09a78ae6308f4c8c8701b1efa19c282b0b3519bf.nq.gz
    ├── 09b61fef22493b768f050c8b2d5cf5f87eac07ac.nq.gz
    ├── 09cfd8c3d7ef0a8d873d706787bb0580651235b6.nq.gz
    ├── 09d6968400d1d4993e855c7030ef6f4dcf533d5b.nq.gz
    ├── 0a023c904ff0332fca56d9d7353bf53b9e836110.nq.gz
    ├── 0a08a5ddd260e7069d33ee510e0d169e26d2c83b.nq.gz
    ├── 0a1437981d33cd1292c3632556f1d5a0248b325b.nq.gz
    ├── 0a185ab6ed0c2dd9b383a403c56c909bbab8b9a1.nq.gz
    ├── 0a2271186522260d2d6d9ecacad17567b660f1ae.nq.gz
    ├── 0a7612fea5dfe74707049b77cc3a0f3a0074c7d3.nq.gz
    ├── 0aa835ffe16b1300541addc369360aa19ef84e0c.nq.gz
    ├── 0ab99b4bfab4b42f5c6fb993d35511709de3c799.nq.gz
    ├── 0abc8196f7ce8fa9b56cafa9712092e9b26348a7.nq.gz
    ├── 0adec6f0640adbbc6d4f239b3183fc6f5cf60bf2.nq.gz
    ├── 0aee459757f4ada65bbfc860504c81332588d7d3.nq.gz
    ├── 0af7b122c831691a05ef7c6cd36527b199a29ca7.nq.gz
    ├── 0affd02095a5ad6c12863f4454edfcabfbdb8a81.nq.gz
    ├── 0b17de5099b41d637197127a141c1707020081ca.nq.gz
    ├── 0b359e4b4182680e53f1117b8716de6e25629816.nq.gz
    ├── 0b39b5c2f41dc1e370b7746c5ede0490b963e20d.nq.gz
    ├── 0b3aca4a46d57e6b2ccf76bfd6653e4be3f1c1a3.nq.gz
    ├── 0b83f64f07a8b706cc7786c94e4ed5ad19516266.nq.gz
    ├── 0b8dab2b3ef8b976caa2c3bd93bf727b923a3a79.nq.gz
    ├── 0ba50c3e93d139eabe425994fe78ad8fbcebd2b8.nq.gz
    ├── 0bb266d34799ced7d6b1b6f38b05afe859dce418.nq.gz
    ├── 0bfc647396f6456e847ae9c9f26006329c27c637.nq.gz
    ├── 0bfe1a98aa03ef74eb6b3d365102456bf34c8754.nq.gz
    ├── 0c111117da6aed3eedd152a0411497eb75c577d2.nq.gz
    ├── 0c20c6768d3341b74d7345f24406f2c6a01b6753.nq.gz
    ├── 0c557dd9ffdde1cfb580b303ef739c5679915c21.nq.gz
    ├── 0ccb7af81e49b1dbe1cf085ef571c099f2221121.nq.gz
    ├── 0ccf116fc1b52ab2442258073245226bb5c56743.nq.gz
    ├── 0cd4c8e3c5efd50d3dae3599624e9f211cbfc760.nq.gz
    ├── 0ce3f2468df549cfd209eee6eb402a359db18248.nq.gz
    ├── 0d10abf0da822500aa8e8159f81acc343792bce7.nq.gz
    ├── 0d12472175794f92a33b73266ec4434baa745416.nq.gz
    ├── 0d36a89baaa1826299be42ac8b467424b54cabf7.nq.gz
    ├── 0d731949048c1b44abbc4b48fb5ccf39bdd93267.nq.gz
    ├── 0d793f53d54d14426f2d494739d31c862d37c5f6.nq.gz
    ├── 0d94d59ca78e4fb45f1f850dbb2cb4a14146573f.nq.gz
    ├── 0d971e4b5693aa25d16e5f8b89cc2ace93fad76f.nq.gz
    ├── 0d9f1fd5a4f683f779972d62a02d89bb95c53f96.nq.gz
    ├── 0da5b640d720c8266dbaa97e36c29283046b4410.nq.gz
    ├── 0daa52c93680a1e68644b3bf4ed844917edeea19.nq.gz
    ├── 0db3fb43b6a3aca598d8dca8274ae4c0fb5204bb.nq.gz
    ├── 0db8d94cd60df7b4e261f775722c819ff24af657.nq.gz
    ├── 0dbd5980b0cb3bf119e3fbf84f7d24adcada9624.nq.gz
    ├── 0dbe457a82657522970819658098275c2f3c9aee.nq.gz
    ├── 0dc23b887b1255407076da79d6ae3cf65b4bdc0e.nq.gz
    ├── 0de00b736f4b5de6b38483811a49ac63bd146582.nq.gz
    ├── 0e15c6f537e6e8bf90f8c971d8026eb947f7560e.nq.gz
    ├── 0e4078dac14eed27f22d84cdd0a242f2ccfdff25.nq.gz
    ├── 0e4676f245f3e9e171ebd987cb2dfb4247e8f3c3.nq.gz
    ├── 0ea5037c84a5f29e4ad15174d91eca395644dbd3.nq.gz
    ├── 0ec3b7cff944caed68b2d26c8538178557bf33df.nq.gz
    ├── 0eefba993b43505d3b389016a7c3e189428f9cd5.nq.gz
    ├── 0ef2b62cde59f6c994f204c8a3e64895e2993d6d.nq.gz
    ├── 0ef6c2d69a82280049a5f7a574b2b5c3071794d1.nq.gz
    ├── 0f12dc44080b6529e09cba4a51026f48c6097b54.nq.gz
    ├── 0f13678d80a762375223f060e23b56c7b2eac89e.nq.gz
    ├── 0f32988c6b1e5a0f84be29ea92b18aeddf7a3974.nq.gz
    ├── 0f7b2570c3291b8921de0ab6a0943930d676619f.nq.gz
    ├── 0fa5723c67c2c67a92c692f45b6ed2419838f3b1.nq.gz
    ├── 0fbcf402184c81fc874f5afdffbc72c4f6bad29a.nq.gz
    ├── 0fc774a0ab335866d04cc7879b9bd92dcb14b3f4.nq.gz
    ├── 1006fcc86717f4635f6106b2f446648d08315aa7.nq.gz
    ├── 103a72b5df00e89f990f65fa9717cddba1edf58f.nq.gz
    ├── 103ceb44e92789a703df0d069fb67c186e504ed9.nq.gz
    ├── 104881a03dd05bb484d3db39ea70289198fa09fd.nq.gz
    ├── 104c58b1f88c1d8818fe2ade1b557f427c6f7a5f.nq.gz
    ├── 10a6ccee8c8d0b501ae32a7dfef612d4e2f3b32e.nq.gz
    ├── 10a92e9b94099f9531003ec797380bf5dfb8f147.nq.gz
    ├── 10c2560d0c5eb21eab703c71cbcd0cd44566671e.nq.gz
    ├── 10cb92b4831ecd2346c5c1bac397ddb2357b7846.nq.gz
    ├── 10e978b661fc291cbeea9ab0c248601cf216f96d.nq.gz
    ├── 10f537d72432d469437768049f05afafc4a4462c.nq.gz
    ├── 11064a1e4e3ebfaebac7e189b01707a3aeb0a2d1.nq.gz
    ├── 113ff3f1d19c3699767f744dad14aeadcee4fb4a.nq.gz
    ├── 1177336b7a9059be9637df212c5d934931f2a7ad.nq.gz
    ├── 11943f20940534c59323a45e53056c4a9763e473.nq.gz
    ├── 11a8a01f3a900c47f18c1f67655103ea97349157.nq.gz
    ├── 11a8df5f88c0236046d76e0bd8cc153ec6e5efcf.nq.gz
    ├── 11bcca0c7db939d367595b6afaf3db49da0bcb0e.nq.gz
    ├── 11c21363562dbf40f59f49cd1d5a26e0c0648b09.nq.gz
    ├── 1218afa0c12826693b2a32456f51a3f62f9be0c7.nq.gz
    ├── 12296387091b7d10820c3f5a2676528cf8ad3658.nq.gz
    ├── 122da4a487736a7099429df9d1997d8bbed0224e.nq.gz
    ├── 126a395793d3dec94390e6ffeb572509f7e2adef.nq.gz
    ├── 12bc1ccacb8723de15078413f91f3248bdece77f.nq.gz
    ├── 12f5139ff95b5ffb6c2749c53d012e332c1930a1.nq.gz
    ├── 12f9a5482252826bb2ccec67bfafb13b104f3b53.nq.gz
    ├── 1301aebae8952254d693269767eafbd861b755db.nq.gz
    ├── 13599c575565a6aaf354c82ed1d9edc1e9d6ea83.nq.gz
    ├── 13700df012007ae73e63e12555182b75d3899a4a.nq.gz
    ├── 1371bdd34098b1f8bf8601b6e71444658f03bb15.nq.gz
    ├── 1378ff1cb961912f6c0c2f623a529bad9b37daa0.nq.gz
    ├── 138b21e9d8285b6c5e13e4b25c657255cdd9e978.nq.gz
    └── 13aacade6119a8607abcc11fcbc6c5025a290f69.nq.gz

9 directories, 200 files
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

[NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
