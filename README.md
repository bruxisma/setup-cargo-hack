# Setup Cargo Hack

`setup-cargo-hack` will install the [`cargo-hack`][1] tool and place it on the
system `PATH`. Additionally, the tool will be cached to reduce the overhead of
future runs.

### Inputs

| Variable | Description |
| :-: | :-: |
| `cargo-hack-version` | A semantic version compatible range value to select the version of `cargo-hack` to install |

### Outputs

| Variable | Description |
| :-: | :-: |
| `cache-hit` | Indicates whether an exact match was found for `cargo-hack` |

[1]: https://crates.io/crates/cargo-hack
