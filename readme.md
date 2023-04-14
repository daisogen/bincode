# Daisogen's bincode

This is a fork [bincode](https://github.com/bincode-org/bincode) that just implements the feature `rustc-dep-of-std`, so it can be compiled with dependency injection as an actual dependency of `std`, which Daisogen's kernel bindings need for serializing/deserializing messages.
