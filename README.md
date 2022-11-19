https://www.zero2prod.com/

## Requirements

* Rust
* Docker
* SQLx CLI
  `cargo install --version="~0.6" sqlx-cli --no-default-features --features rustls,postgres`

## Usage

```bash
./scripts/init_db.sh
cargo watch -x check -x test -x run
```