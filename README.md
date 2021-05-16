# test-build-action

Repository used to test github action https://github.com/mesopelagique/build-action

## main branch

[![build](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml/badge.svg)](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml?query=branch%3Amain)

## branch with compilation failure

[![build](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml/badge.svg?branch=feature%2Ffailure)](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml?query=branch%3Afeature%2Ffailure)

and a [pull request open](https://github.com/mesopelagique/test-build-action/pull/1/files) where we could see real compilation errors

## branch with compilation failure by enforcing variable typing

[![build](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml/badge.svg?branch=test%2Fcompilation-options)](https://github.com/mesopelagique/test-build-action/actions/workflows/build.yml?query=test%2Fcompilation-options)

and a [pull request open](https://github.com/mesopelagique/test-build-action/pull/3/files) where we could see errors and code modification to enforce variable typing
