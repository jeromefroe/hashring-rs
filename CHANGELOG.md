# Changelog

## [v0.3.6](https://github.com/jeromefroe/hashring-rs/tree/0.3.6) - 2024-07-31

- Remove `Clone` trait bound from `IntoIterator` implementation.

## [v0.3.5](https://github.com/jeromefroe/hashring-rs/tree/0.3.5) - 2024-05-24

- Derive `PartialEq` and `Debug` traits on `HashRing`.

## [v0.3.4](https://github.com/jeromefroe/hashring-rs/tree/0.3.4) - 2024-05-18

- Derive `Clone` trait on `HashRing`.

## [v0.3.3](https://github.com/jeromefroe/hashring-rs/tree/0.3.3) - 2023-11-12

- Add `batch_add` method.

## [v0.3.2](https://github.com/jeromefroe/hashring-rs/tree/0.3.2) - 2023-07-19

- Add `get_with_replicas` method.

## [v0.3.1](https://github.com/jeromefroe/hashring-rs/tree/0.3.1) - 2023-07-14

- Add support for iterators.

## [v0.3.0](https://github.com/jeromefroe/hashring-rs/tree/0.3.0) - 2022-03-05

- Get rid of unnecessary transformation of hash value.

## [v0.2.1](https://github.com/jeromefroe/hashring-rs/tree/0.2.1) - 2022-02-28

- Use reference instead of mutable reference in `get` method.

## [v0.2.0](https://github.com/jeromefroe/hashring-rs/tree/0.2.0) - 2020-02-13

- Make hash function configurable and replace MD5 as default with SipHash.

## [v0.1.0](https://github.com/jeromefroe/hashring-rs/tree/0.1.0) - 2016-11-27

- Initial release.
