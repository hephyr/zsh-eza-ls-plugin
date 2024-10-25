# zsh-eza-ls-plugin

This zsh plugin enables a number of aliases allowing `eza`, to act as a drop-in
replacement for `ls` and `tree`.

## Installation

### Install eza
Install [`eza`](https://github.com/eza-community/eza).

### Next (Manually)
Next, download this repo into your custom plugins directory. For my installation
using [Oh My Zsh](https://ohmyz.sh/), Clone the repo to
`~/.oh-my-zsh/custom/plugins`.

Finally, add `zsh-eza-plugin` to the plugins array of your zshrc file:

```sh
plugins=(... zsh-eza-ls-plugin)
```

### Next (zplug)

Add `zplug hephyr/zsh-eza-ls-plugin` to your `~/.zshrc` and re-open your terminal session.
