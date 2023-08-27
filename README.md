# Example usage of Typescript with Rust

## dependencies

Rust & wasm-pack should be installed and available in your PATH

- rust can be installed via `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`
- wasm-pack can be installed with `npm i -G wasm-pack`
- both will be installed at `~/.cargo/bin`

## how to run example

```shell
# compile web assembly
cd rust;
wasm-pack build --target nodejs;

# install packages
cd ../javascript;
pnpm install;

# build and run example
pnpm build;
pnpm start;
```
