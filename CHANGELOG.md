# Changelog

## [0.1.8](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.7...v0.1.8) (2025-01-30)


### Miscellaneous Chores

* **deps:** update helm release argo-cd to v7.7.18 ([#20](https://github.com/schrodingers-stack/helm-argo-cd/issues/20)) ([103e6b1](https://github.com/schrodingers-stack/helm-argo-cd/commit/103e6b1693521db4bba5b67a49aeb6fde39f8318))
* **deps:** update helm release argo-cd to v7.7.22 ([#22](https://github.com/schrodingers-stack/helm-argo-cd/issues/22)) ([097caff](https://github.com/schrodingers-stack/helm-argo-cd/commit/097cafff1caf3240845b5e6a6abd98bc7506cb18))

## [0.1.7](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.6...v0.1.7) (2025-01-24)


### Miscellaneous Chores

* **deps:** update helm release argo-cd to v7.7.17 ([#18](https://github.com/schrodingers-stack/helm-argo-cd/issues/18)) ([13298ae](https://github.com/schrodingers-stack/helm-argo-cd/commit/13298ae89a95e826d77aa10ae8201ec8dc13cbcd))

## [0.1.6](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.5...v0.1.6) (2025-01-15)


### Miscellaneous Chores

* **deps:** update helm release argo-cd to v7.7.16 ([#16](https://github.com/schrodingers-stack/helm-argo-cd/issues/16)) ([ef67e20](https://github.com/schrodingers-stack/helm-argo-cd/commit/ef67e20828b5f23cd99d2c3c4c205ca01dc94dda))

## [0.1.5](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.4...v0.1.5) (2025-01-08)


### Miscellaneous Chores

* **deps:** update helm release argo-cd to v7.7.14 ([#14](https://github.com/schrodingers-stack/helm-argo-cd/issues/14)) ([f0c1c43](https://github.com/schrodingers-stack/helm-argo-cd/commit/f0c1c43287cd6d6122644daf2e8afbe740bb41b8))

## [0.1.4](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.3...v0.1.4) (2024-12-24)


### Features

* add default Schtack labels ([f7a45d2](https://github.com/schrodingers-stack/helm-argo-cd/commit/f7a45d2e014252d444806b0b497067f96f90249f))
* add new values with resources, ingress and HA configuration ([568bde8](https://github.com/schrodingers-stack/helm-argo-cd/commit/568bde8b860acf4ca2655df3bd4ca6bb5accb086))


### Styles

* stylize domain for consistency ([5083465](https://github.com/schrodingers-stack/helm-argo-cd/commit/508346579b9048a1e32b05a14b4dee9cfe0efe3a))
* use more generic domain ([d35f5d0](https://github.com/schrodingers-stack/helm-argo-cd/commit/d35f5d066d3430cf391946db001686a7e616b656))


### Miscellaneous Chores

* **deps:** update helm release argo-cd to v7.7.10 ([#11](https://github.com/schrodingers-stack/helm-argo-cd/issues/11)) ([ee54c6c](https://github.com/schrodingers-stack/helm-argo-cd/commit/ee54c6c46d00ab7ff4a8f40ee9ef0137f4b19e2f))
* **deps:** update helm release argo-cd to v7.7.11 ([#13](https://github.com/schrodingers-stack/helm-argo-cd/issues/13)) ([0a457cb](https://github.com/schrodingers-stack/helm-argo-cd/commit/0a457cb6712a08bac1ba0d600620b1c6f2f8ce0a))


### Continuous Integration

* add config to enable Renovate ([2829f33](https://github.com/schrodingers-stack/helm-argo-cd/commit/2829f33b93b0ab7dfa3be6893bf83e641bf1b25c))

## [0.1.3](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.2...v0.1.3) (2024-12-06)


### Bug Fixes

* shorten namespace prefix to improve readability in the UI ([4755ac1](https://github.com/schrodingers-stack/helm-argo-cd/commit/4755ac1e960ad6efb76950fc9c2ab33df05bc540))

## [0.1.2](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.1...v0.1.2) (2024-11-29)


### Bug Fixes

* disable the SCM generator in ApplicationSets ([12f3bf4](https://github.com/schrodingers-stack/helm-argo-cd/commit/12f3bf4c04c6b7f51ef457381039afa4c5873ff5))

## [0.1.1](https://github.com/schrodingers-stack/helm-argo-cd/compare/v0.1.0...v0.1.1) (2024-11-29)


### Features

* enable Applications from any namespace ([f5c40ff](https://github.com/schrodingers-stack/helm-argo-cd/commit/f5c40ff8360e28315511d54f39a780e0862592f0))


### Code Refactoring

* rename the template for the Grafana charts ([f24a1dd](https://github.com/schrodingers-stack/helm-argo-cd/commit/f24a1ddbac1fa61822a8b939c8e5ef89eb65366e))

## 0.1.0 (2024-11-21)


### Features

* initial commit (migrate code form monorepository) ([1ac9c7e](https://github.com/schrodingers-stack/helm-argo-cd/commit/1ac9c7e990dc3e6544ae7ba12f9bc265f52fc7b2))
* update Argo CD chart ([6547445](https://github.com/schrodingers-stack/helm-argo-cd/commit/6547445e0b681e2c883600060dadb2bd1448a9e9))


### Bug Fixes

* enable admin user only for the bootstrap ([f3b981c](https://github.com/schrodingers-stack/helm-argo-cd/commit/f3b981c3bfa577cc23739acfc08dd65ade172814))


### Miscellaneous Chores

* add comment to update version on Chart.yaml ([cf653cc](https://github.com/schrodingers-stack/helm-argo-cd/commit/cf653cc5d1c5ce69b63903e6bf36badc464e5bea))
* add website and description to Chart.yaml ([f332781](https://github.com/schrodingers-stack/helm-argo-cd/commit/f332781648d7f15c9ea44fd7fea46c0b86d28511))
* add/edit .gitignore ([6df3dce](https://github.com/schrodingers-stack/helm-argo-cd/commit/6df3dce76e0b958fbc53fa442b33f86043b9c020))
* add/edit .gitignore ([76f2e0b](https://github.com/schrodingers-stack/helm-argo-cd/commit/76f2e0b1339df09ec2ab78d003b85595471982b6))
* add/edit CODEOWNERS ([0251de7](https://github.com/schrodingers-stack/helm-argo-cd/commit/0251de74f4dc655ba78a9cefe6db2bb7f2df0022))
* add/edit CODEOWNERS ([702e276](https://github.com/schrodingers-stack/helm-argo-cd/commit/702e2761bedf18d5384ae1146fac99e08edfce9d))
* add/edit CODEOWNERS ([82d6f23](https://github.com/schrodingers-stack/helm-argo-cd/commit/82d6f234eb83ddb5f6e27808fcb4b81fc292debf))
* add/edit CODEOWNERS ([0f1cf91](https://github.com/schrodingers-stack/helm-argo-cd/commit/0f1cf91573674f008dfc9bdac3118b4437952db4))
* add/edit LICENSE.txt ([d4b52e7](https://github.com/schrodingers-stack/helm-argo-cd/commit/d4b52e773c39f5ce63d0c5905414ef150094ccf3))
* add/edit release-please-config.json ([f50d137](https://github.com/schrodingers-stack/helm-argo-cd/commit/f50d137a7dbe18d3ddf331e29a64b695f549a426))
* add/edit release-please-config.json ([21e61d9](https://github.com/schrodingers-stack/helm-argo-cd/commit/21e61d9591a16e7e7c80749ffb486c376c73e55f))
* add/edit release-please-config.json ([b792479](https://github.com/schrodingers-stack/helm-argo-cd/commit/b792479cbb53362c6677e5c730f9b11523d476d5))
* add/edit release-please-config.json ([40f3270](https://github.com/schrodingers-stack/helm-argo-cd/commit/40f3270b82d30a714bc3f4b02b24e3f9ce32e069))
* add/edit release-please-config.json ([5c6fcb6](https://github.com/schrodingers-stack/helm-argo-cd/commit/5c6fcb6efb10586b750cd3befe98c7647caa49d3))
* add/edit release-please-config.json ([3a80fb9](https://github.com/schrodingers-stack/helm-argo-cd/commit/3a80fb9553c6510d11fa98f6ffe1f11f4281b9a0))
* add/edit release-please-manifest.json ([e499872](https://github.com/schrodingers-stack/helm-argo-cd/commit/e499872cd8a448aa1ca68fa3f32a3b1f359156fb))
* delete old CODEOWNERS file ([d9aeddf](https://github.com/schrodingers-stack/helm-argo-cd/commit/d9aeddf02536b0ea3ddb59fc4e5186d9c73079e5))
* update Argo CD's upstream chart ([47868dc](https://github.com/schrodingers-stack/helm-argo-cd/commit/47868dc7c743134b1c928872b8cbdf50fee4058d))


### Continuous Integration

* add/edit commits-checks.yaml ([dd8b3ab](https://github.com/schrodingers-stack/helm-argo-cd/commit/dd8b3abe97de8edc3b61bf94b8899654540d6ed6))
* add/edit commits-checks.yaml ([37ccda4](https://github.com/schrodingers-stack/helm-argo-cd/commit/37ccda4d28d11e2764841e6b32db480b6097d0b9))
* add/edit pr-issues-project.yaml ([ef7822f](https://github.com/schrodingers-stack/helm-argo-cd/commit/ef7822ff4ea1030d49d7d5c52f8927cc171928d9))
* add/edit pr-issues-project.yml ([0f02be3](https://github.com/schrodingers-stack/helm-argo-cd/commit/0f02be3ee0e25a3ca00a9cd68f7c0c3ed384bbde))
* add/edit release-please.yaml ([3595210](https://github.com/schrodingers-stack/helm-argo-cd/commit/35952100b0a6bf17d1279b9fa63b8dd714a8794a))
