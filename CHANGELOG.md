# Changelog

## [0.5.3](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.5.2...0.5.3) (2026-07-01)


### Features

* **auth/google:** Require audience or clientId for mcpEnabled ([mcp-toolbox#​3450](https://redirect.github.com/googleapis/mcp-toolbox/issues/3450)) ([59f7b6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/59f7b6e8eaceffca042cb7e2f2b6e5e9284b6bc3)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **mcp:** Add URL parameter binding for HTTP transport ([mcp-toolbox#​3112](https://redirect.github.com/googleapis/mcp-toolbox/issues/3112)) ([0cc7b37](https://redirect.github.com/googleapis/mcp-toolbox/commit/0cc7b37b733b6a99dad5281af4024b26d730106a)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **release:** Add digital signature to Toolbox binaries ([mcp-toolbox#​3528](https://redirect.github.com/googleapis/mcp-toolbox/issues/3528)) ([3f0f0af](https://redirect.github.com/googleapis/mcp-toolbox/commit/3f0f0af29007929b01e95ee2caef4fd2015d5f12)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **scylladb:** Adding support for ScyllaDB source and tool ([mcp-toolbox#​3119](https://redirect.github.com/googleapis/mcp-toolbox/issues/3119)) ([2dada83](https://redirect.github.com/googleapis/mcp-toolbox/commit/2dada8306c8737e445c4f8cd3d213b72713c1834)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **server:** Add support for toolset filtering in prebuilt CLI flag ([mcp-toolbox#​3245](https://redirect.github.com/googleapis/mcp-toolbox/issues/3245)) ([7cc4f65](https://redirect.github.com/googleapis/mcp-toolbox/commit/7cc4f65a8e767e0da37cf21f0ff2568b38d32b8e)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **skills:** Generate skills offline without live source connections ([mcp-toolbox#​3388](https://redirect.github.com/googleapis/mcp-toolbox/issues/3388)) ([4c860b6](https://redirect.github.com/googleapis/mcp-toolbox/commit/4c860b66b03f0ebf86205e73cd8521ad90ccebe4)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **skills:** Tolerate missing env vars during offline skills-generate ([mcp-toolbox#​3399](https://redirect.github.com/googleapis/mcp-toolbox/issues/3399)) ([ea5d3e5](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea5d3e5b9e60bf808e10d21b522954d76f7741b6)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **tools:** Decouple tool initialization from sources ([mcp-toolbox#​3355](https://redirect.github.com/googleapis/mcp-toolbox/issues/3355)) ([32a24e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/32a24e35b5bf107bcf5e89af2a9b7af3740747ee)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **tools/dataplex-get-data-product:** Add dataplex-get-data-product tool ([mcp-toolbox#​3499](https://redirect.github.com/googleapis/mcp-toolbox/issues/3499)) ([7ea7a09](https://redirect.github.com/googleapis/mcp-toolbox/commit/7ea7a095cc6dcf85520a8f39c4cd5a20062289f7)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **tools/dataplex-list-data-assets:** Add dataplex-list-data-assets tool ([mcp-toolbox#​3500](https://redirect.github.com/googleapis/mcp-toolbox/issues/3500)) ([182f933](https://redirect.github.com/googleapis/mcp-toolbox/commit/182f9332d67cc90d81f78b536081a7f47766d966)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **tools/dataplex-list-data-products:** Add dataplex-list-data-products tool ([mcp-toolbox#​3337](https://redirect.github.com/googleapis/mcp-toolbox/issues/3337)) ([6dd669a](https://redirect.github.com/googleapis/mcp-toolbox/commit/6dd669ad9bad3e54206a82b3af122d845e2cdc63)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **tools/dataplex:** Add tools to support metadata enrichment workflow ([mcp-toolbox#​3270](https://redirect.github.com/googleapis/mcp-toolbox/issues/3270)) ([05289aa](https://redirect.github.com/googleapis/mcp-toolbox/commit/05289aaa022e35996038b061f07eb43574e38bd2)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* Enable per source level flags for sql commenter ([mcp-toolbox#​3465](https://redirect.github.com/googleapis/mcp-toolbox/issues/3465)) ([ecce6b7](https://redirect.github.com/googleapis/mcp-toolbox/commit/ecce6b7bb551b947b0951cd684cce627a4b6cf1b)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* Support MCP 2026 draft specs ([mcp-toolbox#​3544](https://redirect.github.com/googleapis/mcp-toolbox/issues/3544)) ([d12eaa8](https://redirect.github.com/googleapis/mcp-toolbox/commit/d12eaa856bad70b49ba2b7b9f2882cffbf81220f)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))


### Bug Fixes

* **auth/dataplex:** Fix failing source with service account credentials ([mcp-toolbox#​3369](https://redirect.github.com/googleapis/mcp-toolbox/issues/3369)) ([ba4deef](https://redirect.github.com/googleapis/mcp-toolbox/commit/ba4deef140358e5876d73d355d664f629f7aeccc)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **bigquery:** Wire maximumBytesBilled into prebuilt config ([mcp-toolbox#​3385](https://redirect.github.com/googleapis/mcp-toolbox/issues/3385)) ([4abbf6e](https://redirect.github.com/googleapis/mcp-toolbox/commit/4abbf6e82cc4af4c1903d9143337c965987475a9)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **config:** Add doc/line context to parse errors ([mcp-toolbox#​2957](https://redirect.github.com/googleapis/mcp-toolbox/issues/2957)) ([4b097da](https://redirect.github.com/googleapis/mcp-toolbox/commit/4b097daa2143817e55a9e557e8c1dea054bfc7b8)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **npm:** Source binary version from cmd/version.txt ([mcp-toolbox#​3417](https://redirect.github.com/googleapis/mcp-toolbox/issues/3417)) ([6ffbdec](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ffbdecaea98db5c16dc9eeca8fb73e4bbc48102)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **prebuilt/alloydb-omni:** Require password env var explicitly ([mcp-toolbox#​3398](https://redirect.github.com/googleapis/mcp-toolbox/issues/3398)) ([fcbe3e7](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcbe3e70d3d4e671e97e424187dba907d7c5b10b)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **server:** Fail if MCP auth is enabled together with enable-api ([mcp-toolbox#​3435](https://redirect.github.com/googleapis/mcp-toolbox/issues/3435)) ([a6ff910](https://redirect.github.com/googleapis/mcp-toolbox/commit/a6ff910a602adece11f0a6581d6211e5927f7182)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **server:** Return errors instead of panicking in InitializeConfigs ([mcp-toolbox#​3397](https://redirect.github.com/googleapis/mcp-toolbox/issues/3397)) ([f48b01d](https://redirect.github.com/googleapis/mcp-toolbox/commit/f48b01dc1775e4583a06689a2e67fb06e5dd3c68)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* **source/dataplex,source/datalineage:** Specify cloud-platform scope for default credentials ([mcp-toolbox#​3376](https://redirect.github.com/googleapis/mcp-toolbox/issues/3376)) ([13e8c36](https://redirect.github.com/googleapis/mcp-toolbox/commit/13e8c364de6fa598f1864134eff5b756340c8358)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* Bound MCP HTTP body size ([mcp-toolbox#​3216](https://redirect.github.com/googleapis/mcp-toolbox/issues/3216)) ([d4f4342](https://redirect.github.com/googleapis/mcp-toolbox/commit/d4f434251392fb597779a90a12c63d21533ea187)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))
* Escape delimiter characters in applyEscape to prevent SQL injection ([mcp-toolbox#​2811](https://redirect.github.com/googleapis/mcp-toolbox/issues/2811)) ([932519a](https://redirect.github.com/googleapis/mcp-toolbox/commit/932519a9551861bf5f18787dc43b20d06350343f)) ([2cf5b24](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/2cf5b2449ccab5de17be9b49816edfeb375869f5))

## [0.5.2](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.5.1...0.5.2) (2026-06-11)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v1.4.0 ([#114](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/114)) ([b3df58e](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/b3df58e81ae46a1497a1186fc82119d328ec730c))

## [0.5.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.5.0...0.5.1) (2026-05-22)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v1.3.0 ([#109](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/109)) ([02e9214](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/02e92142f70ee05a129149f118b315c72dc02a92))

## [0.5.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.4.0...0.5.0) (2026-04-16)


### ⚠ BREAKING CHANGES

* add support for skills ([#102](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/102)) ([f16120b](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/f16120b76720f5d88ea0a6b1fab7e4a874d86978))


### Features

* **dataplex:** Add support for lookup context tool. ([mcp-toolbox#​2744](https://redirect.github.com/googleapis/mcp-toolbox/issues/2744)) ([facb69d](https://redirect.github.com/googleapis/mcp-toolbox/commit/facb69d01fe0c7ff9e2e1c40804dd00762e508a6)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Add Claude Code support to generated scripts ([mcp-toolbox#​2966](https://redirect.github.com/googleapis/mcp-toolbox/issues/2966)) ([a1609e1](https://redirect.github.com/googleapis/mcp-toolbox/commit/a1609e10a2eaf4ea68eae36acec3eed355b8a052)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Add codex user agent ([mcp-toolbox#​2973](https://redirect.github.com/googleapis/mcp-toolbox/issues/2973)) ([070e939](https://redirect.github.com/googleapis/mcp-toolbox/commit/070e9399c02f088d43175ce6bf343378beb7f584)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Tool invocation via npx ([mcp-toolbox#​2916](https://redirect.github.com/googleapis/mcp-toolbox/issues/2916)) ([377dc5b](https://redirect.github.com/googleapis/mcp-toolbox/commit/377dc5b00145a0044eef39314dd6b0ef5966fcd7)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **tool/dataplex-lookup-context:** Relax project constraint and enforce location ([mcp-toolbox#​2952](https://redirect.github.com/googleapis/mcp-toolbox/issues/2952)) ([7ebfdf1](https://redirect.github.com/googleapis/mcp-toolbox/commit/7ebfdf1cfc7debac020de51be1aa01c81628879e)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* add claude code plugin config ([#104](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/104)) ([5238172](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/523817249c1404dd59f52fff632a607ef37bbdf4))
* add codex plugin config ([#105](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/105)) ([0d660f9](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/0d660f9038529fab79eb69f1f160c0d6d75861b4))



### Bug Fixes

* **skills:** Fix integer parameter parsing through agent skills ([mcp-toolbox#​2847](https://redirect.github.com/googleapis/mcp-toolbox/issues/2847)) ([4564efe](https://redirect.github.com/googleapis/mcp-toolbox/commit/4564efe75436b4081d9f3d1f7c912bc64c13f850)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Fix skill generation template ([mcp-toolbox#​2914](https://redirect.github.com/googleapis/mcp-toolbox/issues/2914)) ([a01a15e](https://redirect.github.com/googleapis/mcp-toolbox/commit/a01a15ed1aa9a83eda8362578fed2e3a3c8dde99)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Prevent empty strings overriding optional env vars in node scripts ([mcp-toolbox#​2963](https://redirect.github.com/googleapis/mcp-toolbox/issues/2963)) ([c52adeb](https://redirect.github.com/googleapis/mcp-toolbox/commit/c52adeba76fc13d0e6e415f6393def0648e478d6)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))

## [0.4.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.3.1...0.4.0) (2026-04-10)


### ⚠ BREAKING CHANGES

* **renaming:** Renaming changes across all the files.  ([#93](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/93))

### Miscellaneous Chores

* **renaming:** Renaming changes across all the files.  ([#93](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/93)) ([6e9215a](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/6e9215ae9d4dd6e3ccf37a041ba963304b0b0a42))

## [0.3.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.3.0...0.3.1) (2026-03-20)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.30.0 ([#89](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/89)) ([0341db1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/0341db179417f95ad00b243edbb6f27de4717fc6))

## [0.3.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.2...0.3.0) (2026-03-16)


### ⚠ BREAKING CHANGES

* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566))
* **source/knowledge-catalog:** restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640))

### Features

* **skill:** Attach user agent metadata for generated skill ([mcp-toolbox#​2697](https://redirect.github.com/googleapis/mcp-toolbox/issues/2697)) ([9598a6a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9598a6a32597b9c9abdb0f20c06d86a01b0d011f)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skill:** Update skill generation logic ([mcp-toolbox#​2646](https://redirect.github.com/googleapis/mcp-toolbox/issues/2646)) ([c233eee](https://redirect.github.com/googleapis/mcp-toolbox/commit/c233eee98cd9621526cb286245f3874f5bd6e7da)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skills:** Add additional-notes flag to generate skills command ([mcp-toolbox#​2696](https://redirect.github.com/googleapis/mcp-toolbox/issues/2696)) ([73bf962](https://redirect.github.com/googleapis/mcp-toolbox/commit/73bf962459b76872f748248bb5e289be232a30b6)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **source/knowledge-catalog:** restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **source/knowledge-catalog:** Restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640)) ([acb9a80](https://redirect.github.com/googleapis/mcp-toolbox/commit/acb9a80cf2438e04c76cf10267b1c9ca9227da0b)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Add user agent to embeddings generation ([mcp-toolbox#​2572](https://redirect.github.com/googleapis/mcp-toolbox/issues/2572)) ([287251a](https://redirect.github.com/googleapis/mcp-toolbox/commit/287251a0cfed4d24617e5d0d957026a94f65d820)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([131d764](https://redirect.github.com/googleapis/mcp-toolbox/commit/131d764f895c14908e29914b3c0c273d91a2654f)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))


### Bug Fixes

* **mcp:** Guard nil SSE session lookup and return 400 for missing session ([mcp-toolbox#​2681](https://redirect.github.com/googleapis/mcp-toolbox/issues/2681)) ([f66189f](https://redirect.github.com/googleapis/mcp-toolbox/commit/f66189fe43cb711da3a041fa31edbacd7bbc7153)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **oracle:** Update oracle-execute-sql tool interface to match source signature ([mcp-toolbox#​2627](https://redirect.github.com/googleapis/mcp-toolbox/issues/2627)) ([81699a3](https://redirect.github.com/googleapis/mcp-toolbox/commit/81699a375b7e5af37945f4124aa4c5f2a1a9f7a6)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **server/mcp:** Scope defer span.End inside loop iteration ([mcp-toolbox#​2558](https://redirect.github.com/googleapis/mcp-toolbox/issues/2558)) ([c88a62d](https://redirect.github.com/googleapis/mcp-toolbox/commit/c88a62dcf4c16118ae706cc43d18cad827e7496d)), closes [mcp-toolbox#​2549](https://redirect.github.com/googleapis/mcp-toolbox/issues/2549) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skill:** Fix env variable propagation ([mcp-toolbox#​2645](https://redirect.github.com/googleapis/mcp-toolbox/issues/2645)) ([5271368](https://redirect.github.com/googleapis/mcp-toolbox/commit/52713687208994c423da64333cb0a04fb483f794)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **telemetry:** Histogram buckets from OTel standard to MCP standards ([mcp-toolbox#​2729](https://redirect.github.com/googleapis/mcp-toolbox/issues/2729)) ([87cd4a0](https://redirect.github.com/googleapis/mcp-toolbox/commit/87cd4a0bf48605225ef25ca554cc787def976d11)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **ui:** Remove module from script ([mcp-toolbox#​2703](https://redirect.github.com/googleapis/mcp-toolbox/issues/2703)) ([6943ab6](https://redirect.github.com/googleapis/mcp-toolbox/commit/6943ab6839d21da7b6a4241700c7891c6f4a9b2c)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Improve list locks integration test for postgres ([mcp-toolbox#​2279](https://redirect.github.com/googleapis/mcp-toolbox/issues/2279)) ([d9ebe5d](https://redirect.github.com/googleapis/mcp-toolbox/commit/d9ebe5d4bf1b7ca04cae47386b36c38ca5b77b8a)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Return AllParams for GetParameter() for tools with templateParameter([mcp-toolbox#​2734](https://redirect.github.com/googleapis/mcp-toolbox/issues/2734)) ([bfd7ba6](https://redirect.github.com/googleapis/mcp-toolbox/commit/bfd7ba601a52294fa71623d88af71bd0288bf887)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Update toolset attributes naming ([mcp-toolbox#​2554](https://redirect.github.com/googleapis/mcp-toolbox/issues/2554)) ([3d6ae4e](https://redirect.github.com/googleapis/mcp-toolbox/commit/3d6ae4eeaf5acfbde83374a244573edd8fc9012b)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))

## [0.2.2](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.1...0.2.2) (2026-03-03)


### Features

* **dataproc:** Add dataproc source and list/get clusters/jobs tools ([mcp-toolbox#​2407](https://redirect.github.com/googleapis/mcp-toolbox/issues/2407)) ([cc05e57](https://redirect.github.com/googleapis/mcp-toolbox/commit/cc05e5745d1c25a6088702b827cd098250164b7e)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **ui:** Make tool list panel resizable ([mcp-toolbox#​2253](https://redirect.github.com/googleapis/mcp-toolbox/issues/2253)) ([276cf60](https://redirect.github.com/googleapis/mcp-toolbox/commit/276cf604a2bb41861639ed6881557e38dd97a614)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Add polling system to dynamic reloading ([mcp-toolbox#​2466](https://redirect.github.com/googleapis/mcp-toolbox/issues/2466)) ([fcaac9b](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcaac9bb957226ee3db1baea24330f337ba88ab7)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Added basic template for sdks doc migrate ([mcp-toolbox#​1961](https://redirect.github.com/googleapis/mcp-toolbox/issues/1961)) ([87f2eaf](https://redirect.github.com/googleapis/mcp-toolbox/commit/87f2eaf79cdecca7b939151e1543eccf2f812a69)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))


### Bug Fixes

* **ci:** Add path for forked PR unit test runs ([mcp-toolbox#​2540](https://redirect.github.com/googleapis/mcp-toolbox/issues/2540)) ([04dd2a7](https://redirect.github.com/googleapis/mcp-toolbox/commit/04dd2a77603c7babf01da724dfb77808e3f25fe5)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **docs/adk:** Resolve dependency duplication ([mcp-toolbox#​2418](https://redirect.github.com/googleapis/mcp-toolbox/issues/2418)) ([4d44abb](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d44abb4638926ca50b0fa4dcf10a03e7fab657f)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **docs/langchain:** Fix core at 0.3.0 and align compatible dependencies ([mcp-toolbox#​2426](https://redirect.github.com/googleapis/mcp-toolbox/issues/2426)) ([36edfd3](https://redirect.github.com/googleapis/mcp-toolbox/commit/36edfd3d506e839c092d04cbca1799b5ebc38160)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **oracle:** Enable DML operations and resolve incorrect array type error ([mcp-toolbox#​2323](https://redirect.github.com/googleapis/mcp-toolbox/issues/2323)) ([72146a4](https://redirect.github.com/googleapis/mcp-toolbox/commit/72146a4b1605bcdd3e1038106bfb1f899e677e39)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **server/mcp:** Guard nil dereference in sseManager.get ([mcp-toolbox#​2557](https://redirect.github.com/googleapis/mcp-toolbox/issues/2557)) ([e534196](https://redirect.github.com/googleapis/mcp-toolbox/commit/e534196303c2b8d9b6e599ac25add337e6fc9b8f)), closes [mcp-toolbox#​2548](https://redirect.github.com/googleapis/mcp-toolbox/issues/2548) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests:** Resolve LlamaIndex dependency conflict in JS quickstart ([mcp-toolbox#​2597](https://redirect.github.com/googleapis/mcp-toolbox/issues/2597)) ([ac11f5a](https://redirect.github.com/googleapis/mcp-toolbox/commit/ac11f5af9c7bcf228d667e1b8e08b5dc49ad91a0)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests/postgres:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2377](https://redirect.github.com/googleapis/mcp-toolbox/issues/2377)) ([8a96fb1](https://redirect.github.com/googleapis/mcp-toolbox/commit/8a96fb1a8874baa3688e566f3dea8a0912fcf2df)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests/postgres:** Restore list\_schemas test and implement dynamic owner ([mcp-toolbox#​2521](https://redirect.github.com/googleapis/mcp-toolbox/issues/2521)) ([7041e79](https://redirect.github.com/googleapis/mcp-toolbox/commit/7041e797347f337d6f7f44ca051ae31acd58babe)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Deflake alloydb omni ([mcp-toolbox#​2431](https://redirect.github.com/googleapis/mcp-toolbox/issues/2431)) ([62b8309](https://redirect.github.com/googleapis/mcp-toolbox/commit/62b830987d65c3573214d04e50742476097ee9e9)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Enforce required validation for explicit null parameter values ([mcp-toolbox#​2519](https://redirect.github.com/googleapis/mcp-toolbox/issues/2519)) ([d5e9512](https://redirect.github.com/googleapis/mcp-toolbox/commit/d5e9512a237e658f9b9127fdd8c174ec023c3310)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))

## [0.2.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.0...0.2.1) (2026-02-19)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.27.0 ([#74](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/74)) ([7297207](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7297207178cf6367225a1c041b3ae1e28eafeb54))

## [0.2.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.4...0.2.0) (2026-01-26)


### ⚠ BREAKING CHANGES

* Validate tool naming ([mcp-toolbox#​2305](https://redirect.github.com/googleapis/mcp-toolbox/issues/2305)) ([5054212](https://redirect.github.com/googleapis/mcp-toolbox/commit/5054212fa43017207fe83275d27b9fbab96e8ab5))

### Features

* **embeddingModel:** Add embedding model to MCP handler ([mcp-toolbox#​2310](https://redirect.github.com/googleapis/mcp-toolbox/issues/2310)) ([e4f60e5](https://redirect.github.com/googleapis/mcp-toolbox/commit/e4f60e56335b755ef55b9553d3f40b31858ec8d9)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **prebuilt/cloud-sql:** Add create backup tool for Cloud SQL ([mcp-toolbox#​2141](https://redirect.github.com/googleapis/mcp-toolbox/issues/2141)) ([8e0fb03](https://redirect.github.com/googleapis/mcp-toolbox/commit/8e0fb0348315a80f63cb47b3c7204869482448f4)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **prebuilt/cloud-sql:** Add restore backup tool for Cloud SQL ([mcp-toolbox#​2171](https://redirect.github.com/googleapis/mcp-toolbox/issues/2171)) ([00c3e6d](https://redirect.github.com/googleapis/mcp-toolbox/commit/00c3e6d8cba54e2ab6cb271c7e6b378895df53e1)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **tools:** Add `valueFromParam` support to Tool config ([mcp-toolbox#​2333](https://redirect.github.com/googleapis/mcp-toolbox/issues/2333)) ([15101b1](https://redirect.github.com/googleapis/mcp-toolbox/commit/15101b1edbe2b85a4a5f9f819c23cf83138f4ee1)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* add Configuration settings ([#67](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/67)) ([1c05d52](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/1c05d52d1907373855b146c76d7793ba3056585e))
* Add new `user-agent-metadata` flag ([mcp-toolbox#​2302](https://redirect.github.com/googleapis/mcp-toolbox/issues/2302)) ([adc9589](https://redirect.github.com/googleapis/mcp-toolbox/commit/adc9589766904d9e3cbe0a6399222f8d4bb9d0cc)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Add remaining flag to Toolbox server in MCP registry ([mcp-toolbox#​2272](https://redirect.github.com/googleapis/mcp-toolbox/issues/2272)) ([5e0999e](https://redirect.github.com/googleapis/mcp-toolbox/commit/5e0999ebf5cdd9046e96857738254b2e0561b6d2)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Support combining multiple prebuilt configurations ([mcp-toolbox#​2295](https://redirect.github.com/googleapis/mcp-toolbox/issues/2295)) ([e535b37](https://redirect.github.com/googleapis/mcp-toolbox/commit/e535b372ea81864d644a67135a1b07e4e519b4b4)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Support MCP specs version 2025-11-25 ([mcp-toolbox#​2303](https://redirect.github.com/googleapis/mcp-toolbox/issues/2303)) ([4d23a3b](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d23a3bbf2797b1f7fe328aeb5789e778121da23)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Validate tool naming ([mcp-toolbox#​2305](https://redirect.github.com/googleapis/mcp-toolbox/issues/2305)) ([5054212](https://redirect.github.com/googleapis/mcp-toolbox/commit/5054212fa43017207fe83275d27b9fbab96e8ab5)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))

## [0.1.4](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.3...0.1.4) (2026-01-15)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.25.0 ([#64](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/64)) ([dbf5a4a](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/dbf5a4a71ff3a6ccd3e35a54f931896620966c92))

## [0.1.3](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.2...0.1.3) (2025-12-29)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.24.0 ([#62](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/62)) ([fccf2a5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/fccf2a5979bbc49b82a8b4c9074868f77df5b385))

## [0.1.2](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.1...0.1.2) (2025-12-11)


### Bug Fixes

* Update knowledge-catalog context for new syntax ([#60](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/60)) ([82281dd](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/82281dd94143814629cd47729220ea2f85af9096))

## [0.1.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.0...0.1.1) (2025-09-30)


### Features

* additional instructions for the context file ([#26](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/26)) ([16e0d13](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/16e0d13f56ec98206f58f04b00220f191aaba07c))
* standardize mcp server names ([#24](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/24)) ([5cfdc0b](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/5cfdc0b9f7461ea3161db54b797650e79ced8504))

## 0.1.0 (2025-09-21)


### Features

* add knowledge-catalog Extension ([#9](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/9)) ([7ed91b2](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7ed91b2fdc551739485e212b91080ce8285f87be))
