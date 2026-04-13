# Repolex Knowledge Graph of python-cffi/cffi

RDF knowledge graph data for [python-cffi/cffi](https://github.com/python-cffi/cffi), parsed by [repolex](https://repolex.ai).

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
lexq download python-cffi/cffi
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6366c01d84e9a78e7e85f12ebe9760ba5d19b6d3
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6366c01d84e9a78e7e85f12ebe9760ba5d19b6d3.nq.gz
│   └── repolex
│       └── 6366c01d84e9a78e7e85f12ebe9760ba5d19b6d3
│           └── chunk-001.nq.gz
└── blob
    ├── 0069e3766acba09ac971208d7c3a4287c48aa746.nq.gz
    ├── 02e6a471d04e4cbf45eb7698aecd3355ecd32546.nq.gz
    ├── 052e8b6f4c2e13934e156ca20d6d2bda48f7874a.nq.gz
    ├── 063e52cffe9d9f50d242ca4c7be2c9d8da261865.nq.gz
    ├── 0914ead5297f56a68aed6c7967f8fd04589d065e.nq.gz
    ├── 0a1dbfb017c2e0afcaac48ba6750d32539335e41.nq.gz
    ├── 0a27247c32a381ab7cecedd0f985b781619c1ea5.nq.gz
    ├── 0c4933eeff6dccbf04da7b2fb7f0d3be47ad6271.nq.gz
    ├── 0eb0e71c78562ea533af8a34d7e659d38653c10b.nq.gz
    ├── 0f88a8ae0a022b13f2c545a9ea8088cf4a913676.nq.gz
    ├── 1093505c9ddd468ca2775415bb7287b505b8a67e.nq.gz
    ├── 11247d4907316d1126856e0726c05c2d01c77f6a.nq.gz
    ├── 11eef3bb378fc0cf2ba72fcb89d62bbbdbf7699d.nq.gz
    ├── 1361912bed431601677141fc745f435bb2b05d82.nq.gz
    ├── 136abdddf9d1276095e6f6724298ac19811c136a.nq.gz
    ├── 158e0590346a9a8b2ab047ac1bd23bcb3af21398.nq.gz
    ├── 17e8a40b83f90f69a9867744da1b5d8eda3f4f2d.nq.gz
    ├── 18ea3f664eb0f2c04b07d0aa1fb61c5e27e47f44.nq.gz
    ├── 1a1a3ecbf0f70c15a2c59e30ab4b7a7d87da58cc.nq.gz
    ├── 1a510eb14b80361c4e7a3d38042d0d57d962dad6.nq.gz
    ├── 1a7e05dbe977e492abe1ec08b9c45d1626c706d0.nq.gz
    ├── 2195bf52e3e90691dfdcec00ea91320ca422db3f.nq.gz
    ├── 2337bf994479eb096664ffd5862602c7f057fb82.nq.gz
    ├── 2569bb4a46a0fa77c0056fa42674ae6e6a4ad90e.nq.gz
    ├── 2754fd35d74941f88848d62ded2a26c6df0c0e2c.nq.gz
    ├── 283e33dc10b250b97739be558621cf72842e9f49.nq.gz
    ├── 285361cd46c7d2ca87d1a505293e5fd713481c84.nq.gz
    ├── 2fb042cee81943690009c77e064b1ce626b951e2.nq.gz
    ├── 301188bc9c17f5142ada552eed6f676a5c0d3079.nq.gz
    ├── 30a6cfb32a080f7853764beaf575fe6d6350e649.nq.gz
    ├── 30f2e0439de1846d93dc82d14700510dbefac6cc.nq.gz
    ├── 311a464a8d3c8f15180f7eaedaae87de948ee12e.nq.gz
    ├── 328ba2d635f6d9d5c5d328c29e6073c894eb82fb.nq.gz
    ├── 34147c87757185f80e8fe19526e6f17f44d49e34.nq.gz
    ├── 370a25d317c9063a3b87d59d0168570f4ee27cf2.nq.gz
    ├── 373e4fc2338155877e24735e9615128e733d98a9.nq.gz
    ├── 3788308d51af6b4d926eab331f7aa1703735f2de.nq.gz
    ├── 38d3cd166b0ecad62ea4d9aab86cc574de0c9fe7.nq.gz
    ├── 3c5bb0b32b97da584fb56c287b05c9b56c321b7d.nq.gz
    ├── 3cb9341ca9173c6e08ee383fb665066ec9734482.nq.gz
    ├── 3d208e6e1533ae2feb4bd2742a200f10c186d3b4.nq.gz
    ├── 3dfed136a2f5fde1ac08ed2c14f77c60be1d62f4.nq.gz
    ├── 3ece252a76916dcae4371cf27a8fc488292faeb0.nq.gz
    ├── 43fb83b481055f48114591441debfac42e2d34a1.nq.gz
    ├── 4433ac28c8c8f1223abd99b94921443360f92125.nq.gz
    ├── 4437b870c75bb4603e056191630385038a9745e0.nq.gz
    ├── 49a31d5411e013a8607b6bc72b3426b7ea297103.nq.gz
    ├── 4a3c0f829ce8744e96afa16e3ed161fd6164ac6c.nq.gz
    ├── 4cf6ea5cde9bc499bec6d40ed414f0a2c8273a3c.nq.gz
    ├── 4dee1aa7c7c85366f83f73e051f9373162868702.nq.gz
    ├── 4e7e8c3b76afcb82d110d5e98dc52148e19b3dc0.nq.gz
    ├── 4f0857f3526d8e51bd917f38274a5aae2a33df8c.nq.gz
    ├── 512389ff34bc871102d3541a9c147f8b276a6e32.nq.gz
    ├── 54934f221fee481b67b67202a7e19223e26263e1.nq.gz
    ├── 55446ec3741a72754ca5ed40124b7adc85ee40a1.nq.gz
    ├── 598fb7eed062daac57a3a243ae4a4ecd8d3c85c4.nq.gz
    ├── 59db1c4e95f7f613f60caae545678e7477f2be8f.nq.gz
    ├── 59efb54ec78e02d3d74050143e619f50dd658932.nq.gz
    ├── 5a474f3da9288e51df2ab93f7c40372955986265.nq.gz
    ├── 5b360e8cf7e10961124b408d940d05c600b56182.nq.gz
    ├── 5c93f15a60e6f904b2dd108d6e22044a5890bcb4.nq.gz
    ├── 5cdd246fb4dfb808dc8b09df5724a68386fa4bc3.nq.gz
    ├── 5cfd872bd26e7db3a9ebce34a93f03ea5847d2f5.nq.gz
    ├── 5d286f9997b29088993b987f783fabd49695a4d6.nq.gz
    ├── 5daa6b511e81037b3d4f984c1741c8d2c910b24d.nq.gz
    ├── 5f4bd138112a520a0dc9adbc1c337ab1064ca3f2.nq.gz
    ├── 600e2cf90b94074e8cce1d9433c1f96e9ead1553.nq.gz
    ├── 601cd2ce2d8032b2b8c45fbaa2c7a42e7526b53d.nq.gz
    ├── 6255beb03840ab38b535bb038dcde20afd0b23eb.nq.gz
    ├── 62f5ec849a1ec9f2a1e46c89aa8e0ab0619e4ac3.nq.gz
    ├── 63900435a8f07e365cfb21cf551d837d5dbc8870.nq.gz
    ├── 6421df62134ce43a10d72b3b404102681574abf3.nq.gz
    ├── 64c04f67cacb5d9f2aeb295e0e48a07720d07076.nq.gz
    ├── 6513dfde24a844d0658c469953405f33df4196eb.nq.gz
    ├── 69ada27d7fb36d13cf5a0358763c7cce5011f1f9.nq.gz
    ├── 6d8f72abdaed6274960a04b33b2645bad963e345.nq.gz
    ├── 6e7c5afaea67ffb3b2f9472a84b1acaa203d8924.nq.gz
    ├── 6f89ae9213565ffa2b51ad3855e08b61b941dd18.nq.gz
    ├── 70bb861a26841a6967991280617c3abb6f4034b7.nq.gz
    ├── 70d9ee8e0fe15624cfb70e4a785dbd4292271dbc.nq.gz
    ├── 723624d743d5da7785c66e274da1c9a83915e5de.nq.gz
    ├── 7651e6e0a67e0f7f93135b2da222b55a6d1996c9.nq.gz
    ├── 7734a34863330766984a00d3ff496393471aebfd.nq.gz
    ├── 775cf5629539acf7f54c93ebc979bdbcae15206a.nq.gz
    ├── 77bebaf47363089a0c9891ca71d274de32b5de3a.nq.gz
    ├── 7800dffa87c705af45de622a380538579f7ed806.nq.gz
    ├── 7db7ae280fbe586cf56c72b8ae50838398e7ba75.nq.gz
    ├── 7e386b322e24d486463458e05f3a94525e866d17.nq.gz
    ├── 7ef0d76f653170ca6152a612432e85c936180047.nq.gz
    ├── 8020f21625a51daa33a864ea55487b8ca8081f17.nq.gz
    ├── 8061f83ad71e346ebeee76c7b2c03684f3897fa3.nq.gz
    ├── 824beaf3611968fce624c9ae23b7bf142eb25f40.nq.gz
    ├── 82a34c0c72f64508838294aab482072b7558e46c.nq.gz
    ├── 839c6cdff9a331987e37b511d21d7a9f83c333a2.nq.gz
    ├── 84e4ef85659eb63e6453d8af9f024f1866182342.nq.gz
    ├── 85f5ee81bbe6f5e852ae452eb41cb8569dfb966a.nq.gz
    ├── 87fb22b7d93e43ff3d970d115e6c391fe4878523.nq.gz
    ├── 8e6ea5806540b5004e8bf3e1afe8fb0d06695667.nq.gz
    ├── 8f7f14dbbe58bbcf9a091b86b059c75664a3cda3.nq.gz
    ├── 908a1d7343f1869bc8818ca8e786f2c94a4732d2.nq.gz
    ├── 922f6da6c9efda7fe0b02a617ae8da9747d00330.nq.gz
    ├── 943dd676d921cdd763f5ecf197f31464e3d407e7.nq.gz
    ├── 96208436ec9c02b8102880a07ab8ce4398be4332.nq.gz
    ├── 97a12cfb6fe8a45894fa3ca8eab9ed8350bc46d3.nq.gz
    ├── 986f7081df2d1c12e0cad67dc3af8a23d9902480.nq.gz
    ├── 9a5936dbfa064ca770b36c4c19e1692335361c06.nq.gz
    ├── 9b1cef2c8340689d857bb68fd8f77f9ab67d8d47.nq.gz
    ├── 9e7d79e9affefa980d1bec4c08c7dad8e51f7a4d.nq.gz
    ├── 9e86d990d4a27c37525d9272244bf011339b3f81.nq.gz
    ├── 9f55b7993bb16ab61601e9c899eea4d2d17a3528.nq.gz
    ├── a0e8458e6dcb31ee3fc556e29af26132581cb958.nq.gz
    ├── a339a025549114f52c09dde9f2438e7d2d054cc7.nq.gz
    ├── a4d5551eff196701f7dd6a26492f9afe0ca2ad64.nq.gz
    ├── a6c072415b10bf36816d1abe175d384f2709b09d.nq.gz
    ├── a744a72c20c022b2b50e8497476852b061eb17dc.nq.gz
    ├── a7616ffe9316b1a9b5afd652d2a59606cdde321e.nq.gz
    ├── a8056302c1a293c74f1d38e6e7a220d6334578b8.nq.gz
    ├── a88aa8fc8032875c4698f3eb5b98a86c1bed894c.nq.gz
    ├── a8d20f422620830c81df0aca7db71ff6cb7ded30.nq.gz
    ├── a9fdbcff582907c7c3d83f2a8798eb02bcd65518.nq.gz
    ├── adca28f1a480bb04a11977d26457fe8886139043.nq.gz
    ├── ae9b5731fb8e7d8758f569e69c59de28fd008d44.nq.gz
    ├── b00dd500877a8881746c7a01ca00fad4432380d4.nq.gz
    ├── b02620959058e32770278d9a8a71a15138ba69a7.nq.gz
    ├── b044c0af29798353199adbd1b4961b532ba57fcb.nq.gz
    ├── b0710acceec7fbf0295e084d12bcab7e0856b0b4.nq.gz
    ├── b15c050fadfb17b5085e5160312dc8ffe0b439a9.nq.gz
    ├── b3f79e1684c924225cb672b98dcb888a3ac9551e.nq.gz
    ├── b4ee686e34cf643fbdc8c6320888e9fab92912b5.nq.gz
    ├── b78a03d45ab3646c10d22712c1c5df6a5007e73b.nq.gz
    ├── b85e7ed4e011952af09c934ec66bf990105b628e.nq.gz
    ├── b9e324ff7e11d0fe11273da13416c54729298734.nq.gz
    ├── b9ede184dd4bc1d786e1557d2cf4dbf3eff2fb1e.nq.gz
    ├── bd8c19f4a99e5695ae16450ee5d4250fc71c23f0.nq.gz
    ├── be4e23b65f69049ca5bd923aafa27dc4ea959960.nq.gz
    ├── bf8ece732821aff738f15d0dea5f890da555ca51.nq.gz
    ├── bffc82122c353fbd15a395d77e829a95bf8546b0.nq.gz
    ├── c14f653ec894cfd8b1a868feea04092c74a8844a.nq.gz
    ├── c3d23128189fc121bff3f86b19330b0ac5ce0a45.nq.gz
    ├── c66b56e97e3b1ec16f511cffc4248bcec87cabee.nq.gz
    ├── c75812c24b6725f4fafbf523d46864e9946251e2.nq.gz
    ├── c8abdcbed588411063b712aaf2f42ed4e03df763.nq.gz
    ├── c98605c5ecfc766b8c73850064adcd428931ca94.nq.gz
    ├── c99ec3d481788c39ea12dc57e4b61547176c8e88.nq.gz
    ├── cac9200afa6112cfcdc279a301fe8a4523928739.nq.gz
    ├── cbb7b9dba9a1aed182914459e2c0c13cc9d39246.nq.gz
    ├── ccb2fde6b9f413950b85108460b6fe7db69e039d.nq.gz
    ├── cd29b790ffc727716031226b500e8126c06b3be9.nq.gz
    ├── d23d55fb6676b1a594dfeef498e518d2a2aa135e.nq.gz
    ├── d3d2e178104473471aea30cf0655551dbec36918.nq.gz
    ├── d4dae3517009fc3f7ccaf01d97d10df098700d06.nq.gz
    ├── d5622e133625cac90c334476b41d7b6b1aee6f88.nq.gz
    ├── d5e993f4b4a6f5e382c0c00b3f9805c1446139a8.nq.gz
    ├── d6ce9da1de97fde6c99e68d94253d96eb2ab8156.nq.gz
    ├── d7172e1c31f272c7a24dfe6fcc0699678ac97104.nq.gz
    ├── d92da317ade24e6bd2bf25dc37a78c710c13cb7b.nq.gz
    ├── dad950df0c09265b2934b04272cba8b19afa8b33.nq.gz
    ├── db91b7158c4ee9aa653462fe38e79ed1b553db87.nq.gz
    ├── dc955a57e94a99b08fda88c7f12c4b2f3fb2549d.nq.gz
    ├── dd590d8743d1828eb6139401b2269d173f487b6c.nq.gz
    ├── dd8441dbcd33e0a0c70b7b8603759e6460e753a4.nq.gz
    ├── df703f1462b84339925fc65aacf111632fbf2564.nq.gz
    ├── df94a9887584928601a39cecd74520498cff56fc.nq.gz
    ├── dfe3f9331dd27e8b0ded5688358f6db1b73b11f4.nq.gz
    ├── e1a6000dc80988b843d715675f0af0a7ee2f3084.nq.gz
    ├── e1b97fdf4eba921b3b1ed5db0359d522a3756006.nq.gz
    ├── e22f92e9864777805640d269f4b6051fd2f5da97.nq.gz
    ├── e392a2b7fdab66662f5a32885cbe865d6c538ebe.nq.gz
    ├── e3d28a53917ceb83f1ec60a51dd69278c4ffd800.nq.gz
    ├── e4b3dd2d425b3dc21a28dbb61a6750de46fcee2b.nq.gz
    ├── e5f4cae3e84c73cd09980dabd2ec571d455fe0c1.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7335e45ed854d403523b42e23d04b856a96816b.nq.gz
    ├── e7956a79cfb1c3d28a2ad22a40b261ae7dbbbb5f.nq.gz
    ├── e888ff133cd5369c24caed49bbf50e624dc22cc1.nq.gz
    ├── e8a867ecf0cf75df025b73b5dcf3bd2f72b344c2.nq.gz
    ├── e97767c9d75c1603577d06a151e89fe25816f793.nq.gz
    ├── e9825db8400d06d2aeabb97630e28efbb13e2464.nq.gz
    ├── ea89f502d2bcb3abb09dc5625dceda4ede0d17a7.nq.gz
    ├── ec3d20e043a98623453526ba9447095454cbba8f.nq.gz
    ├── ede8cb97bfe6bac662b8d424137c6bf481ae9717.nq.gz
    ├── efb63c16d870a1692c109be69f8885a33da89f6b.nq.gz
    ├── f10b989a1d60717315e8e037e358e7e3ac0bf8b5.nq.gz
    ├── f147723458843f2abf8e37a1cd8267f6281e4b6b.nq.gz
    ├── f15464ef609eb0ba16ea5e07f90b0860d1a1ba11.nq.gz
    ├── f315cc548159df931849a7f286da74d4f7073aa3.nq.gz
    ├── f3a50a12d4ff7565d24c3c6c40fc282672a3d951.nq.gz
    ├── f51a70c67480c20884904ad8ad1e4b9887e6785b.nq.gz
    ├── f531e5fad5ee01eee75c48b927c967309245fd08.nq.gz
    ├── f591795152d66fc43cad5e55b4adbf66c73b37a2.nq.gz
    ├── f66cf70f9c90e1412445b45b767a93c49d4a95f2.nq.gz
    ├── f75f897f7d1258eb8f1d75ff89d50da0de40ae3d.nq.gz
    ├── f832d6a39b99f1ce20d1772fce12001f9ad25d2b.nq.gz
    ├── f97f404b3e605373c405af66848a55ecf8e86536.nq.gz
    ├── fa62a054fd13401cc13919b1b199a468ab6c4108.nq.gz
    ├── fb78249ff6d904eb581d99f4303e99680ca51f33.nq.gz
    └── fbfa68ca7489038feef356ac9cd032094d6694c7.nq.gz

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

[python-cffi/cffi](https://github.com/python-cffi/cffi)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
