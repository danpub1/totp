# totp - time-based one time password

[https://danpub1.github.io/totp/totp.html](https://danpub1.github.io/totp/totp.html)

A standalone implementation using web crypto of the Time-based One-Time Password algorithm of RFC-6238, with secret base-32 encoded according to RFC-3548.

# usage

Enter an issuer (e.g. github) and/or an account (e.g. danpub1).  At least one of the two is required for the uri & QR code to be valid.

A random secret is provided at the start.

An otpauth:// uri may be pasted into the secret.

To get a repeatable random secret, enter a string in the secret field and press the '#' (hash) button to replace it with the PBKDF2 hash of the secret, using the issuer and account as the salt.

If the secret is empty and the '#' (hash) button is pressed, a new random secret is provided.