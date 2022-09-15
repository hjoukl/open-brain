# open-brain
Assorted knowledge, tips &amp; tricks

## vim / neovim
Use `:verbose set ...` to show where a certain option has been set, e.g. by a plugin.

Example:
```
:verbose set conceallevel

NORMAL  1:[No Name]                               unix | utf-8 | no ft  100%    0:1  
  conceallevel=2
        Last set from ~/.vim/bundle/indentLine/after/plugin/indentLine.vim line 105
Press ENTER or type command to continue
```
