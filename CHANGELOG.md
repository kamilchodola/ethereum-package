# Changelog

## [1.1.0](https://github.com/kurtosis-tech/ethereum-package/compare/1.0.0...1.1.0) (2023-11-30)


### Features

* Add adminer ([#295](https://github.com/kurtosis-tech/ethereum-package/issues/295)) ([99b5913](https://github.com/kurtosis-tech/ethereum-package/commit/99b5913bfbc2ea25716b593cafbaebc486bf3c88))
* Add broadcaster ([#355](https://github.com/kurtosis-tech/ethereum-package/issues/355)) ([0f9c3aa](https://github.com/kurtosis-tech/ethereum-package/commit/0f9c3aad1f1360fa896dce75cb1b2c46e9872af1))
* add custom label configuration option ([#375](https://github.com/kurtosis-tech/ethereum-package/issues/375)) ([82ec85e](https://github.com/kurtosis-tech/ethereum-package/commit/82ec85e84e8c0972217f43962674493195970866))
* add custom labels ([#340](https://github.com/kurtosis-tech/ethereum-package/issues/340)) ([789ed8e](https://github.com/kurtosis-tech/ethereum-package/commit/789ed8e7f0a1a1512132732540a713dca17bbe56))
* add dencun example, bump teku mem, update mev-relay postgres name ([#369](https://github.com/kurtosis-tech/ethereum-package/issues/369)) ([1097531](https://github.com/kurtosis-tech/ethereum-package/commit/10975312c4d5c74b9bb80b872f205374997fc33c))
* Add Ethereum Metrics Exporter Dash ([#338](https://github.com/kurtosis-tech/ethereum-package/issues/338)) ([3ce9a78](https://github.com/kurtosis-tech/ethereum-package/commit/3ce9a780f50c4909b9fe64ccd6580432135e1c37))
* Add initial support for Blobscan ([#363](https://github.com/kurtosis-tech/ethereum-package/issues/363)) ([837fb97](https://github.com/kurtosis-tech/ethereum-package/commit/837fb970bb65d12bbe31dfec011a7f323d520111))
* add prometheus custom configuration for participants ([#354](https://github.com/kurtosis-tech/ethereum-package/issues/354)) ([e9bbc7d](https://github.com/kurtosis-tech/ethereum-package/commit/e9bbc7debf9db9c7f30271084b6276fcbe167d93))
* added a gitpod badge ([#356](https://github.com/kurtosis-tech/ethereum-package/issues/356)) ([e273993](https://github.com/kurtosis-tech/ethereum-package/commit/e2739935d8ed3993d7152a8403a194ea628360a2))
* Allow verkle to be at genesis or post genesis ([60a7529](https://github.com/kurtosis-tech/ethereum-package/commit/60a752932242d795e5c087094ca5e26f6f4029c4))
* differentiate builder ec by suffixing it with '-builder' ([#347](https://github.com/kurtosis-tech/ethereum-package/issues/347)) ([c558cb2](https://github.com/kurtosis-tech/ethereum-package/commit/c558cb2eab25cc8c3718b1fda6759a0819e6f942))


### Bug Fixes

* add java opts for besu ([#346](https://github.com/kurtosis-tech/ethereum-package/issues/346)) ([8aa88e3](https://github.com/kurtosis-tech/ethereum-package/commit/8aa88e34212321b2a148fd26c0e5a0da0b1a5b3f))
* blobscan lint error ([#374](https://github.com/kurtosis-tech/ethereum-package/issues/374)) ([32f862b](https://github.com/kurtosis-tech/ethereum-package/commit/32f862be000a547fba300be4be3f954835ac707f))
* builder args incorrectly configured ([#343](https://github.com/kurtosis-tech/ethereum-package/issues/343)) ([66e73fb](https://github.com/kurtosis-tech/ethereum-package/commit/66e73fb9f20d8dcce17beb00bf25dafb1e4ada65))
* network params setting invalid value for min/max configs ([#353](https://github.com/kurtosis-tech/ethereum-package/issues/353)) ([764b7dc](https://github.com/kurtosis-tech/ethereum-package/commit/764b7dc0577a8e8da9dac3519d18db51720f2b4b))
* update validator reward address ([#350](https://github.com/kurtosis-tech/ethereum-package/issues/350)) ([57f82c0](https://github.com/kurtosis-tech/ethereum-package/commit/57f82c0432c9a77bfa12f78a14b2e0038228a99c))
* Use unused accounts for mev flood ([#359](https://github.com/kurtosis-tech/ethereum-package/issues/359)) ([286654c](https://github.com/kurtosis-tech/ethereum-package/commit/286654c769b33c1d63d20bf31c1dd3a71f7a3f0d))

## [1.0.0](https://github.com/kurtosis-tech/ethereum-package/compare/0.6.1...1.0.0) (2023-10-25)


### ⚠ BREAKING CHANGES

* merged genesis generation ([#288](https://github.com/kurtosis-tech/ethereum-package/issues/288))

### Features

* add "disable_peer_scoring" global flag ([#311](https://github.com/kurtosis-tech/ethereum-package/issues/311)) ([63f7ff3](https://github.com/kurtosis-tech/ethereum-package/commit/63f7ff3c396ab567caf3397822ea7c2d614baeb9)), closes [#304](https://github.com/kurtosis-tech/ethereum-package/issues/304)
* add mock mev ci ([#310](https://github.com/kurtosis-tech/ethereum-package/issues/310)) ([d4bec9e](https://github.com/kurtosis-tech/ethereum-package/commit/d4bec9e7a723d1cdbbd37d63684b526a4f1f325b))
* add trusted setup file to teku ([#325](https://github.com/kurtosis-tech/ethereum-package/issues/325)) ([605e155](https://github.com/kurtosis-tech/ethereum-package/commit/605e155ee5e5058cc159739ee673eff4b702bc52))
* bump json-rpc-snooper ([#329](https://github.com/kurtosis-tech/ethereum-package/issues/329)) ([242a4cd](https://github.com/kurtosis-tech/ethereum-package/commit/242a4cdeded040eb50c9e259aacf9a58eee236ec))
* json to yaml everything ([#332](https://github.com/kurtosis-tech/ethereum-package/issues/332)) ([c9669ae](https://github.com/kurtosis-tech/ethereum-package/commit/c9669ae83063a5dd9faf478f386582a2cac595ac))
* merged genesis generation ([#288](https://github.com/kurtosis-tech/ethereum-package/issues/288)) ([743ba44](https://github.com/kurtosis-tech/ethereum-package/commit/743ba44d82e9433e6781e4965ef80bc83e962e25))
* rework how keys are generated ([#301](https://github.com/kurtosis-tech/ethereum-package/issues/301)) ([59f15ca](https://github.com/kurtosis-tech/ethereum-package/commit/59f15cae142b778a676ee6a3f56d4c8e3a2ed1c0))
* **tooling:** Add Ethereum Metrics Exporter ([#331](https://github.com/kurtosis-tech/ethereum-package/issues/331)) ([de5eee8](https://github.com/kurtosis-tech/ethereum-package/commit/de5eee82a7757b218a902e0bef36dae42e966b31))
* use base image instead of pip install ([#322](https://github.com/kurtosis-tech/ethereum-package/issues/322)) ([18da90b](https://github.com/kurtosis-tech/ethereum-package/commit/18da90bd3f8b6471457e613edc1e17ff01d2ae0a))


### Bug Fixes

* add readme for mev-builder-cl-image ([#314](https://github.com/kurtosis-tech/ethereum-package/issues/314)) ([c46b6bf](https://github.com/kurtosis-tech/ethereum-package/commit/c46b6bf1e83fa567727675ef0644d7d3eefcb1f2))
* formatting - missing jwt secret ([#312](https://github.com/kurtosis-tech/ethereum-package/issues/312)) ([728964c](https://github.com/kurtosis-tech/ethereum-package/commit/728964c7034c94dff6b2c4479e7a962d69bafc62))
* genesis validators root had an extra new line ([#326](https://github.com/kurtosis-tech/ethereum-package/issues/326)) ([4fa4937](https://github.com/kurtosis-tech/ethereum-package/commit/4fa49375c0f0e96aaef011e0afd053c2975c3a69))
* geth flags for verkle genesis ([#328](https://github.com/kurtosis-tech/ethereum-package/issues/328)) ([e721373](https://github.com/kurtosis-tech/ethereum-package/commit/e721373f93e8113802c47e815f3152af5974dc41))
* path based storage - disable for older forks ([#336](https://github.com/kurtosis-tech/ethereum-package/issues/336)) ([76e3424](https://github.com/kurtosis-tech/ethereum-package/commit/76e34245dffcd6976d631d40cab813880b9a224a))
* path based storage disable for elecra ([#316](https://github.com/kurtosis-tech/ethereum-package/issues/316)) ([86fa8ef](https://github.com/kurtosis-tech/ethereum-package/commit/86fa8efccd18236d0cbbfd7565f66883cc774fcc))
* remove image name for ethereum-metrics-exporter ([#335](https://github.com/kurtosis-tech/ethereum-package/issues/335)) ([4bac042](https://github.com/kurtosis-tech/ethereum-package/commit/4bac04249f61a408f792d4eb65c6c1ea3b844f61))
* remove path based storage when builder is used ([#327](https://github.com/kurtosis-tech/ethereum-package/issues/327)) ([d3cf3f4](https://github.com/kurtosis-tech/ethereum-package/commit/d3cf3f42ebe68b02cf28ad3d7c69c77e7c934af7))
* revert the default deneb at epoch 4 ([#323](https://github.com/kurtosis-tech/ethereum-package/issues/323)) ([9342418](https://github.com/kurtosis-tech/ethereum-package/commit/9342418fc643fbf41a95db828ec5fcd3be4913cf))
* take out the genesis versions as constants ([#324](https://github.com/kurtosis-tech/ethereum-package/issues/324)) ([a8afcef](https://github.com/kurtosis-tech/ethereum-package/commit/a8afcef6a8969ad2062c78f1b2d32e275697ea60))
* wrong builder metrics flag ([#319](https://github.com/kurtosis-tech/ethereum-package/issues/319)) ([51a4422](https://github.com/kurtosis-tech/ethereum-package/commit/51a44228994e2c0088ffccb3c2cca60376087bff))
* zero count validators and parallel keystore generation ([#302](https://github.com/kurtosis-tech/ethereum-package/issues/302)) ([18b141e](https://github.com/kurtosis-tech/ethereum-package/commit/18b141edf901b39c7ddc8cc60ba81b5185d4e15e))

## [0.6.1](https://github.com/kurtosis-tech/ethereum-package/compare/0.6.0...0.6.1) (2023-10-17)


### Bug Fixes

* `get_transaction_count` does not count pending transactions ([#299](https://github.com/kurtosis-tech/ethereum-package/issues/299)) ([2c64de0](https://github.com/kurtosis-tech/ethereum-package/commit/2c64de058ff0b8b207b6f6908c2daa6c321f12c4))
* big table spin up logic for k8s ([#298](https://github.com/kurtosis-tech/ethereum-package/issues/298)) ([e01ce16](https://github.com/kurtosis-tech/ethereum-package/commit/e01ce1602addba1eb132ebbe0c03439fdf060f58))

## [0.6.0](https://github.com/kurtosis-tech/ethereum-package/compare/0.5.1...0.6.0) (2023-10-17)


### Features

* Add builder metrics to default mev builder ([#277](https://github.com/kurtosis-tech/ethereum-package/issues/277)) ([d0eff2e](https://github.com/kurtosis-tech/ethereum-package/commit/d0eff2e9dd39411e71e1d36f9d0e66041ff33c0a))
* Add configurable spamming frequency to custom flood ([#283](https://github.com/kurtosis-tech/ethereum-package/issues/283)) ([f1e18ca](https://github.com/kurtosis-tech/ethereum-package/commit/f1e18ca7440ff9494b9a6bf6c20aa97a695d6084))
* add full beacon chain explorer ([#253](https://github.com/kurtosis-tech/ethereum-package/issues/253)) ([1eddda5](https://github.com/kurtosis-tech/ethereum-package/commit/1eddda5e61ecb86687ca2eae8d691a58cdafbd45))
* add inputs for additional grafana dashboards ([#279](https://github.com/kurtosis-tech/ethereum-package/issues/279)) ([ad02c43](https://github.com/kurtosis-tech/ethereum-package/commit/ad02c43c661de9151e541852520fd9f8e68fd0d1))
* added another blob spamming tool (`goomy_blob`) ([#268](https://github.com/kurtosis-tech/ethereum-package/issues/268)) ([3f2c797](https://github.com/kurtosis-tech/ethereum-package/commit/3f2c797900cf1bfbef9b3dcac35b204e3a258b69))
* Adding 4788 deployment ([#275](https://github.com/kurtosis-tech/ethereum-package/issues/275)) ([1c7de29](https://github.com/kurtosis-tech/ethereum-package/commit/1c7de293e44822aff2f26267285512c22d5f139c))
* return participants, timestamp of genesis and validator root for consumers ([#262](https://github.com/kurtosis-tech/ethereum-package/issues/262)) ([3f2ea88](https://github.com/kurtosis-tech/ethereum-package/commit/3f2ea88bb4792ececf7f723c72bce704effc016b))
* update ethereum-genesis-generator ([#260](https://github.com/kurtosis-tech/ethereum-package/issues/260)) ([a5b939c](https://github.com/kurtosis-tech/ethereum-package/commit/a5b939caa171f8cb7ab3979939f114a8b6398db7))


### Bug Fixes

* Add disable peer scoring ([#247](https://github.com/kurtosis-tech/ethereum-package/issues/247)) ([c75af3c](https://github.com/kurtosis-tech/ethereum-package/commit/c75af3cf3215d3aac3eb2d11eafdf9f3c7729512))
* editor config used tabs still ([#274](https://github.com/kurtosis-tech/ethereum-package/issues/274)) ([7bbba4c](https://github.com/kurtosis-tech/ethereum-package/commit/7bbba4c2b77abbc27efcb2a9af352af6cc932f9b))
* enable trace http-api for reth ([#251](https://github.com/kurtosis-tech/ethereum-package/issues/251)) ([ba47763](https://github.com/kurtosis-tech/ethereum-package/commit/ba4776365fca21c0a3a0e841834d7379443b76be))
* explicitly set persist to false ([#296](https://github.com/kurtosis-tech/ethereum-package/issues/296)) ([37d8ccd](https://github.com/kurtosis-tech/ethereum-package/commit/37d8ccd86da44bc2e8fd60150c36068d36c2cb8b))
* fix dora image ([#270](https://github.com/kurtosis-tech/ethereum-package/issues/270)) ([19fe54a](https://github.com/kurtosis-tech/ethereum-package/commit/19fe54a7ee5b9ced651c8f867c5b38b5ea529d8b))
* fix the tx_fuzzer params ([#278](https://github.com/kurtosis-tech/ethereum-package/issues/278)) ([b0ee145](https://github.com/kurtosis-tech/ethereum-package/commit/b0ee145e94bc1b02a4dde48f198ab97357fd1ce9))
* get rid of explorer type ([#280](https://github.com/kurtosis-tech/ethereum-package/issues/280)) ([f5595f4](https://github.com/kurtosis-tech/ethereum-package/commit/f5595f4cbb4307a0b14e9bf379a1823c40d7e170))
* Pass all beacons to the relay ([#226](https://github.com/kurtosis-tech/ethereum-package/issues/226)) ([b4fde3d](https://github.com/kurtosis-tech/ethereum-package/commit/b4fde3d064e498a14410f776a76d23af97fd4f0f))
* re run custom flood whenever it crashes ([#264](https://github.com/kurtosis-tech/ethereum-package/issues/264)) ([fab3995](https://github.com/kurtosis-tech/ethereum-package/commit/fab39957b28dbd9731cc15ec2fde242d7d71f5e3)), closes [#245](https://github.com/kurtosis-tech/ethereum-package/issues/245)
* readme deadlink ([#269](https://github.com/kurtosis-tech/ethereum-package/issues/269)) ([f380cc4](https://github.com/kurtosis-tech/ethereum-package/commit/f380cc4c70e6c5a4f7d5fd0a755231eaf232a31b))
* remove engine from http-api list for reth ([#249](https://github.com/kurtosis-tech/ethereum-package/issues/249)) ([b3114d1](https://github.com/kurtosis-tech/ethereum-package/commit/b3114d130f8a551853aac9774d864e8b7d36775a))
* return data about pariticpants even if no additional services are launched ([#273](https://github.com/kurtosis-tech/ethereum-package/issues/273)) ([d29f98e](https://github.com/kurtosis-tech/ethereum-package/commit/d29f98e580afeca3a5d6d305f607d6f297606b9b))
* set MEV image to 0.26.0 and complain if capella is zero with MEV set to full ([#261](https://github.com/kurtosis-tech/ethereum-package/issues/261)) ([9dfc4de](https://github.com/kurtosis-tech/ethereum-package/commit/9dfc4de19045ee2fd5be4eac31c341921d984e3d))
* use 0.27 as the mev boost image ([839af19](https://github.com/kurtosis-tech/ethereum-package/commit/839af1986480dec245b03e91a927d693526cd1a1))
* use ethpandaops/erigon as its multiarch ([839af19](https://github.com/kurtosis-tech/ethereum-package/commit/839af1986480dec245b03e91a927d693526cd1a1))

## [0.5.1](https://github.com/kurtosis-tech/ethereum-package/compare/0.5.0...0.5.1) (2023-09-28)


### Bug Fixes

* enable all apis for reth ([#241](https://github.com/kurtosis-tech/ethereum-package/issues/241)) ([db92f7b](https://github.com/kurtosis-tech/ethereum-package/commit/db92f7b01be1dd05c65eb88463dee76f2261f42f))
* rename light-beaconchain-explorer to dora-the-explorer & change db location ([#243](https://github.com/kurtosis-tech/ethereum-package/issues/243)) ([d3a4b49](https://github.com/kurtosis-tech/ethereum-package/commit/d3a4b495873eeb25647a113f3cd39ab42029faf8))

## [0.5.0](https://github.com/kurtosis-tech/ethereum-package/compare/0.4.0...0.5.0) (2023-09-28)


### ⚠ BREAKING CHANGES

* rename the package to ethereum-package ([#234](https://github.com/kurtosis-tech/ethereum-package/issues/234))

### Features

* add generic prometheus endpoints ([#209](https://github.com/kurtosis-tech/ethereum-package/issues/209)) ([d04e85f](https://github.com/kurtosis-tech/ethereum-package/commit/d04e85f4ce6b82b989a07087cf20fdd4c984573b))


### Bug Fixes

* add an MIT licence ([#246](https://github.com/kurtosis-tech/ethereum-package/issues/246)) ([f632ff1](https://github.com/kurtosis-tech/ethereum-package/commit/f632ff14cacf6aab9aab6ab29ef94b4b87848f90))
* make nimbus work with mev components ([#244](https://github.com/kurtosis-tech/ethereum-package/issues/244)) ([5c64ed5](https://github.com/kurtosis-tech/ethereum-package/commit/5c64ed5efcc064799d5c6154d3e7e9ca2d6343ef))


### Code Refactoring

* rename the package to ethereum-package ([#234](https://github.com/kurtosis-tech/ethereum-package/issues/234)) ([23e4d5e](https://github.com/kurtosis-tech/ethereum-package/commit/23e4d5ecdc24ef9a463cbe4a58ded162f79d0d1f))

## [0.4.0](https://github.com/kurtosis-tech/ethereum-package/compare/0.3.1...0.4.0) (2023-09-27)


### ⚠ BREAKING CHANGES

* merge eth-network-package onto ethereum-package ([#228](https://github.com/kurtosis-tech/ethereum-package/issues/228))

### Code Refactoring

* merge eth-network-package onto ethereum-package ([#228](https://github.com/kurtosis-tech/ethereum-package/issues/228)) ([b72dad3](https://github.com/kurtosis-tech/ethereum-package/commit/b72dad35ac0991a6a33e8720aaa5c9455d34752b))

## [0.3.1](https://github.com/kurtosis-tech/ethereum-package/compare/0.3.0...0.3.1) (2023-09-26)


### Features

* add blobspammer ([f166d71](https://github.com/kurtosis-tech/ethereum-package/commit/f166d714ac7f708f533ab3006b051da0859017a3))
* add blobspammer  ([#165](https://github.com/kurtosis-tech/ethereum-package/issues/165)) ([f166d71](https://github.com/kurtosis-tech/ethereum-package/commit/f166d714ac7f708f533ab3006b051da0859017a3))
* add support for electra ([#176](https://github.com/kurtosis-tech/ethereum-package/issues/176)) ([fbe6c00](https://github.com/kurtosis-tech/ethereum-package/commit/fbe6c004e5a9e47e4e819eddea7d2b424a555634))
* Add Tx_spamer_params and move MEV to the bottom of main.star ([#208](https://github.com/kurtosis-tech/ethereum-package/issues/208)) ([23628b2](https://github.com/kurtosis-tech/ethereum-package/commit/23628b27a8d571df1c90c5cbe84455c7382e091c))
* added a reliable flooder ([#186](https://github.com/kurtosis-tech/ethereum-package/issues/186)) ([8146ab7](https://github.com/kurtosis-tech/ethereum-package/commit/8146ab7b7d90817ca93a1ed2569a57aa64903231))
* all_el_metrics ([#195](https://github.com/kurtosis-tech/ethereum-package/issues/195)) ([3bbcca7](https://github.com/kurtosis-tech/ethereum-package/commit/3bbcca70346d6e1f67bec2023543404df832ffa6))
* Allow selection of additional services ([#220](https://github.com/kurtosis-tech/ethereum-package/issues/220)) ([57b15fe](https://github.com/kurtosis-tech/ethereum-package/commit/57b15fe49479e0aaada3379782f4e668b3bfdf71))
* Make args optional ([#190](https://github.com/kurtosis-tech/ethereum-package/issues/190)) ([a3ad030](https://github.com/kurtosis-tech/ethereum-package/commit/a3ad030810b2c0d3be02b52d6d6c4ccb17c1e5c0))
* pass slots per epoch to mev-boost-relay ([#188](https://github.com/kurtosis-tech/ethereum-package/issues/188)) ([14acb6f](https://github.com/kurtosis-tech/ethereum-package/commit/14acb6f94b9a43508e40ce61cb198f6c59425dc5))


### Bug Fixes

* bring back wait for capella fork epoch ([#212](https://github.com/kurtosis-tech/ethereum-package/issues/212)) ([c7cce7e](https://github.com/kurtosis-tech/ethereum-package/commit/c7cce7ea39c4030ded65400a75b75ca7389fe2cc))
* bug with participant counts that lead to more than needed participants ([#221](https://github.com/kurtosis-tech/ethereum-package/issues/221)) ([7b93f1c](https://github.com/kurtosis-tech/ethereum-package/commit/7b93f1ceb2d4f1311efd5fc6691c1ad95623ab83))
* dont wait for epoch 1 and launch MEV before tx-fuzz ([#210](https://github.com/kurtosis-tech/ethereum-package/issues/210)) ([8b883af](https://github.com/kurtosis-tech/ethereum-package/commit/8b883aff7811a2f36a36531be1c047d087c0ac93))
* fail capella fork epoch ([#196](https://github.com/kurtosis-tech/ethereum-package/issues/196)) ([ebff2d0](https://github.com/kurtosis-tech/ethereum-package/commit/ebff2d0b85a3da08725d88a5c4ce284cf28ef79b))
* fix mismatch between validator_count & metrics gazer ([#223](https://github.com/kurtosis-tech/ethereum-package/issues/223)) ([5dd4f9b](https://github.com/kurtosis-tech/ethereum-package/commit/5dd4f9b352a571775684b30fe6fd530512fa943b))
* Improve MEV setup to use less containers for non_validator nodes ([#224](https://github.com/kurtosis-tech/ethereum-package/issues/224)) ([bd176f0](https://github.com/kurtosis-tech/ethereum-package/commit/bd176f08941300c98740adc82a0cf0f03694c569))
* Kevin/postgres package upgrade ([#179](https://github.com/kurtosis-tech/ethereum-package/issues/179)) ([1bcc623](https://github.com/kurtosis-tech/ethereum-package/commit/1bcc623f6e2a260751869b3b519b759bf510a994))
* Kevin/unpin redis version ([#182](https://github.com/kurtosis-tech/ethereum-package/issues/182)) ([4eb7127](https://github.com/kurtosis-tech/ethereum-package/commit/4eb7127816098a4615f061e0203b7e162d4b3a75))
* lodestar flag ([#217](https://github.com/kurtosis-tech/ethereum-package/issues/217)) ([5f1e0f2](https://github.com/kurtosis-tech/ethereum-package/commit/5f1e0f2943a006426b638c0699ddd58c47cc57c0))
* mev should work with the validator count change ([#225](https://github.com/kurtosis-tech/ethereum-package/issues/225)) ([37dccce](https://github.com/kurtosis-tech/ethereum-package/commit/37dccce1c1a1760b1ecac9264985a844f0db46a6))
* mev-boost creation by making it depend on actual participant count ([#191](https://github.com/kurtosis-tech/ethereum-package/issues/191)) ([7606cff](https://github.com/kurtosis-tech/ethereum-package/commit/7606cffafc054153dc4ad43d925dad7cfa4a9984))
* Mock builder updates ([#193](https://github.com/kurtosis-tech/ethereum-package/issues/193)) ([6cc3697](https://github.com/kurtosis-tech/ethereum-package/commit/6cc369703f821da788d49c9418e1b4008796ce95))
* parse input ([#205](https://github.com/kurtosis-tech/ethereum-package/issues/205)) ([a787b38](https://github.com/kurtosis-tech/ethereum-package/commit/a787b38d8c8e61008244818581bf5d9a3103bd33))
* pass through env var now for builder_signing_tx_key ([#207](https://github.com/kurtosis-tech/ethereum-package/issues/207)) ([a63f2fd](https://github.com/kurtosis-tech/ethereum-package/commit/a63f2fd78613607dd4be195eb002fa9af3c6a894))
* Pin Redis version in prep for package catalog version upgrade ([#180](https://github.com/kurtosis-tech/ethereum-package/issues/180)) ([09b235a](https://github.com/kurtosis-tech/ethereum-package/commit/09b235a37f62c2fd6f99dd466a9918d7d468831d))
* remove hardcoding of addresses in MEV flood ([#184](https://github.com/kurtosis-tech/ethereum-package/issues/184)) ([21b0975](https://github.com/kurtosis-tech/ethereum-package/commit/21b0975f20a955354482092f5f04fcb4a85114b0))
* replace plan.assert with plan.verify ([#202](https://github.com/kurtosis-tech/ethereum-package/issues/202)) ([073135d](https://github.com/kurtosis-tech/ethereum-package/commit/073135ddc8ab5fb912b20bae96ec2ec72c3ac2f4))
* start boost immediately after relay starts running ([#213](https://github.com/kurtosis-tech/ethereum-package/issues/213)) ([b6ce1e9](https://github.com/kurtosis-tech/ethereum-package/commit/b6ce1e9132ded99c1398353fa4324bbf9fb6e78c))
* update readme for MEV params ([#189](https://github.com/kurtosis-tech/ethereum-package/issues/189)) ([c1bf13e](https://github.com/kurtosis-tech/ethereum-package/commit/c1bf13ee737f3437d0aca7cf3bfd9753e2f31d43))
* use 4th private key (index 3) for tx fuzz like before ([#215](https://github.com/kurtosis-tech/ethereum-package/issues/215)) ([1752ed0](https://github.com/kurtosis-tech/ethereum-package/commit/1752ed0a9861c0a2f7fb313dbe44a800e419b6bc))
* use the third address instead of coinbase for tx-fuzz ([#185](https://github.com/kurtosis-tech/ethereum-package/issues/185)) ([3b2993c](https://github.com/kurtosis-tech/ethereum-package/commit/3b2993c050172dec63c26d9b53c53fc7a77ad079))

## [0.3.0](https://github.com/kurtosis-tech/ethereum-package/compare/0.2.0...0.3.0) (2023-09-03)


### ⚠ BREAKING CHANGES

* Uses the `plan` object. Users will have to update their Kurtosis CLI to >= 0.63.0 and restart the engine

### Features

* add beacon-metrics-gazer + beacon-metrics-gazer grafana dashboard ([#114](https://github.com/kurtosis-tech/ethereum-package/issues/114)) ([5540587](https://github.com/kurtosis-tech/ethereum-package/commit/55405874ee50826b65dc2a5664e2b8bf9d7f668b))
* add deneb support ([#96](https://github.com/kurtosis-tech/ethereum-package/issues/96)) ([07ed500](https://github.com/kurtosis-tech/ethereum-package/commit/07ed500890ab01b6bed04cdacc19b9373e6a4b6a))
* add ethereumjs to nightly runners ([b86d886](https://github.com/kurtosis-tech/ethereum-package/commit/b86d886197ddad2d0ea78efac7e11109838b5dd9))
* add ethereumjs to nightly runners ([#154](https://github.com/kurtosis-tech/ethereum-package/issues/154)) ([b86d886](https://github.com/kurtosis-tech/ethereum-package/commit/b86d886197ddad2d0ea78efac7e11109838b5dd9))
* add forkmon ([#107](https://github.com/kurtosis-tech/ethereum-package/issues/107)) ([2a8ad19](https://github.com/kurtosis-tech/ethereum-package/commit/2a8ad19e8ad9c4202bd6dc9dff28eb3ea2cf08f2))
* add light-beaconchain-explorer ([83e01a1](https://github.com/kurtosis-tech/ethereum-package/commit/83e01a114a3bad970ebecc2ae10bc863e14cdb3a))
* add light-beaconchain-explorer ([#125](https://github.com/kurtosis-tech/ethereum-package/issues/125)) ([83e01a1](https://github.com/kurtosis-tech/ethereum-package/commit/83e01a114a3bad970ebecc2ae10bc863e14cdb3a))
* add multiple endpoint support for lightbeaconchain expolorer ([#151](https://github.com/kurtosis-tech/ethereum-package/issues/151)) ([68572cd](https://github.com/kurtosis-tech/ethereum-package/commit/68572cdddb1e2074892f148b69e603a2ee06edb8))
* counting by summing each participant ([f9b638b](https://github.com/kurtosis-tech/ethereum-package/commit/f9b638bc1c26be34fd3dd0ad6e4d59ee4ecd66c3))
* counting by summing each participant ([#112](https://github.com/kurtosis-tech/ethereum-package/issues/112)) ([f9b638b](https://github.com/kurtosis-tech/ethereum-package/commit/f9b638bc1c26be34fd3dd0ad6e4d59ee4ecd66c3))
* disable login for grafana ([4d7df4b](https://github.com/kurtosis-tech/ethereum-package/commit/4d7df4be895b950119d1e5fabe0e4ae3cc0c822e))
* disable login for grafana ([#122](https://github.com/kurtosis-tech/ethereum-package/issues/122)) ([4d7df4b](https://github.com/kurtosis-tech/ethereum-package/commit/4d7df4be895b950119d1e5fabe0e4ae3cc0c822e))
* **formatting:** Add editorconfig, move everything to using tabs (4) ([#106](https://github.com/kurtosis-tech/ethereum-package/issues/106)) ([cb0fc69](https://github.com/kurtosis-tech/ethereum-package/commit/cb0fc695cce7a64386349193ef3cd3ebf692f18d))
* launch the mock mev builder ([#94](https://github.com/kurtosis-tech/ethereum-package/issues/94)) ([7fcd3e2](https://github.com/kurtosis-tech/ethereum-package/commit/7fcd3e24aa1d1c23afa0c37ba3c939c204720d31))
* make it possible to have capella on epoch 0 or non 0 ([#108](https://github.com/kurtosis-tech/ethereum-package/issues/108)) ([1133497](https://github.com/kurtosis-tech/ethereum-package/commit/1133497b18c6fa46f2b6483c9b2eea27bc272868))
* make mev more configurable ([#164](https://github.com/kurtosis-tech/ethereum-package/issues/164)) ([0165ef1](https://github.com/kurtosis-tech/ethereum-package/commit/0165ef1a67a77dfca2030c1b36ed12d00ae48d18))
* parameterize mev_boost and  mev_builder images ([#171](https://github.com/kurtosis-tech/ethereum-package/issues/171)) ([28adec1](https://github.com/kurtosis-tech/ethereum-package/commit/28adec114779e0b5946705038cb19c859c430242))
* snooper support ([#121](https://github.com/kurtosis-tech/ethereum-package/issues/121)) ([d2cccf4](https://github.com/kurtosis-tech/ethereum-package/commit/d2cccf4af8873a912cc4389f8db75ce4e11e2e44))
* support full MEV ([#115](https://github.com/kurtosis-tech/ethereum-package/issues/115)) ([e9e8c41](https://github.com/kurtosis-tech/ethereum-package/commit/e9e8c418c4a7a9ff099b4514430f8235f4ad1331))
* use eth-network-package to spin up participant network ([#90](https://github.com/kurtosis-tech/ethereum-package/issues/90)) ([91029ac](https://github.com/kurtosis-tech/ethereum-package/commit/91029acfb7867c134baac3aaf758eb06f67fe997))


### Bug Fixes

* a bug around participants ([#129](https://github.com/kurtosis-tech/ethereum-package/issues/129)) ([9382767](https://github.com/kurtosis-tech/ethereum-package/commit/9382767f88690817de189a3551c37325389faf98))
* delay deneb to 500 epoch ([#102](https://github.com/kurtosis-tech/ethereum-package/issues/102)) ([d07270b](https://github.com/kurtosis-tech/ethereum-package/commit/d07270bc9802fe2adc44d70e6e8e9c274958eacb))
* dont spin up extra el/cl client for mock-mev ([#158](https://github.com/kurtosis-tech/ethereum-package/issues/158)) ([46d67fc](https://github.com/kurtosis-tech/ethereum-package/commit/46d67fc5878a01984623c8f3ac9f667d1fb891f2))
* fix an arg parsing bug ([#135](https://github.com/kurtosis-tech/ethereum-package/issues/135)) ([f084e7c](https://github.com/kurtosis-tech/ethereum-package/commit/f084e7c72738b7afd71d9a1a05f6fba4c388a5de))
* fix passed argument parsing ([#85](https://github.com/kurtosis-tech/ethereum-package/issues/85)) ([a5d40e9](https://github.com/kurtosis-tech/ethereum-package/commit/a5d40e9bd178ff7ade06f22818475d01546f861a))
* fixed teku validator params for MEV ([#149](https://github.com/kurtosis-tech/ethereum-package/issues/149)) ([b0079cf](https://github.com/kurtosis-tech/ethereum-package/commit/b0079cff08b7c5812e97151ba56a0929593516ba))
* fixing nimbus payload url ([#155](https://github.com/kurtosis-tech/ethereum-package/issues/155)) ([55c1f59](https://github.com/kurtosis-tech/ethereum-package/commit/55c1f59404872c26315844995cbea6a4286b1cb2))
* geth failing after ethash package removal ([#93](https://github.com/kurtosis-tech/ethereum-package/issues/93)) ([41e3d2c](https://github.com/kurtosis-tech/ethereum-package/commit/41e3d2cd292dd19b805e5c93f3d65ec0ba063104)), closes [#91](https://github.com/kurtosis-tech/ethereum-package/issues/91)
* make besu a bootnode ([29296cd](https://github.com/kurtosis-tech/ethereum-package/commit/29296cd1c78615743d32f68ca50fb51121c5921c))
* make besu a bootnode ([#146](https://github.com/kurtosis-tech/ethereum-package/issues/146)) ([29296cd](https://github.com/kurtosis-tech/ethereum-package/commit/29296cd1c78615743d32f68ca50fb51121c5921c))
* make this work with kurtosis 0.65.0 ([#73](https://github.com/kurtosis-tech/ethereum-package/issues/73)) ([13c72ec](https://github.com/kurtosis-tech/ethereum-package/commit/13c72ec56e4da79c6a9bd6802a0995c6b00d0a0a))
* mention reth in package readme ([#133](https://github.com/kurtosis-tech/ethereum-package/issues/133)) ([d11a689](https://github.com/kurtosis-tech/ethereum-package/commit/d11a6898b9f7377a5e8c50ccd3859ec5eed0e556))
* move parallel keystore generation to global config ([0789eed](https://github.com/kurtosis-tech/ethereum-package/commit/0789eedb1f77c418944a2cc7047edd95256d983d))
* move parallel keystore generation to global config ([#130](https://github.com/kurtosis-tech/ethereum-package/issues/130)) ([0789eed](https://github.com/kurtosis-tech/ethereum-package/commit/0789eedb1f77c418944a2cc7047edd95256d983d))
* nightly tests that rely on etherejums get the right image ([#159](https://github.com/kurtosis-tech/ethereum-package/issues/159)) ([97b4d33](https://github.com/kurtosis-tech/ethereum-package/commit/97b4d33aa4c236e9615df7f3c62e6221a056385f))
* Nimbus can't run when slot time is below 12s ([#100](https://github.com/kurtosis-tech/ethereum-package/issues/100)) ([c38bff9](https://github.com/kurtosis-tech/ethereum-package/commit/c38bff9f5d6d49f57c1a66c84828f8bad9c550cc))
* pass right mev-boost url to teku ([#147](https://github.com/kurtosis-tech/ethereum-package/issues/147)) ([8bb75d9](https://github.com/kurtosis-tech/ethereum-package/commit/8bb75d91b9a45a5a2fc7e64118d5913ffef138f4))
* pin postgres package ([#174](https://github.com/kurtosis-tech/ethereum-package/issues/174)) ([6b8d9d3](https://github.com/kurtosis-tech/ethereum-package/commit/6b8d9d39fd06d1dc01d4f3cbbc6c20f9f962bb6a))
* Remove nethermind restriction ([#126](https://github.com/kurtosis-tech/ethereum-package/issues/126)) ([373c6c9](https://github.com/kurtosis-tech/ethereum-package/commit/373c6c9b45ac4fc9bee930bc5430921cd3a16a1f))
* Switch default images to latest ([#99](https://github.com/kurtosis-tech/ethereum-package/issues/99)) ([4a85c9d](https://github.com/kurtosis-tech/ethereum-package/commit/4a85c9dccb0e5cbd809ed7047b78e7190d466a91))
* Update enclave name flag ([#87](https://github.com/kurtosis-tech/ethereum-package/issues/87)) ([6531a7a](https://github.com/kurtosis-tech/ethereum-package/commit/6531a7af37faa2d227a2a53739ca7ae0cd4aed9e))
* update genesis generator to support netherminds new format ([#68](https://github.com/kurtosis-tech/ethereum-package/issues/68)) ([094352d](https://github.com/kurtosis-tech/ethereum-package/commit/094352d6666755da5de6ed3f4b78fd5f37c01f7f))
* update nightly runner ([#163](https://github.com/kurtosis-tech/ethereum-package/issues/163)) ([4eba65d](https://github.com/kurtosis-tech/ethereum-package/commit/4eba65df4fd29ece8a89ac77066e68d330fc2297))
* use eth maintained tx-fuzz ([#110](https://github.com/kurtosis-tech/ethereum-package/issues/110)) ([b0903bd](https://github.com/kurtosis-tech/ethereum-package/commit/b0903bdae490ffa30251ddede9edca21105fba48))
* use flashbots builder ([#162](https://github.com/kurtosis-tech/ethereum-package/issues/162)) ([7a0c2d0](https://github.com/kurtosis-tech/ethereum-package/commit/7a0c2d03dff1dd0ee5c92b5c2f9478f4e56f6920))
* use mev-boost-relay by flashbots ([#141](https://github.com/kurtosis-tech/ethereum-package/issues/141)) ([fca62fc](https://github.com/kurtosis-tech/ethereum-package/commit/fca62fcee23525cc891eaf2494a2b1cb694f5bf4))
* use named artifacts ([#69](https://github.com/kurtosis-tech/ethereum-package/issues/69)) ([968f073](https://github.com/kurtosis-tech/ethereum-package/commit/968f0734a0ee834c75e184b758989ce1dc9d58be)), closes [#70](https://github.com/kurtosis-tech/ethereum-package/issues/70)
* Use plan object ([#65](https://github.com/kurtosis-tech/ethereum-package/issues/65)) ([8e5d185](https://github.com/kurtosis-tech/ethereum-package/commit/8e5d18558f92a9fc71ae9a70f1ca139df406d7b7))
* use v2 endoint to get the head block ([#153](https://github.com/kurtosis-tech/ethereum-package/issues/153)) ([f084711](https://github.com/kurtosis-tech/ethereum-package/commit/f084711061c777c78ef8f002a4f7e597c27e8eb5))
* work with latest eth-network-package ([14dc957](https://github.com/kurtosis-tech/ethereum-package/commit/14dc95776e16f8cdf8ac83a03c53abad489cb8f7))
* work with latest eth-network-package ([#116](https://github.com/kurtosis-tech/ethereum-package/issues/116)) ([14dc957](https://github.com/kurtosis-tech/ethereum-package/commit/14dc95776e16f8cdf8ac83a03c53abad489cb8f7))

## 0.2.0

- Adds config variables for `genesis_delay` and `capella_fork_epoch`
- Updates genesis generator version
- Fixes genesis timestamp such that the shanghai fork can happen based on timestamps
- Update `--enclave-id` flag to `--enclave` in README

### Breaking Change

- Introduced optional application protocol and renamed protocol to transport_protocol

## 0.1.0

### Breaking changes

- Updated `struct` to `PortSpec` for declaring port definitions

### Changes

- Change `exec` syntax

## 0.0.5

### Fixes

- Fix bug with input parsing of participants
- Fix bug with `get_enode_for_node` being assigned to two parameters

### Changes

- Updated `run(input_args)` to `run(args)`
- Refactor code to use `wait` and `request` commands
- Removed `print(output)` at the end as it is now printed by the framework
- Updates nimbus default docker image
- Updates `genesis-generator` image to include a fix for nimbus post-merge genesis
- Use the `args` argument instead of flags

## 0.0.4

### Changes

- Removed 'module' key in the 'kurtosis.yml' file

## 0.0.3

### Changes

- Replaced 'module' with 'package' where relevant
- Removed protobuf types as they are now unsupported in Kurtosis.
- Renamed `kurtotis.mod` to `kurtosis.yml`

### Fixes

- Fixed a bug in `run` of `main.star` where we'd refer to `module_io` instead of `package_io`

## 0.0.2

### Features

- Added the docs

### Fixes

- Renamed `num_validators_per_keynode` to `num_validator_keys_per_node`
- Moved away from `load` infavor of `import_module`
- Moved away from `store_files_from_service` to `store_service_files`
- Removed empty `ports` from a few service configs as passing it is now optional
- Adjusted to the new render templates config
- Moved away from passing json string to struct/dict for render templates

### Changes

- Move from `main` to `run` in `main.star`

## 0.0.1

### Features

- Changed the .circlei/config.yml to apply to Startosis
- Added genesis_constants
- Added a lot of participant_network/pre_launch_data_generator
- Added a lot of simple objects that just keep data
- Added monitoring on top of the repo
- Almost perfect parity with the eth2-merge-kurtosis-module

### Fixes

- Fixes some bugs with the initial implementation of the monitors

## 0.0.0

- Initial commit
