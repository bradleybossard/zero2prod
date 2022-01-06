
### Scaffold new project
```
# create a new project "zero2prod"
cargo new zero2prod
```

### Run tests
```
cargo test
```

### Code coverage
```
cargo install cargo-tarpaulin
cargo tarpaulin --ignore-tests
```

### Linting
```
rustup component add clippy

cargo clippy

# For CI/CD
cargo clippy -- -D warnings
```

### Formatting
```
rustup component add rustfmt

cargo fmt

# For CI/CD
cargo fmt -- --check
```

### Security Vulnerabilities
```
cargo install cargo-audit

cargo audit
```

### Generate docs
```
cargo doc
```

```
```

```
```

```
```

```
```

```
```

## TODOs

[GitHub Actions - Rust setup](https://gist.github.com/LukeMathWalker/5ae1107432ce283310c3e601fac915f3)
