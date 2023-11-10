
** Install Rust
https://www.rust-lang.org/tools/install

** Using rustup
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

Welconme info:
    package manager: Cargo
    Rustup home directory(RUSTUP_HOME): /Users/jzwang/.rustup
    Cargo home directory(CARGO_HOME): /Users/jzwang/.cargo    
    ~/.cargo/bin
        cargo
	rustc
	rustup

    This path(~/.cargo/bin) will then be added to your PATH environment
variable by modifying the profile files located at:
        /Users/jzwang/.profile
        /Users/jzwang/.zshenv
	
    Current installation options:
          default host triple: x86_64-apple-darwin
            default toolchain: stable (default)
                      profile: default
         modify PATH variable: yes

1) Proceed with installation (default)
2) Customize installation
3) Cancel installation
>
输入: 回车

    info: profile set to 'default'
    info: default host triple is x86_64-apple-darwin
    info: syncing channel updates for 'stable-x86_64-apple-darwin'
    info: latest update on 2023-10-05, rust version 1.73.0 (cc66ad468 2023-10-03)
    info: downloading component 'cargo'
    info: downloading component 'clippy'
    info: downloading component 'rust-docs'
            13.8 MiB /  13.8 MiB (100 %)   8.8 MiB/s in  1s ETA:  0s
    info: downloading component 'rust-std'
            23.3 MiB /  23.3 MiB (100 %)   8.9 MiB/s in  2s ETA:  0s
    info: downloading component 'rustc'
            56.1 MiB /  56.1 MiB (100 %)   7.3 MiB/s in  7s ETA:  0s
    info: downloading component 'rustfmt'
    info: installing component 'cargo'
    info: installing component 'clippy'
    info: installing component 'rust-docs'
            13.8 MiB /  13.8 MiB (100 %)   2.0 MiB/s in  5s ETA:  0s
    info: installing component 'rust-std'
            23.3 MiB /  23.3 MiB (100 %)  10.7 MiB/s in  2s ETA:  0s
    info: installing component 'rustc'
            56.1 MiB /  56.1 MiB (100 %)  12.3 MiB/s in  4s ETA:  0s
    info: installing component 'rustfmt'
    info: default toolchain set to 'stable-x86_64-apple-darwin'
    
    stable-x86_64-apple-darwin installed - rustc 1.73.0 (cc66ad468 2023-10-03)

    Rust is installed now. Great!

    To get started you may need to restart your current shell.
    This would reload your PATH environment variable to include
    Cargo's bin directory ($HOME/.cargo/bin).

    To configure your current shell, run:
    source "$HOME/.cargo/env"

** rustc --version
rustc 1.73.0 (cc66ad468 2023-10-03)

** rustup documentation
https://rust-lang.github.io/rustup/

** uninstall
    rustup self uninstall

** cargo
    cargo --verision
    cargo build
    cargo run
    cargo test
    cargo doc
    cargo publish

    the cargo book: https://doc.rust-lang.org/cargo/index.html

** other tools (emacs)

