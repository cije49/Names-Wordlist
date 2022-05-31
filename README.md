# Names-Wordlist
Names-Wordlist is a command line tool that extracts popular first names from Wikipedia dumps to generate wordlist for password cracking.

# Installation
```bash
curl -L https://github.com/crissyfield/names-wordlist/releases/download/v1.0.0/names-wordlist-`uname -s`-`uname -m` >/tmp/names-wordlist

chmod +x /tmp/names-wordlist

sudo mv /tmp/names-wordlist /usr/local/bin/names-wordlist
```
# Usage

Run names-wordlist in the command line like this:
```bash
names-wordlist output.lst
```
# Licence
Copyright (c) 2019 Crissy Field GmbH. Released under the
[MIT License](https://github.com/crissyfield/names-wordlist/blob/master/LICENSE).

Dictionary icon made by [Freepik](https://www.flaticon.com/authors/freepik) from
[www.flaticon.com](https://www.flaticon.com/).
