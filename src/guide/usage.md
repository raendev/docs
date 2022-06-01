# Basic usage

## Build Rust

In a NEAR smart contract project:

```bash
raen build --release
```

This builds the contract (or contracts if workspace), embeds the contract's types in a custom section,
and places them in `./target/res/crate_name.wasm`.
