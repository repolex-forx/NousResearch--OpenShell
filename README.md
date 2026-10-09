# Repolex Knowledge Graph of NousResearch/OpenShell

RDF knowledge graph data for [NousResearch/OpenShell](https://github.com/NousResearch/OpenShell), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/OpenShell
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 40e9bf6feb7202625580e50863ad7abf456f97af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 40e9bf6feb7202625580e50863ad7abf456f97af
│           └── chunk-001.nq.gz
└── blob
    ├── 001255ceaea4bbc57cd62a4b60a2d46d6b484538.nq.gz
    ├── 0017b737f1d5ff02c7a5ab726af645ab7666561e.nq.gz
    ├── 01ad4941e663837808f9faa01ea03bb967fd241e.nq.gz
    ├── 01b5c2372026025f8199f07d9a4160e95ef3fd98.nq.gz
    ├── 01ff303477895e03660eb9053d86a26f9f85bc4e.nq.gz
    ├── 0248c6593a6296fb6a24f19607adc148d46739ea.nq.gz
    ├── 02f487050db2d93207a9d38f2b4de1d878d59386.nq.gz
    ├── 03b7dc7bd266f972f6c868bb76762f34fbcfe597.nq.gz
    ├── 04850d9d6b02ed5a4af3b25e426783bd4d70aa63.nq.gz
    ├── 05011e5557f92c03f7289ae3b6a500221ee26349.nq.gz
    ├── 055a093175f95299a5c8b68e64ebc325447dc923.nq.gz
    ├── 06677c16c4ab765ac3fc2e2f25608d17e2e4f286.nq.gz
    ├── 069ce2048015214e05acf2052503b6689284bee8.nq.gz
    ├── 0741998b75f6c423d5fdc59f3dafde47992759ad.nq.gz
    ├── 07459c2380fb12212680e3383f8cbfd983de837b.nq.gz
    ├── 0827fa0d0192b18b49d125b5a1c31bc936473d7e.nq.gz
    ├── 084a013d94ccbb3014b48f0ba42250c06fc8546d.nq.gz
    ├── 08b062d2e5f9cb5f7bccba6c176768c76df4cf61.nq.gz
    ├── 096a35d1f93a9837f2af9ffbe99affee3b6ed6bc.nq.gz
    ├── 09bd88c0591c07475ec8c84e21119a6dd8b9704b.nq.gz
    ├── 09ced971b0f9afaec3c8adc1c88eb19b6882abbc.nq.gz
    ├── 09fe2b76814f0533a8aca05edac08af9f624de67.nq.gz
    ├── 0aa48c9f76121ab5b51516c2accafa449763176d.nq.gz
    ├── 0abc24b4367a92d7b6fcafa41fb99f07a9bf2a4a.nq.gz
    ├── 0ad6eee63940391f742d329b68ebafa93ed95f78.nq.gz
    ├── 0aeeca9b1aa01c418eb7c2d1c3661ac841b32813.nq.gz
    ├── 0b51666e0c710e82d2c969f8ec80f062f219c5b4.nq.gz
    ├── 0c6fa09eeb6cc49aa77252cac51c6199de758e0c.nq.gz
    ├── 0c802e63cac41bce23d5290e0104b3568d4f3918.nq.gz
    ├── 0d2cb17da8da31ecfa6e99264da14e16e860d6c8.nq.gz
    ├── 0d5eab24640275604d3392af4f561facb7ca58ca.nq.gz
    ├── 0d9a4407ebc9522b1568e45233f184a456f91936.nq.gz
    ├── 0dbe3941428fd6be0b6a77cee364e5399b370f3e.nq.gz
    ├── 0dd3cd4e5c21f850efefaac41e08fefc34c45b9b.nq.gz
    ├── 0e0fb2b122c31e1e4f743668f549894bb8cbb4c2.nq.gz
    ├── 0e4aa4b763051a52be79dc85663ba2017bd0d814.nq.gz
    ├── 0eab117824f0927ab73b201bbd59d0b9bff4cca9.nq.gz
    ├── 0ef1e0355ec780ef2b86ea32d97d742be8fef35e.nq.gz
    ├── 0f33c685f43d7b602f2c6e7857f29b7455d19aa9.nq.gz
    ├── 0f944e09f2027dec2b9420a495a2b443ca2a0540.nq.gz
    ├── 0f9a96e6bb2b12a47438920e169c2509dab99b04.nq.gz
    ├── 0ffc8e15c2cedcd409e20151d611d9d1f4eea182.nq.gz
    ├── 1017607154936b36c995a429f0939425827e0d2c.nq.gz
    ├── 10d2d4d746e9a723b00b83692e165c0217b235af.nq.gz
    ├── 10fd3de0d22325185674e0aa524cb82e463ed486.nq.gz
    ├── 110f777e917b203177319db5584d281fef31d885.nq.gz
    ├── 144bc750849afd504faeccd60a2c8cc1ce44ba5e.nq.gz
    ├── 148e47e10e621134068f0085b97e3e24402bddae.nq.gz
    ├── 14cc93ba319abe7a33b3f5d776ecdfbfced93746.nq.gz
    ├── 15063d2c7f202eb75a3c1f17c27b95565672f06b.nq.gz
    ├── 1517c0577b408e35ce3b39c052242993c48e2429.nq.gz
    ├── 1540401844f1fafe19e02b7713769f3140e8f801.nq.gz
    ├── 154f3308ef21c3e4c10423100e3a4115248b4948.nq.gz
    ├── 1746547ef67dec0a8d0cecb7e02d5406bf92d604.nq.gz
    ├── 175f31afc869afc8bb23978f6c94f4f3dfa8cfa5.nq.gz
    ├── 17d695a4337a50fa825f2adc0fd6db4a05923664.nq.gz
    ├── 17f9bcc3d74d4268459a2f4d8a006f7491a1b1ab.nq.gz
    ├── 192b57b6cefc47e15a776be6d6c0618ce6fcb054.nq.gz
    ├── 1957c5b87d5030963d11ab974e0bbaed3f935c59.nq.gz
    ├── 1995ab9d7b07cf9a6c3f1170c469d09ee83d3010.nq.gz
    ├── 1a83e96d1a92d21ba2e61198ea312fadc083090a.nq.gz
    ├── 1be05e81e3c2020d21873e2a04a23a6139376692.nq.gz
    ├── 1be202367174d6832f5422ca1e356aaa85667fb6.nq.gz
    ├── 1c514f370fec3f320f9c60aec798941a4bc3f79a.nq.gz
    ├── 1cb0ca70ac48ce42fc6e08b78cb4dd1dc5cba102.nq.gz
    ├── 1cb686a31181bf4df4d9eeaee2470b357debd769.nq.gz
    ├── 1cc7716dcb7f248129cd4ac4ac39348e22fee9d0.nq.gz
    ├── 1d756117cfec7946a36410e4ce6ec862f120af68.nq.gz
    ├── 1e1f5c9efa895aecd677c78325aaba867d720b35.nq.gz
    ├── 1e53da7fbe691b2ae48a58b849ba09c7bb4de88f.nq.gz
    ├── 1f03f8e94c12414fce1fb55c7ecc4981c4657713.nq.gz
    ├── 1f7022ef8e359c50871faafc316ec89afab33707.nq.gz
    ├── 1fcaf322ac3ee501c0a01b751a97efe81060a383.nq.gz
    ├── 1fdd49b05ac87d152bbd3b563ac7315db739d8c3.nq.gz
    ├── 2053ba4b2b3a42f57d97221d40c4ed008d274c3a.nq.gz
    ├── 216fba20057178a6c35df13b80c4d6a47ab4a5e2.nq.gz
    ├── 22f08434d6aef03184d6c50746067d130b84dde7.nq.gz
    ├── 23519e5662def3d2495db226e109bb6ba58ed69e.nq.gz
    ├── 2399368fc8d6b27cc64abc5cf0ea8c5d1ad0a42f.nq.gz
    ├── 256f4db9d689495ec7cba6627a0bd2f8675eebc5.nq.gz
    ├── 26a77e9da6a51c3dfffb2a40ea482acd764ea2f2.nq.gz
    ├── 26f87b916637732e4958f2f29c898250347ac08d.nq.gz
    ├── 27207a6aef16b2cedbf635b3252edb9fed74b17e.nq.gz
    ├── 2837168baef5cef9791e0a62a96576e1167b2f97.nq.gz
    ├── 2852bfa4383eaa4d413b209cd434b736875057b7.nq.gz
    ├── 28e6b201b59f071d6d0b5509d645ea7d5926b12f.nq.gz
    ├── 296a22f2051f6c2f69f91b13afde5f53f07c08b6.nq.gz
    ├── 29779d9086dc3ddc487f90d66e946cb8660ef797.nq.gz
    ├── 297face213a1705edf58fc725a4d7ec8f8358299.nq.gz
    ├── 2aa793d20e94430c02456f5d0c26849ed6f0548e.nq.gz
    ├── 2b4db1caf45750b6ae88b3761b9ccd912e08a1e7.nq.gz
    ├── 2bb3c7d088d6d13175c4ad7e230b06c89cb7c7fa.nq.gz
    ├── 2c3480cbe64f0f2ca66a4d5710c2442629229785.nq.gz
    ├── 2c5a94467b5b374759f83719e7f22d53319231be.nq.gz
    ├── 2c87dd4182341b8027e924477cde6ce95cfbae4d.nq.gz
    ├── 2c8c0cc769bd5de2f6f1eeea7abf7f075faa21cf.nq.gz
    ├── 2cd36202394630d43797997558c1beab42daa29f.nq.gz
    ├── 2d04569ba7df63bca00deaa8b63bfe59e930208c.nq.gz
    ├── 2e515757d239878388e97e162c90b73b06bc0317.nq.gz
    ├── 2e758f5e06d9187bcb594d51bf5d957ab8aeb770.nq.gz
    ├── 2f26c7bfba21e76f10b1f49539150122228d648f.nq.gz
    ├── 2f7737d961683300569a1858881dec682d9f8677.nq.gz
    ├── 2f98784583d9865cfd4b4fa5c37de9c1870a3da7.nq.gz
    ├── 319800c0813809c906629643ba487e76adcf8604.nq.gz
    ├── 320c00efb74f92dd14783fbdec45b8d37d582a49.nq.gz
    ├── 336d46c3e7446586abc70033f70410b5f763808f.nq.gz
    ├── 33fab9a78ca51649620972aad157cb6e765eab56.nq.gz
    ├── 35ef222c1f047554bfd641c30b6038f3f3767c09.nq.gz
    ├── 368716ef96a3c366fe0255ba1f07fce6e8b4cc49.nq.gz
    ├── 37a0dca85850ada4b97b3d65d2e1e1b20e7c9ac3.nq.gz
    ├── 37d11f0c3e9e850385a51300dae44183405e48fd.nq.gz
    ├── 395b1897a9c3e2fbc4500208d6564c4d2713ea18.nq.gz
    ├── 39d3e1ced0c1bdb1f67bb29988ff3ecff444efc4.nq.gz
    ├── 39f6411c43aeba5cba7bc9bf5125e5b11780dafe.nq.gz
    ├── 3a7976273dbc20ab91dd4f550c47f6afd0933697.nq.gz
    ├── 3acd52f828b7631253c27ea184a5848118855bfe.nq.gz
    ├── 3ace22421cf2f9e8b7c3677e1d40ba8c6ccff85c.nq.gz
    ├── 3c26f806116b340a0c476b50f48d4db8db363da0.nq.gz
    ├── 3c850f45a15d3e69be27f7f6f338b8a373033252.nq.gz
    ├── 3cd00d7b8aee4741c51193cf07cc03608b0fa3e5.nq.gz
    ├── 3cdf9cd3b63bda39ea703902d5a1dce380bebc79.nq.gz
    ├── 3cf9ddfc67244b6ccdf79dc562fcd205cd76d0fb.nq.gz
    ├── 3cfdf3f54173b82e62e3c15111b2ec6a03ab130d.nq.gz
    ├── 3d2e6f7827287f7f2aa2636f1df1b20593595374.nq.gz
    ├── 3d31f6e9f690ec25974507c9bfadb057980a4fab.nq.gz
    ├── 3d3fbf4b6129237baaedbf959f3c157b9ea8da4e.nq.gz
    ├── 3ee7799d7974855edb0017a4a15af26fc5dc42e8.nq.gz
    ├── 3f6aae8c35ad2df314a627001810671a1fbe14a2.nq.gz
    ├── 414bb6e8a67e3853d14134dc9649efd888b04596.nq.gz
    ├── 416adef6667ced527f277c0e1643a467d77d0d45.nq.gz
    ├── 417bdb6c2967476d6c3d4faae4415e180aadebb8.nq.gz
    ├── 41eda0e0a83429e874544b507977c3a56f5a489f.nq.gz
    ├── 41f9ed6c0f6ccb4f79e64829a2cb0cf49327d87e.nq.gz
    ├── 43293e73cc8242c8625fc980011c950f2c9a29f2.nq.gz
    ├── 43a2f96c510fca6da25b099d8bad6e8b8b94006b.nq.gz
    ├── 43ae6a937057998493e357a269d88fb80505f8a5.nq.gz
    ├── 440703af570c1e4fc114983fd72e917ebd916357.nq.gz
    ├── 44305e2f87d53931738d513de7305fda7697558b.nq.gz
    ├── 452b6aeb5ebbe7659f0b57fc8fe06311e3142dad.nq.gz
    ├── 458bab0e435fd2c5174dc22bd35b161e2348a93c.nq.gz
    ├── 4609e0cc51d2840819ece6cd06e8aaad2a1d2a86.nq.gz
    ├── 4901d19754d6e4feff85e4efb9e6d54b780fa999.nq.gz
    ├── 49809f95bac3cf462c2b675d73d5765db95087b2.nq.gz
    ├── 49b8cb0549267a8176467738b172a63d86eff436.nq.gz
    ├── 4a85332c6b5e15c9605dbd04893d7ee100423350.nq.gz
    ├── 4c42fb4a1f65e59f8ace68508f8dac0c206a60a4.nq.gz
    ├── 4cbd76b501532763869759930bdcf915f8b7aded.nq.gz
    ├── 4cd277af8c6cda7c2d2ff8dea6f68afd00c01333.nq.gz
    ├── 4cfadb8aca153af27c27cc359bf9ac31775add5b.nq.gz
    ├── 4cfbdc7f05f17ca41bf53589524bb0f9564d1891.nq.gz
    ├── 4d4a6b64c79daae15b8a7f9b91bfa8e341c4db0a.nq.gz
    ├── 4dc074eb73824b605f94e7d08f2f130f47e4489f.nq.gz
    ├── 4e5781a590398028e09098415cbd4d4acb1b8bf6.nq.gz
    ├── 4e73a61be3ba5a3e0ea848b29d53024f62a94bfd.nq.gz
    ├── 4e89deef7b0c0ab8a8f1d53087ca1c784a181f40.nq.gz
    ├── 505250c1d85a4da747899eab9148fa424bf4027c.nq.gz
    ├── 510b3d92db0c88244bb898b38e8e6e31599d2ca1.nq.gz
    ├── 536513ccd8741317e6cb75b42457b1700cea34d5.nq.gz
    ├── 53b0ac27d54b2c59d15422dded251dbcbb892b42.nq.gz
    ├── 54149fe83df8c7dd106644c8177020a28ed9b437.nq.gz
    ├── 548b86d178c16188316c10402e2f04a490ab32e7.nq.gz
    ├── 54a7354c86fa12d14df866cfc86efe7e3d4c6b5d.nq.gz
    ├── 56281bea1cb3581720597479bcd75dbb5f005d4a.nq.gz
    ├── 569c333887c7f2738c2bf811462e662403b1a397.nq.gz
    ├── 570fce660cd7c695a0f8cc641525dbcbbd792a7a.nq.gz
    ├── 576b30e385314ee9176a807391fb5a3d97447e52.nq.gz
    ├── 57e8fbf5156bd0737d89394b602a15216f0c20ef.nq.gz
    ├── 58d98e300c9ef4ba66fa488bcf2ec26bd24e69c0.nq.gz
    ├── 5974268fa3f1074250e0033ed8dcf9257219f58f.nq.gz
    ├── 5b0558b54c428bac55dc98a805c863c63ec8219a.nq.gz
    ├── 5b72fe3f76358383d4652d2d9a2a79f0c5527e13.nq.gz
    ├── 5ba44b1ec0ccecf84271d791835713b610db4c46.nq.gz
    ├── 5cd36693b96cfe0f3821e9de3e468e101a18726c.nq.gz
    ├── 5d04239bf58124b9ba7136afaa5abd18149a1c62.nq.gz
    ├── 5d62dde0baea648aa12d44f89bbc71c3c6a82b04.nq.gz
    ├── 5e247dc77211389f786569de5f86af30011fee51.nq.gz
    ├── 5fd055036dbe2472b01da207a8a860c52394346e.nq.gz
    ├── 614b3b473888e9d7d7b8cf06757489000e6bac36.nq.gz
    ├── 61aa025be2581a852d27abb34aaed5371dc8cc2b.nq.gz
    ├── 61cdf4e3c68c99928216640b0a7b62f040d625d5.nq.gz
    ├── 621d35f8e754835ec5aa48dca75f32c91afbc9a0.nq.gz
    ├── 62985c1dd9bddf6a1f415efc206747f8dcdf41ea.nq.gz
    ├── 62fe5a4618fcf83b41787aed94d08a84cdf38dd6.nq.gz
    ├── 630d1eecd1b0e21432f81680952496fd47e34e7a.nq.gz
    ├── 6325ebf9c4616e99ee96d86654ca70a7e0fdbddd.nq.gz
    ├── 6389c728e1c89b9fa959b0acc2af3a13cb5c4482.nq.gz
    ├── 63cfb79d6dd050902d59d33221b6253cfc29488b.nq.gz
    ├── 63f83b874ab9fa350fab4d45613382318ef01e92.nq.gz
    ├── 63f8dd5ab681c4e2808c388ad93b4610c9f76a5b.nq.gz
    ├── 64112ff4ba553c8a9e8c6015cda2c635b321adc1.nq.gz
    ├── 65305af39aac074887e8d6f83f0abedc4c73c131.nq.gz
    ├── 65c5f0034c337ebd734a344826f0b76e48cfbea8.nq.gz
    ├── 660509d9e5d41ca74b322ed2ec07561b7ea7eea1.nq.gz
    ├── 66ae54d348d0d29f010dee5126cdc056e4769cfc.nq.gz
    ├── 66daac6ee1aed7dd34e21ba559547742e7500d41.nq.gz
    ├── 68108389ee935110d1318f8ac01383f6f62cd266.nq.gz
    ├── 68c3a86d0ef1f1480f96e9e25050511d621a9ef8.nq.gz
    └── 69214ce7ffb906d05c78ba9449ad5924e6cef7b8.nq.gz

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

[NousResearch/OpenShell](https://github.com/NousResearch/OpenShell)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
