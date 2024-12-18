# Changelog

## [1.2.0](https://github.com/nils1k/release-please-test/compare/v1.1.0...v1.2.0) (2024-12-18)


### Features

* Add checkout action to release workflow ([02c4ec0](https://github.com/nils1k/release-please-test/commit/02c4ec0e726d8b116351b90fd1e794c1bae2387a))
* Add continue-on-error to printing of output variables ([64dbecf](https://github.com/nils1k/release-please-test/commit/64dbecf254f886867f394bc2ae34120ca38fce69))
* Add echo of output from jq manipulation ([0638802](https://github.com/nils1k/release-please-test/commit/0638802303dc3d743ea78f0e30897c444224f06b))
* Add extraction of pr number using grep instead of jq ([5d8b935](https://github.com/nils1k/release-please-test/commit/5d8b935de8956b8ec97b4f17aa37bd8a06d434ba))
* Add extraction of version number from pull request title in release workflow ([224d267](https://github.com/nils1k/release-please-test/commit/224d267f074943cf96d386f326d8714461960341))
* Add generation of release notes ([1fcfa92](https://github.com/nils1k/release-please-test/commit/1fcfa92a059efe2f2bdc27499ba1e3470b5f6960))
* Add output variable from release-pr step in release workflow ([f107bfc](https://github.com/nils1k/release-please-test/commit/f107bfc6d162de3994d7723fab0c687ae874577a))
* Add printing of all release output variables ([e5c2900](https://github.com/nils1k/release-please-test/commit/e5c2900a01734c5f5cedfbbca141fec5cb9c36f6))
* Add printing of pull request payload ([b69f4a1](https://github.com/nils1k/release-please-test/commit/b69f4a16caca5fc47d95d23bfc97bc24dc651683))
* Add programmatic merging of the release PR ([7535dbc](https://github.com/nils1k/release-please-test/commit/7535dbcd7ebf5e02d61c87e452a63356bd2d8b37))
* Add reading from variable instead of file to jq ([41a92b1](https://github.com/nils1k/release-please-test/commit/41a92b150bf6deae9f3a02470b0cc53e1e16a427))
* Add storing the release PR id in an environment variable for later use in jq step ([8dfc825](https://github.com/nils1k/release-please-test/commit/8dfc825873cf74c1b2debed3fed14d731ce72255))
* Add toJSON for proper printing ([3ee7f54](https://github.com/nils1k/release-please-test/commit/3ee7f54fee3a5578f3e124f67f8bef4940beaec5))


### Bug Fixes

* Add missing GH_TOKEN environment variable to the get release PR number step in the release workflow ([b457122](https://github.com/nils1k/release-please-test/commit/b4571221e7c1b38938e18f056ca4f6366cb32f62))
* Add missing GH_TOKEN environment variable to the merge release PR step in the release workflow ([f6449a7](https://github.com/nils1k/release-please-test/commit/f6449a75dcc2e75877a65efaf8d1d0ae8644a1ce))
* Add missing permissions to creation pull requests for release-please action ([a4b3e79](https://github.com/nils1k/release-please-test/commit/a4b3e79f6c98aa2d726659a16e69e5c19e435008))
* Modify Print calculated version in release workflow to reference correct output variable ([cd4e8cd](https://github.com/nils1k/release-please-test/commit/cd4e8cd91efc31b18e1dadc1e3a360478eb7669c))
* Modify token reference to use correct secret in release workflow ([3c914c9](https://github.com/nils1k/release-please-test/commit/3c914c909b714610126c6ff0fbff459b7bbb2d9e))
* Replace deprecated ::set-output syntax with  and squash release pr instead of merge ([08f221b](https://github.com/nils1k/release-please-test/commit/08f221b5c18f593c614f48f26cc02ab86ef43f8a))

## [1.1.0](https://github.com/nils1k/release-please-test/compare/v1.0.0...v1.1.0) (2024-12-18)


### Features

* Add checkout action to release workflow ([02c4ec0](https://github.com/nils1k/release-please-test/commit/02c4ec0e726d8b116351b90fd1e794c1bae2387a))
* Add continue-on-error to printing of output variables ([64dbecf](https://github.com/nils1k/release-please-test/commit/64dbecf254f886867f394bc2ae34120ca38fce69))
* Add echo of output from jq manipulation ([0638802](https://github.com/nils1k/release-please-test/commit/0638802303dc3d743ea78f0e30897c444224f06b))
* Add extraction of pr number using grep instead of jq ([5d8b935](https://github.com/nils1k/release-please-test/commit/5d8b935de8956b8ec97b4f17aa37bd8a06d434ba))
* Add extraction of version number from pull request title in release workflow ([224d267](https://github.com/nils1k/release-please-test/commit/224d267f074943cf96d386f326d8714461960341))
* Add output variable from release-pr step in release workflow ([f107bfc](https://github.com/nils1k/release-please-test/commit/f107bfc6d162de3994d7723fab0c687ae874577a))
* Add printing of all release output variables ([e5c2900](https://github.com/nils1k/release-please-test/commit/e5c2900a01734c5f5cedfbbca141fec5cb9c36f6))
* Add printing of pull request payload ([b69f4a1](https://github.com/nils1k/release-please-test/commit/b69f4a16caca5fc47d95d23bfc97bc24dc651683))
* Add programmatic merging of the release PR ([7535dbc](https://github.com/nils1k/release-please-test/commit/7535dbcd7ebf5e02d61c87e452a63356bd2d8b37))
* Add reading from variable instead of file to jq ([41a92b1](https://github.com/nils1k/release-please-test/commit/41a92b150bf6deae9f3a02470b0cc53e1e16a427))
* Add storing the release PR id in an environment variable for later use in jq step ([8dfc825](https://github.com/nils1k/release-please-test/commit/8dfc825873cf74c1b2debed3fed14d731ce72255))
* Add toJSON for proper printing ([3ee7f54](https://github.com/nils1k/release-please-test/commit/3ee7f54fee3a5578f3e124f67f8bef4940beaec5))


### Bug Fixes

* Add missing GH_TOKEN environment variable to the get release PR number step in the release workflow ([b457122](https://github.com/nils1k/release-please-test/commit/b4571221e7c1b38938e18f056ca4f6366cb32f62))
* Add missing GH_TOKEN environment variable to the merge release PR step in the release workflow ([f6449a7](https://github.com/nils1k/release-please-test/commit/f6449a75dcc2e75877a65efaf8d1d0ae8644a1ce))

## 1.0.0 (2024-12-17)


### Features

* Add generation of release notes ([1fcfa92](https://github.com/nils1k/release-please-test/commit/1fcfa92a059efe2f2bdc27499ba1e3470b5f6960))


### Bug Fixes

* Add missing permissions to creation pull requests for release-please action ([a4b3e79](https://github.com/nils1k/release-please-test/commit/a4b3e79f6c98aa2d726659a16e69e5c19e435008))
* Modify Print calculated version in release workflow to reference correct output variable ([cd4e8cd](https://github.com/nils1k/release-please-test/commit/cd4e8cd91efc31b18e1dadc1e3a360478eb7669c))
* Modify token reference to use correct secret in release workflow ([3c914c9](https://github.com/nils1k/release-please-test/commit/3c914c909b714610126c6ff0fbff459b7bbb2d9e))
