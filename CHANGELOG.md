# Changelog

## 1.0.0 (2025-07-18)

Full Changelog: [v0.2.13...v1.0.0](https://github.com/slekkala1/llama-stack-client-python/compare/v0.2.13...v1.0.0)

### Features

* `llama-stack-client providers inspect PROVIDER_ID` ([#181](https://github.com/slekkala1/llama-stack-client-python/issues/181)) ([6d18aae](https://github.com/slekkala1/llama-stack-client-python/commit/6d18aae31ce739b1a37a72b880aa8a60f890df72))
* add client-side utility for getting OAuth tokens simply ([#230](https://github.com/slekkala1/llama-stack-client-python/issues/230)) ([91156dc](https://github.com/slekkala1/llama-stack-client-python/commit/91156dca28567352c5f6be75d55327ef2b49ff19))
* add client.chat.completions.create() and client.completions.create() ([#226](https://github.com/slekkala1/llama-stack-client-python/issues/226)) ([ee0e65e](https://github.com/slekkala1/llama-stack-client-python/commit/ee0e65e89dba13431cc3b9abdbebaa9525a5fbfb))
* Add llama-stack-client datasets unregister command ([#222](https://github.com/slekkala1/llama-stack-client-python/issues/222)) ([38cd91c](https://github.com/slekkala1/llama-stack-client-python/commit/38cd91c9e396f2be0bec1ee96a19771582ba6f17))
* add support for chat sessions ([#167](https://github.com/slekkala1/llama-stack-client-python/issues/167)) ([ce3b30f](https://github.com/slekkala1/llama-stack-client-python/commit/ce3b30f83eb122cc200c441ddad5e173e02e5adb))
* add type hints to event logger util ([#140](https://github.com/slekkala1/llama-stack-client-python/issues/140)) ([26f3c33](https://github.com/slekkala1/llama-stack-client-python/commit/26f3c33cd0f81b809afa514b9a8ca63fa64643ca))
* add updated batch inference types ([#220](https://github.com/slekkala1/llama-stack-client-python/issues/220)) ([ddb93ca](https://github.com/slekkala1/llama-stack-client-python/commit/ddb93ca206d97c82c51a0efed5985a7396fcdf3c))
* add weighted_average aggregation function support ([#208](https://github.com/slekkala1/llama-stack-client-python/issues/208)) ([b62ac6c](https://github.com/slekkala1/llama-stack-client-python/commit/b62ac6cf2f2f20e248cbbce6684cef50f150cac0))
* **agent:** support multiple tool calls ([#192](https://github.com/slekkala1/llama-stack-client-python/issues/192)) ([43ea2f6](https://github.com/slekkala1/llama-stack-client-python/commit/43ea2f6d741b26181db1d7ba0912c17a9ed1ca74))
* **agent:** support plain function as client_tool ([#187](https://github.com/slekkala1/llama-stack-client-python/issues/187)) ([2ec8044](https://github.com/slekkala1/llama-stack-client-python/commit/2ec8044356b5d6285948ae22da007899f6148408))
* async agent wrapper ([#169](https://github.com/slekkala1/llama-stack-client-python/issues/169)) ([fc9907c](https://github.com/slekkala1/llama-stack-client-python/commit/fc9907c781dc406756c20d8a1829343eac0c31c0))
* autogen llama-stack-client CLI reference doc ([#190](https://github.com/slekkala1/llama-stack-client-python/issues/190)) ([e7b19a5](https://github.com/slekkala1/llama-stack-client-python/commit/e7b19a505cc06c28846e85bb5b8524632bdef4d6))
* client.responses.create() and client.responses.retrieve() ([#227](https://github.com/slekkala1/llama-stack-client-python/issues/227)) ([fba5102](https://github.com/slekkala1/llama-stack-client-python/commit/fba5102d03f85627025f4589216651d135841d5a))
* datasets api updates ([#203](https://github.com/slekkala1/llama-stack-client-python/issues/203)) ([b664564](https://github.com/slekkala1/llama-stack-client-python/commit/b664564fe1c4771a7872286d0c2ac96c47816939))
* enable_persist: sync updates from stainless branch: yanxi0830/dev ([#145](https://github.com/slekkala1/llama-stack-client-python/issues/145)) ([59a02f0](https://github.com/slekkala1/llama-stack-client-python/commit/59a02f071b14cb6627c929c4d396a3d996219c78))
* new Agent API ([#178](https://github.com/slekkala1/llama-stack-client-python/issues/178)) ([c2f73b1](https://github.com/slekkala1/llama-stack-client-python/commit/c2f73b11301c6c4a87e58ded9055fd49b1626b47))
* support client tool output metadata ([#180](https://github.com/slekkala1/llama-stack-client-python/issues/180)) ([8e4fd56](https://github.com/slekkala1/llama-stack-client-python/commit/8e4fd56a318a2806e81679877d703f6270fbcbfe))
* Sync updates from stainless branch: ehhuang/dev ([#149](https://github.com/slekkala1/llama-stack-client-python/issues/149)) ([367da69](https://github.com/slekkala1/llama-stack-client-python/commit/367da690dabee8a34039499f8e151cc8f97ca91b))
* unify max infer iters with server/client tools ([#173](https://github.com/slekkala1/llama-stack-client-python/issues/173)) ([548f2de](https://github.com/slekkala1/llama-stack-client-python/commit/548f2dee5019b7510d17025f11adbf61431f505e))
* update react with new agent api ([#189](https://github.com/slekkala1/llama-stack-client-python/issues/189)) ([ac9d1e2](https://github.com/slekkala1/llama-stack-client-python/commit/ac9d1e2166c88d2445fbbf08e30886fcec6048df))


### Bug Fixes

* `llama-stack-client provider inspect` should use retrieve ([#202](https://github.com/slekkala1/llama-stack-client-python/issues/202)) ([e33b5bf](https://github.com/slekkala1/llama-stack-client-python/commit/e33b5bfbc89c93031434720cf7265f9bc83f2a39))
* accept extra_headers in agent.create_turn and pass them faithfully ([#228](https://github.com/slekkala1/llama-stack-client-python/issues/228)) ([e72d9e8](https://github.com/slekkala1/llama-stack-client-python/commit/e72d9e8eb590facd693938a93a7a782e45d15b6d))
* added uv.lock ([546e0df](https://github.com/slekkala1/llama-stack-client-python/commit/546e0df348b648651da94989053c52f4cc43cdc4))
* **agent:** better error handling ([#207](https://github.com/slekkala1/llama-stack-client-python/issues/207)) ([5746f91](https://github.com/slekkala1/llama-stack-client-python/commit/5746f918351f9021700f0a90edf6b78e74d58c82))
* **agent:** initialize toolgroups/client_tools ([#186](https://github.com/slekkala1/llama-stack-client-python/issues/186)) ([458e207](https://github.com/slekkala1/llama-stack-client-python/commit/458e20702b5aa8f435ac5ce114fee9252b751d25))
* broken .retrieve call using `identifier=` ([#135](https://github.com/slekkala1/llama-stack-client-python/issues/135)) ([626805a](https://github.com/slekkala1/llama-stack-client-python/commit/626805a74a19011d742a60187b1119aead153a94))
* bump to 0.2.1 ([edb6173](https://github.com/slekkala1/llama-stack-client-python/commit/edb6173ec1f0da131e097a993d6f177a3655930d))
* bump version ([b6d45b8](https://github.com/slekkala1/llama-stack-client-python/commit/b6d45b862ca846bed635d64816dc7de9d9433e61))
* bump version in another place ([7253433](https://github.com/slekkala1/llama-stack-client-python/commit/7253433f6d7a41fe0812d26e4ce7183f922f2869))
* **cli:** align cli toolgroups register to the new arguments ([#231](https://github.com/slekkala1/llama-stack-client-python/issues/231)) ([a87b6f7](https://github.com/slekkala1/llama-stack-client-python/commit/a87b6f7b3fd07262bfbd4321652e51b901c75df5))
* correct toolgroups_id parameter name on unregister call ([#235](https://github.com/slekkala1/llama-stack-client-python/issues/235)) ([1be7904](https://github.com/slekkala1/llama-stack-client-python/commit/1be7904133630127c0a98ba4aed1241eee548c81))
* fix duplicate model get help text ([#188](https://github.com/slekkala1/llama-stack-client-python/issues/188)) ([4bab07a](https://github.com/slekkala1/llama-stack-client-python/commit/4bab07a683adee9a476ce926fe809dafe3cc27f0))
* llama-stack-client providers list ([#134](https://github.com/slekkala1/llama-stack-client-python/issues/134)) ([930138a](https://github.com/slekkala1/llama-stack-client-python/commit/930138a9013ee9157d14ee0606b24c5677bf4387))
* react agent ([#200](https://github.com/slekkala1/llama-stack-client-python/issues/200)) ([b779979](https://github.com/slekkala1/llama-stack-client-python/commit/b779979c40c638e835e5190e5877f57430c89d97))
* React Agent for non-llama models  ([#174](https://github.com/slekkala1/llama-stack-client-python/issues/174)) ([ee5dd2b](https://github.com/slekkala1/llama-stack-client-python/commit/ee5dd2b662ffdeb78b324dddd6884a4d0f1fd901))
* React agent should be able to work with provided config ([#146](https://github.com/slekkala1/llama-stack-client-python/issues/146)) ([08ab5df](https://github.com/slekkala1/llama-stack-client-python/commit/08ab5df583bb74dea9104950c190f6101eb19c95))
* react agent with custom tool parser n_iters ([#184](https://github.com/slekkala1/llama-stack-client-python/issues/184)) ([aaff961](https://github.com/slekkala1/llama-stack-client-python/commit/aaff9618601f1cded040e57e0d8067699e595208))
* remove the alpha suffix in run_benchmark.py ([#179](https://github.com/slekkala1/llama-stack-client-python/issues/179)) ([638f7f2](https://github.com/slekkala1/llama-stack-client-python/commit/638f7f29513cdb87b9bf0cf7bc269d2c576d37ba))
* update CONTRIBUTING.md to point to uv instead of rye ([3fbe0cd](https://github.com/slekkala1/llama-stack-client-python/commit/3fbe0cdd6a8e935732ddc513b0a6af01623a6999))
* update uv lock ([cc072c8](https://github.com/slekkala1/llama-stack-client-python/commit/cc072c81b59c26f21eaba6ee0a7d56fc61c0317a))
* validate endpoint url ([#196](https://github.com/slekkala1/llama-stack-client-python/issues/196)) ([6fa8095](https://github.com/slekkala1/llama-stack-client-python/commit/6fa8095428804a9cc348b403468cad64e4eeb38b))


### Chores

* api sync, deprecate allow_resume_turn + rename task_config-&gt;benchmark_config (Sync updates from stainless branch: yanxi0830/dev) ([#176](https://github.com/slekkala1/llama-stack-client-python/issues/176)) ([96749af](https://github.com/slekkala1/llama-stack-client-python/commit/96749af83891d47be1f8f46588be567db685cf12))
* AsyncAgent should use ToolResponse instead of ToolResponseMessage ([#197](https://github.com/slekkala1/llama-stack-client-python/issues/197)) ([6191aa5](https://github.com/slekkala1/llama-stack-client-python/commit/6191aa5cc38c4ef9be27452e04867b6ce8a703e2))
* deprecate eval task (Sync updates from stainless branch: main) ([#150](https://github.com/slekkala1/llama-stack-client-python/issues/150)) ([39b1248](https://github.com/slekkala1/llama-stack-client-python/commit/39b1248e3e1b0634e96db6bb4eac7d689e3a5a19))
* remove litellm type conversion ([#193](https://github.com/slekkala1/llama-stack-client-python/issues/193)) ([ab3f844](https://github.com/slekkala1/llama-stack-client-python/commit/ab3f844a8a7a8dc68723ed36120914fd01a18af2))
* sync repo ([e515481](https://github.com/slekkala1/llama-stack-client-python/commit/e515481f103480285df700fb5dcf204810e05508))
* Sync updates from stainless branch: ehhuang/dev ([#182](https://github.com/slekkala1/llama-stack-client-python/issues/182)) ([e33aa4a](https://github.com/slekkala1/llama-stack-client-python/commit/e33aa4a682fda23d708438a976dfe4dd5443a320))
* Sync updates from stainless branch: ehhuang/dev ([#199](https://github.com/slekkala1/llama-stack-client-python/issues/199)) ([fa73d7d](https://github.com/slekkala1/llama-stack-client-python/commit/fa73d7ddb72682d47464eca6b1476044e140a560))
* Sync updates from stainless branch: main ([#201](https://github.com/slekkala1/llama-stack-client-python/issues/201)) ([f063f2d](https://github.com/slekkala1/llama-stack-client-python/commit/f063f2d6126d2bd1f9a8dcf854a32ae7cd4be607))
* update SDK settings ([7878113](https://github.com/slekkala1/llama-stack-client-python/commit/7878113536606734388e035960ddda19d7904da0))
* update SDK settings ([9410d73](https://github.com/slekkala1/llama-stack-client-python/commit/9410d73217e5e6ce6d043d0c42a27cd7f740abbc))
* use rich to format logs ([#177](https://github.com/slekkala1/llama-stack-client-python/issues/177)) ([303054b](https://github.com/slekkala1/llama-stack-client-python/commit/303054b6a64e47dbdf7de93458433b71bb1ff59c))


### Refactors

* update react_agent to use tool_config ([#139](https://github.com/slekkala1/llama-stack-client-python/issues/139)) ([b5dce10](https://github.com/slekkala1/llama-stack-client-python/commit/b5dce10f0a621f8f8a0f893dba4d2acebd7e438b))


### Build System

* Bump version to 0.1.19 ([ccd52f8](https://github.com/slekkala1/llama-stack-client-python/commit/ccd52f8bb298ecfd3ec06ae2d50ccaeebbfb3973))
* Bump version to 0.1.8 ([0144e85](https://github.com/slekkala1/llama-stack-client-python/commit/0144e857c83afc807122b32f3f53775e87c027ac))
* Bump version to 0.1.9 ([7e00b78](https://github.com/slekkala1/llama-stack-client-python/commit/7e00b784ee859aa04aa11955e3888e5167331dfe))
* Bump version to 0.2.10 ([05e41a6](https://github.com/slekkala1/llama-stack-client-python/commit/05e41a6eb12053b850a3abc56bb35e3121042be2))
* Bump version to 0.2.11 ([d2e7537](https://github.com/slekkala1/llama-stack-client-python/commit/d2e753751519cb9f0e09d255e875f60449ab30aa))
* Bump version to 0.2.12 ([e3d812e](https://github.com/slekkala1/llama-stack-client-python/commit/e3d812ee3a85949e31e448e68c03534225b4ed07))
* Bump version to 0.2.13 ([b6c6c5e](https://github.com/slekkala1/llama-stack-client-python/commit/b6c6c5ed7940bb625665d50f88ff7ea9d734e100))
* Bump version to 0.2.2 ([47f8fd5](https://github.com/slekkala1/llama-stack-client-python/commit/47f8fd568634c9e2f7cd7d86f92f7c43cfc448cd))
* Bump version to 0.2.4 ([7e6f5fc](https://github.com/slekkala1/llama-stack-client-python/commit/7e6f5fce18f23b807e52ac173251687c3b58979b))
* Bump version to 0.2.5 ([62bd127](https://github.com/slekkala1/llama-stack-client-python/commit/62bd12799d8a4a0261d200d1c869e2be98c38770))
* Bump version to 0.2.6 ([3dd707f](https://github.com/slekkala1/llama-stack-client-python/commit/3dd707fb84ba2ce56151cec9fb30918c651ccdd9))
* Bump version to 0.2.7 ([e39ba88](https://github.com/slekkala1/llama-stack-client-python/commit/e39ba882f9d1f635f5e7398f623d7ceeae1b446f))
* Bump version to 0.2.8 ([645d219](https://github.com/slekkala1/llama-stack-client-python/commit/645d2195c5af1c6f903cb93c293319d8f94c36cc))
* Bump version to 0.2.9 ([d360557](https://github.com/slekkala1/llama-stack-client-python/commit/d36055741dd5c152c629dc28ec3b88b2c78f5336))
