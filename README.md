# Swanky2.0-Sample

## デプロイ済みのコントラクト

| No. | コントラクト名      | Contract UI     | ネットワーク |
| --- | ----------------------------------------------- | ---------------------------- | ------------ |
| 1   | Content | [YxeQPrU75g7Vv9biMw27jFqjfLU5ansb5ryqvgG7QN2W8VG](https://contracts-ui.substrate.io/contract/YxeQPrU75g7Vv9biMw27jFqjfLU5ansb5ryqvgG7QN2W8VG) | Shibuya      |

## 動いた環境

- swanky

```bash
@astar-network/swanky-cli/2.1.2 darwin-x64 node-v18.12.1
```

- rustc 

```bash
rustc 1.69.0 (84c898d65 2023-04-16)
```

- rustup show 

```bash
Default host: x86_64-apple-darwin
rustup home:  /Users/harukikondo/.rustup

installed toolchains
--------------------

stable-x86_64-apple-darwin (default)
nightly-x86_64-apple-darwin

active toolchain
----------------

stable-x86_64-apple-darwin (default)
rustc 1.69.0 (84c898d65 2023-04-16)
```

- cargo contract 

```bash
cargo-contract-contract 2.2.1-unknown-x86_64-apple-darwin
```

### 動かし方

- flipperのコンパイル

```bash
yarn compile:flipper
```

- contentのコンパイル

```bash
yarn compile:content
```