# Gitlab CI Caching  [![pipeline status](https://gitlab.com/egee-irl/ci-caching/badges/main/pipeline.svg)](https://gitlab.com/egee-irl/ci-caching/-/commits/main)
 
A simple project of projects to demonstrate basic CI caching for quicker builds in continuous integration environments.

This repository uses Gitlab CI as the [target example](https://github.com/egee-irl/ci-caching/blob/main/.gitlab-ci.yml) but all continuous integration services provide caching as a basic feature and are implemented in roughly the same way.

## How to use this repository

This example repository isn't meant to be a complete or comprehensive example of CI caching but rather as a place to start for those that have never seen or used caching before.

The only important thing in this repository is the [.gitlab-ci.yml](https://github.com/egee-irl/ci-caching/blob/main/.gitlab-ci.yml) file. Open it up, examine it, and copy the bits that are useful to you or your projects.

## References

Here are some references for some CI platforms I've used and recommend:

- [Travis CI](https://docs.travis-ci.com/user/caching/): Easy to get started, integrates with practically every git hosting platform.
- [Gitlab CI](https://docs.gitlab.com/ee/ci/caching/): 100% Free & Open Source and uses markup similar to Travis.
- [Circle CI](https://circleci.com/docs/2.0/caching/): Similar to Travis CI but much more container-focused.
- [Github Actions](https://github.com/actions/cache): Good for simple projects already hosted on Github.

Gitlab also has some great documentation regarding best practices when using caches and artifacts in CI - https://docs.gitlab.com/ee/ci/caching
