# gnupg public key

This repo contains the GnuPG public key associated with this account and information on ways to add it to your keychain.

## Key details
``` bash
& gpg --list-keys --keyid-format LONG 29140722+chdd-ltd@users.noreply.github.com
rsa4096 2023-01-02 [SC]
      CA8C79A7F676456F79D0FB4055B53CBDA8B87A79
uid           [ultimate] chdd-ltd <29140722+chdd-ltd@users.noreply.github.com>
sub   rsa4096 2023-01-02 [E]
```

## Keyserver
``` bash
$ gpg --keyserver http://keyserver.ubuntu.com --search-keys CA8C79A7F676456F79D0FB4055B53CBDA8B87A79

$ gpg --keyserver http://keyserver.ubuntu.com --receive-keys CA8C79A7F676456F79D0FB4055B53CBDA8B87A79
```

## Download & import key
``` bash
$ wget https://raw.githubusercontent.com/chdd-ltd/gngpg_public_key/main/29140722+chdd-ltd@users.noreply.github.com_public.asc

$ gpg --import 29140722+chdd-ltd@users.noreply.github.com_public.asc

$ gpg --list-keys --keyid-format LONG 29140722+chdd-ltd@users.noreply.github.com
```

## Cut & paste key
``` bash
-----BEGIN PGP PUBLIC KEY BLOCK-----

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
NYsfHK5fKxXMhMvTaQ0afdnrRnX8
=zgM/
-----END PGP PUBLIC KEY BLOCK-----
```
