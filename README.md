### my zshrc config

1. install iterm2
2. open iterm2, `⌘ +`, create new profile, download any preset you love from [here]([url](https://iterm2colorschemes.com/)https://iterm2colorschemes.com/). save the file as `.itermcolors` and load preset
<img width="614" alt="Screenshot 2024-01-19 at 3 15 14 PM" src="https://github.com/btjm123/zshrc-config/assets/19306879/fc02df2d-a299-4c7a-829d-e9394ed5534d">

3. again, navigate to text tab, download any nerd font [ttf]([url](https://www.jetbrains.com/lp/mono/)https://www.jetbrains.com/lp/mono/) or [this]([url](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf)https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf). import under font section
<img width="603" alt="Screenshot 2024-01-19 at 3 17 43 PM" src="https://github.com/btjm123/zshrc-config/assets/19306879/93927470-cf44-4c6f-9a42-1a7d4548c780">

4. use homebrew to install zsh
```
# install some zsh plugins via homebrew
brew install zsh zsh-completions zsh-syntax-highlighting

# install oh my zsh
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# some additional themes and fish
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k
git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

5. `⌘ +` -> profile -> text -> switch on natural text editing. also rmb to set back to vertical bar + blinking cursor

some additional commands i had to run
```
sudo chown -R $(whoami) /usr/local/share/zsh /usr/local/share/zsh/site-functions
chmod u+w /usr/local/share/zsh /usr/local/share/zsh/site-functions
```

[ref]([url](https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961)https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961)
