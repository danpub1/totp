# totp - time-based one time password

[https://danpub1.github.io/totp/totp.html](https://danpub1.github.io/totp/totp.html)

A standalone implementation using web crypto of the Time-based One-Time Password algorithm of RFC-6238, with secret base-32 encoded according to RFC-3548.

An otpauth:// uri may be pasted into the secret.

The '#' (hash) button replaces the secret with the PBKDF2 hash of the secret