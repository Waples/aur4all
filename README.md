# aur4all [WIP]
---
A simple AUR scraper (and future aur-helper).
> to be written in Python if possible


## todo
---
### Base
- [ ] Convert this README to asciidoc
- [ ] Decide if I want to write this program in bash or in python..
- [ ] Add to PyPi
- [ ] Add to AUR


### Find
- [ ] Create alpha-python version for scraper


### Install
- [ ] Create alpha-${lang} version for installer


## aur4all
---
### Commands Cheatsheet
* [core]
- -S    Sync internal mirrorlist
- -Q    Query installed PKGs
- -R    Remove PKG(s)
- -U    Update installed PKGs

* [args]
- -s    Search.
- -i    Install.
- -y    Same as *-i* but without confirmation.


### Examples
```
aur4all -Ss *package*
  > Searches the AUR for query
```
