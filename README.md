# Noxium 

Fork of [Nox](https://github.com/kbrsh/nox) by [Kabir Shah](https://kabir.sh)

![Noxium](https://raw.githubusercontent.com/mietzen/noxium/master/img/noxium.png)

### Install 

Prerequisite: [zsh](http://www.zsh.org/) and [Oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh#basic-installation) are installed


#### Minimal

1. Download the theme in your oh-my-zsh's themes directory:

    ```zsh
    wget -O ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/noxium.zsh-theme https://raw.githubusercontent.com/mietzen/noxium/master/noxium.zsh-theme
    ```

2. Activate the theme in `~/.zshrc`:
    ```zsh
     ZSH_THEME="noxium"
    ```
#### Full (Like in the picture)

1. Install [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
    ```zsh
    git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
    ```
   and [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)    
    ```zsh
    git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
    ```    

2. [Install Base16 Shell](https://github.com/chriskempson/base16-shell)
    ```zsh
    git clone https://github.com/chriskempson/base16-shell.git ~/.config/base16-shell
    ```
    
3. Download the theme in your oh-my-zsh's themes directory:

    ```zsh
    wget -O ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/noxium.zsh-theme https://raw.githubusercontent.com/mietzen/noxium/master/noxium.zsh-theme
    ```

4. Download the minimal `.zshrc` from the Repo:

    ```zsh
    mv ~/.zshrc ~/.zshrc.bak && wget -O ~/.zshrc https://raw.githubusercontent.com/mietzen/noxium/master/.zshrc
    ```

5. Open a new terminal and pick a Base16 color theme:
    ```zsh
    base16_flat
    ```

### License

Licensed under the [MIT License](https://raw.githubusercontent.com/mietzen/noxium/master/LICENSE) by [ngerke](https://github.com/ngerke)
