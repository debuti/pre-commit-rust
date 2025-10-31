# Rust hooks for pre-commit

[Rust](https://www.rust-lang.org) tools package for [pre-commit](https://pre-commit.com).

## Using Rust tools with pre-commit

```yaml
  - repo: https://github.com/debuti/pre-commit-rust
    rev: master
    hooks:
      - id: fmt
      - id: cargo-check
      - id: clippy
```
