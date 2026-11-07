# Repolex Knowledge Graph of allenai/vla-evaluation-harness

RDF knowledge graph data for [allenai/vla-evaluation-harness](https://github.com/allenai/vla-evaluation-harness), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/vla-evaluation-harness
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cc260841a0a32be778ec8604504de4bd5e663a5f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cc260841a0a32be778ec8604504de4bd5e663a5f
│           └── chunk-001.nq.gz
└── blob
    ├── 00158f55103c42046ef295fd7155a124ba61070d.nq.gz
    ├── 00d0acacf112afdd6401b0375736f72aeaddb7f7.nq.gz
    ├── 0145b17ae6f34f5cb1da1c0bdb1f1e7f48e7fffb.nq.gz
    ├── 017b89c06f53c429c476efae88d48bedffd916ce.nq.gz
    ├── 02337f6653d7b57f6deb1225709f7633989d2822.nq.gz
    ├── 0327495df65769ef5643e88e5dd6c1a428004437.nq.gz
    ├── 0390dd7828c72f3ad673644345e56f8f2e060ade.nq.gz
    ├── 04ae7cada0b00baa3482b62c0dabd154b3d2fb4b.nq.gz
    ├── 04c063564202d7f906212a0f42527f848946eb05.nq.gz
    ├── 05796c06565baae2b4bfe675ea1453ade9bf1a35.nq.gz
    ├── 05ab42ef7e522df6fec1631f1a1c85cb3da08371.nq.gz
    ├── 05e7cdac5842e692faae5bf197019c8eac10f608.nq.gz
    ├── 06e83a326d1a9821d8de19eef87a9a14a9e3e6ef.nq.gz
    ├── 070d33dc169122aabe22d9677fcff1dec13b784a.nq.gz
    ├── 087c62e783960f0214c477da8c2d70a86b2b7dd3.nq.gz
    ├── 0898132ea94f53638e71fb2a4caae7ae0bd8f73f.nq.gz
    ├── 099e1ecf54d31e3f30e0690c22fc9a408d44963a.nq.gz
    ├── 09ed1ee2bc6feab17a1c2788d223b8f71dfd20e0.nq.gz
    ├── 0baf7bb42b83abbdf463c074dba71d45ffc18fef.nq.gz
    ├── 0bf2cf1b33b95b202dff656c82e578f196a37fad.nq.gz
    ├── 0c2ec940548279f5fe22c51f087c6e0cec1548b6.nq.gz
    ├── 0d014c7fefd85497330a45d11855e83b93b3e5ca.nq.gz
    ├── 0de4cdbf0b38846266ea369c364a197dd9488d1e.nq.gz
    ├── 0f3d57e80a6f1678a0b18cfc5643fb5280cd7985.nq.gz
    ├── 0fc17fe6de8b84be95be295663ac9fb76b4a5f14.nq.gz
    ├── 100ea1129eb8db48636796c81c06f49f307edfdf.nq.gz
    ├── 11f58825bbf9dc4cf026f2fdb6e02677c9827fb1.nq.gz
    ├── 123b913c17c63999eb9a447427ebaacd74a96041.nq.gz
    ├── 127f777d5b6e88721e2ec50c5e773d95959db222.nq.gz
    ├── 134b3b964d00a9d9d78c98383b64e4361584f1e3.nq.gz
    ├── 13b1adb4d66eaaa52f00dae44c672eb7b7c605b1.nq.gz
    ├── 13f509a067b183bbdecc29391ce6e9906d3754d4.nq.gz
    ├── 1436ec720f732475400c74bcc7b81a5a0e29760e.nq.gz
    ├── 145c705cbfba8c3109eed19765bb2603a3f1a355.nq.gz
    ├── 15ce3d7290275351be27a62606742f790513cba6.nq.gz
    ├── 15f51e9b3a895984e22a2e1a9e6a18e1075eb15c.nq.gz
    ├── 168bc1b18f6971ad9110bcc24f8425e009a15c4b.nq.gz
    ├── 17aa483ab4ec10e27cd1e78e657e547b5772f345.nq.gz
    ├── 1829eff3b4634ffcc9477d1b9a882ea65717ae12.nq.gz
    ├── 1902716b4bb99d18422e0d771f46829ced947808.nq.gz
    ├── 193c5e2ef0237357d9ddf781dfd285ecce446a63.nq.gz
    ├── 1972c9146b04f2ecd023826be5e351dad6d7b490.nq.gz
    ├── 19ca8b604945cda2265b6838e906973f8bf6c096.nq.gz
    ├── 19e14f17a2c0b3c608bb801df2661c84ebdd259a.nq.gz
    ├── 1a9a9132f10b86dff5fc669ddd25c784cf0f5986.nq.gz
    ├── 1b77c52144fabc55b432a9c3476ee3d99aa938c8.nq.gz
    ├── 1b78ea54aaf9172a28b218b1a3dc4d6a65d6cb84.nq.gz
    ├── 1b7b6bb83d0689bb08fb3ce2bb3b05a7e3c47635.nq.gz
    ├── 1b7c07cb99cc885c80880fa2d5ce10d3be60de1b.nq.gz
    ├── 1ba41a60d4f16033373c2e425307dc2de03a6f96.nq.gz
    ├── 1bba2751467e1abe3e45cdc4af0a155cd6c6d9a1.nq.gz
    ├── 1be69a569dc1650d80c7416828658c477421c250.nq.gz
    ├── 1c04066e39aa51246eb0b26273bb97eb22dd17f6.nq.gz
    ├── 1c41bf7e2665ded7a675198b14875545759c73f0.nq.gz
    ├── 1d4b2b8dafb8b74a0f12c1811c0fd0540861fc22.nq.gz
    ├── 1e2fcdce29d68b3a7506418865d82d4caaf303b5.nq.gz
    ├── 1e927cce7965b40e40306eb74ea4622b04447717.nq.gz
    ├── 1efdf0a2a47f9b2932cd8a34f8c811ffb5dede3f.nq.gz
    ├── 1f316d64c0b8d39e496d309d6decfbb5bb38e25b.nq.gz
    ├── 1fb2432910320c957f86a3f9efa0867368bfc3e9.nq.gz
    ├── 204db3fe8868fdca2f9c6c42acbb268cd96e3114.nq.gz
    ├── 20e4f0293c919c10e62f1bb8fa87e4f0f7c38b38.nq.gz
    ├── 21d353e164d55a37651322290bbcd26b317445b4.nq.gz
    ├── 22c0af967884d10417085f6815dfb5dbb928a15f.nq.gz
    ├── 23021af04d23e6477a88ad6aa66f3a8806843224.nq.gz
    ├── 23801657b48edb40f384b918e01e82ebfe2558c8.nq.gz
    ├── 24a0a91395c5430dcf8ec7de22da4a7582b6906a.nq.gz
    ├── 24b485221a8257e4a603ad180f0d50aefd2b6aa3.nq.gz
    ├── 24c50b7d619c08ca0d2f84a5c1dc319af642579a.nq.gz
    ├── 24ee3fe44fca85417249c5541a3da25b6db46907.nq.gz
    ├── 25bf90a1155ebfec0e39b82643a1cfc7651ad61b.nq.gz
    ├── 25d82df780c3a461dbb5bb88febaef90ca2a2721.nq.gz
    ├── 263bd4762bef2cf1dd81ebbdee86b83ecac43c02.nq.gz
    ├── 268c99ae06da91f3fb1d8badf762ba0cd7162de5.nq.gz
    ├── 26db9a3b39498dd8eecfb28c46fa5c4fc6362368.nq.gz
    ├── 280793690568394e7a6938b558a33ff8ac2cf035.nq.gz
    ├── 2898e3f8dd24565187e99c0f335f34e1bfa4a324.nq.gz
    ├── 28c6ca8e7a6a0474291c9f0d1ed52b8503c37cd4.nq.gz
    ├── 296573eaee67e082a105615670d3a7f4e2f22167.nq.gz
    ├── 299236f53bf4d7e88ce130141fa6d71cbc4dbf5e.nq.gz
    ├── 29b0fe1cc2d11948f80e2026081d7aebecc94035.nq.gz
    ├── 2a24a2dc9febb76f150d85fc73e30ba70c04126d.nq.gz
    ├── 2a2b2af085ec78b092146b9f614b684325547230.nq.gz
    ├── 2a5a598b73735bae2842f952dbfdae742c868c85.nq.gz
    ├── 2ab38065bc51b12a1e997542d10da838b44c6a71.nq.gz
    ├── 2afc1eba90b2eaaf78a82ac4925aad5a0c759025.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2d52f7925abf50611c4c7ca60c997be27b77ee1c.nq.gz
    ├── 2d54bf85ab483588d5238e05dd708505ed384fe7.nq.gz
    ├── 2d9e306df6791a7f6a56b6051fe93d9f7552373d.nq.gz
    ├── 2e3ae6ecebe4734660fae1b2b55f502c2107dcf2.nq.gz
    ├── 2e4f3f6b6c83acebdf551e1ac23ac9585cb530eb.nq.gz
    ├── 2e54faec1975bc4e5718e0f35eef889761cc678e.nq.gz
    ├── 2e758326aa2616aa4c45537fc303e2b83a44a6a2.nq.gz
    ├── 2eb647c38adfd3aa8757b58d81eb5d255bf629a1.nq.gz
    ├── 2ed0bfd1291a15351a9838448f688b6774a85423.nq.gz
    ├── 2ef5f521e09af617127d0b8a6afcd4ad98e38026.nq.gz
    ├── 307f7933c5f69d1a86cac6a964462d97390af586.nq.gz
    ├── 30cdcedfd57b4c73b5e063e8a41a885867f0bb34.nq.gz
    ├── 324cf992be9441db9e11485b379917ce1a2454ea.nq.gz
    ├── 33e8137f7d0078433600e017d0a1878532c555be.nq.gz
    ├── 34156d872f9d220445413748670a63298dcd9e60.nq.gz
    ├── 34adcd2d4dbcefca341774211716261b0362fae9.nq.gz
    ├── 359c1fc5ef9a430bc12d8e0a1714c12ed4689b68.nq.gz
    ├── 35d64aff14fddcde7da66ed3122db199e140d88c.nq.gz
    ├── 35fab86964928865091614da6b218ebc1a07ef50.nq.gz
    ├── 361f794aba352d9f4a192c02d13a5ac9d3527a70.nq.gz
    ├── 37e1caf5ec98ee8555e66f8771245dc076632b75.nq.gz
    ├── 37f16dc8817450bda1852de517624bcf668d24bb.nq.gz
    ├── 38a41a9b1f8bdc2be4ff59393050a8b08c1040a3.nq.gz
    ├── 39582ac8088343b149cd8a44c4cee53647d412f2.nq.gz
    ├── 3974e7c6d23de163d0f21a8681630fcd9bc684b8.nq.gz
    ├── 3b1eec38ec6ac2f0872fd4164774964afb426e7f.nq.gz
    ├── 3bb00f0d708780a0b9390cb6afe9c97c720b2f37.nq.gz
    ├── 3bf44a7f360f0e1a04edbe3180026e1cc748acfa.nq.gz
    ├── 3c8e658229f39d426ac1713f9142c6b128d3e5b3.nq.gz
    ├── 3d32631da79fc049c7d0bd637febb7f44595f1a2.nq.gz
    ├── 3d9efd41ae32a13fba543dd566d83fb5d909bc73.nq.gz
    ├── 3dbd6512fe0dd1a34e27468909955ae00c314244.nq.gz
    ├── 3de53e8b6ce9fe5cfadc4fe1d80a23dc27e7aaab.nq.gz
    ├── 3e25b5881744a54939b6d4221ad519cef1977f95.nq.gz
    ├── 3f2bbd5df92640bea8c14eeb620fe3705d6061e7.nq.gz
    ├── 3f6514c9c0e9ad087665aceebe48ffb5f12b639a.nq.gz
    ├── 3f9bf1913420ce4f0e6094424957eca8a15e4a10.nq.gz
    ├── 3fbb058c1cf4477dcf1ffbd0bc373f15ad490918.nq.gz
    ├── 3febcd93ba668104fdb0471d7d5c7a4ff728c5af.nq.gz
    ├── 402eb45dd02430497cbba8495cb4d3d33caa16fe.nq.gz
    ├── 40b87dc9c3a31a05ffb93eb96d4b017e428e0703.nq.gz
    ├── 40d4425830e03d3f55d9ae5c6a06fcd2e7bd2592.nq.gz
    ├── 40f9bc0d29e85319484112e59db56c62ca4031f7.nq.gz
    ├── 42843807658943ec42376ab99d16a9e7038db02d.nq.gz
    ├── 429887d9f1b022aba8b5fe8ce45bb2fadbfee796.nq.gz
    ├── 42b71ec399b300916bdd15b6396aabb735c1efd2.nq.gz
    ├── 42c5394a18a882778ebf50eb940fb5a96bc4a6d9.nq.gz
    ├── 43c2553afc8e97f44ddd18d812e57a3868065107.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 440865e6aed16f2498c5347f6db7b7b4f9365dc5.nq.gz
    ├── 455e1fc9a05944e0e0e71d33ae00550ea5623adf.nq.gz
    ├── 45e6ba9b2f5791cb05fc42fa4cc879e712cf0e23.nq.gz
    ├── 4642987519a1d0dd48e5510ac52aff2ac46e3dcc.nq.gz
    ├── 46d7701de9b37c7a591260329207fd6acc5ef044.nq.gz
    ├── 478726f9d5bfce8d43e9ed723eafaf5bcf6fcb5d.nq.gz
    ├── 48f3ee5e2fc45fad5e49d8d3399c4289b4b6d141.nq.gz
    ├── 48f481dab29312ee6f9c63ae114c367cd2f3818c.nq.gz
    ├── 491a1d5ba22157ca328927bf60e5d82100fbb962.nq.gz
    ├── 49678d36e27e4fb0739b7cb98be06b616c7d3bbd.nq.gz
    ├── 49a6e1db72c79f588abc3b12ba8e00b59b8ba9eb.nq.gz
    ├── 4af08570520b024ce5e1272d7a793a0c8bd0f5d0.nq.gz
    ├── 4af0ecf33afff28b516c2cc2dc423d87bcc545b0.nq.gz
    ├── 4b39d5a1d583b0342341fc9bc24f0fe1b13608ba.nq.gz
    ├── 4bbf11d7e54e21296a66f18def2799def488fe8f.nq.gz
    ├── 4c350aff4137878c01648d9ab34a961de7e0bf16.nq.gz
    ├── 4c76946da2604767f58f31099f5993ee2ce85272.nq.gz
    ├── 4d6e54b5dded4dda51bedb9286beccdd0dda6ab1.nq.gz
    ├── 4dbe5ffa5aa61a5b3857b6e7e1f728eb15017f78.nq.gz
    ├── 4de95c03ffb3f8e4419033fb975e661ba7c9e99d.nq.gz
    ├── 4e1ac57a86f336a4f0a120c45721bbdcd1d4dd2e.nq.gz
    ├── 4f3f2387624809f00646f0d3873309d03dbe400c.nq.gz
    ├── 506702188ad7c91ee6743d9b8ec6a61bb3b20fe5.nq.gz
    ├── 50e57cd505d46b12ac95beafe56a4fc25fa7ef74.nq.gz
    ├── 51752da1ed8ef5b7413375121e7032bc32589f61.nq.gz
    ├── 530ed5076f96af700452db9fc96f4a75576c8f81.nq.gz
    ├── 531242c3eefe31bfa6e20b2d217381995b1896a5.nq.gz
    ├── 53741765554e795e6bd8e95a87d4e8d2cfd5c2f1.nq.gz
    ├── 53b2470c9af5b36a9e5f59b64becd7b89c847567.nq.gz
    ├── 546a8fd5cf84608e8e8e0751819a9f2eb6f39f9e.nq.gz
    ├── 54e1317c9803b7e57f92e422d226521132e1ea42.nq.gz
    ├── 558a938e85b15bc2d877baf1d66479478e88649b.nq.gz
    ├── 5598fdc04e977bcbf53e9003c6fa191e05e2ebe4.nq.gz
    ├── 56a8abd3a88d1c91ff875346e8bc031c6c6700f9.nq.gz
    ├── 576c8f020d093fddc4cb9ee6f46cc003cd9d56ef.nq.gz
    ├── 578efdc045bc22bf954f9412f11a55e906755f98.nq.gz
    ├── 57bf867f8d6eaa4d2004ac443464b20bf56761cf.nq.gz
    ├── 583eb5dcbe7cc5434bcca5734a1f91bc811cb921.nq.gz
    ├── 584d09711f564a7bca63ee576b77fb74e2feb081.nq.gz
    ├── 58585f552cdebf21bc8f87c8248593d14059d858.nq.gz
    ├── 58ebb21205d9351549a08eb20ea28fb563ffb669.nq.gz
    ├── 58f947fbd598a55e1108334a59368967a7618d74.nq.gz
    ├── 59bfa3758b7c410e4ae0b389d113363679374f41.nq.gz
    ├── 5ad82314041ac78d15dd9cf25750559004b060eb.nq.gz
    ├── 5c17f85e22203b8dd6ad41f6a0e1fe1d116181ad.nq.gz
    ├── 5d1ff8d9c646d2ab8f0533c1a1f303f86d067d78.nq.gz
    ├── 5d6446fa4528e5e88775740ca6800566815f5936.nq.gz
    ├── 5ddfe8c4afa9fcead4a2b09b61be730b9ee07497.nq.gz
    ├── 5f24a5f401bd028585fbaa34a78285b1d175fdbc.nq.gz
    ├── 5f9d1167dc23a77d948c868e4aa969573d2c84fd.nq.gz
    ├── 60a60b60fd6ce358e5c37cff57c81a54f3e3b8b8.nq.gz
    ├── 612596a3647d51990e5947df5004d7b923e65269.nq.gz
    ├── 6165111d67752ba327b32420022d75cdcb37ef24.nq.gz
    ├── 61836aa6b17c1e7d79a4f9a7344b96f0f98ff565.nq.gz
    ├── 61d5340276a1deea104cd8d3ece6321ac6cb46a3.nq.gz
    ├── 6305de3d92fe5e17c09d7074a43f8606698f2428.nq.gz
    ├── 637aa5e7255687963cca4ddc89057a2b89469a8a.nq.gz
    ├── 63e3d92b6dd0d14bcb8d60fa52ef9231134e4500.nq.gz
    ├── 6660ce9b72cefe15c617ad4a8bee0a0d3a6b4a54.nq.gz
    ├── 66a06ad94cd9388418d72c4057cce754ef0beea3.nq.gz
    ├── 67e2476dde98a54c873bd5904ec64b40f2828732.nq.gz
    └── 68393f68d252e755864b533715878d1b620ae69a.nq.gz

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

[allenai/vla-evaluation-harness](https://github.com/allenai/vla-evaluation-harness)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
