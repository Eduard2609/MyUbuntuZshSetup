# MyUbuntuZshSetup

1. Install Oh My Zsh: 
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
2. Install Powerlevel10k Theme
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
3. Install Auto Suggestions Plugin 
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
4. Install Syntax Highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
echo "source ${(q-)PWD}/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
5. Install Micro
sudo curl https://getmic.ro | bash
6. Open your .zshrc file with Micro
./micro ~/.zshrc
7. Set theme to (includes the quotes)
"powerlevel10k/powerlevel10k"
8. Activate Enable Correction
#ENABLE_CORRECTION="true"
to this
ENABLE_CORRECTION="true"
9. Add our plugins
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
10. Save by pressing CNTRL + Q and then type Y to save
11. Download Nerd Fonts
https://www.nerdfonts.com
