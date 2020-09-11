[![CircleCI](https://circleci.com/gh/shunak/minigrep.svg?style=svg&circle-token=53341d4939909cd2847be25c1332a52794d5ba27)](https://app.circleci.com/pipelines/github/shunak/typescript-sandbox)<br>

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
cargo run "word you wanna search" "text you wanna search in"
```
## Example
case: you wanna search a word "into" if contains in a sample.txt or not.
```
cargo run into sample.txt
```
### result
> _Finished dev [unoptimized + debuginfo] target(s) in 0.00s_<br>
> _Running `target/debug/minigrep into sample.txt`_<br>
> and did his best to reach them by jumping as high as he could <span style="color: red;">into</span> the air.

like this, a line contains "into" found.
