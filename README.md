This is too much simple grep tool by Rust.
## Install
```
git clone https://github.com/shunak/minigrep.git
```
## How to use
```
cd minigrep
```
```
cargo run "word you wanna find" "text you wanna search"
```
example
```
cargo run into sample.txt
```
result
>Finished dev [unoptimized + debuginfo] target(s) in 0.00s
> Running `target/debug/minigrep into sample.txt`
> and did his best to reach them by jumping as high as he could into the air.

like this, a line contains "into" found.
