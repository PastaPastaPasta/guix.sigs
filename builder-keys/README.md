PGP keys
========

This folder contains the public keys of developers / community members that
have produced a guix build.

The keys are mainly used to sign git Guix builds.

You can import the keys into gpg as follows. Also, make sure to fetch the
latest version from the key server to see if any key was revoked in the
meantime.

```sh
gpg --import ./*.pgp
gpg --refresh-keys
```
