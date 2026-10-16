# Repolex Knowledge Graph of scikit-beam/scikit-beam

RDF knowledge graph data for [scikit-beam/scikit-beam](https://github.com/scikit-beam/scikit-beam), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-beam/scikit-beam
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dbe344435f6b12749104b868f7e251624acee565
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dbe344435f6b12749104b868f7e251624acee565
│           └── chunk-001.nq.gz
└── blob
    ├── 0042f500dda69811d81b5e5d1632ead0c4bac14a.nq.gz
    ├── 00df43c0ecff35c41b31f356626df8d3a7e47057.nq.gz
    ├── 02a10274e48836b6c34c67ef855314b2e9195365.nq.gz
    ├── 03405040b1eb3393d0fdf891076ad2d5c16ec753.nq.gz
    ├── 03939e0da773359535934974b0669f8f1187f50f.nq.gz
    ├── 04e6d5424bddaa5c3396b8faa97b11edeab2f3b8.nq.gz
    ├── 05bffcfe68de14baa0f5dbb34f0a41e3ec7dc921.nq.gz
    ├── 089b2174c535ad0e9ca5aaeaaced12f8d8894a19.nq.gz
    ├── 08dd720204f810b8b5326b98b9554ce61a108844.nq.gz
    ├── 0bbd1e43915935cba973f7bb4e3d253d695b7a04.nq.gz
    ├── 0dfe22eb58bce0f8801bdbb73b0409eec2385a95.nq.gz
    ├── 0ef3c67788f7fc5ae4db44b287faa4dffc727fbd.nq.gz
    ├── 0f20e4ffdc294b40f29eb066c6669c41ae6f2747.nq.gz
    ├── 125bf78dae649607ff419f6e6b721a8a7cd39745.nq.gz
    ├── 1267c0564231c92603c4908714395ff18aa798f6.nq.gz
    ├── 12c52faa359b4c6e6061cb519a57311c6fbe0b0a.nq.gz
    ├── 12e69696adb34659f50c2328643076ceefa1e6a9.nq.gz
    ├── 1325b7649e71cd3ff76abefe4920b2be43d1bcf5.nq.gz
    ├── 14deb9069d0d1d8ba8c8c7125d1ebca57fcfc2f2.nq.gz
    ├── 17027cb3edb2a3119f3034d2be23f7df97f6dbc6.nq.gz
    ├── 17ebdeefdb523b5e158638342a1218212b084849.nq.gz
    ├── 192b6a23cecc494dbfcf4842fc6e7386c79a9a40.nq.gz
    ├── 1a1b1a23783270f9daee2a41b4696c8ffa62c589.nq.gz
    ├── 1a578699eadccf75927a4536092a1cd30945864d.nq.gz
    ├── 1ea379dcd28df9c0452c54bf6b5263d6f95fdeb6.nq.gz
    ├── 1ecff3ac5016b57e6effa1269b01130d8467403b.nq.gz
    ├── 1f287f4b577e31d444a72495e35a039655b7c63e.nq.gz
    ├── 20f2969bec4b23ba70c79c320a5edd22713526fe.nq.gz
    ├── 20f4dcfffd4ae0e2d00146c283b7dabbf635bcff.nq.gz
    ├── 210eb6eb885e7eb83c73a9534a78b8b237745acf.nq.gz
    ├── 2198a2ab62d78009783c8aa7ed15723c0444f1e6.nq.gz
    ├── 22002e160761dd866678980c83b164622638439e.nq.gz
    ├── 234724f74e6e953b25f1d7fcce1a9f761f3935d8.nq.gz
    ├── 23ac01c6a60a334843474523c4484aa4ab387c04.nq.gz
    ├── 2456ceb1d447b3781767519ce92272f9e168533d.nq.gz
    ├── 2623195f234cb5254b8f2f19350c3686662b887c.nq.gz
    ├── 290510222788a4fd1c1946acc2c4a9e596f50b71.nq.gz
    ├── 2938feadd5b4ccdb786f8db977e446fbb7a37b73.nq.gz
    ├── 2be830693f03e3ad4fc432407fc75e6cb93138ce.nq.gz
    ├── 2c6c2a97200cabb99f4695fa256ae698755cdaeb.nq.gz
    ├── 2f3b8f105de216e76de76dc6254260dc82029058.nq.gz
    ├── 2f43c88e42cfb7da04ee01f6b98f06e65e724841.nq.gz
    ├── 2fa469052899bb0a14979998e72587be9f54621d.nq.gz
    ├── 2fa67100cf55638cb6caa0353b15fa4d4e274b9c.nq.gz
    ├── 30a9ad65a295501b58bb918108393d458585cf07.nq.gz
    ├── 330ad4f68abba4f8b0d44d0652f96858905fa23c.nq.gz
    ├── 33498c10a645ad5c4720df9be34b4001861a37a6.nq.gz
    ├── 3870cf537d303ee4b8563eca125c19137d9dc758.nq.gz
    ├── 3ba7d46641bb234a40a4f37b55cb06c7ab4f79a3.nq.gz
    ├── 3c01d9cad8af31189a8ec490f90d3e4755db0c24.nq.gz
    ├── 3dca9684302cf908d46c819ad472768ca81d9d21.nq.gz
    ├── 3e1df63478b7ef6468f315a627665394287259ac.nq.gz
    ├── 3e27989f0faad751c361558b70f84d1e0e82f2b6.nq.gz
    ├── 3f78935a3e1596587855883f1bd33aab80d9e0c2.nq.gz
    ├── 3fa387c8217e9036ae5ab398b11d6cf1faa68a9a.nq.gz
    ├── 40aa24f4b55471b3a0e8585355b4c54335804d1a.nq.gz
    ├── 4298d02728cbc1ae0d48a36d89d42f3526cccaed.nq.gz
    ├── 42de5c23fc928061151c4d6d824f5727322faa64.nq.gz
    ├── 430e842c4eed90c8a9a7f4d52057426450fd2faf.nq.gz
    ├── 4333a74775623f738c13e094d3949c7096f9e025.nq.gz
    ├── 43ea96fee87ec6aeae35133df6d06e24d4b23c91.nq.gz
    ├── 43f5b2c5dc8e7f52c514e44745ab417a9539c530.nq.gz
    ├── 46f1c8fd3cada28636229acb9495183af7094812.nq.gz
    ├── 472c4ff3a221c8d118ec8ca1e1c964840e38db2c.nq.gz
    ├── 47c95e8252c0f959c7a7292106f6ea044d5244b9.nq.gz
    ├── 485ffecd6fecc0425fa096f520a8cc0356f11868.nq.gz
    ├── 4951c49673f44d0bc12bf47df6cca8f94c597c11.nq.gz
    ├── 4a7a34ae1cc29362f31e89149a8771e5924394f1.nq.gz
    ├── 4a91fd3563d926ef98f42443b2cd62159b49e9b9.nq.gz
    ├── 4cc6061b653b683feae594ae2384edc6d0863b54.nq.gz
    ├── 4d106a9b8289d2daf6d22af455d6eac0e72ad3af.nq.gz
    ├── 4eb2a56be677f30857621da52c8319fea133ea7c.nq.gz
    ├── 51eff98d0201d0579c717f744761c63c015d7794.nq.gz
    ├── 532087a07808db34644f8b45617a51b2790d7665.nq.gz
    ├── 53dac1341d1010a24dd24f9e41e8dd431d4c9c40.nq.gz
    ├── 5494116e17881c4e187fe54dedf0b662dde1a2b5.nq.gz
    ├── 54d8768672425402934c6ecb9bea8f8df010e19d.nq.gz
    ├── 56a205c9c067ee6de05fb890a1aa18df4315fc88.nq.gz
    ├── 5907d557f4503659e5f5ea15cf5f4372f6f2e539.nq.gz
    ├── 598d59f583ec5fc448df7e78780a9c882873c954.nq.gz
    ├── 59a92b09c795ec36228d86ef739869b698229190.nq.gz
    ├── 5bce6d3eba4ddee8fe04355c038115b276781486.nq.gz
    ├── 5d623787f9ba9a092fb7a6364606163cdae47f31.nq.gz
    ├── 5e75fbb63e22728c0fd41837719b9d3bd24a7214.nq.gz
    ├── 5f1ea73dd5df46a58773a14374dbc910bd7250da.nq.gz
    ├── 5fc3184fe141ffff25c598dfe0b83c6e09e466db.nq.gz
    ├── 60065a5754361b4b11dc7d05748f8012752134c5.nq.gz
    ├── 601cb313a42e1741a7b39bb86cb08a5bef41d88f.nq.gz
    ├── 61f7bc03af156c4b82eecba2f8931813d099080c.nq.gz
    ├── 6235b356f1dd9f747fc98538c34aca802fb9e6c9.nq.gz
    ├── 62ab64d4410edcdf01a347144656058b831c2429.nq.gz
    ├── 642a0a8751c99167cab23765edbf80701e0b74fc.nq.gz
    ├── 64744d262064eb2c6071afbbe4633a569b7de4ef.nq.gz
    ├── 656e16391b7f35f6e691ccf5af65f9655d28948d.nq.gz
    ├── 6640efdde888b8bc60743d53930e5dd49d03c1d6.nq.gz
    ├── 67887693fa18240cd6dd805b18af460bd6e82280.nq.gz
    ├── 67916c490740a72a80d1144220f99ceb069926a2.nq.gz
    ├── 691f997200db7ca1dd09236e1fc30750429e7bfe.nq.gz
    ├── 698ff0c38fd0107eb81730b30491ca1c3d7c163f.nq.gz
    ├── 6b1b4a8aae9ca83ad664b6a225a735df72b48001.nq.gz
    ├── 6c5031f624c5e374b88c2b897b486036982757c4.nq.gz
    ├── 6cafd9ccf6fe777e5cf4c7d00cedac9f1e447ca4.nq.gz
    ├── 6cd06711f9efa21b0db281c3196ffcc05b860c7d.nq.gz
    ├── 6e8b1c2b5f89cf591809c90ea0bdf52244cfc05d.nq.gz
    ├── 6f6428f3f1ac07c4228b54c09d4a82e47941a288.nq.gz
    ├── 6f6c15a4eaf2137822dc451253cbd38845b94bc2.nq.gz
    ├── 6f8506f998ce77fa06fcd2ec862b6d01b021611d.nq.gz
    ├── 7029f1fb2df43f600c926a7cbf147f6c90310617.nq.gz
    ├── 71ae1eb05bc037e1b2f5b060c5a8a13dab563ac3.nq.gz
    ├── 75dc3c2b8617301452c04e7c2fa3cb02d6f8d891.nq.gz
    ├── 77f025424102a13d7133ff5ce110e37bcd4f0d8f.nq.gz
    ├── 7811965f04af7e587e8e7988c6d3d4ff7fb730d1.nq.gz
    ├── 7848330a379058ee0fe49ced3a90f6385f656a3b.nq.gz
    ├── 7b0e6baf48981be3a7b6f4604fedc351d7c375bd.nq.gz
    ├── 7c9760afc039ca73cd627988892c7bd3d0b00e72.nq.gz
    ├── 7e945cfe06bc213e4ceb037a23fa526e5e676bba.nq.gz
    ├── 7f27988d9f555dc166e862260231807edb8d8cab.nq.gz
    ├── 804b1d75bad4da31bc70f774e07a4f1b452295a3.nq.gz
    ├── 80e4d467781213c6e069feeac7bd9a28392aa672.nq.gz
    ├── 81afb797ca53a4a0c59df15d04b8659eb43f0c70.nq.gz
    ├── 81bf87e7dc6e3e25f039ebf98c6378b5beaef941.nq.gz
    ├── 824ee288e3939cd3483b0edd0864c43ca687bc72.nq.gz
    ├── 829cac16a4672aae866b3e7c0072bfb87d2e08de.nq.gz
    ├── 86e964ed12f02791ba8756ba62658cfc49f1985f.nq.gz
    ├── 8981a5d4c89ab3f9824ff71236d32c481b7c5c6d.nq.gz
    ├── 8a132551551956d856f49e0cafa7c415e88c6706.nq.gz
    ├── 8ae0f342ee126c37cde85df6c6149b59ab4a356d.nq.gz
    ├── 8cfc6d012133a279f9cf920d986a5a2cc7c67cb1.nq.gz
    ├── 8da583e5f515333a31c8f2d9cde871b4a9b6b552.nq.gz
    ├── 8df761e88beb0543286dba316b9a8480a18ac861.nq.gz
    ├── 8dffa4939df800db6dd79056d62b676ecf2aa003.nq.gz
    ├── 8e1cf85c9a6a629b694b5e1d47362d74781ace39.nq.gz
    ├── 8e4edd4263680fb3eb3708d4dec9757d7863c8a0.nq.gz
    ├── 906b72752f237a83c20c9a2cc74700551367227d.nq.gz
    ├── 913870bfc70c28153ca854d91effa8bf7031bbb8.nq.gz
    ├── 94810e8df18b91d931204fb17ab886f029a0a961.nq.gz
    ├── 95e4d4c888a7b3ca9f304428790d8f8c45c27f94.nq.gz
    ├── 983f4b4d2f7f3d2ae0c06994a37d086f7213d18f.nq.gz
    ├── 9d5319d08fed40792f26e560d623caa28bb102b1.nq.gz
    ├── 9f1cf94123fff5fa6296f3d2997c374ae761372d.nq.gz
    ├── 9f57351aab7813919ac8c080513e3df2311453f6.nq.gz
    ├── a32dc5973a248b75cbb69707bad5f902b7ee438a.nq.gz
    ├── a7072faf143594241f914844fb15e88605d67161.nq.gz
    ├── a80dad4f51a057911e1f34ca9c4846b64783ef83.nq.gz
    ├── a87d8189e368381df219ab64b2b38b60e2e6c9e1.nq.gz
    ├── a983137acab4c6a66e11365f2e5eaeece77b9ca1.nq.gz
    ├── aa1ef2db66c8c3f02c6f91b1d9a410c3a612f110.nq.gz
    ├── abb36de3a26f7acb1774fd37ae9eec4037af7637.nq.gz
    ├── ac9c74a51ead39f84bcaed2b3e9e3f0d38199ff3.nq.gz
    ├── acd8d97f802058f8de31cdca82bde6394197093d.nq.gz
    ├── ad698d24629e9e462f991e9676a01f832ec0168b.nq.gz
    ├── ae9073bc4115fd5fb7ef03381da59f4d9115bca2.nq.gz
    ├── b1b7cdfc97ddab6f96338f7e09d37310b7cb06b7.nq.gz
    ├── b26a1db3d1d20119b7a110c25a30fdc9f4f5661f.nq.gz
    ├── b31d0bd0c5401039a8dc3d6ea7cc18d34ef18e5e.nq.gz
    ├── b387088bbfc843da36542879247d14139ac99a38.nq.gz
    ├── b4bb6369e4099ec47f29abf95a275c778860daa9.nq.gz
    ├── b4cbd5451ae54b46fe263c93ff4480509814e7b5.nq.gz
    ├── b6d311d9b3da428256ff778adfcbed3b4e27f2ce.nq.gz
    ├── b749581151771336992ecc572dc17a71d1d9fd21.nq.gz
    ├── baa7a8001cd8ec06ac04188515fea8d513cd2766.nq.gz
    ├── bc20b7b6aed0146ab5163941d5f979f5fc49f016.nq.gz
    ├── bc53dbc60a7c66ff4f4cbd0f32c1fac00ca1f346.nq.gz
    ├── bcb61f2bf540eeeb64ec41057142c63b6c898905.nq.gz
    ├── bd5314d71f00163f134236b77c836d7bef7a4a48.nq.gz
    ├── bfd4e6aed1e80582f392954f044da24b504a8e5c.nq.gz
    ├── c09be46fe16c48676e3a2bb694853b8fd3b0a110.nq.gz
    ├── c175d5d6fe0577a01d74ffaf7339ba70361cfe71.nq.gz
    ├── c1df580e0a97aaf8af89d4b77fdada4e9a070b86.nq.gz
    ├── c25eff6db15a0a11a2172ff5d26eda9a4e48754b.nq.gz
    ├── c279820980baf558a8ad7a1a33936438a72e4f07.nq.gz
    ├── c2d22ad0c9ef401086c7b5de2a9314611e70a5e2.nq.gz
    ├── c3589381ddbcbd93b1ef41712ec85b730564b06f.nq.gz
    ├── c53b7e2661bea50b1e008fa8b66d4d07744e9c1c.nq.gz
    ├── c54fb967bb1dff8d4bfcf0437476ab9f716d22e3.nq.gz
    ├── c672302e9ad65659cd03584c2a9563c2bcc10a3b.nq.gz
    ├── c8160bab9cb77c1c4b5652fafa8517c91b82f094.nq.gz
    ├── c9aa36aa6190b010e9a41249248a95cf203adf45.nq.gz
    ├── ca383cd30ecd89060e2984096dce39b7116d648b.nq.gz
    ├── cad7c3d7c8e09c344dcb3647c1949fd4f33366d8.nq.gz
    ├── cb10c8c210d460e3731fc648a04f74302cd35870.nq.gz
    ├── cb25fc5103895b496e89679b196ed1bea787fa6a.nq.gz
    ├── cb4f8047982d36139b0d0b2972c6236e50def655.nq.gz
    ├── cc8e8bfd7db6f352711e7b0b16b61eed4dd1daa1.nq.gz
    ├── cd340d542883cb056a41db42c7dbb4e1b371fbcf.nq.gz
    ├── cd3662e719035ac0aa987c071c61a1a79293885c.nq.gz
    ├── cf0b5f74de2616397abda3f35c49449c05b1d22d.nq.gz
    ├── cf1c4187e5b03982078f3934022ac241330963f3.nq.gz
    ├── cfe054431220f3bc86c38f0326ae7f549c197553.nq.gz
    ├── d06eb0ace02b267549100c800e692b638596cb52.nq.gz
    ├── d0931d34f448967c94b40279869c455a743d0db0.nq.gz
    ├── d392d2353721d64d19acff7cff207ea23f0965aa.nq.gz
    ├── d3b90216f0edf18ee0123c4d3dd3dfa6bc7e31c5.nq.gz
    ├── d4072ca9b90b6fc64431da6ef93e29876d6c1c0b.nq.gz
    ├── d7a6821973f4d82e743a8bb6069dcf136becbecd.nq.gz
    ├── d7d1cd170c6991c1d8177a6c1edde17b6a84be0f.nq.gz
    ├── da66dad03798e2d59b023689babbb8f6deec0a6d.nq.gz
    └── dae48dde22b1484474380416411bce2a3d4403c9.nq.gz

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

[scikit-beam/scikit-beam](https://github.com/scikit-beam/scikit-beam)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
