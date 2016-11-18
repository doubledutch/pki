# pki

The files included in this repo are the CA certificates used for the internal
PKI at [DoubleDutch](https://doubledutch.me/). These certificates are probably
of no use to the external public, but are here to make it easy for anyone to
download.

The `.crt` files are the certificates themselves, while the `.txt` files are the
output of `openssl x509 -text -in <file>.crt -out <file>.txt`.
