# byteview

Fast line/byte counter written in Rust

## How to use

```bash
./target/release/byteview src/*.rs
cat README.md | ./target/release/byteview
```

## Install

```bash
cargo build --release
```

## What it does

- Reads stdin or multiple files
- Parallel over files with std threads
- Counts lines, words and bytes like wc
- Zero dependencies outside std

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── Cargo.toml
```

## Development

```bash
cargo build
cargo clippy -- -D warnings
```

## 说明

个人练习项目, 谨慎用于生产环境。
