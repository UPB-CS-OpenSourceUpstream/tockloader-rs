# ![TockLoader](http://www.tockos.org/assets/img/tockloader.svg#a "Tockloader Logo")

This is a work-in-progress port to Rust for Tock Loader.

Please use the original Python version of [TockLoader](https://www.github.com/tock/tockloader).

## Roadmap

This is a non exhaustive list of functionalities that should be 
implemented to make TockLoader usable.

  - [x] Setup the directory structure
  - [x] Implement the command line arguments parser
  - [ ] Implement the serial port listener
  - [ ] Implement the tockloader serial protocol
  - [ ] Implement the TBF Parser

## Install Prerequisites

### Linux

```bash
sudo apt update
sudo apt install libudev-dev
```

### WSL

```bash
sudo apt update
sudo apt install libudev-dev pkg-config
```

License
-------

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or
  http://opensource.org/licenses/MIT)

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
