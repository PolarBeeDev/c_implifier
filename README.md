A library that makes coding in Rust just a little bit simpler. 

To set this up:
-In the dependencies section of the Cargo.toml file, paste the following line in:
c_implifier = {git = "https://github.com/PolarBeeDev/c_implifier", branch = "master"}
-Then, in your .rs file, you can write: use c_implifier::[the gen of the commands]
-Now, you can call the commands

Example:

Cargo.toml:
[dependencies]
c_implifier = {git = "https://github.com/PolarBeeDev/c_implifier", branch = "master"}

main.rs:
use c_implifier::gen1cmds::*;

fn main() {
    print!("Hello, world!");
    endl!();
}
