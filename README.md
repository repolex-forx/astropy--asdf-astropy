# Repolex Knowledge Graph of astropy/asdf-astropy

RDF knowledge graph data for [astropy/asdf-astropy](https://github.com/astropy/asdf-astropy), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/asdf-astropy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── de7045b49ae13b5acc519124c0735f4c4a406d3b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── de7045b49ae13b5acc519124c0735f4c4a406d3b
│           └── chunk-001.nq.gz
├── blob
│   ├── 005f8630171e34367b77b6726b9b00746f69c26e.nq.gz
│   ├── 00ae9f7f03f0b54c807e1dee6e0e1eaade3a66e3.nq.gz
│   ├── 023a8bc262847ebc5103d1894e942feb18d6a8f7.nq.gz
│   ├── 03a68a5b8ec87d631b7fef332a617947384a4dbe.nq.gz
│   ├── 0a968999a347a673ab76aa2afd1f260c08b8ce15.nq.gz
│   ├── 0c0b942db92a22cfe7e61a89b5f7a928f91db340.nq.gz
│   ├── 0cae014c48facbd9317c52351a8eaf89fc22d8b6.nq.gz
│   ├── 0f443c93f9cb1ba6cb0690c7a516502fe7b6dcda.nq.gz
│   ├── 1406dd8518b9a9a829730c5a7cb015cc74a212ac.nq.gz
│   ├── 1656861c36cf8c172f06a5e1e519aacfa63ad78f.nq.gz
│   ├── 188bb652d35cc623af34e71580ba47900e752215.nq.gz
│   ├── 18e630698c6cc10e9266eb74f63d4accf279f5b5.nq.gz
│   ├── 195527045231088f377b078eac5d4889b224f630.nq.gz
│   ├── 1a218f5e5bc6f6fcf957402a14d721e762095351.nq.gz
│   ├── 1bd45d7ed44c03ca25679d78ae3a7e338e05cc4d.nq.gz
│   ├── 1d0b9570117cd32c862830aa2279245549beceb2.nq.gz
│   ├── 1d76ac038fa66df0b819a400a00880fedeae02f8.nq.gz
│   ├── 20fcdd7feadfed08078799701cb2fd88dc8bc862.nq.gz
│   ├── 23573a0e13381024a1b1007fdc7dcb6b85bb3636.nq.gz
│   ├── 276979cfc026a6eb6822b75a555e492833db3e93.nq.gz
│   ├── 2786805280fd3c210d81ea339529fccc967b31df.nq.gz
│   ├── 28d7ab26bc7fc8468bc0c0b067147f72c73bdb41.nq.gz
│   ├── 2a434b2dd202b41533334cf921a59469f97eb118.nq.gz
│   ├── 2a889a1598530bb9b4fe30372281416021901478.nq.gz
│   ├── 3169c4f8ac67f4dfdbd85302f88735040eefaa6e.nq.gz
│   ├── 343d77ad221a845f2e244b848f50f987ca1de677.nq.gz
│   ├── 34eea6d62858ab428a0a002ac7377598432920c4.nq.gz
│   ├── 3644a91cefc0b98791a704f711d8d5fa1eba81d8.nq.gz
│   ├── 3976722b5a3ace5fb687551838d4028dba09c4e6.nq.gz
│   ├── 3a504860ae015225de6a78c82cc3d8f4255ed4fe.nq.gz
│   ├── 3ab83217b7cdb553613e877a3aadf22181615cba.nq.gz
│   ├── 3f03e69e0ac9c9a2f3904a0493653566185f5d7d.nq.gz
│   ├── 4030a3a71bf2013228e59f99dcaa9a2f500bda86.nq.gz
│   ├── 453b7cb8e0f986f35ff9e0e44e7f4ba0ff83572d.nq.gz
│   ├── 47a03f291e44753aeff28f03fbd1c81dce2e183a.nq.gz
│   ├── 4bea429116ada8d706745f3369159bc3ce9c5d3b.nq.gz
│   ├── 4c89831b917803a9d629842c7f0c34d75e2b51a4.nq.gz
│   ├── 4f6d25b7715840c88285c4ce8b5570bb95d52375.nq.gz
│   ├── 514ca1e06b012b01306099c81e76e1eb8fd0af05.nq.gz
│   ├── 534901f53872d82021dc9d5a1f9244d1d28b242e.nq.gz
│   ├── 54282d4d6e3f6b5b569e4aaab64899b8357b57db.nq.gz
│   ├── 54eb3ac88310f28a6e6c707105bd0918b969cf22.nq.gz
│   ├── 54f5fbefcbfc37439fdebaf3fe1cb08203f0ac3e.nq.gz
│   ├── 5c56259a1f861e4792d96130d735e2f9f831d3b7.nq.gz
│   ├── 5e48a9764b3443e949e7d2e06e0ffa42fcf96497.nq.gz
│   ├── 5f822a531c07e6f74596b5ba23ffaaa8be70c63b.nq.gz
│   ├── 6310b863c5a8393f9a9fb6714af8576727248ef2.nq.gz
│   ├── 63d10b45172bff8e900d0138527b5a4cb308e9dd.nq.gz
│   ├── 641fc093342fb2dc2ecd92854da1a4fc18ba40ec.nq.gz
│   ├── 655f7cc85454ef34cebd0671d922237cb4f673ac.nq.gz
│   ├── 680825fac59a9035f77791c377c158f7980d8866.nq.gz
│   ├── 6d320c7ab661d795eaa37416a817f3bcbe0e8a49.nq.gz
│   ├── 6e9f353bb02b09f5a32f7247cc290bf9e269a997.nq.gz
│   ├── 6ec97920ecbebd1c7e5e4bb12363e0e913a605fa.nq.gz
│   ├── 70cf9128741e29f88cac9de042f0759cb37b3d6d.nq.gz
│   ├── 72b00587f721012a1bc89ba2ffe6ea27782fef68.nq.gz
│   ├── 747eede2bebf7882fabbde79a7ef51649df49572.nq.gz
│   ├── 78100d0704553159000a79d596d1977eb9980a2e.nq.gz
│   ├── 7c30ff1a7785db7a3433107240e9adabc902e79e.nq.gz
│   ├── 7dc780a6b08ee6167f324cd96a1e0c869d5de8a1.nq.gz
│   ├── 7dd794337443bc80400b1dbed9754e93422adb85.nq.gz
│   ├── 7ebf03d52b26c2f31c9698fc6d7920ad7b851663.nq.gz
│   ├── 7f01537d0c695d2566e33d786cbb9cf9e785d688.nq.gz
│   ├── 80bdacc9e05f88a9862abed02f2543f096fb401f.nq.gz
│   ├── 84ac3b745d4d649e1c22fb315d117415ee893607.nq.gz
│   ├── 86f4053ca424d10aaf379b384c2353cca712626f.nq.gz
│   ├── 876ec31854340bce09dd39c1f5dfc98936a311fa.nq.gz
│   ├── 8874a55771ade971d31e48e1b0db50d0b08dc0ba.nq.gz
│   ├── 8c0a1ec6485d3f8c9ce80e95b7fd4112112a7f2a.nq.gz
│   ├── 8cddf7d71cfd4caedd43facc6236c3bcbbe0bf68.nq.gz
│   ├── 8d3cf9bc2ef366614aaa14c8743b3893dddb605e.nq.gz
│   ├── 8fb36fa30282566d6d588cb579cca19158e63bd4.nq.gz
│   ├── 90d59ea8996fec5913c0996d4bed0ce8d17c33af.nq.gz
│   ├── 91cbee98b8c364150cd8eb3a3b7ec90baf503c01.nq.gz
│   ├── 927bb8b589bf3d4e7ec95b50fbc104141a8576c0.nq.gz
│   ├── 964412fe0d62ce7c4a6168912debe947aa113d0a.nq.gz
│   ├── 9b041e31c42e504948b8427624bd24eb6404b178.nq.gz
│   ├── 9bbdf71c398a83725614f86fd88b68152fbd5271.nq.gz
│   ├── 9e8094a97ad4f0b50f2a07c829f440d63c07096a.nq.gz
│   ├── 9e8e519ca28725746ec8cc8568953bf81e4b9a05.nq.gz
│   ├── 9ec30d8918fc550df8c98659fe4ae32e5d09f8e0.nq.gz
│   ├── 9ecfe42c6f1fa0d880b755c20653bc6555d3fcce.nq.gz
│   ├── a08431e1ef5dabb334e7c5f6e7f222f11e5bb098.nq.gz
│   ├── a2c6ba64f86674cb9c9080d38fadc17b77572f1d.nq.gz
│   ├── a373a8ff36d0ff53cec34c455617306bc8a0dd09.nq.gz
│   ├── a7595184bf07fef3275e09c4d187dcd94fab70d0.nq.gz
│   ├── a8d188a643576cfd1e6538e53b9195d2ba37bcd7.nq.gz
│   ├── a905c9d39eacc329a312781e05ddac9cb68f1217.nq.gz
│   ├── aa930134b5de891e548ce582fcd8670951cd6035.nq.gz
│   ├── af96a50882ae575280251f55bf16d826c808696e.nq.gz
│   ├── b06e2e3f796bc6cee846b9475d8298fd5eb9ab2a.nq.gz
│   ├── b0df02d8f60bd2951491564a0b8a87e2199af5a5.nq.gz
│   ├── b1f712216e02882319b7ec88608afc9ff5569b42.nq.gz
│   ├── b2186532bafc619d802c024cb6e65684a440c5eb.nq.gz
│   ├── b3464da2efd94db6d6d6da952947f844d8631d76.nq.gz
│   ├── b5025e0f85b09b0d48efde984b6c227e65f72537.nq.gz
│   ├── b5442ccffbde42194125f0c6e08adc298c73e8a2.nq.gz
│   ├── b7918842afe533538cc3d70435e4cedd091ee6de.nq.gz
│   ├── ba99ae84d5b8cf07bcb8545fc71988f2aa7b1010.nq.gz
│   ├── baab5ed6424ac0017a0eabdbf3b3fc405dc348c2.nq.gz
│   ├── beaddb911d619b31d108bb339c2094685d5e7b44.nq.gz
│   ├── bfb0727b871c5cc7538b2d292f1f5e8db28c7779.nq.gz
│   ├── c388e65d5a378ad1c9106445b5cb2d97a77f1762.nq.gz
│   ├── c84dff2633a33a2c9ec00f8ffa576faa0dac628d.nq.gz
│   ├── c9d590fdf2a4972dbe69bfb263f304ffb3a1057b.nq.gz
│   ├── c9e7c9d7d76592730126c1a432bebb9231ef309c.nq.gz
│   ├── cbbbb752bb148f33f8400039b0047034e529ef37.nq.gz
│   ├── cdf195e227032120b04b3f4bc99507ad523eab0c.nq.gz
│   ├── ce82cc2b8c1de588673338489a7c62bdb9ccb526.nq.gz
│   ├── d32f797ef3ab23c686ea5d72fd40e371f4538b6d.nq.gz
│   ├── d42e511e87e8c7a44a3acbff6d0e98191a0d68fd.nq.gz
│   ├── d62801f217ae7d6f6744fa2e72e9283cbd0482c7.nq.gz
│   ├── d8789387c59443edbdd88f1ca21a34d516a31a50.nq.gz
│   ├── d986e5bce2208d4ae4d9de7fd5dfd534d2bd1d67.nq.gz
│   ├── da2f2e1814894476f370cafd5239d821ff4ed9ce.nq.gz
│   ├── db4c589058db38714fd62140ad4f7251714c2ade.nq.gz
│   ├── dbb3f6ad46a56589c881a865b5ec1163043b97f3.nq.gz
│   ├── df649dae6a18d8ab8ca618e6af58a00ca3eb64a5.nq.gz
│   ├── e3c6b7211994a3065993cb81f5df5158038e42c2.nq.gz
│   ├── e417cf74d6dc6a2d986fa64ca1d6d5c896dff216.nq.gz
│   ├── e4dd31a2e220e3fa7623fef7d979e4c3d21bf66c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6d8839d046bbff878a34ec588af41f0b0948b74.nq.gz
│   ├── e707c77a737e2272f4604be389beb785526b91b6.nq.gz
│   ├── e77dfa45579eb783bc4260a1f4c9830f77151e84.nq.gz
│   ├── e7886248afcd17ed2a250d2ab5329623e7d99b8f.nq.gz
│   ├── e807a2c7af807a269033c18a1a3b29b7eed882a5.nq.gz
│   ├── e8180cbe48e69ed563a5a5a3dfa83478f38f0793.nq.gz
│   ├── e829b479ed37923e3cbb679def3f2dc94f52b13a.nq.gz
│   ├── e88333bcf8b83422a55f848fc850556fe939d450.nq.gz
│   ├── e9dd87e3aa28f7a711f6cdf431712a61fb420896.nq.gz
│   ├── eb185ad3721563b63aa478e3a0bf5a9ebc97d4e7.nq.gz
│   ├── efd9a2fa8ec3ad2a1ab3a06ee3575ca8a85ec0a6.nq.gz
│   ├── f5eb819339b9b7b264c6774775b61ac59a9945e3.nq.gz
│   ├── f619b542cb991ac2fffd1e17998473d895a2ffc0.nq.gz
│   ├── fa84ca8e1943282dce239bb55120a6a2673ebbf0.nq.gz
│   ├── fa8c236b43f954470f45b393c89dc27783b45278.nq.gz
│   ├── fb03f26e6be82581a39a45b00c82f59717bd983d.nq.gz
│   └── ffd6a80e63ed72cee9abd9e5b8be89291a3b35d6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── de7045b49ae13b5acc519124c0735f4c4a406d3b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 147 files
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

[astropy/asdf-astropy](https://github.com/astropy/asdf-astropy)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
