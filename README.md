# bip39-cli

[![npm version](https://badge.fury.io/js/bip39-cli.svg)](https://badge.fury.io/js/bip39-cli)

bip39-cli is a simple cli tool to create, and verify
[bip39 mnemonics](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki).

## Options

```
  Usage: index [options] [command]

  Options:

    -V, --version                      output the version number
    -h, --help                         output usage information

  Commands:

    generate|gen [options]             generate a new bip39 mnemonic
    validate|val [options] <mnemonic>  validate the given bip39 mnemonic
    accounts|acc [options] <mnemonic>  print accounts with public address and private key
```

## License (ISC)

Copyright (c) 2018 , Asure Foundation <mailto:info@asure.io>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
