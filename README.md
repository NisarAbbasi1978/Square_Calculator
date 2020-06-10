# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`square_calculator = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "square_calculator"
version = "0.1.0"
authors = ["N A Abbasi <nisar_abbasi@yahoo.com>"]
edition = "2018"

[dependencies]
square_calculator = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use firstwelcome;
fn main() {
    println!("Hello, world!");
    firstwelcome::hello();
}
```
following will also work:
```
use firstwelcome::hello;
fn main() {
    println!("Hello, world!");
    hello();
    }
```

now `cargo run` for results
