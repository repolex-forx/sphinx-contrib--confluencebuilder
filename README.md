# Repolex Knowledge Graph of sphinx-contrib/confluencebuilder

RDF knowledge graph data for [sphinx-contrib/confluencebuilder](https://github.com/sphinx-contrib/confluencebuilder), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/confluencebuilder
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14515276dd10f664e16b56f7681a4f57c8fe4235
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14515276dd10f664e16b56f7681a4f57c8fe4235
│           └── chunk-001.nq.gz
└── blob
    ├── 0093ffd186d3cbbd58a78e4765bcb92041c6e47c.nq.gz
    ├── 00ae3871cadda684ab08f33c9a9567bd31c2d5c9.nq.gz
    ├── 00d6c413f2d6d296a588feb780cd962f2c957841.nq.gz
    ├── 01d435fb99f745b2a6747c9a5d6a013c8f683001.nq.gz
    ├── 029f19005b3b963635ff5e4c4894b9585c655e28.nq.gz
    ├── 02bea8a75d8bbb2a9098913d5acbf219c5cb5d46.nq.gz
    ├── 041d3aed6d2f423413f043046c058e93f9d2ec24.nq.gz
    ├── 04574299b5f72fe5421621ea7d11e295ac5b9bb4.nq.gz
    ├── 04677018659e39efac832beced16bfced2e6ffec.nq.gz
    ├── 05337b480e54f3f2208d47c010f1a4e89a8a49ac.nq.gz
    ├── 058aa5650ce96e62578dd41bd08e0877fa9f2ead.nq.gz
    ├── 064b04b3bfe720570301444db8eb3271ff1570bb.nq.gz
    ├── 0722bdd5f731b43fa7e94fdad755332549a3b152.nq.gz
    ├── 07a3e53c69b53ef2caa32380f868c80663e28229.nq.gz
    ├── 07f10a78736d2b3e36769ee61eaad04a706bb667.nq.gz
    ├── 07ff056264bbd1e80be716488ecdc91b7d2d2b75.nq.gz
    ├── 0a34ee3068dbc57382fbaf366b68c627dc824389.nq.gz
    ├── 0a86473e7e3fef5faf4b60a0cf1c8202808b6083.nq.gz
    ├── 0b5b024132274872c2fe685a490182495ecfac98.nq.gz
    ├── 0b90915f4e18cdedfac22786166c51386d38475b.nq.gz
    ├── 0b95f7de46828e176b6370e9396bb3cdb9bcb09e.nq.gz
    ├── 0bcd3c2416c8fe76f8fe9a45954e2e2e61f3d08b.nq.gz
    ├── 0da58fc6878039d3c83ed2ba3ee57a845dbcbc5f.nq.gz
    ├── 0dd12f2c9e27fff1808c477cb51bbe93d69fcfff.nq.gz
    ├── 0e02184f6a1c53d65105927ee2daaef38d2dce28.nq.gz
    ├── 0e40d1144c2feba35e18d3dfe8379127ee75a0e5.nq.gz
    ├── 0e57a895571fdc7b1fe8fe559fa0136d5de16911.nq.gz
    ├── 0f9d7f8d527cc978ad912f98ea66f696a91ecbc8.nq.gz
    ├── 0fdb25c69d952c1000d2b31adcebf3f7a314b21a.nq.gz
    ├── 1035ae685871f31a47325591f17f761774b09d92.nq.gz
    ├── 1061390c5fccd965fb4996cdf276912ec98f98b8.nq.gz
    ├── 1097c9ccfba1eeff773121e5a37f0fbc21e24c9b.nq.gz
    ├── 10c48e05dfc1e739f81cf11e3c5e72970dc4588e.nq.gz
    ├── 1133c9c20afd9befc8ad96da68da2827d41dbb15.nq.gz
    ├── 124a4bdff999e9c2a5c71599556ac88bf4c9ca15.nq.gz
    ├── 126b979bd79e3d038be574bd7bd72dcafb6dbccf.nq.gz
    ├── 12affba6cfd2454f518eaa8e47ee221980975e27.nq.gz
    ├── 12c9889f5f24765aea1fc828c46ad4108c333333.nq.gz
    ├── 131e1ceb76aa4428367b1aec5783cb3921c74e3c.nq.gz
    ├── 141a4419177ad9fc51370b5e4c782dc264318501.nq.gz
    ├── 145038d508c5ff335ff968cfeebbde257b1633b0.nq.gz
    ├── 14785e1ceb78fa35b967463320db131b2ecc3083.nq.gz
    ├── 1479e82ea2eb22a36318cbc22c0a94ac0e763cf1.nq.gz
    ├── 152824cfd5f924a5f1f87743bde1b15289a9ad7e.nq.gz
    ├── 15353985e0cf4a06d04b8753ec9f2166ab4899f4.nq.gz
    ├── 1681218524695b967763c9b053847c97ccb29218.nq.gz
    ├── 16cd0d6bfd8283109a556ac81faab429bbdb312c.nq.gz
    ├── 17cde4ddfb48a42fcd1031aec72c16ef3f3a9f69.nq.gz
    ├── 1888c74a13b67eac5a733eee58c55e26e85ee7c7.nq.gz
    ├── 18d57e70c7cb78e5010cf291202863b31bd389c1.nq.gz
    ├── 19c91fddd302d93e41ae5c31f33ba1e8b7c9c94c.nq.gz
    ├── 1a36216843c94990920c4e663e5087828140d64e.nq.gz
    ├── 1a57a5e0e611c589c9f7408663695f9defa3b9e4.nq.gz
    ├── 1b11f2a8ed838f067528531f718b2e80b04ed4a7.nq.gz
    ├── 1b46bc427694cb4af615bd8b52b9f99d882c5238.nq.gz
    ├── 1bd2f0a43c52ef607c16a81c5eb655221c7ffec9.nq.gz
    ├── 1c8cfcb253bf79c803a1885a85ba1932ce8a65c2.nq.gz
    ├── 1cef368b2d9bf060089d2bda8146f1295dbb8306.nq.gz
    ├── 1d9972444327608ffa9606fa459717143feed4ef.nq.gz
    ├── 1de4c484afe4f04414713cf1d7591994a934ae99.nq.gz
    ├── 1f3406bd6406ba90ad93da62e55b8406101c7e9a.nq.gz
    ├── 1f6962fde60e032d60b39a159b58371d269b6f73.nq.gz
    ├── 1f869b38f02473ea950ac9931c12fdc3a0c8fb9a.nq.gz
    ├── 1feb69c9372f23d3881bc7541348356da5a62617.nq.gz
    ├── 205cdae5a8a03dbb93d94d311e997895f9505b59.nq.gz
    ├── 20937346d1b9e7864e2d3b7c455baf7a6afe449d.nq.gz
    ├── 20d5925c631d90843683da8a45f892f7688853c3.nq.gz
    ├── 211202ef52bc4651bbc742c4436875dca53c4164.nq.gz
    ├── 2258c83cf5d833a633371a3f356c83d7a5068997.nq.gz
    ├── 22c4e4ad9d484f28c9d403c0e62aa3052fc0b049.nq.gz
    ├── 23659de3bc9ef6a79a79af160ee41b288b1320e7.nq.gz
    ├── 23a9ac4f836d34ee546433cdc2e6e0e62decf2c0.nq.gz
    ├── 24e643492400e0699c65b5d816ec614bcce2ddbf.nq.gz
    ├── 272877adfaa46d46245ce25348ff4db6c31afd8c.nq.gz
    ├── 27a971383c23be89aafc2931559c2cb1484b0128.nq.gz
    ├── 281cb4484817f718634dba09be1f51649c154b2c.nq.gz
    ├── 2821e9afd8d88246df985c8392f82a4d63c10773.nq.gz
    ├── 29b4532f1fc710a9e3b3cbae59d460eb461b1844.nq.gz
    ├── 29e544a7fb6f6636dfbc5b2bfa03a8addeafb4da.nq.gz
    ├── 2a2d8ac7715441061a7740a0ced59a249a91203e.nq.gz
    ├── 2a4fdfc524097586f002363ea093e7451abd360b.nq.gz
    ├── 2a74b5b8a082a3a648b390927eb83b1336d87567.nq.gz
    ├── 2ab2845296f65819c67db69cd18e894d2f746f12.nq.gz
    ├── 2ab36034569f2a511b5b8e3a1902b777e372d8f0.nq.gz
    ├── 2ca63d57ef29c52126fc61cb46f5aa9bd274ff7c.nq.gz
    ├── 2ca6834d9f587b5240fe5ac1ece6674a74ca8724.nq.gz
    ├── 2ccc83f0d9defa53bb9fe17cde3c7d60abb444ad.nq.gz
    ├── 2ce38ff42b2f7d83849ac16be482cb55e8539e6f.nq.gz
    ├── 2d5b17c603cde68dfed8501507e7e35f4d4d950c.nq.gz
    ├── 2e553021e13ac44311a084cbc8abaaa8f5fdbe53.nq.gz
    ├── 2ed1247299ba4278510a4431bbb4e30c27540210.nq.gz
    ├── 2f2cc1cdadf4d8264b4875336e497890c1b85941.nq.gz
    ├── 30031888b242c8a5b9395cb5a94040492c4bc31d.nq.gz
    ├── 30bbfb5c2672a255d01c2586199b922e7a436f0b.nq.gz
    ├── 30eceada07f34a6774740c73bc923a6837c9c5da.nq.gz
    ├── 319abf86bbec546ae900aaeb0216d70584441336.nq.gz
    ├── 324dcb228b6c6a15222c2ddbd0af30df6d414e76.nq.gz
    ├── 3452885010f40daef52494540d95d86fffcd9f62.nq.gz
    ├── 34bb4dff162b7d066861492fd418596793ff6d2a.nq.gz
    ├── 34f59f72270a9a3992eb5e8c5f51aff4833f4961.nq.gz
    ├── 3631532dbfbf2bdc4fe2d337e0f2eb13ecc03dae.nq.gz
    ├── 366f52f33932994b8056d5c9f5f507d9c97b1152.nq.gz
    ├── 376b6d43fc1e5e55680fe5bcea40eb294004866f.nq.gz
    ├── 3791077cc6d3793f5e0139b79180da29335806df.nq.gz
    ├── 38238f3c2c785447b219eaaac05c50151b6abbf5.nq.gz
    ├── 38651918d2a0a6aafca4e233f28e48a573e1993a.nq.gz
    ├── 388064581081398e8da032409fe04d8fbf6d456b.nq.gz
    ├── 38ab119e3e6f6f39c1e89c1725a9a52c34d155df.nq.gz
    ├── 38eaa2f5b91a8add28540ba2286779fe6d20d54f.nq.gz
    ├── 3921c2ed4634630f414986d665970cb6edf251fc.nq.gz
    ├── 3938bbd79dff1835874680b0429b91b768aff8c5.nq.gz
    ├── 3950f2febed2ba7ea5f3a0aa52e7e13da97faf81.nq.gz
    ├── 39649c41bd4b76ba526906180210ef6ee9f990c0.nq.gz
    ├── 39ebace64e054e5e2bac7dede9486ec60981c259.nq.gz
    ├── 3a8f4d2e0c337393c399ad1899aa552bfec98532.nq.gz
    ├── 3b2071fd221321cc2b3655cb86b4d5f70acf652f.nq.gz
    ├── 3c36e97d6e82c8386b6b0a5d31986c40c1e9d80c.nq.gz
    ├── 3eb92306cf3c7b1b32a819358115f2868554b07f.nq.gz
    ├── 3f93e7da3f652a945d65dcca119a1352b5c976aa.nq.gz
    ├── 3fbb5778520ec0bf2f7ca16a4610e1c121bc0b81.nq.gz
    ├── 3fdf6db82afe0b4ed6dffd3c3b7f1d8d9c79e595.nq.gz
    ├── 3fe31ebe994a782e5dce5c55fcc610118f91050f.nq.gz
    ├── 4015ae8ce2d07e3e71a1c9b5206cf7b19efc02fb.nq.gz
    ├── 403d40233a8416f8a01ef144462361a84ed6fe4d.nq.gz
    ├── 4086966aeb7f1a1434c7b1b66f8c9192568696f0.nq.gz
    ├── 4095cfd54b4cc10a0b1dbbdece5b2ad250fa6ab8.nq.gz
    ├── 40e722163603060b06b2ac455a27d8dae660f825.nq.gz
    ├── 410480762070faf4cd820ba876c75a2eb982cf45.nq.gz
    ├── 414262faf79f409a0edd029e425043875a0c4998.nq.gz
    ├── 418a7378cf9dda0744299d94baf8a88d0b578e43.nq.gz
    ├── 41c57743f8ac29f5958b262e7734ad07e1bc089b.nq.gz
    ├── 41c74dddfff5660927fc47b6ea4491e1edb5ccb0.nq.gz
    ├── 42b8a2c5e55035789b3a5d3f93940ca72fb99293.nq.gz
    ├── 42e6ec3d43916d3710b6426eb516e30d85aa6769.nq.gz
    ├── 430b75a3db2b340333bf81774a2914257f757edf.nq.gz
    ├── 4353af6483dc8007a1ed653cb118c2c78e422c56.nq.gz
    ├── 437faf7c0d82c8e3e589e3d4543ae567ec944004.nq.gz
    ├── 4557776e91fc49a2eb99270bf7828c0b8cc0603e.nq.gz
    ├── 463d9fb6d3ade9ded7603e022b1e0430f3aad340.nq.gz
    ├── 466b16a73195862d7a7a12599283c261f5589611.nq.gz
    ├── 46fe1f4bd628ea9616d938f657f8a687f20961e7.nq.gz
    ├── 47606f63caf6a31893fe8b1f82bf7000c6c4c715.nq.gz
    ├── 47f746851ae229a8465d4f9672cdf05a08e0baae.nq.gz
    ├── 48cd2e4c551efcbdb2ab88c942d29ac5fbc5b31a.nq.gz
    ├── 49829a4ef2432370bbfe7ede87910decda677c37.nq.gz
    ├── 4a54d5457eb5af686eff7012153d02db03c234d8.nq.gz
    ├── 4b2c160f7470bb4b2c72d1ea1bb7adc3382255c5.nq.gz
    ├── 4bf9856feef300275d2539882ac2cce1081a82d3.nq.gz
    ├── 4c49df5fa788013b3ae9f0b8dbe8876359495320.nq.gz
    ├── 4d2c7535092807d1acc80c0d2b94b759ba1a6283.nq.gz
    ├── 4d41d199afbe9d52ca95ab5aa15288400b1610ee.nq.gz
    ├── 4e05e6f6674476beffc35ed71a1a939eb0bf13db.nq.gz
    ├── 4e9312c7c3b61aa1389c69c1935797445f57bbf7.nq.gz
    ├── 4eee5734bca2cd2b6d7917fa4c095f9a1fdff18c.nq.gz
    ├── 4f8349448ae4d73557cb1cd35ea971838646ba3c.nq.gz
    ├── 5092f3c54f20291bf4028dbcc71d3b3086b708bb.nq.gz
    ├── 50e25427809361c265662a8a1209366e0ebaa38f.nq.gz
    ├── 50f23e4b9bb78cedea0a0d20f9a28cf0823661de.nq.gz
    ├── 5133a65fe321c794e6f5dc76a3e740338882c516.nq.gz
    ├── 51b45061f9640e901dae670ca502c53c2ac86ca9.nq.gz
    ├── 51d73eab7ae91969b8122a6a2608b128f2961900.nq.gz
    ├── 51e3d21e7b553ed9fa7db677668b6241e9d1fdc5.nq.gz
    ├── 52b6825707f690024233086307f9a54a2d847096.nq.gz
    ├── 52d42a96131eef99a67b34c794fe7ce7733ffe04.nq.gz
    ├── 5352cbb55df7a9d6f728497ad1946de75db0c753.nq.gz
    ├── 539a71e75d3092c91dc300dd83aa023bbb98f041.nq.gz
    ├── 53b3e7462278bb6edba9e29eca08397a6825c932.nq.gz
    ├── 544aa664614377a90fb4ea83bae3451c27a0d12f.nq.gz
    ├── 5479d92e817d6c0b925b1080b33eafa6c8d1e8d7.nq.gz
    ├── 54b2e2785cbd6a958772e80e994ab529a0c7a152.nq.gz
    ├── 54e6e9dd1904b3a1891901b23bee589f8b356fca.nq.gz
    ├── 54efbee778e8d83239c64ed442624a7d3b03a9ad.nq.gz
    ├── 57509fed081673edf13d1d8892d11560cd096ae1.nq.gz
    ├── 5797790876f08772254ba95345c35be5ea8dbb4a.nq.gz
    ├── 5803729a2d6a5f64218b5f6e68183967c3154dfc.nq.gz
    ├── 58097abe3f356212b063acce42597078a4b0c43d.nq.gz
    ├── 585e7c3a7080016214bceb0b2a7bc166a928d111.nq.gz
    ├── 587ebe15804b7d0d1cc55c508b795146c0280afa.nq.gz
    ├── 58f6eed34c209e6de59f24e7d1841c3179f7e6a7.nq.gz
    ├── 5965e0733d9701d221e2c97dceb562e109a7d14e.nq.gz
    ├── 597d187f90bcf7347f99859fbc0a5ac4c6fbd285.nq.gz
    ├── 5aacf489e2e4b1abef1a61eb27969c94d3f502f4.nq.gz
    ├── 5ac8635ccf7a088650dbd6c9e2e82518fb8810d7.nq.gz
    ├── 5ba87cb54d849d8d2743fccf1d8c8ac70a8436c6.nq.gz
    ├── 5c2ccf28843b9d15cb702f0f0c06dbae9c83dd04.nq.gz
    ├── 5c83828345387652e44c07a91bc7caa7ed28406f.nq.gz
    ├── 5d43f81c633721f5e50db2b43b86550e1f591208.nq.gz
    ├── 5e31cec1ed95f17fbffd50f7d10761036622c2a6.nq.gz
    ├── 5e3d5d4e01e6378105cd6f4ef266a863d2b940a3.nq.gz
    ├── 60251ba0d58b0fa278ba8bd77ebb248fd3da8dba.nq.gz
    ├── 60aeb22232f6194eadca7cd5ddb9d5f3f05fe582.nq.gz
    ├── 629ab08547a5a99118aac0272b61937313bde688.nq.gz
    ├── 62cdc85d4ae5229393800189d0fe3024cd24e261.nq.gz
    ├── 632764a7f613ef61c021db7350aa3cb84901552f.nq.gz
    ├── 63a983b92099a63ef3c350efcc60580fa58471c2.nq.gz
    ├── 64106de7a64b03bed57cd0cb4a5868bff3889490.nq.gz
    ├── 645437bbfa74a52610738b3e8ca915fdc2a52c17.nq.gz
    └── 645e35415985fe9cf4d1d9321e5bf18117d7ae6e.nq.gz

7 directories, 200 files
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

[sphinx-contrib/confluencebuilder](https://github.com/sphinx-contrib/confluencebuilder)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
