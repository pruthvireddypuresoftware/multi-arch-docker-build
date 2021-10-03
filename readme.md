# Docker on CI

- Circle CI - [![CircleCI](https://circleci.com/gh/ozbillwang/multi-arch-docker-build.svg?style=svg)](https://circleci.com/gh/ozbillwang/multi-arch-docker-build)

- Travis CI - [![Build Status](https://app.travis-ci.com/ozbillwang/multi-arch-docker-build.svg?branch=master)](https://app.travis-ci.com/ozbillwang/multi-arch-docker-build)

### Ref with fixes

https://www.docker.com/blog/multi-arch-build-what-about-travis/

https://www.docker.com/blog/multi-arch-build-what-about-circleci/

Due to these free online pipelines keep changing with docker itself keep enhancing, **these builds are triggered weekly** to confirm the stabilities. 

### Notes

There are other two supported CICD in original upstream repo, but I would not work on them currently

- Gitlab CI - it can't nicely handle secrets with special charactors (https://gitlab.com/gitlab-org/gitlab/-/issues/196871). So it is no-go for me.

- Github Action - in current last commit, the author delete the support of github action, there must be a reason, which I need find it out first ( https://github.com/jdrouet/docker-on-ci/issues/7 )
