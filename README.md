# Repolex Knowledge Graph of pydantic/perses-shared

RDF knowledge graph data for [pydantic/perses-shared](https://github.com/pydantic/perses-shared), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/perses-shared
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bcb5f0209ada59d720eb141912aec29dfed17b62
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bcb5f0209ada59d720eb141912aec29dfed17b62
│           └── chunk-001.nq.gz
└── blob
    ├── 007b55658c783f1f03b224e411a9e087c8c52a2d.nq.gz
    ├── 00f5eb88ad595eb9e2f427914a2255ecb2ade925.nq.gz
    ├── 0252b72c6ee68eb5d16ca124d2e0bc6c077463a0.nq.gz
    ├── 02c39e873091c8977ca4d406d1e639e997bab70f.nq.gz
    ├── 0334b733b0c49d0ed6875ec7ab3fda542fae348d.nq.gz
    ├── 042dcb85c780c8b2c17741e27104ed5ed42ac4fe.nq.gz
    ├── 0438142ddcc1938f7f981aabf86cf35da212da00.nq.gz
    ├── 0440678177450fa4454fc9e129e27a5d31e80201.nq.gz
    ├── 04dc621f7835ca9262ddd736c46ee9bb57f1977d.nq.gz
    ├── 06458b625037523051b271b5e68af88b00f766ee.nq.gz
    ├── 070af5af4f97497e0a1e33e0c79b9211a4eae963.nq.gz
    ├── 076af0ee871bbcc5e021902ca8d76fc8369c96ed.nq.gz
    ├── 08058a85a309d3c35b818895c81313157f9ce125.nq.gz
    ├── 08161c4e6c26d0ed20ea27b4dd11ea173030b09c.nq.gz
    ├── 08342c1f071e0a5ee05d415d8c3db343d962fcb1.nq.gz
    ├── 083e69f0519b5795dd5cda0942044c80ad0d6f22.nq.gz
    ├── 084a99fcf06dfbfe0dcd9f28069f32459c8c0bfd.nq.gz
    ├── 08f5f007381094354e550b7a5978bf47a6314df8.nq.gz
    ├── 0918713b53b6272ff5714e7d8862d412a65cbbdd.nq.gz
    ├── 0aa0493cd91d48a6c67281125279138ca4eb7ee8.nq.gz
    ├── 0ae2540f0987ef1a331d2284f9e37abe2d097941.nq.gz
    ├── 0b29d264d0fea81b447d0e3cd72f837678473766.nq.gz
    ├── 0b5817cc629dd8834660cb250c903217f8fbd9fe.nq.gz
    ├── 0cf06eb21dba51bc783d979268ed988a34120a0c.nq.gz
    ├── 0d516b2039293ce0ee76921ee6a85942ff3b3fc8.nq.gz
    ├── 0d65929e60e36828c7a705c05b12a71cef70df76.nq.gz
    ├── 0df7ac1cffe53d52525fcf8986b4b020212a747b.nq.gz
    ├── 0e4134e2bf63a6b4e6db4ae0ca33005ec530780c.nq.gz
    ├── 0eb38cd67dd25be5be8156354dac1e64cac4f4b4.nq.gz
    ├── 0f264a11c908c0ae33e43ac8e931fde76229e60f.nq.gz
    ├── 0f5c83483ad1ee8d6bb87d367479229bceb8db77.nq.gz
    ├── 0f8aac0d5d426ec4165744947ba60f2a301df4f2.nq.gz
    ├── 0fe1891cc0dd5e0ba7ecaa5b8c82d30c1ca642de.nq.gz
    ├── 102c8ca056aa0de390a4bf45947a102bf1d75a15.nq.gz
    ├── 1036bca0fe5e6559c9bb7c1ea9f9effb773db80c.nq.gz
    ├── 1120f5a1a7ce073604b9226a2779603f0bb66765.nq.gz
    ├── 113242ee71522c7e1e1ec0eb59080e343a12beb9.nq.gz
    ├── 11610a78dd731f9efb5ab710b5648df18d2a52d7.nq.gz
    ├── 121d8b2e0a4dafa740de838531777ab2094ebac3.nq.gz
    ├── 13e0cd317ca52d1059342bf9741141bdb513fa67.nq.gz
    ├── 14c82d6cf82f73e743b82b20b3c71840c0103582.nq.gz
    ├── 16697f4f41a4440d27246f7ade8c1a331d60b7a5.nq.gz
    ├── 16aa9b0f95f17828dbbf53803d47824886ca3095.nq.gz
    ├── 16cd78bdfeecafa79a2fd6cf681aac4fcb9e8c3d.nq.gz
    ├── 16db9cd74b643e18af4ad1e0bcbf4b9f0a2984df.nq.gz
    ├── 1727bbb34f1324f073cd534f0afb3ae927019be3.nq.gz
    ├── 17f5ba3b8f6f3a62ff0deaeae881b430ae658a7a.nq.gz
    ├── 1813417575de30becbe27a57b45563f9d0fbfda1.nq.gz
    ├── 18c407b5a41dd38774294beaeb739b9d40e16280.nq.gz
    ├── 18d7854c0f366d4ef4458a6e77d1d16dceaab5f8.nq.gz
    ├── 18f790fb56460d61a6cd4524afd43523a5086526.nq.gz
    ├── 1920003f5a5f66f39612cc76ee439fae39bb3e31.nq.gz
    ├── 1960d1e8a0155ca7300bd7c0e1eac089cac3b08f.nq.gz
    ├── 196e468afe019efcad19a51a3b0d0e2ad2f8a542.nq.gz
    ├── 1a6848834b1c21125d5de9e6c131ef6dc61b6265.nq.gz
    ├── 1b02acb25ae56b2bfcaf49a8040e6a80468dad51.nq.gz
    ├── 1c285e53eafb8d6dbc588b07c6fc8766caacec3d.nq.gz
    ├── 1c3199b3f1b402208335290619ea22e8d891cbdd.nq.gz
    ├── 1c61d8c17362645bdeed1d6bd2fc21f9f08555d8.nq.gz
    ├── 1c851c265206ef5fc1a1af31b0d1a0f6e3c4c607.nq.gz
    ├── 1d3935f993d281d004a739eaa5f8ffd8117ce839.nq.gz
    ├── 1fcc9918e01ed09444db0a43e19b6b83fe97cbe1.nq.gz
    ├── 22a4f49c67d1ed8307ae5eaffb9db491f9113b68.nq.gz
    ├── 22b0a52672e08f05900fd9ee196cc8e15d7049d9.nq.gz
    ├── 22b98454276593208d9cbed18d7245e52f00dfc9.nq.gz
    ├── 2339592625eba9bb036f5a6961463a8f79555dcf.nq.gz
    ├── 23409d32679d303a94123c5c663530821726e4e3.nq.gz
    ├── 24bcdbcfaa112b89f2ae72fe002fa3d4833aea9b.nq.gz
    ├── 24c45fe9e809ea2401f3e4049dbe7fc5214420d5.nq.gz
    ├── 25137606a68fd03851420bd5d11c8417da7cb359.nq.gz
    ├── 2523c2ef267a9a51de26ce0786f86a7a85b3492e.nq.gz
    ├── 26640e31901d142c389ac0e9ab6b4d026ea413b2.nq.gz
    ├── 267a47ded357f9b4e04fea21f8bd9ef86e37b968.nq.gz
    ├── 2844fc33109dc0ffe405cfe4fd8b6424a45fa370.nq.gz
    ├── 298de68a2858296416125fdf8bc573503710baa2.nq.gz
    ├── 29933f293b0b6e17af1477f853594e2447f25386.nq.gz
    ├── 2a013d54d6be26f1d8ed6f635665a61dffe14f44.nq.gz
    ├── 2a23642a5582645a35784c9ca1b033729fe28f1e.nq.gz
    ├── 2a4b109f214265f0f3daccf85df6e55f5fae7279.nq.gz
    ├── 2a80cf5b802c880e94cc0c706333891c3dabdd2f.nq.gz
    ├── 2ab4f502cfb26b8ab64f005f342820fc6f7e2486.nq.gz
    ├── 2ac9aad90fef488378c73dbe4d27dddf231ba82f.nq.gz
    ├── 2bcd73cfc0d554f50ab13650751dec910209408a.nq.gz
    ├── 2c62500cdaf1f6c0388dc641c4ba1db55772c2bf.nq.gz
    ├── 2c7ff1d9c54910007677713ccc9673deff08ab94.nq.gz
    ├── 2cbb519873ed52e9751b37d54b97f5792bcdb9ed.nq.gz
    ├── 2db68a0caacb2a754cce4be2fc34f86fa1042098.nq.gz
    ├── 2e752429fb62b593882ebc11e31b81495a734763.nq.gz
    ├── 2fa68958147d983fed6d30f82f2419c60949de5e.nq.gz
    ├── 30a5db466e500ca517c05045cc2a409ade59abf5.nq.gz
    ├── 312b7e207a146c5bae5637266a9e0d3a17bc4d8f.nq.gz
    ├── 31ddc5f780994d3ba39e3631b2ac34bd84d6ce42.nq.gz
    ├── 328772cc7d204b9d31e0c40cc58e8db2b37ae510.nq.gz
    ├── 334f8f46c52b60fa39bcf90ea52e11484e63a386.nq.gz
    ├── 33d17b31ca8e71230af161e25c6d60938dc9b7f6.nq.gz
    ├── 33fd1701b2cf96b40602ff728a3457441ca9a9ae.nq.gz
    ├── 34760e383bec4272023a909b4b004b882f656133.nq.gz
    ├── 354fe725644d4efa360ece82c21aa30ac908b927.nq.gz
    ├── 35c288a9efd36b0e3d436a376ce5367073ce9206.nq.gz
    ├── 35c303758da30f7840161316c2aca54febfe31fc.nq.gz
    ├── 37475a1bb48a3e886feb4dd7c3fe4211017d4b00.nq.gz
    ├── 3748c93402dfba9b4c453776ce3d87769b99386f.nq.gz
    ├── 376a2ad21a47e688fd0695dfbbe71c1d0fd4c494.nq.gz
    ├── 38f5263f837d5f7f0757bd8b89962eeac1ab53e2.nq.gz
    ├── 398ff82abc54ba4df28f6acd6239e6a41a37526a.nq.gz
    ├── 399b30cb63039a79590098f01f615e2a018b236d.nq.gz
    ├── 3b15d11c4f3a01d2af31d0a4eaaf5d24035ae607.nq.gz
    ├── 3b2c374f9964db079fe63c88ebfdd0dc92bbe789.nq.gz
    ├── 3b8285448a37cda726534e28ee00df2838c8bc4c.nq.gz
    ├── 3bb2fde2f144acc20e7fe26d08b4db701c12cef6.nq.gz
    ├── 3bc68f3cbeab75ac059112e0ef91bd3f4599487a.nq.gz
    ├── 3ebf006ddf1a25e4356786965eb60f2cc737bf8e.nq.gz
    ├── 3f645639bff834908ce1f806986a34f7aa94ab47.nq.gz
    ├── 3fd909fa8b31fad20c2f03256bf7c75b142d5735.nq.gz
    ├── 3feb918cea930fd3e1b019c76a3fd5c8a29cf779.nq.gz
    ├── 41193a4c20c86950b2584593fbbc7d63ef73c85a.nq.gz
    ├── 42be9a68b4a84ccebde679705576129def3fc5be.nq.gz
    ├── 43ba0582236e3a85daf3f5677e06c536805d534d.nq.gz
    ├── 44c04541b88536571e9677e316b402026d2086ee.nq.gz
    ├── 44e47ec139544521a9855ad9995290851133d8fa.nq.gz
    ├── 44f15c2f60e5139725123166fef06c6bd84e03a3.nq.gz
    ├── 453e8bee9fa62e8dba66d3e148c089fc470e3a76.nq.gz
    ├── 4541d10f64c746e31b489f7e38cf9751289835c8.nq.gz
    ├── 45d0aeb37158f430362d514bfe856f9308174c67.nq.gz
    ├── 46298383424992cf01b7f3b170bb1b694123780e.nq.gz
    ├── 471a76db126a88c1ae388327dd482420823114f4.nq.gz
    ├── 486a4bbab7092a745e3d78b83557a9b6a3ebc133.nq.gz
    ├── 4a01f371afc51af2383cca187f1259f38b319646.nq.gz
    ├── 4a3cc2f475097856a34321d3ec913b60c1f4e0b5.nq.gz
    ├── 4a57937ca1b8a7f8a2b74388decee6ae022b1fb0.nq.gz
    ├── 4ab77390f3750500aac31c98f4d57b14ed0d9a89.nq.gz
    ├── 4adaf9434b0017c1ea96410461061b718a368761.nq.gz
    ├── 4ae4f7893a0b07f44629e6cee7e50e3363fa5d97.nq.gz
    ├── 4af725a2ecaa60a7f3fc1db12b7b5a49758da1bf.nq.gz
    ├── 4b1334de9d03bc2181fe19fe052d455169c87d48.nq.gz
    ├── 4b6bb86088e9549cebab76f28c2361f5c5de5582.nq.gz
    ├── 4b75b06dc09b71a93fd119b9d2f0697d3b291e65.nq.gz
    ├── 4bd4b9f0a19d7f67e2285912f7df80c2c527756f.nq.gz
    ├── 4bf8c048f42b9ac1822ed67a55ea86d9326ca9c5.nq.gz
    ├── 4bfc8b9cbd4a68987d61d5cc27182e1e37d68485.nq.gz
    ├── 4c0f13bc4a3c21a5b0101d3de3103ec308a37e68.nq.gz
    ├── 4c1b0600bc0bf361b42c0b7edf12636e01a67829.nq.gz
    ├── 4c4b626cb3eb9c8b83907d7bc559cc852122a383.nq.gz
    ├── 4ca37f43822918f6857a900d69fc24517a0857cc.nq.gz
    ├── 4de57578bff3ff801f9b70dba3a77fc81ad59dee.nq.gz
    ├── 4e71448f5e1bea79c406838dd3f053b3d54a1283.nq.gz
    ├── 4efb69e969a9bf7541a81e675c5118d818ee23c0.nq.gz
    ├── 4f6d36df3c92fed09e0073b621a1488a778c2c20.nq.gz
    ├── 4fdf710f6a2c1165ad4705a8065f91456a54aad5.nq.gz
    ├── 519f9c6032141b1234a12aba3cd57765b11586c9.nq.gz
    ├── 52f883e354076891af4530c63ceb7d4f43b58fd5.nq.gz
    ├── 5344315b7b9f29a4c33c1af738fdac7fb7598dd6.nq.gz
    ├── 53808e2254711d6a388b363df2823ef50feaec61.nq.gz
    ├── 557c776848a5e1c97f21592781597d094d8bbedc.nq.gz
    ├── 564061b21beb01980dac89f4826ed78a5663192c.nq.gz
    ├── 564422f8b079981cd552364af1964085687b8eaf.nq.gz
    ├── 566241fea82627b8b9a0d2e551b0270115fd2f7f.nq.gz
    ├── 575ca8e02a2d884d51a1392013ffc6e331e50f52.nq.gz
    ├── 57f3ff6e92e60d12f283abf83281e0287514b92b.nq.gz
    ├── 57fbbce95ae57e570cd3c8f7ade0a238e0256f94.nq.gz
    ├── 581e25d73f595acea568b33ff8628ea66c030394.nq.gz
    ├── 59bfccf056eb7d8f8a411cef1187d0815c818eda.nq.gz
    ├── 59c9eff3fb83d4eb6f7dfbe1a8f66c7bdbe232d6.nq.gz
    ├── 5a0c72b29ca731c9103cda26ed77e361e26b63f2.nq.gz
    ├── 5a53588029e18334c0d33a58494c978d1609f605.nq.gz
    ├── 5a5c0fff12f8367c2bbbb48849c19d0144b47144.nq.gz
    ├── 5a9adbfe4afd841804b9f272f04939312d7d7b11.nq.gz
    ├── 5ab41a97ee5d0d932a3474bd5edc11c72a04fbad.nq.gz
    ├── 5af9edb9f654be0deeeca237708db68eb9bafe12.nq.gz
    ├── 5b682b412bfbe549f9a3e2a1a601ca9c30b84dd6.nq.gz
    ├── 5b6ffa8b70f40c8162fac6d8ab53bb5202d2b9c4.nq.gz
    ├── 5b97f35873a24d9db44d74109c83012798c9dd43.nq.gz
    ├── 5bc048bbab23532685c3a042f37bfa84cc55a4d4.nq.gz
    ├── 5d20b0e1de444f5d850b4527aac488e95da9d703.nq.gz
    ├── 5d2d30155f88da82b78e2a6d159dac5261850d12.nq.gz
    ├── 5db28dce847fb425d08ca9ee701f91bc9c7bba9a.nq.gz
    ├── 5e16e72cc8a95a88ec0d4c5705685d73398ba5f0.nq.gz
    ├── 5e7cab08f2776b73ff0b45fdbeb68c2ebc9ef992.nq.gz
    ├── 5f320f114c71dd885eab72cfe71c577cbc5cfe4c.nq.gz
    ├── 5f785e1483b1fc0fa2221ef013f81442e6e45671.nq.gz
    ├── 6017bd5e2b7c895a43767cc78309cd97b8343b86.nq.gz
    ├── 60ce4f998a012dea119d48ae384a36914dccbcfe.nq.gz
    ├── 60fc46aa97233e54a00127596283a9f9162f0763.nq.gz
    ├── 617b4a43555d691787c55611d4e373692d945c7c.nq.gz
    ├── 61a400b1f9c9c070f804544e4b9186f6f12efe81.nq.gz
    ├── 6203ca6b1419b6ada1e0ba1b8d21b70f17d8c8e2.nq.gz
    ├── 62d9731cda96f5685542ee87e040f958cc46c66f.nq.gz
    ├── 631376d5d80d3be77ce9cc6782ffa11450a46e5b.nq.gz
    ├── 634473fe5de47b4d8468fbe3c445e7acabeba6fd.nq.gz
    ├── 63e8546b62f5b3f19b6f1afe525eb0d0bbfade0c.nq.gz
    ├── 63ebe1ebc9b7c3f18d776ed26d4c731fe0302bf9.nq.gz
    ├── 647a2e24cbfe40eda49e6ac7fe35e078bb6710ba.nq.gz
    ├── 65173c8a7e9d15c05720821566da9b02bf548ed8.nq.gz
    ├── 657de6bc400e6a8087ae7e1a40ed3ebb5e3c8aff.nq.gz
    ├── 65df3f48d1a22020041058bb57919ed833e07ea7.nq.gz
    ├── 665cf346408231d256172d3fbcf4601a7d37d890.nq.gz
    ├── 6747e979c5dc8a62f0480ebc31f7176ff75d9812.nq.gz
    └── 686b472b45c3cfd3fb2f469e7f6ef8e41178975c.nq.gz

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

[pydantic/perses-shared](https://github.com/pydantic/perses-shared)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
