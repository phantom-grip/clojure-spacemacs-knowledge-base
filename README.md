# Clojure Spacemacs knowledge base

## Getting started
- [Spacemacs - From First Install to Clojure programming without manual configuration](https://www.youtube.com/watch?v=Uuwg-069NYE)
- [Installing and getting started with Spacemacs: Emacs tutorial](https://www.youtube.com/watch?v=hCNOB5jjtmc)
- [Spacemacs For Noobs](https://www.youtube.com/watch?v=VBYsa3Kpkz8)
- `SPC+h+SPC` - tutorials for getting started

## Cheetsheets

- [#1](https://gist.github.com/robphoenix/9e4db767ab5c912fb558)
- [vim cheetsheet](https://vim.rtorr.com/)

## General commands
- `SPC-b-h` - go to home
- `SPC-SPC` - emacs commands
- `SPC-SPC-shell` - open shell

## Windows

- `SPC-1`, `SPC-2` - move to window 1/2
- `SPC+w+d` - delete window
- `SPC+w+v` - split vertically

## Browsing

- `SPC+f+t` - open file tree
- `SPC+b+b` - list of open buffers

## Saving

- `:w`
- `SPC+f+s` - save current buffer
- `SPC+f+S` - save all open buffers

## Settings

- `SPC+f+e+d` - to open configuration
- `SPC+h+l`- list of availible layers

## Clojure

- `alt+enter` or `,` - clojure related functions
- `SPC+h+SPC -> clojure` - open clojure layer documentation

## To start with clojure

1. You should have clojure layer installed
2. Go to clojure file
3. Turn on cider (`alt+enter+'`)
4. Evaluate code (`alt+enter+e+b` or `alt+enter+e+e`)

## Working with clojure/clojurescript projects
1. `alt+enter+'` or `alt+enter+"` - connect to Cider (nothing will work without it) 
2. `SPC+p+t` - open tree view
3. `SPC+p+f` - navigate & search project files
4. `alt+enter+g+g` or `alt+enter+g+G` - go to definitions (another files)
5. `/word_your_are_searching` + `n/N` - search in this file

## List of thing you should be able to do to be productive

1. Add new text
2. Copy/paste/delete
3. Rename folders/files/namespaces/variables
4. Add folders/files/libraries/imports
5. Search (and replace) through project/folder/file

## .gitignore for autosave files
```
\#*\#
.\#*
```

