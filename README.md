[![PyPI version](https://badge.fury.io/py/song.svg)](https://badge.fury.io/py/song)
[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/ankitmathur3193/song-cli/blob/master/LICENSE)
# QUIET SONG DOWNLOADER #

Forked from `https://github.com/ankitmathur3193/song-cli`

## Installing ##

You **might be screwed** without `ssh`, `zsh` and `pip`.

```
echo 'function s(){ song "$@" > /dev/null 2>&1  &; }' >> ~/.zshrc
zsh source ~/.zshrc

mkdir ~/src; cd ~/src;
git clone git@github.com:louisgv/song-cli.git
cd song-cli

pip install -e .
```

## Usage: ##
```
song [ song_name ]
```

## Disclaimer ##

Downloading copyrighted material may be illegal in your country. JUST DO NOT DO IT.
Use at your own risk.
