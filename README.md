# `keepass`
Unofficial & unaffiliated keepass-rs FFI wrapper.
<!--
## Getting started
```sh
cargo install keepass
keepass
keepass -h
```

or use the library as in:
```rust
cargo add keepass
```
-->

## Development
- Install `cbindgen`: `cargo install --force cbindgen`.
- To generate `pgp-ffi.h` C bindings for Rust, use `cbindgen` in the
  `pgp-ffi` directory:
  ```
  cbindgen --config cbindgen.toml --crate keepass-ffi --output pgp-ffi.h
  ```
