# jump-to-git-root

Simple shell utility to jump back to the Git repo's root directory.

Can pierce through submodule: when already at a submodule's root directory, invoking it
will jump you to the parent repo's root directory.

## Setup

Clone this repository:

```sh
git clone git@github.com:bezhermoso/jump-to-git-root.git /usr/local/share

```

 Then in your `.zshrc` file:

```sh
# Import the `jump-to-git-root` function:
source "/usr/local/share/jump-to-git-root/init.sh"

# RECOMMENDED: Assign to a short alias:
alias gr=jump-to-git-root
```
