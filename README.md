# Repolex Knowledge Graph of pdm-project/pdm

RDF knowledge graph data for [pdm-project/pdm](https://github.com/pdm-project/pdm), parsed by [repolex](https://repolex.ai).

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
rlex download pdm-project/pdm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b8b21a9ce2b8b1af742387d81d29ea19afa85ecf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b8b21a9ce2b8b1af742387d81d29ea19afa85ecf
│           └── chunk-001.nq.gz
└── blob
    ├── 000cfa458eb73fee8786126dda8bff2bfea300ea.nq.gz
    ├── 0027b47e89f4510743bbfa40b567f785b7a751fb.nq.gz
    ├── 005ce849419e69e0a8ad0a5bc3874b7c380ccfd5.nq.gz
    ├── 0166ca0f6c8e6ad7068a2dd18e6c524c0b87b89f.nq.gz
    ├── 0215ec9c44756ae69da6dd545c50e516f874e401.nq.gz
    ├── 024352faa02435349371d73399ebc6035e539cc1.nq.gz
    ├── 029ac7212d7b11567a433a432fae0627f5e1820d.nq.gz
    ├── 03649cd3988cb12357a7ab96cf429cea9a36dd63.nq.gz
    ├── 03e39d93400c638bbd8eb57e60904b83104b05eb.nq.gz
    ├── 0477df5e5704e3badaa3e3f284146d4d3d93981f.nq.gz
    ├── 048e432218cd90a149dd5bc6b8572d6d97c43824.nq.gz
    ├── 05b75731d806dc71ed7f469d703179013c8ddd38.nq.gz
    ├── 05d18b0f7903251e4b87b9c7bbacab3189ae4fce.nq.gz
    ├── 064b8b6c317b7e09ae652c17f2086c4683498422.nq.gz
    ├── 0728171227ad5db5cd0dfeb997c720a7fff2692c.nq.gz
    ├── 084c438b40616e436bbe92cb30e1091840e3e635.nq.gz
    ├── 09221e37f171023fc6ad1adaea754be6f7a35b08.nq.gz
    ├── 09ea9e85b6d72a93dbd48c1858cce9638745b467.nq.gz
    ├── 0a06fad56123d85632d368e208c8cdb8e043cf39.nq.gz
    ├── 0ab2d4368a1a4b869ec0825312f6ba4bce6a0dd3.nq.gz
    ├── 0b58b07f670693ea010ad43f9bdcdf3f4004e9b3.nq.gz
    ├── 0b6b53c480b6db7507e7250547e845eb8765a0ca.nq.gz
    ├── 0c3e00787fc4f2935ab47b8fb5c1b1b0de9671d8.nq.gz
    ├── 0c5324436cb764b67e9f6c935d09eceda5e574bd.nq.gz
    ├── 0ce275341b55ac2fe294c2e829b100e6e491474e.nq.gz
    ├── 0d3fc16919227d4951715594fe7e40fab395129f.nq.gz
    ├── 0dd47c3c9d5591fb53980a29b7beb7992f8c16b9.nq.gz
    ├── 0e2bb6aaddefb06736cc607b3914e9d7c74b9308.nq.gz
    ├── 0f8710b7e275f7257d9dae0f8805f7c5f66f23bc.nq.gz
    ├── 1072d38a8af3a77f5b6d6add5ed5d51985deb8b8.nq.gz
    ├── 10a21ba1a027a7de342cf6e26be73f848ca5e5bb.nq.gz
    ├── 10dc48de67d568832379ff80c10bb68c6215719b.nq.gz
    ├── 114f58917907b0954ada840d0d9ec9e7bee228f1.nq.gz
    ├── 119c4899405aa11d843704448923de6ab6a86374.nq.gz
    ├── 11ab785d8504c27b7a2d3d01694cb92740d26a95.nq.gz
    ├── 14b29e59814619a16c071b11da86b76468969302.nq.gz
    ├── 163b4a389ce294392cbdc5ceac9b4f3131509d78.nq.gz
    ├── 1790a118ad5eda68c3c5ce6b83eefc2a9d455405.nq.gz
    ├── 17f6246ff03e87ffba800397c1282926307d5e65.nq.gz
    ├── 183e39af22362781fa7025af7b8badc5c14d8a0f.nq.gz
    ├── 19486376a0c1bbd92a8c2a6912699935edffb5d4.nq.gz
    ├── 1aa1a2ea6bc49ae344411bfcf62cf3849fdd1bd7.nq.gz
    ├── 1ac67c10f15d7561c83face9351e6f8ee953c50d.nq.gz
    ├── 1be96fe2ed8d6e0760019850be85c9275d44ca6e.nq.gz
    ├── 1c7642a50c8188cf6ec01ec398ba5a281c4beba5.nq.gz
    ├── 1d2429baf2af9d8b0c42fed3fcaa98e82197c03e.nq.gz
    ├── 1d2bc57a72737c000496f7aec1cb6f66490d9409.nq.gz
    ├── 1d319957c659873e5f2a994f07f277fa91eed2c3.nq.gz
    ├── 1d4f31a21f72ee832f9f4c4e18732dd26d26a2f7.nq.gz
    ├── 1e4bf07ba4228706d1db42eb1bc520b6b1bb40d0.nq.gz
    ├── 20791d2d0d348158188b475d150d23916a3bc9de.nq.gz
    ├── 2228784e463e618f2114c84b97f940897163b7a3.nq.gz
    ├── 22f624e2c0a9a5044900d0a29be74c997d543567.nq.gz
    ├── 23cd93f8322e7b44fa911fa088187e083c673b4a.nq.gz
    ├── 25841843b001b9eb61c4394b9de0ad01658032e9.nq.gz
    ├── 25d1aad1f5261d666d65f6c9be210223d28a6ad6.nq.gz
    ├── 265e2bc528c4d86bdb3028c797bcd3d0a194277a.nq.gz
    ├── 2872b38dfa00ebf4a005d4e07cb1e62062463f61.nq.gz
    ├── 29f6098048baccccc60fa1e100e34c40f0d6a943.nq.gz
    ├── 2a561e40b27ff928fa2ce350f41624e6452e0dd1.nq.gz
    ├── 2a950bada8e131b6d6265f07d8f10573b117243c.nq.gz
    ├── 2bec911d9379a723b7e6ded34c8b77e2e1348659.nq.gz
    ├── 2c55ffe6ec5aec9575941d15fe109ceb48fcc8a6.nq.gz
    ├── 2c7bf2278851ccc3172e34134e31ca1e409bf766.nq.gz
    ├── 2e62d921c25dd7329385594190a269eaf24d1c73.nq.gz
    ├── 2fa6abb02abb710bde8a943aaaaabc75a9555867.nq.gz
    ├── 3066f0378527610dc48730f83ab422aa36d6e791.nq.gz
    ├── 310d68835c86d80ea96d3ec3bf409693bd57d1df.nq.gz
    ├── 319bc2d4b933cbe6269ecb1f49c04b041ed58f5c.nq.gz
    ├── 31dc786146d9227c50ecd528719dcc86a9c1df76.nq.gz
    ├── 321fd43f9f66901207f60469d9695076fca9efd2.nq.gz
    ├── 3266916c79e6b543f58ce24ebed10e69de921735.nq.gz
    ├── 3440985c3140e43863de0b6ffec5cab4248b8583.nq.gz
    ├── 358c18627ce02be92d94cbc19d9e3f7385166f2c.nq.gz
    ├── 3591368b4f69a9171048a89b1f639f16d9e8a5f5.nq.gz
    ├── 368e6f3b9d618561120255514d22a59139a0b785.nq.gz
    ├── 37c36011e2e59e66eddc6a556413808a7ddb2e27.nq.gz
    ├── 381d3c8c981f98611561a6ed7cfcf0d8c45ee3d2.nq.gz
    ├── 392bfb0bb3281e8c1587da2502b5e6820d9d8026.nq.gz
    ├── 39a1ceb1175a3cf3db0e6f383861e877b6f30ed1.nq.gz
    ├── 39c3ef6986c273307af9aba0ad4d8bc587cb74dd.nq.gz
    ├── 39e237d274ebbef5ca692238d7a865cdb52d22c5.nq.gz
    ├── 3aa8945daa75bd1b2ebeb3b71ac15c0729a65f36.nq.gz
    ├── 3c4f2f6e637f6c8633878da3654f2e1c94604c17.nq.gz
    ├── 3da2db41c3bef3912a76e56002273cabc06eadc5.nq.gz
    ├── 3dc1f76bc69e3f559bee6253b24fc93acee9e1f9.nq.gz
    ├── 3e2c83e55eb45b3252fb98ebf1a1842043996047.nq.gz
    ├── 3f6b046d1c7a251f072c208dbf3ce31cfef2cab7.nq.gz
    ├── 3f7fffb15ae94b34441b3c600f118cc435181dca.nq.gz
    ├── 401732882043955639199477bb684ea415f176e4.nq.gz
    ├── 4086b552a23d5d54cb63b368259892741b1bb174.nq.gz
    ├── 427ae0c46bc240a06aa6532e8bdf9c903b4997b9.nq.gz
    ├── 42b8c7ee0f3cf70f954ea3fe388851eae6e4bc26.nq.gz
    ├── 42f20c5dacf624d410ce552b49c6c8b38566fa71.nq.gz
    ├── 42f9532e0f7f287242bfaac4b399d99a6fdbbc0b.nq.gz
    ├── 43cc8a75d5d8fd745c34f25ff844eb0f6487a84c.nq.gz
    ├── 465ddeda3208b442ef5eef934060e10d8e279f46.nq.gz
    ├── 477b3d8185c988ada64357af23f497e27992a43f.nq.gz
    ├── 479933221264d449dcbaeddca91ef0e34092c7d3.nq.gz
    ├── 486cba9d1ae2e30f2470220fc308c191f006e7e9.nq.gz
    ├── 48e5b6f29d23e80f71b60cc4d73fb4bad62ff975.nq.gz
    ├── 4937cd5dc3b7d23917ed7d9a50490ddd1fd1f364.nq.gz
    ├── 494ed3e74d5ceb988d80954afd11091f00c383cb.nq.gz
    ├── 497d4d169d7b7f99c9fef4bdf454d7dfe2acc050.nq.gz
    ├── 49916a071b28d02bbef7107d0828ea2dc05dff92.nq.gz
    ├── 4a1e0792353289e8a7622592efc1b4ec753dda24.nq.gz
    ├── 4a9a40178b223dc943e4235e5aa56dbca9c2c9d5.nq.gz
    ├── 4af7b944dd22358d73ec2a62f58aa7aa6e994ffc.nq.gz
    ├── 4bccfa35bd259f02478ddadaf45d4276afcadfc0.nq.gz
    ├── 4c0bd813b3cf4d6a81651246c1823097646e9ddd.nq.gz
    ├── 4ce6de04654bf1fc5004099c3ef7fb88dac0e0cf.nq.gz
    ├── 4d776f5e23ad64a27418a17337bbedecaa31feb3.nq.gz
    ├── 4e20e0c2b868677df7adc1f07ab3c41201690d3d.nq.gz
    ├── 4e97968e9c242ebdaecf474734fd871e7dfc82ec.nq.gz
    ├── 5075e073a09ef53e9b3b8454f8eeac9566fad6dc.nq.gz
    ├── 512d00ee4f802380439b8d29da9b021bbcd639f0.nq.gz
    ├── 51cff778de1f6212b0f96cf3fcec91a43fbf309e.nq.gz
    ├── 52159d2a411094b0f63e407db19bb7c3f05021b4.nq.gz
    ├── 536b8020aa1e910edcc61347c9fceba457b7adeb.nq.gz
    ├── 541f859dc9ea238cf66986b5b7ccd3189c4c74dc.nq.gz
    ├── 5505f3e71ae861edcb4547aed1b0cd3911a26329.nq.gz
    ├── 559be4a2a1868e017f31bd2b950f47a4b7af3ad3.nq.gz
    ├── 55e9d96b675d0a72eae0ce999e3bc6d8f03276cb.nq.gz
    ├── 56762ac4db92521042882f12016e81d9daddd2f4.nq.gz
    ├── 57e5af73c44cda21579d78dba9011b09b255d6ff.nq.gz
    ├── 581bc10b11337f12d621da6aca1b17d1553c384f.nq.gz
    ├── 582dc52023b7aeffe068bf90219fbde465605335.nq.gz
    ├── 5a858190c62f0b2012a6ebc9b65caf90b8e873aa.nq.gz
    ├── 5c08778cf6ac5f37d7112bcc179c4fee3034833c.nq.gz
    ├── 5c4e1a7f3e496ffee0c3048e155e4382e879e144.nq.gz
    ├── 5cd0fdf7db2878a25c5c0ae2b319bc3176552360.nq.gz
    ├── 5eb7c1e6197d63b44ebc5740b1282fb271b22900.nq.gz
    ├── 5f6766fdec880d073b6bc9bbb04cf04819ad123e.nq.gz
    ├── 6069e65ab6766ec8b222bb7d3f0857f5846e9c81.nq.gz
    ├── 608449968ace8288fbae695be4c9ea59c3f269fe.nq.gz
    ├── 610bf19bf662e690843ae63cdc8ab4bb75ed81e3.nq.gz
    ├── 6120f7c36fc22d2dad66033b6bb8935849a4edbf.nq.gz
    ├── 6228f4e99d909cacbd0d1488fabd938596ede2ca.nq.gz
    ├── 62d1db0d3bc7a9cd96941cf551bf9ee1c2679f0a.nq.gz
    ├── 62eed56a553bd1177191a8e5c1bd571404588dde.nq.gz
    ├── 65e2af37450c291016204618166d6e0e39759dec.nq.gz
    ├── 665f052b453a1f011387527adc6e1e2c60d8c080.nq.gz
    ├── 666ce9e9ac0f49be871cfc724f4fa2797d3a2ae8.nq.gz
    ├── 6709218a38e3dc3605a1d1bdb66f1a30398a12f9.nq.gz
    ├── 6781d0ad5660591e82beb9aa5eb456baac8362b1.nq.gz
    ├── 68372a39f38fbc281e4e5fea28de51ba4556904b.nq.gz
    ├── 6ec29f05a33f8d45953309747000c53fdc5ca49f.nq.gz
    ├── 6f3b549190385e7f3788ff21432bb362179fc256.nq.gz
    ├── 70dd8481e0e3762084251a767425d1b36388d4f4.nq.gz
    ├── 717088474b04017b77fc325460a1b4b1a8785573.nq.gz
    ├── 727aa6f73bbe29813828cdd5dc2045af95d48867.nq.gz
    ├── 7466706932bede2206055aa8d6e301a0525687f3.nq.gz
    ├── 748121f6f727c7bcc4e6020f17f4a270565982f8.nq.gz
    ├── 75b47e48e6fd97c1ac6a759cb83082dea9b1464b.nq.gz
    ├── 76487781ddd0ad82ae2b36529e4300b18511ae48.nq.gz
    ├── 76a2a0084c4b614c55e228dd32da83c49adb5f5a.nq.gz
    ├── 77c44f514b7a853080c3e5ea8cd891ef607ee2e2.nq.gz
    ├── 79168ac7a95ae72690e9f12607fc1430ef479512.nq.gz
    ├── 798682f7142757474088b0368f06e445ec8ad844.nq.gz
    ├── 7a7dcfc116467c686e931c25fc9ae646c38e8468.nq.gz
    ├── 7bdc37e65b1439aa9002f7ebe0e6502c5f10ff17.nq.gz
    ├── 7c30965f61ad0149abe4bd4c3fb1e1284d42216e.nq.gz
    ├── 7c4c2f5ce2c6bab4bf622b4489306de7100142d9.nq.gz
    ├── 7c5b0d9aaabcf20bf3a7f9033ed10af5e42d3039.nq.gz
    ├── 7d1f341254b10cd4ba9f7166eacacf80a277b703.nq.gz
    ├── 7d3078d15615dd9211fca6198e298362ff5bd713.nq.gz
    ├── 7f5e4339b43eec3c0bcb51ee7a77636ddf40af26.nq.gz
    ├── 80843e0f380b2f2345fbd0b1b99c8a0f9d8464d4.nq.gz
    ├── 80d85bc4e26c88832886458b183f5d8f66a6d3f5.nq.gz
    ├── 81f15459ba1b756f2b266d1754640356c4fdbd88.nq.gz
    ├── 830c33c218033dd5d878d48521850b7f37846268.nq.gz
    ├── 87bcea8d7ed87a55313eda29e0eb364b01cbc917.nq.gz
    ├── 899f2e1a14b29234d35b1797cbd08d572267a8ae.nq.gz
    ├── 8aeeab16dd8fe22aca9861c851cdbc905411d55f.nq.gz
    ├── 8b2c0fb0b0f6211ea162796d1ef30fd7ede54744.nq.gz
    ├── 8bcec07d7f369e9d5175960204daa9e3b9744a5b.nq.gz
    ├── 8c20c6cf005adefb5f3888a2b270e78236e3d204.nq.gz
    ├── 8cd658557c358e468815c7634be6163d7df58e36.nq.gz
    ├── 8cde7829c178ede96040e03f17c416d15bdacd01.nq.gz
    ├── 8d3c59efca484e61a0584c316ffd0a26dfed8ef2.nq.gz
    ├── 8d58c96874947894abd6c73dcbaf22f637c975ca.nq.gz
    ├── 8e1521e6be636d72ca0f17d6fcccd5802f2c95fe.nq.gz
    ├── 8ef107ebdbcb16eccf90afc42922664e8c948424.nq.gz
    ├── 8f6ebf8ec1ae85e7e27e05adf6397b55b1ecc89f.nq.gz
    ├── 900c4180242e019fe3cbca706e447d86a59ebb19.nq.gz
    ├── 90aa99ccfcb07e1bff05abe2e5acda9fb0da4720.nq.gz
    ├── 9101fa4820b82021505199de99cd5a15c764cee1.nq.gz
    ├── 91916a82c63e77a16bf965a3d8b600f6ae8f973c.nq.gz
    ├── 938882878435a4ace95532a64a7fd33f4d84130f.nq.gz
    ├── 93971d87133c7cc368f8b474d2b15038068bbae2.nq.gz
    ├── 94a07f455c02acc5686cad2c44a1c11995977e49.nq.gz
    ├── 94dc651c15e61348bc9eb8a829900331d5887004.nq.gz
    ├── 94f66ce099a6dccdb1f39fef44ea3c2ac90fd87b.nq.gz
    ├── 953518bb1939653725f7a446539f484d59c3bb00.nq.gz
    ├── 955ca5a5881aafcc4d38642826111dc9bd0f23e5.nq.gz
    ├── 95e20f08dd11f22365fe2d2726458c1bbe5b3f39.nq.gz
    ├── 97541b62972ee4e2bb7a3e28d884c1c7969dd63d.nq.gz
    └── 977e0e49211ba68d154da7c394a2b48a9f615b48.nq.gz

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

[pdm-project/pdm](https://github.com/pdm-project/pdm)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
