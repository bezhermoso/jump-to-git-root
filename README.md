# jump-to-git-root

Simple ZSH utility to jump back to the Git repo's root directory.

Can pierce through submodule: when already at a submodule's root directory, invoking it
will jump you to the parent repo's root directory.

## Setup

Clone this repository:

```sh
git clone https://github.com/bezhermoso/jump-to-git-root.git /usr/local/share

```

Add the `functions` directory of this repo to your `fpath`:

```sh
# Add to fpath
fpath+=('/usr/local/share/jump-to-git-root/functions')

# RECOMMENDED: Assign to a short alias:
alias gr=jump-to-git-root
```
