# rust-hello-world

# install Rust: go to https://rustup.rs/
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

Exit your terminal (to reload rust paths)

# crete your cargo hello sample
$ cargo new rust-hello-world
$ cd rust-hello-world

# build your sample
$ cargo build

# execute your sample
$ ./target/debug/hello_world
Hello, world!

# compile andn run in 1 step
$ cargo run
