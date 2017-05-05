# Altium on git

Boilerplate repository to use Altium Designer on git.


# Instruction

This repository is a well-tested starting point to use Altium Designer in a mixed Unix-Windows environment.

If you run Altium in a VM, keeping the files on Linux, you need this.

```shell
git clone git@github.com:fermiumlabs/altium-on-git.git
git submodule update --init --recursive
```

When you save a new schematic file, save it in ASCII. This will keep the repository size low.
