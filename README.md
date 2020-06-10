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
use square_calculator;
fn main() {
    let (firstsq,secondsq) = square_calculator::square (10,12);
    println!("First square is {}",firstsq);
    println!("Second square is {}",secondsq);
}
```
following will also work:
```
use square_calculator::square;
fn main() {
    let (firstsq,secondsq) = square (10,12);
    println!("First square is {}",firstsq);
    println!("Second square is {}",secondsq);
    }
```

now `cargo run` for results
