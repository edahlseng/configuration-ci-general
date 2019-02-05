# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.13.2"></a>
## [1.13.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.1...v1.13.2) (2019-02-05)


### Bug Fixes

* Auto approve the terraform destroy step for cleanup-pr-deployments ([1e9c1fb](https://github.com/edahlseng/configuration-ci-general/commit/1e9c1fb))



<a name="1.13.1"></a>
## [1.13.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.0...v1.13.1) (2019-02-05)


### Bug Fixes

* Use correct get-workspace command within cleanup-pr-deployments ([ad2068c](https://github.com/edahlseng/configuration-ci-general/commit/ad2068c))



<a name="1.13.0"></a>
# [1.13.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.12.0...v1.13.0) (2019-01-25)


### Features

* Add cleanup-pr-deployments job ([b16ed12](https://github.com/edahlseng/configuration-ci-general/commit/b16ed12))
* Add halt-if-not-pr command ([0e058ce](https://github.com/edahlseng/configuration-ci-general/commit/0e058ce))
* Add post-pr-comment command ([9169b2f](https://github.com/edahlseng/configuration-ci-general/commit/9169b2f))
* Add select-or-create-workspace command ([a6f49cb](https://github.com/edahlseng/configuration-ci-general/commit/a6f49cb))
* Add workspace parameter to terraform-plan and terraform-apply jobs ([d641cbe](https://github.com/edahlseng/configuration-ci-general/commit/d641cbe))



<a name="1.12.0"></a>
# [1.12.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.11.0...v1.12.0) (2019-01-23)


### Features

* Add add-github-to-known-hosts command ([aaa7024](https://github.com/edahlseng/configuration-ci-general/commit/aaa7024))



<a name="1.11.0"></a>
# [1.11.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.10.0...v1.11.0) (2019-01-18)


### Features

* Add run-validate-after-init parameter to validate-terraform job ([41bd762](https://github.com/edahlseng/configuration-ci-general/commit/41bd762))



<a name="1.10.0"></a>
# [1.10.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.9.0...v1.10.0) (2019-01-17)


### Bug Fixes

* Move setup_remote_docker before setup-steps for build-image job ([fcfefaf](https://github.com/edahlseng/configuration-ci-general/commit/fcfefaf))


### Features

* Add `configure-aws-profile` command ([f2e2bed](https://github.com/edahlseng/configuration-ci-general/commit/f2e2bed))
* Add `login-ecr` command ([9aacc1f](https://github.com/edahlseng/configuration-ci-general/commit/9aacc1f))
* Add build-options parameter to build-image job ([f9a8575](https://github.com/edahlseng/configuration-ci-general/commit/f9a8575))



<a name="1.9.0"></a>
# [1.9.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.8.1...v1.9.0) (2019-01-16)


### Features

* Add build-image job ([c5024dd](https://github.com/edahlseng/configuration-ci-general/commit/c5024dd))



<a name="1.8.1"></a>
## [1.8.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.8.0...v1.8.1) (2019-01-09)


### Bug Fixes

* Add default for artifact-paths parameter ([cbf7c0a](https://github.com/edahlseng/configuration-ci-general/commit/cbf7c0a))



<a name="1.8.0"></a>
# [1.8.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.2...v1.8.0) (2019-01-09)


### Bug Fixes

* Remove redundant word from GitHub Release name ([791b7a9](https://github.com/edahlseng/configuration-ci-general/commit/791b7a9))


### Features

* Add lint-css job ([9b0328d](https://github.com/edahlseng/configuration-ci-general/commit/9b0328d))
* Add validate-js job ([a84d970](https://github.com/edahlseng/configuration-ci-general/commit/a84d970))



<a name="1.7.2"></a>
## [1.7.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.1...v1.7.2) (2019-01-08)


### Bug Fixes

* Add additional logging ([576f751](https://github.com/edahlseng/configuration-ci-general/commit/576f751))
* Improve array expansion for iterating over artifact paths ([bd05ee6](https://github.com/edahlseng/configuration-ci-general/commit/bd05ee6))



<a name="1.7.1"></a>
## [1.7.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.0...v1.7.1) (2019-01-07)


### Bug Fixes

* Put .git directory after creating tag ([f88138b](https://github.com/edahlseng/configuration-ci-general/commit/f88138b))



<a name="1.7.0"></a>
# [1.7.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.6.1...v1.7.0) (2019-01-07)


### Features

* Add create-github-release job ([8b2f9ba](https://github.com/edahlseng/configuration-ci-general/commit/8b2f9ba))



<a name="1.6.1"></a>
## [1.6.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.6.0...v1.6.1) (2018-12-12)


### Bug Fixes

* Add option for terraform-apply to ignore a missing plan ([3fd2c23](https://github.com/edahlseng/configuration-ci-general/commit/3fd2c23))
* Add setup-steps to validate-terraform job ([ea43d7f](https://github.com/edahlseng/configuration-ci-general/commit/ea43d7f))
* Set Terraform executor to use a CircleCI-compatible Docker image ([84e4680](https://github.com/edahlseng/configuration-ci-general/commit/84e4680))
* Set user on Node Docker executor ([9f51b61](https://github.com/edahlseng/configuration-ci-general/commit/9f51b61))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.5.0...v1.6.0) (2018-12-07)


### Features

* Add setup-steps parameter to install-dependencies-npm job ([b4ca5ab](https://github.com/edahlseng/configuration-ci-general/commit/b4ca5ab))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.4.0...v1.5.0) (2018-12-04)


### Features

* Add Terraform-related jobs and executor ([bd4d790](https://github.com/edahlseng/configuration-ci-general/commit/bd4d790))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.2...v1.4.0) (2018-11-19)


### Features

* Add tag job ([65e1c35](https://github.com/edahlseng/configuration-ci-general/commit/65e1c35))
* Add test job ([6c45cd1](https://github.com/edahlseng/configuration-ci-general/commit/6c45cd1))



<a name="1.3.2"></a>
## [1.3.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.1...v1.3.2) (2018-11-18)


### Bug Fixes

* Use correct URL for checking for an existing release pull request ([b662ab6](https://github.com/edahlseng/configuration-ci-general/commit/b662ab6))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.0...v1.3.1) (2018-11-18)


### Bug Fixes

* Use proper path for validating orbs ([91e1610](https://github.com/edahlseng/configuration-ci-general/commit/91e1610))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.2.0...v1.3.0) (2018-11-18)


### Bug Fixes

* Add version number tag to release pull request ([5574dc2](https://github.com/edahlseng/configuration-ci-general/commit/5574dc2))


### Features

* Add lint-circleci-orb job ([973927d](https://github.com/edahlseng/configuration-ci-general/commit/973927d))
* Add publish-circleci-dev job ([24d9774](https://github.com/edahlseng/configuration-ci-general/commit/24d9774))
* Add tag-and-publish-circleci job ([0448b35](https://github.com/edahlseng/configuration-ci-general/commit/0448b35))
* Parameterize Git user and credentials ([1e1ddc4](https://github.com/edahlseng/configuration-ci-general/commit/1e1ddc4))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.2...v1.2.0) (2018-11-18)


### Bug Fixes

* Add names to steps ([cf90df8](https://github.com/edahlseng/configuration-ci-general/commit/cf90df8))


### Features

* Rename get command to get-workspace ([0edb986](https://github.com/edahlseng/configuration-ci-general/commit/0edb986))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.1...v1.1.2) (2018-11-18)


### Bug Fixes

* Add description to tag command ([91e7e6a](https://github.com/edahlseng/configuration-ci-general/commit/91e7e6a))
* Rename ssh-fingerprint parameters to git-ssh-fingerprint ([02b2b92](https://github.com/edahlseng/configuration-ci-general/commit/02b2b92))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.0...v1.1.1) (2018-11-18)


### Bug Fixes

* Remove quotes for regex comparison ([2fb9297](https://github.com/edahlseng/configuration-ci-general/commit/2fb9297))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.2...v1.1.0) (2018-11-18)


### Features

* Add create-release-pr job ([e696099](https://github.com/edahlseng/configuration-ci-general/commit/e696099))
* Add tag-and-publish-npm job ([cf41ff5](https://github.com/edahlseng/configuration-ci-general/commit/cf41ff5))



<a name="1.0.2"></a>
# [1.0.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.1...v1.0.2) (2018-11-17)


### Bug Fixes

* Update commit message checking to working regex ([b9b101f](https://github.com/edahlseng/configuration-ci-general/commit/b9b101f))



<a name="1.0.1"></a>
# [1.0.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.0...v1.0.1) (2018-11-17)


### Bug Fixes

* Add more logging ([8e9cb51](https://github.com/edahlseng/configuration-ci-general/commit/8e9cb51))



<a name="1.0.0"></a>
# 1.0.0 (2018-11-17)


### Features

* Add general orb ([81fb280](https://github.com/edahlseng/configuration-ci-general/commit/81fb280))
