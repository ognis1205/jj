# AGENTS.md

## 1. Current Goal
- [ ] Understand how Jujutsu handles CLI command routing and automatic snapshots.

## 2. Agent Constraints (Do's and Don'ts)
- **DO NOT** run interactive TUI commands or `jj edit`. It will hang the session.
- **DO** use `cargo check` to verify the Rust code layers.
- **STOP AND ASK** before modifying any file or trying to write a test.

## 3. Active Exploration Notes
* This is a Rust-based multi-crate repository.
