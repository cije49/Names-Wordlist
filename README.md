# Names-Wordlist
Names-Wordlist is a command line tool that extracts popular first names from Wikipedia dumps to generate wordlist for password cracking.

## Installation

### Wordlists

Pre-generated wordlists can be downloaded directly from the
[release page](https://github.com/crissyfield/names-wordlist/releases/latest).

### Binaries

Pre-built binaries are available from the
[release page](https://github.com/crissyfield/names-wordlist/releases/latest) as well. Simply download, make
executable, and move it to a folder in your `PATH`:

```bash
curl -L https://github.com/crissyfield/names-wordlist/releases/download/v1.0.0/names-wordlist-`uname -s`-`uname -m` >/tmp/names-wordlist
chmod +x /tmp/names-wordlist
sudo mv /tmp/names-wordlist /usr/local/bin/names-wordlist
```
# Usage
Run names-wordlist in the command line like this:
```bash
names-wordlist output.lst
names-wordlist [flags]
Flags:
  -c, --count int              ignore names with less than N occurences (default 1)
  -d, --digits int             append up to N digits after the name (default 4)
  -u, --dump-url string        overwrite default URL for given language
  -h, --help                   help for names-wordlist
  -s, --special-chars string   append special characters from this set (default "!$@_")
  -v, --verbose                write more
      --version                version for names-wordlist
```
# Licence
Copyright (c) 2019 Crissy Field GmbH. Released under the
[MIT License](https://github.com/crissyfield/names-wordlist/blob/master/LICENSE).

Dictionary icon made by [Freepik](https://www.flaticon.com/authors/freepik) from
[www.flaticon.com](https://www.flaticon.com/).
