### Usage

- Enable "timer" feature in Cargo.toml
- Specify the feature before module (#[cfg(feature="timer")])
Snippet for using the macros:
```console
let _time = timer_start!(|| "Benchmarking my function");
<...>
timer_end!(_time);
```
