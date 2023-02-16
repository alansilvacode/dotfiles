# dotfiles

Um padrão do sistemas unix hoje em dia é guardar as mais diversas configurações em arquivos iniciados com ponto: .gitignore, .bash, .bashrc, .profile, .m2, .zsh e por ai vai.

## Configurando o git

```sh
  cp examples/.gitconfig ./.gitconfig
  ln -s ~/.dotfiles/.gitconfig ~/.gitconfig
```

## Comandos para Seguir

```sh
  ln -s ~/.dotfiles/.screenrc ~/.screenrc
  ln -s ~/.dotfiles/.dmrc ~/.dmrc
  ln -s ~/.dotfiles/.face ~/.face
  ln -s ~/.dotfiles/.genentriesrc ~/.genentriesrc
  ln -s ~/.dotfiles/.yarnrc ~/.yarnrc
  ln -s ~/.dotfiles/.conkyrc ~/.conkyrc
  ln -s ~/.dotfiles/zsh/.zshrc ~/.zshrc
  ln -s ~/.dotfiles/bash/.bashrc ~/.bashr
  ln -s ~/.dotfiles/bash/.bash_profile ~/.bash_profile
  ln -s ~/.dotfiles/bash/.bash_logout ~/.bash_logout
  ln -s ~/.dotfiles/alacritty/alacritty.yml ~/.config/alacritty/alacritty.yml
  ln -s ~/.dotfiles/polybar/.config ~/.config/polybar/config
```

![Image Kang](./images/readme.jpg)
