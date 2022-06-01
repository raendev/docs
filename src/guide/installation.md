# Installation

## Rust

`raen` is a Rust crate and can be installed via `cargo`:

```bash
cargo install raen
```

## npm (optionally)

`raen` is also distributed on npm which wraps the rust binary built for your computer:

```bash
npm install --global raen-cli
```

## Additional requirements

`raen` is an extension for [`near-cli-rs`](https://github.com/near/near-cli-rs/tree/master/extensions), but until this project is stable now you need to install the JS version `near-cli` to deploy your contracts.

```bash
npm install --global near-cli
```
