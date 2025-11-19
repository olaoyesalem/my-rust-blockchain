# Rust Blockchain

A minimal blockchain implementation in Rust featuring:

- Block structure (`src/block.rs`)
- Proof of Work (`src/proof_of_work.rs`)
- Transaction model (`src/transaction.rs`)
- Entry point (`src/main.rs`)

## Development

Build:
```
cargo build
```
Run:
```
cargo run
```
Format & Lint:
```
cargo fmt -- --check
cargo clippy --all-targets --all-features -- -D warnings
```

## Next Steps
- Add networking / P2P layer
- Persist chain state (e.g. sled or sqlite)
- Wallet & key management
- Unit tests for consensus logic

---
Initial commit message: "Initialize Rust blockchain project with basic structure and dependencies"