# wpa_supplicant.conf

My wpa_supplican.conf for connecting to wpa2 enterprise networks for Universities

To generate a hash for the password (instead of storing the password in plaintext)
Type in the following command:

```shell
$ tr -d '\n' | iconv -t utf16le | openssl md4
```
Then type in your password and press CTRL-D.
Paste the following hash after the 'hash:' so it looks like 'hash:31d6cfe0d16ae931b73c59d7e0c089c0'
