# Minimal working example for PNPM [#3561](https://github.com/pnpm/pnpm/issues/3561)

## Steps to reproduce

`$ cd packages/package-b/test && pnpm install`

## Expected behavior

PNPM installs package `rollup` to `packages/package-b/test`.

## Current behavior

PNPM installs the dependencies of the two monorepo, but not of `packages/package-b/test`.