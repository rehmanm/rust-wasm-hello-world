# rust-wasm-hello-world

## Dependencies
[Install wasm pack](https://rustwasm.github.io/wasm-pack/installer/)

## Code generation
```shell
cargo new --lib [project-name]
```

## Changes in toml file
```
[lib]
crate-type = ["cdylib"]

[dependencies]
wasm-bindgen = "0.2"
```

## Build
```shell
wasm-pack build --target web
```

## Running Server
```shell
python3 -m http.server
```
