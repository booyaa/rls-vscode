### 0.2.2 - 2017-08-21

* Highlights errors from build tasks
* Find all impls
* Adds cargo clean task
* Auto-detect `--lib` or `--bin`
* Adds an opt-out option for creating tasks.json
* Add a command to update the RLS and an option to do so on startup
* Deprecate `RLS_PATH` and `RLS_ROOT` env vars
* Changes to the RLS:
  - Easier to use deglob refactoring
  - Debugging and troubleshooting [instructions](https://github.com/rust-lang-nursery/rls/blob/master/debugging.md)

### 0.2.1 - 2017-08-09

* Fix bug installing the rls

### 0.2.0 - 2017-08-07

* Unicode (fixed width) spinner
* Logging and debugging options in configuration
* Deglob command is in the Rust category
* Don't check tests by default (still configurable)
* Set `RUST_SRC_PATH` for Racer
* Travis CI for the repo
* Performance and robustness improvements in the RLS, support for required options
  here, including
  - blacklist large and non-very useful crates (configurable)
  - configure compiler data
  - don't error on missing options
  - stabilise renaming
  - don't crash on non-file URLs
  - Racer and Rustfmt updates
  - only use Racer for code completion (never for 'goto def', still configurable)
  - improve startup build/index time
  - handle stale compiler data better
  - add an option to only build/index on save (not on change)
  - rebuild if Cargo.toml changes

### 0.1.0 - 2017-07-17

* First release
