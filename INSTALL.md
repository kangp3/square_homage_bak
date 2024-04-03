# Apt Installs
```bash
$ sudo apt-get install -y \
    libssl-dev \          # Dependency of simple-http-server
    libfontconfig-dev \   # Dependency of something in the Cargo.toml
    clang \               # Dependency of something in the Cargo.toml
    pkg-config \          # Dependency of something in the Cargo.toml
    cmake                 # Dependency of something in the Cargo.toml
```

# Build commands
```bash
$ RUSTFLAGS=--cfg=web_sys_unstable_apis wasm-pack build --target web
```
Unclear if `RUSTFLAGS` is necessary

# Install simple-http-server
```bash
$ cargo install simple-http-server
```

# Run commands
```bash
$ simple-http-server
```

