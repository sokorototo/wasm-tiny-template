# A simple template for writing quick `WebAssembly` binaries in Rust

Simply edit `src/libs.rs`, then run `./build.sh`. The output file: `out/output.wasm`, is the resulting `WebAssembly`.

It only requires that you give it an `exit` function: **`fn exit(error_type: u8) -> !`**.

To run `./build.sh` without errors, ensure you have `wabt`  and `wasm-opt`installed
