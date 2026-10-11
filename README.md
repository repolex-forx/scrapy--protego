# Repolex Knowledge Graph of scrapy/protego

RDF knowledge graph data for [scrapy/protego](https://github.com/scrapy/protego), parsed by [repolex](https://repolex.ai).

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
rlex download scrapy/protego
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 53d6df88ea74a29561d4c415d45ee77ddc86c1af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 53d6df88ea74a29561d4c415d45ee77ddc86c1af
│           └── chunk-001.nq.gz
└── blob
    ├── 00002d25a5c5f62df304730bee8cce552a6e9689.nq.gz
    ├── 005704683a23dd2f5f2807057b7b650d47bade54.nq.gz
    ├── 00ba9d2ab3d360008449bdd0ec64854998356a02.nq.gz
    ├── 00be36a7e5b399d97ae34c59a181476fc18304db.nq.gz
    ├── 00f7cd4966e600082bb8dcb8d2086a5c90d2f082.nq.gz
    ├── 0179a4586c0b9f546252a5eff2289e9db2b86acd.nq.gz
    ├── 0257133a0bc7b2d6175dd9f21073febee9001796.nq.gz
    ├── 03d84b8514c0e07290c85db3843716b987e52a2f.nq.gz
    ├── 042191e54dbac52bb1aefd5d0e23a951d7f398b2.nq.gz
    ├── 05310b6dfd94dc7eae3367715fad97baeaa39e21.nq.gz
    ├── 0740d263cc15d517583f04b39beecbd42d2e53c1.nq.gz
    ├── 07493cb45f7ddf69997c1a4e71badc6f70e15069.nq.gz
    ├── 08c33814352f9c4c82a3adfde8474afdaa1db8c0.nq.gz
    ├── 08ff08f7d2f84763a6dbba5ab22d47cf8d32fea5.nq.gz
    ├── 0a4386c3f921d6c57bd44873842adf9e1d4c3ce7.nq.gz
    ├── 0a8b39090fce38f94a66b62365bd1026e5b9fb68.nq.gz
    ├── 0ad279c73692eed60c7ecc269726c10f3327fd0c.nq.gz
    ├── 0b060983969fa32fd75df3a0bb9d972c8dd14f9d.nq.gz
    ├── 0b286db06dd9f4992b495d06816ba6ead92c9fce.nq.gz
    ├── 0b3393e814cb52ed0ebbafa253bdbae2bbb4935c.nq.gz
    ├── 0b668f76874e4d47d598c1eb73ca8caf7c09d62d.nq.gz
    ├── 0b6c1663e277ffad0d6f0479c29c9bfa95efa5fd.nq.gz
    ├── 0baca26c2cd3773d7462c53f94ef1c1c8f16303c.nq.gz
    ├── 0d8c0641490f70f2fd10aecc97793ccd757d6f81.nq.gz
    ├── 0f1fd8a5a6d2f69b3aad227e537ac582bd1132a6.nq.gz
    ├── 1036d919cac2d4b6d12b0bcdb63d2b82d0da5b73.nq.gz
    ├── 10e9999078553f052447cc6ba54d12e7cebb7ce9.nq.gz
    ├── 1126e627b1fd0f5d015d4a21da3009b25df8078f.nq.gz
    ├── 11650b211f8fa5402e00cd706a1ad98d7631c65e.nq.gz
    ├── 125c34b6d96da2b9e2b590b7f44f6436345ed599.nq.gz
    ├── 13483a81ce23c2736864d70d009072e00a72e521.nq.gz
    ├── 13acd12328519fbabd72144b63a694332f66c490.nq.gz
    ├── 14064a2fcfb00efefc9266204fee3c5604412a5f.nq.gz
    ├── 15286b65403f1619f7a5facaf2fdeecec22e3218.nq.gz
    ├── 15b6112b38201ba8dcd2ade0ddcd0e6172d98973.nq.gz
    ├── 17fd89b5b8bbecf68983316c5c0920b470564bc3.nq.gz
    ├── 180b0873067a2fa51a40c26541ba2af3bbf6933f.nq.gz
    ├── 18369ce5577c6cb0d903d07e1e1f83d55b6bd745.nq.gz
    ├── 188360a026062fcb16e2048875d2f6759316634b.nq.gz
    ├── 189f8838b4f72b03b5e14b2135d8a749836f7538.nq.gz
    ├── 18f3b2182e806ae6402915dc170a3a448f2321bc.nq.gz
    ├── 1977a6eb798b968af18e98eac0e175d12ac9e322.nq.gz
    ├── 19ac3ff121fcfe6e61c38c0dc48e19f9795cab0b.nq.gz
    ├── 19fb0e6611f8feab714015f207901aee977a6a7d.nq.gz
    ├── 1a8a486ccb445d14fa7a70760e2ec708e25eeb3e.nq.gz
    ├── 1ac287550433b8d8a804ce7f1b98d3a99207f20b.nq.gz
    ├── 1ae06772a1643cca38be6d50d3419ee35ed3a978.nq.gz
    ├── 1bbbb6271995a7f312459eaa014f24db52b3c8ec.nq.gz
    ├── 1bcc7183096b1175693dda0e4ef34062354ebee7.nq.gz
    ├── 1bd0971f2e7cf20ed080826eea904adf0241ad70.nq.gz
    ├── 1be875584d90503d27cfe42cc06c90be432f65fe.nq.gz
    ├── 1c8951d773c6acca19cee796b25ede53fe995971.nq.gz
    ├── 1edf1663fe92555ac117e26bae01d00b1bcde1e5.nq.gz
    ├── 1f42f7e7a1646634e9c0e5b0ec6177cfe39fcf8f.nq.gz
    ├── 1f53798bb4fe33c86020be7f10c44f29486fd190.nq.gz
    ├── 1f5a3956b6d63c3e407de432c1c7511e0b5cedc1.nq.gz
    ├── 20275c63c1adf91db01bdc0bd0bef8e2bdfade54.nq.gz
    ├── 20fc6e504d1cbb1f34c94d29bc9ba8dfdd7a84cf.nq.gz
    ├── 219d9f4ae950063a4071e4a857c47ca03a2f572a.nq.gz
    ├── 21a5ab788d878c9754e27d615ec52f385eeab4ba.nq.gz
    ├── 2268a073f0ec0b9db940b339cfd406b3ab752cc9.nq.gz
    ├── 2452f5e9c7f63212cb53eecea896fb43bb8e3bce.nq.gz
    ├── 263c19dc22811cd987593544821094acf314cac8.nq.gz
    ├── 2654fd23cc739f91f0f1392f96c352b6214868a6.nq.gz
    ├── 26b4d70f481e1b44f70039e344290419d139add0.nq.gz
    ├── 26bd28a222b64f3e415b5d45f1aa3a1034308e7e.nq.gz
    ├── 274d4740e9a1d4d18056611d2cf726a8378dbbd8.nq.gz
    ├── 2789e202b055778d29019d219370a7485390eb6e.nq.gz
    ├── 282dc99b06a4c484f9611cd6b1f9af9f1dc460cf.nq.gz
    ├── 2943f36d787a27182d112b426c8940d602de9385.nq.gz
    ├── 297e0709279e3186f924dad927ea30072416e058.nq.gz
    ├── 2a877e1ee04da4189c56b354c0355e60323e0adc.nq.gz
    ├── 2ab52e68bb232aac145729a6086dcdebe4d8cdd8.nq.gz
    ├── 2b1829965682b5c063cc564602f03a986d264bc0.nq.gz
    ├── 2b6e275f1f8305b8d53bab35ca497925562a3ecb.nq.gz
    ├── 2bb691a19e24780977e8d118fd226b4e021e4544.nq.gz
    ├── 2c26d6a39c52bbd77b00a29e3ed9de0c99afc131.nq.gz
    ├── 2ca6aa1cac71151a77a1a90d23d0550a5da24717.nq.gz
    ├── 2cad84e2e292f5219651dd567e29c1e7a9a94820.nq.gz
    ├── 2ce13a892d5fc9330f2ca10a2b4a48b8fb155868.nq.gz
    ├── 2d4ac332ce6b1b98751fc2663da16ff52b83a5c8.nq.gz
    ├── 2d58ae10d8492552d93d31f07086d1befa8e274b.nq.gz
    ├── 2d60c7d9882eb1ea6bb1789f5eceb5360f92ba45.nq.gz
    ├── 2e9c46ab3e45026e9ec47f7c497fe4a31b5629e7.nq.gz
    ├── 2f152aa7c5979e325dd8c74671a3fcaed6adc49c.nq.gz
    ├── 2fd0c99f39f962467d70b872183b3f1d56a9ce96.nq.gz
    ├── 308dc3f7e5448f4e3bea337cf4275ab3d227a435.nq.gz
    ├── 317c2905d7cc7918a7d03d8ffcc77210835eb0aa.nq.gz
    ├── 31b994c773ae8f94bc9fe48cd8fed45e416d0f4e.nq.gz
    ├── 32bceda44ae3ca3a6837584635e6a6c0f9039a41.nq.gz
    ├── 32e3cec8f55159bea865dff0212810fb2933b1f3.nq.gz
    ├── 33786bf6c4d1842d86c32eb1cf54bcf0d52adfce.nq.gz
    ├── 33cebda358b9ca2e20489c0d7b57586e1f849766.nq.gz
    ├── 33e36873644b71d0aae83f3392084cc7927a44bb.nq.gz
    ├── 346ed96ae5a2c249f8c4d1fa605351b86e23f7cb.nq.gz
    ├── 3497aef5855e29aa26f5078508b4b864d9257769.nq.gz
    ├── 34b3507da25cc982f5127b265dafc38cdb6d0d93.nq.gz
    ├── 3525d0683be63cdb9a3c90194ae509bd39c3b646.nq.gz
    ├── 38e7779a42144dbfd029f39e875514ef3bb2d569.nq.gz
    ├── 39509b2a82dd8e387cdb6aac98065551e060f0e6.nq.gz
    ├── 3a233a1318306de321dffc5886e20d86e252a654.nq.gz
    ├── 3a71760c9f2b409f2cb11cde35ffb297ce5d4b4f.nq.gz
    ├── 3aafa61fc28579d150c02c5c95c9a0c85d7d10db.nq.gz
    ├── 3add48fba2d163d9bc37a7e0e684783f5d097db6.nq.gz
    ├── 3c4c104819c05f8539e424773fa8c2f4531f9036.nq.gz
    ├── 3c661a40b7c6908daca4b1c8b090b9fb4f0bfcfc.nq.gz
    ├── 3c9c7c01f30b90e009de2d15952ae83230f8e37a.nq.gz
    ├── 3d060573646b8138dea8bfa729aba5099c0cb144.nq.gz
    ├── 3d6000237f861c94e2b848d95a2f1ab24d598cf8.nq.gz
    ├── 3db39cbe5cd9398987e5bc7ccfbe0efa93780eb0.nq.gz
    ├── 3db4a53a9b34f61424ccda9cc09c1e5627d44f20.nq.gz
    ├── 3ec8b11a30ebc41852624733a95cd5b08639590e.nq.gz
    ├── 3f6a87bbe2219f8df6060b58c39864cca4f199ed.nq.gz
    ├── 3f873407e9f605aafb28fb6af39cc63e96a400af.nq.gz
    ├── 40c4c60afd7744bcd802516c3d50608440aba6a3.nq.gz
    ├── 40e79e0f0277d41af87fe875af8dbe84c231a2e5.nq.gz
    ├── 411e231a4c094670db717123816038d1f474dd3a.nq.gz
    ├── 41249473dae3a9cb2ea5e41d3ffa47ee385bcb92.nq.gz
    ├── 41a2fdbf5e2c43b692560bb708d33c5b90ac0101.nq.gz
    ├── 41bd157ecbd11395b31a9956923b5f4abe930013.nq.gz
    ├── 41d1a2c207e7563def103b9d8ffc0b2fe1a6ef9d.nq.gz
    ├── 41fc7e1537e3405c68ac526ca33d0a344dd61648.nq.gz
    ├── 420a71ffece536721289e8aebf0ef3aafb82f7da.nq.gz
    ├── 42ed122a4f962a38c59a971b6622027202e0a62a.nq.gz
    ├── 435486849c69942949419e8cb378476c8a98a449.nq.gz
    ├── 435f0176b3e06a9371dffe33c8d2ea077faaa47d.nq.gz
    ├── 43dc1d1d39ec7f190098acabd1b5223f1ffb3785.nq.gz
    ├── 446e5ef9a6ed7f13a87ca5941c0dc999c41da53a.nq.gz
    ├── 4489b2ec667123c78e5abc5ee9b395f503dd2cdf.nq.gz
    ├── 45b8aa7c0c7a7a750f32d5516799d46908b95103.nq.gz
    ├── 45e3d06c3a7dab9a66afef238402c650fe7cef32.nq.gz
    ├── 460036b60c586f82a13c1e532e9bd463e7f5cde3.nq.gz
    ├── 466587231f489a69040a5ffa0aae7bfda7421d62.nq.gz
    ├── 46b2f68eaa4811edb91e708b2048728d4f75a84a.nq.gz
    ├── 47512344362b6594c21373c5ce263c836c46bc95.nq.gz
    ├── 47b427ef45139b1ac84cf36a21f47cca4bac67c1.nq.gz
    ├── 47ffd188b922fee2c05f3ef513b33f934479c7c7.nq.gz
    ├── 4817d3ed39cb31008800947271a2a29593fcb91e.nq.gz
    ├── 481c6686a7e7b632e2ae92345c2d7b535d80d70e.nq.gz
    ├── 4848d5e6700383c211a3d3c365302e6062129a78.nq.gz
    ├── 48e9f70b7d512dc3ef667671d7b92dfc83bba292.nq.gz
    ├── 49ab0d3a854a105cc1adb7d18137850cfe21808f.nq.gz
    ├── 49d2395340ed1b24a1f98688b04ef4653a81447a.nq.gz
    ├── 49f87d7482cac64749d8a458b79f5b759ff01819.nq.gz
    ├── 4a67a8dadc4bf9d4b0cd2332c0cea9c604733e7e.nq.gz
    ├── 4a71ff3cc8cfb39d21e3158e703e47e33dca6052.nq.gz
    ├── 4a989eb9d4c76217ea79a5046515780550df02f3.nq.gz
    ├── 4a9c40d50d32866381796ee575a53bc1b2a29bf3.nq.gz
    ├── 4ab9e89fe1478af95c827e76b8ceb38236decef8.nq.gz
    ├── 4abe405dc2f1d6f2e9dfcfee2ae9fbb827da9d1d.nq.gz
    ├── 4c0c9eb513989abddb12decc19c37ae56272a400.nq.gz
    ├── 4cacddbe64f0c7c939365ffb9fe35fb86c9eb3e4.nq.gz
    ├── 4dbf46b3682a2d06043b5f659c617cc2874a5851.nq.gz
    ├── 4faa173c45572e90c5df56e39163d3f692034d46.nq.gz
    ├── 503a4ccd8ed1c144a6864fa997c4f45c9f1e25af.nq.gz
    ├── 51cea0498f693e111853be03dea6b6937c0acf83.nq.gz
    ├── 53585211636931480350cfa6edf74855b04deb4e.nq.gz
    ├── 53c017f2b0782fc486e90d9a799971e73b2c563e.nq.gz
    ├── 53d2bd5ab0da8666be9254e3daad17d507090e58.nq.gz
    ├── 54da16277ade77495e7b227288c62f7d8abfe9a1.nq.gz
    ├── 554f6c06bc5a8739bdf896be1f1135cf6ae968b6.nq.gz
    ├── 556bbfec6e11ad5f7cc40cdcaafc780c28029f9f.nq.gz
    ├── 55eb14cfe62fbd4aa72c54ebf89a22c64f237ef2.nq.gz
    ├── 5606f83a5a24a9c66327abfd0e1c0df957f8d480.nq.gz
    ├── 567bb0340c1c2c28277ee4940b998816afcbd147.nq.gz
    ├── 57804de49d1be60fb7ba4b7b4eea5b4e942eb647.nq.gz
    ├── 579b679e1fa76fc40bf2335083f7b958bd3b9daa.nq.gz
    ├── 57a2506491e79406e8373af56dc26199b2adf985.nq.gz
    ├── 57a8df79c24469621c35ef58649822c6cf56784f.nq.gz
    ├── 57fc56625b6f862c4b203f286571b78db059237c.nq.gz
    ├── 59164886b348c462bd81c0820fd0c83718109fbd.nq.gz
    ├── 59963cf4df43c68a0eabb3078013e87a48689ba4.nq.gz
    ├── 59d80c6a3510e4c157bf2292352163695c27ec9d.nq.gz
    ├── 5a8aa2641ef0b514ddac7971e33c455ddab13553.nq.gz
    ├── 5a95ae9084a85de3f3fb51e23c06b50176e3c243.nq.gz
    ├── 5ac4add555cc86c3cc7c619e5138dfc427d708b0.nq.gz
    ├── 5afd0619ab0830a0bffad8d0a9304a537300c702.nq.gz
    ├── 5c808309cf332390607baa2906856f348bdea645.nq.gz
    ├── 5cefc58453ddfc3060feeef32453052835ee570d.nq.gz
    ├── 5cf9feccac328f503dd9085eb1a978d111e141a5.nq.gz
    ├── 5de80c5650a1613ff2d41f404fdc87815aa56595.nq.gz
    ├── 5e55dacbc5c2b5d70d71b53cfda080078f91458b.nq.gz
    ├── 5ed08b19a0803f16d8200fdbe17493310b0e1669.nq.gz
    ├── 5f9945cf38367688eb787f8f4f82afd21dbe5946.nq.gz
    ├── 60ca3052843214fc2f3ed70d44c2863e3a203756.nq.gz
    ├── 60db1f228b3a7f7532aa10a0d0908b69c691f69f.nq.gz
    ├── 60de92beb4010c63d2cafd49ecef01db289e3fbe.nq.gz
    ├── 61fcedce4565416f7f411e2fa1e8c413ecbe8526.nq.gz
    ├── 63529ffb01debbca541c39ee8b234da506b1ef74.nq.gz
    ├── 638f73de6639d5d7d9c38a51b7e3f3b33a3f361d.nq.gz
    ├── 63f1525472c9dd7deb3a9b0510b1dd44b8e96eb0.nq.gz
    ├── 649a2b4fe8f8a6c34f42c96d0ba9db8fe6f0f83a.nq.gz
    ├── 64d8b3c8343453cd0e5738fe61fcce5b2c20f549.nq.gz
    ├── 652e2dbd1d6ad4450f455aa5266ec3db07f9b7ba.nq.gz
    ├── 65a5c13f96311c681308a9062de1afe0f81737e9.nq.gz
    ├── 660fcbf1b23f21e6fcd416540eb8b3d531189e9b.nq.gz
    ├── 6622648052a5e8a16f951ad48c485fce0fe71e84.nq.gz
    └── 67732bc4d3c7584f24010b36d35e983d56194348.nq.gz

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

[scrapy/protego](https://github.com/scrapy/protego)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
