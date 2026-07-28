# Changelog

All notable changes to XRDB are documented here.

## [3.14.0](https://github.com/djsaikrishna/XRDB/compare/v3.13.0...v3.14.0) (2026-07-28)


### Added

* **admin:** add UUID cohort trends for final image cache visibility ([b0db31c](https://github.com/djsaikrishna/XRDB/commit/b0db31c9c183a8d200245705361e605949e646fe))
* **admin:** Replace inactive config hard deletion with soft marking ([9128d24](https://github.com/djsaikrishna/XRDB/commit/9128d24167b495c666aa2905a349feef240ff1b2))
* **aggregate:** split critics and audience colours, and a score ramp ([1ec57f8](https://github.com/djsaikrishna/XRDB/commit/1ec57f8374c8daca3952a3ff3deed7243c304920))
* **aiometadata:** add mixed-library thumbnail auto mode ([6fd342e](https://github.com/djsaikrishna/XRDB/commit/6fd342ec51732e9b56349861462f62d6f35493de))
* **animemap:** add nattadasu supplement dataset to fill film/special gaps ([816f799](https://github.com/djsaikrishna/XRDB/commit/816f79959977ee744eadbbfb18e0e7cabcede6b1))
* **app:** v2 — full UI redesign, theme system, admin panel, community themes ([c2cf9c3](https://github.com/djsaikrishna/XRDB/commit/c2cf9c39d67512a699901894b4a4465331eca7b1))
* **artwork:** add an original-language option and missing codes ([9632b2a](https://github.com/djsaikrishna/XRDB/commit/9632b2a98590e23cf8cac267589b3bb58dd6f8b2))
* **auth:** add signed partner access controls ([41cf95a](https://github.com/djsaikrishna/XRDB/commit/41cf95a84cd2726986891a60b2c6b9bd5d6b1119))
* **badges:** FR-66 community badge system, tile style, HD badge, per-badge style overrides ([56de17d](https://github.com/djsaikrishna/XRDB/commit/56de17d62ed83f77f29c73e8b2cc51e57144f3ea))
* **badges:** FR-98 add trending and recognition quality tags ([323f44c](https://github.com/djsaikrishna/XRDB/commit/323f44c6c2c981cc1d9f56173a59d177cede255d))
* **badges:** per-provider mark size, and decode v2 provider appearance ([1282a54](https://github.com/djsaikrishna/XRDB/commit/1282a549bd7e3c972add793d660ec19924fd7694))
* **badges:** per-style offsets, an edge inset and a single bottom row ([0f164b4](https://github.com/djsaikrishna/XRDB/commit/0f164b49d1ea734fa28b442d6ce0a6b50ab5fe2b))
* **badges:** style the release status badge like the age badge ([189c3e5](https://github.com/djsaikrishna/XRDB/commit/189c3e57832ab0186d1c8bfaab709462e2059e7e))
* **badges:** trim provider marks to a shape ([a54a9e1](https://github.com/djsaikrishna/XRDB/commit/a54a9e1b85781e9104a1fc27c35ddf5b793017cf))
* **cache:** add entry delete and full purge ([a06a2df](https://github.com/djsaikrishna/XRDB/commit/a06a2dfc744e2196fdd24232a49e5b2ef98ec71d))
* **cache:** add uuid scoped poster caching with admin cache controls and metrics ([49322d7](https://github.com/djsaikrishna/XRDB/commit/49322d71f719eebd340716dd1b7fc9550907cc23))
* **compact-ring:** FR-34 ring rating style visual improvements ([d61bc02](https://github.com/djsaikrishna/XRDB/commit/d61bc025bec94d398a79ca7eb72d75f6c7d25cb7))
* **compose,provider,web:** anime genre grouping, and no more inert config ([9886795](https://github.com/djsaikrishna/XRDB/commit/98867955b0a43895e42a3fa1e050a530b3023159))
* **compose,web:** age-rating 'media' and 'silver' badge styles ([4a8934b](https://github.com/djsaikrishna/XRDB/commit/4a8934b90799bfa67ff74c4d1ea4e19b1a85fcea))
* **compose,web:** average and dual-minimal rating presentations ([0a112e2](https://github.com/djsaikrishna/XRDB/commit/0a112e231ecca5c411c518eaaf009c35e7c729d6))
* **compose,web:** configurable genre badge border width ([ede526e](https://github.com/djsaikrishna/XRDB/commit/ede526e993d61e828f577ada85cf80634b190b7b))
* **compose,web:** draw the top-rated rank as a badge ([e522e21](https://github.com/djsaikrishna/XRDB/commit/e522e21029f353695f3a1ce9a1d39b8dc96651b9))
* **compose,web:** genre badge icon and both display modes ([538af41](https://github.com/djsaikrishna/XRDB/commit/538af41ba5a14fc7a924ec620b8274807787f8b2))
* **compose,web:** minimal and dual rating presentation modes ([d74ab95](https://github.com/djsaikrishna/XRDB/commit/d74ab95ab4287890071b7ee4f5ca3e31196d6942))
* **compose,web:** optionally show vote counts on rating badges ([7b28401](https://github.com/djsaikrishna/XRDB/commit/7b284014f2ce014d5105632b0a428f25e296de25))
* **compose,web:** rating ring critics/audience/highest sources ([49a517d](https://github.com/djsaikrishna/XRDB/commit/49a517dcd827a41494c633383be4e5cf40bb68f5))
* **compose,web:** ring top-critic/top-audience sources and age square style ([c30530c](https://github.com/djsaikrishna/XRDB/commit/c30530cd2a74232b81721656f3d03929d6023a25))
* **compose,web:** score-driven 'dynamic' scorebar fill style ([c1658d8](https://github.com/djsaikrishna/XRDB/commit/c1658d819bd990f7a7484bb51d91c9213b64680a))
* **compose,web:** scorebar rating presentation mode ([6b053a5](https://github.com/djsaikrishna/XRDB/commit/6b053a580fa449cbd4f129f1055cea087a31d89e))
* **compose:** accept MAL, AniList and Kitsu ids ([855cde2](https://github.com/djsaikrishna/XRDB/commit/855cde2c0ed47f1a2c19a22b0c2f4fb074d73be1))
* **compose:** add a genre-family classifier ([885db09](https://github.com/djsaikrishna/XRDB/commit/885db091441290f54d695f1e7cfe5c49cd9eebd4))
* **compose:** add a switch to hide every quality badge ([6a15b4f](https://github.com/djsaikrishna/XRDB/commit/6a15b4fbcc926f8c224c192ac71d1eb301241b39))
* **compose:** colour the aggregate rating pill by its score ([d5b8b25](https://github.com/djsaikrishna/XRDB/commit/d5b8b255375194b1b3dd76d34d7b09a74e962b3d))
* **compose:** draw the genre badge the way v2 did ([be7f3c2](https://github.com/djsaikrishna/XRDB/commit/be7f3c242f1e2e7e486d325cd45bd9b85b0b092c))
* **compose:** fall back across providers for missing artwork ([227bc26](https://github.com/djsaikrishna/XRDB/commit/227bc266a4a667419a999f638abd34b4e314f1e7))
* **compose:** genre badge style variants ([65e0184](https://github.com/djsaikrishna/XRDB/commit/65e018455b0f7c02d408fb1ac3b84d127eaeb7f6))
* **compose:** honor the configured trending tag text color ([246e234](https://github.com/djsaikrishna/XRDB/commit/246e234f4aa6c60669850c85cc92cba013ddfc85))
* **compose:** order ratings and size badges to the canvas ([6a0928b](https://github.com/djsaikrishna/XRDB/commit/6a0928b60b8489e324714aee170ff1623b9eeb31))
* **compose:** overhaul poster overlays — brand logos, app-icon chips, anti-collision ([73c76bd](https://github.com/djsaikrishna/XRDB/commit/73c76bd854ac424228092d40352676c975399a0b))
* **compose:** restyle average rating ring ([bcfc42d](https://github.com/djsaikrishna/XRDB/commit/bcfc42d22685594ce85ab57000b80767c384ba7a))
* **compose:** saliency-aware backdrop crop and title logo overlay ([266e6d7](https://github.com/djsaikrishna/XRDB/commit/266e6d787e4783986a73e42aa0ef32cb8968a066))
* **compose:** support top-center and bottom-center overlay positions ([7dfb5e0](https://github.com/djsaikrishna/XRDB/commit/7dfb5e0b89191d56f0c19a8095891d337585e6f4))
* composite TMDB provider logos in streaming badge row ([aa64463](https://github.com/djsaikrishna/XRDB/commit/aa644634df9b1081a499f7bd896a9f2639e3dd01))
* **configurator:** add dedicated per-type genre badge X/Y offset controls ([136f671](https://github.com/djsaikrishna/XRDB/commit/136f671a256880d94cc40dae2702b589f554d982))
* **configurator:** add floating return-to-preview button for resizable workspace mode ([e9b9b05](https://github.com/djsaikrishna/XRDB/commit/e9b9b0518e5bf658493bcc7215e70180ed5c17ea))
* **configurator:** add icon shape controls for rating provider badges ([9fb572a](https://github.com/djsaikrishna/XRDB/commit/9fb572a11c67dd818160dd944821fbbee9dae06f))
* **configurator:** add resizable and floating preview modes for artwork workspace ([d1dd691](https://github.com/djsaikrishna/XRDB/commit/d1dd69130ff923442956e3ca851453e9eaa34086))
* **configurator:** BUG-151 restore compact aggregate controls across all artwork types ([017f4bc](https://github.com/djsaikrishna/XRDB/commit/017f4bce3b4982337c3bf24d4187322a1c9de390))
* **configurator:** collapse quality badge custom icon editor into accordion ([c400bab](https://github.com/djsaikrishna/XRDB/commit/c400babe541097454504a84f65c0bb2daf4cf864))
* **configurator:** per-surface artwork settings ([fffdacd](https://github.com/djsaikrishna/XRDB/commit/fffdacdc49a39a599d515ada9d16ffd33a618d9b))
* **configurator:** provider logos in source list; restore Metacritic User & Roger Ebert ([44a853f](https://github.com/djsaikrishna/XRDB/commit/44a853f557453d38fe64528485730a7c54485e5b))
* **context:** publish a product summary the community bot reads ([ebe0971](https://github.com/djsaikrishna/XRDB/commit/ebe0971f11bbffee13eab536a73d362f883d70d8))
* **deployment:** add optional uid remap and simplify env template ([5837bd1](https://github.com/djsaikrishna/XRDB/commit/5837bd12dd0ea121ccd5903b87f30e87fc9f725a))
* **docs,ui,cache:** README docs and add cache optimization foundation ([ab4f604](https://github.com/djsaikrishna/XRDB/commit/ab4f60446fb40b3b53c74037f43ef14e6be01384))
* **export:** add AIOMetadata public instance picker for repair profiles ([2e98d54](https://github.com/djsaikrishna/XRDB/commit/2e98d5401f8f79326276ff2512e8fd961b5378d0))
* **folderwriter:** write artwork into the media library, opt-in ([8e44902](https://github.com/djsaikrishna/XRDB/commit/8e44902ec9dd6088a3a7843712f448d0248ddaf7))
* **genre-badges:** FR-58 FR-76 add secondary genre replacement mode ([ab5e073](https://github.com/djsaikrishna/XRDB/commit/ab5e07366255c70aa493c0bd1a04f11dff009ff4))
* **imageconfig,compose,web:** age-rating badge style variants ([0721bbc](https://github.com/djsaikrishna/XRDB/commit/0721bbcf4baad7f08972d24963e97f68094fe219))
* **imageconfig,compose,web:** aggregate accent modes ([ff8d25e](https://github.com/djsaikrishna/XRDB/commit/ff8d25e3040e562afd9d2e3c764b179e07987eaa))
* **imageconfig,compose,web:** aggregate bar offset + expose hidden badge fields ([e0edf86](https://github.com/djsaikrishna/XRDB/commit/e0edf86091ca299a13313d515209b9805e49fbf6))
* **imageconfig,compose,web:** aggregate rating source and scorebar styles ([396cedf](https://github.com/djsaikrishna/XRDB/commit/396cedf24c5194466c3933cc9970e794cd842df1))
* **imageconfig,compose,web:** configurable plain-badge text outline ([3b0549e](https://github.com/djsaikrishna/XRDB/commit/3b0549ec027c66297eacb0bb08f3dc6af03b4d7f))
* **imageconfig,compose,web:** dark logo background option ([36eb79f](https://github.com/djsaikrishna/XRDB/commit/36eb79fd89a16ae7ccab758c6bab2c85531fd65f))
* **imageconfig,compose,web:** editorial rating presentation mode ([c6b750d](https://github.com/djsaikrishna/XRDB/commit/c6b750dd32b4cb7e3a90b7cdd33dec4fbda9f44e))
* **imageconfig,compose,web:** episode artwork mode ([c8d9c58](https://github.com/djsaikrishna/XRDB/commit/c8d9c58f80e9c78cb42fb89d7b5b5d855de511c9))
* **imageconfig,compose,web:** independent ring value and fill sources ([99327b4](https://github.com/djsaikrishna/XRDB/commit/99327b4fc14ae35b7ac444ad7f7411f4e036955e))
* **imageconfig,compose,web:** per-provider rating weights and ring fallback order ([473d6a4](https://github.com/djsaikrishna/XRDB/commit/473d6a4119aa902fa5c1b60d3996b0062820f728))
* **imageconfig,compose,web:** provider chip tile colour and country ([d5a365a](https://github.com/djsaikrishna/XRDB/commit/d5a365ab8d99671fb31d63527d6da9eddae88eb4))
* **imageconfig,compose,web:** quality badge style variants ([d7b2d51](https://github.com/djsaikrishna/XRDB/commit/d7b2d5164f11b1caced7b1bd03a944fa284bea24))
* **imageconfig,compose,web:** rating ring center-disc opacity ([11b6c1d](https://github.com/djsaikrishna/XRDB/commit/11b6c1d2ac0cc1186017c6648e7f24a78959a157))
* **imageconfig,compose,web:** rating strip position offset ([f783bc4](https://github.com/djsaikrishna/XRDB/commit/f783bc49450428279f7c1a43c32aa1190fa6a978))
* **imageconfig,compose,web:** split-side ratings geometry ([2133391](https://github.com/djsaikrishna/XRDB/commit/21333916f85ab75c131316b039e88b00dbaeb6df))
* **imageconfig,compose,web:** weight rating sources as percent shares ([1230dda](https://github.com/djsaikrishna/XRDB/commit/1230dda017620bbace44950323f9334099889e3e))
* **imageconfig,compose:** per-config genre badge styling ([179a177](https://github.com/djsaikrishna/XRDB/commit/179a177686ffa4e2beaca940d3ed4c35af3a00a7))
* **imageconfig,compose:** per-config quality badge and trending placement ([d39e30e](https://github.com/djsaikrishna/XRDB/commit/d39e30e64890bb9ae0e0f0d0b8d3be130e7e4f42))
* **imageconfig,compose:** per-config rating badge size and aggregate color ([1ab7373](https://github.com/djsaikrishna/XRDB/commit/1ab7373aaec1e4782c96db4ec0bc4d20b16b0e51))
* **imageconfig,compose:** per-provider rating accent overrides ([8b60bf6](https://github.com/djsaikrishna/XRDB/commit/8b60bf64cfa0c2d53cdebe747d438f82909a5e09))
* **imageconfig,compose:** scorebar band colors and thresholds ([04b8b1c](https://github.com/djsaikrishna/XRDB/commit/04b8b1c8ee71a29b2e122f31d3230da137c04840))
* **imageconfig,provider,web:** random-poster filters ([99668f2](https://github.com/djsaikrishna/XRDB/commit/99668f29ba3718927f5621bca526566b8f08f105))
* **imageconfig:** preserve unmodeled config fields through parse and cache ([5fa2218](https://github.com/djsaikrishna/XRDB/commit/5fa2218b5b1e9b0c29bf9dd6bf123bb2105c381b))
* **image:** improve plain quality badge readability and add poster badge offsets ([5a3d81b](https://github.com/djsaikrishna/XRDB/commit/5a3d81ba63d3a11d0babb33ddf12d84ccb5322c0))
* **integrations:** clarify TMDB first run onboarding prompt ([19eb930](https://github.com/djsaikrishna/XRDB/commit/19eb93053427ca863a9e8ff522d0edc391892f9d))
* **integrations:** refresh TMDB credentials from saved UI settings ([1b16b30](https://github.com/djsaikrishna/XRDB/commit/1b16b30de8b0b7193bc08cbb7cc0310f97df8751))
* **jellyfin:** add an image-provider plugin ([b68aa1c](https://github.com/djsaikrishna/XRDB/commit/b68aa1cddd815468eb57944df27835ee2d36e241))
* **logging:** add structured request and pipeline logging ([0da1218](https://github.com/djsaikrishna/XRDB/commit/0da12185dca2cbba80333a62febc3518b95dfc1c))
* **logging:** change log level at runtime from the admin dashboard ([7c68ad5](https://github.com/djsaikrishna/XRDB/commit/7c68ad5aaefab3897e367a4d98b645e565e0a536))
* **meta:** improve site title, description, and social preview metadata ([eacfd27](https://github.com/djsaikrishna/XRDB/commit/eacfd2727bd156111175249c15e828ee99e627c4))
* **migrate,badges:** carry genre badges, and style the trending tag ([9c2ff35](https://github.com/djsaikrishna/XRDB/commit/9c2ff35672c88249e7e4ab9f17c057055ce81499))
* **migrate:** map v2 quality-badge side onto the placement, refresh the doc ([00a41bf](https://github.com/djsaikrishna/XRDB/commit/00a41bf20090cbe9e0b086a35aaf7a3a4100a745))
* **migrate:** report what a migration could not carry, and why ([05e8ff9](https://github.com/djsaikrishna/XRDB/commit/05e8ff9de525d756b4c9416e6fc14d9f4c91cf5f))
* **migrate:** report which config fields render now versus are preserved ([bc642a1](https://github.com/djsaikrishna/XRDB/commit/bc642a1e95ca64f3bfcc1ed1787325d10b961e13))
* **migrate:** translate v2 profile configs into the shape XRDB renders ([08a9d24](https://github.com/djsaikrishna/XRDB/commit/08a9d2401ed7c48c52223e8a06e4075358888a9b))
* **poster:** add customizable trending tag styles and safe poster placement ([e262dd8](https://github.com/djsaikrishna/XRDB/commit/e262dd825cfa7e903b9780059e2ba9440e83c31d))
* **profile:** encrypt provider keys at rest and check them on save ([e9194a0](https://github.com/djsaikrishna/XRDB/commit/e9194a0e685735baa10cb6f4cd4f1700f4c9f808))
* **profile:** let an owner supply their own provider API keys ([128d8df](https://github.com/djsaikrishna/XRDB/commit/128d8df47ebf476e712b6161d89f055ca64d2e0e))
* **profile:** make import idempotent by legacy uuid ([fc3f1bc](https://github.com/djsaikrishna/XRDB/commit/fc3f1bcaac7146629e21040d782bbf3df7cc04d4))
* **provider,compose,web:** AlloCiné, AlloCiné Press and Filmweb rating sources ([af4cf12](https://github.com/djsaikrishna/XRDB/commit/af4cf123ea82c26522c86de0b1b73db3e3ae3bc9))
* **provider,compose,web:** OMDb as a poster artwork source ([d4a6c05](https://github.com/djsaikrishna/XRDB/commit/d4a6c050ce188c4b3b421906dcf4713c4607da45))
* **provider,compose,web:** release status badge ([99c970f](https://github.com/djsaikrishna/XRDB/commit/99c970f96bbaf2aa2415b55be225508d2a164829))
* **provider,compose:** fall back to a source's last good result ([fc6218d](https://github.com/djsaikrishna/XRDB/commit/fc6218d952ebaec3f1291c3bcdd0f0793645f820))
* **provider:** apply saved API keys to every provider without a restart ([2b4ab37](https://github.com/djsaikrishna/XRDB/commit/2b4ab373e8ac0aedc4839f1cdbacc74a81411e56))
* **provider:** compute a top-rated film ranking from the IMDb dataset ([6491403](https://github.com/djsaikrishna/XRDB/commit/64914039267555f9503f5aab64d9f4eb975f4851))
* **quality-badges:** add custom icon URL override support via qualityBadgeAppearance param ([4b41862](https://github.com/djsaikrishna/XRDB/commit/4b4186263b7630ef0a57e85f93c8ffe74ca346dc))
* **quality:** always check a quality badge against what the title has ([876dd27](https://github.com/djsaikrishna/XRDB/commit/876dd27aab0d14d7f4488bd3bb92bd6b188f8039))
* **quality:** draw quality badges only for releases that exist ([0138b68](https://github.com/djsaikrishna/XRDB/commit/0138b68290ccaaef9643781fe5b4c0144bc55fc0))
* **ratings:** add normalized clean value mode to trim trailing point zero ([80b2552](https://github.com/djsaikrishna/XRDB/commit/80b25528f214bb2d1e43b142318f19d0adabaec7))
* **ratings:** choose the scale rating values are drawn on ([4387a1b](https://github.com/djsaikrishna/XRDB/commit/4387a1b3371cb8b28bd1b135dff721c2bf59d8da))
* **ratings:** FR-54 add Filmweb provider support ([3573d97](https://github.com/djsaikrishna/XRDB/commit/3573d97372523ce5e2a47bb21f76096e6687cc9f))
* **ratings:** FR-60 customizable aggregate provider weights ([23cf3ec](https://github.com/djsaikrishna/XRDB/commit/23cf3ecf2e4e851ced372db75edd22185b258ad7))
* **render:** add the no-background and tile rating badge styles ([082c017](https://github.com/djsaikrishna/XRDB/commit/082c0179694af8bab04e4c04a1af3de10050478b))
* **render:** add the stacked rating badge style ([b5afd47](https://github.com/djsaikrishna/XRDB/commit/b5afd47e748f66eda188d4971b08d36b0b28ce15))
* **render:** deliver artwork as JPEG at a Stremio-sized tier ([59f1307](https://github.com/djsaikrishna/XRDB/commit/59f1307ac111d7e56a2c1ae9bad0bc5fe36e84e4))
* **render:** draw the left, right and top-bottom rating layouts ([92630d4](https://github.com/djsaikrishna/XRDB/commit/92630d45fe8c3f0e9c94559d773b2878feb1c71d))
* **render:** raise the badge scale ceiling and add two stacked toggles ([dce16e1](https://github.com/djsaikrishna/XRDB/commit/dce16e1defcffd2b4a7100b3103482a68c1d01ca)), closes [#8](https://github.com/djsaikrishna/XRDB/issues/8)
* **rings:** average rating ring + compact wings (FR-119) ([c58fd41](https://github.com/djsaikrishna/XRDB/commit/c58fd41111a5394ebed65750fa85abe547d6a8c1))
* **save:** conflict resolution and split login behavior ([7901109](https://github.com/djsaikrishna/XRDB/commit/79011090e9cd0d5c89e4058e59604653d65489d1))
* **scorebar:** add scorebar rating display mode ([a2fd415](https://github.com/djsaikrishna/XRDB/commit/a2fd415b598ce6a610bd5f3848ce702ace1dd428))
* **scripts:** add a release command that checks, tags and pushes ([b9608b6](https://github.com/djsaikrishna/XRDB/commit/b9608b6fda3845d77c31ee06d74b41316d687df2))
* **server,web:** add Cache-Control, ETag and a profile version token ([69bf4e5](https://github.com/djsaikrishna/XRDB/commit/69bf4e5c5829b49f95285672962fbb7a05882daf))
* **server:** accept RPDB-shaped artwork URLs ([0c17c9a](https://github.com/djsaikrishna/XRDB/commit/0c17c9ad80c21dbae57ef35c19f2ac28b42d7449))
* **server:** adjust the memory limit at runtime ([4f8bbc4](https://github.com/djsaikrishna/XRDB/commit/4f8bbc4b47dfada0fd7e1fa096288fb8a4cf246f))
* **server:** convert a v2 profile when it is imported ([1851988](https://github.com/djsaikrishna/XRDB/commit/185198816d78bcd07963a014323115694d682bc1))
* **server:** tune per-provider cache TTLs at runtime ([2df4e5a](https://github.com/djsaikrishna/XRDB/commit/2df4e5aae27663e528123af925df063ea3edb3d5))
* **stremio:** advertise the addon as configurable and serve /configure ([c6ff895](https://github.com/djsaikrishna/XRDB/commit/c6ff895829c82ec27c039c20bf751cc6086752ed))
* **stremio:** serve a profile-bound addon base ([5d1cb26](https://github.com/djsaikrishna/XRDB/commit/5d1cb262be21f94c836519184a9c12f31f91b350))
* **themes:** add guided slider legends and stabilize preview swatch editing ([dab6e5f](https://github.com/djsaikrishna/XRDB/commit/dab6e5f6d43ee08fd8b458f406256dc3eafe5726))
* **thumbnail:** render and rate series episodes per-episode ([ff4f78c](https://github.com/djsaikrishna/XRDB/commit/ff4f78c6a0ffe8acaf3be5083eb5fad8a8248b64))
* **tmdb:** accept tvdb: and tmdb:type: composite art ids ([659ac2d](https://github.com/djsaikrishna/XRDB/commit/659ac2d568cf7539806658ba1f5bb279d61c40f5))
* **trending:** configurable badge style with vector trend-up arrow ([76ac89e](https://github.com/djsaikrishna/XRDB/commit/76ac89ed4c9df7c666ae6560238e7e5d75b3634a))
* UI review ([01879b0](https://github.com/djsaikrishna/XRDB/commit/01879b0a2f779082a01132fb6e9e0c125955eb9c))
* **ui:** [WIP] FR-110 simplify configurator ([7872fce](https://github.com/djsaikrishna/XRDB/commit/7872fce3d307203b190359a3d94e08ae6c147f47))
* V3 frontend ([3587510](https://github.com/djsaikrishna/XRDB/commit/35875107f44f7d2aba7036ec121f23918bcc0e89))
* v3 redesign ([451cb28](https://github.com/djsaikrishna/XRDB/commit/451cb28d76ff596199f303bfcc4fc4dd1ccd7342))
* **v3:** add Go backend — server, providers, compose, profiles, settings ([a8d4a31](https://github.com/djsaikrishna/XRDB/commit/a8d4a31249c3b80ada1b59005f054a4b45d0ba52))
* **web,server:** convert a v2 config from the configurator ([5624b2d](https://github.com/djsaikrishna/XRDB/commit/5624b2dd216e128e1a60c17097ae3789c951e205))
* **web:** add a first-run orientation to the configurator ([66dc9e7](https://github.com/djsaikrishna/XRDB/commit/66dc9e70604c94b55f7a51f35eff8ce55473c4cb))
* **web:** add a Runtime admin tab for the memory limit and provider TTLs ([6e206b8](https://github.com/djsaikrishna/XRDB/commit/6e206b8acfc9274535904f2297882b34f7637137))
* **web:** add an in-app Help and documentation page ([678bca5](https://github.com/djsaikrishna/XRDB/commit/678bca566e4925ee6d6b46487721b6d436bd73cd))
* **web:** add redo and fix zero-offset display in advanced fields ([291d35a](https://github.com/djsaikrishna/XRDB/commit/291d35a10f3e7d075e248ea8611fd06584501661))
* **web:** add TMDB and IMDb attribution to a site footer ([2017065](https://github.com/djsaikrishna/XRDB/commit/2017065ff54fdb5059c95e7d0436ed8736b6fa9e))
* **web:** advanced styling controls in the configurator ([644fa96](https://github.com/djsaikrishna/XRDB/commit/644fa968a9d40aa6f2e4eec415911a35f61b853e))
* **web:** contextual help for artwork, text and presentation options ([f3bc273](https://github.com/djsaikrishna/XRDB/commit/f3bc2737db09f473c1dbea4ee0775226c422d634))
* **web:** give advanced styling its own configurator tab ([bdf3741](https://github.com/djsaikrishna/XRDB/commit/bdf37411149bac6ddd07c5ddc255fa32641c6ad6))
* **web:** make the keys page per-user and move server keys into admin ([84cfc48](https://github.com/djsaikrishna/XRDB/commit/84cfc48377eb9b77093695714d713aed0bd39565))
* **web:** pair advanced number fields with range sliders ([cb6c9ae](https://github.com/djsaikrishna/XRDB/commit/cb6c9aea6837585c955e0ed9fcea1758bfe0932a))
* **web:** per-provider rating accent override controls ([f5a52c6](https://github.com/djsaikrishna/XRDB/commit/f5a52c65e964d01e2fde14e1506fa84a71dfd388))
* **web:** scorebar band and trending text-color controls ([9c55b69](https://github.com/djsaikrishna/XRDB/commit/9c55b69a18cdd9c9d685e45e49a736ad6e5a777f))
* **web:** show the Stremio addon install URL on the Install tab ([1cacfdd](https://github.com/djsaikrishna/XRDB/commit/1cacfdd4124175f9f59e9af3f5a4e1e526d8fc2c))
* **web:** structure the advanced styling panel into titled sections ([1547204](https://github.com/djsaikrishna/XRDB/commit/154720452acd889e86bc95d6218b44e13020fc0e))
* **web:** surface the per-surface model and keep saved keys on screen ([54fa5f4](https://github.com/djsaikrishna/XRDB/commit/54fa5f470c0f73d2e6cb3e3b44db50f5c7bbc8c3))
* **web:** universal undo history and live 'updating' cue in configurator ([c3b8806](https://github.com/djsaikrishna/XRDB/commit/c3b8806e4ad9f4d563586f3844565ab5b8a58c8d))
* **workspace:** add panel section hierarchy to poster workspace ([665edbd](https://github.com/djsaikrishna/XRDB/commit/665edbdb0e5b69ea58b5bd9d72b2adfe67cc888e))


### Fixed

* address CodeRabbit review findings on PR [#31](https://github.com/djsaikrishna/XRDB/issues/31) ([bbb7aaf](https://github.com/djsaikrishna/XRDB/commit/bbb7aaf9beb29a7219765d0988626de784a13169))
* **admin:** admin panel shows blank page instead of login form ([ae48b39](https://github.com/djsaikrishna/XRDB/commit/ae48b39354a5c7fdb2f395d7e8dc177469fa64e0))
* **admin:** reject malformed warm config JSON instead of warming Default() ([b0241bc](https://github.com/djsaikrishna/XRDB/commit/b0241bcc3982ebfeace86975473f5da08a855550))
* **aiometadata:** repair encoded XRDB art placeholders in saved profiles ([06f374c](https://github.com/djsaikrishna/XRDB/commit/06f374c5a0094c79177ed0fa761e62464e17b1d1))
* anime ratings via self-managed ID mapping (replaces dead mapping service) ([3aac716](https://github.com/djsaikrishna/XRDB/commit/3aac716994d670ebc877a16af628af834e46eff3))
* **anime:** canonicalize episode authority across thumbnails and proxy exports ([4317410](https://github.com/djsaikrishna/XRDB/commit/43174106cfdede6ac2a2228f9481a55502036d15))
* **animemap:** handle Fribb imdb_id array format and index all aliases ([#38](https://github.com/djsaikrishna/XRDB/issues/38)) ([7ad586a](https://github.com/djsaikrishna/XRDB/commit/7ad586a2066eb3dee250885962adf708793a079b))
* **animemap:** make primary cold-load single-flight; tighten supplement-off test ([a811c7d](https://github.com/djsaikrishna/XRDB/commit/a811c7db04b7264473211dda8004fed768453988))
* **animemap:** make single-flight cold-load cleanup panic-safe ([64db2b5](https://github.com/djsaikrishna/XRDB/commit/64db2b55a0e862fffb7486c4d6b6494a40cb2922))
* **badge-customization:** remove age rating from custom icon overrides ([fa630d2](https://github.com/djsaikrishna/XRDB/commit/fa630d2e57b535d23132ac5bde76aece9dfb17d5))
* **badges:** draw brand marks in their own colours ([658bd20](https://github.com/djsaikrishna/XRDB/commit/658bd202f9062536fc6fa7e8412bd40a56eb16cd))
* **build:** restore the internal/ui/dist placeholder ([5642e76](https://github.com/djsaikrishna/XRDB/commit/5642e76882473ae9de9b296ab0f8163aaf825e45))
* **cache:** bound the render cache and stop stats directory scans ([d35f9af](https://github.com/djsaikrishna/XRDB/commit/d35f9af737ee21d9bc03b2d3a69b739ec9c48d97))
* **cache:** cap the TTL of a render missing a rating badge ([7e7d7ae](https://github.com/djsaikrishna/XRDB/commit/7e7d7ae2c54e14873cc403a49fb9dbce8763ec54))
* **cache:** make metadata cache pruning deterministic on every write ([b527df4](https://github.com/djsaikrishna/XRDB/commit/b527df4261f8669998066f188245447005420335))
* **cache:** only a throttled source shortens a render's TTL ([a861ed0](https://github.com/djsaikrishna/XRDB/commit/a861ed0967b369c8498a825ae00bd8c5910c9444))
* **cache:** stop the disk counters drifting against the sweep ([841bbee](https://github.com/djsaikrishna/XRDB/commit/841bbee4f471de80f2b4aa48200df0b532e9dbc1))
* **cache:** tighten image cache pruning ([6979e02](https://github.com/djsaikrishna/XRDB/commit/6979e02fd40d2bbd27b9e57e4e09e54318f41674))
* **catalog:** replace Google S2 favicon URLs with direct gstatic faviconV2 URLs ([2e1cbc6](https://github.com/djsaikrishna/XRDB/commit/2e1cbc63102ecde6be1ece0bf6d178b7f57dd23e))
* **changelog:** reset Unreleased template during changelog updates ([e225144](https://github.com/djsaikrishna/XRDB/commit/e22514498951e21593022d766d98a2e6db4e0142))
* **ci:** auto-catch up missed dev Discord notifications ([ef6eed2](https://github.com/djsaikrishna/XRDB/commit/ef6eed2c48a619bb40a6f890b4f5e3d289f7418b))
* **ci:** fix Go and web lint failures ([ba70126](https://github.com/djsaikrishna/XRDB/commit/ba7012691de9808a241999eeba358c397f07bc8b))
* **ci:** fix Go and web lint failures ([21a97bb](https://github.com/djsaikrishna/XRDB/commit/21a97bbaf6b4ef03d0f767ddbfe87204af83ccc9))
* **ci:** resolve docker runtime package failure and harden action runtime compatibility ([13a80ec](https://github.com/djsaikrishna/XRDB/commit/13a80ec88cfa76dffd0d78a1fa7c873a4ec23d35))
* **ci:** stop truncating dev build release notes ([dcb3588](https://github.com/djsaikrishna/XRDB/commit/dcb3588a1df8bc877088edc9e82089d55c1c4651))
* **ci:** tag :latest during the release build ([3ba8948](https://github.com/djsaikrishna/XRDB/commit/3ba89484541d7530f5995c8382f2bf00d053dbb3))
* **ci:** use last successful dev tag as Discord compare base ([31a54dc](https://github.com/djsaikrishna/XRDB/commit/31a54dcaca70350d99602cbead07d2c2cca5a552))
* **compose,web:** address CodeRabbit round-2 findings on PR [#32](https://github.com/djsaikrishna/XRDB/issues/32) ([e4e53e7](https://github.com/djsaikrishna/XRDB/commit/e4e53e72702aa52d44f3b36745d41631ba26daa2))
* **compose:** add bottom-edge clamp to split-side stacks; use URL.origin in normaliseOrigin ([a55cedd](https://github.com/djsaikrishna/XRDB/commit/a55cedd4e44cfeaab0251c380b73c28d020b0b7a))
* **compose:** address CodeRabbit round-1 findings on provider badges ([a08787c](https://github.com/djsaikrishna/XRDB/commit/a08787c24b0d572750d810ad011838824a4fb3b2))
* **compose:** address CodeRabbit round-3 findings on PR [#35](https://github.com/djsaikrishna/XRDB/issues/35) ([c234780](https://github.com/djsaikrishna/XRDB/commit/c234780dcc4bd5697d044e58dfbdd5c019880c17))
* **compose:** anti-alias badge corners and ring edges (BUG-160) ([e6b3769](https://github.com/djsaikrishna/XRDB/commit/e6b376918899d3940709baf01a89704757de2f61))
* **compose:** backdrop poster auto-shows logo; HDR hierarchy dedup; badge polish ([3e15746](https://github.com/djsaikrishna/XRDB/commit/3e157461b3b3946caceda03f40f16dd5dca592b3))
* **compose:** blend trending badge sheen instead of overwriting pixels ([c552355](https://github.com/djsaikrishna/XRDB/commit/c552355f979371c3f564d4a9bdd38b00d19a1d82))
* **compose:** correct Porter-Duff alpha blending in drawLogoScaled ([401aa47](https://github.com/djsaikrishna/XRDB/commit/401aa47a83c241dfccb5f794af04bfc028aa0cd9))
* **compose:** draw a plate behind shaped rating icons ([b34a70a](https://github.com/djsaikrishna/XRDB/commit/b34a70a42522ec909f078f0506b8a8a453c97756))
* **compose:** draw the trending badge only for trending titles ([7f2ae1a](https://github.com/djsaikrishna/XRDB/commit/7f2ae1a28802490f66f58a7d421951223cc02fbb))
* **compose:** give the square and clean genre styles their own look ([2eba985](https://github.com/djsaikrishna/XRDB/commit/2eba9852c9853d37517332e61cb9c5c609bf52ee))
* **compose:** increase output resolution and enlarge rating badge icons ([7fdcf09](https://github.com/djsaikrishna/XRDB/commit/7fdcf09c2298248d3395cae6324bb3b8c700488d))
* **compose:** overlay the title logo for clean artwork ([fde2e72](https://github.com/djsaikrishna/XRDB/commit/fde2e726513c6e39b11b33e7141fb1d3d2c58711))
* **compose:** remove wings overlay, sharpen rendering quality ([156ee5b](https://github.com/djsaikrishna/XRDB/commit/156ee5b2c53cdc6087a51669093a8e530f2fd2e3))
* **compose:** resolve non-IMDb ids before asking rating sources ([22f548c](https://github.com/djsaikrishna/XRDB/commit/22f548ca496b76ae48601ce71246f8895bc805ba))
* **compose:** size corner overlays to the canvas ([7d3432e](https://github.com/djsaikrishna/XRDB/commit/7d3432ed3ee3dd9a5177598d4627a3357f63d0c3))
* **compose:** stop overlay collisions and provider duplicates ([0ff99bc](https://github.com/djsaikrishna/XRDB/commit/0ff99bcef886e797953c06ace32f9671aaf97612))
* **config-profile:** keep UUID profiles recoverable after admin password reset ([6a370d6](https://github.com/djsaikrishna/XRDB/commit/6a370d62106ba7fb84bb9a2a27ff9669ded74c51))
* **config-profiles:** preserve xrdb key in saved profiles ([97db626](https://github.com/djsaikrishna/XRDB/commit/97db62615b8ba2314d1a634b166d294a44d78ddb))
* **config:** accept the badge placement spellings a v2 config uses ([236de0e](https://github.com/djsaikrishna/XRDB/commit/236de0e2fb2c992a991aae7d2c55db3aaa070f47))
* **config:** fall back to the poster surface, not stock defaults ([1bed50c](https://github.com/djsaikrishna/XRDB/commit/1bed50c0f0c340b6d2398883d4cba526ea67ccb1))
* **config:** honour more v2 rating and badge settings ([2097c86](https://github.com/djsaikrishna/XRDB/commit/2097c8660ff4deac952b8e5223245fa3cd968e06))
* **config:** let an empty rating selection mean no rating badges ([d3764e1](https://github.com/djsaikrishna/XRDB/commit/d3764e199ef4f2dcf78603c1bb3ed1029feee863))
* **config:** map the remaining v2 enum spellings ([9d0d883](https://github.com/djsaikrishna/XRDB/commit/9d0d883540f6f06fcf08958cb1a778e0ffe08a99))
* **config:** read a v2 badge list as tiles plus its features ([da77888](https://github.com/djsaikrishna/XRDB/commit/da778886262c9a6f78dc3dbe09c70255358e8e00))
* **config:** read the v2 credential names as a fallback ([f97cdf7](https://github.com/djsaikrishna/XRDB/commit/f97cdf7d5d58c00a445e3ec3d095e545273688a9))
* **config:** stamp the version into the binary instead of the image env ([6ffc51c](https://github.com/djsaikrishna/XRDB/commit/6ffc51c14ad8a51b913649945f27bc61a0627c5c))
* **config:** treat a zero badge cap as no cap ([4af534f](https://github.com/djsaikrishna/XRDB/commit/4af534f986fa8da62780ef7e1f094e06ec33f187))
* **configurator:** address review — validate surfaces, harden config parsing ([ac44144](https://github.com/djsaikrishna/XRDB/commit/ac44144f96c2fc04d42f1ea975b03c16ed2bcf20))
* **configurator:** BUG-117 restore genre badge position control for tile dark style ([7e7c714](https://github.com/djsaikrishna/XRDB/commit/7e7c714c516ed01b345486324c34af360de4f45f))
* **configurator:** BUG-120 preserve quality badge placement across release status style changes ([e7bc374](https://github.com/djsaikrishna/XRDB/commit/e7bc3744f281ccdf208fc40496eaf27b77de9d7c))
* **configurator:** BUG-122 isolate black bar overlay by artwork type ([5a78846](https://github.com/djsaikrishna/XRDB/commit/5a788468589b55f3282aa9d94209ffdd6582a3a2))
* **configurator:** BUG-126 black bar overlay changes not saved to profile ([d861f54](https://github.com/djsaikrishna/XRDB/commit/d861f5493f455c66aeff4009840ec436efe856c6))
* **configurator:** BUG-149 hide floating preview toggle on mobile ([2bcad13](https://github.com/djsaikrishna/XRDB/commit/2bcad135b4ac01f88bd6c8ad35dde89eb7cae8e6))
* **configurator:** canonical AIOMetadata instance labels in install panel ([66898e8](https://github.com/djsaikrishna/XRDB/commit/66898e8714d04c1db61a0c06414a691aecf6688b))
* **configurator:** enforce type scoped option edits and sync-only cross type propagation ([c9cbc9f](https://github.com/djsaikrishna/XRDB/commit/c9cbc9f94cebbda19dae1a09b649d55aa3f015a6))
* **configurator:** gate install UI behind a saved profile ([b8ebaba](https://github.com/djsaikrishna/XRDB/commit/b8ebaba70b8e32bbc629dbfe23097a87fcfc061e))
* **configurator:** include docs capture in preview memo dependencies ([39523cf](https://github.com/djsaikrishna/XRDB/commit/39523cfe5dde2376e9db08ac594e80dbaec37d7c))
* **configurator:** quality pass — scaling, layout bugs, cache buster, AIOM dropdown ([f26fa53](https://github.com/djsaikrishna/XRDB/commit/f26fa53a950dd9a82beb8a9debb4a940ab46e510))
* **configurator:** resolve completed redesign regressions from today LS tracker ([5f6482b](https://github.com/djsaikrishna/XRDB/commit/5f6482b2f710e50922311bd8498862c3891cf59e))
* **configurator:** restore community badge theme selection in all workspaces ([ce77630](https://github.com/djsaikrishna/XRDB/commit/ce77630e6b2f47a8116f861c8ec404c4827fe891))
* **configurator:** restore custom badge icon controls and display mode toggle ([03bdcd1](https://github.com/djsaikrishna/XRDB/commit/03bdcd1ceed85209f979c14576eb76abe2251602))
* **configurator:** restore custom provider icon URL editing across artwork workspaces ([d4d4cd4](https://github.com/djsaikrishna/XRDB/commit/d4d4cd47ab9011e3bc165ba84b99a06a2f6fe0ea))
* **configurator:** restore drag reorder for rating providers ([4a3f2c1](https://github.com/djsaikrishna/XRDB/commit/4a3f2c15bc634ecfada06536eca29f777e1a1b84))
* **configurator:** restore poster quality badge offset controls in UI ([a83e415](https://github.com/djsaikrishna/XRDB/commit/a83e415c12f340564d48cc42d237d246a917bcf0))
* **context:** stamp a release tag and stop rewriting the timestamp ([a1d7eea](https://github.com/djsaikrishna/XRDB/commit/a1d7eeaf9aa572b7dc98152e0a6157a65c13ddc3))
* **discord:** remove duplicate release bullets and add explicit UK publish time ([2e8f5df](https://github.com/djsaikrishna/XRDB/commit/2e8f5dfa6bbfc97b29e0575cb321bee55fc11604))
* **docs:** refresh script hanging on static asset capture ([4698d6a](https://github.com/djsaikrishna/XRDB/commit/4698d6a34577859cc986f8aec1e76aa78d3fddac))
* **docs:** Refresh static assets. ([a8ce561](https://github.com/djsaikrishna/XRDB/commit/a8ce561c4fee47923b59eac3c2c7d3b0e5fd8f91))
* **docs:** restore docs-capture ready signal to proxy page ([9b4420a](https://github.com/djsaikrishna/XRDB/commit/9b4420a3fcb7f0780203afcbee646526f22ad711))
* **docs:** simplify capture readiness condition to prevent memory exhaustion ([ee04f98](https://github.com/djsaikrishna/XRDB/commit/ee04f982c101e16d3d33e61c78af6b43c810664b))
* **docs:** stabilize docs capture preview flow ([53b5a67](https://github.com/djsaikrishna/XRDB/commit/53b5a67d07b4bb896b16d1042ea2ccde39b46d65))
* **entry:** feature logo mark on home page hero ([49570ed](https://github.com/djsaikrishna/XRDB/commit/49570ed9cbafc1c584b33d1e07d10f1ba766ecd4))
* **entry:** read instance branding html at runtime ([a4094c9](https://github.com/djsaikrishna/XRDB/commit/a4094c99408b2332bdc992c91a877219e8cc1a36))
* **entry:** show signed-in indicator and update action when authenticated ([5dfeb85](https://github.com/djsaikrishna/XRDB/commit/5dfeb851e2d796d6691bc07c8c632a0b47516042))
* **export:** preserve anime season tokens in AIOM thumbnail urls ([e0caa0a](https://github.com/djsaikrishna/XRDB/commit/e0caa0a596688e1047a7f4e2b6e95c0680d4d221))
* **export:** repair xrdb and simkl custom-art placeholders ([2456b39](https://github.com/djsaikrishna/XRDB/commit/2456b39523bf88b3336329e659238933fdddd7b9))
* **feeds:** stabilize nowMs initial value to prevent SSR hydration mismatch ([d59ef8c](https://github.com/djsaikrishna/XRDB/commit/d59ef8cd9310298680ec3a2d221ac3e95e1ca3b2))
* **genre-badge:** preserve fantasy classification with TMDB combined sci fi genres ([538ab17](https://github.com/djsaikrishna/XRDB/commit/538ab17e74af9b32ceff8481844f55d49a1e81ab))
* **ids:** BUG-143 recover malformed TMDB poster IDs from TMDB source exports ([94a7a6c](https://github.com/djsaikrishna/XRDB/commit/94a7a6c69085505e17a34aa673de4470e30b2b3c))
* image build ([4cab7dd](https://github.com/djsaikrishna/XRDB/commit/4cab7dd46cfa8f450dc5beb94516c63bbd12d062))
* **image-route:** restore clean poster textless selection and clean branding behavior ([b61cda8](https://github.com/djsaikrishna/XRDB/commit/b61cda8239bafcf460c3ced0335a42a2dac1caa1))
* **image:** BUG-114 preserve regional TMDB poster locale selection ([7ed9698](https://github.com/djsaikrishna/XRDB/commit/7ed96984551365fbb1eb829f264a794225f425a0))
* **imageconfig:** satisfy staticcheck in the hex colour check ([a81c6e6](https://github.com/djsaikrishna/XRDB/commit/a81c6e65f75d3695354c973f4a51fc49efbbe92a))
* **imageRouteSourceFetch:** BUG-135 Add timeout to source image fetches ([63a3a20](https://github.com/djsaikrishna/XRDB/commit/63a3a202a97472bf1d83495f2e0ea059795a55fa))
* **integrations:** prevent first load crash on Integrations page ([8c2c322](https://github.com/djsaikrishna/XRDB/commit/8c2c32247346d6179cc327d981813a1dcc8b2166))
* **integrations:** suppress tmdb onboarding when settings load fails ([eeec764](https://github.com/djsaikrishna/XRDB/commit/eeec7642cf6d10d16e9395708ae660e09b60fe86))
* **integrations:** tighten TMDB onboarding gating and dedupe media credential checks ([b8268eb](https://github.com/djsaikrishna/XRDB/commit/b8268eb012b1e50257232180d4768b8d6c5f5a48))
* **jellyfin:** add the missing MediaBrowser.Common.Net import ([98292f5](https://github.com/djsaikrishna/XRDB/commit/98292f5fa37a13e1b49b07e42d268e69fe4bc4ba))
* **layout:** prevent logo artwork from being compressed by oversized badge bands ([0334bf3](https://github.com/djsaikrishna/XRDB/commit/0334bf3b61b8810fb83fe20f67b65a679cfc4b16))
* **localization:** BUG-121 enforce regional translation paths across proxy and poster rendering ([362d8ca](https://github.com/djsaikrishna/XRDB/commit/362d8caf02058e3f9642d91716b15598d5a4ba34))
* **logo-ratings:** BUG-129 align auto limited provider logo rendering ([dbf46b0](https://github.com/djsaikrishna/XRDB/commit/dbf46b03f6bcd81cb4ecaa2c4a8e6338f06061d0))
* **logo-rendering:** FR-75 FR-62 adaptive single-row logo ratings and TMDB logo safe-frame centering ([a94eb77](https://github.com/djsaikrishna/XRDB/commit/a94eb772a8751d71e8563ad831b72467c012d611))
* **metadata:** resolve social metadata URLs from runtime host ([e60dc0b](https://github.com/djsaikrishna/XRDB/commit/e60dc0b9eba16414858f6852f5be38300155e3ab))
* **migrate,server:** make the documented v2 migration path actually work ([020d628](https://github.com/djsaikrishna/XRDB/commit/020d628c29f31456bda0319d2169c2b14ea3bcf2))
* **migrate:** carry an empty v2 list as an empty selection ([caf0fab](https://github.com/djsaikrishna/XRDB/commit/caf0fabf47d50d05de19ad6398f3bae9952f9291))
* **migrate:** map v2's glass rating style onto pill ([1494b73](https://github.com/djsaikrishna/XRDB/commit/1494b73920d759d0305b7e9e8464bf8a3162cb9c))
* **migrate:** read v2 values that were stored as strings ([878f297](https://github.com/djsaikrishna/XRDB/commit/878f297c931a8cffe62dc0a224c80b42f4833485))
* **migrate:** v2 streamBadges is the quality check, not streaming chips ([175e6ea](https://github.com/djsaikrishna/XRDB/commit/175e6ead6417abb80a9ac042ac0eb92ea059b9f5))
* **nav,panels:** stabilize tab strip alignment; restore clean overlay strength control ([8df7622](https://github.com/djsaikrishna/XRDB/commit/8df7622fc8ea671167907e50bc4ea745727a4b3e))
* **nav:** BUG-138 restore mobile access to Poster and Backdrop tabs ([987af1b](https://github.com/djsaikrishna/XRDB/commit/987af1b876bd68edabfbc59723eb40d93aca78ae))
* **nav:** collapse theme mode switcher to icon popover on mobile ([a00eec0](https://github.com/djsaikrishna/XRDB/commit/a00eec0293930a9027b3882257b6eb3b68f611d0))
* **nav:** move build meta chip outside home link to resolve nested anchor errors ([c407b1a](https://github.com/djsaikrishna/XRDB/commit/c407b1ab0064e3d61fd2c4a3d35c1cb27d2f8b87))
* **nav:** prevent header metadata overlap in workspace chrome ([8a897ad](https://github.com/djsaikrishna/XRDB/commit/8a897ade76bf706b87342153650328a969ad353f))
* **nav:** restore edge alignment and center primary tabs in header ([ea1a55b](https://github.com/djsaikrishna/XRDB/commit/ea1a55b1f0d9835b7ac95e3c10668341c9cae457))
* **panels:** expose badge size controls for all artwork types ([d651d04](https://github.com/djsaikrishna/XRDB/commit/d651d04550e78c144a923f6e6ac3802eaecc650d))
* **poster:** keep trending preview tags factual ([67d2f11](https://github.com/djsaikrishna/XRDB/commit/67d2f115fa8490f8d69d82dbb54896989bfc821c))
* **poster:** preserve trending tag styling across exported artwork outputs ([4f14dab](https://github.com/djsaikrishna/XRDB/commit/4f14dab6bb0b3855114fdd2778a47dbae24aefed))
* **poster:** stabilize quality badge layout and restore age rating toggle ([fb44f5f](https://github.com/djsaikrishna/XRDB/commit/fb44f5f8bcbe5f26424624c0b597c0f1cf62b81f))
* **preview:** restore trending tag preview updates ([b5b431a](https://github.com/djsaikrishna/XRDB/commit/b5b431a49773d862550f74e705e556c6ddb4f387))
* **profile,imageconfig:** close review gaps in migration safety ([caf8a46](https://github.com/djsaikrishna/XRDB/commit/caf8a462f5449e2c2520215a058fc6d312b96246))
* **profile:** resolve profiles by legacy uuid so migrated v2 URLs keep working ([c632ec0](https://github.com/djsaikrishna/XRDB/commit/c632ec008196b0fe4fc7c744362434890f41eb45))
* **profiles:** resolve alias in the export route ([8f797b2](https://github.com/djsaikrishna/XRDB/commit/8f797b28bae14c5a1b8412b817add66d15316362))
* **provider:** keep credentials out of transport error logs ([5e43f0d](https://github.com/djsaikrishna/XRDB/commit/5e43f0d4446971a759dc8cc8ffc556ff1ffef3f3))
* **provider:** restore RT audience — map MDBList "popcorn" source to rtaudience ([06f7d38](https://github.com/djsaikrishna/XRDB/commit/06f7d385553b8790b1ec32bf0329ed9a8e618758))
* **provider:** retry rate-limited requests and pace each source ([31d5aee](https://github.com/djsaikrishna/XRDB/commit/31d5aeea7f8ed7ae58adda98aba587aeca51f8c7))
* **provider:** stop Fanart serving a movie record for a series (BUG-168) ([17e9e6b](https://github.com/djsaikrishna/XRDB/commit/17e9e6b233aec2331fff0b939f094edade3fef24))
* **provider:** verify Fanart records by TMDB id, not title (BUG-168) ([773cf2b](https://github.com/djsaikrishna/XRDB/commit/773cf2bfe0cab6060529645dca1b3363bb1b88db))
* **proxy:** add missing badge keys to proxy config schema ([7e329e9](https://github.com/djsaikrishna/XRDB/commit/7e329e96077addf7034a180e710b8da4d33134cc))
* **proxy:** BUG-125 keep UUID proxy addon identity stable ([0aa9bbb](https://github.com/djsaikrishna/XRDB/commit/0aa9bbb820024fe29a7ecf6b0c744c95483915d6))
* **quality-badge-placement:** BUG-127 calculate badge width per row to prevent overflow ([51e89bf](https://github.com/djsaikrishna/XRDB/commit/51e89bfb240832abbcfa2045164ae0c525b5373d))
* **quality-badges:** BUG-127 keep custom quality badges aligned when scaled ([e2b2ec8](https://github.com/djsaikrishna/XRDB/commit/e2b2ec88eff0a13e60f9ff10029e0a97d34150ca))
* **quality:** read the stream description when detecting qualities ([5df51e9](https://github.com/djsaikrishna/XRDB/commit/5df51e954f3e78bf6d1df47c74f63f3ef7c1cf5b))
* **ratings:** BUG-137 stabilize rating logos and BUG-131 protect custom badge save flow ([425ecaa](https://github.com/djsaikrishna/XRDB/commit/425ecaa3ccfe5cf8e7947d58b1f29009d5fa7863))
* **ratings:** decouple artwork surface from content type ([e98f156](https://github.com/djsaikrishna/XRDB/commit/e98f15676e9ae00b15febe9ef42daca24d06a605))
* **ratings:** rebalance tile dark badge value spacing and centering ([20b12f6](https://github.com/djsaikrishna/XRDB/commit/20b12f6756ed18271fde22a5577148acd10c7597))
* **release:** discord release notes now render bullet markers correctly ([40ad97c](https://github.com/djsaikrishna/XRDB/commit/40ad97c0e11a423db38a381f82e01ff02bbf5a68))
* **release:** unify docs refresh gate and support v2 README changelog links ([40d5dec](https://github.com/djsaikrishna/XRDB/commit/40d5dec2ad188cbf63dbd4ee8324507d083a0fc3))
* **renderer:** BUG-118 prevent compact ring overlap with age rating and grouped badges ([1b3fe38](https://github.com/djsaikrishna/XRDB/commit/1b3fe3896f6c9a952e276f2bdfa06aed5586e2cb))
* **renderer:** BUG-119 unify custom quality badge full surface rendering and icon fetch reliability ([301879e](https://github.com/djsaikrishna/XRDB/commit/301879ecae1f8fa1a52ee56829d08f51525da83a))
* **renderer:** BUG-123 normalize logo badge icon scale in auto mode ([95b1cb6](https://github.com/djsaikrishna/XRDB/commit/95b1cb6ad02af26b428da69939c29e2e45e2f8ae))
* **renderer:** BUG-124 restore custom quality badge scaling for 4k outputs ([15ab8ae](https://github.com/djsaikrishna/XRDB/commit/15ab8ae8eb0866e4530c8d20297e756cc1d62c82))
* **renderer:** BUG-143 add full trending tag anchor parity for poster overlays ([6488514](https://github.com/djsaikrishna/XRDB/commit/6488514ddf6b7cfc4515f0dde27fa3db86ee65ca))
* **renderer:** BUG-143 normalize provider icon footprint and soften plain badge surface fade ([512baed](https://github.com/djsaikrishna/XRDB/commit/512baede0379e625551eb85e5c1294a63913fc7c))
* **renderer:** BUG-143 prevent clean genre text overlap with trending labels ([a41057c](https://github.com/djsaikrishna/XRDB/commit/a41057c806cc7134e7c97eea79ead9d6086a30d3))
* **renderer:** BUG-144 keep trending overlays proportional across poster sizes ([7c6e1ee](https://github.com/djsaikrishna/XRDB/commit/7c6e1ee9a8a88fe9cfc7536fa5302fbe3aeb0e64))
* **renderer:** BUG-145 make score bar styles refresh and render distinctly ([54a4344](https://github.com/djsaikrishna/XRDB/commit/54a4344a782fd4b7e6273a481c06108ce074159a))
* **renderer:** BUG-146 smooth clean scrim and auto-minimal trending stack ([37026b0](https://github.com/djsaikrishna/XRDB/commit/37026b048ac4dc3491ed858dd5a82609556f41b2))
* **renderer:** BUG-148 prevent genre and trending badge overlap ([af44ad3](https://github.com/djsaikrishna/XRDB/commit/af44ad3d04ab918cb62ed8e3d432c5d1975c67fd))
* **renderer:** FR-91 localize clean genre badge labels ([335aa5b](https://github.com/djsaikrishna/XRDB/commit/335aa5b3093830003e61a772b2265c2e80dfdf2b))
* **renderer:** prevent badge group pileup by nudging quality overlays away from occupied regions ([58b44c7](https://github.com/djsaikrishna/XRDB/commit/58b44c730bb3f39b3a0542434ac3f8a752059f63))
* **render:** handle mislabeled custom badge SVG icons ([7600fc7](https://github.com/djsaikrishna/XRDB/commit/7600fc7d24f7af779302991ad62718f512ad618a))
* **render:** improve custom SVG badge icon reliability ([fa27291](https://github.com/djsaikrishna/XRDB/commit/fa272913e4884a886f3f743e1a750b267f6791ca))
* **render:** thumbnails prefer backdrop artwork ([b7b730d](https://github.com/djsaikrishna/XRDB/commit/b7b730d62a1ab2b7d353020b7d7c21561cb99595))
* **runtime:** BUG-133 harden sqlite startup against bind mount permission failures ([bc4f069](https://github.com/djsaikrishna/XRDB/commit/bc4f0693b736ddb56e77b6e476ce046992b30fde))
* **save:** save button and login preserve ([544abe6](https://github.com/djsaikrishna/XRDB/commit/544abe6a3b9b2d09caf9fac9cd608b4e5697b356))
* **save:** settings no longer reset silently when loading a profile ([e6c398d](https://github.com/djsaikrishna/XRDB/commit/e6c398d5b838e3f2e4a01d2c15ad76d6b7e1e71a))
* **scripts:** add curl timeouts to visual-test.sh to prevent hangs ([aa1a6ad](https://github.com/djsaikrishna/XRDB/commit/aa1a6adac15b39195d1048e4fe2a385c3bbf1a3e))
* **scripts:** always use a fresh capture server for workspace viewport screenshots ([db039c0](https://github.com/djsaikrishna/XRDB/commit/db039c01ff41ab4bf1c444fabf07eac37674786f))
* **scripts:** do not abort the release when a tag fetch is rejected ([c477886](https://github.com/djsaikrishna/XRDB/commit/c4778868b5698d40eedfb3efcf9df8db06298795))
* **scripts:** force-fetch marker tags so the refresh succeeds ([cf6ff53](https://github.com/djsaikrishna/XRDB/commit/cf6ff53eac2645e19e317fafc1d52ce3b77229ea))
* **scripts:** harden visual-test.sh port guard and failure tracking ([879f0d4](https://github.com/djsaikrishna/XRDB/commit/879f0d44dca5ae4dd57fd41a7640c4480fb634b2))
* **scripts:** increase Next.js dev server heap limit for doc asset refresh ([4239a03](https://github.com/djsaikrishna/XRDB/commit/4239a03783f0544880ce62c4e9511144c403bc0a))
* **scripts:** prevent doc capture timeout on proxy route compilation ([a88ac0d](https://github.com/djsaikrishna/XRDB/commit/a88ac0db4a8ce67f5ebfa8fed23d235d24eb6e60))
* **scripts:** use Turbopack for doc asset capture server to prevent OOM ([4975df3](https://github.com/djsaikrishna/XRDB/commit/4975df390808564f3f47a5d589ed9f3fe916561b))
* **security:** harden remote badge icon fetches ([62e15aa](https://github.com/djsaikrishna/XRDB/commit/62e15aa220628d46877fae7443b52417dd793cdc))
* **server:** accept v2-shaped artwork ids ([26efe14](https://github.com/djsaikrishna/XRDB/commit/26efe144b444dd83c705a9b567280a6e0211cc94))
* **server:** cap render concurrency to prevent OOM under load ([fb1f6ab](https://github.com/djsaikrishna/XRDB/commit/fb1f6ab4b45e7722fdbe0e612775e1faf87e58ad))
* **server:** capitalize a refused-save message for display ([3dd7f80](https://github.com/djsaikrishna/XRDB/commit/3dd7f807fc7461f6f24ff429cc121a4784b20a87))
* **server:** gate forwarded headers behind a trusted-proxy list ([ffe0ec9](https://github.com/djsaikrishna/XRDB/commit/ffe0ec950fcf2b5e01d093a76e6a8a8d454f58bf))
* **server:** let the configurator preview render on a keyed instance ([5a2cb0f](https://github.com/djsaikrishna/XRDB/commit/5a2cb0f3af1cc8b2eb38351f1dcfd0eb91801773))
* **server:** serve render placeholders as non-cacheable 404 ([ab732b0](https://github.com/djsaikrishna/XRDB/commit/ab732b03e04377e9284867f8e13e47f2ad10a356))
* **server:** surface AIOMetadata credential errors ([c37e755](https://github.com/djsaikrishna/XRDB/commit/c37e7554d5af25b36d69efceb4f8a5ec8e2db4fb))
* **step-shell:** correct browser timeout ref typing ([5b9e6a3](https://github.com/djsaikrishna/XRDB/commit/5b9e6a31dcedc997c235258c178ec20adb3d280c))
* **step-shell:** reduce client-server hydration mismatch noise on search input ([2046b97](https://github.com/djsaikrishna/XRDB/commit/2046b977857f52c5e63dd7ae30c9e25d4c9ba836))
* **step-shell:** restore back button, simplify nav labels, fix inspect visibility ([ec06b2d](https://github.com/djsaikrishna/XRDB/commit/ec06b2d2606f49fd4306a91d758e0ead768c322d))
* **styles:** BUG-147 inline toggle layout now keeps label and toggle adjacent ([20b822b](https://github.com/djsaikrishna/XRDB/commit/20b822be2eb9c15424979fd3937a1034dda21ece))
* **sync:** include rating style and icon shape in cross type sync with generated sync matrix docs ([a0ff8e0](https://github.com/djsaikrishna/XRDB/commit/a0ff8e08f4f1708d026c294d302d3f1c6bfae19a))
* **tmdb:** resolve a duplicate IMDb id to the right record ([5d4f392](https://github.com/djsaikrishna/XRDB/commit/5d4f392f9c86ac4c0a355c3c2233d2db24709102))
* **tmdb:** skip SVG logos the renderer can't decode ([9ef9a62](https://github.com/djsaikrishna/XRDB/commit/9ef9a62176281a5427295262e3d7921d7185d8cb))
* ui polish and refinements ([d047b0a](https://github.com/djsaikrishna/XRDB/commit/d047b0ad105a6f02a3e34fe2d876c12666537080))
* **ui:** BUG-143 hide genre position control for clean poster genre style ([7fd5f47](https://github.com/djsaikrishna/XRDB/commit/7fd5f47bebfdbcaa85a596e16b485f5293fc4dcd))
* **ui:** ensure embed dist path exists in ci with tracked placeholder ([781d8e4](https://github.com/djsaikrishna/XRDB/commit/781d8e4d44378199de0ceb0f662da3635fa4f7c2))
* **ui:** polish dropdown layering and readability in repair and search panels ([28d427a](https://github.com/djsaikrishna/XRDB/commit/28d427aeaf5d8e0aadb33af9f122c66e96777f80))
* **ui:** restore missing aggregate color controls ([95aafa1](https://github.com/djsaikrishna/XRDB/commit/95aafa11fa4fa52969c1692a17438e6d31f982e0))
* **web:** build install URLs from the item id, not the IMDb id ([7642298](https://github.com/djsaikrishna/XRDB/commit/76422988aa552b3df5cd6813868619b373845974))
* **web:** coalesce undo history and clamp advanced number inputs ([9452ecd](https://github.com/djsaikrishna/XRDB/commit/9452ecdc18004679bfa652ddb79af163514739d0))
* **web:** confirm live runtime-config changes and guard low memory limits ([df068d9](https://github.com/djsaikrishna/XRDB/commit/df068d93c2583306a67c2be0ff1651d096e49668))
* **web:** confirm the share copy on the button, and retry a refused clipboard ([0695870](https://github.com/djsaikrishna/XRDB/commit/0695870b7ebb1c3fac85018ffe6a2983583165cb))
* **web:** disable admin Refresh where it no-ops and scroll wide tables ([a54c479](https://github.com/djsaikrishna/XRDB/commit/a54c479c0df4f213252b490566b6c57d7c6a3d2d))
* **web:** don't assert integration status when it couldn't be verified ([718b931](https://github.com/djsaikrishna/XRDB/commit/718b9314a58d716ff118ebf72c5b48f12936e605))
* **web:** fold badge token aliases when loading a config ([820d83e](https://github.com/djsaikrishna/XRDB/commit/820d83e74599b606d17acc8b80fa39e523eaf5ab))
* **web:** keep the nav bar inside narrow viewports ([b17a22d](https://github.com/djsaikrishna/XRDB/commit/b17a22d434333f13ebd062028e8fade1cad4da77))
* **web:** make Copy work on http origins and surface failures ([fbf4696](https://github.com/djsaikrishna/XRDB/commit/fbf4696c60eeb3ae3d2302accb951a3dffcd8e32))
* **web:** make every tab reachable on a phone ([2e826fc](https://github.com/djsaikrishna/XRDB/commit/2e826fc71fc37a692f99ea775ff7224ce7bd4fdf))
* **web:** make media-search results a keyboard-operable combobox ([58b34c6](https://github.com/djsaikrishna/XRDB/commit/58b34c6bc325c7593289e0a35181a0628e74fff9))
* **web:** make profile export reliable and add file import ([38c8914](https://github.com/djsaikrishna/XRDB/commit/38c8914e15b3f0a64d6ca4809ac92a6d9ec88130))
* **web:** make Share this look copy on plain-http origins ([6169ee6](https://github.com/djsaikrishna/XRDB/commit/6169ee6b2a59f272d7fc2d6e82ddb1f840fe0345))
* **web:** make the SIMKL source logo visible on the dark panel ([4608369](https://github.com/djsaikrishna/XRDB/commit/4608369d852d5a317162d585b1cdc980731ee610))
* **web:** mark quality badges a higher format already covers ([be96161](https://github.com/djsaikrishna/XRDB/commit/be9616121d0465b382b992e9975cecea33414431))
* **web:** mask the render key in the install URL patterns ([9c6480c](https://github.com/djsaikrishna/XRDB/commit/9c6480cf5b285db432734471835d82d39e1dc8fb))
* **web:** name the configured quality-badge position in the hint ([612a399](https://github.com/djsaikrishna/XRDB/commit/612a399415b9d25fdb23cfbe1d6276065677f87b))
* **web:** name the right surfaces in the scope notice ([92764fe](https://github.com/djsaikrishna/XRDB/commit/92764fe26637ac1dce458cf78c3961e39a1c96b7))
* **web:** offer every quality badge the renderer draws ([0bcad4f](https://github.com/djsaikrishna/XRDB/commit/0bcad4f5aed2475abda046fef7bb6664145cfbc1))
* **web:** point non-admins at their own profile API keys ([e01fd82](https://github.com/djsaikrishna/XRDB/commit/e01fd822ab11485f87663ea009b693b02c9264a5))
* **web:** preview thumbnails as an episode ([58d3817](https://github.com/djsaikrishna/XRDB/commit/58d38176fa2184e5718a5c60120efe4f6f565b4f)), closes [#65](https://github.com/djsaikrishna/XRDB/issues/65)
* **web:** raise subtle-text contrast and touch targets to WCAG AA ([d1832cc](https://github.com/djsaikrishna/XRDB/commit/d1832cc53cab60531af291ee294f9e0ec9f3f721))
* **web:** remove collapsed accordion tab stops and add radiogroup keyboard nav ([bd32bb0](https://github.com/djsaikrishna/XRDB/commit/bd32bb0e1368a724f504ca09db716e4e9ca366f7))
* **web:** restore persisted state after mount to avoid hydration mismatch ([d062632](https://github.com/djsaikrishna/XRDB/commit/d0626320c1934053825549db28c2071b3018a477))
* **web:** stabilize integrations onboarding effect and restore green web ci ([c015822](https://github.com/djsaikrishna/XRDB/commit/c015822eab0b9dd999c2d786387de18a50558d77))
* **web:** thread the instance API key through the configurator ([72c8a7f](https://github.com/djsaikrishna/XRDB/commit/72c8a7ffaacc9d5c130e3d9763ab91d048fb8040))
* **web:** thumb-sized secondary links and an even preview action row ([408e09d](https://github.com/djsaikrishna/XRDB/commit/408e09dff996952f245629f74b3cdf37395cae0d))
* **workspace:** all 5 subtabs now fit on one row ([0a1c166](https://github.com/djsaikrishna/XRDB/commit/0a1c1663257a57b0a8da0dce213efaad348ea33f))
* **workspace:** anchor mobile preview action and remove floating overlap ([6f1889f](https://github.com/djsaikrishna/XRDB/commit/6f1889fc539e8544d4f15b51326f7a7881046959))
* **workspace:** BUG-150 and BUG-154 finalize pin layout readability and not-found log visibility ([efba4b0](https://github.com/djsaikrishna/XRDB/commit/efba4b0ab593b3180b97077583c960dc51a5112b))
* **workspace:** improve tab guidance and remove overlap controls ([66e32c2](https://github.com/djsaikrishna/XRDB/commit/66e32c29225e9e9511ef41284b1e5a90a3b0876b))
* **workspace:** move Inspect action to bottom nav on mobile ([87c1ec6](https://github.com/djsaikrishna/XRDB/commit/87c1ec601b139b2c4c5f816d98e94a7684fc5639))


### Performance

* **compose:** cache each source's ratings per title ([01d1195](https://github.com/djsaikrishna/XRDB/commit/01d11952ec32f44b5a2d34b151a55b4d48c56d9a))
* **compose:** only fetch the rating sources a render asked for ([425fcd3](https://github.com/djsaikrishna/XRDB/commit/425fcd3c0e59473143e91453fe37ccc1f1186f42))
* **provider:** stop a rate-limited source from holding up a render ([2520073](https://github.com/djsaikrishna/XRDB/commit/25200736e5dae02ee8c22efbc9568326f2039976))
* **provider:** stop retrying a source that has spent its quota ([c854bc2](https://github.com/djsaikrishna/XRDB/commit/c854bc2c38b3c849cc684ac5c176f5a9d9284ddb))
* **quality:** ask the stream addon alongside the artwork fetch ([c38113b](https://github.com/djsaikrishna/XRDB/commit/c38113b0c2938d7a30e256f01cae481d33033978))
* **simkl:** resolve a title's SIMKL id once ([b8504f5](https://github.com/djsaikrishna/XRDB/commit/b8504f5749dd7632187d2cd3867c0e67067d55b7))
* **web:** give logo images intrinsic dimensions to prevent layout shift ([70e9122](https://github.com/djsaikrishna/XRDB/commit/70e9122db975ab34c454b1c574b91b00f8e8ce71))


### Changed

* **web:** extract shared .color-swatch class for colour inputs ([6bb7605](https://github.com/djsaikrishna/XRDB/commit/6bb7605fe1b5c50e13346ac455ed8edfb2ce4657))
* **web:** keep undo/redo snapshots out of the setState updater ([85dbd0a](https://github.com/djsaikrishna/XRDB/commit/85dbd0ac21665e953547154f9bcc955765a8364b))
* **web:** move each badge's fine controls next to the badge ([926ec64](https://github.com/djsaikrishna/XRDB/commit/926ec64b9bad4b9794e253792af6fa16c25d1526))
* **web:** split the configurator tabs into surface and config groups ([36c58db](https://github.com/djsaikrishna/XRDB/commit/36c58db33d554efb38ef55c8d98d273463f8862a))


### Documentation

* add a setup guide per media client ([c15f63f](https://github.com/djsaikrishna/XRDB/commit/c15f63fed93bc3d5ad697afdd415f79dba37d379))
* add issue templates, contributing guide and README screenshots ([0925381](https://github.com/djsaikrishna/XRDB/commit/092538132eb70a135887e2d2e8d53a46bbc1dc86))
* clarify cache TTL ranges and MDBList tuning guidance ([19897a0](https://github.com/djsaikrishna/XRDB/commit/19897a0fee246c699bf620a2a8477fb175009f98))
* **configurator:** say quality badges are not detected from the title ([008d09c](https://github.com/djsaikrishna/XRDB/commit/008d09c27516c0f51c51671bd6cec4521375ea5c))
* describe the automated release flow ([5dd39c0](https://github.com/djsaikrishna/XRDB/commit/5dd39c0afaa5a673bc66e44089511c98c23b7f84))
* document the proxy-trust, top-rated and folder-writer variables ([4a18324](https://github.com/djsaikrishna/XRDB/commit/4a18324723e019c526b2ada4b38f02f3653331f4))
* environment reference, v2 to v3 migration guide, refreshed README ([84f8ecb](https://github.com/djsaikrishna/XRDB/commit/84f8ecb66c7a3d7d43421a245bce4de6ab05d778))
* point v3 pull instructions at the :dev tag ([4b733fc](https://github.com/djsaikrishna/XRDB/commit/4b733fcd7061deb5f2e971ec43e86ea4fae2f984))
* prepare the v3.0.0 changelog and quick start ([f8cbcf5](https://github.com/djsaikrishna/XRDB/commit/f8cbcf5e6d679e8fa86d22952dd600ffa201907f))
* **readme:** align canonical thumbnail integration guidance ([0f41fff](https://github.com/djsaikrishna/XRDB/commit/0f41fffe14239e087d01f91f1e7c9b12e606cac0))
* **readme:** correct genre badge border width and outline width ranges ([60db768](https://github.com/djsaikrishna/XRDB/commit/60db76802f86e3fd31c3be50648ec159d2a34c84))
* **reference:** align docs ([59655b8](https://github.com/djsaikrishna/XRDB/commit/59655b8070f075332a5e68bd40109e0a0d1f5ce8))
* refresh static doc assets ([f862c98](https://github.com/djsaikrishna/XRDB/commit/f862c980605b0cf75d38535f1908765c482601e2))
* refresh static doc assets ([0df7b6e](https://github.com/djsaikrishna/XRDB/commit/0df7b6e70dcf7eb67af405723c1daddf119c700d))
* refresh static doc assets ([c11ddb3](https://github.com/djsaikrishna/XRDB/commit/c11ddb3fc5a86c81a4a634e0d514255fc1f28ec0))
* refresh static doc assets ([ea13f4d](https://github.com/djsaikrishna/XRDB/commit/ea13f4d05e45e9f5dac9540b52cd87861e6fe7f8))
* refresh static doc assets ([3333a20](https://github.com/djsaikrishna/XRDB/commit/3333a2087867bd53cdb6d5b61c6e1480d8efef7f))
* refresh static doc assets ([d2e84e5](https://github.com/djsaikrishna/XRDB/commit/d2e84e535e1e6e7af6666d626a0c69450eb3b028))
* refresh static doc assets ([776f6e5](https://github.com/djsaikrishna/XRDB/commit/776f6e59f288a7ea994d2e5d5a0c5ff2af0f689c))
* refresh static doc assets ([3f00729](https://github.com/djsaikrishna/XRDB/commit/3f00729dbba1cb3674eeeb0f98fbec5e0efcca2a))
* refresh static doc assets ([782613e](https://github.com/djsaikrishna/XRDB/commit/782613ed7dc47156a0aee2b2c7ecdb3f95e6d213))
* refresh static doc assets ([7a5d379](https://github.com/djsaikrishna/XRDB/commit/7a5d37977af40638ccd8cc89be7b7f2433fff586))
* refresh static doc assets ([ffa6145](https://github.com/djsaikrishna/XRDB/commit/ffa61459da5ab255b1322df98ebaf69299383d61))
* refresh static doc assets ([a74f10e](https://github.com/djsaikrishna/XRDB/commit/a74f10ed2c2b47897a4e24b14383add61ef1a17c))
* refresh static doc assets ([03cf15d](https://github.com/djsaikrishna/XRDB/commit/03cf15d07d4a1551b4cf7ca17267224b99b80884))
* refresh static doc assets ([d4be3d5](https://github.com/djsaikrishna/XRDB/commit/d4be3d554631f85fc7113a0760ca51361ace2368))
* refresh static doc assets ([3e038ab](https://github.com/djsaikrishna/XRDB/commit/3e038ab0a3d8d59007687339a8581352c33ce763))
* refresh static doc assets ([07066e3](https://github.com/djsaikrishna/XRDB/commit/07066e3a1311030ef193a554e0dd187233ee51f4))
* refresh static doc assets ([19f5f44](https://github.com/djsaikrishna/XRDB/commit/19f5f44556556ccf7008f0b93fc1693774f8aa2f))
* refresh static doc assets ([91a7bdc](https://github.com/djsaikrishna/XRDB/commit/91a7bdcedd3ee65048d3e246c8554f1f7119c8ce))
* refresh static doc assets ([2fa577a](https://github.com/djsaikrishna/XRDB/commit/2fa577a48e9497fd7bc14666b5659a58c38c5a41))
* stripped documentation for ease of use and literacy. ([734aaa6](https://github.com/djsaikrishna/XRDB/commit/734aaa69a05f693877770f2e55c60a859d96cc58))
* updated README.md to remove redundant note. ([fb2c2c2](https://github.com/djsaikrishna/XRDB/commit/fb2c2c24a7b9538c36a409e2591301a96381206d))

## [3.13.0](https://github.com/IbbyLabs/XRDB/compare/v3.12.0...v3.13.0) (2026-07-28)


### Added

* **quality:** always check a quality badge against what the title has ([876dd27](https://github.com/IbbyLabs/XRDB/commit/876dd27aab0d14d7f4488bd3bb92bd6b188f8039))

## [3.12.0](https://github.com/IbbyLabs/XRDB/compare/v3.11.0...v3.12.0) (2026-07-28)


### Added

* **context:** publish a product summary the community bot reads ([ebe0971](https://github.com/IbbyLabs/XRDB/commit/ebe0971f11bbffee13eab536a73d362f883d70d8))


### Fixed

* **context:** stamp a release tag and stop rewriting the timestamp ([a1d7eea](https://github.com/IbbyLabs/XRDB/commit/a1d7eeaf9aa572b7dc98152e0a6157a65c13ddc3))


### Performance

* **quality:** ask the stream addon alongside the artwork fetch ([c38113b](https://github.com/IbbyLabs/XRDB/commit/c38113b0c2938d7a30e256f01cae481d33033978))

## [3.11.0](https://github.com/IbbyLabs/XRDB/compare/v3.10.1...v3.11.0) (2026-07-28)


### Added

* **quality:** draw quality badges only for releases that exist ([0138b68](https://github.com/IbbyLabs/XRDB/commit/0138b68290ccaaef9643781fe5b4c0144bc55fc0))


### Fixed

* **migrate:** v2 streamBadges is the quality check, not streaming chips ([175e6ea](https://github.com/IbbyLabs/XRDB/commit/175e6ead6417abb80a9ac042ac0eb92ea059b9f5))
* **quality:** read the stream description when detecting qualities ([5df51e9](https://github.com/IbbyLabs/XRDB/commit/5df51e954f3e78bf6d1df47c74f63f3ef7c1cf5b))


### Documentation

* **configurator:** say quality badges are not detected from the title ([008d09c](https://github.com/IbbyLabs/XRDB/commit/008d09c27516c0f51c51671bd6cec4521375ea5c))

## [3.10.1](https://github.com/IbbyLabs/XRDB/compare/v3.10.0...v3.10.1) (2026-07-27)


### Fixed

* **tmdb:** resolve a duplicate IMDb id to the right record ([5d4f392](https://github.com/IbbyLabs/XRDB/commit/5d4f392f9c86ac4c0a355c3c2233d2db24709102))

## [3.10.0](https://github.com/IbbyLabs/XRDB/compare/v3.9.1...v3.10.0) (2026-07-27)


### Added

* **artwork:** add an original-language option and missing codes ([9632b2a](https://github.com/IbbyLabs/XRDB/commit/9632b2a98590e23cf8cac267589b3bb58dd6f8b2))


### Fixed

* **cache:** cap the TTL of a render missing a rating badge ([7e7d7ae](https://github.com/IbbyLabs/XRDB/commit/7e7d7ae2c54e14873cc403a49fb9dbce8763ec54))
* **cache:** only a throttled source shortens a render's TTL ([a861ed0](https://github.com/IbbyLabs/XRDB/commit/a861ed0967b369c8498a825ae00bd8c5910c9444))

## [3.9.1](https://github.com/IbbyLabs/XRDB/compare/v3.9.0...v3.9.1) (2026-07-27)


### Fixed

* **provider:** stop Fanart serving a movie record for a series (BUG-168) ([17e9e6b](https://github.com/IbbyLabs/XRDB/commit/17e9e6b233aec2331fff0b939f094edade3fef24))
* **provider:** verify Fanart records by TMDB id, not title (BUG-168) ([773cf2b](https://github.com/IbbyLabs/XRDB/commit/773cf2bfe0cab6060529645dca1b3363bb1b88db))

## [3.9.0](https://github.com/IbbyLabs/XRDB/compare/v3.8.3...v3.9.0) (2026-07-27)


### Added

* **compose:** draw the genre badge the way v2 did ([be7f3c2](https://github.com/IbbyLabs/XRDB/commit/be7f3c242f1e2e7e486d325cd45bd9b85b0b092c))

## [3.8.3](https://github.com/IbbyLabs/XRDB/compare/v3.8.2...v3.8.3) (2026-07-27)


### Performance

* **compose:** cache each source's ratings per title ([01d1195](https://github.com/IbbyLabs/XRDB/commit/01d11952ec32f44b5a2d34b151a55b4d48c56d9a))
* **provider:** stop retrying a source that has spent its quota ([c854bc2](https://github.com/IbbyLabs/XRDB/commit/c854bc2c38b3c849cc684ac5c176f5a9d9284ddb))
* **simkl:** resolve a title's SIMKL id once ([b8504f5](https://github.com/IbbyLabs/XRDB/commit/b8504f5749dd7632187d2cd3867c0e67067d55b7))

## [3.8.2](https://github.com/IbbyLabs/XRDB/compare/v3.8.1...v3.8.2) (2026-07-27)


### Performance

* **provider:** stop a rate-limited source from holding up a render ([2520073](https://github.com/IbbyLabs/XRDB/commit/25200736e5dae02ee8c22efbc9568326f2039976))

## [3.8.1](https://github.com/IbbyLabs/XRDB/compare/v3.8.0...v3.8.1) (2026-07-26)


### Fixed

* **provider:** keep credentials out of transport error logs ([5e43f0d](https://github.com/IbbyLabs/XRDB/commit/5e43f0d4446971a759dc8cc8ffc556ff1ffef3f3))


### Performance

* **compose:** only fetch the rating sources a render asked for ([425fcd3](https://github.com/IbbyLabs/XRDB/commit/425fcd3c0e59473143e91453fe37ccc1f1186f42))

## [3.8.0](https://github.com/IbbyLabs/XRDB/compare/v3.7.4...v3.8.0) (2026-07-26)


### Added

* **compose:** add a switch to hide every quality badge ([6a15b4f](https://github.com/IbbyLabs/XRDB/commit/6a15b4fbcc926f8c224c192ac71d1eb301241b39))

## [3.7.4](https://github.com/IbbyLabs/XRDB/compare/v3.7.3...v3.7.4) (2026-07-26)


### Fixed

* **web:** fold badge token aliases when loading a config ([820d83e](https://github.com/IbbyLabs/XRDB/commit/820d83e74599b606d17acc8b80fa39e523eaf5ab))
* **web:** mask the render key in the install URL patterns ([9c6480c](https://github.com/IbbyLabs/XRDB/commit/9c6480cf5b285db432734471835d82d39e1dc8fb))

## [3.7.3](https://github.com/IbbyLabs/XRDB/compare/v3.7.2...v3.7.3) (2026-07-26)


### Fixed

* **web:** build install URLs from the item id, not the IMDb id ([7642298](https://github.com/IbbyLabs/XRDB/commit/76422988aa552b3df5cd6813868619b373845974))

## [3.7.2](https://github.com/IbbyLabs/XRDB/compare/v3.7.1...v3.7.2) (2026-07-26)


### Fixed

* **config:** treat a zero badge cap as no cap ([4af534f](https://github.com/IbbyLabs/XRDB/commit/4af534f986fa8da62780ef7e1f094e06ec33f187))

## [3.7.1](https://github.com/IbbyLabs/XRDB/compare/v3.7.0...v3.7.1) (2026-07-26)


### Fixed

* **compose:** draw a plate behind shaped rating icons ([b34a70a](https://github.com/IbbyLabs/XRDB/commit/b34a70a42522ec909f078f0506b8a8a453c97756))
* **web:** offer every quality badge the renderer draws ([0bcad4f](https://github.com/IbbyLabs/XRDB/commit/0bcad4f5aed2475abda046fef7bb6664145cfbc1))

## [3.7.0](https://github.com/IbbyLabs/XRDB/compare/v3.6.0...v3.7.0) (2026-07-26)


### Added

* **compose:** accept MAL, AniList and Kitsu ids ([855cde2](https://github.com/IbbyLabs/XRDB/commit/855cde2c0ed47f1a2c19a22b0c2f4fb074d73be1))

## [3.6.0](https://github.com/IbbyLabs/XRDB/compare/v3.5.4...v3.6.0) (2026-07-26)


### Added

* **compose:** colour the aggregate rating pill by its score ([d5b8b25](https://github.com/IbbyLabs/XRDB/commit/d5b8b255375194b1b3dd76d34d7b09a74e962b3d))


### Fixed

* **compose:** give the square and clean genre styles their own look ([2eba985](https://github.com/IbbyLabs/XRDB/commit/2eba9852c9853d37517332e61cb9c5c609bf52ee))
* **config:** fall back to the poster surface, not stock defaults ([1bed50c](https://github.com/IbbyLabs/XRDB/commit/1bed50c0f0c340b6d2398883d4cba526ea67ccb1))
* **migrate:** map v2's glass rating style onto pill ([1494b73](https://github.com/IbbyLabs/XRDB/commit/1494b73920d759d0305b7e9e8464bf8a3162cb9c))
* **web:** name the right surfaces in the scope notice ([92764fe](https://github.com/IbbyLabs/XRDB/commit/92764fe26637ac1dce458cf78c3961e39a1c96b7))
* **web:** preview thumbnails as an episode ([58d3817](https://github.com/IbbyLabs/XRDB/commit/58d38176fa2184e5718a5c60120efe4f6f565b4f)), closes [#65](https://github.com/IbbyLabs/XRDB/issues/65)

## [3.5.4](https://github.com/IbbyLabs/XRDB/compare/v3.5.3...v3.5.4) (2026-07-26)


### Fixed

* **compose:** draw the trending badge only for trending titles ([7f2ae1a](https://github.com/IbbyLabs/XRDB/commit/7f2ae1a28802490f66f58a7d421951223cc02fbb))

## [3.5.3](https://github.com/IbbyLabs/XRDB/compare/v3.5.2...v3.5.3) (2026-07-26)


### Fixed

* **config:** read the v2 credential names as a fallback ([f97cdf7](https://github.com/IbbyLabs/XRDB/commit/f97cdf7d5d58c00a445e3ec3d095e545273688a9))

## [3.5.2](https://github.com/IbbyLabs/XRDB/compare/v3.5.1...v3.5.2) (2026-07-25)


### Fixed

* **compose:** resolve non-IMDb ids before asking rating sources ([22f548c](https://github.com/IbbyLabs/XRDB/commit/22f548ca496b76ae48601ce71246f8895bc805ba))
* **server:** surface AIOMetadata credential errors ([c37e755](https://github.com/IbbyLabs/XRDB/commit/c37e7554d5af25b36d69efceb4f8a5ec8e2db4fb))

## [3.5.1](https://github.com/IbbyLabs/XRDB/compare/v3.5.0...v3.5.1) (2026-07-25)


### Fixed

* **compose:** size corner overlays to the canvas ([7d3432e](https://github.com/IbbyLabs/XRDB/commit/7d3432ed3ee3dd9a5177598d4627a3357f63d0c3))
* **web:** make the SIMKL source logo visible on the dark panel ([4608369](https://github.com/IbbyLabs/XRDB/commit/4608369d852d5a317162d585b1cdc980731ee610))

## [3.5.0](https://github.com/IbbyLabs/XRDB/compare/v3.4.0...v3.5.0) (2026-07-25)


### Added

* **compose:** order ratings and size badges to the canvas ([6a0928b](https://github.com/IbbyLabs/XRDB/commit/6a0928b60b8489e324714aee170ff1623b9eeb31))


### Fixed

* **build:** restore the internal/ui/dist placeholder ([5642e76](https://github.com/IbbyLabs/XRDB/commit/5642e76882473ae9de9b296ab0f8163aaf825e45))
* **web:** name the configured quality-badge position in the hint ([612a399](https://github.com/IbbyLabs/XRDB/commit/612a399415b9d25fdb23cfbe1d6276065677f87b))

## [3.4.0](https://github.com/IbbyLabs/XRDB/compare/v3.3.1...v3.4.0) (2026-07-25)


### Added

* **render:** raise the badge scale ceiling and add two stacked toggles ([dce16e1](https://github.com/IbbyLabs/XRDB/commit/dce16e1defcffd2b4a7100b3103482a68c1d01ca)), closes [#8](https://github.com/IbbyLabs/XRDB/issues/8)
* **web:** make the keys page per-user and move server keys into admin ([84cfc48](https://github.com/IbbyLabs/XRDB/commit/84cfc48377eb9b77093695714d713aed0bd39565))


### Fixed

* **web:** point non-admins at their own profile API keys ([e01fd82](https://github.com/IbbyLabs/XRDB/commit/e01fd822ab11485f87663ea009b693b02c9264a5))

## [3.3.1](https://github.com/IbbyLabs/XRDB/compare/v3.3.0...v3.3.1) (2026-07-25)


### Fixed

* **config:** read a v2 badge list as tiles plus its features ([da77888](https://github.com/IbbyLabs/XRDB/commit/da778886262c9a6f78dc3dbe09c70255358e8e00))

## [3.3.0](https://github.com/IbbyLabs/XRDB/compare/v3.2.0...v3.3.0) (2026-07-25)


### Added

* **profile:** encrypt provider keys at rest and check them on save ([e9194a0](https://github.com/IbbyLabs/XRDB/commit/e9194a0e685735baa10cb6f4cd4f1700f4c9f808))
* **profile:** let an owner supply their own provider API keys ([128d8df](https://github.com/IbbyLabs/XRDB/commit/128d8df47ebf476e712b6161d89f055ca64d2e0e))
* **render:** add the no-background and tile rating badge styles ([082c017](https://github.com/IbbyLabs/XRDB/commit/082c0179694af8bab04e4c04a1af3de10050478b))
* **render:** add the stacked rating badge style ([b5afd47](https://github.com/IbbyLabs/XRDB/commit/b5afd47e748f66eda188d4971b08d36b0b28ce15))
* **render:** draw the left, right and top-bottom rating layouts ([92630d4](https://github.com/IbbyLabs/XRDB/commit/92630d45fe8c3f0e9c94559d773b2878feb1c71d))


### Fixed

* **config:** accept the badge placement spellings a v2 config uses ([236de0e](https://github.com/IbbyLabs/XRDB/commit/236de0e2fb2c992a991aae7d2c55db3aaa070f47))
* **config:** honour more v2 rating and badge settings ([2097c86](https://github.com/IbbyLabs/XRDB/commit/2097c8660ff4deac952b8e5223245fa3cd968e06))
* **config:** let an empty rating selection mean no rating badges ([d3764e1](https://github.com/IbbyLabs/XRDB/commit/d3764e199ef4f2dcf78603c1bb3ed1029feee863))
* **config:** map the remaining v2 enum spellings ([9d0d883](https://github.com/IbbyLabs/XRDB/commit/9d0d883540f6f06fcf08958cb1a778e0ffe08a99))
* **migrate:** carry an empty v2 list as an empty selection ([caf0fab](https://github.com/IbbyLabs/XRDB/commit/caf0fabf47d50d05de19ad6398f3bae9952f9291))
* **server:** accept v2-shaped artwork ids ([26efe14](https://github.com/IbbyLabs/XRDB/commit/26efe144b444dd83c705a9b567280a6e0211cc94))
* **server:** capitalize a refused-save message for display ([3dd7f80](https://github.com/IbbyLabs/XRDB/commit/3dd7f807fc7461f6f24ff429cc121a4784b20a87))
* **web:** mark quality badges a higher format already covers ([be96161](https://github.com/IbbyLabs/XRDB/commit/be9616121d0465b382b992e9975cecea33414431))

## [3.2.0](https://github.com/IbbyLabs/XRDB/compare/v3.1.0...v3.2.0) (2026-07-25)


### Added

* **web,server:** convert a v2 config from the configurator ([5624b2d](https://github.com/IbbyLabs/XRDB/commit/5624b2dd216e128e1a60c17097ae3789c951e205))


### Fixed

* **ci:** tag :latest during the release build ([3ba8948](https://github.com/IbbyLabs/XRDB/commit/3ba89484541d7530f5995c8382f2bf00d053dbb3))
* **migrate:** read v2 values that were stored as strings ([878f297](https://github.com/IbbyLabs/XRDB/commit/878f297c931a8cffe62dc0a224c80b42f4833485))

## [3.1.0](https://github.com/IbbyLabs/XRDB/compare/v3.0.0...v3.1.0) (2026-07-25)


### Changed

* Releases are now cut automatically from conventional commits, so the version
  and this changelog no longer need writing by hand ([5dd39c0](https://github.com/IbbyLabs/XRDB/commit/5dd39c0afaa5a673bc66e44089511c98c23b7f84))

## [Unreleased]

<a id="v3-0-0"></a>

## [v3.0.0] - 2026-07-25

v3 is a ground-up rewrite. It is a single Go binary with the configurator
embedded, replacing the v2 stack, and it listens on port **8787** rather than
3000. Profiles do not carry over automatically — see the
[migration guide](docs/migrating-to-v3.md).

### Breaking

- Artwork is served as **JPEG** by default instead of PNG, at a smaller default
  size. A poster is roughly 38 KB rather than 2 MB, which brings it inside
  Stremio's 100 KB limit and under its 50 KB recommendation. Logos stay PNG so
  transparency is preserved. The previous dimensions remain available as the
  `normal`, `large` and `4k` size tiers.
- The container listens on `8787` and stores data under `/data`.
- Forwarded headers (`X-Forwarded-*`, `CF-Connecting-IP`) are now only believed
  from a trusted proxy. The default covers loopback and the private ranges, so
  an ordinary reverse-proxy setup is unaffected; see `XRDB_TRUSTED_PROXIES`.


### Added

- Official rating-provider logos on badges, with pill/square/glass styles and dark/light badge themes
- Six switchable UI themes (Midnight, Violet, Emerald, Ember, Crimson, Slate)
- Title search, trending shuffle, and pinned preview items in the configurator
- Profile aliases (memorable lowercase handles), server-generated IDs, and password-protected editing
- One-click AIOMetadata install plus manual URL patterns (Install tab)
- Cinemeta artwork provider (no key required) and WebP source decoding
- Artwork language / text-preference selection (TMDB + Fanart) and large/4K output sizes
- Per-output-size badge scaling and multi-row badge wrapping
- Admin key gate for the Admin and Integrations pages
- Title search/trending/lookup and AIOMetadata install API endpoints; permissive CORS
- `make dev` one-command local stack; environment reference (`variables.md`), `env.template`, and v2→v3 migration guide
- Stremio addon that can be installed against a saved profile
  (`/stremio/c/{profile}/manifest.json`), with the install URL shown in the
  configurator
- RPDB-compatible artwork URLs, so moving from RPDB is a hostname swap
- Folder-writer mode: writes `poster.jpg`, `fanart.jpg` and `clearlogo.png` next
  to your media for Plex, Jellyfin, Emby and Kodi. Off by default, with a dry
  run and an optional schedule
- Jellyfin image-provider plugin, offering artwork by URL with nothing written
  into the library
- Top-rated film ranking badge, computed locally from the IMDb dataset (opt-in)
- Vote counts alongside rating badges, where the source reports them
- Per-source health at `GET /api/admin/sources`, showing when a rating source is
  degraded and being served from cache
- Cache invalidation: `DELETE /api/admin/cache`, all entries or one
- `Cache-Control` and `ETag` on renders, with `If-None-Match` answered as 304
- A profile version token in artwork URLs, so editing a profile refreshes art in
  clients that cache images regardless of TTL
- Per-client setup guides, a contributing guide, and issue templates

### Fixed

- Anime ratings (MyAnimeList, AniList, Kitsu) never rendered: the pipeline
  passed IMDb/TMDB IDs straight to the anime providers, which only accept
  their own ID space. A new anime ID mapper translates IDs via a disk-cached
  [Fribb/anime-lists](https://github.com/Fribb/anime-lists) dataset with a
  live API fallback — replacing the v2 approach that depended on a single
  third-party mapping host (now offline with a DNS failure)
- Fanart.tv rejected IMDb tt-IDs (every configurator render) and misrouted movie backdrops
- Thumbnails now prefer backdrop artwork over center-cropped posters
- Overlay metadata (age/genre/providers) backfills from TMDB when the artwork source lacks it
- Hydration mismatch from storage reads during first render (React #418)
- Dev-mode builds no longer break on the Go-embed `distDir`
- Rate-limited rating sources are retried with backoff and paced per source,
  instead of silently disappearing from the badge row
- A rating source that breaks or returns nothing now falls back to its last
  known good result rather than dropping its badge

<a id="v3-0-0-beta"></a>

## [v3.0.0-beta] - 2026-06-09

### Added

- Pure-Go image render pipeline (poster, backdrop, thumbnail, logo families)
- SQLite-backed profile store with full CRUD, export, and import
- Two-tier render cache (hot + disk, 72h TTL) with admin visibility
- TMDB provider with mutex-safe concurrency
- Migration tool for importing profiles from previous XRDB installations
- REST API: render, profile management, admin metrics, cache stats
- Next.js 15 configurator with live preview, display config, and profile management
- Admin panel with request metrics, latency percentiles, and cache diagnostics
- Dark OKLCH design system, WCAG AA accessible throughout
- Docker Compose deployment with named volume for data persistence
- Multi-platform Docker images (amd64/arm64) published to GHCR
