# Stream ciphers

Sodium includes implementations of XSalsa20/20 and ChaCha20/20 stream ciphers.

These functions are stream ciphers. They do not provide authenticated encryption.

They can be used to generate pseudo-random data from a key, or as building blocks for implementing custom constructions, but they are not alternatives to `crypto_secretbox_*()`.
