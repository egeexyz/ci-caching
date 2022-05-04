# Gitlab CI Caching  [![pipeline status](https://gitlab.com/egee-irl/ci-caching/badges/main/pipeline.svg)](https://gitlab.com/egee-irl/ci-caching/-/commits/main)
 
A simple project of projects to demonstrate how to use caching for quicker builds in continuous integration environments.

This repository uses Gitlab CI as the [target example](https://github.com/egee-irl/ci-caching/blob/main/.gitlab-ci.yml) but all continuous integration services provide caching as a basic feature and are implemented in roughly the same way.


## How to use this repository

The only important thing in this repository is the [.gitlab-ci.yml](https://github.com/egee-irl/ci-caching/blob/main/.gitlab-ci.yml) file. Open it up, examine it, and reverse engineer the bits that are pertinent to your projects. The Ember, Jekyll, and Nikola projects used in the examples are simply quick-start or bootstrap versions of projects that I've worked with before.

## References

Here are some references for some CI platforms I've used and recommend:

- [Travis CI](https://docs.travis-ci.com/user/caching/): Easy to get started, integrates with practically every git hosting platform.
- [Gitlab CI](https://docs.gitlab.com/ee/ci/caching/): 100% Free & Open Sourceand uses markup is similar to Travis.
- [Circle CI](https://circleci.com/docs/2.0/caching/): Similar to Travis CI but much more container-focused.
- [Github Actions](https://github.com/actions/cache): Good for simple projects already hosted on Github.
