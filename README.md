# Skeleton: Deno

This is a starter project for Deno projects.

## Installation

```bash
# Clone repository
git clone git@github.com:Industrial/skeleton-deno.git my-project
# Change directory
cd my-project
# Remove git directory
rm -rf .git
# Install husky and lint-staged from npm. Initializes new .git/ directory.
deno task prepare
```

### NixOS

For [NixOS](https://nixos.org/), deno can be installed on a project basis by
using the `.envrc` and `flake.nix` file. Run this command to automatically use
the [Nix Flake](https://nixos.wiki/wiki/Flakes) when entering the directory.

## Usage

### Lint

```bash
deno task lint
deno task lint:watch
```

### Test

```bash
deno task test
deno task test:watch
deno task test:coverage
```
