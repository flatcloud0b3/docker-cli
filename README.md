[![build status](https://circleci.com/gh/docker/cli.svg?style=shield)](https://circleci.com/gh/docker/cli/tree/master)
[![Build Status](https://ci.docker.com/public/job/cli/job/master/badge/icon)](https://ci.docker.com/public/job/cli/job/master)

docker-cli
==========

This repository is a fork of the cli used in the Docker CE and
Docker EE products.

Development
===========

`docker-cli` is developed using Docker.

Build a linux binary:

```
$ make -f docker.Makefile binary
```

Build binaries for all supported platforms:

```
$ make -f docker.Makefile cross
```

Run all linting:

```
$ make -f docker.Makefile lint
```

List all the available targets:

```
$ make help
```

### In-container development environment

Start an interactive development environment:

```
$ make -f docker.Makefile shell
```

In the development environment you can run many tasks, including build binaries:

```
$ make binary
```
