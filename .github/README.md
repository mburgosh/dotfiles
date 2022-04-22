# dotfiles

## Usage

```
git clone --bare https://github.com/mburgosh/dotfiles.git $HOME/.dotfiles
```

This will create a bare repo, to actually checkout the code it in the home directory you call

```
git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout
```

## Update

By cloning the repo and using fish this will add the alias `dotfiles` to `/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME` so you can use as a replacement for `git` to operate on that repo.

```
dotfiles pull

```

# New machine pre-setup


1. Install homebrew (link)[https://brew.sh/]

2. Install fish

```
brew install fish
```