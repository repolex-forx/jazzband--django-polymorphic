# Repolex Knowledge Graph of jazzband/django-polymorphic

RDF knowledge graph data for [jazzband/django-polymorphic](https://github.com/jazzband/django-polymorphic), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-polymorphic
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── db86c0c0caaf55417f1767ec149e923711338f9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── db86c0c0caaf55417f1767ec149e923711338f9a
│           └── chunk-001.nq.gz
├── blob
│   ├── 002dcad919813898d18ad36e2211264b24694534.nq.gz
│   ├── 020c8aa1de23b1616c16ae6b0c60694ba7dd40bf.nq.gz
│   ├── 02a5591bc1a1abcec4268b7883f023c50269295d.nq.gz
│   ├── 0317f227bfa5f61ade66af510775a3984e7f9337.nq.gz
│   ├── 035ae32eda7dd05399441cc6bb8490e2708fad7e.nq.gz
│   ├── 03bcbe3b4f00d1e913a5791030d89bbfdaa77b5c.nq.gz
│   ├── 05fe46e5e698c212d57611ed537df44456f9e5fa.nq.gz
│   ├── 072d129f2ce42aea17712fb7aebe4844e070ef91.nq.gz
│   ├── 0d038b17ebf023d45683ab058eb1ba78930584fb.nq.gz
│   ├── 0e184cb86acb6708e853925eaa76da6cd0f7e621.nq.gz
│   ├── 0f1e268af7b493d669f5b7ceaa5b93308619829e.nq.gz
│   ├── 111baebf4209976b28a97be9686f164fbb1005a2.nq.gz
│   ├── 122b20ac493826efcd33bb79a4776f864396f59f.nq.gz
│   ├── 15b0ef228d30e215bc63e6e457de1e9bf9bc6aa1.nq.gz
│   ├── 188ed73df52220a717a8fdf344441c0caee0176a.nq.gz
│   ├── 1bf900b402a1f437690c2a6b959622b69ea2b231.nq.gz
│   ├── 1c6cc6a78c21150dbd1f5439aec3f592183f1131.nq.gz
│   ├── 1cb7761ba157c16ecf055ce1b8972d26c2809b25.nq.gz
│   ├── 1d3757b7e784743f6dc3347ec80056b203cf7621.nq.gz
│   ├── 1da8876281306d1f68f238e34bec35b595b031a9.nq.gz
│   ├── 1e153df360d7e48df4178059885d783ecf54e424.nq.gz
│   ├── 1ec19495939ded1c7a183bce17affc70fc5de4ec.nq.gz
│   ├── 210982912f0d63fc521a1b7f7690b0b8354f0827.nq.gz
│   ├── 23099593f917144a30b61a02611192f03cc59627.nq.gz
│   ├── 23980f450a7d145a59757a632fc52a67ee58299c.nq.gz
│   ├── 2680872f59f757fe971410624e566967f026bad6.nq.gz
│   ├── 26ca81955af889a0efa6592cc928069b425e7d64.nq.gz
│   ├── 28385d1733f0c36035c97fd130018fb9c25c0aba.nq.gz
│   ├── 288ad651156b0523a390101767b9287614ef870a.nq.gz
│   ├── 2cb6d1dbf0b88e7208903bb9a34d70cab96c621f.nq.gz
│   ├── 2e5d980bb62116386970f43a5f0673fd6eeac210.nq.gz
│   ├── 2f866d4326c0b2367eda0c4f20860dbe1da2cdf4.nq.gz
│   ├── 2fc79fc05be71c35491779883f3f885e4df1ad68.nq.gz
│   ├── 30729fc745818c81117cdbe31bdcf6664a725631.nq.gz
│   ├── 33fd360351dd01dabce80daad1fa725a5c500d51.nq.gz
│   ├── 355f65ad2c04096d6cbdeff11abdd493165863b7.nq.gz
│   ├── 380561acd88ee4c882f05cd8c85df2ff3b0de338.nq.gz
│   ├── 38553f7ba5dd7a94274b848a716b1bb5e79bbd9b.nq.gz
│   ├── 389f89c328301972db8f20c88ef682561a1f53c3.nq.gz
│   ├── 398247ab2fcf22c4c3a84c2caf500f6fdad3ea00.nq.gz
│   ├── 39d6d878588b4299816b59f87341205d9a7db235.nq.gz
│   ├── 3be2b242c5720ae1215ecd54d1113f6eb4d288bb.nq.gz
│   ├── 3d2bb0b5bc36792358cbaa12260514a10a58d08e.nq.gz
│   ├── 409be74669a5c7744700b209f90cd1f7fcac1cfe.nq.gz
│   ├── 42c157cc28ab7b40da8cd8dbb0a3395d9d64ae1c.nq.gz
│   ├── 43def9fb107e6bbe88ee2077ebf58e6ce506dc88.nq.gz
│   ├── 44b19052f5bbe1215675a5e825ea659508895366.nq.gz
│   ├── 46f8a33e55295e213810c48a679894215b7b5055.nq.gz
│   ├── 4747a718c93a9516be13ae8c6d2c91b3abc0fe9f.nq.gz
│   ├── 48933f1f2dac2e21157b137800bb026224fa5701.nq.gz
│   ├── 4903db02434aa983b5ba6e53d989b57b6cc3991f.nq.gz
│   ├── 499abd290876f2130da04fab962226d0729d49c9.nq.gz
│   ├── 4abc8e7fc94a3b100b4763e0d4380d7814bb43b5.nq.gz
│   ├── 4f061021a99f9c457d4a8f5c57f0138201516b98.nq.gz
│   ├── 4f8a3a829dcd813911e7ae2a8dc4e8beeef3405a.nq.gz
│   ├── 5071adda56cc0d57f8ba899c9aaeee90a272ffb3.nq.gz
│   ├── 5455f90f6a064bb7e98cbe12e939aa90a756c0ad.nq.gz
│   ├── 54c36608c4c5c29f4e1330ab5bcb16c698406413.nq.gz
│   ├── 5531fbdf1a809a94376bab9e46c854779b9bf5fd.nq.gz
│   ├── 5599905aff7c1777623744a283ae902f0bafdacf.nq.gz
│   ├── 55f7081e6b81cb8ce97a3b30cdbab90296c7efad.nq.gz
│   ├── 56b0f659b54e06f67a86b7af361c13a180dba16d.nq.gz
│   ├── 56cfc0c5fe05f2a35946763452ad07e945a73b1d.nq.gz
│   ├── 571f9f56289992f299aaa536517d7b9147f0628a.nq.gz
│   ├── 5db2865e92ae0050b8eb62d1f4e529ccc42d58be.nq.gz
│   ├── 5f2c1c9462331996398036a514ddc441bd9c11b5.nq.gz
│   ├── 5f595f9567eada2f81a375d728cd267582378164.nq.gz
│   ├── 5f6a0e30e62b0866e12cbf1f3522963539886a24.nq.gz
│   ├── 5fc59eb362f78154035638f4c11fc93aa19018e5.nq.gz
│   ├── 617c8484ddb023aa2d4712a5ba2f6e8dc11911a2.nq.gz
│   ├── 63037777ad643a4c27fb593626dd3a871edaac79.nq.gz
│   ├── 6412211df8f140c0ad4d1ed77caf81b8a0ca9e6e.nq.gz
│   ├── 644457abda0837abd3105e9b48656c284d80e42c.nq.gz
│   ├── 650272a8c28d91b20de734740575037671fafe54.nq.gz
│   ├── 652f3acdd6a052c58775885559c55d6e91a3b4e2.nq.gz
│   ├── 6617323c9934d267e938a265a7f9d2aad341743b.nq.gz
│   ├── 67111789b5b6ad665800b1043836fd33a4f138fe.nq.gz
│   ├── 681d5efea0c00f61a32e2de8cc0cf2518eed2581.nq.gz
│   ├── 681e2f890fb7756adbacaacd7ccde6401bba5733.nq.gz
│   ├── 6845223241cfb83ebf5b37dbd197ca32c673d9c5.nq.gz
│   ├── 690b28bccaabd45a9212ef631cbf3fc6d4889043.nq.gz
│   ├── 69996bd75a606f9c8467e644448e1ecbba6b54e5.nq.gz
│   ├── 6abc0708791af677cacb597d152d79e55d56d2e9.nq.gz
│   ├── 6b398389a4db6b1005480330d49d48c5f1fefc6d.nq.gz
│   ├── 6d6b13786250750ed7c1b704db7cb61414725bc7.nq.gz
│   ├── 7000a1f2e64b49f2fd5f89c538d0c8ed158c6c75.nq.gz
│   ├── 72849637b124324d1ec9c6298b196377e1b0f4a1.nq.gz
│   ├── 731acc10e89f5b87f827f44c2e544aab01df7afb.nq.gz
│   ├── 779c2a7470f6b9360a90ec22624f899b8ff3422e.nq.gz
│   ├── 785217ad95e0b7c54a7d53038cf574077b992a51.nq.gz
│   ├── 7a8ab8eaaff9a216ab0d76dccb54cf0d929dd9eb.nq.gz
│   ├── 7ab5e05d3de71376b18ee862cc895041f2641f57.nq.gz
│   ├── 7b716a05abfa822084161b9cef0653f467d4095d.nq.gz
│   ├── 7bdca8e2a813b3bcb97602f9bdab805e4161aa80.nq.gz
│   ├── 7bf86262564a115a2c6ce21b8bb91eb5709522db.nq.gz
│   ├── 7c7af23f2d60398ecd0e77f726b9787ef1fa791d.nq.gz
│   ├── 7cd54aea7fc3dd72fd3b24eabf46e7989f78dcdf.nq.gz
│   ├── 7ee12fc23e71d1fcf286115a0c1848f6c6c26dbe.nq.gz
│   ├── 7f3ee34d66f513a67ec26481d6a5370fb970ed7e.nq.gz
│   ├── 7f5edbc2747db5c4551268bab5bdb9fe775ed634.nq.gz
│   ├── 801809495b47a7245963fdc9d88ffe8a5512852d.nq.gz
│   ├── 805059a55e08917547121df2ccd9bb18e459b761.nq.gz
│   ├── 807f705029f0e3fba6e6ef191a5a9dd52f458ef9.nq.gz
│   ├── 80fbbf950b2bfc9bea919e820adea0df5b547974.nq.gz
│   ├── 838fc94a63263a148c4ac01105d4dd3119c9950e.nq.gz
│   ├── 85b2fc1584ef5c8a0eda24f99454e00047d2ecd0.nq.gz
│   ├── 87bee8301fc7e471ea72aeb9396f1980f3280944.nq.gz
│   ├── 8aa2e60056a83a3c2fc984875da245958e794774.nq.gz
│   ├── 8b390cf65029f44a500cd337ebfe4ee4072a1b69.nq.gz
│   ├── 8b7788918a75af475ea3101cc8a2ad9a6e4d269a.nq.gz
│   ├── 8bd2c05c17facbc92c7a785b3d9d5a73cbc25c4a.nq.gz
│   ├── 8cdc76ec994072755b9e6a5f0f5fd1db0bf4e618.nq.gz
│   ├── 8cec00f24a2cff756773d57a0eed38875f19f855.nq.gz
│   ├── 91f3981535cd02a7b9a77b4618a586269338673e.nq.gz
│   ├── 92d53f5d0269275da9d75d1e09ea2551fc212835.nq.gz
│   ├── 938e2be3e415e35ee106632f68bc79c7921c60dd.nq.gz
│   ├── 94336d30a18e84ec1486fc2438a59635c7cc6515.nq.gz
│   ├── 94ddafc4829256e9506e97ea5c889b7c6861389c.nq.gz
│   ├── 97fcfc6f7aadac3a8488d0b275dcfbb0d0fa1bd6.nq.gz
│   ├── 9b1676f24e7d0954a525ce7c9b44c4baf0b7b3a8.nq.gz
│   ├── 9ba8ced69d93438a0b5110a6ec04103e574c70df.nq.gz
│   ├── a1f1241c67d3bd0cded78140a20afad884e88246.nq.gz
│   ├── a20850c5d073d74ac36396919a8864351f40fb2a.nq.gz
│   ├── a34109a1ac1424498203c2e6e2953a7b2f3783ff.nq.gz
│   ├── a45cb076fd832d3c4729a1e2b136c6621ba6ef09.nq.gz
│   ├── a6d89b7f6182badd57eb533b29f43a895524fc29.nq.gz
│   ├── a77187ae5a1f5b613d0a33e20cc1f21a2583b7a9.nq.gz
│   ├── a87f2cf4aad05a2f71bf84387d25778e0a668ab6.nq.gz
│   ├── a9eaf82afc61080cf9556344875a427f5023f54f.nq.gz
│   ├── abc48d298e7702d0479de2b41964823aa8fde7a4.nq.gz
│   ├── ad12cae83ac59b50a88568b2521bd6bc5d596bf4.nq.gz
│   ├── aff166c801d7b083d393f2875c7531ddb66aaf61.nq.gz
│   ├── b15caa1d059858fa3f3ddc4c8f4aa6067415eb4a.nq.gz
│   ├── b23b8324b7c7e3b25a94964864a5b06af8dcff68.nq.gz
│   ├── b5a800eb03cb4aea3a45e51ff11f1b54e106d1f0.nq.gz
│   ├── b65bb7438c5269f07eb75f204a522babe116cd93.nq.gz
│   ├── b8fb851fb0fcee8aae9af487e20fb7e4596a01fd.nq.gz
│   ├── b98902e974b505c55a2b1efbb20874ad482be3b0.nq.gz
│   ├── b9b03e8936d6a419176bc5e0ab441c98ddd311ed.nq.gz
│   ├── ba6ad82a211d68cb55b4190ae3b8d5c04eb4a84c.nq.gz
│   ├── bc4db1213dfd28c41abafe680925ecc9dfd83a14.nq.gz
│   ├── bc4f5ad482931d6e24bc1941cd9044f1d279d32d.nq.gz
│   ├── bd6705ccefe0f26b69e3481afbea270b8d4486af.nq.gz
│   ├── bea90603f3733c29c87c3264172538bba29f4ad6.nq.gz
│   ├── bf54d0dcae387e4e64012cfa71af5c6420ea25b2.nq.gz
│   ├── c209488e7245a22d523b0703a0ade00dbe4090d1.nq.gz
│   ├── c3afdf122ecc078dff5134e31653a7bb249b15fb.nq.gz
│   ├── c54413d1d6a8b0e5c34174181338fa8d2f8dcec2.nq.gz
│   ├── c556ffdadb60b2f9b197b2276400bc1e0a020065.nq.gz
│   ├── c56c4a2ded76bd40477744b8cf87f88f2b9045a6.nq.gz
│   ├── c684eb44151c2818bfa5362cf8f25f8cbf3a79f7.nq.gz
│   ├── c7a5b94090ca8c0365c15941e4f3b14c5b344b2e.nq.gz
│   ├── cceacbd0db2c8389dcbd9948b9b6c0ffdff3546f.nq.gz
│   ├── d039d7dd7e6f1b6f7ce26e85f756bcb9388b899a.nq.gz
│   ├── d24d49e6c7ea0e50b180e1cdd208c44bf77a581f.nq.gz
│   ├── d3c359cfa39870cc5ba47c3424ec7e2123d5244f.nq.gz
│   ├── d664c464dfdefd3e83f5af3a405037898ad4cb0b.nq.gz
│   ├── d696b19427cbd38678682b9eec506135eafddce6.nq.gz
│   ├── d9ac68ee5413f7afb4abae1c34214744a1354343.nq.gz
│   ├── dc53c1cc718121829504e1acd6ebd87f518f661c.nq.gz
│   ├── dc83e880ea3757acf203055bdee399bb72673242.nq.gz
│   ├── dd60a2573e823ba46efabc323b20daaa05422331.nq.gz
│   ├── dd8302bdd10c44f2ccc20f520b7cbcad92a504aa.nq.gz
│   ├── dd9f99c712a994060303211cae73e61575443987.nq.gz
│   ├── e0383420fbca60f614e3c50dc06fa8ff4d1c9f23.nq.gz
│   ├── e04e72977c208eed78cb644dbf4bc28ad817d8e3.nq.gz
│   ├── e1549f5b4c0804f5c2b45b7af7967c8c6fa3387d.nq.gz
│   ├── e2a58f0d3e16d8a4a2932098a77d81e86d8eba05.nq.gz
│   ├── e37af96be2b7190cb91be9b4481a76ff197ab5f1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e83491335d9450b1f65bc16e1ce1093d51377bcc.nq.gz
│   ├── e9e66303fb339db3d28ab2582f5bd5b315fbcd76.nq.gz
│   ├── ea1285ac41b5dfbd0a7be617e2db06d45b0a6b42.nq.gz
│   ├── ea764fbd225c5ea8e0e787c08eae0d00bd5dc5fb.nq.gz
│   ├── eb43c2a5cdec1900ef9b7110116548f2f9fc518d.nq.gz
│   ├── ebaec75579f7785efa6d3172039219ef57fbfbb2.nq.gz
│   ├── ebb725bc1ce32a71b11b0180cdd0311aad80c48b.nq.gz
│   ├── ecf5cf95bf5d682e08f2b690f4102e3460199468.nq.gz
│   ├── ed8cb65fab5effc0644a76adadb09eb1d5f17bdc.nq.gz
│   ├── f20e4ae288be5e5bf18f091fbb92c12d5b1fd07f.nq.gz
│   ├── f22fe7c8eaebb8a4891b9efd325fc104904151cc.nq.gz
│   ├── f332738297b93b4862b6a493e9f66b1b385b1c7e.nq.gz
│   ├── f37971d1f257eda7ac124e2852f3cdcc1f5eb36f.nq.gz
│   ├── f48805906e4bedf295badf767debdbd0ab787a33.nq.gz
│   ├── f490fc914942b2b24d1097fb9a5eb048e81c9eb7.nq.gz
│   ├── f74b36df671155711ef405e06a92450239a78f88.nq.gz
│   ├── f7844fbf9d3fbd28da5c38ed73ff19e41b7e7e56.nq.gz
│   ├── f920f1814476b5b32244aac1c0be0d5310d0ccc7.nq.gz
│   ├── f9655f7bf0ef743db8d2af36bd88ea4506e0e090.nq.gz
│   ├── fa2403d6302c747642dc4e96e3449d8fad0efafc.nq.gz
│   ├── fc985d6cce22294cee424760ca8122397aaeb162.nq.gz
│   ├── fd08c220601729c2c75ba46e1399fd206b953545.nq.gz
│   ├── febc3b069cc1023133cdf1516a437092f6dfff1b.nq.gz
│   ├── ff29145f2583acf3131618b80e9b4012dcec89c8.nq.gz
│   └── ffaeeca69932c80a631512282c7b95793e59bed9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── filetree
    └── db86c0c0caaf55417f1767ec149e923711338f9a.nq.gz

10 directories, 200 files
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

[jazzband/django-polymorphic](https://github.com/jazzband/django-polymorphic)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
