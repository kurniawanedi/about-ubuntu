
# How to install Oh My Zsh (zshell) in Ubuntu
1. Open terminal and type command `sudo apt-get install zsh` 
2. Change default shell from bash to zsh with command `chsh -s /bin/zsh` and `sudo chsh -s /bin/zsh`
3. After that reboot your computer `sudo reboot`

# How to install and add plugin Auto Suggestion and Syntax Highlighting in Zsh
1. Open your terminal `ctrl+alt+t` and clone or download the plugin `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions` for autosuggestions
2. And `https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting` for syntax-highlighting
3. When the downloading process completes, use your text editor and open .zshrc in your home directory, to change it from:<br/>
plugins=(git)<br/>
to<br/>
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
4. Save
5. Next, just close your terminal and reopen it. Done :)

