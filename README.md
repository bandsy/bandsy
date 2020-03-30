# bandsy
master repo with git submodules so i dont have to clone 20 different repos one by one

## instructions
when cloning the repo:
- git clone --recursive-submodules (this repo)

or if you forgot to add `--recursive-submodules`:
- git clone (this repo)
- git submodule update --init --recursive
