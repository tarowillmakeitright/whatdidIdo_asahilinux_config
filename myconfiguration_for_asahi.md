## Here is packages what I've installed so far for AsahiLinux

- git
```
sudo dnf install -y git-all
```
---

- zsh
```
sudo dnf install zsh
curl -sL --proto-redir -all,https https://raw.githubusercontent.com/zplug/installer/master/installer.zsh | zsh
```
---

- starship
```
curl -sS https://starship.rs/install.sh | sh
```
---

- neovim
```
sudo dnf copr enable agriffis/neovim-nightly
```
replace nvim with vim using alias
```
alias vim="nvim"
```
change the configuration

[Here is my configuration of init.vim](https://github.com/tarowillmakeitright/init.vim)

---
- tmux
```
sudo dnf install tmux
```
