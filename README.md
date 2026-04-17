# Repolex Knowledge Graph of facebook/jest

RDF knowledge graph data for [facebook/jest](https://github.com/facebook/jest), parsed by [repolex](https://repolex.ai).

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
lexq download facebook/jest
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 67c1aa20c5fec31366d733e901fee2b981cb1850
│   │       ├── chunk-001.nq.gz
│   │       └── chunk-002.nq.gz
│   ├── lsp
│   │   └── 67c1aa20c5fec31366d733e901fee2b981cb1850.nq.gz
│   └── repolex
│       └── 67c1aa20c5fec31366d733e901fee2b981cb1850
│           └── chunk-001.nq.gz
└── blob
    ├── 000bed86e804ed23460e3fb4eff664e557c0b4e8.nq.gz
    ├── 0013a08d081fac2c6ddc4e706e98e8b3de2ccd61.nq.gz
    ├── 001503ad57fe271fd197e42b8c349702a6543fc5.nq.gz
    ├── 001968d98e1b78ed5d9aa1a57135f86863447fec.nq.gz
    ├── 00246b97111358843e09273f295a45767424e472.nq.gz
    ├── 0029e5f6ff9ebcb13841d3df01fdb272814f1417.nq.gz
    ├── 002e3a9738fffee934b0b44f41861dd82dc98bb4.nq.gz
    ├── 00415cbfc572277f7282efc86c871b5c5f42790c.nq.gz
    ├── 004885a68c1b9a76e426a3d1f6efa90c72a0b704.nq.gz
    ├── 004ace393d137e2c3569b10f5c8329037194f524.nq.gz
    ├── 00562172fff90e1619bae936faf19e804ab8e6ff.nq.gz
    ├── 00569d511ff5c91bb6d08de4b79b5dd3e4688e02.nq.gz
    ├── 00593e14b4ef087a552e141edff746695b637941.nq.gz
    ├── 005ef98f211c74d73e71fca5475df83e4fd35a03.nq.gz
    ├── 0066317b7d814a9f1ba74cf20bd0ce74e3c99554.nq.gz
    ├── 006f2357e83e764a9a03458fb2d5aa9da7bb8642.nq.gz
    ├── 008d5b3f50e21c52e1c182bfd58b531276f2375f.nq.gz
    ├── 008dc10d9bab7001e7eb10d7ce827485daecf3a4.nq.gz
    ├── 0093d0f769a75e13f73010464506a23682689718.nq.gz
    ├── 009c00cb92bd6b9f34a5cdff5fb41acce9ba522a.nq.gz
    ├── 00a64ee35a6f35473179bf4a07d6c2e690c2a81d.nq.gz
    ├── 00a934b64559698b4d135a560ab2c97263954c30.nq.gz
    ├── 00b319311d1e0e49116589146d396e0045180f66.nq.gz
    ├── 00b69bf7097e0afe67d54fa72a87b2290fb2c728.nq.gz
    ├── 00baa350c9aec7aa5748e831e34db8b54bf67f86.nq.gz
    ├── 00bb293f258e815aab6f4b5a22e5efafb19c695f.nq.gz
    ├── 00bfd14d0bd797c04412fb527b2d286fba3f81e4.nq.gz
    ├── 00c2ef1292e0f9956769016138fdbe3468975994.nq.gz
    ├── 00cc817bb59d40c19ecb64607761dd872f768fb6.nq.gz
    ├── 00d138b99214fe4fcc85fe5e8ca1ddc729dd18a5.nq.gz
    ├── 00df2a4f383760cacc04134619df6551c86a6370.nq.gz
    ├── 00dfeafee70709ae3b2aa461f2c8d20b090dc100.nq.gz
    ├── 00e39eced7a2643790cf1fb418f7870950cbae16.nq.gz
    ├── 010324e24593c1035de2b7603890a36b33b0132f.nq.gz
    ├── 0137be8037a56d81805fe1c566361ad1cb701f5a.nq.gz
    ├── 013b4d9a9c986cb11861d4e18981cb54e0f71b66.nq.gz
    ├── 013de89711338e40aa3b6855276428211c269e55.nq.gz
    ├── 014006ee0b2a3c91dc5b1f8804d2c2b974011303.nq.gz
    ├── 0144a2f64a3b59e6d0009843dfe2a144da62e32f.nq.gz
    ├── 015de4de23b879c05113cff9f7475596b655b03e.nq.gz
    ├── 016f7dd30d62ace360202dbc9d997dd9313462ee.nq.gz
    ├── 017bfa27008864669475562782c1b75dea5df06c.nq.gz
    ├── 0181635309cff40894af52fc62b5afeb7ae49d47.nq.gz
    ├── 01870c19a4b62890f8fb6bd4b1772a10aaf36edb.nq.gz
    ├── 019ca685df840a2905b471dfec65694b28056246.nq.gz
    ├── 01a2daf59f8a7a0f3c09b880988fd62b9bdb48f6.nq.gz
    ├── 01a675d29beeaf1950496f33581fca8b33001fa4.nq.gz
    ├── 01ac5b96108e697baa6923978604c31c657fbb3d.nq.gz
    ├── 01c2868a6b2aeb7c6119b341ecc4e3309a7b9619.nq.gz
    ├── 01cb7f85a591aa1cb2ccc530e035e2fdf8e9927b.nq.gz
    ├── 01d4476728b743fd09672283ef5f7471a41ce3e5.nq.gz
    ├── 01d760010709d5b20ccc935c398679fe0eca7e27.nq.gz
    ├── 01dddbe47c482d4fcd1a6bbcf2f86be20aedb412.nq.gz
    ├── 01e96d92d8e239a39e5c59a53f77dad53e213291.nq.gz
    ├── 01f02767e0b2ce66d6a7295260071dcc85c2847e.nq.gz
    ├── 02068f11be331c6f913f99aa80c48d6d4303651f.nq.gz
    ├── 021655db00d09b12f0e57c26cc09eeaef114e57e.nq.gz
    ├── 0217b7649c2e65d7925d489effa03afa91daae64.nq.gz
    ├── 0228a8a723c3c0ef214db1109673b74ac4b7c7c4.nq.gz
    ├── 02310895e016657dec50ac47f8001d8adec51bfd.nq.gz
    ├── 0238c408fd911a02f49beecb51252881662447c3.nq.gz
    ├── 023b81d1c254525d7a6129f5f0162d13a723a62f.nq.gz
    ├── 023c475b2b3d5f9486d98a00bb39d2ad391381c2.nq.gz
    ├── 023cc956d3268814953507272df554a04c94b64f.nq.gz
    ├── 024d5777ca987870880abac254d66d7cb99d2fc9.nq.gz
    ├── 02523d11afd0c15f753082fc8ea606246f0167d6.nq.gz
    ├── 027e0280f8f95628d18c31d3ae7804582ba72f11.nq.gz
    ├── 0285f916ae72b6b94f417828fba1eba68deffae7.nq.gz
    ├── 0289478be3073a717a5f31809e8cf3af164fd2ef.nq.gz
    ├── 02a36cbcfcb43f20a05eec7149bc0878cbc34d03.nq.gz
    ├── 02a38ac2631d409f52a79bda18640c9d34626361.nq.gz
    ├── 02a662016d2257d2ba3410b7af8d3f2447fa8acd.nq.gz
    ├── 02b19ee2b820fa26f2ad0a4fc3c763a1e178e841.nq.gz
    ├── 02b203ef35f4231168311e15cf5edfc5f717beaa.nq.gz
    ├── 02b75b6286b7d7a2faf06eaad9d79c92282a5ad7.nq.gz
    ├── 02b7c16634b753e0d34cbf3c22debcd1aae18320.nq.gz
    ├── 02ca3754ae269baf3882a450e5860d5a3d488da1.nq.gz
    ├── 02cd99388ec738ecee771392395404ac591530ec.nq.gz
    ├── 02d797bb2abaa9fdf4f872fadac1fd92a8f363a7.nq.gz
    ├── 02d9180a53fd2a7fb1a3d924f6ecf3a6f43faa30.nq.gz
    ├── 02df09cac93ffe1cd462e183858b57c762d7f41e.nq.gz
    ├── 02e19607e3260b6bf7e60ab3fc687d5260f56c66.nq.gz
    ├── 02e4c59813d0e36f1b12cc425b3ce6aa5ccc9f7d.nq.gz
    ├── 02ec10bb2f2869806475440aaf27d7a7985c222f.nq.gz
    ├── 02ef153defd1a870ab8545669c5989ec10c1b7d2.nq.gz
    ├── 02efd5e4672404345a90c98d11987ac19e764698.nq.gz
    ├── 02f1ea6099cdc89219c1d9fb1c42b5c306c38695.nq.gz
    ├── 02f26b685a2f89a9f832292e718919d0b2ef4bd3.nq.gz
    ├── 0304acff755bff71237d09a747ea8ed26958a1a9.nq.gz
    ├── 03065680eb747f041f8bc223617fcbe08b6ebae1.nq.gz
    ├── 031035e624ca70324273d25d9843cab7a366a244.nq.gz
    ├── 0319f585011270e7329439874b7001520c742c66.nq.gz
    ├── 0337cb1a449748dcee05462c46f4a6efe1a78720.nq.gz
    ├── 035160d483e584c11ccab0641367b6affa6b60f1.nq.gz
    ├── 035623289b76bb7f00643adf650c1cbe344bdaf5.nq.gz
    ├── 0366621e272f69195865dc4649246e1e9f5d545b.nq.gz
    ├── 037c3c2f3d9bb01431804706c678135dbfb71bff.nq.gz
    ├── 037ccf4cffb9a0d8164f004e068fcd0c978b7b20.nq.gz
    ├── 0382870b900e88ccee8d316ff74103147ee59135.nq.gz
    ├── 0383bea654194f119c9e74db517b9699cbb95edd.nq.gz
    ├── 0393e203b536e246bf3347991e6744b5ded9178d.nq.gz
    ├── 03942bad0799fe2e8493c77961302ff210de5f61.nq.gz
    ├── 039469ae9c34f81a308124a11f79a0f641d680a0.nq.gz
    ├── 0394ba971bb072137aafddc1432f3b37e6f75865.nq.gz
    ├── 03b7da7273b29dba93f80f87baa5d20456eba6f6.nq.gz
    ├── 03b8fed6bf4437dd3b98d49e5403f19feb079ad0.nq.gz
    ├── 03c29c3d7b45f97d0eda1f36f512dbc4dcea6d63.nq.gz
    ├── 03c667dc7c40847b914d56e87cfefb11fdae62ce.nq.gz
    ├── 03da7dc17eda9b1962aff9177145f2bf0b2ce14f.nq.gz
    ├── 03eaec78c8498b0afd008ddaf940db9635dbfbb0.nq.gz
    ├── 03f19b1f840b9c2e33f708c290c330741e5f9e9c.nq.gz
    ├── 03f27a96ad0fe724845da2aa46297cd43e342a6a.nq.gz
    ├── 03ffa082d9474f9625f3a01838384bfe67e582b5.nq.gz
    ├── 0402152ce0732ba5efe78ae545ddbe26e5857e5a.nq.gz
    ├── 0408261931ddfb72daeef78e4f6676ee74380e76.nq.gz
    ├── 0411a6e11a44b085dfa0d11e277cac4012fc1c45.nq.gz
    ├── 042638c7ebb2a00216fc30fdec1e89b4839a0238.nq.gz
    ├── 0426f3790f56a93e21eca07e932fd4d611f25fe7.nq.gz
    ├── 0449eaa8a653e6478e253a9a83c5d98f5ba708b1.nq.gz
    ├── 0451f3af2d22b106bf5286198266a246d65b4db1.nq.gz
    ├── 045c1ce702fc6e17fd45f542ab581773f374719f.nq.gz
    ├── 045dd1ace184b988bfd086535d73ccfabaf6cbb6.nq.gz
    ├── 04756f5d97f9830d4978b1f96b00f9e16b1e81ea.nq.gz
    ├── 0479f544beb46d8eea143eb6356dd52b47cd524f.nq.gz
    ├── 047eeabe576c32c3ccc31545afe3e9e7ba736f05.nq.gz
    ├── 047f02a6189597e4cdf8e1b00ba09255ce021fa7.nq.gz
    ├── 0482b12f732336cc38bd69964add77147f5d1d69.nq.gz
    ├── 048789e0d62412fc1832f7eec07b488ff8715150.nq.gz
    ├── 0492149b5ba2f8434654821aee64683ffd98deec.nq.gz
    ├── 04967c2fb36744e65468d72e1348e71c53dfba9f.nq.gz
    ├── 04aa26ee3d2d187db75176334640f15c925f48eb.nq.gz
    ├── 04b08db87937c6a895f78ca12f881a377df98a85.nq.gz
    ├── 04cca00192467c0fbfd3601ccda492dbf18db71e.nq.gz
    ├── 04d46f86078f0bf5f07fcaa90b754a4733c1fcd7.nq.gz
    ├── 04d9abff9e775baebcfc1623be4151250e08e975.nq.gz
    ├── 04d9fae63e7fd29fa94848905da312237216a01b.nq.gz
    ├── 04da41dc99003b9ab4d2f0f466a703c2108e9a37.nq.gz
    ├── 04dd48db6c390d586397c71750e63a8bea829101.nq.gz
    ├── 04e609ad26553860ddd2324f05f875b4bdf86c91.nq.gz
    ├── 04e7203447f71dd6f5cbf6dec8084b99e0638784.nq.gz
    ├── 04e77e777bb15e27f7e338eaf5ba48b7ff16efcd.nq.gz
    ├── 04e93e76d414fcfcace538fcc618dd4d84c7e217.nq.gz
    ├── 050347b40df6721f64080d037b85d431edc5e239.nq.gz
    ├── 051be7b4f4d159c34aa24743c474b8581ac8fe65.nq.gz
    ├── 051f30e2e86de1a4b4248bbad732439b84d3ddd0.nq.gz
    ├── 053273934c0164844c88e7b52bd620982bf25e6b.nq.gz
    ├── 0534aec12667b2b5ec4c6e2a23cddf0f82043e0c.nq.gz
    ├── 054d0e13606ed3ec094dcaea8820576d0428591f.nq.gz
    ├── 05518ea48fe90f5295d2a0d76f261e17ff611fa4.nq.gz
    ├── 0560d9c0a4d355add786a9b059854f329e30e03c.nq.gz
    ├── 0561c3fd3736bf286bae438cc015ecafcc42d5c6.nq.gz
    ├── 0568033c7f5b60fb5c615409f2471e8b7b417ad7.nq.gz
    ├── 056c422509ca9fac3b4ac8ac5df2a57bb9ba6455.nq.gz
    ├── 0575a48008bffa6d112f8592acdbc707a9d5a426.nq.gz
    ├── 058eea6bdaae0d4b73a7ecba46aa5151900568c1.nq.gz
    ├── 05907845163eac9bdb69245a84bf96d8eb520d4c.nq.gz
    ├── 059aa966f758926123840f85ef9d4e26ed4603bf.nq.gz
    ├── 059e2e2483e4efbc4f0fed38846d7a874cfbe94f.nq.gz
    ├── 059e98235ab2bf2dcb454aa3c27949637bb693e9.nq.gz
    ├── 05a89ab546b93adb613b7fa4847d56c93b4be191.nq.gz
    ├── 05b06762b9d8e05de045f9d19715b97febb67bd5.nq.gz
    ├── 05b2e8f7b0acdae7b55f09f2a6b63582f52722b2.nq.gz
    ├── 05bc2e9b9724be39f626e0657f3cc0ec6f00acbe.nq.gz
    ├── 05c7c2cd6187d489782587c51326c82f71ab5055.nq.gz
    ├── 05d594015029d10bb78a8239227772f1e1d0618a.nq.gz
    ├── 05dbc2bb99a1c733e5b165def2d670932191bc7a.nq.gz
    ├── 05dcc677cb81f75cd7324c6cd46716fb4ee1ad0f.nq.gz
    ├── 05dee3a4cdfa58215859dc16c63b13341037337f.nq.gz
    ├── 05ecbadbe682ec01d6ffa15b99d3e82af7f80887.nq.gz
    ├── 05f177c59d2fa8b4828adab7bd2190de12305f9e.nq.gz
    ├── 05f68725e4e50924d5b5e37e6c5227e043620840.nq.gz
    ├── 060dd5ce89c8fe97b2d97a6447999ad52d333d3c.nq.gz
    ├── 06105cd3c375327ad0f029b47e6e54596a20e264.nq.gz
    ├── 06212b2f5caf633f7179a615f432bf3c7c19ecf7.nq.gz
    ├── 062748be2ca7d36ed2be17552428312148c30d4a.nq.gz
    ├── 0628b0c3fa70fc87446a7b414c7366a491fbfd24.nq.gz
    ├── 06326db15b4131d0f1491e234715236c0e89c9f5.nq.gz
    ├── 063f1d620fac434d5e49362b802e2ac1865a1c8c.nq.gz
    ├── 064add5fbe4cb984674180633dc284b11c6cf801.nq.gz
    ├── 0654d99a43c271cef2d0f2396c68e46439c39021.nq.gz
    ├── 0674c5e4cdf871664db336618e8b6ddbffc79931.nq.gz
    ├── 068dfa172e769dfa304415f3f2308c03c35cee9e.nq.gz
    ├── 0694a1fe0d001afd45087ee73384766e1658cc6b.nq.gz
    ├── 069a4e2e03ab5b893a75ca029bc3f2c2951203e2.nq.gz
    ├── 06a46d71077087cae826216fcae36ac7b298473e.nq.gz
    ├── 06a61e2bc74ca968b0ab03299fc4aa38ef4c53ed.nq.gz
    ├── 06a9f1a180e8c15e807131c8e6670694d42999d9.nq.gz
    ├── 06a9f85ea00492c4012b2e9a009708163c48db38.nq.gz
    ├── 06c39bed10617658cc51b296e1993eb4c4927cf6.nq.gz
    ├── 06d66e72f00702c8d3ae0b5ec0bc1accc293a24d.nq.gz
    ├── 06db29575bf2c89328e742c66e940f74ac41399c.nq.gz
    ├── 06df69671e14205b093f9509deb95a75a94b06a4.nq.gz
    ├── 06e6c25e3075ddcf3a55022431eb31ef7983329f.nq.gz
    ├── 06f4a7adacf893f6f826ad2ca57e59c933390bb8.nq.gz
    ├── 06f6b19c3477392afccf8c00ca16233f1df1e630.nq.gz
    └── 0718a8e61672caee8523ffbb84291eb177410a44.nq.gz

8 directories, 200 files
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

[facebook/jest](https://github.com/facebook/jest)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
