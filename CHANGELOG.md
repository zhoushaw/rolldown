## 0.0.5 (2024-03-08)


### Bug Fixes

* `rolldown` node api should create graph ([#302](https://github.com/rolldown-rs/rolldown/issues/302)) ([c7749ba](https://github.com/rolldown-rs/rolldown/commit/c7749bacf50ef8a0ef7e068a1a01a790ee56c987))
* A `Symbol` should only be declared in one chunk ([#338](https://github.com/rolldown-rs/rolldown/issues/338)) ([340cd27](https://github.com/rolldown-rs/rolldown/commit/340cd2738605010b8facc0bad64d338d0aa26e8c))
* add identifier for export default function without identifier ([#81](https://github.com/rolldown-rs/rolldown/issues/81)) ([e84cde7](https://github.com/rolldown-rs/rolldown/commit/e84cde7d3baefd590c585ae400c627ab5837a107))
* add stmt info declare symbol for resolution found symbol ([#91](https://github.com/rolldown-rs/rolldown/issues/91)) ([50e191a](https://github.com/rolldown-rs/rolldown/commit/50e191a6e33bb8ef160e0bd53a06b0bee19e4471))
* allow cjs to be both entry and dependency ([#336](https://github.com/rolldown-rs/rolldown/issues/336)) ([d53155b](https://github.com/rolldown-rs/rolldown/commit/d53155b18a258447f352ea7d39264410888b9d9a))
* async_scope_block_on ([#210](https://github.com/rolldown-rs/rolldown/issues/210)) ([51f1be1](https://github.com/rolldown-rs/rolldown/commit/51f1be1c0c9c02c3416f18bbe493f644ccd265fe))
* bump to `oxc@0.7` ([1af4b86](https://github.com/rolldown-rs/rolldown/commit/1af4b8688db9223711ef02ea6440f69ed3564174))
* ci release ([#428](https://github.com/rolldown-rs/rolldown/issues/428)) ([483e533](https://github.com/rolldown-rs/rolldown/commit/483e533b6471b79a7aab08d7a63dfa98079a8013))
* clean up render exports from external module ([#394](https://github.com/rolldown-rs/rolldown/issues/394)) ([e51a69a](https://github.com/rolldown-rs/rolldown/commit/e51a69aec7ae1d599f7a20adc1d325ef6103b752))
* clippy ([#4](https://github.com/rolldown-rs/rolldown/issues/4)) ([f028cff](https://github.com/rolldown-rs/rolldown/commit/f028cffb7f5de19f182127d79684285107b16ff0))
* conflict between imported and local binding ([#356](https://github.com/rolldown-rs/rolldown/issues/356)) ([7387e35](https://github.com/rolldown-rs/rolldown/commit/7387e3586be27bbdd37a470b8e0eca6a6b8ba52b)), closes [#355](https://github.com/rolldown-rs/rolldown/issues/355)
* deconflict export named declaration ([#386](https://github.com/rolldown-rs/rolldown/issues/386)) ([21aaa36](https://github.com/rolldown-rs/rolldown/commit/21aaa360d7f8db566b8d9ab8508a57df30b2340e))
* deconflict for duplicate canonical names ([#365](https://github.com/rolldown-rs/rolldown/issues/365)) ([eebea46](https://github.com/rolldown-rs/rolldown/commit/eebea46c4db084f8ddda99d8998c3bc9024db127)), closes [#364](https://github.com/rolldown-rs/rolldown/issues/364)
* defonflict export default function ([#385](https://github.com/rolldown-rs/rolldown/issues/385)) ([518aa5f](https://github.com/rolldown-rs/rolldown/commit/518aa5fc655508d2653b7fbd0a2f6ef1e266299c))
* determine call expression result is used to render require call ([#144](https://github.com/rolldown-rs/rolldown/issues/144)) ([85224ea](https://github.com/rolldown-rs/rolldown/commit/85224ea21a572a96f510efda667aa2859e61201a))
* don't rename symbols that show many times. Fixes [#419](https://github.com/rolldown-rs/rolldown/issues/419) ([f985755](https://github.com/rolldown-rs/rolldown/commit/f9857554ecce8d7c5ad0b7b41feee6d1a53a5107))
* duplicate dynamic entries ([#380](https://github.com/rolldown-rs/rolldown/issues/380)) ([6067e74](https://github.com/rolldown-rs/rolldown/commit/6067e7472831745701a44337c6ff7ee6fdc0740d))
* dynamic import as entry ([#366](https://github.com/rolldown-rs/rolldown/issues/366)) ([8d33829](https://github.com/rolldown-rs/rolldown/commit/8d33829b92c2356f6fc1643facc6d0f5d703ab0d))
* dynamic import chunk is_entry should be false ([#361](https://github.com/rolldown-rs/rolldown/issues/361)) ([6f2b75a](https://github.com/rolldown-rs/rolldown/commit/6f2b75a996e3f3dcdf4b89d7ea8b80ebae66e826))
* ensure valid output for import the same cjs twice ([#323](https://github.com/rolldown-rs/rolldown/issues/323)) ([87b5000](https://github.com/rolldown-rs/rolldown/commit/87b50002d5d08df990010000304ef5bac7ec04ca))
* export rolldown compat types ([#337](https://github.com/rolldown-rs/rolldown/issues/337)) ([3efa4fd](https://github.com/rolldown-rs/rolldown/commit/3efa4fd8117533879defeca4b5da2fd5a506affb))
* generate local symbol for esm import cjs instead of reference cjs namespace symbol ([#141](https://github.com/rolldown-rs/rolldown/issues/141)) ([5c53415](https://github.com/rolldown-rs/rolldown/commit/5c534155ca9a9963bedd46a202201c2dc844a5bb))
* hoist  statements. Fixes [#418](https://github.com/rolldown-rs/rolldown/issues/418) ([276bbae](https://github.com/rolldown-rs/rolldown/commit/276bbae7130010f34f184dee032c3eae5e42a28b))
* hoisted import declaration ([#80](https://github.com/rolldown-rs/rolldown/issues/80)) ([569409d](https://github.com/rolldown-rs/rolldown/commit/569409d3a15ac5aa39619d119010eff7adc64591))
* hoisted top level scope declaration for wrapped esm ([#387](https://github.com/rolldown-rs/rolldown/issues/387)) ([ec20c03](https://github.com/rolldown-rs/rolldown/commit/ec20c0311a84b0aff7e3e1cc84893f0acc954a84))
* invalid output for conflict global and local name ([#359](https://github.com/rolldown-rs/rolldown/issues/359)) ([d464eee](https://github.com/rolldown-rs/rolldown/commit/d464eeef1b9062effc96d1cce1458fe90c8ea803))
* keep the context of function call while deconflict symbols ([7401a05](https://github.com/rolldown-rs/rolldown/commit/7401a056127646f56a7f85407ce40fad2bbe2c76))
* make sure namespace name is valid identifier ([#107](https://github.com/rolldown-rs/rolldown/issues/107)) ([d3c81aa](https://github.com/rolldown-rs/rolldown/commit/d3c81aa7b6adce7db991475ea29d045cd406d8a7))
* module execute order ([#148](https://github.com/rolldown-rs/rolldown/issues/148)) ([7ef1c20](https://github.com/rolldown-rs/rolldown/commit/7ef1c2037ffb2d3d0ad4aedaf31643d232061e3d))
* more meaningful chunk filename ([#381](https://github.com/rolldown-rs/rolldown/issues/381)) ([47b4b6d](https://github.com/rolldown-rs/rolldown/commit/47b4b6d449d8b77ed34f9c5318172d9f4fb6ae3f)), closes [#49](https://github.com/rolldown-rs/rolldown/issues/49)
* only import needed runtime symbols ([#324](https://github.com/rolldown-rs/rolldown/issues/324)) ([51db31f](https://github.com/rolldown-rs/rolldown/commit/51db31fe90a01519a558f36948ae574171850714)), closes [/github.com/rolldown-rs/rolldown/pull/319#discussion_r1398069930](https://github.com//github.com/rolldown-rs/rolldown/pull/319/issues/discussion_r1398069930)
* only pull out `__export()` when it's needed ([670dbb6](https://github.com/rolldown-rs/rolldown/commit/670dbb6b99776a87d984c837e006b9758f813483))
* **packages/core:** allow empty `OutputOptions.format` ([#224](https://github.com/rolldown-rs/rolldown/issues/224)) ([0a79036](https://github.com/rolldown-rs/rolldown/commit/0a79036e4730c6f9d6e0c2a78fdcca1f66009c83))
* **packages/core:** make `outputOptions` optional ([#223](https://github.com/rolldown-rs/rolldown/issues/223)) ([b2439b1](https://github.com/rolldown-rs/rolldown/commit/b2439b10d4c9217b99ba5912c5508eea9502bda3))
* playground panic ([#263](https://github.com/rolldown-rs/rolldown/issues/263)) ([f97bea0](https://github.com/rolldown-rs/rolldown/commit/f97bea0d062c0fb77a08d0900d5ed5a495658bf6))
* reexport star from local named export ([#290](https://github.com/rolldown-rs/rolldown/issues/290)) ([77c77ec](https://github.com/rolldown-rs/rolldown/commit/77c77ecbd90e55ce772923438a4e64ec65aaa725))
* rename in `SimpleAssignmentTarget` ([1d24efc](https://github.com/rolldown-rs/rolldown/commit/1d24efc36cf6672781d00f5039d06d1ce689f2c1))
* rewrite `AssignmentTargetProperty` ([5605fc2](https://github.com/rolldown-rs/rolldown/commit/5605fc23f73c9fbc38c4ca2daecee38fb36e735c))
* rewrite object shorthand property reference ([#384](https://github.com/rolldown-rs/rolldown/issues/384)) ([9f3332b](https://github.com/rolldown-rs/rolldown/commit/9f3332b5ad8349f3c1220870cd9301184e26a727))
* rewrite unresolved symbol reference callee to indirect call ([#94](https://github.com/rolldown-rs/rolldown/issues/94)) ([6284028](https://github.com/rolldown-rs/rolldown/commit/6284028a2508bb8d83d2496c0f0ceec2fb037553))
* runtime module should always be the first to be executed ([#116](https://github.com/rolldown-rs/rolldown/issues/116)) ([883168f](https://github.com/rolldown-rs/rolldown/commit/883168f884b7fae7f541e9ad12bd02f91002c0de))
* **rust:** remove `RUNTIME_PATH` ([#274](https://github.com/rolldown-rs/rolldown/issues/274)) ([c93a2fb](https://github.com/rolldown-rs/rolldown/commit/c93a2fb3725a0ebf6f792aa9191a366ceae4fcb9))
* should correctly render `export default xxx` ([#377](https://github.com/rolldown-rs/rolldown/issues/377)) ([7fa642f](https://github.com/rolldown-rs/rolldown/commit/7fa642f01ce48dd014a0b5ead66f0170b2d56908))
* should rewrite `export default import(...)` correctly ([#220](https://github.com/rolldown-rs/rolldown/issues/220)) ([cd8ad5e](https://github.com/rolldown-rs/rolldown/commit/cd8ad5ec04146b41b128033a74d238e23734ef64))
* stable generated exports ([#313](https://github.com/rolldown-rs/rolldown/issues/313)) ([526a04b](https://github.com/rolldown-rs/rolldown/commit/526a04be7caa110ec5723f0d27add11c71f7c253))
* support browser filed false value ([#395](https://github.com/rolldown-rs/rolldown/issues/395)) ([c3a82a4](https://github.com/rolldown-rs/rolldown/commit/c3a82a4b4e4c649d86bd3450fa0156b764db5278))
* top level await fix compile error ([#226](https://github.com/rolldown-rs/rolldown/issues/226)) ([ac60fdf](https://github.com/rolldown-rs/rolldown/commit/ac60fdf03ec566e2b219e7c06dcfce85a66588ea))
* use the same `Resolver` everywhere ([#253](https://github.com/rolldown-rs/rolldown/issues/253)) ([cbcee58](https://github.com/rolldown-rs/rolldown/commit/cbcee5851c54bdfde8b56930d496b151a2d0846a))
* using vec to keep input options order ([#217](https://github.com/rolldown-rs/rolldown/issues/217)) ([4e4f20a](https://github.com/rolldown-rs/rolldown/commit/4e4f20aafb7278cc66ac0b1add0bda19b4ff95b4))
* wrapped require module ([#79](https://github.com/rolldown-rs/rolldown/issues/79)) ([ee9a682](https://github.com/rolldown-rs/rolldown/commit/ee9a682ada40a218ea1e01516ac2e65eb083c16d))


### Features

* add ([#124](https://github.com/rolldown-rs/rolldown/issues/124)) ([ca07f3e](https://github.com/rolldown-rs/rolldown/commit/ca07f3ee579c4e245ec1dd792f8e35618740280b))
* add `ChunkRenderReturn` struct to make code clear ([87f02c2](https://github.com/rolldown-rs/rolldown/commit/87f02c2e819dff496797fb3cc8b8e86708fec988))
* add `ExportsKind::None` ([#315](https://github.com/rolldown-rs/rolldown/issues/315)) ([efdd252](https://github.com/rolldown-rs/rolldown/commit/efdd2529853f7cf7d30fcd88a1245073908a6065))
* add `generateBundle` hook ([#403](https://github.com/rolldown-rs/rolldown/issues/403)) ([21fe501](https://github.com/rolldown-rs/rolldown/commit/21fe501869683566988f062c751b877c407d258f))
* add `OutputChunk` is_entry and facade_module_id ([#230](https://github.com/rolldown-rs/rolldown/issues/230)) ([8fcfda3](https://github.com/rolldown-rs/rolldown/commit/8fcfda3255c15c18aa79ec762d133c64c9c48a03))
* add `referenced_symbols` to `StmtInfo` ([#75](https://github.com/rolldown-rs/rolldown/issues/75)) ([465e6e7](https://github.com/rolldown-rs/rolldown/commit/465e6e760031decaa550acf3665b5ba98796e2df))
* add `Renamer` ([#123](https://github.com/rolldown-rs/rolldown/issues/123)) ([7709cd4](https://github.com/rolldown-rs/rolldown/commit/7709cd4afc1ad1ef21623dea843530175b9a2659))
* add `resolve` option ([#392](https://github.com/rolldown-rs/rolldown/issues/392)) ([cd52449](https://github.com/rolldown-rs/rolldown/commit/cd5244973c938687d5430d21f33641f2b33e4036))
* add `RuntimeNormalModuleTask` ([#40](https://github.com/rolldown-rs/rolldown/issues/40)) ([2401386](https://github.com/rolldown-rs/rolldown/commit/2401386c6c9d8c48c6f2eec03373b007d8fdd571))
* add basic `renderChunk` hook ([#401](https://github.com/rolldown-rs/rolldown/issues/401)) ([b7ea28b](https://github.com/rolldown-rs/rolldown/commit/b7ea28b9c084439844db98ee93f2a6f423beb695))
* add buildStart buildEnd hook ([#208](https://github.com/rolldown-rs/rolldown/issues/208)) ([e878c3b](https://github.com/rolldown-rs/rolldown/commit/e878c3bd34a99f2007a7abb69feeaa205b2b4ece))
* add external option ([#259](https://github.com/rolldown-rs/rolldown/issues/259)) ([a80db39](https://github.com/rolldown-rs/rolldown/commit/a80db39313c93a964d595b41f5d0699bd5bc1e0d))
* add indentor for inserted code ([#159](https://github.com/rolldown-rs/rolldown/issues/159)) ([eaebf11](https://github.com/rolldown-rs/rolldown/commit/eaebf114df4724049c533cee2066f2aa45256b37))
* add native plugin example ([#262](https://github.com/rolldown-rs/rolldown/issues/262)) ([246693f](https://github.com/rolldown-rs/rolldown/commit/246693f26d2f5a081186dae3c7b70237a5924038))
* add node binding ([#50](https://github.com/rolldown-rs/rolldown/issues/50)) ([9391f16](https://github.com/rolldown-rs/rolldown/commit/9391f16cbdfcbbb9851746e28295ebef9c8d2b66))
* add output chunk isDynamicEntry ([#373](https://github.com/rolldown-rs/rolldown/issues/373)) ([7f0e987](https://github.com/rolldown-rs/rolldown/commit/7f0e98762487532c546e63d4ad376c13e6d7874f))
* add OutputAsset ([#231](https://github.com/rolldown-rs/rolldown/issues/231)) ([42420d7](https://github.com/rolldown-rs/rolldown/commit/42420d73090227754ad68fa90a55cb901619853d))
* add OutputChunk exports ([#241](https://github.com/rolldown-rs/rolldown/issues/241)) ([46fe0bf](https://github.com/rolldown-rs/rolldown/commit/46fe0bfa4480653558102f75cc2b0578651d5fb9))
* add OutputChunk modules ([#240](https://github.com/rolldown-rs/rolldown/issues/240)) ([ccf06fe](https://github.com/rolldown-rs/rolldown/commit/ccf06fe1936ccc8c10e34f9885756cf8dabfa73d))
* add plugin adapter ([#53](https://github.com/rolldown-rs/rolldown/issues/53)) ([6438255](https://github.com/rolldown-rs/rolldown/commit/64382553dd997672a95002b309f3010c3a799ea5))
* add PluginDriver ([#198](https://github.com/rolldown-rs/rolldown/issues/198)) ([526f896](https://github.com/rolldown-rs/rolldown/commit/526f8962297ff8b02b66ab4a23dc3d29dc4a0ff5))
* add PluginDriver resolve_id ([#204](https://github.com/rolldown-rs/rolldown/issues/204)) ([1f0b4f2](https://github.com/rolldown-rs/rolldown/commit/1f0b4f293632b41c35a796261d39993793f3bd54))
* add resolve_id hook options, include kind and is_entry ([#218](https://github.com/rolldown-rs/rolldown/issues/218)) ([763dedb](https://github.com/rolldown-rs/rolldown/commit/763dedb0d078a043a13231371045995a0db8e78f))
* add rolldown_fs crate ([#173](https://github.com/rolldown-rs/rolldown/issues/173)) ([583c858](https://github.com/rolldown-rs/rolldown/commit/583c858fe5b349a23aee7e7f4be2461384694875))
* add sourcemap ([#420](https://github.com/rolldown-rs/rolldown/issues/420)) ([d6a0efd](https://github.com/rolldown-rs/rolldown/commit/d6a0efd2cd50551fb612f15a9a9d1da8623e8708))
* add sourcemap option ([#424](https://github.com/rolldown-rs/rolldown/issues/424)) ([2f7c61b](https://github.com/rolldown-rs/rolldown/commit/2f7c61b32db81cc41ffe9c8f42940f5a9fa3dfe4))
* add ViteScannerPlugin ([#261](https://github.com/rolldown-rs/rolldown/issues/261)) ([3d8aff7](https://github.com/rolldown-rs/rolldown/commit/3d8aff74e061d020b3708d51f2975e24b1165fe3))
* add writeBundle hook ([#405](https://github.com/rolldown-rs/rolldown/issues/405)) ([683416a](https://github.com/rolldown-rs/rolldown/commit/683416afa0bf7ff267e52256e13b5324ab412599))
* allow custom require ([#170](https://github.com/rolldown-rs/rolldown/issues/170)) ([d792da2](https://github.com/rolldown-rs/rolldown/commit/d792da2b0934ed5e6a22b5ac4699bf2b57c07ce1))
* allow to get current `StmtInfo` in visiting ast ([#370](https://github.com/rolldown-rs/rolldown/issues/370)) ([d962268](https://github.com/rolldown-rs/rolldown/commit/d9622682b3a97ce29b82205530a45b543285c455))
* allow to use node module specifier as the bundle input ([#211](https://github.com/rolldown-rs/rolldown/issues/211)) ([51da74c](https://github.com/rolldown-rs/rolldown/commit/51da74ce19680c1586ff873b18dd81d115193932))
* ast-based manipulation ([#410](https://github.com/rolldown-rs/rolldown/issues/410)) ([6f4bfed](https://github.com/rolldown-rs/rolldown/commit/6f4bfed764ef3be29b5a2b3b206b346b077d7231))
* basic code splitting ([#23](https://github.com/rolldown-rs/rolldown/issues/23)) ([74a7ccf](https://github.com/rolldown-rs/rolldown/commit/74a7ccf544ab8442bbd78f3f1e23e2515b70f4d3))
* basic code splitting ([#97](https://github.com/rolldown-rs/rolldown/issues/97)) ([395abb8](https://github.com/rolldown-rs/rolldown/commit/395abb833cb2ab52b29d57d8b8fce962a95fec49))
* basic commonjs support ([#38](https://github.com/rolldown-rs/rolldown/issues/38)) ([d40c919](https://github.com/rolldown-rs/rolldown/commit/d40c91949bda45415e997d8824c8cc26fddafc97))
* basic error mechanism ([#150](https://github.com/rolldown-rs/rolldown/issues/150)) ([0c9ab02](https://github.com/rolldown-rs/rolldown/commit/0c9ab02bd89da358a0d9fb9719e85cd63d0f4aad))
* basic support for importing external module ([#168](https://github.com/rolldown-rs/rolldown/issues/168)) ([6d7e891](https://github.com/rolldown-rs/rolldown/commit/6d7e891f3d2528285e992f44ee95ab49ea12dd1c))
* basic treeshaking ([#372](https://github.com/rolldown-rs/rolldown/issues/372)) ([b240923](https://github.com/rolldown-rs/rolldown/commit/b2409232d8919bb1ca5311b77e2d866e30e37f39)), closes [#16](https://github.com/rolldown-rs/rolldown/issues/16)
* basic warning mechanism ([#332](https://github.com/rolldown-rs/rolldown/issues/332)) ([84697ce](https://github.com/rolldown-rs/rolldown/commit/84697ce98e512d6c2d3344e7cf8189229bcf2f56)), closes [#331](https://github.com/rolldown-rs/rolldown/issues/331)
* call PluginDriver load to get source content ([#199](https://github.com/rolldown-rs/rolldown/issues/199)) ([01b3563](https://github.com/rolldown-rs/rolldown/commit/01b3563ef1d88ebf3ebd2bb739bee22aaac4bc16))
* call PluginDriver transform ([#202](https://github.com/rolldown-rs/rolldown/issues/202)) ([42cdd61](https://github.com/rolldown-rs/rolldown/commit/42cdd612df9d36d8d4857d809d62046be185f4fa))
* **ci:** add release workflow ([#409](https://github.com/rolldown-rs/rolldown/issues/409)) ([85c1b9e](https://github.com/rolldown-rs/rolldown/commit/85c1b9e9a1fdce378fd84c3a38c44e3fdf4c072e))
* code splitting rely on tree shaking. Closes [#390](https://github.com/rolldown-rs/rolldown/issues/390) ([5e7491e](https://github.com/rolldown-rs/rolldown/commit/5e7491e9dd27a9f930baea7f2cd786798d91ecef))
* code splitting for dynamic import ([#27](https://github.com/rolldown-rs/rolldown/issues/27)) ([6cd5c8e](https://github.com/rolldown-rs/rolldown/commit/6cd5c8e8d45e0dba6070889b0fe471a37889a3e1))
* collect errors from `NormalModuleTask` ([#298](https://github.com/rolldown-rs/rolldown/issues/298)) ([4d7d595](https://github.com/rolldown-rs/rolldown/commit/4d7d59523d2ebcd6d1209f7d6dfd68f0af2c27fb))
* compat node module commonjs interop ([#56](https://github.com/rolldown-rs/rolldown/issues/56)) ([58c2786](https://github.com/rolldown-rs/rolldown/commit/58c278671f6a0abc11cb4cabbd185890483ecd96))
* compute cross chunk links in parallel. Closes [#354](https://github.com/rolldown-rs/rolldown/issues/354) ([5844943](https://github.com/rolldown-rs/rolldown/commit/58449435b6c6b01e6dda082288dd990868398f84))
* concat sourcemap ([#423](https://github.com/rolldown-rs/rolldown/issues/423)) ([f10dac8](https://github.com/rolldown-rs/rolldown/commit/f10dac8f572e2ef3c41530b7cb394d623fea7250))
* correct indent for generated code ([#160](https://github.com/rolldown-rs/rolldown/issues/160)) ([21a70c2](https://github.com/rolldown-rs/rolldown/commit/21a70c2b2c702a8b8357e7cccb5ae34e36e54e86))
* correct indent for wrapped cjs module ([#161](https://github.com/rolldown-rs/rolldown/issues/161)) ([58dff4e](https://github.com/rolldown-rs/rolldown/commit/58dff4e2fe51da179092ff948d6d880f46f3cee9))
* **crates/rolldown:** expose `build` api ([#266](https://github.com/rolldown-rs/rolldown/issues/266)) ([4430a89](https://github.com/rolldown-rs/rolldown/commit/4430a8945e12f5081fe72a4f64263184525cc14e))
* create cross-chunk links for runtime module and facade symbols ([#114](https://github.com/rolldown-rs/rolldown/issues/114)) ([0c1e164](https://github.com/rolldown-rs/rolldown/commit/0c1e1641a948dc8c157249902adeaf7324a54624))
* deconflict symbols in nested scopes in parallel ([b3c5e01](https://github.com/rolldown-rs/rolldown/commit/b3c5e0178aec3381b54ed9bde3ee94bfa0fc0cc2))
* deconflicting for symbols of nested scopes ([#188](https://github.com/rolldown-rs/rolldown/issues/188)) ([42a2421](https://github.com/rolldown-rs/rolldown/commit/42a242142c906dc9969dc50d3fe00e3b32f4dc01))
* don't render empty module. Closes [#440](https://github.com/rolldown-rs/rolldown/issues/440), [#162](https://github.com/rolldown-rs/rolldown/issues/162) ([b310a9a](https://github.com/rolldown-rs/rolldown/commit/b310a9aff8c8203be06cb0c8797e7c1f824f14ad))
* empty module should have `ExportsKind::None` ([#317](https://github.com/rolldown-rs/rolldown/issues/317)) ([b15ff14](https://github.com/rolldown-rs/rolldown/commit/b15ff1454fd6ed06a94920cb9ef6413c3383f5ba))
* enable bare import by default ([#284](https://github.com/rolldown-rs/rolldown/issues/284)) ([833dfc6](https://github.com/rolldown-rs/rolldown/commit/833dfc6aa5d1bda366829b8928b970920be530e9))
* exclude modules in code splitting ([#383](https://github.com/rolldown-rs/rolldown/issues/383)) ([ec60aca](https://github.com/rolldown-rs/rolldown/commit/ec60aca10b94758aaf0b971304e8afcff4a3e16a))
* extract html scripts at vite scanner plugin ([#268](https://github.com/rolldown-rs/rolldown/issues/268)) ([1045b0b](https://github.com/rolldown-rs/rolldown/commit/1045b0bc8902a98930a0ed45472031e9e5fbfbc4))
* finish bench use @rolldown/core ([#234](https://github.com/rolldown-rs/rolldown/issues/234)) ([aa7982b](https://github.com/rolldown-rs/rolldown/commit/aa7982b6577adb011186ff5fa4bd35d1393560dd))
* follow virtual module convention ([#39](https://github.com/rolldown-rs/rolldown/issues/39)) ([a264b4a](https://github.com/rolldown-rs/rolldown/commit/a264b4a587353072e343833003f7ad643dd40e42))
* generate cross chunk imports by usages ([d9ccdb7](https://github.com/rolldown-rs/rolldown/commit/d9ccdb74957e0db346be6712ebe8d1036a7c4649))
* generate default export for cjs entry ([#219](https://github.com/rolldown-rs/rolldown/issues/219)) ([699fc5d](https://github.com/rolldown-rs/rolldown/commit/699fc5de92aad4dcbcd8c0be12748b562e7ce7e6))
* generate module namespace binding on demand ([#126](https://github.com/rolldown-rs/rolldown/issues/126)) ([e09002f](https://github.com/rolldown-rs/rolldown/commit/e09002f092fb24fb706066613ae2bfc396944f56))
* generate namespace decl ([62768fe](https://github.com/rolldown-rs/rolldown/commit/62768fe70cc3b7df22c4bc43e5b58788848e0e64))
* generate sourcemap ([#425](https://github.com/rolldown-rs/rolldown/issues/425)) ([da9db71](https://github.com/rolldown-rs/rolldown/commit/da9db717bdb886141cd386ff43c38b396e05e7f3))
* generate the namespace variable on demand ([44d5aa8](https://github.com/rolldown-rs/rolldown/commit/44d5aa8cccf0214edbfe2181aa5bf0fe976f304e))
* hoist exported function declaration ([#73](https://github.com/rolldown-rs/rolldown/issues/73)) ([f530305](https://github.com/rolldown-rs/rolldown/commit/f530305d9877a1155d98447548cfb4b427f2bf7a))
* impl `Extend` for `BatchedErrors` ([e22acce](https://github.com/rolldown-rs/rolldown/commit/e22accebb2a1326bdd7ce8fe171b5b112e2c4d8b))
* improve side-effect detection of `MemberExpression` ([#374](https://github.com/rolldown-rs/rolldown/issues/374)) ([abbc8aa](https://github.com/rolldown-rs/rolldown/commit/abbc8aa709a77726ca2fae7104062aefa42514a3))
* introduce `ChunkGraph` ([#90](https://github.com/rolldown-rs/rolldown/issues/90)) ([0f7c82c](https://github.com/rolldown-rs/rolldown/commit/0f7c82c779d8fbe6fb016233395cdb64138768d8))
* introduce `rolldown_rstr` ([a97e444](https://github.com/rolldown-rs/rolldown/commit/a97e44461ce7b72cd5054ad1ce921b87df6edb3c)), closes [#427](https://github.com/rolldown-rs/rolldown/issues/427)
* introduce `trait BuildErrorLike` ([#327](https://github.com/rolldown-rs/rolldown/issues/327)) ([158b11d](https://github.com/rolldown-rs/rolldown/commit/158b11d02423cdb63b70d6a37f1a864ec745ae62))
* introduce helper method `visit_top_level_stmt` while visiting ast ([#371](https://github.com/rolldown-rs/rolldown/issues/371)) ([7bc5f92](https://github.com/rolldown-rs/rolldown/commit/7bc5f92fc957d1a50bd427ca612fecb3ff870c71))
* make `BuildError` newtype ([#326](https://github.com/rolldown-rs/rolldown/issues/326)) ([475907e](https://github.com/rolldown-rs/rolldown/commit/475907ecdb837d1a884fe7f926a79a36755cf560))
* make sure chunks are evaluated for their side effects ([db6ac0a](https://github.com/rolldown-rs/rolldown/commit/db6ac0a45ea4004edc1acf10c470d288abb5a969))
* **node:** add `scan` api ([#340](https://github.com/rolldown-rs/rolldown/issues/340)) ([ba5257a](https://github.com/rolldown-rs/rolldown/commit/ba5257a32b58dc2a86060dfec8cdc0b2962b57b4))
* **node:** export some types ([#283](https://github.com/rolldown-rs/rolldown/issues/283)) ([aea91ab](https://github.com/rolldown-rs/rolldown/commit/aea91abcf3c7db3da3b1acfea1c0696f1440b752))
* only split runtime module into runtime chunk in rust test ([#117](https://github.com/rolldown-rs/rolldown/issues/117)) ([7d56461](https://github.com/rolldown-rs/rolldown/commit/7d56461382188e30298282a6847f331e2217db59))
* only start including modules with entry point in tree shaking ([f5b920d](https://github.com/rolldown-rs/rolldown/commit/f5b920db7058e8579341cbb5973d896fb303f639))
* output code block should be readonly ([#267](https://github.com/rolldown-rs/rolldown/issues/267)) ([629fd35](https://github.com/rolldown-rs/rolldown/commit/629fd35f7ea54dd36240b0597d2cce84d5436378))
* parsing with correct `SourceType` ([#179](https://github.com/rolldown-rs/rolldown/issues/179)) ([aeaf38b](https://github.com/rolldown-rs/rolldown/commit/aeaf38b959e60d582e2758b924ddf43886dfbdc7))
* prepare supporting runtime ([#37](https://github.com/rolldown-rs/rolldown/issues/37)) ([cd4899f](https://github.com/rolldown-rs/rolldown/commit/cd4899f719c3bd764128744f7336989347ef3ef5))
* print fancy messages for errors ([#329](https://github.com/rolldown-rs/rolldown/issues/329)) ([8751ee4](https://github.com/rolldown-rs/rolldown/commit/8751ee4a214b5778aefb585d1774792fd0c326fd))
* reexport commonjs ([#87](https://github.com/rolldown-rs/rolldown/issues/87)) ([20271ad](https://github.com/rolldown-rs/rolldown/commit/20271ad6c6eb6a3e99fb4bbffc00c5c2a3b59752))
* refactor `Symbols` and remove a lot of `ReferenceId` ([#93](https://github.com/rolldown-rs/rolldown/issues/93)) ([5b980d5](https://github.com/rolldown-rs/rolldown/commit/5b980d5311b1347327d525772b139fe08d1309ca))
* rely on the standalone copy of rollup types. Closes [#439](https://github.com/rolldown-rs/rolldown/issues/439) ([e231e14](https://github.com/rolldown-rs/rolldown/commit/e231e14fa89f88d23ce26dda5afe1c12609dd8d0))
* remove `build` api ([65b9bd6](https://github.com/rolldown-rs/rolldown/commit/65b9bd6bd6b8d1e9a71e59a7b83d15a57396bcb4))
* remove `VirtualStmtInfo` ([#99](https://github.com/rolldown-rs/rolldown/issues/99)) ([344be1a](https://github.com/rolldown-rs/rolldown/commit/344be1a5331b8d125dcdba06376c7ca9aab6ffa0))
* remove special tree shaking logic for entry point ([ba046e6](https://github.com/rolldown-rs/rolldown/commit/ba046e650fffade8f341545aaab3259406c2becc))
* render chunk hook binding ([#402](https://github.com/rolldown-rs/rolldown/issues/402)) ([25fca9d](https://github.com/rolldown-rs/rolldown/commit/25fca9d38fe19f7ddc081d3ed9b088be5e3ae7ca))
* replace `SymbolId` with `SymbolRef` ([#95](https://github.com/rolldown-rs/rolldown/issues/95)) ([9c90067](https://github.com/rolldown-rs/rolldown/commit/9c90067a9db235ed9f31743a8c59cb83dc74f827))
* runtime symbol deconflict ([#54](https://github.com/rolldown-rs/rolldown/issues/54)) ([0fc1d3a](https://github.com/rolldown-rs/rolldown/commit/0fc1d3a144ec3b13baa451c634af58c242147aad)), closes [#59](https://github.com/rolldown-rs/rolldown/issues/59)
* **rust:** add `OutputFormat::Cjs` ([#358](https://github.com/rolldown-rs/rolldown/issues/358)) ([44c6331](https://github.com/rolldown-rs/rolldown/commit/44c6331b0823d2467d05d4563443f46d839c7271)), closes [#45](https://github.com/rolldown-rs/rolldown/issues/45)
* **rust:** add `print` in `OxcCompiler` ([#281](https://github.com/rolldown-rs/rolldown/issues/281)) ([ad962af](https://github.com/rolldown-rs/rolldown/commit/ad962afa91f76f05c9623b81c1887a2b8225c3d0))
* **rust:** rendering runtime module in snapshot testing ([#375](https://github.com/rolldown-rs/rolldown/issues/375)) ([3cb39a2](https://github.com/rolldown-rs/rolldown/commit/3cb39a22db150b27b9292897c252279fb937dacf))
* **rust:** return errors from `NormalModuleTask#resolve_dependencies` ([#270](https://github.com/rolldown-rs/rolldown/issues/270)) ([fdbf290](https://github.com/rolldown-rs/rolldown/commit/fdbf290113b3a24b9c963475ab9035dfa3155a21))
* setup rolldown node test ([#307](https://github.com/rolldown-rs/rolldown/issues/307)) ([7638193](https://github.com/rolldown-rs/rolldown/commit/76381939613d6a3cf1a32e5f3b175d22689eb1d6))
* should rewrite symbols in complex patterns correctly ([#193](https://github.com/rolldown-rs/rolldown/issues/193)) ([e267018](https://github.com/rolldown-rs/rolldown/commit/e2670185fb94da9b414f0e4f92406e45db0340f0))
* store `source` in `BuildError` ([#328](https://github.com/rolldown-rs/rolldown/issues/328)) ([c34d3cd](https://github.com/rolldown-rs/rolldown/commit/c34d3cd7213975e89412f527fb61efd6d0ce85ae))
* support enabling tracing ([#291](https://github.com/rolldown-rs/rolldown/issues/291)) ([8310a17](https://github.com/rolldown-rs/rolldown/commit/8310a17d28aa870f334dea259c3d7152d60b191b)), closes [/github.com/rolldown-rs/rolldown/blob/6601e8863d8934f18f7b1aa9b44867aba854b6f4/crates/rolldown_tracing/src/lib.rs#L1-L6](https://github.com//github.com/rolldown-rs/rolldown/blob/6601e8863d8934f18f7b1aa9b44867aba854b6f4/crates/rolldown_tracing/src/lib.rs/issues/L1-L6)
* support export star commonjs ([#85](https://github.com/rolldown-rs/rolldown/issues/85)) ([07b8c03](https://github.com/rolldown-rs/rolldown/commit/07b8c039fd5e52f7ba60b5a74eb807ee5b577789))
* support mix cjs and esm ([#76](https://github.com/rolldown-rs/rolldown/issues/76)) ([22794c3](https://github.com/rolldown-rs/rolldown/commit/22794c3986a0abeac3bd6e5130c3f9f8dac55c3d))
* support tree shaking ([6e32999](https://github.com/rolldown-rs/rolldown/commit/6e32999b473a50e4faa6e668153f30fd91c48478))
* support load hook return map ([#421](https://github.com/rolldown-rs/rolldown/issues/421)) ([b42b32b](https://github.com/rolldown-rs/rolldown/commit/b42b32b2cdb27fb652100df55bcef0aa8af01ed1))
* support transform hook return map ([#422](https://github.com/rolldown-rs/rolldown/issues/422)) ([9206754](https://github.com/rolldown-rs/rolldown/commit/92067541217777fb1cbed392040deaa80c65f8da))
* treat empty files as cjs in compat mode ([456e0b3](https://github.com/rolldown-rs/rolldown/commit/456e0b3eef2f6b3607ddb3635f96839d56edd704))
* treat required module with `ExportKind::None` as commonjs ([#319](https://github.com/rolldown-rs/rolldown/issues/319)) ([0738ad8](https://github.com/rolldown-rs/rolldown/commit/0738ad8e2413ea1a94e8d5c5ce6c2b055aa00ba9))
* treeshaking in module level ([#382](https://github.com/rolldown-rs/rolldown/issues/382)) ([6f8b03f](https://github.com/rolldown-rs/rolldown/commit/6f8b03f2e3435b7bc3ac47d88b4c47206436eae3))
* update to `oxc@0.9.0` ([5cf2c6b](https://github.com/rolldown-rs/rolldown/commit/5cf2c6bdba2f77081ca45c274446e002642579a9))
* use `ariadne` for better error display ([#163](https://github.com/rolldown-rs/rolldown/issues/163)) ([2cd7d49](https://github.com/rolldown-rs/rolldown/commit/2cd7d49eca7f7d5f8b71db0ef07ceb42ecbc3d11))
* use oxc_resolver ([#32](https://github.com/rolldown-rs/rolldown/issues/32)) ([79de1ad](https://github.com/rolldown-rs/rolldown/commit/79de1ad14555fef2a0555752d88bca727b5da784))
* **vite-scanner:** load script content from html ([#280](https://github.com/rolldown-rs/rolldown/issues/280)) ([3bcaabc](https://github.com/rolldown-rs/rolldown/commit/3bcaabc3d9dd6b1434e8f58219c949289a9be776))
* wasm ([#178](https://github.com/rolldown-rs/rolldown/issues/178)) ([d8d0b2a](https://github.com/rolldown-rs/rolldown/commit/d8d0b2afa305657a60d406c99b03b2ed1759f2c8))
* wasm playground ([#233](https://github.com/rolldown-rs/rolldown/issues/233)) ([724f4b2](https://github.com/rolldown-rs/rolldown/commit/724f4b2d36abcb11794af864d6f385d7cc91fba1))
* **wasm:** enable multi entry ([#250](https://github.com/rolldown-rs/rolldown/issues/250)) ([571ee4b](https://github.com/rolldown-rs/rolldown/commit/571ee4bbe1c02eb92071671a0b8367b675eae30b))


### Performance Improvements

* bump `string_wizard` for better performance ([#292](https://github.com/rolldown-rs/rolldown/issues/292)) ([10a884a](https://github.com/rolldown-rs/rolldown/commit/10a884a69389074da1c1531435a62addd04edd0c))
* reduce Module size ([#6](https://github.com/rolldown-rs/rolldown/issues/6)) ([b1ceb65](https://github.com/rolldown-rs/rolldown/commit/b1ceb65eeaaea3ea583eb56f2fcfb6c9053995ea))
* reference needed symbols in parallel ([#426](https://github.com/rolldown-rs/rolldown/issues/426)) ([26d3468](https://github.com/rolldown-rs/rolldown/commit/26d346854e9e38cb602cca7b5c26ff90818b4157))
* spawn runtime task ASAP ([#276](https://github.com/rolldown-rs/rolldown/issues/276)) ([ba7f558](https://github.com/rolldown-rs/rolldown/commit/ba7f558c30d4900a13802cf7d5e8d4dead5b01cd))


### Reverts

* Revert "perf: reduce Module size (#6)" (#7) ([711ddb0](https://github.com/rolldown-rs/rolldown/commit/711ddb0db3637f1ac6c8f3443be4a4af4e415091)), closes [#6](https://github.com/rolldown-rs/rolldown/issues/6) [#7](https://github.com/rolldown-rs/rolldown/issues/7)


