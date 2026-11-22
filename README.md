# Repolex Knowledge Graph of knurling-rs/defmt

RDF knowledge graph data for [knurling-rs/defmt](https://github.com/knurling-rs/defmt), parsed by [repolex](https://repolex.ai).

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
rlex download knurling-rs/defmt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7814e1c6cafbf25a896345fd61327627372df4c6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 7814e1c6cafbf25a896345fd61327627372df4c6.nq.gz
│   └── repolex
│       └── 7814e1c6cafbf25a896345fd61327627372df4c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01077a56373b229edd0f15cc3328ba9c895ae72a.nq.gz
│   ├── 026620b806afbba6ba6501cb015f338888245a4c.nq.gz
│   ├── 0652bc0df9346abed76b613b17c7f706f3e5f73e.nq.gz
│   ├── 06cbd03a0deb326198c11cace20bf914db165eac.nq.gz
│   ├── 076cd02678956c70833eaa7df622256ec8f4b3b6.nq.gz
│   ├── 08294cd81d66fd15fe2773aaf557a0ecd0fd9ff7.nq.gz
│   ├── 0aa72c448f03ee68c0d87bcd8945b935793ea2cc.nq.gz
│   ├── 0acc084800bb5a6fb12b2e43454e17f267a99c15.nq.gz
│   ├── 0cab8f57f12a7842f083052cc44c1c7bae5b2868.nq.gz
│   ├── 0e6cf191d25c77ce430dde96727de7d79824c6b1.nq.gz
│   ├── 11069edd79019f7dafbe3138841cf289209270dd.nq.gz
│   ├── 131db669b55ae2c402f14ed7eb9c3cc0844621d6.nq.gz
│   ├── 13d22ca1e09c0c483fdb84091bc5500712747025.nq.gz
│   ├── 14a18ede35d2288723581b77eed38e70fde8f4db.nq.gz
│   ├── 14b6225c735ae2ec44362c29e8386a51313f648e.nq.gz
│   ├── 15a838419ab4b063a0d3f986edfc3c9a67625e27.nq.gz
│   ├── 16bab3d4fd900bae61320d8d066022093cc49fa6.nq.gz
│   ├── 16e771c484ce46df88edcdf8bcad195db03dcd6e.nq.gz
│   ├── 17bbcee3004393ff1dba51964b26f29a0f8b7d8d.nq.gz
│   ├── 1f7e65c4a24b08180b3a3cd235ae410c66bbcaaa.nq.gz
│   ├── 210e4ea9f3e97d6e25dd419d502d97e15c6c4d00.nq.gz
│   ├── 21d65dae8782dfda4458a428ed3d9e2e19b7ae31.nq.gz
│   ├── 23aff3b8b0dde1a57b6fa3d84259db72183d4124.nq.gz
│   ├── 28a2faca0893646d609af8a71f9f1c37ad7e9681.nq.gz
│   ├── 2d761561839b8f017a2684057a49a4572843fc71.nq.gz
│   ├── 2e03cea4c7244883d08e747f50098ed6497b4cea.nq.gz
│   ├── 2f6113d18651c1004be367742e6ba27317a3e364.nq.gz
│   ├── 2f876a6831b4f3e6ec06df2e9afea932cf87f551.nq.gz
│   ├── 30ef4e2e8cf8d5a7259a6f3cfa86e57e51ae94a3.nq.gz
│   ├── 3299ee4f89787be6d770dc753bf3d89a582c4f40.nq.gz
│   ├── 3447c411fff28dfe8cb4b064caba489a582faa1c.nq.gz
│   ├── 354a8207285f3699fd23b00ee4184d09451d98b7.nq.gz
│   ├── 36d6614297213225cfcc88ffe976c11eecf9162c.nq.gz
│   ├── 3868aea9eb770db955105970f735599f98c58d61.nq.gz
│   ├── 3a62bf7f8a382441b41a4fabd91ee08ccaf4d13e.nq.gz
│   ├── 3c352bc4f8b387a72850fbd4d6fa6cc9bd673aeb.nq.gz
│   ├── 40090861b48df00027a3f0021c5001c0c94e372c.nq.gz
│   ├── 42cec4ee34a23a2b98371d92e138f2dd9913fa69.nq.gz
│   ├── 43af3a48bd2cd981663fc4f24098bb3bdadded43.nq.gz
│   ├── 443917705f6a7c56aa27ba68bd42b5a672c4fd40.nq.gz
│   ├── 468cd79a8f6e50f2b24558c41ed3abafa5bb40ae.nq.gz
│   ├── 49c1031cc739db032f7b611758ad62a99d6ac778.nq.gz
│   ├── 4a3066ea9b03e8a219e5ed96ee98ff30df48dd52.nq.gz
│   ├── 4fc58dc1f67178969ac9261e9ae17b5ebab4f170.nq.gz
│   ├── 50214d71562d677288b23fe13b02577bfbb3dfdb.nq.gz
│   ├── 58ddab9752075bcb8295fe4ee945c53df7d09bcb.nq.gz
│   ├── 59b2ffaf13ee7f31ac2648dbaf3d7855caad42cb.nq.gz
│   ├── 5a5355e397c889993de197b0a854700b100d676a.nq.gz
│   ├── 5c2062345cb539f7e746cfcfbaafa5322697eef7.nq.gz
│   ├── 5c9505dedc83b30aa9d06678ccd867806ae0fd77.nq.gz
│   ├── 5f05cc9a72eb1dd265b724c17f5548223a4bef77.nq.gz
│   ├── 601f6206970cb91013fffe1888d48cc126014e68.nq.gz
│   ├── 60d1f9b10c31c0d945262345fe19a1307efdf7a7.nq.gz
│   ├── 61010c9c6b7403a704dd20ccb2c5571a00d70c92.nq.gz
│   ├── 61a935077c9a5897cf3e7a417ccc9654a031938b.nq.gz
│   ├── 63cdcafb2ef7cd845359d511960eb4be56c8aa04.nq.gz
│   ├── 6491428c0207ac9cfd47ea03a7a2ed948dca16c0.nq.gz
│   ├── 64ce5e664a37ad499d0eea1bcaac335954ea3832.nq.gz
│   ├── 6537bedbae9d75d45e0acaa12a4c03f9c9881da3.nq.gz
│   ├── 6557497696c5f11f38f8f924676429283bde3f73.nq.gz
│   ├── 65dbd9263cdf4aa7c660d69fee945954cd25f6cb.nq.gz
│   ├── 67c39c71185d05195257b0a72cb89e1131cf94c3.nq.gz
│   ├── 69655038d076d38e1acb15b3c67883dd7b59e103.nq.gz
│   ├── 699f79992e1950b379041fa89fa011166d7f71b7.nq.gz
│   ├── 6afe5a2c5902f5fe9958999a91352c66e25b56f6.nq.gz
│   ├── 6bafe7b83c69e80f80704600868f226f19406299.nq.gz
│   ├── 6bc3f9c3c3d24abd21c6050d1d01e2b3ffb728a2.nq.gz
│   ├── 6c86529223e3b7cf74ee111b382ca2bb3b1f9511.nq.gz
│   ├── 6e1349df7df2f234ae5e43e2eaf0357e11d18ada.nq.gz
│   ├── 71c789efe8950a450fc7cbe8c72716e8a0a3bb2e.nq.gz
│   ├── 72d6f2a34e40017cbb327cb3bb4bc574f0a8bdab.nq.gz
│   ├── 7585238efedfc33acdd9494b0269951aaf3909ec.nq.gz
│   ├── 7c69179c6ed5f57169ec2d63f33c6adab77990e6.nq.gz
│   ├── 7eccdc1f3d9727ab20743a4152c9a28f604fe4b6.nq.gz
│   ├── 7f7eef7dcdce734c9e59224fa18ed2389577aac3.nq.gz
│   ├── 8121721ebfdd113c346adfb6c5f95c51f1be814d.nq.gz
│   ├── 81c821ef6791c5c04bfb8aac7faf85010fd385c7.nq.gz
│   ├── 829c19657c2974097d2808763ae8253d523d3d66.nq.gz
│   ├── 86433236684090eeadeb069aecbf7ef69d5f3870.nq.gz
│   ├── 88f7fef81f872bd233dd7c6b13bfe04dccb5a276.nq.gz
│   ├── 8a0c13f119caed02ca540e281a41ea56b6b4c1c6.nq.gz
│   ├── 8b41ad6c19c4dc62abc3a3aa186c5e12fd2aa0a3.nq.gz
│   ├── 8d2e03399b814e987639b30bb4c1dc988688a41c.nq.gz
│   ├── 8eb8410ed0251d947bc8241a3f901564492dcafa.nq.gz
│   ├── 934e8b5088f166bdb711ab62d41d2eb1ab2d5628.nq.gz
│   ├── 939d59681a22ff8d95ba6297fd8d8a4a61ee3ba6.nq.gz
│   ├── 95de161bed6014ed78475144014864ec3d0cd65e.nq.gz
│   ├── 966c8aeabeb4522a906f84ec445ea4e7c4e395c6.nq.gz
│   ├── 99591e35f4ff5fd668e6dfb828797fb2f90f9711.nq.gz
│   ├── 9f12c7da71e0e4a403c6dcb97a04fbbfcb6c9d48.nq.gz
│   ├── a0463961c06759187af489efde878a937fe8e7be.nq.gz
│   ├── a2a194309b48af509710d1f6c3e1877016aebda4.nq.gz
│   ├── a4659d2c76f4ef58e69b91c5492267127470cb0a.nq.gz
│   ├── a4b093f6299630ea0cd8a7d4f68f1122aae42989.nq.gz
│   ├── a78ee710ddd633ce3f78f3867ead1358eb2ce2dd.nq.gz
│   ├── a8725b68cdd2656096b93d7087c8aa89b43561bb.nq.gz
│   ├── a8818c1189b0af53e7563a1919b6599f5c9db766.nq.gz
│   ├── a9bf7ee851336f30f69aeb0fe0fb9a973eefab3b.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── abe5c86baba6a579d27f341814c54a8dde00b677.nq.gz
│   ├── ae36df62ba5679d9ac015896ec526caa7b7a691b.nq.gz
│   ├── aef5106fb339ed4f27a2a7342cedaf4481cacbcb.nq.gz
│   ├── b40d97d40ed87519e3ec51064008c0a219e6d372.nq.gz
│   ├── b5c372c05049c315352fe91a76602e8a3e0a5775.nq.gz
│   ├── b5e5005cfb80807d7b5ae40370aede9a04728f0f.nq.gz
│   ├── b671a49809e8db3de9a5bd2a3e473d73975faea1.nq.gz
│   ├── b76ae95f65281ca6ae303fb184bb64444f893d1e.nq.gz
│   ├── b8e1ef10d79ac1079dd81222160d49d95c31b74f.nq.gz
│   ├── b8f96c4bbaebde977d447114c74c11a53c2b991a.nq.gz
│   ├── b9bc7c219d18fd46efc83bedbebe22a8e16a31b7.nq.gz
│   ├── baf47653bbfebfc1bccc41038511bd7b84dad375.nq.gz
│   ├── bcf2107fc48aae0350590e6d0d2424e384746494.nq.gz
│   ├── bd97b1dfce6204bdae72dac616a4e2d46f2e6659.nq.gz
│   ├── c13fde55c3065ca89acc0c38bb608b7797ae363f.nq.gz
│   ├── c29579aa4a1f049916df8d6bb237098b43f6bcc2.nq.gz
│   ├── c2a30226d48efaa31c512a3b3fd1a3b8d24cf8c0.nq.gz
│   ├── c31ebe48cd84536c4ef7a97bc74d2ea949de263d.nq.gz
│   ├── c3680bdae420a484b62604c77c651c029df1f23d.nq.gz
│   ├── c64a4f1bdb9fe02a95b738b4c269abcfd96a665a.nq.gz
│   ├── c689222e3b12c9580337b225b9683065d5c90dfe.nq.gz
│   ├── c8e2bdf02c9a890dbdccc573eb3a4f57544de538.nq.gz
│   ├── c9acc5d1dcdf3f52caeeb2fdec77d91bb088aad0.nq.gz
│   ├── cab4b723eb64f0e018911fd10aadaa4a1479c85a.nq.gz
│   ├── cb05d8ab604301293395d1927bacea0495641e2d.nq.gz
│   ├── cc02f3129d894d53c6ce7eb8958db9c6ec871e83.nq.gz
│   ├── ccaa5d08920740bbd03bdfac765ead09697426f4.nq.gz
│   ├── cd202b33b8f0ea4fd9d5b02e6c78482f06c90679.nq.gz
│   ├── ce0a7f3d1aae1a424749400aa9601a56ace0cd72.nq.gz
│   ├── d19803152e4a3ca592e9ebb66d13db4fb8c9b3a8.nq.gz
│   ├── d2f63890f89b865d6ddcff94e15ee7a112e43ea2.nq.gz
│   ├── d63744b2a947dd1f7a1a1edbbff2d0389317536b.nq.gz
│   ├── d7f80c52363ddd8164f799c65abc2f7291c3e5c7.nq.gz
│   ├── d8c34ef0ba9811745063e2698a6c261b3bba857a.nq.gz
│   ├── d9b96eac63f6fb37e4c10405b0119e71ba99736a.nq.gz
│   ├── da5eda71300e7e44c5994a1f95453b71d56e9840.nq.gz
│   ├── dba48c0a89d732e6e31bd95cd6f457a08ba3ed18.nq.gz
│   ├── dc88e6cf4a7a9cc2efb847e8a7809252fd62f01f.nq.gz
│   ├── dd398aeac4fcf68b628bc7beb742c52e3b7fb4a2.nq.gz
│   ├── df43bda44fddf56ad3260167412c650fab852a92.nq.gz
│   ├── e23da75805c2a5d74e0eabd82943fb206a313dfa.nq.gz
│   ├── e4ba05e2a0cc5b05df6859563b3922631a763570.nq.gz
│   ├── e664ab0049046e561e98c13eede1f7341461b29c.nq.gz
│   ├── e99e2d792431f7901ac0259fde8afe37c7090cf5.nq.gz
│   ├── ef963e275583ac52ce0ec8001e1412c477499771.nq.gz
│   ├── f028fd68f13ed1fd0c9f9e9e4d3c29a814f2e8d5.nq.gz
│   ├── f179076f485d3f2e04f762401c828fe5f8bc14c4.nq.gz
│   ├── f37fd2054cba05b7fba9d2fb133ef4ead429a311.nq.gz
│   ├── f4f6f150b8f1492b34bdd4b5db742a387e1d226f.nq.gz
│   ├── f7d4de54e19fde445f391cc162252c1e9adf3ba9.nq.gz
│   ├── f7f66a9cc4b11acf468d3047938c508a18a8046b.nq.gz
│   ├── f885634c611473a92e0290e74e16ccb1df05cc45.nq.gz
│   ├── fa451071df14deff7933731a0f503df8f72364e1.nq.gz
│   └── fb9e0661c6d9449a3dc925f286f7bd26392c1469.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 7814e1c6cafbf25a896345fd61327627372df4c6.nq.gz
├── filetree
│   └── 7814e1c6cafbf25a896345fd61327627372df4c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 163 files
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

[knurling-rs/defmt](https://github.com/knurling-rs/defmt)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
