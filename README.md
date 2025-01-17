# RustCrypto: Key Derivation Functions

[![Project Chat][chat-image]][chat-link] [![dependency status][deps-image]][deps-link] ![Apache2/MIT licensed][license-image]

Collection of [Key Derivation Functions][KDF] (KDF) written in pure Rust.

## Supported Algorithms

| Algorithm | Crate  | Crates.io     | Documentation | MSRV |
|-----------|--------|:-------------:|:-------------:|:----:|
| [HKDF]    | [`hkdf`] | [![crates.io](https://img.shields.io/crates/v/hkdf.svg)](https://crates.io/crates/hkdf) | [![Documentation](https://docs.rs/hkdf/badge.svg)](https://docs.rs/hkdf) | ![MSRV 1.41][msrv-1.41] |

*NOTE: for password-based KDFs (e.g. Argon2, PBKDF2, scrypt), please see [RustCrypto/password-hashes]*

### Minimum Supported Rust Version (MSRV) Policy

MSRV bumps are considered breaking changes and will be performed only with minor version bump.

## License

All crates licensed under either of

 * [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
 * [MIT license](http://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

[//]: # (badges)

[chat-image]: https://img.shields.io/badge/zulip-join_chat-blue.svg
[chat-link]: https://rustcrypto.zulipchat.com/#narrow/stream/260043-KDFs
[license-image]: https://img.shields.io/badge/license-Apache2.0/MIT-blue.svg
[deps-image]: https://deps.rs/repo/github/RustCrypto/KDFs/status.svg
[deps-link]: https://deps.rs/repo/github/RustCrypto/KDFs
[msrv-1.41]: https://img.shields.io/badge/rustc-1.41.0+-blue.svg

[//]: # (crates)

[`hkdf`]: ./hkdf

[//]: # (algorithms)

[KDF]: https://en.wikipedia.org/wiki/Key_derivation_function
[HKDF]: https://en.wikipedia.org/wiki/HKDF
[RustCrypto/password-hashes]: https://github.com/RustCrypto/password-hashes
