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
## Example
case: you wanna search a word "into" if contains in a sample.txt or not.
```
cargo run into sample.txt
```
result
> _Finished dev [unoptimized + debuginfo] target(s) in 0.00s_<br>
> _Running `target/debug/minigrep into sample.txt`_<br>
> and did his best to reach them by jumping as high as he could <font color="OrangeRed">into</font> the air.

like this, a line contains "into" found.
