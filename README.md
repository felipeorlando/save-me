# save-me
> Save anything 🔐

[![Codeship Status for bukinoshita/save-me](https://app.codeship.com/projects/2dd81180-dd21-0134-15ed-7ad4e00365e1/status?branch=master)](https://app.codeship.com/projects/204513)
[![Build Status](https://travis-ci.org/bukinoshita/save-me.svg?branch=master)](https://travis-ci.org/bukinoshita/save-me)
[![GitHub release](https://img.shields.io/github/release/bukinoshita/save-me.svg)](https://www.npmjs.com/package/save-me)
[![license](https://img.shields.io/github/license/bukinoshita/save-me.svg)](https://raw.githubusercontent.com/bukinoshita/save-me/master/LICENSE)

## Install
```bash
$ npm install -g save-me
```
_Linux users will probably have to install xsel to use copy to clipboard option: `sudo apt install xsel`_

## Usage
```bash
$ save-me --help

  Usage:
    $ save-me          Save an item
    $ save-me <item>   Search and get an item

  Example:
    $ save-me
    $ save-me <item> --copy
    $ save-me -l
    $ save-me -r <item>

  Options:
    -r, --remove       Remove item selected
    -l, --list         List all saved items

    -h, --help         Show help options
    -v, --version      Show version
    -c, --copy         Copy item to clipboard
```

## How it works
<img src="https://cldup.com/hAKpM7LUpJ.gif"/><br/>

## Related
[caesar-encrypt](https://github.com/bukinoshita/caesar) — :closed_lock_with_key: One of the simplest forms of encryption

## License
[MIT](https://github.com/bukinoshita/save-me/blob/master/LICENSE) &copy; Bu Kinoshita
