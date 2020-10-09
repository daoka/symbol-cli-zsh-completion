# symbol-cli-zsh-completion

Completion function for [symbol-cli](https://www.npmjs.com/package/symbol-cli)
capable for v0.22.x (0.10.0.x Milestone)

## Usage

1. Create a directory to save completion file.

```sh
$ mkdir -p ~/.zsh/completion
```

2. Download completion file.

```sh
$ cd ~/.zsh/completion/
$ wget https://raw.githubusercontent.com/daoka/symbol-cli-zsh-completion/master/_symbol-cli
```

3. Edit `.zshrc` to load completion.

```sh
# add
fpath=(~/.zsh/completion $fpath)
autoload -Uz compinit && compinit -i
```

