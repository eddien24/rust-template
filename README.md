# Eddie's Rust Template
Minimal template for Rust projects to be used with Nix developement environments.

### Requirements
- Flakes-enabled installation of [Nix](https://nixos.org/download/)
- [cargo-generate](https://crates.io/crates/cargo-generate)

### Installation
```shell
cargo generate eddien24/rust-template
```

### Usage
- `nix develop`: start developement shell. Will create `flake.lock` the first time it is run.
- `nix build`: build project
- `nix run`: run project

Modified from [MordragT/nix-templates](https://github.com/MordragT/nix-templates/tree/master/rust-stable).
