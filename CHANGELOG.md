# CHANGELOG

> Package changelog.

<section class="release" id="v0.3.1">

## 0.3.1 (2026-02-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.3.0">

## 0.3.0 (2026-01-31)

<section class="features">

### Features

-   [`a2ed277`](https://github.com/stdlib-js/stdlib/commit/a2ed277054861fb48c64484446e8ff5f070a8505) - add C implementation for `stats/base/dists/f/stdev` [(#4351)](https://github.com/stdlib-js/stdlib/pull/4351)
-   [`9c225d9`](https://github.com/stdlib-js/stdlib/commit/9c225d9d649ffd725037384783d67f9dddee87a4) - add C implementation for `stats/base/dists/f/skewness` [(#4041)](https://github.com/stdlib-js/stdlib/pull/4041)
-   [`0cab817`](https://github.com/stdlib-js/stdlib/commit/0cab817744fa607bd863eadf32204b36e668d31c) - add C implementation for `stats/base/dists/f/variance` [(#4042)](https://github.com/stdlib-js/stdlib/pull/4042)
-   [`242b011`](https://github.com/stdlib-js/stdlib/commit/242b011a78ef3fce16befeca9e36629096e952c1) - add C implementation for `stats/base/dists/f/mode` [(#4036)](https://github.com/stdlib-js/stdlib/pull/4036)
-   [`df52159`](https://github.com/stdlib-js/stdlib/commit/df521591cd6b8d5bb9cfa241e241231d45319285) - add C implementation for `stats/base/dists/f/entropy` [(#4044)](https://github.com/stdlib-js/stdlib/pull/4044)
-   [`67eacfd`](https://github.com/stdlib-js/stdlib/commit/67eacfd73be1ac9ac96595eee7dabd21ccdc2ffb) - add C implementation for `stats/base/dists/f/kurtosis` [(#4043)](https://github.com/stdlib-js/stdlib/pull/4043)
-   [`b283652`](https://github.com/stdlib-js/stdlib/commit/b2836521feb83b741d0190d7600f297f0379851f) - add C implementation for `stats/base/dists/f/mean` [(#4033)](https://github.com/stdlib-js/stdlib/pull/4033)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`9256312`](https://github.com/stdlib-js/stdlib/commit/9256312621508d17a4bddb161991fd02c778c4e5) - remove unused `eps` dependency from `f/mean` manifest

</section>

<!-- /.bug-fixes -->

<section class="issues">

### Closed Issues

A total of 7 issues were closed in this release:

[#3595](https://github.com/stdlib-js/stdlib/issues/3595), [#3596](https://github.com/stdlib-js/stdlib/issues/3596), [#3597](https://github.com/stdlib-js/stdlib/issues/3597), [#3598](https://github.com/stdlib-js/stdlib/issues/3598), [#3601](https://github.com/stdlib-js/stdlib/issues/3601), [#3602](https://github.com/stdlib-js/stdlib/issues/3602), [#3603](https://github.com/stdlib-js/stdlib/issues/3603)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`993324c`](https://github.com/stdlib-js/stdlib/commit/993324c928a43c5cd49768b6cd2e6666c71340f9) - **docs:** replace manual `for` loop in examples [(#7888)](https://github.com/stdlib-js/stdlib/pull/7888) _(by Harsh Yadav)_
-   [`b8343ec`](https://github.com/stdlib-js/stdlib/commit/b8343ec7ccbe3524a933c2ac0e479864fc8169ba) - **docs:** replace manual `for` loop in examples [(#7889)](https://github.com/stdlib-js/stdlib/pull/7889) _(by Harsh Yadav)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`fc438e0`](https://github.com/stdlib-js/stdlib/commit/fc438e0edbad0689d6923d6f3edb959b96597662) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`11581aa`](https://github.com/stdlib-js/stdlib/commit/11581aaca8c3cb824cbb92c0c0f80e76890bdb20) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`07f7c05`](https://github.com/stdlib-js/stdlib/commit/07f7c0522c73e6ad9505e1d45035ae439344200d) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`9c21fd2`](https://github.com/stdlib-js/stdlib/commit/9c21fd20ef8b8a6a88abb96d80ea6d8e4c5434eb) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`7e24b8b`](https://github.com/stdlib-js/stdlib/commit/7e24b8ba0fff87a56584bb1a2fa106eb88267596) - **test:** slightly increase tolerances for passing tests _(by Philipp Burckhardt)_
-   [`c698e73`](https://github.com/stdlib-js/stdlib/commit/c698e73a6365ec5d828861bb26a6e3bb74fb1af8) - **chore:** add missing eps dependency to benchmark and examples configs _(by Philipp Burckhardt)_
-   [`5d83a20`](https://github.com/stdlib-js/stdlib/commit/5d83a20bab1fd787ba28f19cb13c20d395398b43) - **style:** remove double empty lines in C files _(by Philipp Burckhardt)_
-   [`9256312`](https://github.com/stdlib-js/stdlib/commit/9256312621508d17a4bddb161991fd02c778c4e5) - **fix:** remove unused `eps` dependency from `f/mean` manifest _(by Philipp Burckhardt)_
-   [`0def122`](https://github.com/stdlib-js/stdlib/commit/0def122ace01882b5b7344ac90754ea5f4375ac7) - **docs:** minor clean-up _(by Philipp Burckhardt)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`f7988d3`](https://github.com/stdlib-js/stdlib/commit/f7988d3c02e0eff3bd9bd7523b5dc975bb98dc0e) - **bench:** fix `isnan` checks in `stats/base/dists` [(#5296)](https://github.com/stdlib-js/stdlib/pull/5296) _(by Karan Anand)_
-   [`911e179`](https://github.com/stdlib-js/stdlib/commit/911e1793885aced96a177f2ea54300503b2c2a26) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`e61b1de`](https://github.com/stdlib-js/stdlib/commit/e61b1dee3334bacf30d213de5b5f1c7868c0753b) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`6335415`](https://github.com/stdlib-js/stdlib/commit/633541558ed3c1707e9aaa7874ab76043ff329af) - **bench:** refactor random number generation in `stats/base/dists/f` [(#4921)](https://github.com/stdlib-js/stdlib/pull/4921) _(by Karan Anand, stdlib-bot)_
-   [`f75a0ce`](https://github.com/stdlib-js/stdlib/commit/f75a0cef6a3112b166dba04c13bada9763cec350) - **chore:** use excess kurtosis consistently _(by Philipp Burckhardt)_
-   [`f3df15f`](https://github.com/stdlib-js/stdlib/commit/f3df15f118d563573f27d2d2b96e35b842f05a18) - **chore:** directly draw from the desired distribution instead of adding constants _(by Philipp Burckhardt)_
-   [`fc0ff17`](https://github.com/stdlib-js/stdlib/commit/fc0ff171dab59e73e1748c1bff504166adc826c3) - **chore:** directly draw from the desired distribution instead of adding constants _(by Philipp Burckhardt)_
-   [`a2ed277`](https://github.com/stdlib-js/stdlib/commit/a2ed277054861fb48c64484446e8ff5f070a8505) - **feat:** add C implementation for `stats/base/dists/f/stdev` [(#4351)](https://github.com/stdlib-js/stdlib/pull/4351) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`4a70790`](https://github.com/stdlib-js/stdlib/commit/4a707903dfef7c2b56216000165706497d19a251) - **style:** add missing spaces _(by Philipp Burckhardt)_
-   [`ed5c4cc`](https://github.com/stdlib-js/stdlib/commit/ed5c4cccc06ad98f4de90310bf24a5a373761b43) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`b7867cb`](https://github.com/stdlib-js/stdlib/commit/b7867cbb3a4fc453e19203794402c36f19b264fd) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`0ba282b`](https://github.com/stdlib-js/stdlib/commit/0ba282b89c384f06bbe3ff8ecd71982f05209606) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`9f71ae0`](https://github.com/stdlib-js/stdlib/commit/9f71ae0ab3105190b6638768b83756e69d9146ea) - **chore:** address feedback and enable tests _(by Philipp Burckhardt)_
-   [`318f280`](https://github.com/stdlib-js/stdlib/commit/318f28057bf00d910a656c4f315b8de17f89d3b5) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`9c225d9`](https://github.com/stdlib-js/stdlib/commit/9c225d9d649ffd725037384783d67f9dddee87a4) - **feat:** add C implementation for `stats/base/dists/f/skewness` [(#4041)](https://github.com/stdlib-js/stdlib/pull/4041) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`0cab817`](https://github.com/stdlib-js/stdlib/commit/0cab817744fa607bd863eadf32204b36e668d31c) - **feat:** add C implementation for `stats/base/dists/f/variance` [(#4042)](https://github.com/stdlib-js/stdlib/pull/4042) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`242b011`](https://github.com/stdlib-js/stdlib/commit/242b011a78ef3fce16befeca9e36629096e952c1) - **feat:** add C implementation for `stats/base/dists/f/mode` [(#4036)](https://github.com/stdlib-js/stdlib/pull/4036) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`df52159`](https://github.com/stdlib-js/stdlib/commit/df521591cd6b8d5bb9cfa241e241231d45319285) - **feat:** add C implementation for `stats/base/dists/f/entropy` [(#4044)](https://github.com/stdlib-js/stdlib/pull/4044) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`67eacfd`](https://github.com/stdlib-js/stdlib/commit/67eacfd73be1ac9ac96595eee7dabd21ccdc2ffb) - **feat:** add C implementation for `stats/base/dists/f/kurtosis` [(#4043)](https://github.com/stdlib-js/stdlib/pull/4043) _(by Vivek Maurya, Philipp Burckhardt)_
-   [`b283652`](https://github.com/stdlib-js/stdlib/commit/b2836521feb83b741d0190d7600f297f0379851f) - **feat:** add C implementation for `stats/base/dists/f/mean` [(#4033)](https://github.com/stdlib-js/stdlib/pull/4033) _(by Vivek Maurya)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 4 people contributed to this release. Thank you to the following contributors:

-   Harsh Yadav
-   Karan Anand
-   Philipp Burckhardt
-   Vivek Maurya

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-29)

<section class="commits">

### Commits

<details>

-   [`41d41e9`](https://github.com/stdlib-js/stdlib/commit/41d41e959b4eaad3c631e6898e3144a4015a5458) - **test:** include trailing newlines in Julia-generated JSON fixtures _(by Philipp Burckhardt)_
-   [`9ed7d0e`](https://github.com/stdlib-js/stdlib/commit/9ed7d0e7d57edb5ad0dfb65c944bed87d475cbf3) - **chore:** add missing trailing newlines _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="commits">

### Commits

<details>

-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="features">

### Features

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`d5fa8e8`](https://github.com/stdlib-js/stdlib/commit/d5fa8e8a6267a837a25a7027e9fe3e847bc2d1c5) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`ce7e336`](https://github.com/stdlib-js/stdlib/commit/ce7e3367c0f9477773fe76dd0eca64dc6ad33c02) - **docs:** update equations _(by Philipp Burckhardt)_
-   [`37f032d`](https://github.com/stdlib-js/stdlib/commit/37f032d4a571f667ea99f6f52f60b5d736c627f3) - **docs:** render equations via math code blocks _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-07-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-28)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

