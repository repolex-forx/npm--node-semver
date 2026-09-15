# Repolex Knowledge Graph of npm/node-semver

RDF knowledge graph data for [npm/node-semver](https://github.com/npm/node-semver), parsed by [repolex](https://repolex.ai).

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
lexq download npm/node-semver
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 281055e7716ef0415a8826972471331989ede58c
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 281055e7716ef0415a8826972471331989ede58c.nq.gz
│   └── repolex
│       └── 281055e7716ef0415a8826972471331989ede58c
│           └── chunk-001.nq.gz
├── blob
│   ├── 0165ed997b8506b964d50c7ab39b0663fd240053.nq.gz
│   ├── 01fe5ae383715768e93e2b2c5f3c006a6212fb83.nq.gz
│   ├── 02ad5d7a10ad2a7bcfa3ec34d37f14f1570d0ab3.nq.gz
│   ├── 04792919aec7d594c126d2d2b08bddd2a1d12e77.nq.gz
│   ├── 04e064e9196b58d64737515c01fe2deb3237554e.nq.gz
│   ├── 0514103b577535587a65df76cf991e27208a6a8a.nq.gz
│   ├── 08c4bc08a1f841918068e4f41c655862b77b85f5.nq.gz
│   ├── 09a65aa36fd5178264b77a05b19bc187b289294a.nq.gz
│   ├── 0b7f72678541dd313bcac0e5d914f4cacc0d1971.nq.gz
│   ├── 0c9771a48d23b72eea7df630a27e621fcbbfcd0b.nq.gz
│   ├── 0cb5372d904acd6bf5d44c3f805da687735b611b.nq.gz
│   ├── 0db67edcb5952a9b56dfe514b4d934da090c4e65.nq.gz
│   ├── 0e12c75be5d96ac2d9f711275250b0345caf7800.nq.gz
│   ├── 0e7601f693554a1c24854ca0be67447b70b7ca16.nq.gz
│   ├── 1257ce13d5cfc414ef04f2642629d8fb3029f06a.nq.gz
│   ├── 12ceae60741c7726a6edb45bce86d31a79089493.nq.gz
│   ├── 167043c29d41dbaecb72db5e4559b7ec2042e333.nq.gz
│   ├── 182b5017dc23596a4ce4f823ced0b934944970ac.nq.gz
│   ├── 19129e315fe593965a2fdd50ec0d1253bcbd2ece.nq.gz
│   ├── 1913008c2c5fcaaee955429ac3a5a77705bf6ec9.nq.gz
│   ├── 1a89583ed596210951a9274a3c830b85936a15ea.nq.gz
│   ├── 1aca375cfb38351fbc4b4c4f94ea258b75c21a11.nq.gz
│   ├── 1b4b186afc590b7edf74e4cbe85573c21de74166.nq.gz
│   ├── 1ea8693c35c0e6f559bbb8bcfc8f4eb3f9620e0c.nq.gz
│   ├── 1fbef5a9bf9cd8d6606aa0741186de2599325b31.nq.gz
│   ├── 206b6eeb5b2930b0b67209ddee3f6234b79fe9ed.nq.gz
│   ├── 20d1e9dceea90e730220344671d4807203f5d9d8.nq.gz
│   ├── 217806da8a80af6a9b3de66764d5a4c6a0bbb432.nq.gz
│   ├── 217bee224c2b600c6c63cd81a3754bc6d29185c5.nq.gz
│   ├── 21d3d421643d124405a13a7dba2e369987d8dcef.nq.gz
│   ├── 241924ae316fdaaf2bd319f3a52ce117ccf20f25.nq.gz
│   ├── 262732e670d7dfdca05bb3278321dff65a8bd984.nq.gz
│   ├── 285662acb32892e926f05d2bef2306048edc825b.nq.gz
│   ├── 292b8b79ab51a0f6232762d6343b401e7bd51578.nq.gz
│   ├── 2c49aef1be5e87719bc7922aba4377abbfd57f9a.nq.gz
│   ├── 2c54b0d25037224d0d0292fe076df675e5449bf1.nq.gz
│   ├── 2c81ea9803fbc6bffabe1b1f6e6748702442c6b5.nq.gz
│   ├── 2e60b5067f0dc73d865b3e1fca195a0e1155e860.nq.gz
│   ├── 2efba0f4b6451e0a78557f2b959b348f0ee551ca.nq.gz
│   ├── 2fb32a0e63c9a140cc3acb351cd5ce6c3c75d501.nq.gz
│   ├── 3066f524cd8e3ef79f34ced3d305abcb0070e890.nq.gz
│   ├── 33e477080e12489b83cc7824c5b7fc3db88627e3.nq.gz
│   ├── 36ab422997acb014673ac025d0417603b406ee81.nq.gz
│   ├── 3a91911617dd716db6ab156fc1420a58dcd92748.nq.gz
│   ├── 3fdd5ff2d48804e4259b04bcc74bcb594bc89720.nq.gz
│   ├── 42729d54e7b679e43a0573d6391087c8413aeb34.nq.gz
│   ├── 44d951917294530a8bd5c6b49349bd65246fb0d3.nq.gz
│   ├── 4758c58d424a9be78121fb0bc4a9521899952572.nq.gz
│   ├── 477b2ab610646268297084fd40a59f9b4d3638ff.nq.gz
│   ├── 4938f10dab17800bd862c03780f95edddf5e8cb6.nq.gz
│   ├── 4e783057059b11f50e04c41358dedea719fe7269.nq.gz
│   ├── 4fe06a2a32c77345c8ef5c0f555b0bbb471587d2.nq.gz
│   ├── 5295454130d421f5b9e54bae4572b3615af696bf.nq.gz
│   ├── 529f93e74dce214a1f1118c0fb80f293b808ec58.nq.gz
│   ├── 5304739f5c4fc2c2c8ea8408c3f60eee48fb32ed.nq.gz
│   ├── 55f2133913ca4bf59c45d0b2a71706fe09395d66.nq.gz
│   ├── 5756eee2613c0bb664b5bab56313a91565c8acab.nq.gz
│   ├── 580603dd40c921a45ce2fd63d22ba83bd4c3b4ce.nq.gz
│   ├── 5a54baa14b468a0d4326161ce3025e72b915e4e6.nq.gz
│   ├── 5be251961acbdfa429cf087f94ad3b4c1719764e.nq.gz
│   ├── 5d3d20096844b17956ee75c1f44e8885d7eb0396.nq.gz
│   ├── 5f0eead1169fe5e7d661ff2bb2b9bede6967014b.nq.gz
│   ├── 61119745daaed8bc60013dc74f92b4310a1294ae.nq.gz
│   ├── 639fca89de8e63e8959972388c7721cee47aa44d.nq.gz
│   ├── 63d8090c626cea207b5cc1fbb022dd51881bbf99.nq.gz
│   ├── 647c1f0976fd7838c1b8fe0ba59888f088fb3c5d.nq.gz
│   ├── 647c541481a304c21b3c0f398213d5686b55955d.nq.gz
│   ├── 669eee35227061f8779644fa43dfe36f68d92544.nq.gz
│   ├── 66bd585678d27684877c23221ec42dc92fdd3c08.nq.gz
│   ├── 67d9a369e6dd5216d4b347cb9a22ede0b0d7e4c1.nq.gz
│   ├── 681f2668f5700f07a2ebe62cedd4effe98c35b48.nq.gz
│   ├── 689a129271cdee9dff23103a6b001d3897094b4a.nq.gz
│   ├── 69e8878830762ab5cbc325dd441957b43ee57dd8.nq.gz
│   ├── 6be1252b5d4a533f7a40f22d3fcc6d76f1e12704.nq.gz
│   ├── 6d1db9154331d4198faadda0a5432b6b1cc3a5e8.nq.gz
│   ├── 71602ed916cdcd071fbd5dccfee9944dcaf6cf99.nq.gz
│   ├── 71d21bbaa25d90048dcfd3094f7e0ba51445c83d.nq.gz
│   ├── 741022e79cd5026f7b25657ac1f1c68aea75d1b6.nq.gz
│   ├── 74ac1f017fdc00125b0022b2a815c4e96561453d.nq.gz
│   ├── 75316346a81cb3b3ba74442fb24583d6972a48ee.nq.gz
│   ├── 7675162f1742afbe0750d1c28fb3ac9695384a74.nq.gz
│   ├── 76922b002f40ea59c0bae18bb8765e4498590523.nq.gz
│   ├── 77487dcaac5f502ad1172a54a7047bcafbfbda4d.nq.gz
│   ├── 79703d6316617ea8df49384c47b1e235357ff1a9.nq.gz
│   ├── 7c52bdf2529ad82aacf17bb895d18bc228da19ec.nq.gz
│   ├── 7eb225d69671606a00dbbdea61abe9864185078f.nq.gz
│   ├── 7f62918bff66e0ca792bcff1614c069f0c3a69c1.nq.gz
│   ├── 81db8c247dd4d89c2bce7602046692575cf25ade.nq.gz
│   ├── 824f941f581d4c7f9e7762f9e70165eebfe6fec7.nq.gz
│   ├── 83c98cce62453a82b5241ec3e0f2634eed2392c9.nq.gz
│   ├── 84326b773361035e89898edc52fa69bd96371003.nq.gz
│   ├── 84a57ddff50a098bafaa44973830114fa150c3fa.nq.gz
│   ├── 85282bdf5cab8dafffedc8150a49c1473bcbb78f.nq.gz
│   ├── 87ebca5081704f14f3a697699be5cb94d4ab231c.nq.gz
│   ├── 87fadc121bba31b0efe9987162fb3bf995afbcb6.nq.gz
│   ├── 881edffea0f71553afee8f2a23ea996be6e3516a.nq.gz
│   ├── 88a1fdb2cf8b9f51ced8ca8ac6084c9f305c2f70.nq.gz
│   ├── 8c09675785c223f405b304268379b0d312f75d25.nq.gz
│   ├── 8c5f9eada8cc4d3ba6283bb0911fdbf0be2e7243.nq.gz
│   ├── 8e1c222b2ffc24e93a52378ad4d158dbc0d63c27.nq.gz
│   ├── 90d1cd1e2fb3050c4974ffc9b0302c75e8537ef7.nq.gz
│   ├── 917be7e4293d2b0f5a7cd6327addaab0f18c7ef1.nq.gz
│   ├── 91c24ec4a726497e218889190d533e754a8c1143.nq.gz
│   ├── 92254be1bf075a9a50c2ae308a8f0d7f2ee11627.nq.gz
│   ├── 94629ce6f5df60851017d35ef0091e75a2dd1193.nq.gz
│   ├── 99157cf3d105e07072d856b72475983836e2a48a.nq.gz
│   ├── 99cc44941966c6e81360b9fd203ef6c73eae5463.nq.gz
│   ├── 99d6085c422041cf2afbaa6478a7d16d020354ff.nq.gz
│   ├── 99f43218075c862efae82ffa6f30aa9dd44b527f.nq.gz
│   ├── 9b4c8d460beb67794d996e90acf5d74de2e1e8c8.nq.gz
│   ├── 9b6d63981cd709fccbdad95794fc2b4ce0f51887.nq.gz
│   ├── 9ca9a2b86bf519bef30484acf1ab946f3eb507c3.nq.gz
│   ├── 9e70ffda19223a878a2dbb2851d7092e776eb1c7.nq.gz
│   ├── a0264a222ac82d7271d755bbb40390961871601c.nq.gz
│   ├── a4613dee7977f09f21c34995e3335103fdb574f4.nq.gz
│   ├── a84de9160859983933c13628bae04decab6b9fa6.nq.gz
│   ├── a87f9d29fe1083d04f42b607307189d63181dd1a.nq.gz
│   ├── aa5e568ec279da4a3c292694ed066b2fde4e14b7.nq.gz
│   ├── aabd04a20221cbc23de769cd49101c71898e9ea2.nq.gz
│   ├── ab2b836cedac7fbf7d60bc3f4a5529aabf9451c1.nq.gz
│   ├── af10ec520f3e04f054226081992feae7d2295129.nq.gz
│   ├── af89c8ef4326921204264943a9e37ef4fc151ccd.nq.gz
│   ├── b706e527d77c0120707b693eda5303db35b658d3.nq.gz
│   ├── b8bf5262a0505c8b4bba7003a7cd1bd898fed789.nq.gz
│   ├── b8fe1db5049a23a0c772a465e48932f3de7d5d65.nq.gz
│   ├── bcb582abbde53837d3a826567c2efaf4787ffa37.nq.gz
│   ├── be58ad504d9f4f2565775370b63d9c086cab68c8.nq.gz
│   ├── c0a18fda9cb33f42dd2813da4c18777f89e5f9fc.nq.gz
│   ├── c0c2fcd3ad0defe7c8f88988f597fbd3fdc786ad.nq.gz
│   ├── c28cc98e99d9877eb6c24468f71f9e777f7f2937.nq.gz
│   ├── c3106d9a6e6c86cb306c27ee07c60a99a205c7ee.nq.gz
│   ├── c3f82daf2971dd4a8115d6b90ebe865cc1b1cf29.nq.gz
│   ├── c447fb3fccbff6d870b5014767cba27191814b0d.nq.gz
│   ├── c56fd1d8ab836b96906b75faa35eaf1c14fdcb80.nq.gz
│   ├── c69932daae754dc60100d839325d3dd75d0f80f3.nq.gz
│   ├── c8ed5651658696b462c7e91ae28d2b44210ce0cd.nq.gz
│   ├── c99ab51cc571695ddbb293156f3380e0c5896dfb.nq.gz
│   ├── ca7442120798eaff9d2cd621562a5a4b11da3629.nq.gz
│   ├── cb217eda3595475f9d478e2e304aa306122989a8.nq.gz
│   ├── cc6b0e9f68f95f8a5a26f47fa9fddb06f3625e7a.nq.gz
│   ├── cf38b8938940f130d458521cf52e92f35fa9cb93.nq.gz
│   ├── cfe027599516f3d6c2165a1858d50d7810dc9dba.nq.gz
│   ├── d012e50c057e9bbe7281db8794bf8258f4305cfa.nq.gz
│   ├── d043192f143b7739d43d1b36478c1ec0b58de376.nq.gz
│   ├── d053472dd58b3ca0593e9cb9bab33ac4e0eb2320.nq.gz
│   ├── d1220c90cfb1142490e6529ba900c94ac7a1305f.nq.gz
│   ├── d16501535939606a172ff61d53fe3cca652c50b9.nq.gz
│   ├── d32c0e09a9f5043491217bc035863524c8ee5bcf.nq.gz
│   ├── d4c6ae0d76c9ac0c10c93062e5ff9cec277b07cd.nq.gz
│   ├── d544d33a7e93cb8e88a0641d3666398c3d515759.nq.gz
│   ├── d61a0e9e81cebb029f913bfb140f9367b7254ee1.nq.gz
│   ├── d62bfc0ecd5216c875e7694fd24eeed1e7ce3f2e.nq.gz
│   ├── d640909f5414535b4dff87a30f12f45c8395575a.nq.gz
│   ├── d735ccf2ebc765549850b90fbc7a6f5c10acd851.nq.gz
│   ├── da9ee8f4e4404e5acf0af1045b6045534dbbfe06.nq.gz
│   ├── dbb1bf534ec72246c07ee57bbd8759a5e509d9e6.nq.gz
│   ├── e2bf3d11b94f8ef822020ab4a242715257bb8323.nq.gz
│   ├── e3d9c88c80c7c06b02af63a220d94f0264d88697.nq.gz
│   ├── e4e252d766d668e27bbd39bb6b7c722d7c1ccc98.nq.gz
│   ├── e6c47b9b051d9bdeb19eb26c362ff97907e9c69f.nq.gz
│   ├── e6d08dc20cf20bc84e954762375ece363452c616.nq.gz
│   ├── e7a4ee9dc2bac6919d400cc20ba0ddcf75389b34.nq.gz
│   ├── e9522153976da589c8b66b0d44da1596cb410749.nq.gz
│   ├── e9d1bc5e0e544f19b5d937e05e639b768ad61188.nq.gz
│   ├── eac6624aa709fdc43ccaef188574f6f6b3d88e01.nq.gz
│   ├── ec75f2d3e28a01220baa4c64c71f93360217c45f.nq.gz
│   ├── edb24b1dc3324d6938191b41d7003db4489b7f90.nq.gz
│   ├── eeb9b725f32fde237cf328df68760a033c52d8e9.nq.gz
│   ├── f21d26eccec7d4120affe30f8abad6d29a8e4d4c.nq.gz
│   ├── f4327d752e11d0cc0171525c1cd19c0c750f940e.nq.gz
│   ├── f80c2359c6b82f127be15e65850044fa5fe4007b.nq.gz
│   ├── ff999e9d04d7fa3a725621912399df35f450c845.nq.gz
│   └── fff1ab4131f9f4a1ef317d6ea6b0bd435551f83f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 281055e7716ef0415a8826972471331989ede58c.nq.gz
├── filetree
│   ├── 281055e7716ef0415a8826972471331989ede58c.nq.gz
│   └── 5993c2e42bdf17c5f03e6360da51bc707fcee460.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 184 files
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

[npm/node-semver](https://github.com/npm/node-semver)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
