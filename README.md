## Code Checkout

This repository uses Git submodule functionality. To check out this repo and its submodule recursively, run

```bash
git clone --recurse-submodules git@github.com:gautamdhameja/substrate-enterprise-sample.git <target>
cd <target>
git pull --recurse-submodules
```

If you have been working on this repo, the first time switching to a branch with git-submodule, run:

```bash
# you have done this, checking out out first time the branch with sub-modules
git checkout <branch>
git submodule update --init --recursive
# Afterwards, you can just:
# git pull --recurse-submodules
```