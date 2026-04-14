# nest-smaller-docker

![Build](https://github.com/alpercitak/nest-smaller-docker/actions/workflows/build.yaml/badge.svg) 
![Lint](https://github.com/alpercitak/nest-smaller-docker/actions/workflows/lint.yaml/badge.svg) 
![Test](https://github.com/alpercitak/nest-smaller-docker/actions/workflows/test.yaml/badge.svg) 
![License](https://img.shields.io/github/license/alpercitak/nest-smaller-docker)

Optimized multi-stage Docker configuration for NestJS using pnpm to minimize container image size.

Companion repository for the Medium article [Nest.js — Reducing Docker container size](https://medium.com/@alpercitak/nest-js-reducing-docker-container-size-4c2672369d30)

## Installation

```bash
$ pnpm install
```

## Running the app

```bash
# watch mode
$ pnpm start:dev

# build
$ pnpm build
```

## Test

```bash
# unit tests
$ pnpm test

# watch
$ pnpm test:watch
```
