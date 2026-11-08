# Repolex Knowledge Graph of run-llama/llama-agents

RDF knowledge graph data for [run-llama/llama-agents](https://github.com/run-llama/llama-agents), parsed by [repolex](https://repolex.ai).

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
rlex download run-llama/llama-agents
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6019e81075ca18f21457813e6437c49c9e57be24
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6019e81075ca18f21457813e6437c49c9e57be24
│           └── chunk-001.nq.gz
└── blob
    ├── 00132f17580b31dd1a2a84ed519bdb701e9fe47d.nq.gz
    ├── 0168927e61473453436f6ed54ee69eef6bd2f1c9.nq.gz
    ├── 017e9d832bfa932637dd0884c3c2e50e8062018f.nq.gz
    ├── 01e0f181edddfce389267ab1cc158cb8699b2391.nq.gz
    ├── 02521223289d4068ed48f77ea10a29c78d342295.nq.gz
    ├── 026f9c9a2a9519752fcde9cf213ddbd66bc29b33.nq.gz
    ├── 0373700f7e42d7076daa4dbcb394c57959bb8e74.nq.gz
    ├── 04628d33aedd89872972b92ce378d96f3266b3cd.nq.gz
    ├── 05336d3218c08591477b3aae830852a8068af2fc.nq.gz
    ├── 05d69376a4710b5a8611659532553e1462e43d5f.nq.gz
    ├── 06ef905faa6031ac34f7c158d73b4251b7cf9ba4.nq.gz
    ├── 079ff6617458d02ea92a9b048c05adf6c7fabd1e.nq.gz
    ├── 07c47a495c5d1f341c337f9c42b2a38c6cfb1f07.nq.gz
    ├── 08052432cc09d4899753f257c3de361dcac18104.nq.gz
    ├── 0811f89437dcf9750a1e8a6959088411a486cae6.nq.gz
    ├── 0a02e3189d8c93783694fb42ff5e68d41220d333.nq.gz
    ├── 0a0d10c5058b38bc5e65ed25411eb5561d3dea02.nq.gz
    ├── 0a1ad84e01bbd37405698696bb0c297b3244aa01.nq.gz
    ├── 0b5eab9190014363be780b792ec6ba50e69f559a.nq.gz
    ├── 0b7534e46f904e1c911d522222e7de74b6d763b4.nq.gz
    ├── 0b90c5672a2e8f2310563d448e81d33374ec932f.nq.gz
    ├── 0b9692fca2a7ab24c1e7bbd9bfbb24c71592903d.nq.gz
    ├── 0c418e1928b19d02d7412f16c1f35b5f02d9d21c.nq.gz
    ├── 0cc307c21ee3ce41d4d95d4ca3d82803f263429e.nq.gz
    ├── 0da6ff87fc015f10b014e990df380795304d13e2.nq.gz
    ├── 0dc6daf7673d047a8bd19e351df08094306f0987.nq.gz
    ├── 0e3d3a6b3fbfeff80a8d4b406850f590ae470ef3.nq.gz
    ├── 10bf1750fd203fc5948daa2fad1f95a6fa395e70.nq.gz
    ├── 1212d3ec4a7b6cedf56d0f001fed65999c1218e7.nq.gz
    ├── 12874886e38071f39e338f8650932bdc68758363.nq.gz
    ├── 12d43d01a00c0cde91ad99757d5bb9817d3a7db3.nq.gz
    ├── 1439c1f8626595ed1f6899c47dbbb0f45d010b54.nq.gz
    ├── 154d42ead37504eaec14c603ac1093cad058d4b5.nq.gz
    ├── 15c8c6d3d5059775ef4b193972be7d9fc2f3e179.nq.gz
    ├── 15fccd9c31e5f814fe1248e2fb1cbc94535c46b8.nq.gz
    ├── 165fa5031f3fd783bc99ba8dd44b55645bb6148b.nq.gz
    ├── 16760286f122a81c58c80910c9ec4f1bc996ef2e.nq.gz
    ├── 171cd61986a2885229ca7a793e9c66d5b23265ea.nq.gz
    ├── 175c8101e80259e310c255f88b3aa930f8b84155.nq.gz
    ├── 18c0c6a94377f3c6dfb4e3c960a0ef0161cf88ae.nq.gz
    ├── 18e3acc2925d9d7034654d7605138eee5b843a5d.nq.gz
    ├── 192bbfcdcd23e30f0a2d429812e7cb3fb2b15a2e.nq.gz
    ├── 19e6e462b8af847f9beeeec0a56e9d110617bcc6.nq.gz
    ├── 19e9f4a4550ddeea91345a9a981458d9ba0501ca.nq.gz
    ├── 19ffcdb3153b4f4a45e28f3d124634aa78486d03.nq.gz
    ├── 1a1167de14233f3da0cce6670ade846ebca60a6c.nq.gz
    ├── 1ae6521beafc8549b46bbf926137d2cd7cf9755d.nq.gz
    ├── 1ae8d3fe8ceee61d6737317e33d7449dda379a8c.nq.gz
    ├── 1afbd02eb302f56bfcc45a48258ceca7043456fc.nq.gz
    ├── 1b7fc9c1d9bc7cd086644ab2a920a0ea194bf384.nq.gz
    ├── 1c00511aacdd3fcc8bbe671e9d730f9c61792181.nq.gz
    ├── 1c1ddc5abac4a47f06f24a06439051ea62e420b9.nq.gz
    ├── 1c9dbd797d7051ecf1739379b145629859788b8a.nq.gz
    ├── 1cd60f405204b59b1ce0c1799134e4f3ccd829da.nq.gz
    ├── 1d38f729dc270930f77e6a5e4f5d1b0e02034ded.nq.gz
    ├── 1eb3fe2d37841be628bc7bebaef6eda033dbc7cb.nq.gz
    ├── 1eebb97ed31fb8cfb04b605703734d6969b4d52d.nq.gz
    ├── 1f8fe49203414037f870222a2f342bf45f316f0c.nq.gz
    ├── 1fc12a3b3f28a4193ccb9b60eb1a42832ec2e6b0.nq.gz
    ├── 200e43fe2b2b2e0b57e74252c8490d5d86bcd8ee.nq.gz
    ├── 201cbc59566c06e21c2844e5c03abf2c0c129bfd.nq.gz
    ├── 2060cc806688876dad5294c28e7b7e721887003b.nq.gz
    ├── 208bce1ea55f45336306e034f62bec437ab63ff4.nq.gz
    ├── 21db616e01e5def35dd825bc59d243ecf2233851.nq.gz
    ├── 22198adf7c951478af9ff5dffd5df4bb11db0753.nq.gz
    ├── 228c3727525a85141bd104dab1bcf181b50cb67d.nq.gz
    ├── 22d108e93920ccf693b07036063376351d2072eb.nq.gz
    ├── 232a97806f16d2afa4aca85784a306d188e86222.nq.gz
    ├── 237f63bd79783a155c2d2c872a620173618d1eb5.nq.gz
    ├── 244fb8061a30fa6fc8fc9ae6fc855c00ad765c60.nq.gz
    ├── 249f367b8e4da68381b81f6dbe15f3fb69b82b4b.nq.gz
    ├── 2501a705bb1615162df86e34575fc50807d7dae8.nq.gz
    ├── 2663d5d983d5c0341ea337e0d9238ea034cd9e2b.nq.gz
    ├── 27396da5dfccf0c177615429583714718ff903d5.nq.gz
    ├── 282d04168a0f8c2a8f5493192fc1ad49617338c1.nq.gz
    ├── 28a30cb2327651062a32083c135ac621a774f1a0.nq.gz
    ├── 28ae20b6f8125baa6a71ad0d1746a2c7f104413d.nq.gz
    ├── 290786c2b26dfa59baf63a775ac71281775df2aa.nq.gz
    ├── 2aec6ed759177e7234dd513636ee7063f94951fd.nq.gz
    ├── 2af33e4fbb8f74b3f55d380b8334a103bb290ad9.nq.gz
    ├── 2b355cb9c3493838e015b5444478763c4f3e1596.nq.gz
    ├── 2b618a78ebeb7ae2f879b987a63d3ff3c0ddb711.nq.gz
    ├── 2c3e072910038491880bbd8c0a5bbc7b74e218d8.nq.gz
    ├── 2c459bde5d88a70f996423ea4a8897eb5ba74fd4.nq.gz
    ├── 2c6c4bd96837ef1890da493b739b1dba72978c53.nq.gz
    ├── 2c9b033d42346641965d00bf4af28661e1eb8d9d.nq.gz
    ├── 2ddc81592d6a55349146810e97a4a7f43a5c01be.nq.gz
    ├── 2dfb1fe3275cc72b73c7894662b0034d3b559908.nq.gz
    ├── 2e487b0a1af4336da4c1f1712788f002f3a038c1.nq.gz
    ├── 2ec10e1c035b6070a2a79c09f58e698d22257745.nq.gz
    ├── 2f24634d902b33445d63d1f79281954f03f120d6.nq.gz
    ├── 2f3a7b80e39d35809a711b6129ed70d973de0764.nq.gz
    ├── 2f9c9eef595d36cd3f0ba9a883f747821364154b.nq.gz
    ├── 2fcfc3b04b38661157ca871f1d4ce497d0755b69.nq.gz
    ├── 3028b9d9443bec20c4fa978af0fb4dcf8a826967.nq.gz
    ├── 30359abc02b3904a3e5676d7861a2f76a74dd2fe.nq.gz
    ├── 309fdde42bfe8851ecda409bd73f3471a41dd203.nq.gz
    ├── 326c64cd20d5446616bd36933d5a3dcada9f931f.nq.gz
    ├── 336a317d4f2773da6b44d31cc6b79e8064a0f1a5.nq.gz
    ├── 33813c5ac9934a9d8af8ad1294801196b818b369.nq.gz
    ├── 33b5d157393cb0f5362b47f643b9907331fc0308.nq.gz
    ├── 34ea339897fdc823d07ff6a0c15003455c49597f.nq.gz
    ├── 3601b68331d7c04dc29088b45fe41c7b8abf261e.nq.gz
    ├── 37524c92a90b8188dd1727d2bb2396752dae007c.nq.gz
    ├── 37894a60f3197beb0745195a9414971923adbc07.nq.gz
    ├── 37d916495dd3db218601ccc32de157af29d5f170.nq.gz
    ├── 380d18682be60ac4298b9514597f1e15fbc8d71d.nq.gz
    ├── 3879857a3d41f89e2acf3c2ead2766609a2d0bf4.nq.gz
    ├── 38ed197affb0ac64e5c1fbb13dd4b3943a9af37c.nq.gz
    ├── 3952736f6e30cc1def6e50464aa73bef9d02c915.nq.gz
    ├── 3acfb8645090fdb0aa9563ee5452cb5bbd06a2b6.nq.gz
    ├── 3ae86b270244c51e08ad71521c85fdefc57a2278.nq.gz
    ├── 3b60fe61d89d96f52ac3b8e116e9597384de418b.nq.gz
    ├── 3be4362941b90c1e954c026fcd8c38fbf5d65923.nq.gz
    ├── 3c1a7a0216ea452fc3f63ce4e506e5ca99fc3975.nq.gz
    ├── 3c260327c615c20eb839db142227a7709363a965.nq.gz
    ├── 3c8d242ecd1ccb678933a353a302e8abec6bd95a.nq.gz
    ├── 3cf4d178d68a4e031258e2919767e6c791ec526f.nq.gz
    ├── 3d0189e8f9bf8f1a875ccc6049b447e7d3bf511f.nq.gz
    ├── 3d88af5bc6ac8d00eef0baf6461cf098544f0370.nq.gz
    ├── 3e2b276ab379111f26c4b883084789de96765308.nq.gz
    ├── 3edd10d27e25ff99871581dfd3ebae04db011b84.nq.gz
    ├── 409a67c25d99275261d1e6549111b5346234c427.nq.gz
    ├── 410e95ed2a9ce215acb938cff12d929ac80fdaa5.nq.gz
    ├── 4178196abe7871be0b94e1b274cf5d4795bcd2fc.nq.gz
    ├── 41c6f4887eb976a1235ed148962bf19f7d171332.nq.gz
    ├── 41fe67232844916712d826d5ef8209b0588db3c3.nq.gz
    ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
    ├── 43e1ced4f9037b03f54834c6dfa4ee9737f18089.nq.gz
    ├── 43e80ad5e15b2a22aef873fbde37f7708c3209f3.nq.gz
    ├── 43ebf7f640389e3ef5e0eb0b76e34bde393249e3.nq.gz
    ├── 447671e155fcd12c3a701e017856c248113d2652.nq.gz
    ├── 448f37a6073f0837eb772244be1a52be9b62ce21.nq.gz
    ├── 44b401da4e4e56348489be85b05049e998be4f28.nq.gz
    ├── 45b1430c6fbdf6ecd800f33c5c3a0be71bb98cc3.nq.gz
    ├── 46b72b68bf34985040b046cba9d5c4ecee3acd76.nq.gz
    ├── 46ef1bc55eadc799bbd6e55c6630c0f0a8bb4db3.nq.gz
    ├── 472c814252ed5b159502f43f74a02b1e15a66f81.nq.gz
    ├── 4760ced6f2e6c763e62f7b32bc5cf01cf09a5cae.nq.gz
    ├── 4775af133521dd2ad7ad9d58bd5e49d04e97b252.nq.gz
    ├── 47bc404730afb66974a948aa6ad0f0f247ba70e5.nq.gz
    ├── 48871a62fb2d2a8306da1b9b9e846523224c3986.nq.gz
    ├── 48a4ec5074f25ffa6b8d957c4888db92a28f2cb8.nq.gz
    ├── 4962455b1351265d8478ae16c16680010c89c552.nq.gz
    ├── 497a1a38ba7052504c0d87d6937687a0da17b083.nq.gz
    ├── 49cb009fd6a2633c2c488a82f14cf60d53207502.nq.gz
    ├── 4a48f0e2da05a0729009e566cce7229ae530e62b.nq.gz
    ├── 4a8cb34fc02a64c08fdf6fb7270b3a4c8ed95725.nq.gz
    ├── 4c354450bfd764fefe84b63d4b2b5969080454d3.nq.gz
    ├── 4e825e67dc49231c1a1185c49585283f7c274c1d.nq.gz
    ├── 4efc615b23220480cf815e4ba0cb3c98f2a9f65a.nq.gz
    ├── 4fdacbe0cea7830ea81757f1007f92d7343f773f.nq.gz
    ├── 5066e50f710d9cc612f09721d58729834c17b3b9.nq.gz
    ├── 517cb60ce720196b66bff46d10a4ad515af5f94a.nq.gz
    ├── 527a3876ef72d33ee531bbf0f2095a83779247f4.nq.gz
    ├── 53901006d5a9d0d0cd177643250dcc157d2bf2c9.nq.gz
    ├── 543a3ebf97c4040490dde1cacfd836d1970d620e.nq.gz
    ├── 54577ed35bf60351010601708b310e299a03f1f6.nq.gz
    ├── 54775cf7a123cd7f5a23fe5e502889f33fd260a5.nq.gz
    ├── 549ee0afe050a7e886ebdea7e5420be5c9ec4af3.nq.gz
    ├── 54a3bcdb127b43c998d40ae7ec190d59a80077f1.nq.gz
    ├── 55a836d4f103f020142f52b4cace19bfaf9fbc21.nq.gz
    ├── 55c18550cde6d90cfd582f66e404347cf5d882f1.nq.gz
    ├── 5727fd66bcd4f70fbf3f0b810f52be9f0bc27905.nq.gz
    ├── 5784913e30391fdd68388d61a80d1dc9da36b2a5.nq.gz
    ├── 587c804aad86e0ffee400943d361f31575257b4a.nq.gz
    ├── 58d1cf49bec7a173aed03e3131835bc247877c07.nq.gz
    ├── 59226f850cc6564829918387b5b95437776d16a1.nq.gz
    ├── 5a27e37c912c729db1bf35c0a6a18479d6c52bbb.nq.gz
    ├── 5af280081697bdc0c8b43fdedf982ee3af79c86d.nq.gz
    ├── 5af5bd28b47fa919804d8fb7b853e88017c82f50.nq.gz
    ├── 5b08fb99fe4fc9c7b541d7ba91bb7c760d4b6d6a.nq.gz
    ├── 5b8047073be1fc4b97d46451d3f768d93eaac471.nq.gz
    ├── 5bc723b86324441aaa2b0c1d5b83c5644dbf7f4a.nq.gz
    ├── 5c733500dc6ffb4f5bebdf51775915de41964819.nq.gz
    ├── 5e7b030d734684fbf1940371ebc664792c85a5d5.nq.gz
    ├── 5ea5b89a551d8920c81694c508f86d1e12b74e46.nq.gz
    ├── 5edb824aa1a5e3e158c5f200af5917f6b3e65224.nq.gz
    ├── 5eeca5373340de0765c56315962c11e9e107fc9c.nq.gz
    ├── 5f9481e20aecc65f2deced9b873df8f7d0e51daa.nq.gz
    ├── 61307bf8a3644cdb8adb044ac704ad0b7a09cf98.nq.gz
    ├── 621730a12f3c94b8cdffe3fa9ce99e4e9deef616.nq.gz
    ├── 62a69216c788a0f54d84bae1fdb5719738747b7e.nq.gz
    ├── 6313b56c57848efce05faa7aa7e901ccfc2886ea.nq.gz
    ├── 63ee2c46f0847367e9c52ca2795cba172f452373.nq.gz
    ├── 63f32f69cd819861e9982f69790446a96f33f949.nq.gz
    ├── 6477e1d434945730fa171be230a6f9ce2b7237cf.nq.gz
    ├── 6520dd89a6978bf5564954d92814f6ffab20e798.nq.gz
    ├── 66151fa35b1d0dff25256b9bc25df074b54dad57.nq.gz
    ├── 66541e9fb5fdb315a3d62c8bfc418d354deec57b.nq.gz
    ├── 67528eb828a98419f07962111054dde87347b458.nq.gz
    ├── 67b61929d10baf98a2beaa8866328649dcb2e6ac.nq.gz
    ├── 688cfb4639840753fc16417cf9c163731fe1ce24.nq.gz
    ├── 6988edd734164729277f06fe33448adaf686a4ad.nq.gz
    ├── 6a7679caa85cabb59b9bb9c3908f7b463cbf78fb.nq.gz
    ├── 6a8090b76310cfb2b31e6fa7b5cffaff764aeea0.nq.gz
    ├── 6ae0401298ee34f9e3de2fb12dd7eb31ac560b2c.nq.gz
    └── 6ca4faaf77c95b67ee37cdea47b69d96b496456c.nq.gz

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

[run-llama/llama-agents](https://github.com/run-llama/llama-agents)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
