# dogecoin-miner-rust

Mine Dogecoin (testnet) blocks

### pre-requisites (ubuntu 20.4 LTS)
- cargo (for compiling rust sources and deps)
- libssl-dev (for openssl-sys dependency)
- pkg-config (for openssl-sys dependency)

```bash
sudo apt install cargo libssl-dev pkg-config
```

### build
```bash
cargo build
```

### configure
create a `.env` file with the following contents:
```
<rpc hostname>
<rpc port>
<rpc user>
<rpc pass>
//no newline at end of file
```

### run
```bash
target/debug/miner-rust
```
