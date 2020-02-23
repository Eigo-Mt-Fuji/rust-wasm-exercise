* Install

```
asdf global rust 1.37.0
```


```
rustup target add wasm32-unknown-unknown
```

* Install wasm-objdump

   - [command not found?](https://command-not-found.com/wasm-objdump)

```bash
EigonoMacBook-Pro:rust-wasm-exercise fujikawa$ wasm-objdump -h ./example1.wasm
-bash: wasm-objdump: command not found
EigonoMacBook-Pro:rust-wasm-exercise fujikawa$ brew install wabt
Updating Homebrew...
```
