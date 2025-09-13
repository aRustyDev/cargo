# TODOs

- [ ] extend `cargo::util::context::GlobalContext::home()`
  - check for key `xdg`; then make `CARGO_BIN_DIR`, `CARGO_CONFIG_DIR`, `CARGO_CACHE_DIR`
- [ ] create `cargo::util::context::GlobalContext::is_xdg()`
  - check for `$CARGO_BIN_DIR`, `$CARGO_CONFIG_DIR`, `$CARGO_CACHE_DIR` vars
  - check for rust version
