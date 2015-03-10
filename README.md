# vim-cheat

Prints vim commands to terminal ... so you can `grep` them.

## Installation

```
$ cd ~/src
$ git clone https://github.com/otternq/vim-cheat.git
$ cd ./vim-cheat
$ chmod +x ./bin/vim-cheat
```

Add export PATH="/path/to/vim-cheat/bin:$PATH" to your .rc file (.zshrc | .bashrc)

## Usage

```
$ vim-cheat
```

will print out all commands

```
$ vim-cheat | grep 'delete'
s   delete character and substitute text
S   delete line and substitute text (same as cc)
xp  transpose two letters (delete and paste)
dd  delete (cut) a line
2dd delete (cut) 2 lines
dw  delete (cut) word
D   delete (cut) to the end of the line
d$  delete (cut) to the end of the line
x   delete (cut) character
d   delete marked text
:bd delete a buffer (close a file)
$ 
```

will print out commands handling deletions

## To-Do

- [ ] use yaml - like [rtorr/vim-cheat-sheet/_config.yml](https://github.com/rtorr/vim-cheat-sheet/blob/master/_config.yml) - to provide searching

## Stolen from
The commands are taken directly from [rtorr/vim-cheat-sheet](https://github.com/rtorr/vim-cheat-sheet) ([website](http://vim.rtorr.com/)), I just wanted them on my terminal.
