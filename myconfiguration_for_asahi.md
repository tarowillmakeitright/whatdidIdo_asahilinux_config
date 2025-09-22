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
[My PlugIn for tmux](https://github.com/tarowillmakeitright/tmuxconf)

[Here is example what I've refrenced](https://github.com/tmux-plugins/tpm)

- wikiman

This is useful for additional deatails of commands when you want to look up a coomand like a "man" command does.

[Here is github](https://github.com/filiparag/wikiman)

---

- tldr
  
When you want to look up a command and would like to understand the command immidiately, it is very useful.

[TLDR github](https://github.com/tldr-pages/tldr)
   
