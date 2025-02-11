# Changelog

## [0.5.4](https://github.com/open-feature/flagd/compare/core/v0.5.3...core/v0.5.4) (2023-06-07)


### ✨ New Features

* add `sem_ver` jsonLogic evaluator ([#675](https://github.com/open-feature/flagd/issues/675)) ([a8d8ab6](https://github.com/open-feature/flagd/commit/a8d8ab6b4495457a40a2c32b8bd5be48b1fd6941))
* add `starts_with` and `ends_with` json evaluators ([#658](https://github.com/open-feature/flagd/issues/658)) ([f932b8f](https://github.com/open-feature/flagd/commit/f932b8f4c834a5ebe27ebb860c26fdea8da20598))
* telemetry improvements ([#653](https://github.com/open-feature/flagd/issues/653)) ([ea02cba](https://github.com/open-feature/flagd/commit/ea02cba24bde982d55956fe54de1e8f27226bfc6))


### 🐛 Bug Fixes

* **deps:** update module github.com/bufbuild/connect-go to v1.8.0 ([#683](https://github.com/open-feature/flagd/issues/683)) ([13bb13d](https://github.com/open-feature/flagd/commit/13bb13daa11068481ba97f3432ae08de78392a91))
* **deps:** update module github.com/bufbuild/connect-opentelemetry-go to v0.3.0 ([#669](https://github.com/open-feature/flagd/issues/669)) ([e899435](https://github.com/open-feature/flagd/commit/e899435c29c32264ea2477436e69ce92c7775ee9))
* **deps:** update module github.com/prometheus/client_golang to v1.15.1 ([#636](https://github.com/open-feature/flagd/issues/636)) ([b22279d](https://github.com/open-feature/flagd/commit/b22279df469dc78f9d3e5bc4a59ab6baf539a8ae))
* **deps:** update module github.com/stretchr/testify to v1.8.3 ([#662](https://github.com/open-feature/flagd/issues/662)) ([2e06d58](https://github.com/open-feature/flagd/commit/2e06d582ee9c8abfd57f8945d91261eab6cf9854))
* **deps:** update module github.com/stretchr/testify to v1.8.4 ([#678](https://github.com/open-feature/flagd/issues/678)) ([ca8c9d6](https://github.com/open-feature/flagd/commit/ca8c9d66a0c6b21129c4c36a3c10dcf3be869ee7))
* **deps:** update module golang.org/x/mod to v0.10.0 ([#682](https://github.com/open-feature/flagd/issues/682)) ([16199ce](https://github.com/open-feature/flagd/commit/16199ceac9ebbae68dafbd6c21239f64f8c32511))
* **deps:** update module golang.org/x/net to v0.10.0 ([#644](https://github.com/open-feature/flagd/issues/644)) ([ccd9d35](https://github.com/open-feature/flagd/commit/ccd9d351df153039a124064f30e5829610773f27))
* **deps:** update module golang.org/x/sync to v0.2.0 ([#638](https://github.com/open-feature/flagd/issues/638)) ([7f4a7db](https://github.com/open-feature/flagd/commit/7f4a7db8139294a21b3415710c143f182d93264a))
* **deps:** update module google.golang.org/grpc to v1.55.0 ([#640](https://github.com/open-feature/flagd/issues/640)) ([c0d7328](https://github.com/open-feature/flagd/commit/c0d732866262240e340fe10f8ac0f6ff2a5c4f8c))
* **deps:** update module sigs.k8s.io/controller-runtime to v0.15.0 ([#665](https://github.com/open-feature/flagd/issues/665)) ([9490ed6](https://github.com/open-feature/flagd/commit/9490ed62e2fc589af8ae7ee26bfd559797a1f83c))
* fix connect error code handling for disabled flags ([#670](https://github.com/open-feature/flagd/issues/670)) ([86a8012](https://github.com/open-feature/flagd/commit/86a8012efcfeb3e967657f6143c143b457d64ca2))
* remove disabled flags from bulk evaluation ([#672](https://github.com/open-feature/flagd/issues/672)) ([d2ce988](https://github.com/open-feature/flagd/commit/d2ce98838edf63b88ee9fb5ae6f8d534e1112e7e))


### 🔄 Refactoring

* introduce additional linting rules + fix discrepancies ([#616](https://github.com/open-feature/flagd/issues/616)) ([aef0b90](https://github.com/open-feature/flagd/commit/aef0b9042dcbe5b3f9a7e97960b27366fe50adfe))
* introduce isyncstore interface ([#660](https://github.com/open-feature/flagd/issues/660)) ([c0e2fa0](https://github.com/open-feature/flagd/commit/c0e2fa00736d46db98f72114a449b2e2bf998e3d))


### 🧹 Chore

* refactor json logic evaluator to pass custom operators as options ([#691](https://github.com/open-feature/flagd/issues/691)) ([1c9bff9](https://github.com/open-feature/flagd/commit/1c9bff9a523037c3654b592dc08c193aa3295e9e))
* update otel dependencies ([#649](https://github.com/open-feature/flagd/issues/649)) ([2114e41](https://github.com/open-feature/flagd/commit/2114e41c38951247866c0b408e5f933282902e70))

## [0.5.3](https://github.com/open-feature/flagd/compare/core/v0.5.2...core/v0.5.3) (2023-05-04)


### 🐛 Bug Fixes

* **deps:** update module github.com/bufbuild/connect-go to v1.6.0 ([#585](https://github.com/open-feature/flagd/issues/585)) ([8f2f467](https://github.com/open-feature/flagd/commit/8f2f467af52a3686196a821eec61954d89d3f71d))
* **deps:** update module github.com/bufbuild/connect-go to v1.7.0 ([#625](https://github.com/open-feature/flagd/issues/625)) ([1b24fc9](https://github.com/open-feature/flagd/commit/1b24fc923a405b337634009831ef0b9792953ce5))
* **deps:** update module github.com/open-feature/open-feature-operator to v0.2.34 ([#604](https://github.com/open-feature/flagd/issues/604)) ([3e6a84b](https://github.com/open-feature/flagd/commit/3e6a84b455a330f541784b346d3b6199f8b423f7))
* **deps:** update module github.com/prometheus/client_golang to v1.15.0 ([#608](https://github.com/open-feature/flagd/issues/608)) ([0597a8f](https://github.com/open-feature/flagd/commit/0597a8f23d0914b26f06b1335b49fe7c18ecb4f9))
* **deps:** update module github.com/rs/cors to v1.9.0 ([#609](https://github.com/open-feature/flagd/issues/609)) ([97066c1](https://github.com/open-feature/flagd/commit/97066c107d14777eaad8a05b3bb051639af3179c))
* **deps:** update module github.com/rs/xid to v1.5.0 ([#614](https://github.com/open-feature/flagd/issues/614)) ([e3dfbc6](https://github.com/open-feature/flagd/commit/e3dfbc6753bddc9e2f5c4a2633a7010123cf2f97))
* **deps:** update module golang.org/x/crypto to v0.8.0 ([#595](https://github.com/open-feature/flagd/issues/595)) ([36016d7](https://github.com/open-feature/flagd/commit/36016d7940fa772c01dd61b071b2c9ec753cfb75))


### ✨ New Features

* Introduce connect traces ([#624](https://github.com/open-feature/flagd/issues/624)) ([28bac6a](https://github.com/open-feature/flagd/commit/28bac6a54aed79cb8d84a147ffea296c36f5bd51))


### 🧹 Chore

* add instructions for windows and fix failing unit tests ([#632](https://github.com/open-feature/flagd/issues/632)) ([6999d67](https://github.com/open-feature/flagd/commit/6999d6722581ab8e2e14bfd4b2d0341fe5216684))

## [0.5.2](https://github.com/open-feature/flagd/compare/core/v0.5.1...core/v0.5.2) (2023-04-13)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/open-feature-operator to v0.2.32 [security] ([#606](https://github.com/open-feature/flagd/issues/606)) ([6f721af](https://github.com/open-feature/flagd/commit/6f721af379fcb0f1a74410637a313477148ef863))
* eventing configuration setup ([#605](https://github.com/open-feature/flagd/issues/605)) ([edfbe51](https://github.com/open-feature/flagd/commit/edfbe5191651f25da991b507a3feedcbbe3c66f1))


### ✨ New Features

* introduce metrics for failed evaluations ([#584](https://github.com/open-feature/flagd/issues/584)) ([77664cd](https://github.com/open-feature/flagd/commit/77664cdf53a868f56ca040bdfe3f4930cd9a8fb4))
* otel traces for flag evaluation ([#598](https://github.com/open-feature/flagd/issues/598)) ([1757035](https://github.com/open-feature/flagd/commit/175703548f88469f25d749e320ee48030c9f9074))

## [0.5.1](https://github.com/open-feature/flagd/compare/core/v0.5.0...core/v0.5.1) (2023-04-12)


### 🧹 Chore

* move startServer functions into errGroups ([#566](https://github.com/open-feature/flagd/issues/566)) ([0223c23](https://github.com/open-feature/flagd/commit/0223c23fbd72322cf6ecbe6736968b3e6c6132bb))


### ✨ New Features

* flagd OTEL collector ([#586](https://github.com/open-feature/flagd/issues/586)) ([494bec3](https://github.com/open-feature/flagd/commit/494bec33dcc1ddf0fa5cd0866f06265618408f5e))


### 🔄 Refactoring

* remove connect-go from flagd-proxy and replace with grpc ([#589](https://github.com/open-feature/flagd/issues/589)) ([425de9a](https://github.com/open-feature/flagd/commit/425de9a1c2d1574779b905ac6debb9edfc156b15))


### 🐛 Bug Fixes

* flagd-proxy locking bug fix ([#592](https://github.com/open-feature/flagd/issues/592)) ([b166122](https://github.com/open-feature/flagd/commit/b1661225c912ee11ba4749f7ef157a0335e8781f))

## [0.5.0](https://github.com/open-feature/flagd/compare/core/v0.4.5...core/v0.5.0) (2023-03-30)


### ⚠ BREAKING CHANGES

* rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/open-feature/flagd/issues/576))
* unify sources configuration handling ([#560](https://github.com/open-feature/flagd/issues/560))

### 🧹 Chore

* move credential builder for grpc sync into seperate component ([#536](https://github.com/open-feature/flagd/issues/536)) ([7314fee](https://github.com/open-feature/flagd/commit/7314feea8c7bc90aac0528a9e1be0759a7a60c15))
* refactor configuration handling for startup ([#551](https://github.com/open-feature/flagd/issues/551)) ([8dfbde5](https://github.com/open-feature/flagd/commit/8dfbde5bbffd16fb66797a750d15f0226edf54a7))
* refactor middleware setup in server ([#554](https://github.com/open-feature/flagd/issues/554)) ([01016c7](https://github.com/open-feature/flagd/commit/01016c7df7c5f653cdadf151539432f692f36251))
* refactor service configuration objects ([#545](https://github.com/open-feature/flagd/issues/545)) ([c7b29ed](https://github.com/open-feature/flagd/commit/c7b29edcfe9dab61eaa585011a690d47829601b6)), closes [#524](https://github.com/open-feature/flagd/issues/524)
* unify sources configuration handling ([#560](https://github.com/open-feature/flagd/issues/560)) ([7f4888a](https://github.com/open-feature/flagd/commit/7f4888a1676e49acecf328685623566ea057ffcf))


### 🐛 Bug Fixes

* **deps:** update module google.golang.org/grpc to v1.54.0 ([#548](https://github.com/open-feature/flagd/issues/548)) ([99ba5ec](https://github.com/open-feature/flagd/commit/99ba5ece76d98124c108bc6280bee03a5c0cd25d))
* **deps:** update module sigs.k8s.io/controller-runtime to v0.14.6 ([#572](https://github.com/open-feature/flagd/issues/572)) ([bed9458](https://github.com/open-feature/flagd/commit/bed94584a30bb6752284ece152cb114a102cbe8a))
* fixing silent lint failures ([#550](https://github.com/open-feature/flagd/issues/550)) ([30c8022](https://github.com/open-feature/flagd/commit/30c8022e891d1d278c096dd2438137ced7552678))
* nil pointer fix + export constructors ([#555](https://github.com/open-feature/flagd/issues/555)) ([78adb81](https://github.com/open-feature/flagd/commit/78adb81f4eb7a5b7fdb7075fa0bf8afa6d03dc72))


### ✨ New Features

* expose Impression metric ([#556](https://github.com/open-feature/flagd/issues/556)) ([77e0a33](https://github.com/open-feature/flagd/commit/77e0a33be24dcd0b6e239e5ed709167167c14171))
* Introduce kube-proxy-metrics ([#558](https://github.com/open-feature/flagd/issues/558)) ([ad0baeb](https://github.com/open-feature/flagd/commit/ad0baeb08fa67c94356d6a3f298283373bd5211b))
* rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/open-feature/flagd/issues/576)) ([223de99](https://github.com/open-feature/flagd/commit/223de99ee3efbcd601bf75ab1f6258eeac0c426e))
* refactor core module into multiple packages ([#530](https://github.com/open-feature/flagd/issues/530)) ([9d68d0b](https://github.com/open-feature/flagd/commit/9d68d0b45815facdf6079ffcd7864f720ccb8475))

## [0.4.5](https://github.com/open-feature/flagd/compare/core/v0.4.4...core/v0.4.5) (2023-03-20)


### 🐛 Bug Fixes

* **deps:** update kubernetes packages to v0.26.3 ([#533](https://github.com/open-feature/flagd/issues/533)) ([6ddd5b2](https://github.com/open-feature/flagd/commit/6ddd5b29806f3101cf122bfc4196ba7d0ef4c025))
* **deps:** update module github.com/open-feature/open-feature-operator to v0.2.31 ([#527](https://github.com/open-feature/flagd/issues/527)) ([7928130](https://github.com/open-feature/flagd/commit/7928130b10906b10f4501630f16a71bdd8e4e365))
* **deps:** update module google.golang.org/protobuf to v1.29.1 [security] ([#504](https://github.com/open-feature/flagd/issues/504)) ([59db0bb](https://github.com/open-feature/flagd/commit/59db0bba43a9c002378fdced2fcf4729d619e28b))
* **deps:** update module google.golang.org/protobuf to v1.30.0 ([#499](https://github.com/open-feature/flagd/issues/499)) ([f650338](https://github.com/open-feature/flagd/commit/f650338e01e721a9d24e2ed6f6fe585dbb6beb42))


### ✨ New Features

* grpc connection options to flagd configuration options ([#532](https://github.com/open-feature/flagd/issues/532)) ([aa74951](https://github.com/open-feature/flagd/commit/aa74951f43b662ff2df53e68d347fc10e6d23bb8))
* Introduce flagd kube proxy ([#495](https://github.com/open-feature/flagd/issues/495)) ([440864c](https://github.com/open-feature/flagd/commit/440864ce87174618321c9d5146221490d8f07b24))

## [0.4.4](https://github.com/open-feature/flagd/compare/core-v0.4.3...core/v0.4.4) (2023-03-10)


### ✨ New Features

* Restructure for monorepo setup ([#486](https://github.com/open-feature/flagd/issues/486)) ([ed2993c](https://github.com/open-feature/flagd/commit/ed2993cd67b8a46db3beb6bb8a360e1aa20349da))
