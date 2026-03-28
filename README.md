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
└── blob
    ├── 0028b93fa2e96d13d0616f325596cdd1b0d372f8.nq.gz
    ├── 005a657d5294af48ca89edb95fed6d4fcd7dd2c6.nq.gz
    ├── 00d91de909e660945c8140faab8869ece24da149.nq.gz
    ├── 00eca12c4f34896489b795ce3629d2e21a8cd883.nq.gz
    ├── 011ede4c16a9a8913891b501621aabb22facccbd.nq.gz
    ├── 01204e8aa68626a2985086a934d1c3b45a8cccc1.nq.gz
    ├── 01339608d48529dbc96a6d231bd4a2f0666edd6a.nq.gz
    ├── 013ed663538442af094d36b6eda4d849f70e0c96.nq.gz
    ├── 0151daf2a1f70be30ca3fdadea9c7795e27a00b5.nq.gz
    ├── 019c08a0fe87266d33f86fbba5bedb2b5e10ec01.nq.gz
    ├── 01af1c15a0e12b64c676e4adb75864e1f25a88fd.nq.gz
    ├── 01b6421a52e56063edb8df7c6bc8c20905e0c2ae.nq.gz
    ├── 01cff91826aa250b53191ba4e61dddb3a395c2e0.nq.gz
    ├── 020e15bd606d022b3427f73f9bb9a04d47c756a8.nq.gz
    ├── 0227c9ee14b4aac3ad3734fe7f2c0dcb9bbeed63.nq.gz
    ├── 0232846ca1cee702729d8586c69df0aba69c7c6c.nq.gz
    ├── 0236b261d9e254ca1a72274fa6c7696f44eec979.nq.gz
    ├── 0288b620d2a759995f67fbc2f6a68a54d41b1102.nq.gz
    ├── 035f4d01c93aa31d53e6107c00d3653b48851f1b.nq.gz
    ├── 039ce6b2ef7c3b56a0f796345726c25634120ee5.nq.gz
    ├── 03bae5f60245ef5999dc1b5282f2bc3b8f9f9c45.nq.gz
    ├── 041909b071456e6993c221bae0985fd8d898b74d.nq.gz
    ├── 042e46f7bf9ab4b4e20d5255e78ebd38af66b963.nq.gz
    ├── 045b64abc41e4b8f2d19cf0fd74a91308188483c.nq.gz
    ├── 0472bdbac94fe74b70fe48f694b8f4c5352ada7d.nq.gz
    ├── 047783202345ebc55c6647fbe979cc78fc71d1ba.nq.gz
    ├── 0490aad9ce12e44d3851bd27264d34c39ad816f0.nq.gz
    ├── 04ad703c9e44d8cc9fe379ee7174d0e45b57da09.nq.gz
    ├── 04c2848c50ccf3aa4d3c683c5b79dfc6eaaa2383.nq.gz
    ├── 056511699e593d46f3e0b77c478f8d3832b252d2.nq.gz
    ├── 057bb13611f26ce1714228973785dbf288db3c2e.nq.gz
    ├── 058678d36a998bead4cf64c0a741cae508b84e06.nq.gz
    ├── 059b94f77c3b7c10e766047be6a25d7cff8f2a3f.nq.gz
    ├── 059cb598a93f3425a8e9537a29288b9b6feb2917.nq.gz
    ├── 0633b73231d20e88df999ff7b12846cfe308adc1.nq.gz
    ├── 0637a088a01e8ddab3bf3fa98dbe804cbde1a0dc.nq.gz
    ├── 0637a7db0dedaa436cd0b0146e7cb564c373a1d4.nq.gz
    ├── 0668f931945175ca8535db25cc27fa603920cc3c.nq.gz
    ├── 067393273ad51d8299708d73684a3249fb73ec2a.nq.gz
    ├── 067ecc4cff76df98b297f1251edca0dbbac12c6e.nq.gz
    ├── 074b8e2d45d898c07e3e72df8e72670d92ee016c.nq.gz
    ├── 074ba8dec7fe59ffff1f4d598b4b056430259d73.nq.gz
    ├── 07d3a3ab33420ff5501a0a77079819e3b6f24d61.nq.gz
    ├── 07d46af6462608036dc8f7a4cbba3a448ee06c70.nq.gz
    ├── 08bed89ff36fa877a42b75c0ba9a30a756691d2b.nq.gz
    ├── 08ed34269496aa38ef27b97af2e823d862fb16b8.nq.gz
    ├── 08efacda0ca98319f5cfaea91a9033361997f8b6.nq.gz
    ├── 096ef9d3f36be0ecf67af6def2ed329deb72184c.nq.gz
    ├── 0976533b1b4b1192503c66128e72e2aff1461d8c.nq.gz
    ├── 09a78ae6308f4c8c8701b1efa19c282b0b3519bf.nq.gz
    ├── 0a023c904ff0332fca56d9d7353bf53b9e836110.nq.gz
    ├── 0a185ab6ed0c2dd9b383a403c56c909bbab8b9a1.nq.gz
    ├── 0a7612fea5dfe74707049b77cc3a0f3a0074c7d3.nq.gz
    ├── 0aa835ffe16b1300541addc369360aa19ef84e0c.nq.gz
    ├── 0af7b122c831691a05ef7c6cd36527b199a29ca7.nq.gz
    ├── 0b3aca4a46d57e6b2ccf76bfd6653e4be3f1c1a3.nq.gz
    ├── 0ba50c3e93d139eabe425994fe78ad8fbcebd2b8.nq.gz
    ├── 0bb266d34799ced7d6b1b6f38b05afe859dce418.nq.gz
    ├── 0bfc647396f6456e847ae9c9f26006329c27c637.nq.gz
    ├── 0bfe1a98aa03ef74eb6b3d365102456bf34c8754.nq.gz
    ├── 0c20c6768d3341b74d7345f24406f2c6a01b6753.nq.gz
    ├── 0c557dd9ffdde1cfb580b303ef739c5679915c21.nq.gz
    ├── 0ccb7af81e49b1dbe1cf085ef571c099f2221121.nq.gz
    ├── 0ccf116fc1b52ab2442258073245226bb5c56743.nq.gz
    ├── 0ce3f2468df549cfd209eee6eb402a359db18248.nq.gz
    ├── 0d793f53d54d14426f2d494739d31c862d37c5f6.nq.gz
    ├── 0d9f1fd5a4f683f779972d62a02d89bb95c53f96.nq.gz
    ├── 0daa52c93680a1e68644b3bf4ed844917edeea19.nq.gz
    ├── 0db3fb43b6a3aca598d8dca8274ae4c0fb5204bb.nq.gz
    ├── 0db8d94cd60df7b4e261f775722c819ff24af657.nq.gz
    ├── 0dbe457a82657522970819658098275c2f3c9aee.nq.gz
    ├── 0dc23b887b1255407076da79d6ae3cf65b4bdc0e.nq.gz
    ├── 0ec3b7cff944caed68b2d26c8538178557bf33df.nq.gz
    ├── 0eefba993b43505d3b389016a7c3e189428f9cd5.nq.gz
    ├── 0ef2b62cde59f6c994f204c8a3e64895e2993d6d.nq.gz
    ├── 0f13678d80a762375223f060e23b56c7b2eac89e.nq.gz
    ├── 0f32988c6b1e5a0f84be29ea92b18aeddf7a3974.nq.gz
    ├── 0f7b2570c3291b8921de0ab6a0943930d676619f.nq.gz
    ├── 0fbcf402184c81fc874f5afdffbc72c4f6bad29a.nq.gz
    ├── 1006fcc86717f4635f6106b2f446648d08315aa7.nq.gz
    ├── 103a72b5df00e89f990f65fa9717cddba1edf58f.nq.gz
    ├── 103ceb44e92789a703df0d069fb67c186e504ed9.nq.gz
    ├── 10a92e9b94099f9531003ec797380bf5dfb8f147.nq.gz
    ├── 10c2560d0c5eb21eab703c71cbcd0cd44566671e.nq.gz
    ├── 10cb92b4831ecd2346c5c1bac397ddb2357b7846.nq.gz
    ├── 10e978b661fc291cbeea9ab0c248601cf216f96d.nq.gz
    ├── 10f537d72432d469437768049f05afafc4a4462c.nq.gz
    ├── 11943f20940534c59323a45e53056c4a9763e473.nq.gz
    ├── 11bcca0c7db939d367595b6afaf3db49da0bcb0e.nq.gz
    ├── 126a395793d3dec94390e6ffeb572509f7e2adef.nq.gz
    ├── 12bc1ccacb8723de15078413f91f3248bdece77f.nq.gz
    ├── 12f5139ff95b5ffb6c2749c53d012e332c1930a1.nq.gz
    ├── 12f9a5482252826bb2ccec67bfafb13b104f3b53.nq.gz
    ├── 13700df012007ae73e63e12555182b75d3899a4a.nq.gz
    ├── 1378ff1cb961912f6c0c2f623a529bad9b37daa0.nq.gz
    ├── 13c34507028945fa2097d417ec3e3677c1ecc6ec.nq.gz
    ├── 14b766e5b58bbb5e99ce3a3f107dc9d4904cdf6c.nq.gz
    ├── 14b9b6974487839ca39b07ad371f088e7253f787.nq.gz
    ├── 14c3f0dd67e84d3d0d97b56e4f922665fb4853a8.nq.gz
    ├── 14ef488865f3ae6150776220ebbcf4788f89066a.nq.gz
    ├── 14f9c6bf30d0d16d33b39ba53db67af314c08a53.nq.gz
    ├── 14fe0c4a3162115b6f3d35fbf4e45dd8daff2388.nq.gz
    ├── 1549d5170e610309e4632086c966de2e69f4a363.nq.gz
    ├── 15890015b94016b2948b0afa2ec4d8a45c50a19d.nq.gz
    ├── 15c0705cfe9e27fbbe499597c5bcee5475aa4294.nq.gz
    ├── 15e2e6634cc8025273797169cf48f6d13580013c.nq.gz
    ├── 1690d2b45250b0eb9f1319d2fa6bad0c8341761a.nq.gz
    ├── 169c63e8aced80ac38565b225fc749774962b033.nq.gz
    ├── 16a15aea442e146a6aa2a0bda5142c8ef76df2ce.nq.gz
    ├── 16a418da87cbe90a78487fd8729a95a8d542b7d7.nq.gz
    ├── 16e144541cb07687e8b64cc0ecf9ac595e471037.nq.gz
    ├── 175fd1e063dede9b61891b0c74f022b35ece2b5e.nq.gz
    ├── 17689ba1d35fee0133703ff5f021e5427a647a50.nq.gz
    ├── 179f46b6e92e4d6a0d28b2731264dfb1bf7169c6.nq.gz
    ├── 17e7cf0f79bef05998be467301ffd3cd00d4c27c.nq.gz
    ├── 18440ed9c270f219e0927176b17a5bf1c267612d.nq.gz
    ├── 185710cf08ecd16dc081e4c88a2338491f44ac00.nq.gz
    ├── 18a4497cec3fe59e40ebd9b35266ea1d8b5416d5.nq.gz
    ├── 1902d8c5c50ea4e5d80fded042c934cd8fd2d120.nq.gz
    ├── 195f80ab339eb0ad46a500ee1a3a55e864904a80.nq.gz
    ├── 1982f5e88a3c6b3e2004ca4b7e02c93d1371f3cb.nq.gz
    ├── 1990fcfe19c9494dcb8238e5c741c0b0d0ae8db1.nq.gz
    ├── 19c1159d2645e617a364b7a7ca90410bd33bdb66.nq.gz
    ├── 19dba47bc2b35671190fb4082fee25ea6c578bb1.nq.gz
    ├── 19f844cfcc651fed9bb76f0986a61cfbf69f6da6.nq.gz
    ├── 1a69f6528f2195865302792d6eac659d2534c607.nq.gz
    ├── 1a779f8a0bb7d3cd3629147ae4c95b293b38011e.nq.gz
    ├── 1a7a9da5185170dd0fbdeba0f6d8968290a0ee6a.nq.gz
    ├── 1aa0e11445afd496bf2509a42d392df5f7353ee3.nq.gz
    ├── 1aad8e6e07b7a2ab718411b008d5f8b2aff8bf68.nq.gz
    ├── 1afe7ffcb993eb1c91409ba77f8fae87162d99b9.nq.gz
    ├── 1b52c15f896b724e18f2cb79881c27f4a3d56d42.nq.gz
    ├── 1b6216c50a8581165c168891364656100f8f0b68.nq.gz
    ├── 1b7a1d78b36daa3c1349f3a66b9656e37e1820d6.nq.gz
    ├── 1b9bb462b18408b50e18e30e9fdd055a3734791c.nq.gz
    ├── 1bfed6bfc4ba67f6f5e9509d8d1f7928dc2012e4.nq.gz
    ├── 1c0a5e7e9e474d1b90b28397aeaf0c462bf8c34f.nq.gz
    ├── 1c46b75cca0f38ecf0c129d2ba850692706401ed.nq.gz
    ├── 1c56725aae2af2fbf0e15ac107051a4c7ab20cf9.nq.gz
    ├── 1c587a54d5613355974d8ac25ebb7d5d741c84e0.nq.gz
    ├── 1d1d29bd7fc78b4f92f5cd97bf4f750cd128deda.nq.gz
    ├── 1d7629ab633222ac93702d0b7433000f589b2952.nq.gz
    ├── 1dbf05140d07fa014f18a5630acc0613d8058e52.nq.gz
    ├── 1dd6c680e654b957d5a50bac2fa0819e7cf7aa61.nq.gz
    ├── 1df449986daef5fb8bb0a64434597cb5f8a59b4c.nq.gz
    ├── 1e78480975a5878619e71b1dc7957d6eb9489c4b.nq.gz
    ├── 1ef323c16f11c5984ba31706428355a9d0b2ea28.nq.gz
    ├── 1f5975ef6ae3b62c02d93fd2248c3db697e36a97.nq.gz
    ├── 1fb9ff4196d2c7a6aefd79c654b433bc71faef8f.nq.gz
    ├── 20840199596d3c737e5a0cd4491d7a6cfe0b64d6.nq.gz
    ├── 20b64b0131101e93ccf73696ecf8b7892dc3450b.nq.gz
    ├── 20cee9fc8242b708e03f465c3d8b6a9fca08d620.nq.gz
    ├── 20f7d73a8fe0379daa058d1db1772af0c5a857ba.nq.gz
    ├── 212c49c0f26a1e05ff72eea949c4c1fe366bb731.nq.gz
    ├── 2132e5bef778cd802783de9ca8c0a23139defc44.nq.gz
    ├── 219f281bd0acaff696c7305e7aeced692f4950c1.nq.gz
    ├── 21bb176c8f9b9e96dadf9a768d29fe8bdc593722.nq.gz
    ├── 21ef7fdbd589f2831984a4c8cd0d668224cfcdc6.nq.gz
    ├── 2200f75c2f80f3c60a7eba508bdf90c18bebd1b5.nq.gz
    ├── 22063e73489483524e7152985f55848cfc1671aa.nq.gz
    ├── 22678c96be9301c6d9c4056d9d8bdd416ac5e185.nq.gz
    ├── 228a93e7c0a0f395c4a47724a4434339c96c5792.nq.gz
    ├── 22f651e41899e6aeabae89506ef7bbced4c914db.nq.gz
    ├── 23108525d5acc66dc7dfd3adab224935bc558668.nq.gz
    ├── 2318ec80e5304b51d87dba57756bb5157eb18ce6.nq.gz
    ├── 2384715f949cd6e8315d16fee9214f4eeea6308f.nq.gz
    ├── 238506b05a6cd4a4c1a4a9fd49c42e35386b63ff.nq.gz
    ├── 23b96d1cb196c77597d50f1538498d4eb1ae0fb7.nq.gz
    ├── 241c17f8f6c7d8a4452200de277958637cc40722.nq.gz
    ├── 24432093acc15546118d66e9812954c9daf0139e.nq.gz
    ├── 24c34c5329f8d81fc9773b4e4e93e6da6de822e7.nq.gz
    ├── 24eb08a27779ef9c1975f1d95e5adafe1cf42f25.nq.gz
    ├── 25a8417170c9645fc7806486bd89d64665e5bf1e.nq.gz
    ├── 25cddde6e8dc9942aeed3f75ead260f7dede52b6.nq.gz
    ├── 2645256a180871c943815e7134fda0bfd1c83aad.nq.gz
    ├── 2674373a7754262f653a63878026e307c1f858bf.nq.gz
    ├── 26dc1b8d7f4d3ec1a09d7b7be1d1d7171bcd178c.nq.gz
    ├── 26ec11a6e5e90172341fc94df5c6faeea11ce566.nq.gz
    ├── 27785c9ee949fe9362e61095c3111a97d7594af4.nq.gz
    ├── 27c96ad4b2cca4460e5192e6c595daf2480cea07.nq.gz
    ├── 282bc06b0b354b8fbbaca4992582cd065abd4e36.nq.gz
    ├── 288c38383677ca0b14837d1b4abd024596777d71.nq.gz
    ├── 28b7cf754afff58f852c70af57155fa742e71d1b.nq.gz
    ├── 28bb0ed12a82c6b36edc1ff355747af780c97294.nq.gz
    ├── 29f40fc2435617fe36b2a771831f8efa199d29b1.nq.gz
    ├── 2a3d2470fb61ddc249ffc36e14404d387989f119.nq.gz
    ├── 2a4dd4ff02965523e5a9e4737fdd393ebfa4c295.nq.gz
    ├── 2a6042a7004da8401809397d1bf3f140a0c377a5.nq.gz
    ├── 2a6044294f38de2b049b6fc5acd605ef361aef96.nq.gz
    ├── 2a93865b7810ab709ef77a765c17153c5ad22404.nq.gz
    ├── 2ab6b0ea4a234ade23e8b5ffc1c257f3fb2b89b6.nq.gz
    ├── 2b0f793315e90184c0695cc314f3122fefba6d55.nq.gz
    ├── 2b47ff3eedba29c3f4f9926d5eeb293f556c1408.nq.gz
    ├── 2b4d2f7054bf256b7416c663db09e4498e7d5b1b.nq.gz
    ├── 2b544dc982f60417274162d5d7fa5fdd453603df.nq.gz
    ├── 2bddce29214882eb9fdf2be8a50ed5bdd0c69dfc.nq.gz
    ├── 2c00495c8e3aecd0034997bc155c97a8bd4a7569.nq.gz
    ├── 2c44cabf6b81fb1a81517b4770b9190ad7824b55.nq.gz
    ├── 2c4a160ceb721402e21ae107cbea45bbd80702b5.nq.gz
    └── 2cd29c76753b64ce448552e4c07ea91e53c1bc25.nq.gz

2 directories, 200 files
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
*Parsed on 2026-03-28 by [repolex](https://repolex.ai)*
